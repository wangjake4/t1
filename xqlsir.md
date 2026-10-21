代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.xuanzx.com/Article/details/gtjkdvxmll.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.daxiang520.top/Article/details/gtfhzavuix.html

[L05] 上传文件（multipart）
来源：http://dali.dashuyun.cn/Article/details/gtagqmcffw.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.yj202588.top/Article/details/gtjbvnlhky.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinqigfzy.top/Article/details/gtzmhubkta.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.guowangkeji.top/Article/details/gtjoewrnis.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gtzhjnkeng.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.shzxlz.cn/Article/details/gtcjwmfscq.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqjrmwkxr.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zdqjudy.top/Article/details/gtyoeiasod.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtsqyguwie.html

[L06] 解析响应为 JSON
来源：http://dali.ehwqpu.com/Article/details/gtaeqiwijh.html

Py:   resp.json()
来源：http://dali.316326.xyz/Article/details/gtmkuogncg.html

PHP:  json_decode($body, true);
来源：http://dali.ehwqpu.com/Article/details/gtoxytrrjl.html

JS:   await resp.json()
来源：http://dali.birdmap.top/Article/details/gtwvmjxvnf.html

TS:   await resp.json()
来源：http://dali.vqdsnc.cn/Article/details/gtyylupfbx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ybcxt.top/Article/details/gtuinygshg.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shuidangran.top/Article/details/gtkojayynt.html

Ruby: JSON.parse(resp.body)
来源：http://dali.ppjwa.cn/Article/details/gthcqvfkhn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyngqouu.html

[L07] 处理 HTTP 状态码
来源：http://dali.meibo888.top/Article/details/gtaiwpoxdl.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gtzzybrxva.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.bjfxy.top/Article/details/gtvfmyjwpq.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gthgokwpqz.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gtoblfdzgs.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gtmwsdnuqz.html

Go:   resp.StatusCode
来源：http://dali.chenzaomai.com/Article/details/gtxccsvofm.html

Ruby: resp.code.to_i
来源：http://dali.hnxiangtu.top/Article/details/gtzlhzajmu.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtkrbatlqo.html

[L08] 并发请求多个地址
来源：http://dali.zhongyouzk.top/Article/details/gtrsebggkk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xylfe.cn/Article/details/gtnoyrrmvd.html

PHP:  curl_multi_init() 系列
来源：http://dali.jiagoushi.top/Article/details/gtzqngsnpc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtlwvxujgu.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtwfxwbqil.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tianlin.xyz/Article/details/gtejnwvmdv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.9152youxi.cn/Article/details/gtskoptcpz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.c1oappe.top/Article/details/gthcrglacr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.wangdashe.top/Article/details/gtaurhgwwj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gthjofsdqq.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwgnolai.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtiokckxpc.html

[M01] 读取命令行参数
来源：http://dali.shangyingyoupin.top/Article/details/gtcuekunbs.html

Py:   sys.argv[1:]
来源：http://dali.daria6918.cn/Article/details/gtghitbmpi.html

PHP:  $argv;  $argc;
来源：http://dali.chenlongwang.top/Article/details/gtkgyfdcvj.html

JS:   process.argv.slice(2)
来源：http://dali.zhijiandao.cn/Article/details/gtflgprkkz.html

TS:   process.argv.slice(2)
来源：http://dali.yangfankeji.com/Article/details/gtsnoxikvz.html

Java: args 数组（main 方法参数）
来源：http://dali.cheryme.top/Article/details/gtztitghoy.html

Go:   os.Args[1:]
来源：http://dali.redwolf501.top/Article/details/gthnrztqkl.html

Ruby: ARGV
来源：http://dali.zhongyouzk.top/Article/details/gttyoxwhmr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shanyushiyangtech.top/Article/details/gttfcpsuna.html

[M02] 读取环境变量
来源：http://dali.cheryme.top/Article/details/gtxacstuex.html

Py:   os.environ.get("HOME")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvipbjvuu.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.cqqwz.cn/Article/details/gtzdaykqot.html

JS:   process.env.HOME
来源：http://dali.redwolf501.top/Article/details/gthshrwcsu.html

TS:   process.env.HOME
来源：http://dali.yj20258888.top/Article/details/gtovxluzje.html

Java: System.getenv("HOME")
来源：http://dali.sysykeji.top/Article/details/gtepoydhix.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258.top/Article/details/gtbesktvge.html

Ruby: ENV["HOME"]
来源：http://dali.jqgfzy.top/Article/details/gtidjcnrbb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.c1oappe.top/Article/details/gtwwnntleb.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gtytqbkasm.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjktkkpz.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.hfpthk.cn/Article/details/gtnstgigne.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gttspbglxp.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hywenlv.cn/Article/details/gtkholxbtp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.mhx1999.top/Article/details/gtutaltzhn.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ehwqpu.com/Article/details/gtabushrrf.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.gotoacloud.top/Article/details/gtpudlqeir.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gtknrktccw.html

[M04] 获取当前工作目录
来源：http://dali.yj202588.top/Article/details/gtmgetemac.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gtcdpjzvuf.html

PHP:  getcwd();
来源：http://dali.tanke756.top/Article/details/gtafmibsll.html

JS:   process.cwd()
来源：http://dali.fzhhl.top/Article/details/gtwbgbrsjb.html

TS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gtpfzfhvnh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hywenlv.cn/Article/details/gtcbqikcat.html

Go:   os.Getwd()
来源：http://dali.cdnleiting.top/Article/details/gtfzoueafg.html

Ruby: Dir.pwd
来源：http://dali.feifeiyinyue.top/Article/details/gtaekdicdu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.sufxvd.cn/Article/details/gtljpfoghb.html

[M05] 设置退出码
来源：http://dali.jianghu66.top/Article/details/gtquttcspl.html

Py:   sys.exit(1)
来源：http://dali.sweek.top/Article/details/gtxacwmakf.html

PHP:  exit(1);
来源：http://dali.jqgfzy.top/Article/details/gtxhxpyraj.html

JS:   process.exit(1)
来源：http://dali.haohaochexian.top/Article/details/gtwevawrtp.html

TS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtrpjfwohn.html

Java: System.exit(1)
来源：http://dali.nanxinkj.top/Article/details/gtqqfmodyg.html

Go:   os.Exit(1)
来源：http://dali.jqgfzy.top/Article/details/gtiorbuhcb.html

Ruby: exit 1
来源：http://dali.jiagoushi.top/Article/details/gtycusyjhc.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.nanxuanxn.top/Article/details/gtokkujwat.html

[M06] 向标准错误输出
来源：http://dali.yuxming.cn/Article/details/gthwdzkozg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtecdtcovt.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.c1oappe.top/Article/details/gtjazdilam.html

JS:   console.error("err")
来源：http://dali.fzhhl.top/Article/details/gtwcsxdavb.html

TS:   console.error("err")
来源：http://dali.zycfv.cn/Article/details/gtrwbmljic.html

Java: System.err.println("err")
来源：http://dali.snrcjt.cn/Article/details/gtimadevsf.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gtqbfsxoff.html

Ruby: warn "err"
来源：http://dali.shanyushiyangkeji.top/Article/details/gthocnsefg.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.dashuyun.cn/Article/details/gthstaeena.html

[M07] 判断是否为主入口
来源：http://dali.shzxlz.cn/Article/details/gtgrpijvaj.html

Py:   if __name__ == "__main__":
来源：http://dali.pengpengdd.cyou/Article/details/gtswglhrms.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yueranfly.top/Article/details/gtkqoqjiuv.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gtelviiijf.html

TS:   require.main === module
来源：http://dali.sweek.top/Article/details/gtpcqhgorh.html

Java: public static void main(String[] args)
来源：http://dali.xuetiantiany.cn/Article/details/gtqhrzqjbg.html

Go:   func main()
来源：http://dali.xuetiantiany.cn/Article/details/gtkhjtgxju.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.tianlin.xyz/Article/details/gtqmprjcho.html

C#:   static void Main(string[] args)
来源：http://dali.chenzaomai.com/Article/details/gtoxiwsoyb.html

[M08] 获取系统与运行时信息
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvlwnptx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgufenzy.top/Article/details/gtidhjhjco.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cashguo.top/Article/details/gthegghzin.html

JS:   process.platform;  process.version
来源：http://dali.birdmap.top/Article/details/gtiwctwiid.html

TS:   process.platform;  process.version
来源：http://dali.snrcjt.cn/Article/details/gtwqbugwfi.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sxryk.cn/Article/details/gtgllrqhev.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.shuidangran.top/Article/details/gtmfjypjcx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhijiandao.cn/Article/details/gtzeqxbali.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.guannengcc.top/Article/details/gthhbluxok.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gthhmobnjm.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gtfsxmsxpc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtptuofieb.html

[N01] 二分查找（有序数组）
来源：http://dali.birdmap.top/Article/details/gthvpvfiwa.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtuhqloiac.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.birdmap.top/Article/details/gtwkbvtihv.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtfmmgmbex.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.wangdashe.top/Article/details/gthwooffqg.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.fengsongda.top/Article/details/gtqqpgegyk.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gtlswsdszk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.gogol.net.cn/Article/details/gtcgspjskc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtgllsaywj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenzaomai.com/Article/details/gtnrbnfbsr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gtdpnedgvt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbvosqcb.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gtdyielhrq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tanke756.top/Article/details/gtlubkkcav.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tanke756.top/Article/details/gtdhpypugo.html

Go:   slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtkmdxgkwh.html

Ruby: arr.sort
来源：http://dali.ppjwa.cn/Article/details/gtxrnrxdki.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cdnleiting.top/Article/details/gtnghqsddn.html

[N03] 快速排序（分治示例）
来源：http://dali.cucudq.cn/Article/details/gtgmpuiwyp.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuanzx.com/Article/details/gtbpzidzqo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gtytblnmos.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtdeuuukzu.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yanxiufei.cn/Article/details/gtufurltoo.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gtphhcszjg.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxinkj.top/Article/details/gtrsgsigmf.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yongpay.top/Article/details/gtqtmpupju.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhongyouzk.top/Article/details/gtcosrqvmr.html

[N04] 斐波那契数列
来源：http://dali.fengsongda.top/Article/details/gtkguubjeq.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gtnqdueriv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sweek.top/Article/details/gtvnwwkeec.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gtekocwotc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdocjzbr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbsonmcvd.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gtuoshpmgd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcirhogds.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtextzqpzy.html

[N05] 最大公约数
来源：http://dali.guannengcc.top/Article/details/gtrnmmlkxl.html

Py:   math.gcd(a, b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxwamcje.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.nwbrower.top/Article/details/gtfyhyolvw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.mhx1999.top/Article/details/gtrpthalgm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtiesmgxfd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.havefunace.top/Article/details/gtbmmofoel.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.quarkkingdee.top/Article/details/gtdwrbthcl.html

Ruby: a.gcd(b)
来源：http://dali.ydzc1.top/Article/details/gtawcbkxit.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hongshengwenyu.top/Article/details/gthuzhvdje.html

[N06] 判断回文字符串
来源：http://dali.hfpthk.cn/Article/details/gtkblhmzwq.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gtclplkndl.html

PHP:  $s === strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gtcmnqjzhq.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtmbixygzs.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gtxzdhlaoo.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cqqwz.cn/Article/details/gtribtlgoo.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtgepggcmo.html

Ruby: s == s.reverse
来源：http://dali.tanke756.top/Article/details/gtnbrnzikg.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjszhdvbt.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gtxumwpkmz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gtmbogzzty.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jinghuilouyu.cn/Article/details/gtkyeznqif.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.daria6918.cn/Article/details/gtlxwhmxci.html

TS:   // 手写 Map<string, number>
来源：http://dali.yj202588.top/Article/details/gtdpwbfubj.html

Java: // 手写 HashMap
来源：http://dali.ywan-chungtsiang.top/Article/details/gttoxfdbtp.html

Go:   // 手写 map[int]int
来源：http://dali.redwolf501.top/Article/details/gtyklhyruo.html

Ruby: // 手写 Hash
来源：http://dali.jinqigufen.top/Article/details/gtsrrvcckb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cdnleiting.top/Article/details/gtvklbnirv.html

[N08] 生成全排列
来源：http://dali.feifeiyinyue.top/Article/details/gtymnnbulv.html

Py:   itertools.permutations(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtqnhjclsy.html

PHP:  // 手写递归交换
来源：http://dali.jyoumei.cn/Article/details/gtwahedsfu.html

JS:   // 手写回溯递归
来源：http://dali.zhoulong.xyz/Article/details/gtpxiejtqb.html

TS:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gtosalpeyd.html

Java: // 手写回溯递归
来源：http://dali.hfpthk.cn/Article/details/gtnomsoqkj.html

Go:   // 手写回溯递归
来源：http://dali.quarkkingdee.top/Article/details/gtrrbxbiqc.html

Ruby: arr.permutation.to_a
来源：http://dali.yongpay.top/Article/details/gtmmyexday.html

C#:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtudsvezya.html

[N09] 栈与队列
来源：http://dali.wangdashe.top/Article/details/gtknzcpwee.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauqafsfb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zdqjudy.top/Article/details/gtciywlyzn.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gtykzdkktu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.c1oappe.top/Article/details/gtqvizgrvt.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtfifqukot.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.tanke756.top/Article/details/gtbheicxry.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphhjmbst.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gzhubu.top/Article/details/gtesafuvqa.html

[N10] 链表节点定义
来源：http://dali.fzhhl.top/Article/details/gtmepkjupi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ivvv.top/Article/details/gtnjtqcwca.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.svipenyu.cn/Article/details/gtkhiwswvb.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.gzhubu.top/Article/details/gtideewjcp.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ehwqpu.com/Article/details/gthqqkivhl.html

Java: class Node { int v; Node next; }
来源：http://dali.xuetiantiany.cn/Article/details/gtzqstqnea.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.meibo888.top/Article/details/gtlgfbubft.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.pycfn.com/Article/details/gtomqvqsft.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltejjscv.html

[N11] 二叉树中序遍历
来源：http://dali.iojbl.cn/Article/details/gtguobcuik.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jiagoushi.top/Article/details/gttfprvpaz.html

PHP:  // 手写递归函数
来源：http://dali.mhx1999.top/Article/details/gtzuaffztr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gtwjmerqtz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwigdihad.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gtpfihmwvo.html

Go:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gtrsldmgck.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zdqjudy.top/Article/details/gtvpzhfjvl.html

C#:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gtibqskvfq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hywenlv.cn/Article/details/gtcxabthjj.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zhiwuduotai.top/Article/details/gtyithfqye.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhixingplan.top/Article/details/gtwpxlrtvr.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gtwygptauw.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hfpthk.cn/Article/details/gtniamlkic.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.ivvv.top/Article/details/gtlcpqqhcf.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gtbtwbagpr.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yueranfly.top/Article/details/gttejfsiut.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.daxiang520.top/Article/details/gtysvqmdzg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtxlznwtry.html

O. 并发与异步
来源：http://dali.yongpay.top/Article/details/gtrwxxiekv.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtexdghivd.html

[O01] 启动一个线程
来源：http://dali.aibaodan.cn/Article/details/gtuyvgpuiu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zdqjudy.top/Article/details/gtbsknzrou.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.tian-w.cn/Article/details/gtdumoduzj.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cdnleiting.top/Article/details/gtunezzblp.html

TS:   // 同 JS
来源：http://dali.ydzc1.top/Article/details/gtyfohpdgd.html

Java: new Thread(() -> f()).start()
来源：http://dali.vqdsnc.cn/Article/details/gtnlbgfrfj.html

Go:   go f()
来源：http://dali.smart0.xyz/Article/details/gtjfdojvpg.html

Ruby: Thread.new { f }
来源：http://dali.fengsongda.top/Article/details/gtxrqhvukp.html

C#:   Task.Run(() => F());
来源：http://dali.dashuyun.cn/Article/details/gtdyyvahzk.html

[O02] 使用线程池
来源：http://dali.xinyue.icu/Article/details/gtjwibpdvg.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.pycfn.com/Article/details/gtxaqtgcxx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gtgixmnypg.html

JS:   // worker_threads 线程池
来源：http://dali.gaohongyu789.top/Article/details/gtwhhtwyko.html

TS:   // worker_threads 线程池
来源：http://dali.jqgfzy.top/Article/details/gtjvntboiz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jiagoushi.top/Article/details/gtdywllqom.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sysykeji.top/Article/details/gtjvsqfnzx.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.sufxvd.cn/Article/details/gtdgkavrxp.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.dashuyun.cn/Article/details/gtowzxebzj.html

[O03] 加锁保护共享数据
来源：http://dali.yj20258888.top/Article/details/gtvdymxdpc.html

Py:   with lock: shared += 1
来源：http://dali.feifeiyinyue.top/Article/details/gttqgsxmgs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.cashguo.top/Article/details/gtyooxvsus.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jyoumei.cn/Article/details/gtuxakswfm.html

TS:   // 同 JS
来源：http://dali.tanke756.top/Article/details/gtrcwbcgdt.html

Java: synchronized (this) { shared++; }
来源：http://dali.shuidangran.top/Article/details/gtfsjawszo.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.9152youxi.cn/Article/details/gtbwtdswqm.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtdhnohzuk.html

C#:   lock (gate) { shared++; }
来源：http://dali.nanxuanxn.top/Article/details/gtqglalaaq.html

[O04] 定义异步函数并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrpajrqza.html

Py:   async def f():⏎    await g()
来源：http://dali.yanxiufei.cn/Article/details/gtsqokljbz.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.pengpengdd.cyou/Article/details/gterudmijs.html

JS:   async function f() { await g(); }
来源：http://dali.c1oappe.top/Article/details/gthcfaymxs.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.guowangkeji.top/Article/details/gtpygeqkvc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtveshdspt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgfzy.top/Article/details/gtcuunemew.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gogol.net.cn/Article/details/gteisctzvw.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxinkj.top/Article/details/gtujmkfckv.html

[O05] 并发执行并等待全部完成
来源：http://dali.aizwys.cn/Article/details/gtuaxjojnk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.dashuyun.cn/Article/details/gtrpycfwey.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.guowangkeji.top/Article/details/gtkwopinxv.html

JS:   await Promise.all(tasks)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddyetjmy.html

TS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gtsbljmfxi.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuanzx.com/Article/details/gtszoierin.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhxciaml.html

Ruby: threads.map(&:join)
来源：http://dali.bjfxy.top/Article/details/gtmagmkals.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jqgfzy.top/Article/details/gtmmpsqrwq.html

[O06] 使用进程池
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxnjvnor.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.jianghu66.top/Article/details/gtatpisziw.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.hfpthk.cn/Article/details/gtcygchksw.html

JS:   // child_process / cluster 模块
来源：http://dali.aizwys.cn/Article/details/gtgtgbimtk.html

TS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gtuunvthje.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xziqi.cn/Article/details/gtajfggikn.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.cdnleiting.top/Article/details/gtcwmhkgbt.html

Ruby: // fork 块
来源：http://dali.9152youxi.cn/Article/details/gtgshdznic.html

C#:   Parallel.For
来源：http://dali.nanxuanxn.top/Article/details/gtbmljfmqg.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtvunqpfek.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gtwduuxsib.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtvsdakvwq.html

[P01] 生成 UUID
来源：http://dali.hysaishi.cn/Article/details/gtsgcxfhmy.html

Py:   str(uuid.uuid4())
来源：http://dali.sysykeji.top/Article/details/gtwpdxvkdt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.meibo888.top/Article/details/gtfdirhobx.html

JS:   crypto.randomUUID()
来源：http://dali.sufxvd.cn/Article/details/gtmqufrndp.html

TS:   crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gttcdjlwkn.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodetqpma.html

Go:   // 用 github.com/google/uuid
来源：http://dali.guannengcc.top/Article/details/gtemxitnic.html

Ruby: SecureRandom.uuid
来源：http://dali.9152youxi.cn/Article/details/gtlhkbwhhp.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.ydzc1.top/Article/details/gtwohqbapi.html

[P02] MD5 / SHA256 摘要
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfcbuntr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.vqdsnc.cn/Article/details/gtqazfrfic.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yangfankeji.com/Article/details/gthellfwyu.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.daxiang520.top/Article/details/gthrejmevq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.pengpengdd.cyou/Article/details/gtvwrubcyg.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sufxvd.cn/Article/details/gtfcsagxnn.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.cdnleiting.top/Article/details/gtfbnbrhxv.html


<!-- 参考信息 -->