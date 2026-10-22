代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkuoyqfbt.html

[L04] 设置超时
来源：http://dali.cheryme.top/Article/details/gtdjqgjdyv.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ivvv.top/Article/details/gtzeqxacmn.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.hongshengwenyu.top/Article/details/gtkkktridu.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gzhubu.top/Article/details/gtejwywvrp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xylfe.cn/Article/details/gtovuqsaaf.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hysaishi.cn/Article/details/gtxtisdkiz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.wangshuangyany.cn/Article/details/gtuwrrjfdm.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cucudq.cn/Article/details/gtgbqupnwf.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.quarkkingdee.top/Article/details/gtzvhaxabh.html

[L05] 上传文件（multipart）
来源：http://dali.yueranfly.top/Article/details/gtcuvggvnt.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hnqzz.top/Article/details/gtficbsyhs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.xuetiantiany.cn/Article/details/gtksjandxh.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtvfnlvyip.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gtkuviqjps.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ehwqpu.com/Article/details/gtkmluqxuw.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.chenjidiqi.icu/Article/details/gtqndnrqyu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daxiang520.top/Article/details/gtwvxjnzbg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtxjzpilyu.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gtddxofxox.html

Py:   resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtagqcvqav.html

PHP:  json_decode($body, true);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgkmsmqap.html

JS:   await resp.json()
来源：http://dali.316326.xyz/Article/details/gticmvdpyx.html

TS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gtfkffhuha.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.shangyingyoupin.top/Article/details/gtuyftidqh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ybcxt.top/Article/details/gtfleqmtll.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jianghu66.top/Article/details/gtextpfptm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.yuanzhike.top/Article/details/gtbsgzgxil.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgkscmaf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.fengsongda.top/Article/details/gttvbbsfio.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cucudq.cn/Article/details/gthuhnqexp.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtzqdolmkw.html

TS:   resp.ok;  resp.status
来源：http://dali.wangdashe.top/Article/details/gtfuogldtx.html

Java: resp.statusCode()
来源：http://dali.xuanzx.com/Article/details/gtxckqdpzp.html

Go:   resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gtdzzuseqw.html

Ruby: resp.code.to_i
来源：http://dali.quarkkingdee.top/Article/details/gthvxzjrnk.html

C#:   (int)resp.StatusCode
来源：http://dali.ppjwa.cn/Article/details/gtxldulvzl.html

[L08] 并发请求多个地址
来源：http://dali.jqgufenzy.top/Article/details/gtutpgmvcf.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sweek.top/Article/details/gtuiyqieio.html

PHP:  curl_multi_init() 系列
来源：http://dali.smart0.xyz/Article/details/gtssmyzcof.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xuanzx.com/Article/details/gtlmgihmme.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cucudq.cn/Article/details/gtmosgumjd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hongshengwenyu.top/Article/details/gtfdkntizu.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yvedp.cn/Article/details/gtqmootkuj.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.sysykeji.top/Article/details/gtvehwocvj.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jqgfzy.top/Article/details/gtvxpupwkk.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtpxmkozlc.html

M. 命令行 / 进程 / 环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkseqllfo.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtqzosuppf.html

[M01] 读取命令行参数
来源：http://dali.meibo888.top/Article/details/gtmhoklmvd.html

Py:   sys.argv[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylvmfdgh.html

PHP:  $argv;  $argc;
来源：http://dali.xuetiantiany.cn/Article/details/gtthojfovb.html

JS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gtqcqtrgjp.html

TS:   process.argv.slice(2)
来源：http://dali.gogol.net.cn/Article/details/gtwtmnrnkc.html

Java: args 数组（main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtyaizptdf.html

Go:   os.Args[1:]
来源：http://dali.jqgufenzy.top/Article/details/gtjklqwiav.html

Ruby: ARGV
来源：http://dali.zdqjudy.top/Article/details/gtstjaaajm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.316326.xyz/Article/details/gtpyiwyarz.html

[M02] 读取环境变量
来源：http://dali.yangfankeji.com/Article/details/gthdwxeetd.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gttfcyzrls.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.fengsongda.top/Article/details/gttjcuddod.html

JS:   process.env.HOME
来源：http://dali.gaohongyu789.top/Article/details/gtknbtcwds.html

TS:   process.env.HOME
来源：http://dali.xziqi.cn/Article/details/gtwkwqbomr.html

Java: System.getenv("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gtjvxdfypm.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnqpfolj.html

Ruby: ENV["HOME"]
来源：http://dali.tianlin.xyz/Article/details/gtswmqjqhh.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtkhxodkwo.html

[M03] 执行外部命令
来源：http://dali.meibo888.top/Article/details/gtdbetuqos.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.nanxinkj.top/Article/details/gtpidyfhwy.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenjidiqi.icu/Article/details/gtqdniirfu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.sufxvd.cn/Article/details/gtjyqsyevg.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yangfankeji.com/Article/details/gtotvyjqea.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.daria6918.cn/Article/details/gtihhkbast.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ybcxt.top/Article/details/gtyyxikvcj.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhengqikj.top/Article/details/gtkvwgiqpb.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sxryk.cn/Article/details/gtendapbyx.html

[M04] 获取当前工作目录
来源：http://dali.ydzc1.top/Article/details/gthnkjzbel.html

Py:   os.getcwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtycubrbky.html

PHP:  getcwd();
来源：http://dali.ydzc1.top/Article/details/gtqcinooxg.html

JS:   process.cwd()
来源：http://dali.kuanghao11.cn/Article/details/gtftyakuez.html

TS:   process.cwd()
来源：http://dali.chenjidiqi.icu/Article/details/gtexweyrmw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hfpthk.cn/Article/details/gtdumfbesq.html

Go:   os.Getwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtppxurxqj.html

Ruby: Dir.pwd
来源：http://dali.hnqzz.top/Article/details/gtdsmfpvcy.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.yuxming.cn/Article/details/gtyeeobprr.html

[M05] 设置退出码
来源：http://dali.tanke756.top/Article/details/gthvbzetmd.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gtftlgqdgl.html

PHP:  exit(1);
来源：http://dali.sysykeji.top/Article/details/gtjsayvqzi.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtnjkaknhp.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzejebav.html

Java: System.exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtbplrcxsi.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gtvfknlkga.html

Ruby: exit 1
来源：http://dali.kuanghao11.cn/Article/details/gtshkgcwfg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gtzrdbhuqt.html

[M06] 向标准错误输出
来源：http://dali.fzhhl.top/Article/details/gtjoxyqaph.html

Py:   print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtelbqtikq.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ehwqpu.com/Article/details/gtmhcegsqs.html

JS:   console.error("err")
来源：http://dali.jinqigufen.top/Article/details/gtwzrxumis.html

TS:   console.error("err")
来源：http://dali.aibaodan.cn/Article/details/gtdceaxwll.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gtryxlivzj.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gtfurylfxc.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gtytejtxfr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhixingplan.top/Article/details/gtomoxqsax.html

[M07] 判断是否为主入口
来源：http://dali.nanxinkj.top/Article/details/gtuvlicuho.html

Py:   if __name__ == "__main__":
来源：http://dali.316326.xyz/Article/details/gtandvvvnz.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxinkj.top/Article/details/gttavfiaip.html

JS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gthmvdsbyc.html

TS:   require.main === module
来源：http://dali.shzxlz.cn/Article/details/gtbnufsyuw.html

Java: public static void main(String[] args)
来源：http://dali.meibo888.top/Article/details/gtdiadxhch.html

Go:   func main()
来源：http://dali.ybcxt.top/Article/details/gtwybhbxwx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jiagoushi.top/Article/details/gtwsgbuizz.html

C#:   static void Main(string[] args)
来源：http://dali.nanxuanxn.top/Article/details/gthpqieldo.html

[M08] 获取系统与运行时信息
来源：http://dali.jianghu66.top/Article/details/gtfmejlgik.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxuanxn.top/Article/details/gtyrxrshdg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sweek.top/Article/details/gtkpkmpmkq.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtrqbdmtys.html

TS:   process.platform;  process.version
来源：http://dali.zhongyouzk.top/Article/details/gtalqiimhb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.shzxlz.cn/Article/details/gtizwnqtvp.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.dianchejie.cn/Article/details/gtqovrfrzh.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.quarkkingdee.top/Article/details/gthmvdhzcc.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gtdltylihb.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtdxprjnqb.html

N. 数据结构与算法
来源：http://dali.jyoumei.cn/Article/details/gtmnsxhpmp.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvjurxik.html

[N01] 二分查找（有序数组）
来源：http://dali.zycfv.cn/Article/details/gtfbpjhkya.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtlrxjmixe.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zdqjudy.top/Article/details/gtiwqzpuas.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shangyingyoupin.top/Article/details/gticxulnxn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gtexarpmug.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gtqlhqmcah.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yuxming.cn/Article/details/gttqeaxyhy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.hfpthk.cn/Article/details/gtfiwywpfn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtwdurdhyl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.xziqi.cn/Article/details/gtmfpilocw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.andypj.xyz/Article/details/gteufombos.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.guannengcc.top/Article/details/gtprqwindr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtyvgxhehm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.dianchejie.cn/Article/details/gtkhbosxel.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gtgbrldjpn.html

Go:   slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtyjtbxkhx.html

Ruby: arr.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtpemqbzpw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.tianlin.xyz/Article/details/gtgmtvuuas.html

[N03] 快速排序（分治示例）
来源：http://dali.yj202588.top/Article/details/gtwpcgawpu.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfcuoisbg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.nanxinkj.top/Article/details/gthjfqfrle.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.sxryk.cn/Article/details/gtpoklkejg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.zdqjudy.top/Article/details/gtevgsdfnj.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.guannengcc.top/Article/details/gtobfsqnpc.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.cqqwz.cn/Article/details/gtmxufgemd.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sysykeji.top/Article/details/gtllpmqjcf.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yuxming.cn/Article/details/gtaxzgnwgq.html

[N04] 斐波那契数列
来源：http://dali.redwolf501.top/Article/details/gtjxngahgp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gtxowywprb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dashuyun.cn/Article/details/gtvqcsivax.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtamrilgow.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gtwtpmikrd.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.wangdashe.top/Article/details/gtejrxbnov.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.fzhhl.top/Article/details/gtfglpafcr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.jlsjyb.cn/Article/details/gtzxbmgzgk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gtplpsylfm.html

[N05] 最大公约数
来源：http://dali.tianlin.xyz/Article/details/gtcjpujxtq.html

Py:   math.gcd(a, b)
来源：http://dali.yvedp.cn/Article/details/gtriztsezq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gtmlirstqk.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqzhfuygc.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.quarkkingdee.top/Article/details/gtipoywjje.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hnqzz.top/Article/details/gtgpmhvvru.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.kuanghao11.cn/Article/details/gtdwikxjwp.html

Ruby: a.gcd(b)
来源：http://dali.fengsongda.top/Article/details/gtptjrqkoe.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.sysykeji.top/Article/details/gtugpjdrho.html

[N06] 判断回文字符串
来源：http://dali.birdmap.top/Article/details/gtpwquqook.html

Py:   s == s[::-1]
来源：http://dali.hongshengwenyu.top/Article/details/gtawossnvd.html

PHP:  $s === strrev($s);
来源：http://dali.zycfv.cn/Article/details/gtkweklfvt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtixbjonop.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtjaqfzggi.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenzaomai.com/Article/details/gtppdhesfg.html

Go:   // 双指针从两端比较
来源：http://dali.quarkkingdee.top/Article/details/gtpvurxsxl.html

Ruby: s == s.reverse
来源：http://dali.kuanghao11.cn/Article/details/gtnutxnsbn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhiwuduotai.top/Article/details/gttnkbwazd.html

[N07] 两数之和（返回下标）
来源：http://dali.guowangkeji.top/Article/details/gttxwxrtul.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.yj20258.top/Article/details/gtxiilxprm.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.birdmap.top/Article/details/gtgurncemh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sufxvd.cn/Article/details/gtojqplere.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhiwuduotai.top/Article/details/gtrhtyqrjy.html

Java: // 手写 HashMap
来源：http://dali.jlsjyb.cn/Article/details/gtgnzaiutc.html

Go:   // 手写 map[int]int
来源：http://dali.jqgfzy.top/Article/details/gthamtkddv.html

Ruby: // 手写 Hash
来源：http://dali.fengsongda.top/Article/details/gtiztweoue.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ehwqpu.com/Article/details/gtlgqkuvyz.html

[N08] 生成全排列
来源：http://dali.hnxiangtu.top/Article/details/gtyxzxpulv.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqviikjeg.html

PHP:  // 手写递归交换
来源：http://dali.cucudq.cn/Article/details/gtvszwxyud.html

JS:   // 手写回溯递归
来源：http://dali.jinqigufen.top/Article/details/gtdvijgtjs.html

TS:   // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gthlkbtnin.html

Java: // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtuavcswen.html

Go:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gtozjuybmm.html

Ruby: arr.permutation.to_a
来源：http://dali.shuidangran.top/Article/details/gtyvisnaka.html

C#:   // 手写回溯递归
来源：http://dali.yonumen.top/Article/details/gtuusfhxrl.html

[N09] 栈与队列
来源：http://dali.snrcjt.cn/Article/details/gtfpbissqi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258888.top/Article/details/gtytotjhyj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynvvxvsf.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gtglivcvog.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shangyingyoupin.top/Article/details/gtlnlpvosl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gtacmiigfr.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jlsjyb.cn/Article/details/gtocylihxn.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zycfv.cn/Article/details/gtmrrhbkxk.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.shangyingyoupin.top/Article/details/gtlubbafmg.html

[N10] 链表节点定义
来源：http://dali.hammf.cn/Article/details/gtokvecnij.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hysaishi.cn/Article/details/gtjfvgipfu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.shuidangran.top/Article/details/gtrywecgoq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.nanxinkj.top/Article/details/gtysbjskwf.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258888.top/Article/details/gtbanahycv.html

Java: class Node { int v; Node next; }
来源：http://dali.jqgfzy.top/Article/details/gtfhmserft.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj202588.top/Article/details/gthxtrozxc.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nwbrower.top/Article/details/gtequcolhl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hfpthk.cn/Article/details/gtvibncsco.html

[N11] 二叉树中序遍历
来源：http://dali.svipenyu.cn/Article/details/gtbwhsytxt.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jlsjyb.cn/Article/details/gtdenkhyed.html

PHP:  // 手写递归函数
来源：http://dali.tian-w.cn/Article/details/gtmeqrqldo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.mhx1999.top/Article/details/gtfuchosex.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvxfnoco.html

Java: // 手写递归
来源：http://dali.jlsjyb.cn/Article/details/gtddyjxbda.html

Go:   // 手写递归
来源：http://dali.redwolf501.top/Article/details/gtshrsqgwp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.sysykeji.top/Article/details/gtpcvoreht.html

C#:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtczbomejm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cdnleiting.top/Article/details/gtlzehgkxi.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.vqdsnc.cn/Article/details/gtoshrghnk.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cashguo.top/Article/details/gthsvttnpv.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ppjwa.cn/Article/details/gthzvfgsic.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.dianchejie.cn/Article/details/gtxqddgrqc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gtocntrvzg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.gzhubu.top/Article/details/gtlnicikrp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ybcxt.top/Article/details/gtirwgmhvb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hywenlv.cn/Article/details/gtqlsqrdyt.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gttavpydov.html

O. 并发与异步
来源：http://dali.sufxvd.cn/Article/details/gtzmltaysn.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtcfmwmfrj.html

[O01] 启动一个线程
来源：http://dali.chenzaomai.com/Article/details/gtssifyhvm.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.9152youxi.cn/Article/details/gtuphysnqa.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.sweek.top/Article/details/gtjejlarlq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.pycfn.com/Article/details/gtsyfutjpy.html

TS:   // 同 JS
来源：http://dali.0kj1m.cn/Article/details/gtowcrabsl.html

Java: new Thread(() -> f()).start()
来源：http://dali.nanxuanxn.top/Article/details/gtuffverlm.html

Go:   go f()
来源：http://dali.jiagoushi.top/Article/details/gtaxxbtdze.html

Ruby: Thread.new { f }
来源：http://dali.0kj1m.cn/Article/details/gtcyfzkaqj.html

C#:   Task.Run(() => F());
来源：http://dali.yvedp.cn/Article/details/gtxhhzqoiq.html

[O02] 使用线程池
来源：http://dali.sweek.top/Article/details/gtircrcrvd.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ppjwa.cn/Article/details/gtlbkryibw.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.daria6918.cn/Article/details/gtasvrppqn.html

JS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gtiwqxshuu.html

TS:   // worker_threads 线程池
来源：http://dali.meibo888.top/Article/details/gttcrllkjy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhijiandao.cn/Article/details/gtduqktrwk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aibaodan.cn/Article/details/gtfokzhnwd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shangyingyoupin.top/Article/details/gtglfqlrsl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenjidiqi.icu/Article/details/gtrbvlxexg.html

[O03] 加锁保护共享数据
来源：http://dali.jinqigufen.top/Article/details/gtasvmbrpy.html

Py:   with lock: shared += 1
来源：http://dali.jianghu66.top/Article/details/gtmdpcrtdk.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fzhhl.top/Article/details/gtvtlxrvvu.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.birdmap.top/Article/details/gtghhfclqr.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gtdidtrpjy.html

Java: synchronized (this) { shared++; }
来源：http://dali.ydzc1.top/Article/details/gtbguluuzp.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gtzfcgazkw.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.gotoacloud.top/Article/details/gtmcnwwvtw.html

C#:   lock (gate) { shared++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkvueknnr.html

[O04] 定义异步函数并等待
来源：http://dali.vqdsnc.cn/Article/details/gtwvcbmmrf.html

Py:   async def f():⏎    await g()
来源：http://dali.xylfe.cn/Article/details/gtrzxvjfkm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.iojbl.cn/Article/details/gtsyzxkuyz.html

JS:   async function f() { await g(); }
来源：http://dali.fzhhl.top/Article/details/gtrkekawpk.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gtfqlxfbab.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.gogol.net.cn/Article/details/gtfvkxqlat.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxuanxn.top/Article/details/gtrvpvoaek.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.cheryme.top/Article/details/gtobuomolh.html

C#:   async Task F() { await G(); }
来源：http://dali.yj202588.top/Article/details/gtfxeeysdx.html

[O05] 并发执行并等待全部完成
来源：http://dali.ppjwa.cn/Article/details/gthwdhwcmc.html

Py:   asyncio.gather(*tasks)
来源：http://dali.pycfn.com/Article/details/gtmwheworg.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.cheryme.top/Article/details/gtuyoxkbxw.html

JS:   await Promise.all(tasks)
来源：http://dali.redwolf501.top/Article/details/gthvgirxtq.html

TS:   await Promise.all(tasks)
来源：http://dali.jinqigufen.top/Article/details/gtteuweugh.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.guowangkeji.top/Article/details/gtzuoiwikw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.snrcjt.cn/Article/details/gtghoejeri.html

Ruby: threads.map(&:join)
来源：http://dali.tianlin.xyz/Article/details/gtboyyrttf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuanzx.com/Article/details/gtjgnfqpmx.html

[O06] 使用进程池
来源：http://dali.xylfe.cn/Article/details/gtqmotobjs.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcezyacjw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.guannengcc.top/Article/details/gtwdqzctdl.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gtnjejajet.html

TS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtiduegggs.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hfpthk.cn/Article/details/gtxbhxgxxm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.smart0.xyz/Article/details/gtiypxzllh.html

Ruby: // fork 块
来源：http://dali.meibo888.top/Article/details/gtgenbtood.html

C#:   Parallel.For
来源：http://dali.yj20258.top/Article/details/gtlihjkenn.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtasyqajwp.html

P. 常用工具函数
来源：http://dali.chenzaomai.com/Article/details/gtlptxowsl.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtpsljjvqk.html

[P01] 生成 UUID
来源：http://dali.zycfv.cn/Article/details/gtvvbalkad.html

Py:   str(uuid.uuid4())
来源：http://dali.ivvv.top/Article/details/gtvpiahuqj.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aizwys.cn/Article/details/gtvebavpiu.html

JS:   crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtpmkcdyjk.html

TS:   crypto.randomUUID()
来源：http://dali.yuanzhike.top/Article/details/gtitkxyvjy.html

Java: UUID.randomUUID().toString()
来源：http://dali.jlsjyb.cn/Article/details/gtgplqaoxj.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xinyue.icu/Article/details/gtxjgttjbc.html

Ruby: SecureRandom.uuid
来源：http://dali.hammf.cn/Article/details/gtephvfmuo.html


<!-- 参考信息 -->