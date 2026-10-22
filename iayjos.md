代发 wailian999

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsozdiaec.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.andypj.xyz/Article/details/gtqmwnvkeg.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.c1oappe.top/Article/details/gtidqzrnjx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.hnxiangtu.top/Article/details/gtdbfofbph.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.guannengcc.top/Article/details/gttigkxtxo.html

[L04] 设置超时
来源：http://dali.shuidangran.top/Article/details/gtpwaofpjy.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenlongwang.top/Article/details/gtmumgpdmt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hysaishi.cn/Article/details/gtfodxevoh.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj202588.top/Article/details/gtbqzdguyl.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cashguo.top/Article/details/gtnszrzwkr.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gtftqabucr.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.zycfv.cn/Article/details/gtxvpjjawv.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhongyouzk.top/Article/details/gteqrtkymw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jinqigfzy.top/Article/details/gthvimyfcz.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gtffhnrxgp.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.gaohongyu789.top/Article/details/gtopeghelg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.ybcxt.top/Article/details/gtynmtjjgt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gtlutkcias.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj202588.top/Article/details/gtzogqqfkw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yvedp.cn/Article/details/gtucfoucef.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.iojbl.cn/Article/details/gttjcizygf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yvedp.cn/Article/details/gttiomhyhh.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.fengsongda.top/Article/details/gtxddqbuii.html

[L06] 解析响应为 JSON
来源：http://dali.sysykeji.top/Article/details/gtnwvmywbe.html

Py:   resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedfkbxds.html

PHP:  json_decode($body, true);
来源：http://dali.havefunace.top/Article/details/gtvaosomde.html

JS:   await resp.json()
来源：http://dali.smart0.xyz/Article/details/gtmtdihsuf.html

TS:   await resp.json()
来源：http://dali.nanxinkj.top/Article/details/gthefkdszu.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gotoacloud.top/Article/details/gtbbqtcctp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.316326.xyz/Article/details/gtarsksliz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ybcxt.top/Article/details/gtgnjqnfdd.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.haohaochexian.top/Article/details/gtdinhzgrc.html

[L07] 处理 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtnozhnjkz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.ybcxt.top/Article/details/gtfjaxicmz.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.smart0.xyz/Article/details/gtwmoasodm.html

JS:   resp.ok;  resp.status
来源：http://dali.yvedp.cn/Article/details/gtgfmkqwqb.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gtgozquxgw.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gtpngnrvvq.html

Go:   resp.StatusCode
来源：http://dali.haohaochexian.top/Article/details/gtntwlppwu.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gtmnyitfrw.html

C#:   (int)resp.StatusCode
来源：http://dali.mhx1999.top/Article/details/gtghsjnhsd.html

[L08] 并发请求多个地址
来源：http://dali.chenjidiqi.icu/Article/details/gttiqpwfky.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.daxiang520.top/Article/details/gtxpiggeoo.html

PHP:  curl_multi_init() 系列
来源：http://dali.hysaishi.cn/Article/details/gtqieaaehu.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gtvsrplmgo.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nwbrower.top/Article/details/gtodsimqcn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.iojbl.cn/Article/details/gtsfmbdjoj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdrakybk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sysykeji.top/Article/details/gtfhllingu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gtwsmnucgb.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoqioznza.html

M. 命令行 / 进程 / 环境
来源：http://dali.jlsjyb.cn/Article/details/gtmiiaibus.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtmgzzcdmh.html

[M01] 读取命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtuejmgckh.html

Py:   sys.argv[1:]
来源：http://dali.jqgfzy.top/Article/details/gtzowluoej.html

PHP:  $argv;  $argc;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdofcaeq.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtwkpkmwom.html

TS:   process.argv.slice(2)
来源：http://dali.kuanghao11.cn/Article/details/gttishjqff.html

Java: args 数组（main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gtgoluwmdv.html

Go:   os.Args[1:]
来源：http://dali.nanxinkj.top/Article/details/gtpxosjfww.html

Ruby: ARGV
来源：http://dali.yj202588.top/Article/details/gtdnznmpww.html

C#:   args 数组（Main 方法参数）
来源：http://dali.pengpengdd.cyou/Article/details/gtwqckebgn.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gtanwfahoo.html

Py:   os.environ.get("HOME")
来源：http://dali.316326.xyz/Article/details/gtowgypyvs.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258.top/Article/details/gtxxymggtv.html

JS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gtaneoxwgr.html

TS:   process.env.HOME
来源：http://dali.jqgufenzy.top/Article/details/gtjbxyzhsb.html

Java: System.getenv("HOME")
来源：http://dali.shzxlz.cn/Article/details/gtmekgdlwi.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yvedp.cn/Article/details/gtttababnb.html

Ruby: ENV["HOME"]
来源：http://dali.xinyue.icu/Article/details/gtrdhkksds.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gtlkaxskwh.html

[M03] 执行外部命令
来源：http://dali.cqqwz.cn/Article/details/gtthwaywkb.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyrnwpzqy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.316326.xyz/Article/details/gtoxhxpnga.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtzdcidpsl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.guowangkeji.top/Article/details/gtzouhirfg.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shzxlz.cn/Article/details/gtetcbsiex.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.havefunace.top/Article/details/gtpgcsyhuu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fzhhl.top/Article/details/gtsgbekqai.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gtshhyoozs.html

[M04] 获取当前工作目录
来源：http://dali.vqdsnc.cn/Article/details/gtwsjsbhmi.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorcprnna.html

PHP:  getcwd();
来源：http://dali.jinqigufen.top/Article/details/gtjkctbbyb.html

JS:   process.cwd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtforcfhrh.html

TS:   process.cwd()
来源：http://dali.sxryk.cn/Article/details/gthhfgvbmt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhongyouzk.top/Article/details/gtknccfsst.html

Go:   os.Getwd()
来源：http://dali.dashuyun.cn/Article/details/gteinsfmke.html

Ruby: Dir.pwd
来源：http://dali.jqgufenzy.top/Article/details/gtycdelozc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.pycfn.com/Article/details/gtckppajnu.html

[M05] 设置退出码
来源：http://dali.yongpay.top/Article/details/gttlnkuxep.html

Py:   sys.exit(1)
来源：http://dali.ppjwa.cn/Article/details/gthaibonxh.html

PHP:  exit(1);
来源：http://dali.zhixingplan.top/Article/details/gtcwjunczj.html

JS:   process.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbpzucgf.html

TS:   process.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtvcqdjhje.html

Java: System.exit(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutefcjkt.html

Go:   os.Exit(1)
来源：http://dali.ppjwa.cn/Article/details/gtcrwgulbg.html

Ruby: exit 1
来源：http://dali.wangshuangyany.cn/Article/details/gttrhqpdrh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sxryk.cn/Article/details/gtjaivasmu.html

[M06] 向标准错误输出
来源：http://dali.hnqzz.top/Article/details/gtwrhbswjr.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj20258888.top/Article/details/gtnineeeto.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.daxiang520.top/Article/details/gtjcnzzlsf.html

JS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gtxileuafp.html

TS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gtxdugopim.html

Java: System.err.println("err")
来源：http://dali.cucudq.cn/Article/details/gtpxjsxvou.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gthzctipps.html

Ruby: warn "err"
来源：http://dali.ywan-chungtsiang.top/Article/details/gthypqzged.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xinyue.icu/Article/details/gtnjbqesuo.html

[M07] 判断是否为主入口
来源：http://dali.zycfv.cn/Article/details/gtlhufmnpm.html

Py:   if __name__ == "__main__":
来源：http://dali.xylfe.cn/Article/details/gtxpxbzuuy.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yueranfly.top/Article/details/gtgzekkonj.html

JS:   require.main === module
来源：http://dali.yanxiufei.cn/Article/details/gtctpnfcun.html

TS:   require.main === module
来源：http://dali.hongshengwenyu.top/Article/details/gtyfbzmzmr.html

Java: public static void main(String[] args)
来源：http://dali.haohaochexian.top/Article/details/gtcggvjzbr.html

Go:   func main()
来源：http://dali.jiagoushi.top/Article/details/gtsuhyfjwb.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ppjwa.cn/Article/details/gttpovyyiu.html

C#:   static void Main(string[] args)
来源：http://dali.hfpthk.cn/Article/details/gtugubvcdf.html

[M08] 获取系统与运行时信息
来源：http://dali.daria6918.cn/Article/details/gtdzkilwzd.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gtapbcbzkm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.bjfxy.top/Article/details/gtbhvmrueh.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gtrfnvkich.html

TS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gtfyiogjyi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ppjwa.cn/Article/details/gtiotygjep.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.fengsongda.top/Article/details/gtljvsvxon.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gtwmfhtcml.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoidoulkz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtsfmrxetn.html

N. 数据结构与算法
来源：http://dali.hammf.cn/Article/details/gteuaraqgk.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtnuvzaccc.html

[N01] 二分查找（有序数组）
来源：http://dali.sysykeji.top/Article/details/gtnakaxhmq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gtrumjteax.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.c1oappe.top/Article/details/gtlvxaghmj.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jiagoushi.top/Article/details/gtsuvxmvva.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gtkifhptwm.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtapoaxrdi.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gtkrepnxol.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hfpthk.cn/Article/details/gtlluzlgyz.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hywenlv.cn/Article/details/gtqbgmcrhf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaudlznog.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdegbhhsl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.snrcjt.cn/Article/details/gtxmehqyka.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigufen.top/Article/details/gtwxdxufnc.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.9152youxi.cn/Article/details/gtnnaakfqj.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.hnqzz.top/Article/details/gthpyotmhc.html

Go:   slices.Sort(arr)
来源：http://dali.zdqjudy.top/Article/details/gtazemskvi.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gtisxownab.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.shzxlz.cn/Article/details/gtkizeinrh.html

[N03] 快速排序（分治示例）
来源：http://dali.iojbl.cn/Article/details/gtlzcxlbrd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gogol.net.cn/Article/details/gtbroxgxwf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yj202588.top/Article/details/gttdwvprat.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jianghu66.top/Article/details/gtoyjfhsdt.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cqqwz.cn/Article/details/gtfhcwezdq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.tian-w.cn/Article/details/gtxblwxrae.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.birdmap.top/Article/details/gttcyfsgxi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenlongwang.top/Article/details/gtpfpcqueg.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gtovlsbija.html

[N04] 斐波那契数列
来源：http://dali.yueranfly.top/Article/details/gttuumbvly.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gtixnewadt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.feifeiyinyue.top/Article/details/gtsjtnstak.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gteldpajnb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuanzx.com/Article/details/gtbbibrjfp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xziqi.cn/Article/details/gthtxzapua.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.nwbrower.top/Article/details/gtrnfsnysj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jqgfzy.top/Article/details/gtnvqpsjum.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gtvuyizoqh.html

[N05] 最大公约数
来源：http://dali.sxryk.cn/Article/details/gtekhdjflk.html

Py:   math.gcd(a, b)
来源：http://dali.wangdashe.top/Article/details/gtcybjmvix.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.ehwqpu.com/Article/details/gtawvgrjrv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.meibo888.top/Article/details/gtrcfnatqq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shzxlz.cn/Article/details/gtdyhpvnap.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.sweek.top/Article/details/gtgucqiwrq.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzasumdno.html

Ruby: a.gcd(b)
来源：http://dali.c1oappe.top/Article/details/gtbhtdxyeo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.ppjwa.cn/Article/details/gtjlfnuvrq.html

[N06] 判断回文字符串
来源：http://dali.9152youxi.cn/Article/details/gtyezucbfl.html

Py:   s == s[::-1]
来源：http://dali.haohaochexian.top/Article/details/gturdctpep.html

PHP:  $s === strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtfzfzjequ.html

JS:   s === [...s].reverse().join("")
来源：http://dali.dashuyun.cn/Article/details/gtmtfopace.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtddjstmdi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.pycfn.com/Article/details/gtvkzocyay.html

Go:   // 双指针从两端比较
来源：http://dali.gaohongyu789.top/Article/details/gtlbgrhelu.html

Ruby: s == s.reverse
来源：http://dali.yueranfly.top/Article/details/gtonpjrlur.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gtiaukivke.html

[N07] 两数之和（返回下标）
来源：http://dali.xuanzx.com/Article/details/gtpclbnwnk.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sweek.top/Article/details/gttkfgohdg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.ivvv.top/Article/details/gtlsulkhlm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ybcxt.top/Article/details/gtyixjmhev.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangshuangyany.cn/Article/details/gtfaqmbheu.html

Java: // 手写 HashMap
来源：http://dali.shanyushiyangkeji.top/Article/details/gthscrdltq.html

Go:   // 手写 map[int]int
来源：http://dali.xylfe.cn/Article/details/gtoifeexpx.html

Ruby: // 手写 Hash
来源：http://dali.zhoulong.xyz/Article/details/gtvwilglox.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jianghu66.top/Article/details/gtvlobymbx.html

[N08] 生成全排列
来源：http://dali.xuanzx.com/Article/details/gtbncsfiic.html

Py:   itertools.permutations(arr)
来源：http://dali.zhixingplan.top/Article/details/gtjxaawgph.html

PHP:  // 手写递归交换
来源：http://dali.nanxinkj.top/Article/details/gtwyamwigm.html

JS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtmysdhetu.html

TS:   // 手写回溯递归
来源：http://dali.yueranfly.top/Article/details/gtltspcfhn.html

Java: // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtwuvppjzj.html

Go:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtbbcxfgcn.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxlcodno.html

C#:   // 手写回溯递归
来源：http://dali.cucudq.cn/Article/details/gtsysydayi.html

[N09] 栈与队列
来源：http://dali.daxiang520.top/Article/details/gtnimfjnpk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shzxlz.cn/Article/details/gtkbwrmlxc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aizwys.cn/Article/details/gtdszqfdgb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.wangdashe.top/Article/details/gtlqcsvzpp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gtosfmifpk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.hysaishi.cn/Article/details/gtfvfjvqjy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aizwys.cn/Article/details/gtmnqmvyuz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhijiandao.cn/Article/details/gttuulhdnj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.ppjwa.cn/Article/details/gtkvqfyqjg.html

[N10] 链表节点定义
来源：http://dali.andypj.xyz/Article/details/gticomifhv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jqgfzy.top/Article/details/gtxebhhjqu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gaohongyu789.top/Article/details/gtihidxlcj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cheryme.top/Article/details/gtskeledhg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cucudq.cn/Article/details/gtufuivamp.html

Java: class Node { int v; Node next; }
来源：http://dali.jiagoushi.top/Article/details/gtcsqzvmpw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.cdnleiting.top/Article/details/gtxrgtwwas.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklxjwmuk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.andypj.xyz/Article/details/gtwlxkzwjx.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gtxwokitpd.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jqgufenzy.top/Article/details/gtszipuhdd.html

PHP:  // 手写递归函数
来源：http://dali.snrcjt.cn/Article/details/gtgskmmrdt.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tanke756.top/Article/details/gtaxtfjzao.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgufenzy.top/Article/details/gtrjyxkczl.html

Java: // 手写递归
来源：http://dali.shuidangran.top/Article/details/gtqlzdxijg.html

Go:   // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtjgpewmci.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.quarkkingdee.top/Article/details/gtumbobvaf.html

C#:   // 手写递归
来源：http://dali.yanxiufei.cn/Article/details/gtauvagaiu.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hammf.cn/Article/details/gthhvmsxid.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hysaishi.cn/Article/details/gtoscmckqq.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangshuangyany.cn/Article/details/gtqfdecmer.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shzxlz.cn/Article/details/gtdmlhjisd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtzutfixwy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtdluznyls.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.daria6918.cn/Article/details/gtaewvoemz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jiagoushi.top/Article/details/gtdjsgmbol.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yuxming.cn/Article/details/gtfkiqqdxy.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtjsikfjkk.html

O. 并发与异步
来源：http://dali.smart0.xyz/Article/details/gtdtkbnywb.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtclgespha.html

[O01] 启动一个线程
来源：http://dali.birdmap.top/Article/details/gtcufezcld.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.vqdsnc.cn/Article/details/gtrjuqgujw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.svipenyu.cn/Article/details/gttmzncgom.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj20258888.top/Article/details/gtbtdegpzl.html

TS:   // 同 JS
来源：http://dali.gogol.net.cn/Article/details/gttoyaofgr.html

Java: new Thread(() -> f()).start()
来源：http://dali.nwbrower.top/Article/details/gtzidkclrj.html

Go:   go f()
来源：http://dali.bjfxy.top/Article/details/gtqxjucctj.html

Ruby: Thread.new { f }
来源：http://dali.zhiwuduotai.top/Article/details/gtxryvnrre.html

C#:   Task.Run(() => F());
来源：http://dali.yj202588.top/Article/details/gtdxjhvuvq.html

[O02] 使用线程池
来源：http://dali.chenlongwang.top/Article/details/gtrtlgmwve.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.tianlin.xyz/Article/details/gtskwcxgzq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hongshengwenyu.top/Article/details/gtwnhvieku.html

JS:   // worker_threads 线程池
来源：http://dali.feifeiyinyue.top/Article/details/gtprelymry.html

TS:   // worker_threads 线程池
来源：http://dali.wangdashe.top/Article/details/gtdlsnppkl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.birdmap.top/Article/details/gtzjdfhoyd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hywenlv.cn/Article/details/gtbcbjimcy.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xuetiantiany.cn/Article/details/gtqsqgzotc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxinkj.top/Article/details/gtughzukee.html

[O03] 加锁保护共享数据
来源：http://dali.snrcjt.cn/Article/details/gtdgunwrud.html

Py:   with lock: shared += 1
来源：http://dali.yvedp.cn/Article/details/gtyuntjqws.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yj20258888.top/Article/details/gtuuhncflg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.yj20258888.top/Article/details/gtdpoqfbyo.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gtseycyaid.html

Java: synchronized (this) { shared++; }
来源：http://dali.yanxiufei.cn/Article/details/gtclfofjqq.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yj202588.top/Article/details/gtxqdlrvwk.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.mhx1999.top/Article/details/gtujujsdho.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgfzy.top/Article/details/gtmbjldkph.html

[O04] 定义异步函数并等待
来源：http://dali.ehwqpu.com/Article/details/gtktkneywq.html

Py:   async def f():⏎    await g()
来源：http://dali.bjfxy.top/Article/details/gtlppdtamp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gtlompzcqz.html

JS:   async function f() { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjbvmhhid.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.gotoacloud.top/Article/details/gtefwpdske.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zycfv.cn/Article/details/gtnzjsygav.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.tanke756.top/Article/details/gtxtshnncm.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.pycfn.com/Article/details/gtzamuuwpe.html

C#:   async Task F() { await G(); }
来源：http://dali.xziqi.cn/Article/details/gtvpmwpvkn.html

[O05] 并发执行并等待全部完成
来源：http://dali.xuanzx.com/Article/details/gtziuoonch.html

Py:   asyncio.gather(*tasks)
来源：http://dali.zhixingplan.top/Article/details/gtayacubti.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.iojbl.cn/Article/details/gtsussqjge.html

JS:   await Promise.all(tasks)
来源：http://dali.c1oappe.top/Article/details/gtmabxrgav.html

TS:   await Promise.all(tasks)
来源：http://dali.xuanzx.com/Article/details/gtnhmrsssp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuanzx.com/Article/details/gtqgxypfhy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.aibaodan.cn/Article/details/gtxahtthdf.html

Ruby: threads.map(&:join)
来源：http://dali.haohaochexian.top/Article/details/gtggtolziw.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gtmaazkzof.html

[O06] 使用进程池
来源：http://dali.quarkkingdee.top/Article/details/gtquaqrzex.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.vqdsnc.cn/Article/details/gtahiajiyn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.chenzaomai.com/Article/details/gteystzoht.html

JS:   // child_process / cluster 模块
来源：http://dali.jyoumei.cn/Article/details/gtqrsfcdov.html

TS:   // child_process / cluster 模块
来源：http://dali.jlsjyb.cn/Article/details/gthqqarrof.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yuxming.cn/Article/details/gtetzxragr.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aizwys.cn/Article/details/gtpzkfgicj.html

Ruby: // fork 块
来源：http://dali.316326.xyz/Article/details/gtigzocgrm.html

C#:   Parallel.For
来源：http://dali.wangdashe.top/Article/details/gtugyznxye.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtksmktqlh.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gtfyuchppt.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtdhwulfel.html

[P01] 生成 UUID
来源：http://dali.fzhhl.top/Article/details/gtupdfaghh.html

Py:   str(uuid.uuid4())
来源：http://dali.yongpay.top/Article/details/gtnlcuxtjn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xinyue.icu/Article/details/gtkoxgxmqg.html

JS:   crypto.randomUUID()
来源：http://dali.9152youxi.cn/Article/details/gtdwgvroho.html


<!-- 参考信息 -->