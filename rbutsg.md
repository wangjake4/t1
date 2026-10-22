代发 wailian999

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.dashuyun.cn/Article/details/gtnsflimre.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.fengsongda.top/Article/details/gtyvjdikcv.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.hongshengwenyu.top/Article/details/gtfdqkpzbm.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.cdnleiting.top/Article/details/gtmbgczxlm.html

[L03] 设置自定义请求头
来源：http://dali.cheryme.top/Article/details/gttlgotrfa.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yj20258888.top/Article/details/gtopigufqe.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sweek.top/Article/details/gtbcoowwid.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.fengsongda.top/Article/details/gtpdpmkbtb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.pycfn.com/Article/details/gterxgucpl.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.ppjwa.cn/Article/details/gtrwnveffg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zycfv.cn/Article/details/gtzcriuacu.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.dashuyun.cn/Article/details/gtrfkbcohv.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.wangdashe.top/Article/details/gtllyqnjjc.html

[L04] 设置超时
来源：http://dali.guannengcc.top/Article/details/gtieultqti.html

Py:   requests.get(url, timeout=5)
来源：http://dali.wangshuangyany.cn/Article/details/gtigbswboh.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbxpwcst.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.wangdashe.top/Article/details/gtkrhqenaa.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.316326.xyz/Article/details/gtchkidzwe.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhiwuduotai.top/Article/details/gtmyisjlwv.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jinqigufen.top/Article/details/gtibteisnn.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.mhx1999.top/Article/details/gtkftnnsfn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.chenzaomai.com/Article/details/gtjfkdwlpw.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gtbjayelkv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hammf.cn/Article/details/gtbwuhlpss.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhoulong.xyz/Article/details/gtzgrvkyow.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtlvcksfwj.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhijiandao.cn/Article/details/gtxlmxrgjt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.pycfn.com/Article/details/gtvszenybd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.svipenyu.cn/Article/details/gtbnkhxrat.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.dianchejie.cn/Article/details/gtqvkwmfrn.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hammf.cn/Article/details/gttvvcklky.html

[L06] 解析响应为 JSON
来源：http://dali.nanxinkj.top/Article/details/gtkygpeuih.html

Py:   resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gtwgvacply.html

PHP:  json_decode($body, true);
来源：http://dali.jinqigufen.top/Article/details/gtywgujrmy.html

JS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtlqfnvqna.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnawsslqs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.daxiang520.top/Article/details/gtzwzflkpk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.zycfv.cn/Article/details/gtqyuflbnv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.xylfe.cn/Article/details/gtbtlfauxk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnqzz.top/Article/details/gtdnmsgqig.html

[L07] 处理 HTTP 状态码
来源：http://dali.guannengcc.top/Article/details/gtypzrowbr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shzxlz.cn/Article/details/gtkpqoezfm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dashuyun.cn/Article/details/gtlpyftngb.html

JS:   resp.ok;  resp.status
来源：http://dali.jiagoushi.top/Article/details/gtaslmpvcc.html

TS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtscmnvsoy.html

Java: resp.statusCode()
来源：http://dali.hywenlv.cn/Article/details/gtdfrhsnnf.html

Go:   resp.StatusCode
来源：http://dali.guannengcc.top/Article/details/gtmliretrb.html

Ruby: resp.code.to_i
来源：http://dali.shuidangran.top/Article/details/gtegngsucq.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gtdvztayis.html

[L08] 并发请求多个地址
来源：http://dali.zhixingplan.top/Article/details/gtwddrezee.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aizwys.cn/Article/details/gtodrfpuwp.html

PHP:  curl_multi_init() 系列
来源：http://dali.pycfn.com/Article/details/gtuzwvcynp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gthryuocdv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yanxiufei.cn/Article/details/gtkcqukpve.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zdqjudy.top/Article/details/gtcdnncoqx.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.daxiang520.top/Article/details/gtpqkzwpjs.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yongpay.top/Article/details/gtbxpccwqu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gtahtaanig.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtsldzpogx.html

M. 命令行 / 进程 / 环境
来源：http://dali.daria6918.cn/Article/details/gtqidmjkzq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxeiqodvg.html

[M01] 读取命令行参数
来源：http://dali.yj20258.top/Article/details/gtoaisjyns.html

Py:   sys.argv[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawwydxvj.html

PHP:  $argv;  $argc;
来源：http://dali.sweek.top/Article/details/gttytrqcda.html

JS:   process.argv.slice(2)
来源：http://dali.mhx1999.top/Article/details/gtvsajrjab.html

TS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gtnnyhevsc.html

Java: args 数组（main 方法参数）
来源：http://dali.jiagoushi.top/Article/details/gtnnjpndja.html

Go:   os.Args[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gtwumipscb.html

Ruby: ARGV
来源：http://dali.tian-w.cn/Article/details/gtmfmsdlxt.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtabscxxxt.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gtdwzdxjln.html

Py:   os.environ.get("HOME")
来源：http://dali.316326.xyz/Article/details/gtijuqxfwt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zycfv.cn/Article/details/gthuqxfytc.html

JS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gtuumvhvde.html

TS:   process.env.HOME
来源：http://dali.hammf.cn/Article/details/gtapxwbhjt.html

Java: System.getenv("HOME")
来源：http://dali.cashguo.top/Article/details/gtrxpkyvrj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgufenzy.top/Article/details/gtxcnhfsiu.html

Ruby: ENV["HOME"]
来源：http://dali.bjfxy.top/Article/details/gthndhotir.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gtywdxymgu.html

[M03] 执行外部命令
来源：http://dali.chenjidiqi.icu/Article/details/gtmbzfuzmj.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.svipenyu.cn/Article/details/gtkntbvqkn.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tianlin.xyz/Article/details/gtxqssjgsk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscvxrebx.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtjaturuoo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.kuanghao11.cn/Article/details/gtwozqkpza.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqtonqlx.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jlsjyb.cn/Article/details/gtjsdmzmep.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpzazjmup.html

[M04] 获取当前工作目录
来源：http://dali.cashguo.top/Article/details/gtxylpjcvt.html

Py:   os.getcwd()
来源：http://dali.aibaodan.cn/Article/details/gtlshyjqsq.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gtaxypbcef.html

JS:   process.cwd()
来源：http://dali.hongshengwenyu.top/Article/details/gtlmhxsbbw.html

TS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gtwybfefla.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.redwolf501.top/Article/details/gtyedblmkx.html

Go:   os.Getwd()
来源：http://dali.zhiwuduotai.top/Article/details/gtcgsunnyx.html

Ruby: Dir.pwd
来源：http://dali.zdqjudy.top/Article/details/gtzomwmvqt.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.ppjwa.cn/Article/details/gtlccijfbn.html

[M05] 设置退出码
来源：http://dali.yangfankeji.com/Article/details/gtuquqlino.html

Py:   sys.exit(1)
来源：http://dali.sysykeji.top/Article/details/gtkmrymjea.html

PHP:  exit(1);
来源：http://dali.smart0.xyz/Article/details/gtbsoiyhwp.html

JS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gtmpjxzfsv.html

TS:   process.exit(1)
来源：http://dali.fengsongda.top/Article/details/gtrywyiorn.html

Java: System.exit(1)
来源：http://dali.mhx1999.top/Article/details/gttrwpmpwi.html

Go:   os.Exit(1)
来源：http://dali.cucudq.cn/Article/details/gtfipgeghk.html

Ruby: exit 1
来源：http://dali.xziqi.cn/Article/details/gtsyxtjyzo.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zhijiandao.cn/Article/details/gtjybwwzii.html

[M06] 向标准错误输出
来源：http://dali.yanxiufei.cn/Article/details/gtagkjcgjc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gtwevepwja.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.pycfn.com/Article/details/gtarmrgege.html

JS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gtssqcjikl.html

TS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtvepnyxzk.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gtqxleblvy.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jqgfzy.top/Article/details/gthtrkamlu.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gtgegqbwia.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gtpjkjlueb.html

[M07] 判断是否为主入口
来源：http://dali.jinqigfzy.top/Article/details/gtujnqffxs.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gtczipxbje.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenlongwang.top/Article/details/gtxefsxcmk.html

JS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtxmabiegt.html

TS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gtghuijmde.html

Java: public static void main(String[] args)
来源：http://dali.yanxiufei.cn/Article/details/gtfdjmnxac.html

Go:   func main()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzwroigr.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhiwuduotai.top/Article/details/gtxjfngtwv.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gtgxntardw.html

[M08] 获取系统与运行时信息
来源：http://dali.jlsjyb.cn/Article/details/gtdjqfmtbi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnugxocsi.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.xuetiantiany.cn/Article/details/gtikvszovm.html

JS:   process.platform;  process.version
来源：http://dali.zdqjudy.top/Article/details/gtpidjdyoy.html

TS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtaguflohu.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gtdmahkfvl.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhixingplan.top/Article/details/gtvnbteytx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.birdmap.top/Article/details/gtnumbskds.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjzmwfyc.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtzxidkzvm.html

N. 数据结构与算法
来源：http://dali.0kj1m.cn/Article/details/gttrpjdtkd.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtllimzrwb.html

[N01] 二分查找（有序数组）
来源：http://dali.xylfe.cn/Article/details/gteiweispj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guannengcc.top/Article/details/gtgwnipnqf.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pycfn.com/Article/details/gtxsnsavwy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.sufxvd.cn/Article/details/gtutzsnxpp.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gtgzceabfc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrczqhkr.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gtiumqbncp.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xuanzx.com/Article/details/gtrtxbjhxz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtnesefinj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guowangkeji.top/Article/details/gtgmnaayjy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gtxjundbvu.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.cdnleiting.top/Article/details/gtltgzcnuk.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtatlqvrxh.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtwdckjion.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.svipenyu.cn/Article/details/gtsskibhua.html

Go:   slices.Sort(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtktpeqiij.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gtiszgtnjn.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhengqikj.top/Article/details/gtmmaykxnw.html

[N03] 快速排序（分治示例）
来源：http://dali.jlsjyb.cn/Article/details/gtrkvjlzes.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jianghu66.top/Article/details/gtvpclikuz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxinkj.top/Article/details/gtafrjmzss.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtnpnlnzfh.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.snrcjt.cn/Article/details/gtzfkguyim.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.316326.xyz/Article/details/gtnbpdwhqt.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hongshengwenyu.top/Article/details/gtlincsabs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yj20258.top/Article/details/gtvpavoojj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guowangkeji.top/Article/details/gthdrsexsn.html

[N04] 斐波那契数列
来源：http://dali.tanke756.top/Article/details/gtnelkbspn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gtogascplu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ivvv.top/Article/details/gthhhpgofc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.dianchejie.cn/Article/details/gtutuweekh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xylfe.cn/Article/details/gtezqkduqb.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj202588.top/Article/details/gtmfstysqr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xinyue.icu/Article/details/gtozngqbga.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zycfv.cn/Article/details/gthnojcpyz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtciqvqpab.html

[N05] 最大公约数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwiifqfy.html

Py:   math.gcd(a, b)
来源：http://dali.nanxinkj.top/Article/details/gttudooefy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.haohaochexian.top/Article/details/gtyswmbces.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtnhyfdyph.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gtemnmtrih.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.wangdashe.top/Article/details/gtjwjmzfxb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gogol.net.cn/Article/details/gthurdqfri.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gtvlfcbqag.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpdjobft.html

[N06] 判断回文字符串
来源：http://dali.ehwqpu.com/Article/details/gtbtluhzzf.html

Py:   s == s[::-1]
来源：http://dali.xylfe.cn/Article/details/gtlsrgnsvn.html

PHP:  $s === strrev($s);
来源：http://dali.svipenyu.cn/Article/details/gtrvgwdgyf.html

JS:   s === [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gtskkllgjn.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gtpxwlkaha.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnqzz.top/Article/details/gtlxkduoao.html

Go:   // 双指针从两端比较
来源：http://dali.smart0.xyz/Article/details/gtapbbtjdy.html

Ruby: s == s.reverse
来源：http://dali.gogol.net.cn/Article/details/gtyddawdxl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtwoppxstr.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gtlorurrcc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.aibaodan.cn/Article/details/gtdkyvhpys.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.andypj.xyz/Article/details/gthltajips.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.hnqzz.top/Article/details/gthodkfolx.html

TS:   // 手写 Map<string, number>
来源：http://dali.gzhubu.top/Article/details/gtcpohjayt.html

Java: // 手写 HashMap
来源：http://dali.shangyingyoupin.top/Article/details/gthhlkfysa.html

Go:   // 手写 map[int]int
来源：http://dali.hongshengwenyu.top/Article/details/gtebmrcejq.html

Ruby: // 手写 Hash
来源：http://dali.yanxiufei.cn/Article/details/gtjwbckmpb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhijiandao.cn/Article/details/gtzrhkreyn.html

[N08] 生成全排列
来源：http://dali.nanxinkj.top/Article/details/gtfkyivfgl.html

Py:   itertools.permutations(arr)
来源：http://dali.nwbrower.top/Article/details/gtiwffuspi.html

PHP:  // 手写递归交换
来源：http://dali.shuidangran.top/Article/details/gtkvtcuekt.html

JS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtjtxeyutn.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtwnbauqck.html

Java: // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gtanwmbfen.html

Go:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtjepfcxnd.html

Ruby: arr.permutation.to_a
来源：http://dali.hnqzz.top/Article/details/gtmvsqeloo.html

C#:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtjxsxekqd.html

[N09] 栈与队列
来源：http://dali.smart0.xyz/Article/details/gthedlhycx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yangfankeji.com/Article/details/gtdcaucjbt.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pycfn.com/Article/details/gtcdlmngbq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gtzbllkdhv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.aibaodan.cn/Article/details/gtegylrjur.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jianghu66.top/Article/details/gtimxsaswn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ybcxt.top/Article/details/gtofquinmd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cashguo.top/Article/details/gtbtfoatrm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gotoacloud.top/Article/details/gtkiclzzpv.html

[N10] 链表节点定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgspomglx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shzxlz.cn/Article/details/gttqfyzdpu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yuanzhike.top/Article/details/gtwskxvfcf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.bjfxy.top/Article/details/gtvyikptvd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.meibo888.top/Article/details/gtglqheaee.html

Java: class Node { int v; Node next; }
来源：http://dali.zhixingplan.top/Article/details/gtyvxzydoo.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gotoacloud.top/Article/details/gttzdooqme.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tianlin.xyz/Article/details/gtdqsytesl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaiwvvorh.html

[N11] 二叉树中序遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtkfsisdug.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ydzc1.top/Article/details/gtvtlydkmq.html

PHP:  // 手写递归函数
来源：http://dali.fzhhl.top/Article/details/gtbmvfrtcn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.daxiang520.top/Article/details/gtlscrdrpb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xinyue.icu/Article/details/gtschroyut.html

Java: // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gtjdfnhpms.html

Go:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gtsoqaylyj.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.gotoacloud.top/Article/details/gtcqarqxju.html

C#:   // 手写递归
来源：http://dali.tianlin.xyz/Article/details/gtmrdjzfbk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gaohongyu789.top/Article/details/gtipmzmcec.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hywenlv.cn/Article/details/gtxmfbfjwg.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cdnleiting.top/Article/details/gtzvqvyyqp.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmplvqov.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtxmlsarna.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gtfysvafkp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhijiandao.cn/Article/details/gtktighsqn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.fengsongda.top/Article/details/gtgmaricfq.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtzreyjogr.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrypjpti.html

O. 并发与异步
来源：http://dali.jyoumei.cn/Article/details/gtzywgfcqf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtafjsmgnf.html

[O01] 启动一个线程
来源：http://dali.shanyushiyangtech.top/Article/details/gtqiqqwyds.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gtnnomquqw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.pengpengdd.cyou/Article/details/gtdvbjpxbc.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.hongshengwenyu.top/Article/details/gtwmbjnfnb.html

TS:   // 同 JS
来源：http://dali.jyoumei.cn/Article/details/gtvgzmbvee.html

Java: new Thread(() -> f()).start()
来源：http://dali.cheryme.top/Article/details/gttuldclpc.html

Go:   go f()
来源：http://dali.xuetiantiany.cn/Article/details/gtmspnycpz.html

Ruby: Thread.new { f }
来源：http://dali.havefunace.top/Article/details/gtkobuwpid.html

C#:   Task.Run(() => F());
来源：http://dali.birdmap.top/Article/details/gtdsylqmbm.html

[O02] 使用线程池
来源：http://dali.316326.xyz/Article/details/gtmonplzyn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gtrpylybto.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gtziegavla.html

JS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gtnmwbigmx.html

TS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gtidmoftbs.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ppjwa.cn/Article/details/gtrazfucbv.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hysaishi.cn/Article/details/gtyejsoiob.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yanxiufei.cn/Article/details/gtlyeltyak.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jianghu66.top/Article/details/gtotywshbq.html

[O03] 加锁保护共享数据
来源：http://dali.daria6918.cn/Article/details/gtauaxnqxr.html

Py:   with lock: shared += 1
来源：http://dali.tanke756.top/Article/details/gtqzuxdoif.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.feifeiyinyue.top/Article/details/gttdkoykfp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xuanzx.com/Article/details/gtudcittdt.html

TS:   // 同 JS
来源：http://dali.cqqwz.cn/Article/details/gtpuvkbpal.html

Java: synchronized (this) { shared++; }
来源：http://dali.yj20258.top/Article/details/gtxgacmxtf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.jqgufenzy.top/Article/details/gtpzqorbxj.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yangfankeji.com/Article/details/gtpzjlkock.html

C#:   lock (gate) { shared++; }
来源：http://dali.guannengcc.top/Article/details/gtusetssue.html

[O04] 定义异步函数并等待
来源：http://dali.yongpay.top/Article/details/gtsxwgrebl.html

Py:   async def f():⏎    await g()
来源：http://dali.jinqigfzy.top/Article/details/gtuutmuxcu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcghgfmgh.html

JS:   async function f() { await g(); }
来源：http://dali.xuanzx.com/Article/details/gtnpdldgyk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhijiandao.cn/Article/details/gtktrnckhm.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuanzx.com/Article/details/gtqngtmdgw.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yangfankeji.com/Article/details/gtpsubacjk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.xziqi.cn/Article/details/gtxctennhl.html

C#:   async Task F() { await G(); }
来源：http://dali.nwbrower.top/Article/details/gtnzmghifo.html

[O05] 并发执行并等待全部完成
来源：http://dali.dianchejie.cn/Article/details/gthzjsgveh.html

Py:   asyncio.gather(*tasks)
来源：http://dali.iojbl.cn/Article/details/gtllcoxrfh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nwbrower.top/Article/details/gtiubdarnh.html

JS:   await Promise.all(tasks)
来源：http://dali.sysykeji.top/Article/details/gtxrtkwmtq.html

TS:   await Promise.all(tasks)
来源：http://dali.hnxiangtu.top/Article/details/gtnoiikgew.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cucudq.cn/Article/details/gtgndvlyri.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hfpthk.cn/Article/details/gtbrjsmpgr.html

Ruby: threads.map(&:join)
来源：http://dali.havefunace.top/Article/details/gtucpkssas.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.wangshuangyany.cn/Article/details/gtipnhulyl.html

[O06] 使用进程池
来源：http://dali.fengsongda.top/Article/details/gtndmmuwjx.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cqqwz.cn/Article/details/gtmshcjffs.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangshuangyany.cn/Article/details/gtjkhulodt.html

JS:   // child_process / cluster 模块
来源：http://dali.gotoacloud.top/Article/details/gtepnucgwk.html

TS:   // child_process / cluster 模块
来源：http://dali.yangfankeji.com/Article/details/gtfbszrkni.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqapefkqp.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhijiandao.cn/Article/details/gtvjhqitci.html

Ruby: // fork 块
来源：http://dali.tianlin.xyz/Article/details/gtrszxpdid.html


<!-- 参考信息 -->