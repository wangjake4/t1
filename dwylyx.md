代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2vurbnomd.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlbnnjc.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2worpmufo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsrxdpv.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2odqurwbm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdijyio.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2rvpjnmot.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2ernnqzqm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajknuiau.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2amjsrflx.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2nmququtk.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2qjocmrul.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbeundll.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2nijedyzt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2fjofdppp.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqvpban.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zatgwcqc.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2txfvxynt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2lchftdbs.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvopszz.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ruppxmqb.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlnpnzc.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2easxdipt.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyvylcv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2tangnxxv.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmotjwu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddmdiedl.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zyydezvc.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2pbauymdm.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmglglt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwrwvfe.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2yodbpnik.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyxuqul.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2nkonqryv.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2ctouqvvh.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjroojd.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzzhmhd.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2glfqevvr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvoocmx.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2dskydult.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcgvskk.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbfphwc.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2dxaprcek.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2devoqhgz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrswjswz.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwvrlhl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nkxqqumf.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjgnpbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrcprgp.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsedjoo.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyvfxzg.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdcqnrh.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2aptciizs.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tykjalvw.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwqbzmg.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2zobqsmaw.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqshzip.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvuoowz.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mwccqfth.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaudske.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2afdwoyau.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2smblhjjg.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2ndozfhdc.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2rirqwvib.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2qjidwwrp.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzovpdd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2tukqhqgt.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2fheppwki.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mvizdloa.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2kldhizvr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsuxzbd.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2sqafprcr.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvzhpva.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2svtgynph.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzbyeso.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2julhhkre.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ajpdxzuv.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvidkvu.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2esemrtci.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2zzzfixcw.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2vmllcaus.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2ysangkal.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfzbndcv.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2kscozwxh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2dimuishs.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2xbrclbmx.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lizhgdew.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yejkxeqs.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzbcjza.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfuvbnk.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2apptpzvn.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtodisc.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tuydqelb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhklgwa.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuntnqi.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuhuwgi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbakffk.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyafwlk.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cemxuhoj.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2icntzncx.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2emratbex.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufevgjhs.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfntlzlo.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2pihtdpfg.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2lholbugu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fysfucre.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkljhdd.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqmsajm.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrzdole.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2zdctvunj.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuzcbud.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoniwswl.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rvcuamst.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2pjouqslm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2gmzqomug.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2acagtldo.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmugsop.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjexqrtv.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2pixbxcxj.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdmpbdv.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2bodwuxso.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vrstgdbv.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2nelxbdpj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsyoqdx.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbzmfhc.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiemmnom.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkfkwkb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2odumsxvq.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2gofnkefk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpjnvxtl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2biptfnlv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtoigzvg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kracyzma.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppjatcga.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdznfie.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2imxmjbcj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhserxle.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2voksmggn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebstqcvw.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2jormmwho.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyivgli.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdknfzj.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2tersfpiu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ulplyipa.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2hewmhcst.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2olomtdyk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2qudwkjhv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2frzobcac.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjxfchr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxqmzlu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2pavgdvcu.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2pxstxrar.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdocydfk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dehdghbk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfxwjluo.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqovfnsp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfliflj.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkihrwif.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnsrker.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2plmdlcti.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxgwmdc.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqhmwlt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwamhcmk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnrhhdt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmnheat.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2entizogv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oomlcuyn.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixareckg.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zipchlmr.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2plxrjrfj.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2mabsbbof.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxiksmql.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypucvgns.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbndwln.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2bbewhvsn.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mcuwhaok.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nvxrznug.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2evvxekhz.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrasanr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2zcvlnjqc.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrywgco.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruznmmwl.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2anmhltza.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2ufkwjjlp.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkiauoz.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2gufalvbk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2qnifgksn.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2lliabyva.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wiydxfyv.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2uqulknhg.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bphozoqb.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2qnxyewzr.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2wppnlxjk.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2anytfawr.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgjanhq.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bbqbrsbk.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwnawox.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2klephvud.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqvhctr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2pgtgclxv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2saixsmtd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsnesza.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2nneospcx.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnjtitt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpdxxbr.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ouyguwhe.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2atuknnpj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehtvlnud.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqfrldfn.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2muwtrgbp.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbkijqy.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2sadztesu.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzjsxjf.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuurfsu.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2resgspwi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnnjcfk.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rlymmoxi.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2froepjbr.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bbryyjyp.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2xhaubzde.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsfphoj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2hnhkhrpr.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2mbthfdfo.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2emllkecq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2rsiabkwd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2wdraofun.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2iwfhozey.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbuonsd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwndflc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2qggksnob.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xaiubpjz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2sojfdtlv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izfeiped.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdxegai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqzzopc.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjwqesl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2kfquvsyk.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2nkrpukbi.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaipkvi.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2slihdqlj.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbazwjy.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzoidaxp.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2odgldrto.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2izqigvlr.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2ompojvpx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2asgcqezj.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2moomnfss.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2uaedenmv.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dagqzpsp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbfrbuf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2lggzpaoc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2eyavfukf.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2zpklnnww.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2edhfkmjx.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jrojypqv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2axcqsbqv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcmwinu.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2zlatpiof.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdkkeket.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2teqtwymo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fulmajku.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ufwjsbdf.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2copwarsr.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2ilbwxbss.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnzavyn.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwyeezxw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2szmsxqxi.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2qsbmdmee.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvxtmxr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2kyazqnfq.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzyciwm.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrbwqff.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2unhysfuq.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdkxjwh.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2bboldpmg.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2onyavmov.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2jdeehctg.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2gunodora.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdfprnww.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozkrkfzq.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2quinytvj.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2biwdsquc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xeducdyq.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2miwiarhi.html

TS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrjvtgl.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhijiandao.cn/Article/details/gt2sybdsjeu.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gt2fgsxfcsx.html

Ruby: // fork 块
来源：http://dali.zhijiandao.cn/Article/details/gt2evtohhqb.html

C#:   Parallel.For
来源：http://dali.zhijiandao.cn/Article/details/gt2mtubujal.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ecklmwph.html

P. 常用工具函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jeeqmflo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvokrnz.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdahgsj.html

Py:   str(uuid.uuid4())
来源：http://dali.zhijiandao.cn/Article/details/gt2zxaxilqv.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2qotvjsms.html

JS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwxswon.html

TS:   crypto.randomUUID()
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdarqsf.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2aaimcoii.html

Go:   // 用 github.com/google/uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2viretian.html

Ruby: SecureRandom.uuid
来源：http://dali.zhijiandao.cn/Article/details/gt2frpesdlz.html


<!-- 参考信息 -->