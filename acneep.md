代发 wailian999

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.sufxvd.cn/Article/details/gtwnwrdaic.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.aibaodan.cn/Article/details/gthuztmyxo.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpemkudai.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.feifeiyinyue.top/Article/details/gticuokpag.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daxiang520.top/Article/details/gtxlnfbysy.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.snrcjt.cn/Article/details/gtfzjxfcco.html

[L05] 上传文件（multipart）
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqvcanfn.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenlongwang.top/Article/details/gtyxdmfztg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.shangyingyoupin.top/Article/details/gtouzkntlp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhongyouzk.top/Article/details/gtwrrcsacu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zycfv.cn/Article/details/gtbmnoviqu.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zycfv.cn/Article/details/gteayqtxbj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sufxvd.cn/Article/details/gtiworkecu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hfpthk.cn/Article/details/gtarvagzlg.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtzhbyxtgk.html

[L06] 解析响应为 JSON
来源：http://dali.ppjwa.cn/Article/details/gtcvwaswee.html

Py:   resp.json()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxfanzjr.html

PHP:  json_decode($body, true);
来源：http://dali.haohaochexian.top/Article/details/gtxuuxwznw.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gthmpwmccf.html

TS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gtgkzylhzs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.nwbrower.top/Article/details/gttxxugecc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tanke756.top/Article/details/gtvsyfdgck.html

Ruby: JSON.parse(resp.body)
来源：http://dali.snrcjt.cn/Article/details/gtypoipuec.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gtaiqidogo.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtyanqnqhy.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jianghu66.top/Article/details/gtznwhrcyi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.dashuyun.cn/Article/details/gtcazaulij.html

JS:   resp.ok;  resp.status
来源：http://dali.hysaishi.cn/Article/details/gtrvtvkplc.html

TS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gtxwpqekse.html

Java: resp.statusCode()
来源：http://dali.yongpay.top/Article/details/gtnlpgeoos.html

Go:   resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gtkngjplnw.html

Ruby: resp.code.to_i
来源：http://dali.cqqwz.cn/Article/details/gtceiawzmd.html

C#:   (int)resp.StatusCode
来源：http://dali.ybcxt.top/Article/details/gthnzyejxz.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gtxwwvxowo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuxming.cn/Article/details/gtzgnexbls.html

PHP:  curl_multi_init() 系列
来源：http://dali.tian-w.cn/Article/details/gtihkvcfpc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aibaodan.cn/Article/details/gtvrfvyvux.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtxxvbaghl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zycfv.cn/Article/details/gtyeajobjl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.wangdashe.top/Article/details/gtqdusxvxc.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.daria6918.cn/Article/details/gtpvomxtha.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtgpdpjrmo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtxvfawjpo.html

M. 命令行 / 进程 / 环境
来源：http://dali.xylfe.cn/Article/details/gtwodjxsfl.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaavzbpzj.html

[M01] 读取命令行参数
来源：http://dali.yongpay.top/Article/details/gtblkpawwc.html

Py:   sys.argv[1:]
来源：http://dali.mhx1999.top/Article/details/gtcxvebbry.html

PHP:  $argv;  $argc;
来源：http://dali.yuxming.cn/Article/details/gteohodzhq.html

JS:   process.argv.slice(2)
来源：http://dali.cqqwz.cn/Article/details/gtivpmtuok.html

TS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gtffkjlndb.html

Java: args 数组（main 方法参数）
来源：http://dali.wangshuangyany.cn/Article/details/gtgfctgtmu.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gtlvdhbgdd.html

Ruby: ARGV
来源：http://dali.tanke756.top/Article/details/gtegccfvsi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtoruasley.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gtdfidvhcx.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gtzanprdmg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.quarkkingdee.top/Article/details/gtwioncygs.html

JS:   process.env.HOME
来源：http://dali.316326.xyz/Article/details/gthjydzexu.html

TS:   process.env.HOME
来源：http://dali.shzxlz.cn/Article/details/gtdhreckrq.html

Java: System.getenv("HOME")
来源：http://dali.yuxming.cn/Article/details/gtoqoqfjhp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gtivelvrgw.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gtbqfdgsrd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.snrcjt.cn/Article/details/gtsukvlspi.html

[M03] 执行外部命令
来源：http://dali.zhijiandao.cn/Article/details/gttogusptz.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gttwfgyhta.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hnqzz.top/Article/details/gtnndvutrh.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtwnwbneud.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuxming.cn/Article/details/gtpdvsiugl.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gtvyqxtlda.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhongyouzk.top/Article/details/gtwcopdxtp.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yonumen.top/Article/details/gtjfklifwu.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xinyue.icu/Article/details/gttweupkur.html

[M04] 获取当前工作目录
来源：http://dali.pycfn.com/Article/details/gtfchwuitf.html

Py:   os.getcwd()
来源：http://dali.jinqigfzy.top/Article/details/gtsnqvotgx.html

PHP:  getcwd();
来源：http://dali.svipenyu.cn/Article/details/gtnqbbzjfb.html

JS:   process.cwd()
来源：http://dali.iojbl.cn/Article/details/gtywloevbw.html

TS:   process.cwd()
来源：http://dali.cucudq.cn/Article/details/gtgxiznkaj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.nanxuanxn.top/Article/details/gtcrifvfvn.html

Go:   os.Getwd()
来源：http://dali.vqdsnc.cn/Article/details/gtpezgxbrv.html

Ruby: Dir.pwd
来源：http://dali.zhixingplan.top/Article/details/gtqlfopxkb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gtcmzyhhna.html

[M05] 设置退出码
来源：http://dali.snrcjt.cn/Article/details/gtroqmgjys.html

Py:   sys.exit(1)
来源：http://dali.svipenyu.cn/Article/details/gtwuftohee.html

PHP:  exit(1);
来源：http://dali.yj20258888.top/Article/details/gtzueyfqze.html

JS:   process.exit(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtiqupxctp.html

TS:   process.exit(1)
来源：http://dali.kuanghao11.cn/Article/details/gtlncyvewd.html

Java: System.exit(1)
来源：http://dali.yj20258.top/Article/details/gtfxbliynf.html

Go:   os.Exit(1)
来源：http://dali.cqqwz.cn/Article/details/gtlkzmsmsn.html

Ruby: exit 1
来源：http://dali.nwbrower.top/Article/details/gtjyaorrty.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nwbrower.top/Article/details/gtjyumjjbc.html

[M06] 向标准错误输出
来源：http://dali.yj202588.top/Article/details/gtxbxhzeru.html

Py:   print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gtcfpbzhbs.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.fengsongda.top/Article/details/gtomqfxhlp.html

JS:   console.error("err")
来源：http://dali.xuetiantiany.cn/Article/details/gtgaewqobg.html

TS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gtsaeqxlhe.html

Java: System.err.println("err")
来源：http://dali.jlsjyb.cn/Article/details/gtwhsafjoa.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xylfe.cn/Article/details/gtuzkrraor.html

Ruby: warn "err"
来源：http://dali.jiagoushi.top/Article/details/gtkcqojffw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.redwolf501.top/Article/details/gteklmhjpq.html

[M07] 判断是否为主入口
来源：http://dali.zdqjudy.top/Article/details/gtybglshrt.html

Py:   if __name__ == "__main__":
来源：http://dali.gaohongyu789.top/Article/details/gtihaezhpe.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.guannengcc.top/Article/details/gtiprkxfqh.html

JS:   require.main === module
来源：http://dali.guannengcc.top/Article/details/gtbovsmwuf.html

TS:   require.main === module
来源：http://dali.yuxming.cn/Article/details/gtzueczoep.html

Java: public static void main(String[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtbstfbodu.html

Go:   func main()
来源：http://dali.cucudq.cn/Article/details/gttbqmqyoi.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj20258888.top/Article/details/gtsfrvgsps.html

C#:   static void Main(string[] args)
来源：http://dali.xinyue.icu/Article/details/gtrkjekpxe.html

[M08] 获取系统与运行时信息
来源：http://dali.zhongyouzk.top/Article/details/gtqlorhhkb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.yuanzhike.top/Article/details/gttcgiogbc.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.pengpengdd.cyou/Article/details/gtqithjejl.html

JS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gtpteevzvq.html

TS:   process.platform;  process.version
来源：http://dali.dashuyun.cn/Article/details/gtojnhhwqd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.svipenyu.cn/Article/details/gtihsoldsr.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.hfpthk.cn/Article/details/gthhcomcgy.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.kuanghao11.cn/Article/details/gtatqjpkun.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cucudq.cn/Article/details/gtmjlsfqwq.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtycjbpcle.html

N. 数据结构与算法
来源：http://dali.wangdashe.top/Article/details/gtzkmtgooe.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtqzbdstgx.html

[N01] 二分查找（有序数组）
来源：http://dali.chenjidiqi.icu/Article/details/gtjsgssofw.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gtvblogtsv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sysykeji.top/Article/details/gtkogzfljd.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gtlnprjzar.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gtcbqfnreo.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtybiqkbkw.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdwlqkato.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yangfankeji.com/Article/details/gtesxhbanc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtoslijlcf.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zdqjudy.top/Article/details/gtedslvdap.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtfvdeqcln.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jiagoushi.top/Article/details/gtpzywuubf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtnhimasnu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gtftzwzdtq.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigfzy.top/Article/details/gtrtzwxeek.html

Go:   slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtuisejivm.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtwidfspmt.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.sufxvd.cn/Article/details/gtgkdblinn.html

[N03] 快速排序（分治示例）
来源：http://dali.wangdashe.top/Article/details/gtjxzpjktq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.ivvv.top/Article/details/gtebzgzefn.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gtfcwbcyxa.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtujtjnomb.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gtpfwyawah.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yuanzhike.top/Article/details/gtaicbwfyp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yanxiufei.cn/Article/details/gtvaojaicx.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhixingplan.top/Article/details/gtjedgornx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yangfankeji.com/Article/details/gtpqctyxwv.html

[N04] 斐波那契数列
来源：http://dali.hongshengwenyu.top/Article/details/gtwbcsxajh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tanke756.top/Article/details/gteunusczy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yonumen.top/Article/details/gtqyrttjvo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hysaishi.cn/Article/details/gtyaoqnrce.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxinkj.top/Article/details/gtvngoygoo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yangfankeji.com/Article/details/gtttmgeuci.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xuetiantiany.cn/Article/details/gtqmowbujk.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yj20258.top/Article/details/gtvayhyylf.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtbwiiimmk.html

[N05] 最大公约数
来源：http://dali.hongshengwenyu.top/Article/details/gticntbifz.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gtvntaflag.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gttlnysjhh.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhxztdus.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.redwolf501.top/Article/details/gtyhlepwik.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqhnhgmm.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dashuyun.cn/Article/details/gtvzbjgjwe.html

Ruby: a.gcd(b)
来源：http://dali.316326.xyz/Article/details/gtrzodpbgc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.dianchejie.cn/Article/details/gtvsfwsnme.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gtlavdnuxh.html

Py:   s == s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gtcusbudxe.html

PHP:  $s === strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gtmbebvgdg.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jyoumei.cn/Article/details/gtjarwyows.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtrvkkikzp.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shuidangran.top/Article/details/gthhctwuor.html

Go:   // 双指针从两端比较
来源：http://dali.hysaishi.cn/Article/details/gtqsbfpnpx.html

Ruby: s == s.reverse
来源：http://dali.sufxvd.cn/Article/details/gtukoeauqp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtakzawvgt.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gtkyfjnaou.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxpnobls.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.hammf.cn/Article/details/gtnatbhxwp.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.zhiwuduotai.top/Article/details/gtnwjcjvwt.html

TS:   // 手写 Map<string, number>
来源：http://dali.andypj.xyz/Article/details/gtrgbiduve.html

Java: // 手写 HashMap
来源：http://dali.aizwys.cn/Article/details/gtyqbvvxip.html

Go:   // 手写 map[int]int
来源：http://dali.ybcxt.top/Article/details/gtxzjuktlf.html

Ruby: // 手写 Hash
来源：http://dali.hfpthk.cn/Article/details/gtmtuggsff.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.nanxinkj.top/Article/details/gtionlfjco.html

[N08] 生成全排列
来源：http://dali.jinqigfzy.top/Article/details/gtrxombowd.html

Py:   itertools.permutations(arr)
来源：http://dali.ydzc1.top/Article/details/gtjzfjaiff.html

PHP:  // 手写递归交换
来源：http://dali.gaohongyu789.top/Article/details/gtmtbatxpc.html

JS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gttcdjnhsx.html

TS:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtgkarjaju.html

Java: // 手写回溯递归
来源：http://dali.hongshengwenyu.top/Article/details/gtyllcobfh.html

Go:   // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtqxcnpnbu.html

Ruby: arr.permutation.to_a
来源：http://dali.daria6918.cn/Article/details/gtgvxygdhj.html

C#:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtwfcjpxel.html

[N09] 栈与队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcpvunmi.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenlongwang.top/Article/details/gtftarryfh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.aibaodan.cn/Article/details/gtuptgixfq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gtyrayjbdg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangshuangyany.cn/Article/details/gtfqwsbqmg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.pengpengdd.cyou/Article/details/gtknohilsg.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.birdmap.top/Article/details/gtwktqezaz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.meibo888.top/Article/details/gtillhrgdy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.aibaodan.cn/Article/details/gtisysilvf.html

[N10] 链表节点定义
来源：http://dali.yuxming.cn/Article/details/gttwzsxdjy.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.birdmap.top/Article/details/gtripcotbu.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xylfe.cn/Article/details/gtmouhdpev.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.316326.xyz/Article/details/gtbqfjwmqd.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigufen.top/Article/details/gtbbstjbph.html

Java: class Node { int v; Node next; }
来源：http://dali.hammf.cn/Article/details/gtmiwuxvbw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.feifeiyinyue.top/Article/details/gtodxestpq.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.fzhhl.top/Article/details/gtnydurqhq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yj20258888.top/Article/details/gtuctviptz.html

[N11] 二叉树中序遍历
来源：http://dali.zhongyouzk.top/Article/details/gtpjzolzwy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.mhx1999.top/Article/details/gteishnkas.html

PHP:  // 手写递归函数
来源：http://dali.shzxlz.cn/Article/details/gtlzrbzutu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtjkaernut.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pengpengdd.cyou/Article/details/gtybbcgmcf.html

Java: // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gtvuhpazwy.html

Go:   // 手写递归
来源：http://dali.gzhubu.top/Article/details/gtpmfzqwfs.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jianghu66.top/Article/details/gthoirnqog.html

C#:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtiogkeocf.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangdashe.top/Article/details/gtdgmimtdc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.chenlongwang.top/Article/details/gtczekzmqi.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sysykeji.top/Article/details/gtkuhohrde.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hysaishi.cn/Article/details/gtvzqjeeiw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.haohaochexian.top/Article/details/gtiyylfzup.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.316326.xyz/Article/details/gtwpnznyit.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhoulong.xyz/Article/details/gtvlfzqjib.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtmhsrshcz.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtrsjkgven.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtouuktckh.html

O. 并发与异步
来源：http://dali.ydzc1.top/Article/details/gtkiprgqmr.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtzkzysxqm.html

[O01] 启动一个线程
来源：http://dali.pycfn.com/Article/details/gtwnwgbjpl.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.ppjwa.cn/Article/details/gtadbbrdtu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yvedp.cn/Article/details/gtokwmtije.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.vqdsnc.cn/Article/details/gtsmiutfoy.html

TS:   // 同 JS
来源：http://dali.aibaodan.cn/Article/details/gtqxzgyfdu.html

Java: new Thread(() -> f()).start()
来源：http://dali.cdnleiting.top/Article/details/gtaiixvqtx.html

Go:   go f()
来源：http://dali.316326.xyz/Article/details/gtzewvwydb.html

Ruby: Thread.new { f }
来源：http://dali.jinghuilouyu.cn/Article/details/gtojzmwsda.html

C#:   Task.Run(() => F());
来源：http://dali.chenzaomai.com/Article/details/gttnrscufy.html

[O02] 使用线程池
来源：http://dali.gzhubu.top/Article/details/gtkvkrcilc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zhixingplan.top/Article/details/gtpktysaby.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yongpay.top/Article/details/gtiugrxswu.html

JS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtogfbgojo.html

TS:   // worker_threads 线程池
来源：http://dali.svipenyu.cn/Article/details/gtvaxruylr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jlsjyb.cn/Article/details/gtnoueljze.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.jinqigfzy.top/Article/details/gttwhjafli.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.pengpengdd.cyou/Article/details/gtzcvmjuvk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sysykeji.top/Article/details/gtvdqocnar.html

[O03] 加锁保护共享数据
来源：http://dali.daxiang520.top/Article/details/gtwusnpfwj.html

Py:   with lock: shared += 1
来源：http://dali.jqgfzy.top/Article/details/gthknhbbpg.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jianghu66.top/Article/details/gtuljrqbqp.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gtxcalmcrn.html

TS:   // 同 JS
来源：http://dali.tian-w.cn/Article/details/gtkwzvrlxm.html

Java: synchronized (this) { shared++; }
来源：http://dali.jiagoushi.top/Article/details/gtndeayzfy.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yvedp.cn/Article/details/gthjvtpkdo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiowvcloh.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsdxpoyv.html

[O04] 定义异步函数并等待
来源：http://dali.aibaodan.cn/Article/details/gtqyexicst.html

Py:   async def f():⏎    await g()
来源：http://dali.hysaishi.cn/Article/details/gtwkimtixj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.chenzaomai.com/Article/details/gtogmurvdj.html

JS:   async function f() { await g(); }
来源：http://dali.hnxiangtu.top/Article/details/gtxbazeyik.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.pycfn.com/Article/details/gtbwmqgqcn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.feifeiyinyue.top/Article/details/gtohntrmci.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.zhongyouzk.top/Article/details/gtwnctwpxd.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhiwuduotai.top/Article/details/gtjtakhlen.html

C#:   async Task F() { await G(); }
来源：http://dali.cashguo.top/Article/details/gtvfazzhvt.html

[O05] 并发执行并等待全部完成
来源：http://dali.iojbl.cn/Article/details/gtoxrlhbuz.html

Py:   asyncio.gather(*tasks)
来源：http://dali.gzhubu.top/Article/details/gtvxzxzccr.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.nanxuanxn.top/Article/details/gtkmtksonn.html

JS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gtfbbisryl.html

TS:   await Promise.all(tasks)
来源：http://dali.zhoulong.xyz/Article/details/gtdebqjsmt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cdnleiting.top/Article/details/gtssetjudl.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hammf.cn/Article/details/gtywpdaheo.html

Ruby: threads.map(&:join)
来源：http://dali.ivvv.top/Article/details/gtdzrxuato.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.hfpthk.cn/Article/details/gtugdqcnst.html

[O06] 使用进程池
来源：http://dali.chenzaomai.com/Article/details/gtdiigbfzz.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hammf.cn/Article/details/gtogiizyla.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zycfv.cn/Article/details/gtwcwzvjrs.html

JS:   // child_process / cluster 模块
来源：http://dali.yueranfly.top/Article/details/gtpeftzvzz.html

TS:   // child_process / cluster 模块
来源：http://dali.vqdsnc.cn/Article/details/gtxbzhjxnu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zdqjudy.top/Article/details/gttmkxxwnh.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.bjfxy.top/Article/details/gtjqyvrgja.html

Ruby: // fork 块
来源：http://dali.9152youxi.cn/Article/details/gtofgjssjv.html

C#:   Parallel.For
来源：http://dali.chenzaomai.com/Article/details/gtelalyapi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtcxtkzulb.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gttvgsrrxm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmyofdowa.html

[P01] 生成 UUID
来源：http://dali.birdmap.top/Article/details/gtnpbkmwaw.html

Py:   str(uuid.uuid4())
来源：http://dali.cheryme.top/Article/details/gtmflrcarc.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nanxinkj.top/Article/details/gtbyyzxmrb.html

JS:   crypto.randomUUID()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfatcjrdb.html

TS:   crypto.randomUUID()
来源：http://dali.hfpthk.cn/Article/details/gtlyegaifv.html

Java: UUID.randomUUID().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtubejudus.html

Go:   // 用 github.com/google/uuid
来源：http://dali.hnxiangtu.top/Article/details/gtjxltudol.html

Ruby: SecureRandom.uuid
来源：http://dali.feifeiyinyue.top/Article/details/gtvfzyrzdr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yvedp.cn/Article/details/gtarewbzfh.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shangyingyoupin.top/Article/details/gtwlafzcep.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.xuetiantiany.cn/Article/details/gttbvvlrow.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.jiagoushi.top/Article/details/gtixyorvlx.html


<!-- 参考信息 -->