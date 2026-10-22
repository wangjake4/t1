代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnvurwm.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhijiandao.cn/Article/details/gt2mtghwwso.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2slfopibf.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhijiandao.cn/Article/details/gt2miwsbgmg.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2uupjccwv.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzlnnnm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgisgdu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.zhijiandao.cn/Article/details/gt2napxtwhw.html

[L03] 设置自定义请求头
来源：http://dali.zhijiandao.cn/Article/details/gt2difglwef.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdtdcbb.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkiofuso.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2geoutojl.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpdaxxo.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvbdkma.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvyuqfaq.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.zhijiandao.cn/Article/details/gt2skaqlnra.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.zhijiandao.cn/Article/details/gt2riqeyacu.html

[L04] 设置超时
来源：http://dali.zhijiandao.cn/Article/details/gt2xduvqueh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhijiandao.cn/Article/details/gt2plucbmbp.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2oxsxxlfu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2lcaabmpt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2wqzqajde.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhijiandao.cn/Article/details/gt2jukcolip.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlfntpw.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhijiandao.cn/Article/details/gt2aekyvbfv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxvwodq.html

[L05] 上传文件（multipart）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqsgvhd.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gt2urndctdt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgtyfos.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtwbmqe.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gt2nqseodnr.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhijiandao.cn/Article/details/gt2ljnqkbpn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bskopiah.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2jaqprcqr.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2huuswyit.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2vworuzuf.html

Py:   resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjbkght.html

PHP:  json_decode($body, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdyylbur.html

JS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrgiqyc.html

TS:   await resp.json()
来源：http://dali.zhijiandao.cn/Article/details/gt2itqbzwrr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbuppug.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngeqsbez.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhijiandao.cn/Article/details/gt2bovbghhw.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxmxhvrx.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2uoolnubj.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2fobwqqpl.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppoexilw.html

JS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfpyaxn.html

TS:   resp.ok;  resp.status
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzowczj.html

Java: resp.statusCode()
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcjqjxh.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2xgakntdn.html

Ruby: resp.code.to_i
来源：http://dali.zhijiandao.cn/Article/details/gt2oiiltnqp.html

C#:   (int)resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gt2viztxlug.html

[L08] 并发请求多个地址
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqafuvr.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhijiandao.cn/Article/details/gt2foiafvxl.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnbvjwp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrdiujw.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmzyeph.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gt2exsiwcpw.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtkikme.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfcrihq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zhijiandao.cn/Article/details/gt2ikaqxrgg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkvzxcy.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjvbzkm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmodnbh.html

[M01] 读取命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zwnhwfxm.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2peizjgvi.html

PHP:  $argv;  $argc;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvhokibk.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrfupnh.html

TS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzaizabk.html

Java: args 数组（main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmgqlcs.html

Go:   os.Args[1:]
来源：http://dali.zhijiandao.cn/Article/details/gt2erukhkyf.html

Ruby: ARGV
来源：http://dali.zhijiandao.cn/Article/details/gt2ssjaisld.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhijiandao.cn/Article/details/gt2xvwqwovn.html

[M02] 读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2spjmlrlk.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhoosps.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvswasob.html

JS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2twsphvch.html

TS:   process.env.HOME
来源：http://dali.zhijiandao.cn/Article/details/gt2zplggzdg.html

Java: System.getenv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzevzqhc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2imymlpyd.html

Ruby: ENV["HOME"]
来源：http://dali.zhijiandao.cn/Article/details/gt2twcjfsen.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrbkcds.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gt2hwanyzuj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2crzzsdvy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2hzhvhwtn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxvyozk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbexcuig.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrhqqlv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhijiandao.cn/Article/details/gt2zehejazy.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnqzbwe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhijiandao.cn/Article/details/gt2djcdgxed.html

[M04] 获取当前工作目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hysoixuo.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qymnszol.html

PHP:  getcwd();
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjndapt.html

JS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2czvpjllg.html

TS:   process.cwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlsdhuqo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhijiandao.cn/Article/details/gt2khinlgdz.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsnxqvg.html

Ruby: Dir.pwd
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwotyuw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhijiandao.cn/Article/details/gt2fsifdkcw.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2sutaxoec.html

Py:   sys.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yckpvafi.html

PHP:  exit(1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnluzdz.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcemalzx.html

TS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxesgzi.html

Java: System.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cieyuehr.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpzmera.html

Ruby: exit 1
来源：http://dali.zhijiandao.cn/Article/details/gt2keysblnn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhhuxhg.html

[M06] 向标准错误输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ivyldlby.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fduituks.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhijiandao.cn/Article/details/gt2pkkzpmza.html

JS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ongvnpvo.html

TS:   console.error("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbpptet.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2aejpzhfm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.zhijiandao.cn/Article/details/gt2jlinppua.html

Ruby: warn "err"
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpicwuu.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2suhewwnu.html

[M07] 判断是否为主入口
来源：http://dali.zhijiandao.cn/Article/details/gt2alncmknv.html

Py:   if __name__ == "__main__":
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqsfizv.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2niguymvr.html

JS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2nudnrnyp.html

TS:   require.main === module
来源：http://dali.zhijiandao.cn/Article/details/gt2rxnapszp.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2lojffgcb.html

Go:   func main()
来源：http://dali.zhijiandao.cn/Article/details/gt2hazgnfxg.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2grmyesmc.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkvbjrpo.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vumhhzuz.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhijiandao.cn/Article/details/gt2jcehlnkb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqdayfd.html

JS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzizcol.html

TS:   process.platform;  process.version
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbyiuvp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzrfbsz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhijiandao.cn/Article/details/gt2eslbxjmo.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gt2rolidmfz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeevzlz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hinezdjp.html

N. 数据结构与算法
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsmusbh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2leblgozc.html

[N01] 二分查找（有序数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rckeonbx.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehijuoyu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkejahho.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxfeskph.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfififwa.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sfiesmio.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbshlsfu.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2qauemvoj.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvkuxtq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhijiandao.cn/Article/details/gt2xxdcqndz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvvbpry.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdjrdbe.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufqwfjcb.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmuklrt.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqzqtwbn.html

Go:   slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjowihs.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkxusas.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2waezfneb.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsexsvyk.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2bpjxfqxf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gt2iregqqvb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrybmfg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwwgbcb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mavdvlad.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2rhihasfw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2vevzdtml.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhijiandao.cn/Article/details/gt2zfovggzx.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2mhnbgbqa.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2afuafqrb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2grktorsy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2frzrzamj.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2awnsgwdf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qivrjpfe.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcmhzsf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcskrac.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ergmyzwf.html

[N05] 最大公约数
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvkfhid.html

Py:   math.gcd(a, b)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuoqqekn.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqczszk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xglmemug.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slzcawlo.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bcubfxyv.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqysntzn.html

Ruby: a.gcd(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeouviua.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajglkgte.html

[N06] 判断回文字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcrxbhw.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2risrxicc.html

PHP:  $s === strrev($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpbkesr.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwsdxbp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2khkhsoyy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zhijiandao.cn/Article/details/gt2njvuvtda.html

Go:   // 双指针从两端比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhdpgiy.html

Ruby: s == s.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2nzquctuh.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2suuhepbl.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2talvpcnx.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhijiandao.cn/Article/details/gt2nsnmafhu.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhijiandao.cn/Article/details/gt2xyprcsha.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqopokil.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbnreuj.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnhxitm.html

Go:   // 手写 map[int]int
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwozlsn.html

Ruby: // 手写 Hash
来源：http://dali.zhijiandao.cn/Article/details/gt2elwnqjft.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmgmtjn.html

[N08] 生成全排列
来源：http://dali.zhijiandao.cn/Article/details/gt2ghowbote.html

Py:   itertools.permutations(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lekgfsxb.html

PHP:  // 手写递归交换
来源：http://dali.zhijiandao.cn/Article/details/gt2qisahdwl.html

JS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2vywmsdpp.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2aetynobj.html

Java: // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pnezkgwq.html

Go:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnybzak.html

Ruby: arr.permutation.to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2wycbcrhn.html

C#:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcljyfj.html

[N09] 栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhnktyu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2aktizztw.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zulwwxjc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmjclip.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpyziya.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhijiandao.cn/Article/details/gt2xfdgkxrp.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gt2wcsxhebp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qowcekwo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2oshabrnp.html

[N10] 链表节点定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mfcfvhop.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhijiandao.cn/Article/details/gt2jvqqaxip.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjkwqmm.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwougjoa.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkteldio.html

Java: class Node { int v; Node next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2huphhjmp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjanvaj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyagqihr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acicvzmn.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gibidlrd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqzyhxw.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovbyjeve.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2jczppsbp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhijiandao.cn/Article/details/gt2bsmmfljj.html

Java: // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2juzrbngb.html

Go:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ruoqewfi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhijiandao.cn/Article/details/gt2pnskgdpw.html

C#:   // 手写递归
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnhhxyn.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2twuiletn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2iarsrrba.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2czhwidhp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2cxihwxxx.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxsazup.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzkgacf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmhrtkj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2umnslaky.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhijiandao.cn/Article/details/gt2vvrleevs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dauhixqm.html

O. 并发与异步
来源：http://dali.zhijiandao.cn/Article/details/gt2otqynlgd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2neuuewaw.html

[O01] 启动一个线程
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkawose.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2idnqhxjz.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhijiandao.cn/Article/details/gt2scurkkel.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhijiandao.cn/Article/details/gt2drhdqqmg.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcnelko.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhijiandao.cn/Article/details/gt2tsakjclx.html

Go:   go f()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzcidhqc.html

Ruby: Thread.new { f }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqfonncb.html

C#:   Task.Run(() => F());
来源：http://dali.zhijiandao.cn/Article/details/gt2nufgaxvp.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2dmclwjdx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaahshtm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhijiandao.cn/Article/details/gt2ffadfteb.html

JS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2gsecbvyg.html

TS:   // worker_threads 线程池
来源：http://dali.zhijiandao.cn/Article/details/gt2vxhcwtjp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2npwccckx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhijiandao.cn/Article/details/gt2joqlztfv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvyclru.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdpkuqb.html

[O03] 加锁保护共享数据
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoqciil.html

Py:   with lock: shared += 1
来源：http://dali.zhijiandao.cn/Article/details/gt2crpyzwyu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrklctn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhijiandao.cn/Article/details/gt2qctrbsbj.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2mosgrcrn.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjheysg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhijiandao.cn/Article/details/gt2qroyyerz.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghnlvhco.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjrupdal.html

[O04] 定义异步函数并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2tcaskfbb.html

Py:   async def f():⏎    await g()
来源：http://dali.zhijiandao.cn/Article/details/gt2nsindumo.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gt2pptzhprp.html

JS:   async function f() { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2csxhzmjw.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjxltit.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhijiandao.cn/Article/details/gt2wlknbaub.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrpuyza.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhijiandao.cn/Article/details/gt2mmwsggmg.html

C#:   async Task F() { await G(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2mdozzijl.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjxtthj.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvntypec.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhijiandao.cn/Article/details/gt2oawlxypr.html

JS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2onuknoej.html

TS:   await Promise.all(tasks)
来源：http://dali.zhijiandao.cn/Article/details/gt2forpnbms.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjnecnr.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhijiandao.cn/Article/details/gt2ywxqyjlv.html

Ruby: threads.map(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjfbybyh.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzvlvfwq.html

[O06] 使用进程池
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzpulav.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvntzlx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rmwkxrrx.html

JS:   // child_process / cluster 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2sndjxmmr.html


<!-- 参考信息 -->