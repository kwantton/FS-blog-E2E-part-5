 PART 5 E2E TESTING done. Had to create a separate repo, since

(a) if I had moved this to frontend, "npm test" in Front would've complained about 2 test files failing
(these E2E tests) because wrong folder structure (i.e.; it would recognize the E2E tests even though
in front, you're only supposed to run the Front tests (npm test))
(b) I can't have a single git repo with Front and Back, or the back will be locked out in github. Tried this
out earlier at one point, regretted immensely, couldn't solve that c:. SO: the frontend of part 5 will be at another
repo: https://github.com/kwantton/FS-blog-frontend-part-5.
