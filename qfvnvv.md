代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.gogol.net.cn/Article/details/gtsooccnhv.html

[L04] 设置超时
来源：http://dali.hysaishi.cn/Article/details/gtluqvbgxr.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yvedp.cn/Article/details/gtrazdinzr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtrhxtqgzb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.iojbl.cn/Article/details/gtqbwgsavh.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gtkhurxvbo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jqgfzy.top/Article/details/gtvmthlssg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnxiangtu.top/Article/details/gtadplfibb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.yonumen.top/Article/details/gtrzltvcze.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.zycfv.cn/Article/details/gtilgljxuq.html

[L05] 上传文件（multipart）
来源：http://dali.bjfxy.top/Article/details/gtqodlwbgr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jiagoushi.top/Article/details/gtocwluich.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.smart0.xyz/Article/details/gtpnczxgpm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtmvvslxmv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gtapqdmyfb.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.sysykeji.top/Article/details/gtjhtunvtb.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuxming.cn/Article/details/gtqkmzmxqi.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxinkj.top/Article/details/gtoxughuvf.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.daria6918.cn/Article/details/gtjcoarihj.html

[L06] 解析响应为 JSON
来源：http://dali.9152youxi.cn/Article/details/gtrmxquvyg.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtrejtvffx.html

PHP:  json_decode($body, true);
来源：http://dali.c1oappe.top/Article/details/gtojgtzzlf.html

JS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gtfikzqnui.html

TS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtbgdlvmwx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.andypj.xyz/Article/details/gtxhzgaoum.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ppjwa.cn/Article/details/gtdyyubism.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gttzwcgqea.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gtpkbdorlh.html

[L07] 处理 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtydlsuxsu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jqgufenzy.top/Article/details/gtgrgiofug.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.gaohongyu789.top/Article/details/gtmsszldao.html

JS:   resp.ok;  resp.status
来源：http://dali.nanxuanxn.top/Article/details/gtjxmmbgyk.html

TS:   resp.ok;  resp.status
来源：http://dali.tian-w.cn/Article/details/gtdstsittg.html

Java: resp.statusCode()
来源：http://dali.shzxlz.cn/Article/details/gtrfseygca.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtmsvavupz.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gthwpbrxjs.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gtitrmziik.html

[L08] 并发请求多个地址
来源：http://dali.vqdsnc.cn/Article/details/gtmepjvzin.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.hongshengwenyu.top/Article/details/gtvosiyyex.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gtyredrnwf.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gtxbwdpnfl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtbzftfjpz.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hammf.cn/Article/details/gtiygcztwy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nanxuanxn.top/Article/details/gtllrlfsoy.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yanxiufei.cn/Article/details/gtqtkjqcfi.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.chenjidiqi.icu/Article/details/gterxuobmy.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtgvaubhgd.html

M. 命令行 / 进程 / 环境
来源：http://dali.0kj1m.cn/Article/details/gtuaoelmrk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtwpcttxqh.html

[M01] 读取命令行参数
来源：http://dali.havefunace.top/Article/details/gtxlzuwuka.html

Py:   sys.argv[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtcscknmzm.html

PHP:  $argv;  $argc;
来源：http://dali.tanke756.top/Article/details/gtqtxjowwz.html

JS:   process.argv.slice(2)
来源：http://dali.nwbrower.top/Article/details/gtbcwowtvt.html

TS:   process.argv.slice(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyctveeky.html

Java: args 数组（main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtsanzzwck.html

Go:   os.Args[1:]
来源：http://dali.vqdsnc.cn/Article/details/gturxkiqaf.html

Ruby: ARGV
来源：http://dali.yanxiufei.cn/Article/details/gthmrijbhl.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhixingplan.top/Article/details/gttjvpkrvq.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gtnyksngce.html

Py:   os.environ.get("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtmskfhncz.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gtarzyxxno.html

JS:   process.env.HOME
来源：http://dali.jinqigufen.top/Article/details/gtwiyrwlso.html

TS:   process.env.HOME
来源：http://dali.0kj1m.cn/Article/details/gtrpxzkaho.html

Java: System.getenv("HOME")
来源：http://dali.andypj.xyz/Article/details/gtkhxdinnl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xinyue.icu/Article/details/gtuzpuqrda.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gtpndiasxl.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nanxinkj.top/Article/details/gteygkbign.html

[M03] 执行外部命令
来源：http://dali.daxiang520.top/Article/details/gtwgkrjlmf.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.shzxlz.cn/Article/details/gtwszhcchg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.dianchejie.cn/Article/details/gtkgxwerlk.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gtqvjtcuon.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.xuetiantiany.cn/Article/details/gtuarlvxuw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.guannengcc.top/Article/details/gtsxfplavg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.snrcjt.cn/Article/details/gtkidswlfb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cucudq.cn/Article/details/gtukwzxpsb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gtusiiwnqv.html

[M04] 获取当前工作目录
来源：http://dali.zhoulong.xyz/Article/details/gtmlaiigqs.html

Py:   os.getcwd()
来源：http://dali.sufxvd.cn/Article/details/gtnkkpmugl.html

PHP:  getcwd();
来源：http://dali.hfpthk.cn/Article/details/gtwgkzxhae.html

JS:   process.cwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtszsztdjh.html

TS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtlcalncbp.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnhdwnkl.html

Go:   os.Getwd()
来源：http://dali.xuanzx.com/Article/details/gtidzkrvab.html

Ruby: Dir.pwd
来源：http://dali.guannengcc.top/Article/details/gtsbgxubui.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.iojbl.cn/Article/details/gtfusyztjx.html

[M05] 设置退出码
来源：http://dali.jqgfzy.top/Article/details/gtfpbtdoyt.html

Py:   sys.exit(1)
来源：http://dali.yj202588.top/Article/details/gtncrxenws.html

PHP:  exit(1);
来源：http://dali.zhiwuduotai.top/Article/details/gtrldwboyd.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtqelubega.html

TS:   process.exit(1)
来源：http://dali.ivvv.top/Article/details/gtckaguxyx.html

Java: System.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtmoaxmxeg.html

Go:   os.Exit(1)
来源：http://dali.hnqzz.top/Article/details/gtauprurxt.html

Ruby: exit 1
来源：http://dali.shanyushiyangtech.top/Article/details/gterwriunw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hfpthk.cn/Article/details/gtzkolfiqt.html

[M06] 向标准错误输出
来源：http://dali.xuanzx.com/Article/details/gtnvazczgv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gtbcgtxagn.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuanzhike.top/Article/details/gtecfsulxq.html

JS:   console.error("err")
来源：http://dali.nanxinkj.top/Article/details/gtkssmarwr.html

TS:   console.error("err")
来源：http://dali.nwbrower.top/Article/details/gtpcqbmpnh.html

Java: System.err.println("err")
来源：http://dali.hnxiangtu.top/Article/details/gtnebuwwqm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.tian-w.cn/Article/details/gtaljasokw.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gtpqefpbyj.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gtnrudzfdq.html

[M07] 判断是否为主入口
来源：http://dali.guowangkeji.top/Article/details/gtjgpcunel.html

Py:   if __name__ == "__main__":
来源：http://dali.ivvv.top/Article/details/gtzpjtgtag.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.hywenlv.cn/Article/details/gtcivsjtnz.html

JS:   require.main === module
来源：http://dali.ppjwa.cn/Article/details/gttptkegvi.html

TS:   require.main === module
来源：http://dali.birdmap.top/Article/details/gtaoejatez.html

Java: public static void main(String[] args)
来源：http://dali.shzxlz.cn/Article/details/gtjvrlhhev.html

Go:   func main()
来源：http://dali.fengsongda.top/Article/details/gtpalvjegc.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ybcxt.top/Article/details/gtvapsupcg.html

C#:   static void Main(string[] args)
来源：http://dali.zhijiandao.cn/Article/details/gtqbmawhmu.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgfzy.top/Article/details/gtyhlkesbj.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuxming.cn/Article/details/gtanrkhdix.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fengsongda.top/Article/details/gtwspupwso.html

JS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gtsslyvugc.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gthqindioo.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.yueranfly.top/Article/details/gtwuexswru.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhongyouzk.top/Article/details/gtnwfddfcz.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.cashguo.top/Article/details/gtkmjsecsb.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxeswebqy.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtlsecytid.html

N. 数据结构与算法
来源：http://dali.yueranfly.top/Article/details/gttdxddnvk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gthqkocaph.html

[N01] 二分查找（有序数组）
来源：http://dali.nwbrower.top/Article/details/gtzeglrise.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yj20258888.top/Article/details/gtdegohazh.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtbhkibkuu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxetzwmhg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tian-w.cn/Article/details/gtrwxfbabc.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yj202588.top/Article/details/gtfmfzvprq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtpeqwafrn.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.mhx1999.top/Article/details/gtpeipavio.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gtxugyhanr.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.snrcjt.cn/Article/details/gtuomjlsdt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtwblxvnoe.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fzhhl.top/Article/details/gtaglezzwd.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtqgmwhfqs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gtpqjsldlm.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.quarkkingdee.top/Article/details/gttcmutail.html

Go:   slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gtddepvbru.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gthvpccrxt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yj20258.top/Article/details/gtzpsvsyii.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gtslbmsrsi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.sufxvd.cn/Article/details/gthhkvjlyv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xziqi.cn/Article/details/gteoonyqeu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cheryme.top/Article/details/gtfuxwyhwo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gtbsptxubb.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtmixfwixu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.guowangkeji.top/Article/details/gtbmcwzxay.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.c1oappe.top/Article/details/gtcjykjnip.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.guowangkeji.top/Article/details/gtqphggria.html

[N04] 斐波那契数列
来源：http://dali.cqqwz.cn/Article/details/gtpnvottps.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtmqqqdrhu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ydzc1.top/Article/details/gtyhaoobxy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.c1oappe.top/Article/details/gtpvjhtsfp.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtzhigxffw.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xylfe.cn/Article/details/gteyoulrvy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhijiandao.cn/Article/details/gtliuuyqxv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.andypj.xyz/Article/details/gtcqtubbsv.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zhoulong.xyz/Article/details/gtvjojmkaa.html

[N05] 最大公约数
来源：http://dali.gotoacloud.top/Article/details/gtpeemdzyz.html

Py:   math.gcd(a, b)
来源：http://dali.sweek.top/Article/details/gtdodnicdo.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sweek.top/Article/details/gtqnahbwao.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzeckjaia.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gtrwuqhrse.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpmanktw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.jinqigfzy.top/Article/details/gtaedplath.html

Ruby: a.gcd(b)
来源：http://dali.zycfv.cn/Article/details/gtwqsgywnn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cheryme.top/Article/details/gtahqytxeb.html

[N06] 判断回文字符串
来源：http://dali.xylfe.cn/Article/details/gtpnzjjiur.html

Py:   s == s[::-1]
来源：http://dali.jianghu66.top/Article/details/gtxbdrzlnf.html

PHP:  $s === strrev($s);
来源：http://dali.jianghu66.top/Article/details/gthaybaejz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtfasalprj.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gtdcizknds.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.andypj.xyz/Article/details/gttaullrtn.html

Go:   // 双指针从两端比较
来源：http://dali.xinyue.icu/Article/details/gtlldlquzw.html

Ruby: s == s.reverse
来源：http://dali.cdnleiting.top/Article/details/gtenazuoav.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtfshrtmww.html

[N07] 两数之和（返回下标）
来源：http://dali.aizwys.cn/Article/details/gtcciotrrd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dianchejie.cn/Article/details/gtpdcpixsl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jlsjyb.cn/Article/details/gtqcyhtyzl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.gogol.net.cn/Article/details/gtqnvorrfl.html

TS:   // 手写 Map<string, number>
来源：http://dali.jiagoushi.top/Article/details/gtzcgnwhzh.html

Java: // 手写 HashMap
来源：http://dali.chenjidiqi.icu/Article/details/gtknitthgh.html

Go:   // 手写 map[int]int
来源：http://dali.ehwqpu.com/Article/details/gtxcbfhsmh.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gtpchrbxdq.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hammf.cn/Article/details/gtrqemxszb.html

[N08] 生成全排列
来源：http://dali.aizwys.cn/Article/details/gtyfavcvfz.html

Py:   itertools.permutations(arr)
来源：http://dali.jyoumei.cn/Article/details/gtgxnlutda.html

PHP:  // 手写递归交换
来源：http://dali.yuanzhike.top/Article/details/gthgdmhwjx.html

JS:   // 手写回溯递归
来源：http://dali.cashguo.top/Article/details/gtxcbmrief.html

TS:   // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtuemmqyyl.html

Java: // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gtntqqqqaw.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtewijmedu.html

Ruby: arr.permutation.to_a
来源：http://dali.tianlin.xyz/Article/details/gtrdheuomq.html

C#:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gtoajhhvwq.html

[N09] 栈与队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmnswnrj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aizwys.cn/Article/details/gtsbxutpaf.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtrcjctolc.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gtbwlwxfro.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jianghu66.top/Article/details/gtzkjduknb.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhixingplan.top/Article/details/gtfomjppae.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gtjbnlrqjw.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.jqgufenzy.top/Article/details/gtlqdqxufu.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.dianchejie.cn/Article/details/gtgtqiwujr.html

[N10] 链表节点定义
来源：http://dali.kuanghao11.cn/Article/details/gtxyuzkckj.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.birdmap.top/Article/details/gtwiqhttyt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.sufxvd.cn/Article/details/gtqqkgvhwp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jianghu66.top/Article/details/gtnneiltzt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.dianchejie.cn/Article/details/gtyoamfjsm.html

Java: class Node { int v; Node next; }
来源：http://dali.ehwqpu.com/Article/details/gtzmthnjjf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sysykeji.top/Article/details/gtfqmqgnei.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsqashmzp.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jinqigufen.top/Article/details/gtebdnhtxy.html

[N11] 二叉树中序遍历
来源：http://dali.pycfn.com/Article/details/gtxckuqfil.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenlongwang.top/Article/details/gtjvtifvml.html

PHP:  // 手写递归函数
来源：http://dali.gogol.net.cn/Article/details/gtireumxmk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj202588.top/Article/details/gtkiovvjcd.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.quarkkingdee.top/Article/details/gtnxaifnqb.html

Java: // 手写递归
来源：http://dali.jianghu66.top/Article/details/gtkbfibqwe.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtijdgjgqm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pengpengdd.cyou/Article/details/gtjfcapaei.html

C#:   // 手写递归
来源：http://dali.daria6918.cn/Article/details/gthzmnaexm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cashguo.top/Article/details/gtufknnbku.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.iojbl.cn/Article/details/gtbqxoycom.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sufxvd.cn/Article/details/gtmetlspoa.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gtcvsmnpgk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fengsongda.top/Article/details/gthvrpsvuz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gtrchahtmx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shangyingyoupin.top/Article/details/gtuoupgpdu.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtdacjylbb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gtwbhetnxq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtjyovwkaw.html

O. 并发与异步
来源：http://dali.nwbrower.top/Article/details/gthdpbtabl.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtzmozaflz.html

[O01] 启动一个线程
来源：http://dali.xuanzx.com/Article/details/gturtrujzk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.svipenyu.cn/Article/details/gtpvsutmxe.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenlongwang.top/Article/details/gtxrbpiiql.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ppjwa.cn/Article/details/gtxgdvyjsk.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gtaahdxvqa.html

Java: new Thread(() -> f()).start()
来源：http://dali.smart0.xyz/Article/details/gtoowtjzdy.html

Go:   go f()
来源：http://dali.pycfn.com/Article/details/gthbhdtjtx.html

Ruby: Thread.new { f }
来源：http://dali.sweek.top/Article/details/gtibktmubw.html

C#:   Task.Run(() => F());
来源：http://dali.sxryk.cn/Article/details/gtantznbvx.html

[O02] 使用线程池
来源：http://dali.mhx1999.top/Article/details/gtvnfxcpin.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.andypj.xyz/Article/details/gtibgtxyoy.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhixingplan.top/Article/details/gtocxaaobp.html

JS:   // worker_threads 线程池
来源：http://dali.fengsongda.top/Article/details/gteqfctdcn.html

TS:   // worker_threads 线程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbajzwjty.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jianghu66.top/Article/details/gtbmajmszg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuanzx.com/Article/details/gtdhswzfea.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zycfv.cn/Article/details/gtizatgyqk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yueranfly.top/Article/details/gthdrzulot.html

[O03] 加锁保护共享数据
来源：http://dali.sweek.top/Article/details/gthmokqhbp.html

Py:   with lock: shared += 1
来源：http://dali.hfpthk.cn/Article/details/gtltonvuij.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yongpay.top/Article/details/gtmdruxkcg.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenzaomai.com/Article/details/gtuyosiriy.html

TS:   // 同 JS
来源：http://dali.fzhhl.top/Article/details/gtfyfnnqri.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhoulong.xyz/Article/details/gtgxzmgwre.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yongpay.top/Article/details/gtsfifqvmd.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.smart0.xyz/Article/details/gtbmzggirp.html

C#:   lock (gate) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtglzdnpim.html

[O04] 定义异步函数并等待
来源：http://dali.xuetiantiany.cn/Article/details/gtaukrmsmg.html

Py:   async def f():⏎    await g()
来源：http://dali.316326.xyz/Article/details/gtcyoowsdy.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhoulong.xyz/Article/details/gtnhjdsicc.html

JS:   async function f() { await g(); }
来源：http://dali.yuxming.cn/Article/details/gtdrrbpkir.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.feifeiyinyue.top/Article/details/gtqglzjbho.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuetiantiany.cn/Article/details/gtmfgoxywn.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuanzx.com/Article/details/gtvuilstdr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ydzc1.top/Article/details/gtdzotzmcl.html

C#:   async Task F() { await G(); }
来源：http://dali.0kj1m.cn/Article/details/gtcpxmlvqb.html

[O05] 并发执行并等待全部完成
来源：http://dali.ehwqpu.com/Article/details/gtzvkaxvmz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jinqigufen.top/Article/details/gtiytfwfwv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zhiwuduotai.top/Article/details/gtqsbhrvei.html

JS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gtjwqnroue.html

TS:   await Promise.all(tasks)
来源：http://dali.jianghu66.top/Article/details/gtwbjwffxa.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shangyingyoupin.top/Article/details/gtpbwqtiej.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gtsfqxkuvo.html

Ruby: threads.map(&:join)
来源：http://dali.9152youxi.cn/Article/details/gttkweaxro.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.cqqwz.cn/Article/details/gtirbexaym.html

[O06] 使用进程池
来源：http://dali.xuanzx.com/Article/details/gtedeyzann.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hywenlv.cn/Article/details/gtycxlbpmo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.tianlin.xyz/Article/details/gttcjkgrjp.html

JS:   // child_process / cluster 模块
来源：http://dali.jinqigfzy.top/Article/details/gtohdinnja.html

TS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtdwozhapm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.meibo888.top/Article/details/gtjpdcndet.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sweek.top/Article/details/gtbzqviswa.html

Ruby: // fork 块
来源：http://dali.chenzaomai.com/Article/details/gtoggzqltt.html

C#:   Parallel.For
来源：http://dali.ybcxt.top/Article/details/gtrarvdeai.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtndusybtr.html

P. 常用工具函数
来源：http://dali.ppjwa.cn/Article/details/gtxoxggzdj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtbyajnmpn.html

[P01] 生成 UUID
来源：http://dali.zhongyouzk.top/Article/details/gtnxprzrzn.html

Py:   str(uuid.uuid4())
来源：http://dali.aibaodan.cn/Article/details/gtzusowojk.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmeiijae.html

JS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gtjeepqxwz.html

TS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtwasvfuqf.html

Java: UUID.randomUUID().toString()
来源：http://dali.svipenyu.cn/Article/details/gticrlttjc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xylfe.cn/Article/details/gtvwymjjdy.html

Ruby: SecureRandom.uuid
来源：http://dali.tanke756.top/Article/details/gtfgwbvykl.html


<!-- 参考信息 -->