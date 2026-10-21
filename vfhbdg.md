代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.vqdsnc.cn/Article/details/gtgknydvrz.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhiwuduotai.top/Article/details/gtfnedehqk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtqngmrmji.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fengsongda.top/Article/details/gtvvktyrcn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yuxming.cn/Article/details/gtxerhuiah.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ivvv.top/Article/details/gtyoomijod.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.meibo888.top/Article/details/gtidwcndpz.html

[L06] 解析响应为 JSON
来源：http://dali.daria6918.cn/Article/details/gtfwljakie.html

Py:   resp.json()
来源：http://dali.svipenyu.cn/Article/details/gtuhvyixbg.html

PHP:  json_decode($body, true);
来源：http://dali.chenjidiqi.icu/Article/details/gtkdfvjvls.html

JS:   await resp.json()
来源：http://dali.daria6918.cn/Article/details/gthyecraya.html

TS:   await resp.json()
来源：http://dali.ppjwa.cn/Article/details/gtqzwylmub.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xinyue.icu/Article/details/gtvcnloppq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xylfe.cn/Article/details/gteieonlbj.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gtjdsmbbio.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtrijtcwye.html

[L07] 处理 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gtdeyadxjc.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinqigfzy.top/Article/details/gtwhxxgsqt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258888.top/Article/details/gtvpjxzeay.html

JS:   resp.ok;  resp.status
来源：http://dali.smart0.xyz/Article/details/gtbpclndbo.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtsmuqanls.html

Java: resp.statusCode()
来源：http://dali.ehwqpu.com/Article/details/gtylnsketc.html

Go:   resp.StatusCode
来源：http://dali.dianchejie.cn/Article/details/gtwlwglchd.html

Ruby: resp.code.to_i
来源：http://dali.c1oappe.top/Article/details/gtmxtpxlno.html

C#:   (int)resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gtyjqaaxku.html

[L08] 并发请求多个地址
来源：http://dali.c1oappe.top/Article/details/gtwpjnniji.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.fengsongda.top/Article/details/gtvrufgbei.html

PHP:  curl_multi_init() 系列
来源：http://dali.havefunace.top/Article/details/gtwsvdnzkx.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtamweamtm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gtzbzkjreu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.0kj1m.cn/Article/details/gtoaldkvsh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvvoszsq.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtnwxrrkel.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.iojbl.cn/Article/details/gtholybxel.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtnizijamv.html

M. 命令行 / 进程 / 环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkvphtkf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtiamehamg.html

[M01] 读取命令行参数
来源：http://dali.pycfn.com/Article/details/gteyxwpxuk.html

Py:   sys.argv[1:]
来源：http://dali.daria6918.cn/Article/details/gtxhvmtqpj.html

PHP:  $argv;  $argc;
来源：http://dali.zdqjudy.top/Article/details/gtuphvyidw.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gtffevrxba.html

TS:   process.argv.slice(2)
来源：http://dali.ydzc1.top/Article/details/gteestumbk.html

Java: args 数组（main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtbqevlrxp.html

Go:   os.Args[1:]
来源：http://dali.yueranfly.top/Article/details/gtiewtgxxb.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnoqwluba.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daxiang520.top/Article/details/gtxsiqrcwk.html

[M02] 读取环境变量
来源：http://dali.gogol.net.cn/Article/details/gtjimcitak.html

Py:   os.environ.get("HOME")
来源：http://dali.sweek.top/Article/details/gtrymhksey.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gtlucsooxi.html

JS:   process.env.HOME
来源：http://dali.sweek.top/Article/details/gtftbpzrni.html

TS:   process.env.HOME
来源：http://dali.wangdashe.top/Article/details/gtvunvngcg.html

Java: System.getenv("HOME")
来源：http://dali.tian-w.cn/Article/details/gtdcbccnuv.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwcdnqkgf.html

Ruby: ENV["HOME"]
来源：http://dali.tanke756.top/Article/details/gtcamajeez.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.tianlin.xyz/Article/details/gtgseyetyt.html

[M03] 执行外部命令
来源：http://dali.jyoumei.cn/Article/details/gtgcvdgpel.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhiwuduotai.top/Article/details/gthtwimayp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jqgufenzy.top/Article/details/gtjgyfacwn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xinyue.icu/Article/details/gtjycorbbl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yuanzhike.top/Article/details/gtoqhiyvaw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shangyingyoupin.top/Article/details/gtjtqnpfef.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.cheryme.top/Article/details/gtvjlynqle.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hywenlv.cn/Article/details/gtjzafkqil.html

C#:   Process.Start("ls", "-l");
来源：http://dali.dianchejie.cn/Article/details/gtjyfuksfm.html

[M04] 获取当前工作目录
来源：http://dali.sweek.top/Article/details/gtdeqkqzlm.html

Py:   os.getcwd()
来源：http://dali.daria6918.cn/Article/details/gtrhktlekn.html

PHP:  getcwd();
来源：http://dali.quarkkingdee.top/Article/details/gtyefzouhz.html

JS:   process.cwd()
来源：http://dali.jinghuilouyu.cn/Article/details/gthgszljap.html

TS:   process.cwd()
来源：http://dali.yuanzhike.top/Article/details/gtindxaadv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cqqwz.cn/Article/details/gtcioqbjrl.html

Go:   os.Getwd()
来源：http://dali.yj20258.top/Article/details/gteewtdqnu.html

Ruby: Dir.pwd
来源：http://dali.cqqwz.cn/Article/details/gtjluktnuk.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sxryk.cn/Article/details/gtdzwmzkea.html

[M05] 设置退出码
来源：http://dali.ppjwa.cn/Article/details/gtekwfjinp.html

Py:   sys.exit(1)
来源：http://dali.pycfn.com/Article/details/gtonphhlem.html

PHP:  exit(1);
来源：http://dali.haohaochexian.top/Article/details/gtiioggckg.html

JS:   process.exit(1)
来源：http://dali.vqdsnc.cn/Article/details/gtncooanxg.html

TS:   process.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtgoiqcmex.html

Java: System.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gtudaysyfw.html

Go:   os.Exit(1)
来源：http://dali.jinqigfzy.top/Article/details/gtoyitvkbx.html

Ruby: exit 1
来源：http://dali.yuanzhike.top/Article/details/gtczutxzbx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dianchejie.cn/Article/details/gtgwazsqpd.html

[M06] 向标准错误输出
来源：http://dali.ppjwa.cn/Article/details/gtxvrvfbiz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.pengpengdd.cyou/Article/details/gtymrfqscd.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guannengcc.top/Article/details/gtvsmjantz.html

JS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gtqqqsixrz.html

TS:   console.error("err")
来源：http://dali.daxiang520.top/Article/details/gtympwasrs.html

Java: System.err.println("err")
来源：http://dali.nwbrower.top/Article/details/gtncvtlixk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbeacvmz.html

Ruby: warn "err"
来源：http://dali.vqdsnc.cn/Article/details/gtuuovqpsr.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yvedp.cn/Article/details/gtsqejbzgh.html

[M07] 判断是否为主入口
来源：http://dali.daxiang520.top/Article/details/gtjucuylvh.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gtngjwabnp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.nanxuanxn.top/Article/details/gtzdiwuuzl.html

JS:   require.main === module
来源：http://dali.bjfxy.top/Article/details/gthelrcteb.html

TS:   require.main === module
来源：http://dali.zhongyouzk.top/Article/details/gtfjybqjyw.html

Java: public static void main(String[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtxblhjrsr.html

Go:   func main()
来源：http://dali.yangfankeji.com/Article/details/gtmsjnuvqt.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hfpthk.cn/Article/details/gtcsoooybd.html

C#:   static void Main(string[] args)
来源：http://dali.svipenyu.cn/Article/details/gtcgnkiikf.html

[M08] 获取系统与运行时信息
来源：http://dali.wangshuangyany.cn/Article/details/gtszqnssro.html

Py:   platform.system();  platform.python_version()
来源：http://dali.haohaochexian.top/Article/details/gtdheunwii.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jqgfzy.top/Article/details/gtzzgmnwhi.html

JS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtgwlcgzif.html

TS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gtqmakiaqh.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.ehwqpu.com/Article/details/gtgkzkmimg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.nanxuanxn.top/Article/details/gtxycykwqm.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangshuangyany.cn/Article/details/gtqjkrchns.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hysaishi.cn/Article/details/gtdhpythtq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtysbrnxuu.html

N. 数据结构与算法
来源：http://dali.nanxinkj.top/Article/details/gtmwquisga.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtigrhdhet.html

[N01] 二分查找（有序数组）
来源：http://dali.svipenyu.cn/Article/details/gtavyfverj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.guowangkeji.top/Article/details/gtjddfmglv.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.wangdashe.top/Article/details/gtgtfmgnkv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ehwqpu.com/Article/details/gtjqiweztg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtdecbdnby.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtpbfdlrdg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtkipamvpz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.c1oappe.top/Article/details/gtcipbaxuc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhalqchu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhixingplan.top/Article/details/gtinrxrzal.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtgwbjwpeb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ppjwa.cn/Article/details/gtbutqunbv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shuidangran.top/Article/details/gtadocdntt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinqigfzy.top/Article/details/gtsolhfmyv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.andypj.xyz/Article/details/gtdrrdyazl.html

Go:   slices.Sort(arr)
来源：http://dali.mhx1999.top/Article/details/gtelzfocxq.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gtfcflfmhr.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.vqdsnc.cn/Article/details/gtqcrkhrok.html

[N03] 快速排序（分治示例）
来源：http://dali.guannengcc.top/Article/details/gtapyeperr.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.wangshuangyany.cn/Article/details/gtiuodcmof.html

PHP:  // 递归实现，或用 usort
来源：http://dali.feifeiyinyue.top/Article/details/gtvsqhbrig.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xinyue.icu/Article/details/gtzdvzxkri.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gtdspdhewz.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangshuangyany.cn/Article/details/gtusbgyhfs.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jianghu66.top/Article/details/gtfnioxkkp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cheryme.top/Article/details/gtehschqvm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.kuanghao11.cn/Article/details/gtbjbbswiu.html

[N04] 斐波那契数列
来源：http://dali.zhoulong.xyz/Article/details/gtcurjkffj.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhpetnjs.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.dianchejie.cn/Article/details/gtjqowlaob.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.guannengcc.top/Article/details/gtrxjfpqir.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aibaodan.cn/Article/details/gtmlupsqns.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daria6918.cn/Article/details/gtrbdtvgxn.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.wangdashe.top/Article/details/gtpphnudfy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ppjwa.cn/Article/details/gtqexusulw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.sweek.top/Article/details/gtyaqojtxa.html

[N05] 最大公约数
来源：http://dali.quarkkingdee.top/Article/details/gtueecgsbk.html

Py:   math.gcd(a, b)
来源：http://dali.shzxlz.cn/Article/details/gthcdykhre.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaksffwke.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yuxming.cn/Article/details/gtyainwmqx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jqgfzy.top/Article/details/gtsailafam.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cashguo.top/Article/details/gtcmekdncf.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.chenjidiqi.icu/Article/details/gtbuppccnu.html

Ruby: a.gcd(b)
来源：http://dali.redwolf501.top/Article/details/gtpuhynpfh.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.smart0.xyz/Article/details/gtaxdocsaj.html

[N06] 判断回文字符串
来源：http://dali.yanxiufei.cn/Article/details/gtbzcfkazx.html

Py:   s == s[::-1]
来源：http://dali.ppjwa.cn/Article/details/gtgbcslzeb.html

PHP:  $s === strrev($s);
来源：http://dali.gogol.net.cn/Article/details/gtltmlnbsq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtlusngfjp.html

TS:   s === [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtcovsqwzv.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zdqjudy.top/Article/details/gtlqhmaulf.html

Go:   // 双指针从两端比较
来源：http://dali.aibaodan.cn/Article/details/gtimjvaqrl.html

Ruby: s == s.reverse
来源：http://dali.gotoacloud.top/Article/details/gtwxvnaauu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gtqmtexiqw.html

[N07] 两数之和（返回下标）
来源：http://dali.hfpthk.cn/Article/details/gtkeoeaegt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.bjfxy.top/Article/details/gttsgbuuwl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhongyouzk.top/Article/details/gtdchuqhry.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gtyxvrjxmh.html

TS:   // 手写 Map<string, number>
来源：http://dali.mhx1999.top/Article/details/gtjycimqlg.html

Java: // 手写 HashMap
来源：http://dali.haohaochexian.top/Article/details/gtcanjdvak.html

Go:   // 手写 map[int]int
来源：http://dali.fengsongda.top/Article/details/gtqbnmidyg.html

Ruby: // 手写 Hash
来源：http://dali.gaohongyu789.top/Article/details/gtqkluejks.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jyoumei.cn/Article/details/gtknwghhnp.html

[N08] 生成全排列
来源：http://dali.yanxiufei.cn/Article/details/gtalldigvc.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrozevtk.html

PHP:  // 手写递归交换
来源：http://dali.cucudq.cn/Article/details/gtdwvuvedj.html

JS:   // 手写回溯递归
来源：http://dali.gaohongyu789.top/Article/details/gtdcsuuabc.html

TS:   // 手写回溯递归
来源：http://dali.hammf.cn/Article/details/gtwypoyhol.html

Java: // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtogqrueml.html

Go:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtucxsrwao.html

Ruby: arr.permutation.to_a
来源：http://dali.bjfxy.top/Article/details/gtivnehpmy.html

C#:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gttbfmumse.html

[N09] 栈与队列
来源：http://dali.yueranfly.top/Article/details/gtgmrneyzv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.hysaishi.cn/Article/details/gtxxgmuhnb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gtixntydaj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtctauyuha.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shzxlz.cn/Article/details/gtuspslsyu.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yuanzhike.top/Article/details/gtgflpgawa.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.iojbl.cn/Article/details/gtvllgucii.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gtdznkxyge.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigfzy.top/Article/details/gtsalzbbwl.html

[N10] 链表节点定义
来源：http://dali.cucudq.cn/Article/details/gtdzmomewz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.iojbl.cn/Article/details/gtkwsmehtt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jinqigfzy.top/Article/details/gtsccdfuzz.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.andypj.xyz/Article/details/gttjajvwlg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.sufxvd.cn/Article/details/gtxzmaeyuh.html

Java: class Node { int v; Node next; }
来源：http://dali.jinqigfzy.top/Article/details/gtailuzxkf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.xuetiantiany.cn/Article/details/gtdpnqnjsy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.aibaodan.cn/Article/details/gtfzobxbtw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.cqqwz.cn/Article/details/gtpfbgxjow.html

[N11] 二叉树中序遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtocknpvip.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yuxming.cn/Article/details/gtccchevkg.html

PHP:  // 手写递归函数
来源：http://dali.bjfxy.top/Article/details/gtoyllpcgn.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhengqikj.top/Article/details/gtjtwxjlry.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gticdoxuut.html

Java: // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtysnappzg.html

Go:   // 手写递归
来源：http://dali.zhiwuduotai.top/Article/details/gthmegddei.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.tanke756.top/Article/details/gtphmlbqlj.html

C#:   // 手写递归
来源：http://dali.gogol.net.cn/Article/details/gtcvfeajfq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjlycwnk.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hnqzz.top/Article/details/gtnuzxdxxz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gotoacloud.top/Article/details/gtzjtueclf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacjxmwhr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yangfankeji.com/Article/details/gtiktlxtbx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gtuniwyoan.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.pengpengdd.cyou/Article/details/gtwkehuqqc.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yueranfly.top/Article/details/gtobvumjjl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gtbbklnmbc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtstflfpci.html

O. 并发与异步
来源：http://dali.cashguo.top/Article/details/gtafnvuvvb.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtbomypkkx.html

[O01] 启动一个线程
来源：http://dali.cqqwz.cn/Article/details/gtglpucvsy.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.chenlongwang.top/Article/details/gtmwudvwvt.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxsqyxbfp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.xuanzx.com/Article/details/gtryfbaubn.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gteevggrgv.html

Java: new Thread(() -> f()).start()
来源：http://dali.andypj.xyz/Article/details/gtydobptbk.html

Go:   go f()
来源：http://dali.ivvv.top/Article/details/gtagvsragx.html

Ruby: Thread.new { f }
来源：http://dali.xuanzx.com/Article/details/gtdezwllih.html

C#:   Task.Run(() => F());
来源：http://dali.xylfe.cn/Article/details/gtzwegsyvw.html

[O02] 使用线程池
来源：http://dali.zhijiandao.cn/Article/details/gtcqysnqbk.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.havefunace.top/Article/details/gtgycjyzxl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yongpay.top/Article/details/gtwoblnucs.html

JS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gtknblsqph.html

TS:   // worker_threads 线程池
来源：http://dali.hnqzz.top/Article/details/gtwfdpdpas.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xziqi.cn/Article/details/gtzjxzpbfg.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sxryk.cn/Article/details/gtuhwigzdq.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.vqdsnc.cn/Article/details/gtfczqkfow.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hysaishi.cn/Article/details/gtgbreniqe.html

[O03] 加锁保护共享数据
来源：http://dali.haohaochexian.top/Article/details/gtihxsyjjt.html

Py:   with lock: shared += 1
来源：http://dali.gogol.net.cn/Article/details/gtjfebseel.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.ppjwa.cn/Article/details/gtzyajjfzm.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnxiangtu.top/Article/details/gtdmbrfcgk.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtakdfgzxj.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhengqikj.top/Article/details/gtvoksebgb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.tian-w.cn/Article/details/gtlofevqfl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.nanxinkj.top/Article/details/gtdenosrkr.html

C#:   lock (gate) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxnmlhtec.html

[O04] 定义异步函数并等待
来源：http://dali.havefunace.top/Article/details/gtpcdbretv.html

Py:   async def f():⏎    await g()
来源：http://dali.hfpthk.cn/Article/details/gtotoxriwk.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhixingplan.top/Article/details/gthhigrlgy.html

JS:   async function f() { await g(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzrwfixc.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.haohaochexian.top/Article/details/gtlxveawvx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.9152youxi.cn/Article/details/gthyumoccz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.guannengcc.top/Article/details/gtismqmlfj.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tianlin.xyz/Article/details/gtagmkejdj.html

C#:   async Task F() { await G(); }
来源：http://dali.hysaishi.cn/Article/details/gtzfvpmyqc.html

[O05] 并发执行并等待全部完成
来源：http://dali.havefunace.top/Article/details/gtbcvyjncr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.quarkkingdee.top/Article/details/gtpvyrceif.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.smart0.xyz/Article/details/gtofluqkdg.html

JS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtcsstaoaw.html

TS:   await Promise.all(tasks)
来源：http://dali.hfpthk.cn/Article/details/gtkvkkaavf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.daxiang520.top/Article/details/gtlgkvnkit.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.pengpengdd.cyou/Article/details/gttcyrbuph.html

Ruby: threads.map(&:join)
来源：http://dali.vqdsnc.cn/Article/details/gthmcmpfac.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigufen.top/Article/details/gtmkldhowa.html

[O06] 使用进程池
来源：http://dali.yj20258888.top/Article/details/gtevigdirb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.hysaishi.cn/Article/details/gtyqhucqwt.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.yueranfly.top/Article/details/gtnfeoqygv.html

JS:   // child_process / cluster 模块
来源：http://dali.chenzaomai.com/Article/details/gtjvadjejz.html

TS:   // child_process / cluster 模块
来源：http://dali.hywenlv.cn/Article/details/gtgckomklm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jqgfzy.top/Article/details/gtvfguxros.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.gogol.net.cn/Article/details/gtqujfrhkh.html

Ruby: // fork 块
来源：http://dali.sysykeji.top/Article/details/gtuvvibvct.html

C#:   Parallel.For
来源：http://dali.daxiang520.top/Article/details/gtlubsilme.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxwxwxqaz.html

P. 常用工具函数
来源：http://dali.yvedp.cn/Article/details/gtixroktfm.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtbpmmps.html

[P01] 生成 UUID
来源：http://dali.shuidangran.top/Article/details/gtfmvafhqy.html

Py:   str(uuid.uuid4())
来源：http://dali.iojbl.cn/Article/details/gtpesolicl.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shangyingyoupin.top/Article/details/gtalyggeqi.html

JS:   crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtdzjiywns.html

TS:   crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gtgvkjbzlh.html

Java: UUID.randomUUID().toString()
来源：http://dali.chenzaomai.com/Article/details/gtbcsthpxe.html

Go:   // 用 github.com/google/uuid
来源：http://dali.xziqi.cn/Article/details/gtvzgkspka.html

Ruby: SecureRandom.uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrpjupyq.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsdjvinz.html

[P02] MD5 / SHA256 摘要
来源：http://dali.gogol.net.cn/Article/details/gtwofiebji.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.redwolf501.top/Article/details/gtwziclgms.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.iojbl.cn/Article/details/gthcttglcv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hfpthk.cn/Article/details/gtcctrojpc.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.316326.xyz/Article/details/gtmsnzlzfl.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gotoacloud.top/Article/details/gthvcgsiwx.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.iojbl.cn/Article/details/gttngljkhx.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dashuyun.cn/Article/details/gtuzwlcpms.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.svipenyu.cn/Article/details/gthghaoeed.html

[P03] 生成短随机字符串
来源：http://dali.zhijiandao.cn/Article/details/gtjwlggzso.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.hongshengwenyu.top/Article/details/gthatgwryh.html


<!-- 参考信息 -->