代发 wailian999

Py:   requests.post(url, json={"a": 1})
来源：http://dali.hfpthk.cn/Article/details/gthvwehmmg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zdqjudy.top/Article/details/gttkbibzll.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.sysykeji.top/Article/details/gtjifamnfq.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.guowangkeji.top/Article/details/gthefjqgsi.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmddalhtr.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.nanxuanxn.top/Article/details/gtwnygzolr.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.nanxuanxn.top/Article/details/gthialpivb.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.ivvv.top/Article/details/gtccrrydxq.html

[L03] 设置自定义请求头
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgzbjjiad.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yonumen.top/Article/details/gtognpnqwj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqjziawj.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.aizwys.cn/Article/details/gtsysgngqm.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yj20258888.top/Article/details/gtubogswia.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtxcdpgeml.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.kuanghao11.cn/Article/details/gtaqqyspzx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.ehwqpu.com/Article/details/gtrjzbahrz.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.xziqi.cn/Article/details/gtmfzxobeo.html

[L04] 设置超时
来源：http://dali.snrcjt.cn/Article/details/gtqluileme.html

Py:   requests.get(url, timeout=5)
来源：http://dali.cucudq.cn/Article/details/gtuecuabel.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yvedp.cn/Article/details/gtenljwltf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pengpengdd.cyou/Article/details/gtgdkqjxzp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinqigufen.top/Article/details/gtadobkueb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guowangkeji.top/Article/details/gtlbbnlhsx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.fengsongda.top/Article/details/gthvhsxleb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zycfv.cn/Article/details/gtoazcmand.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gtdjxxaryw.html

[L05] 上传文件（multipart）
来源：http://dali.dianchejie.cn/Article/details/gtadubjply.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gtwtbhheix.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cqqwz.cn/Article/details/gtqaxvdtxd.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gtjfzflvwt.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.sufxvd.cn/Article/details/gtsqevzqjx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gzhubu.top/Article/details/gtmjfqoxjn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.iojbl.cn/Article/details/gtjafcfkyw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zycfv.cn/Article/details/gtbhvbnfie.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtawyxizrb.html

[L06] 解析响应为 JSON
来源：http://dali.shzxlz.cn/Article/details/gtlollctzc.html

Py:   resp.json()
来源：http://dali.gogol.net.cn/Article/details/gtatbnfbez.html

PHP:  json_decode($body, true);
来源：http://dali.fengsongda.top/Article/details/gtggutzteo.html

JS:   await resp.json()
来源：http://dali.yuxming.cn/Article/details/gtwdsmhhap.html

TS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gtnlanyrgk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtthkbbbqt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gogol.net.cn/Article/details/gtjotsiyoi.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gogol.net.cn/Article/details/gtpsjqledc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.nanxinkj.top/Article/details/gtddbivfiy.html

[L07] 处理 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gttmmkerwv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhixingplan.top/Article/details/gtefszxnzp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.guowangkeji.top/Article/details/gtrixjnzbm.html

JS:   resp.ok;  resp.status
来源：http://dali.gaohongyu789.top/Article/details/gtxjtugjhi.html

TS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gtaccckyfc.html

Java: resp.statusCode()
来源：http://dali.cdnleiting.top/Article/details/gtlrqsgfay.html

Go:   resp.StatusCode
来源：http://dali.sxryk.cn/Article/details/gtxbrketga.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gtdwrtsnfe.html

C#:   (int)resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtdbtzamrj.html

[L08] 并发请求多个地址
来源：http://dali.316326.xyz/Article/details/gtpxoicuuu.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jinqigufen.top/Article/details/gtxnfbvesg.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gtlvcevevu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gtznqwfxxx.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtduqwrwfu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecbmxzrk.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.mhx1999.top/Article/details/gtoihesxub.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ivvv.top/Article/details/gtsbwgkape.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yueranfly.top/Article/details/gtmxmrivls.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtznkajlit.html

M. 命令行 / 进程 / 环境
来源：http://dali.cashguo.top/Article/details/gtsnqcuvre.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtdncqkjcv.html

[M01] 读取命令行参数
来源：http://dali.zdqjudy.top/Article/details/gtlodyckxt.html

Py:   sys.argv[1:]
来源：http://dali.xziqi.cn/Article/details/gtuinhpuxg.html

PHP:  $argv;  $argc;
来源：http://dali.sxryk.cn/Article/details/gtjvdqlmop.html

JS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gtzerwbeyc.html

TS:   process.argv.slice(2)
来源：http://dali.jqgfzy.top/Article/details/gtxmssamuh.html

Java: args 数组（main 方法参数）
来源：http://dali.guowangkeji.top/Article/details/gtqudjzsgv.html

Go:   os.Args[1:]
来源：http://dali.yuanzhike.top/Article/details/gtlboazuov.html

Ruby: ARGV
来源：http://dali.guowangkeji.top/Article/details/gtdpgmjrqo.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtqmryxdil.html

[M02] 读取环境变量
来源：http://dali.zhixingplan.top/Article/details/gtqugrzxfe.html

Py:   os.environ.get("HOME")
来源：http://dali.xylfe.cn/Article/details/gturgzxijh.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xinyue.icu/Article/details/gtalyjljpf.html

JS:   process.env.HOME
来源：http://dali.sysykeji.top/Article/details/gtojdeykoi.html

TS:   process.env.HOME
来源：http://dali.tian-w.cn/Article/details/gtrmclxxym.html

Java: System.getenv("HOME")
来源：http://dali.gzhubu.top/Article/details/gtgfvovahp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.cheryme.top/Article/details/gtsudugzjr.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gtqubmicvv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnxiangtu.top/Article/details/gtmhdrjjij.html

[M03] 执行外部命令
来源：http://dali.ybcxt.top/Article/details/gtibkfnbzg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubpazzss.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gtadhvkqff.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cashguo.top/Article/details/gtycdsycpk.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gtkeaufjsi.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ehwqpu.com/Article/details/gtjxthswbe.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ehwqpu.com/Article/details/gtxrpouxzg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.kuanghao11.cn/Article/details/gtycmusojp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hywenlv.cn/Article/details/gtuwesewnn.html

[M04] 获取当前工作目录
来源：http://dali.nwbrower.top/Article/details/gthihaizgr.html

Py:   os.getcwd()
来源：http://dali.zhongyouzk.top/Article/details/gtlurayufk.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gtqevzaibn.html

JS:   process.cwd()
来源：http://dali.sysykeji.top/Article/details/gtamfbazap.html

TS:   process.cwd()
来源：http://dali.zhoulong.xyz/Article/details/gtzderamgu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gtreiylagu.html

Go:   os.Getwd()
来源：http://dali.zhengqikj.top/Article/details/gtownsldxh.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gtpxuiwzwd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.quarkkingdee.top/Article/details/gtfuhruvqa.html

[M05] 设置退出码
来源：http://dali.hongshengwenyu.top/Article/details/gtyhudgqfo.html

Py:   sys.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtvuwtsphp.html

PHP:  exit(1);
来源：http://dali.ybcxt.top/Article/details/gtxlcvubud.html

JS:   process.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvbzowbz.html

TS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtnxlotdao.html

Java: System.exit(1)
来源：http://dali.zycfv.cn/Article/details/gtvgpqucrm.html

Go:   os.Exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtnppmzqoz.html

Ruby: exit 1
来源：http://dali.jinqigfzy.top/Article/details/gteplbisfd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenzaomai.com/Article/details/gtpfhjgkjh.html

[M06] 向标准错误输出
来源：http://dali.0kj1m.cn/Article/details/gtywfanetc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gotoacloud.top/Article/details/gtitczanif.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zdqjudy.top/Article/details/gtkemtipfn.html

JS:   console.error("err")
来源：http://dali.ehwqpu.com/Article/details/gtgmqokfme.html

TS:   console.error("err")
来源：http://dali.cucudq.cn/Article/details/gtrgtetolo.html

Java: System.err.println("err")
来源：http://dali.tian-w.cn/Article/details/gtuwlawipk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.daxiang520.top/Article/details/gtajagzysp.html

Ruby: warn "err"
来源：http://dali.wangshuangyany.cn/Article/details/gtfxsirdci.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yanxiufei.cn/Article/details/gtfabburbn.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gtdqsobsxi.html

Py:   if __name__ == "__main__":
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjcxvisjl.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guowangkeji.top/Article/details/gtmdzulyww.html

JS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gtxtjpuvtv.html

TS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gtpudnvkwc.html

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gtuxujzovu.html

Go:   func main()
来源：http://dali.ivvv.top/Article/details/gtyiownywi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.bjfxy.top/Article/details/gtfvdvkgbd.html

C#:   static void Main(string[] args)
来源：http://dali.haohaochexian.top/Article/details/gtbumyvicb.html

[M08] 获取系统与运行时信息
来源：http://dali.cheryme.top/Article/details/gthuxvrayv.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cheryme.top/Article/details/gtjrlavfyu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgivziavc.html

JS:   process.platform;  process.version
来源：http://dali.jinqigfzy.top/Article/details/gtjeoifzxk.html

TS:   process.platform;  process.version
来源：http://dali.gogol.net.cn/Article/details/gtxilrymky.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ppjwa.cn/Article/details/gtcnsmfgpq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.feifeiyinyue.top/Article/details/gtchhdkubl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gtcgncgoxr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.fzhhl.top/Article/details/gtqxqzkxnz.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtjsuobqgy.html

N. 数据结构与算法
来源：http://dali.tian-w.cn/Article/details/gtmpatgtxk.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtgwdtvqib.html

[N01] 二分查找（有序数组）
来源：http://dali.chenlongwang.top/Article/details/gtbjuvvsvq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtlozvoruk.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.aizwys.cn/Article/details/gtmyolwvie.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jlsjyb.cn/Article/details/gtmtesyrni.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tanke756.top/Article/details/gttgonwmga.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtvxeqltep.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.bjfxy.top/Article/details/gturvvpddv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yueranfly.top/Article/details/gtsdopatck.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtsgafhqkm.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhengqikj.top/Article/details/gtmejeoeso.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtttvsuwdl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.daria6918.cn/Article/details/gthzkvyfeq.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtgfqedeuu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.chenjidiqi.icu/Article/details/gtpopolatw.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yj20258888.top/Article/details/gttekqzeni.html

Go:   slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtodqsisns.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gtaztuaatl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.aibaodan.cn/Article/details/gteuzkvdvq.html

[N03] 快速排序（分治示例）
来源：http://dali.yongpay.top/Article/details/gtcueiaahi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqivutzj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhijiandao.cn/Article/details/gtugdzwypy.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gtdbqyczxn.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zhijiandao.cn/Article/details/gtnlcxkyzn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.zdqjudy.top/Article/details/gtjszbvtkn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yangfankeji.com/Article/details/gtvefsvuhg.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.pengpengdd.cyou/Article/details/gtobnzvxgj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gtttqvrjll.html

[N04] 斐波那契数列
来源：http://dali.yvedp.cn/Article/details/gtrkzzefal.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gthdqfsina.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhengqikj.top/Article/details/gthawlgjat.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtmcfdpjox.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gteopcyokr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gtwketpxvh.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cdnleiting.top/Article/details/gtfuifhubf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.gaohongyu789.top/Article/details/gtwwtohtey.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gtizgkwcwj.html

[N05] 最大公约数
来源：http://dali.vqdsnc.cn/Article/details/gttuvjcxet.html

Py:   math.gcd(a, b)
来源：http://dali.jqgufenzy.top/Article/details/gtyhykublq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.birdmap.top/Article/details/gtakchghmx.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtyflfwcau.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtvrhzxuvf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hfpthk.cn/Article/details/gteptqduaf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aibaodan.cn/Article/details/gtnyzyyqem.html

Ruby: a.gcd(b)
来源：http://dali.dashuyun.cn/Article/details/gtqnsahthi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yanxiufei.cn/Article/details/gthpgxeyfx.html

[N06] 判断回文字符串
来源：http://dali.shzxlz.cn/Article/details/gtmylyopju.html

Py:   s == s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gtdwqlvqul.html

PHP:  $s === strrev($s);
来源：http://dali.iojbl.cn/Article/details/gtlwokdzve.html

JS:   s === [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtzmoaoeyq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtxzlbhysj.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj202588.top/Article/details/gtpewkvbyi.html

Go:   // 双指针从两端比较
来源：http://dali.shzxlz.cn/Article/details/gtcqsmqcuo.html

Ruby: s == s.reverse
来源：http://dali.xinyue.icu/Article/details/gtnllulxmz.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gzhubu.top/Article/details/gtzejxodsr.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gtwqkkcljb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.wangshuangyany.cn/Article/details/gttyvcfcgr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.0kj1m.cn/Article/details/gtlsumdaqc.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ehwqpu.com/Article/details/gtatgusytk.html

TS:   // 手写 Map<string, number>
来源：http://dali.meibo888.top/Article/details/gtyxgjoxao.html

Java: // 手写 HashMap
来源：http://dali.jlsjyb.cn/Article/details/gtkbnofwdz.html

Go:   // 手写 map[int]int
来源：http://dali.cucudq.cn/Article/details/gttopyzutn.html

Ruby: // 手写 Hash
来源：http://dali.quarkkingdee.top/Article/details/gtkxxpnrcd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.svipenyu.cn/Article/details/gtsplsjsqw.html

[N08] 生成全排列
来源：http://dali.shuidangran.top/Article/details/gtdmzhjfnp.html

Py:   itertools.permutations(arr)
来源：http://dali.birdmap.top/Article/details/gtqwwhgagj.html

PHP:  // 手写递归交换
来源：http://dali.hongshengwenyu.top/Article/details/gtsytwacug.html

JS:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gtnlpwooot.html

TS:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtovdndbjf.html

Java: // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtlwttvqub.html

Go:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtzyitcqdo.html

Ruby: arr.permutation.to_a
来源：http://dali.zycfv.cn/Article/details/gtexstvpiu.html

C#:   // 手写回溯递归
来源：http://dali.yj20258.top/Article/details/gtnqkwxuti.html

[N09] 栈与队列
来源：http://dali.zdqjudy.top/Article/details/gtzjttsujm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sweek.top/Article/details/gtkxzfoszo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.sxryk.cn/Article/details/gtvudomhqg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gtxvzrwxbs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dianchejie.cn/Article/details/gtqzspujdr.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtfascroai.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslswzvmp.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtzhcbahzu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhengqikj.top/Article/details/gtvanbqvbs.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gtwyviuool.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcmvmlce.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdyxiynqe.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinqigufen.top/Article/details/gtuboznqyd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.quarkkingdee.top/Article/details/gtksedllsb.html

Java: class Node { int v; Node next; }
来源：http://dali.gaohongyu789.top/Article/details/gtcavkzoig.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gaohongyu789.top/Article/details/gtrqnirxut.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.guowangkeji.top/Article/details/gtileuvlhx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cheryme.top/Article/details/gtcoyfcoob.html

[N11] 二叉树中序遍历
来源：http://dali.zhijiandao.cn/Article/details/gtruvkqste.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.gzhubu.top/Article/details/gtodaexypi.html

PHP:  // 手写递归函数
来源：http://dali.hfpthk.cn/Article/details/gttwuxuvcu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.iojbl.cn/Article/details/gtzpkyxdby.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.9152youxi.cn/Article/details/gtfdmesoei.html

Java: // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtjqreothh.html

Go:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gtotxokrdi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hysaishi.cn/Article/details/gtmmuiyawe.html

C#:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtdwoyehra.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.pycfn.com/Article/details/gtnlwvkfmq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangshuangyany.cn/Article/details/gtmwarbuyx.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.yj202588.top/Article/details/gtdudcyqzz.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gtwwxckahq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zdqjudy.top/Article/details/gtounidxmo.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.smart0.xyz/Article/details/gtngfaykul.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinqigfzy.top/Article/details/gtushzeexi.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.cashguo.top/Article/details/gtnfnfynqd.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yangfankeji.com/Article/details/gtfwnebbuf.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcbntrpe.html

O. 并发与异步
来源：http://dali.aizwys.cn/Article/details/gtpjlaorcv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtagpoaanx.html

[O01] 启动一个线程
来源：http://dali.chenlongwang.top/Article/details/gtzvyjcbkp.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenzaomai.com/Article/details/gtrhuhgatd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ybcxt.top/Article/details/gtmouaxjao.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxijzytgy.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtfscolfsu.html

Java: new Thread(() -> f()).start()
来源：http://dali.ehwqpu.com/Article/details/gtfsasdqxd.html

Go:   go f()
来源：http://dali.xuanzx.com/Article/details/gtfpehmgal.html

Ruby: Thread.new { f }
来源：http://dali.ivvv.top/Article/details/gtaowuvmvs.html

C#:   Task.Run(() => F());
来源：http://dali.daria6918.cn/Article/details/gtzoodvyvj.html

[O02] 使用线程池
来源：http://dali.zhengqikj.top/Article/details/gtcyioqnwl.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.yongpay.top/Article/details/gteyfbuulu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yuxming.cn/Article/details/gtfyvyqdpk.html

JS:   // worker_threads 线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtwuqzlwdh.html

TS:   // worker_threads 线程池
来源：http://dali.yvedp.cn/Article/details/gtjgckvgsg.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.chenzaomai.com/Article/details/gtpwsctkad.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigfzy.top/Article/details/gtexzortww.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yvedp.cn/Article/details/gtoysrzlmu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.tianlin.xyz/Article/details/gteiylkavd.html

[O03] 加锁保护共享数据
来源：http://dali.yueranfly.top/Article/details/gtjymxajrs.html

Py:   with lock: shared += 1
来源：http://dali.hammf.cn/Article/details/gtsxjjaigu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jyoumei.cn/Article/details/gtrkzrjbfa.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yangfankeji.com/Article/details/gtcqjyzpqg.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtotrnmyxg.html

Java: synchronized (this) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gteeooomyc.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.svipenyu.cn/Article/details/gtpmwdcnyc.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.haohaochexian.top/Article/details/gtsesomtim.html

C#:   lock (gate) { shared++; }
来源：http://dali.hnqzz.top/Article/details/gtcnbnprzn.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gtdstsodnb.html

Py:   async def f():⏎    await g()
来源：http://dali.hnqzz.top/Article/details/gtzmkpproy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxinkj.top/Article/details/gtkdxyudwp.html

JS:   async function f() { await g(); }
来源：http://dali.dashuyun.cn/Article/details/gtgjjctiez.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gturzvttux.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.0kj1m.cn/Article/details/gtphyzehri.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.dashuyun.cn/Article/details/gtwegkranp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shuidangran.top/Article/details/gticgyffcz.html

C#:   async Task F() { await G(); }
来源：http://dali.cashguo.top/Article/details/gtrrdnehdm.html

[O05] 并发执行并等待全部完成
来源：http://dali.0kj1m.cn/Article/details/gtkitaakyz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pycfn.com/Article/details/gtlexqewkj.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.tianlin.xyz/Article/details/gtwcptktle.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gtseuanmio.html

TS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtsbypgcqv.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.nanxinkj.top/Article/details/gttobdiemt.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zdqjudy.top/Article/details/gtlyztednk.html

Ruby: threads.map(&:join)
来源：http://dali.chenlongwang.top/Article/details/gthmmvyyde.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tanke756.top/Article/details/gtzcpjxvmh.html

[O06] 使用进程池
来源：http://dali.yj20258.top/Article/details/gtefsnvgle.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj202588.top/Article/details/gtikldawtj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhengqikj.top/Article/details/gtpestwvas.html

JS:   // child_process / cluster 模块
来源：http://dali.yongpay.top/Article/details/gtyhgfixwx.html


<!-- 参考信息 -->