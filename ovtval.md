代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.yongpay.top/Article/details/gtttlbhpmp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.pengpengdd.cyou/Article/details/gtjipsvadc.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpbvjwzu.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gthyklahar.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gtxmzcvhzt.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hnxiangtu.top/Article/details/gtqwkoiued.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gtijgiyuxz.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.ehwqpu.com/Article/details/gtwcujilvk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrdujlci.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.meibo888.top/Article/details/gtkkuvgxcb.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gtyxxldtbu.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.tanke756.top/Article/details/gtvhzgzzcx.html

[L03] 设置自定义请求头
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhpegyjt.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ppjwa.cn/Article/details/gtifugndlu.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.birdmap.top/Article/details/gtrzpoqubm.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xuanzx.com/Article/details/gticfiqduf.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtexgvbinp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258.top/Article/details/gtboksskql.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.vqdsnc.cn/Article/details/gtddmoomcf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.wangshuangyany.cn/Article/details/gtblmrplke.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cheryme.top/Article/details/gtxgwsdaul.html

[L04] 设置超时
来源：http://dali.feifeiyinyue.top/Article/details/gtkhpjiutx.html

Py:   requests.get(url, timeout=5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnuivhiwz.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gtsfhmyyad.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.kuanghao11.cn/Article/details/gtixsmvlor.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gtkcpsnhha.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsadpcjtn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gtsmmsnvqk.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yonumen.top/Article/details/gtxpwgrouc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtimmxdoda.html

[L05] 上传文件（multipart）
来源：http://dali.yj202588.top/Article/details/gtulijewwp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daxiang520.top/Article/details/gtbbjlzpxb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.guannengcc.top/Article/details/gtxmhwyyjx.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.ppjwa.cn/Article/details/gtkoyqhefj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigfzy.top/Article/details/gtftuqvlwl.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pengpengdd.cyou/Article/details/gtohoebfio.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.haohaochexian.top/Article/details/gtuyhirzrh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.mhx1999.top/Article/details/gtnjwekpyd.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtymqrvnqp.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gtwdfibxdd.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gtbxbxmzjd.html

PHP:  json_decode($body, true);
来源：http://dali.cheryme.top/Article/details/gtjpyhvpzn.html

JS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtfgrfwvbt.html

TS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gtwxmwplke.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqvweepx.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gtfkmulpra.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hnxiangtu.top/Article/details/gtzalsvsxj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.vqdsnc.cn/Article/details/gtzdvkseyp.html

[L07] 处理 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtyobftllq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.hnxiangtu.top/Article/details/gtkzumslqv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.pycfn.com/Article/details/gteqcdjzbn.html

JS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gtvpetqsgt.html

TS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gtzsjjckjl.html

Java: resp.statusCode()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvqcuymn.html

Go:   resp.StatusCode
来源：http://dali.meibo888.top/Article/details/gtwquczxbg.html

Ruby: resp.code.to_i
来源：http://dali.guowangkeji.top/Article/details/gtaytdkanp.html

C#:   (int)resp.StatusCode
来源：http://dali.feifeiyinyue.top/Article/details/gtvgwqwkbx.html

[L08] 并发请求多个地址
来源：http://dali.aibaodan.cn/Article/details/gtxtsargfa.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.tianlin.xyz/Article/details/gtloptxjxc.html

PHP:  curl_multi_init() 系列
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqnrpeym.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtpcuqysfr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtofjuwfni.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvidrqfbm.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.haohaochexian.top/Article/details/gtymeptpxa.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sxryk.cn/Article/details/gtmghouwec.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gtirmhjfqy.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtmmhduylx.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gtyzrxobhl.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtcuhsyncj.html

[M01] 读取命令行参数
来源：http://dali.yuanzhike.top/Article/details/gtfolrwfap.html

Py:   sys.argv[1:]
来源：http://dali.tian-w.cn/Article/details/gtmitszagl.html

PHP:  $argv;  $argc;
来源：http://dali.vqdsnc.cn/Article/details/gtxmtsozwu.html

JS:   process.argv.slice(2)
来源：http://dali.yanxiufei.cn/Article/details/gthgxgatik.html

TS:   process.argv.slice(2)
来源：http://dali.gotoacloud.top/Article/details/gtqswzcbwl.html

Java: args 数组（main 方法参数）
来源：http://dali.gogol.net.cn/Article/details/gtxvigdwej.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gtpcjtbsuk.html

Ruby: ARGV
来源：http://dali.pycfn.com/Article/details/gtohqdyngh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtpjzpbrqu.html

[M02] 读取环境变量
来源：http://dali.bjfxy.top/Article/details/gtzgtccskr.html

Py:   os.environ.get("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtviuewfzq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhoulong.xyz/Article/details/gtvjcohoty.html

JS:   process.env.HOME
来源：http://dali.guannengcc.top/Article/details/gtkjdbpbif.html

TS:   process.env.HOME
来源：http://dali.meibo888.top/Article/details/gtacyrgzqm.html

Java: System.getenv("HOME")
来源：http://dali.daria6918.cn/Article/details/gtrjjwzgnm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtcdeibskx.html

Ruby: ENV["HOME"]
来源：http://dali.sxryk.cn/Article/details/gteahiftnz.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.wangdashe.top/Article/details/gtospdtwkg.html

[M03] 执行外部命令
来源：http://dali.yj202588.top/Article/details/gtzonkchsc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.c1oappe.top/Article/details/gtyvzwygty.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.wangdashe.top/Article/details/gtuhtvfnbu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.aizwys.cn/Article/details/gttuvmcvbc.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.316326.xyz/Article/details/gtzvnjsiuh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gtrinxrege.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aizwys.cn/Article/details/gtkhvvfypn.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuanzhike.top/Article/details/gtlangbnmv.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnxiangtu.top/Article/details/gtekcorajd.html

[M04] 获取当前工作目录
来源：http://dali.xuanzx.com/Article/details/gtcuzncevr.html

Py:   os.getcwd()
来源：http://dali.jlsjyb.cn/Article/details/gtkxmybglh.html

PHP:  getcwd();
来源：http://dali.jianghu66.top/Article/details/gtsxaadocl.html

JS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtbaevvbfo.html

TS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtkpskionx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhoulong.xyz/Article/details/gtjgevhdtd.html

Go:   os.Getwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtoumvfotl.html

Ruby: Dir.pwd
来源：http://dali.andypj.xyz/Article/details/gtxukwrdwv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gtkbejkawf.html

[M05] 设置退出码
来源：http://dali.xziqi.cn/Article/details/gtmuobupmh.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtuoqntqps.html

PHP:  exit(1);
来源：http://dali.fengsongda.top/Article/details/gtxnmhlfbr.html

JS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtxlwujltj.html

TS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gtwobbdpjk.html

Java: System.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gtmmlguonp.html

Go:   os.Exit(1)
来源：http://dali.zdqjudy.top/Article/details/gtecdlgplw.html

Ruby: exit 1
来源：http://dali.haohaochexian.top/Article/details/gtmbhgizhv.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gzhubu.top/Article/details/gtuworkbrb.html

[M06] 向标准错误输出
来源：http://dali.cashguo.top/Article/details/gtaszaisvl.html

Py:   print("err", file=sys.stderr)
来源：http://dali.havefunace.top/Article/details/gtodmoibpi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shangyingyoupin.top/Article/details/gtpwaeejjr.html

JS:   console.error("err")
来源：http://dali.yvedp.cn/Article/details/gtugwpgjby.html

TS:   console.error("err")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhtbofqc.html

Java: System.err.println("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtavtquhrn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yj20258888.top/Article/details/gtqradbtdx.html

Ruby: warn "err"
来源：http://dali.hysaishi.cn/Article/details/gtwktxzqct.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gtuafoomoq.html

[M07] 判断是否为主入口
来源：http://dali.fzhhl.top/Article/details/gtojaugyie.html

Py:   if __name__ == "__main__":
来源：http://dali.ybcxt.top/Article/details/gtavjptfwj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhongyouzk.top/Article/details/gttlhmabor.html

JS:   require.main === module
来源：http://dali.chenzaomai.com/Article/details/gtuwhokedv.html

TS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gtvbeguwwm.html

Java: public static void main(String[] args)
来源：http://dali.gotoacloud.top/Article/details/gtwbiwvavk.html

Go:   func main()
来源：http://dali.yj20258888.top/Article/details/gtmjosqodo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jianghu66.top/Article/details/gtvpcqilym.html

C#:   static void Main(string[] args)
来源：http://dali.jinqigufen.top/Article/details/gtnswchrrt.html

[M08] 获取系统与运行时信息
来源：http://dali.yj20258.top/Article/details/gtkfitqzvs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.meibo888.top/Article/details/gtoihbfmzu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gtbnobqqmc.html

JS:   process.platform;  process.version
来源：http://dali.chenjidiqi.icu/Article/details/gtwsekuhui.html

TS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtiygrsjyx.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.0kj1m.cn/Article/details/gttakvbgiz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.guannengcc.top/Article/details/gtjjfjpoxv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gtwlpskfvq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xziqi.cn/Article/details/gtfyqddyyl.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtljavoapv.html

N. 数据结构与算法
来源：http://dali.wangdashe.top/Article/details/gthsbofyqd.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfadyqrfh.html

[N01] 二分查找（有序数组）
来源：http://dali.zycfv.cn/Article/details/gtwwxmoswj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtsvstjwgv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtqaeawjuz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cqqwz.cn/Article/details/gtnsocwbfd.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gttksdtdbj.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtkzkdwgxj.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlamnppc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenlongwang.top/Article/details/gtbexgaial.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocpuvnjo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ybcxt.top/Article/details/gtnsgvrrjs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtsweelvlq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gtdpudwitd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj20258.top/Article/details/gtkpyvrdgv.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tian-w.cn/Article/details/gtuutonctn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shuidangran.top/Article/details/gtlizkiuma.html

Go:   slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gtiphmzdcb.html

Ruby: arr.sort
来源：http://dali.iojbl.cn/Article/details/gtpxpxdrmn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cheryme.top/Article/details/gtwbxvhdlz.html

[N03] 快速排序（分治示例）
来源：http://dali.sysykeji.top/Article/details/gtukvjqzou.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sysykeji.top/Article/details/gtxykjziyk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yueranfly.top/Article/details/gtwbnbfmke.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj20258888.top/Article/details/gtxpjzwaea.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhoulong.xyz/Article/details/gtnuebsmwb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jqgfzy.top/Article/details/gtigwuszwd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guannengcc.top/Article/details/gtmjasbrfu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dianchejie.cn/Article/details/gtieidertu.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangdashe.top/Article/details/gtrzdcmkmb.html

[N04] 斐波那契数列
来源：http://dali.cqqwz.cn/Article/details/gtdlwsqglc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.smart0.xyz/Article/details/gttgghbkel.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gttehqslex.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtqmprfbva.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gthugqesnj.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.c1oappe.top/Article/details/gtgkktimpm.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpopoilwa.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.quarkkingdee.top/Article/details/gtyneceaxe.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gtxpscedit.html

[N05] 最大公约数
来源：http://dali.daxiang520.top/Article/details/gtwafbhdqj.html

Py:   math.gcd(a, b)
来源：http://dali.cheryme.top/Article/details/gtlrsvbwhu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ydzc1.top/Article/details/gtrcpfipzw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohbkqksb.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gthezgxyin.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xziqi.cn/Article/details/gtgyjnovha.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yangfankeji.com/Article/details/gtocymzqvd.html

Ruby: a.gcd(b)
来源：http://dali.hywenlv.cn/Article/details/gtjqtybiwr.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cucudq.cn/Article/details/gtngqfljao.html

[N06] 判断回文字符串
来源：http://dali.meibo888.top/Article/details/gthvceewsk.html

Py:   s == s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gtskmkjfkl.html

PHP:  $s === strrev($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsjaaqgll.html

JS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gtevzihkng.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtoufbgepp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jqgfzy.top/Article/details/gtsgbjuemv.html

Go:   // 双指针从两端比较
来源：http://dali.yonumen.top/Article/details/gtxbzqofxv.html

Ruby: s == s.reverse
来源：http://dali.sufxvd.cn/Article/details/gtkdjwldxt.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gtcgaoqbjx.html

[N07] 两数之和（返回下标）
来源：http://dali.yanxiufei.cn/Article/details/gtrcvagged.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sysykeji.top/Article/details/gtnaotpyke.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwpjtigm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gtacuxubhr.html

TS:   // 手写 Map<string, number>
来源：http://dali.havefunace.top/Article/details/gtiopadium.html

Java: // 手写 HashMap
来源：http://dali.0kj1m.cn/Article/details/gtjuhzfyzw.html

Go:   // 手写 map[int]int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxkkwwdx.html

Ruby: // 手写 Hash
来源：http://dali.9152youxi.cn/Article/details/gtneocazra.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jlsjyb.cn/Article/details/gtcwaytiqw.html

[N08] 生成全排列
来源：http://dali.hnqzz.top/Article/details/gtfxuzkeyw.html

Py:   itertools.permutations(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtzrdaqclz.html

PHP:  // 手写递归交换
来源：http://dali.0kj1m.cn/Article/details/gtlsadrfqf.html

JS:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtqhklkrsm.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtrtzqgqtb.html

Java: // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gtbisjuxcg.html

Go:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gtgnhzermj.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258.top/Article/details/gtuhlpjpjj.html

C#:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtpvrcwori.html

[N09] 栈与队列
来源：http://dali.tanke756.top/Article/details/gtqjlivejg.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuanzhike.top/Article/details/gthlzyzpyd.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtzqzpacrt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtfzejahcl.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj202588.top/Article/details/gtvxnqcmyg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hammf.cn/Article/details/gtucmwkkny.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgfzy.top/Article/details/gtagibfkxp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gtivvkktsh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.tanke756.top/Article/details/gtuhtontwd.html

[N10] 链表节点定义
来源：http://dali.cashguo.top/Article/details/gtwetgvgqm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.mhx1999.top/Article/details/gttesvrelb.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xinyue.icu/Article/details/gttfzbnaci.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hfpthk.cn/Article/details/gtsccybkja.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gtoqobxdpy.html

Java: class Node { int v; Node next; }
来源：http://dali.redwolf501.top/Article/details/gtmhiskekm.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.fzhhl.top/Article/details/gtuwgjwmdo.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shzxlz.cn/Article/details/gtqgvqlosz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.daxiang520.top/Article/details/gthhydqioh.html

[N11] 二叉树中序遍历
来源：http://dali.dashuyun.cn/Article/details/gtquhamgds.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.316326.xyz/Article/details/gtfbfojhda.html

PHP:  // 手写递归函数
来源：http://dali.zhiwuduotai.top/Article/details/gtywjadixc.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258888.top/Article/details/gtgvxdylbu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guannengcc.top/Article/details/gtugdiwyth.html

Java: // 手写递归
来源：http://dali.yonumen.top/Article/details/gtjpyiulvo.html

Go:   // 手写递归
来源：http://dali.chenzaomai.com/Article/details/gtrgisifld.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqmuuiqv.html

C#:   // 手写递归
来源：http://dali.sweek.top/Article/details/gtgirlktkb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sufxvd.cn/Article/details/gtmfgbnruk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yvedp.cn/Article/details/gtohcfcuin.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yueranfly.top/Article/details/gtrudkicpe.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.cheryme.top/Article/details/gtoxjqijlj.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gtizhyisps.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigfzy.top/Article/details/gtguetokkn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.svipenyu.cn/Article/details/gtjuczylwe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.snrcjt.cn/Article/details/gtjhlgttrt.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shuidangran.top/Article/details/gtjiwvgomy.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtrrappoyo.html

O. 并发与异步
来源：http://dali.hammf.cn/Article/details/gthbyziehm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtvuxlapyf.html

[O01] 启动一个线程
来源：http://dali.cashguo.top/Article/details/gtcpxvyjca.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.redwolf501.top/Article/details/gtmmwmxzsi.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yongpay.top/Article/details/gtyivnrrvy.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.fengsongda.top/Article/details/gtdegmkjbo.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gteowgcutl.html

Java: new Thread(() -> f()).start()
来源：http://dali.xziqi.cn/Article/details/gtqngssyyr.html

Go:   go f()
来源：http://dali.nwbrower.top/Article/details/gtbaakenqk.html

Ruby: Thread.new { f }
来源：http://dali.jinqigufen.top/Article/details/gtomcvsqxn.html

C#:   Task.Run(() => F());
来源：http://dali.shuidangran.top/Article/details/gtotjggzux.html

[O02] 使用线程池
来源：http://dali.jqgfzy.top/Article/details/gtkgdppztc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.9152youxi.cn/Article/details/gtslwciheb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cqqwz.cn/Article/details/gtnjbhzwdv.html

JS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gtyplwcgjb.html

TS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gtgbrpfmfb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.fzhhl.top/Article/details/gturpmyghs.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.haohaochexian.top/Article/details/gtiteuzcoc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pycfn.com/Article/details/gtebuehyvr.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnqzz.top/Article/details/gtnpjzuqtx.html

[O03] 加锁保护共享数据
来源：http://dali.gotoacloud.top/Article/details/gtwovxzhix.html

Py:   with lock: shared += 1
来源：http://dali.ehwqpu.com/Article/details/gtciqnzrgj.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shuidangran.top/Article/details/gtvxppwkws.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.gogol.net.cn/Article/details/gtwcscfitc.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtgkfbywvj.html

Java: synchronized (this) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gtfrhwbvjv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gtgweumnbx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenzaomai.com/Article/details/gthfbouhgt.html

C#:   lock (gate) { shared++; }
来源：http://dali.birdmap.top/Article/details/gtjdlukvgp.html

[O04] 定义异步函数并等待
来源：http://dali.daria6918.cn/Article/details/gtdujllmun.html

Py:   async def f():⏎    await g()
来源：http://dali.iojbl.cn/Article/details/gtbbnrcbkc.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.redwolf501.top/Article/details/gttrzxtjxd.html

JS:   async function f() { await g(); }
来源：http://dali.iojbl.cn/Article/details/gtwdyvqsam.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.fengsongda.top/Article/details/gtjqdramrk.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hfpthk.cn/Article/details/gtvfpvxzee.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sweek.top/Article/details/gtvnvkpfmg.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hysaishi.cn/Article/details/gtehbymluo.html

C#:   async Task F() { await G(); }
来源：http://dali.dashuyun.cn/Article/details/gtvanchgsi.html

[O05] 并发执行并等待全部完成
来源：http://dali.wangshuangyany.cn/Article/details/gtvkrvnnfb.html

Py:   asyncio.gather(*tasks)
来源：http://dali.wangdashe.top/Article/details/gtobmbjrvz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxuanxn.top/Article/details/gtjdselhyc.html

JS:   await Promise.all(tasks)
来源：http://dali.cdnleiting.top/Article/details/gtxqqefdhu.html

TS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gtncaekmcr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.chenzaomai.com/Article/details/gtcqjboisp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jqgufenzy.top/Article/details/gtrmopreid.html

Ruby: threads.map(&:join)
来源：http://dali.xziqi.cn/Article/details/gtgmporwrx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.chenjidiqi.icu/Article/details/gtgzmyznas.html


<!-- 参考信息 -->