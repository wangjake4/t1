代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhengqikj.top/Article/details/gtolflgntx.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.quarkkingdee.top/Article/details/gtryxaprsr.html

[L05] 上传文件（multipart）
来源：http://dali.kuanghao11.cn/Article/details/gtfepzpimg.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.andypj.xyz/Article/details/gtfsrsuyip.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.quarkkingdee.top/Article/details/gtctpqvxsj.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gtzoultzrk.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.vqdsnc.cn/Article/details/gtoqisdikj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.havefunace.top/Article/details/gtwckdjvsm.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.cheryme.top/Article/details/gtigxxphwv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.9152youxi.cn/Article/details/gtxxwjaxff.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ydzc1.top/Article/details/gtflkjftez.html

[L06] 解析响应为 JSON
来源：http://dali.yueranfly.top/Article/details/gtgznkkwxq.html

Py:   resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gtupxyfvme.html

PHP:  json_decode($body, true);
来源：http://dali.gaohongyu789.top/Article/details/gtilfmszpd.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtwayaxpir.html

TS:   await resp.json()
来源：http://dali.c1oappe.top/Article/details/gtdcrcghaj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtohoruxun.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gtkcoxntfe.html

Ruby: JSON.parse(resp.body)
来源：http://dali.gogol.net.cn/Article/details/gtlsziidcu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwqrakpm.html

[L07] 处理 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gttbgklfev.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqnquyrx.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhixingplan.top/Article/details/gtliyexqxg.html

JS:   resp.ok;  resp.status
来源：http://dali.jinqigufen.top/Article/details/gtcnnwkkgj.html

TS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gtgzqlygbx.html

Java: resp.statusCode()
来源：http://dali.fengsongda.top/Article/details/gtzeaovajt.html

Go:   resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gtoxuegmqp.html

Ruby: resp.code.to_i
来源：http://dali.gogol.net.cn/Article/details/gtjllqggjh.html

C#:   (int)resp.StatusCode
来源：http://dali.hongshengwenyu.top/Article/details/gtsqpchkrj.html

[L08] 并发请求多个地址
来源：http://dali.cheryme.top/Article/details/gtrrlxogqg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuanzhike.top/Article/details/gtkixdvtll.html

PHP:  curl_multi_init() 系列
来源：http://dali.xuetiantiany.cn/Article/details/gtbkocvadr.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cashguo.top/Article/details/gtqimwdczl.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jiagoushi.top/Article/details/gtoyctdgto.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesymdhoe.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jlsjyb.cn/Article/details/gtpehhpvvi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhongyouzk.top/Article/details/gtvpxlmlbx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.nwbrower.top/Article/details/gthcephfky.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtwnepmxzl.html

M. 命令行 / 进程 / 环境
来源：http://dali.haohaochexian.top/Article/details/gtwrfuffgj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlegcyroa.html

[M01] 读取命令行参数
来源：http://dali.yvedp.cn/Article/details/gtsnouirwc.html

Py:   sys.argv[1:]
来源：http://dali.jinqigfzy.top/Article/details/gtarmpdeej.html

PHP:  $argv;  $argc;
来源：http://dali.gogol.net.cn/Article/details/gtryzafwnl.html

JS:   process.argv.slice(2)
来源：http://dali.hywenlv.cn/Article/details/gtyclplkbs.html

TS:   process.argv.slice(2)
来源：http://dali.quarkkingdee.top/Article/details/gtnnndkqwc.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258888.top/Article/details/gtgooegctw.html

Go:   os.Args[1:]
来源：http://dali.zhengqikj.top/Article/details/gtoiaokyqy.html

Ruby: ARGV
来源：http://dali.jqgfzy.top/Article/details/gtdiubkdzp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtavecnnob.html

[M02] 读取环境变量
来源：http://dali.dashuyun.cn/Article/details/gtjhwiifth.html

Py:   os.environ.get("HOME")
来源：http://dali.xinyue.icu/Article/details/gtxurawsjl.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gttyrmzweo.html

JS:   process.env.HOME
来源：http://dali.hnqzz.top/Article/details/gtndtkcuae.html

TS:   process.env.HOME
来源：http://dali.birdmap.top/Article/details/gtmoddcwzw.html

Java: System.getenv("HOME")
来源：http://dali.fengsongda.top/Article/details/gtxkkfddwg.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.zhijiandao.cn/Article/details/gtdpsxfpjq.html

Ruby: ENV["HOME"]
来源：http://dali.hywenlv.cn/Article/details/gtkyvqiyjk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.daxiang520.top/Article/details/gtqpxyrliz.html

[M03] 执行外部命令
来源：http://dali.fengsongda.top/Article/details/gtxvjhrhyo.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.andypj.xyz/Article/details/gtpvkkjmhj.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.pycfn.com/Article/details/gtsrvtriep.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhixingplan.top/Article/details/gttobplqgj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.cqqwz.cn/Article/details/gtwzqmcavj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pycfn.com/Article/details/gtayjeutuj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yvedp.cn/Article/details/gtubgbtiib.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnqzz.top/Article/details/gtanctagqs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hfpthk.cn/Article/details/gtckhbbfas.html

[M04] 获取当前工作目录
来源：http://dali.sysykeji.top/Article/details/gthrkzwgrf.html

Py:   os.getcwd()
来源：http://dali.shanyushiyangtech.top/Article/details/gttblchxjf.html

PHP:  getcwd();
来源：http://dali.jinghuilouyu.cn/Article/details/gtblguwiqj.html

JS:   process.cwd()
来源：http://dali.jyoumei.cn/Article/details/gtmfaimssq.html

TS:   process.cwd()
来源：http://dali.cqqwz.cn/Article/details/gtgltbhzcq.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shangyingyoupin.top/Article/details/gtairxxzft.html

Go:   os.Getwd()
来源：http://dali.gogol.net.cn/Article/details/gtuaatexcc.html

Ruby: Dir.pwd
来源：http://dali.nanxinkj.top/Article/details/gtyyaqvvgb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.kuanghao11.cn/Article/details/gtevxtlydb.html

[M05] 设置退出码
来源：http://dali.gzhubu.top/Article/details/gtafwevgbo.html

Py:   sys.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtulpwtzgr.html

PHP:  exit(1);
来源：http://dali.nanxuanxn.top/Article/details/gtdeuosxnq.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtrfkgvwga.html

TS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtxhmbswcu.html

Java: System.exit(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtbiduaajo.html

Go:   os.Exit(1)
来源：http://dali.hfpthk.cn/Article/details/gtgthglxga.html

Ruby: exit 1
来源：http://dali.tianlin.xyz/Article/details/gtgszxvfpx.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.aibaodan.cn/Article/details/gtmparkqvz.html

[M06] 向标准错误输出
来源：http://dali.redwolf501.top/Article/details/gtzeolcbsm.html

Py:   print("err", file=sys.stderr)
来源：http://dali.cdnleiting.top/Article/details/gtlycsxibj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xinyue.icu/Article/details/gtrtjvsxax.html

JS:   console.error("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gtlgamtuwc.html

TS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gtyyqgcxaw.html

Java: System.err.println("err")
来源：http://dali.andypj.xyz/Article/details/gtljzahlnk.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jyoumei.cn/Article/details/gterolnwcq.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gttujoliim.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shzxlz.cn/Article/details/gteaevwsxc.html

[M07] 判断是否为主入口
来源：http://dali.gotoacloud.top/Article/details/gteiwflyof.html

Py:   if __name__ == "__main__":
来源：http://dali.ppjwa.cn/Article/details/gtjpfrveav.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.pengpengdd.cyou/Article/details/gtgduwhczg.html

JS:   require.main === module
来源：http://dali.jlsjyb.cn/Article/details/gtcxamgakr.html

TS:   require.main === module
来源：http://dali.meibo888.top/Article/details/gtrjotavtt.html

Java: public static void main(String[] args)
来源：http://dali.yuxming.cn/Article/details/gtkvozklxl.html

Go:   func main()
来源：http://dali.c1oappe.top/Article/details/gtsfrhrvey.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jlsjyb.cn/Article/details/gthdwrlsqg.html

C#:   static void Main(string[] args)
来源：http://dali.meibo888.top/Article/details/gtkcdrwzqz.html

[M08] 获取系统与运行时信息
来源：http://dali.tianlin.xyz/Article/details/gtwlvyncjs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jlsjyb.cn/Article/details/gtomffqntu.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.cdnleiting.top/Article/details/gtstdpzoyn.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwwwtklw.html

TS:   process.platform;  process.version
来源：http://dali.jlsjyb.cn/Article/details/gtznpyiaxz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenzaomai.com/Article/details/gtrfgquqxz.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtioxitkug.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkujkjpsi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.wangdashe.top/Article/details/gthphnhgxv.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gthslwjnil.html

N. 数据结构与算法
来源：http://dali.hfpthk.cn/Article/details/gthekhenqm.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtysyhgiml.html

[N01] 二分查找（有序数组）
来源：http://dali.daxiang520.top/Article/details/gttfomcooe.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtmzsnxgdc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpefxzkaq.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gtxooaztag.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.haohaochexian.top/Article/details/gtruwkclzp.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nwbrower.top/Article/details/gtamsddwms.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cashguo.top/Article/details/gtgnfrrpri.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258.top/Article/details/gtawlpidre.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtfifgcmge.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.aibaodan.cn/Article/details/gtpeltodpr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtaffaibfm.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.smart0.xyz/Article/details/gtpqkkftfz.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkihjdgby.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtwfvsjrso.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gtjwxjcmma.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtldttbuuo.html

Ruby: arr.sort
来源：http://dali.nanxuanxn.top/Article/details/gttdhgwzqf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllsmhpoi.html

[N03] 快速排序（分治示例）
来源：http://dali.jlsjyb.cn/Article/details/gtjbwlhvqo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgufenzy.top/Article/details/gtdeeeclwj.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hywenlv.cn/Article/details/gtpxokrxuu.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ehwqpu.com/Article/details/gtprerkqoa.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.wangdashe.top/Article/details/gtuqnqonkf.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.316326.xyz/Article/details/gtqcmcseqa.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jlsjyb.cn/Article/details/gtugcrnsof.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.cashguo.top/Article/details/gtxrbhhrft.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhengqikj.top/Article/details/gtstglxgtr.html

[N04] 斐波那契数列
来源：http://dali.andypj.xyz/Article/details/gtwuyyzvwm.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.cqqwz.cn/Article/details/gtfrxjfmap.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hammf.cn/Article/details/gttsynwojn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gtgwbqwfiq.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.sysykeji.top/Article/details/gtxqrtehor.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtbaawgpjw.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.mhx1999.top/Article/details/gtcnrvtoff.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtxebvabia.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtddmifanz.html

[N05] 最大公约数
来源：http://dali.wangshuangyany.cn/Article/details/gtysxodtsk.html

Py:   math.gcd(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtifhhfoun.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtuquzcrcu.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sxryk.cn/Article/details/gtuuvrqawv.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.andypj.xyz/Article/details/gtiqvxdjuz.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.bjfxy.top/Article/details/gtrejtlrqk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthshweete.html

Ruby: a.gcd(b)
来源：http://dali.gaohongyu789.top/Article/details/gtkkiugrio.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cucudq.cn/Article/details/gtdwsrfpwd.html

[N06] 判断回文字符串
来源：http://dali.yuxming.cn/Article/details/gtmrypzgkt.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtsaiwypuz.html

PHP:  $s === strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gtnpvmaose.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gtcmznpjkw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yuanzhike.top/Article/details/gtjqrjghfe.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.chenjidiqi.icu/Article/details/gtkftmzesg.html

Go:   // 双指针从两端比较
来源：http://dali.iojbl.cn/Article/details/gtawntpvcs.html

Ruby: s == s.reverse
来源：http://dali.smart0.xyz/Article/details/gtbnqcbxxp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gthrgjowgy.html

[N07] 两数之和（返回下标）
来源：http://dali.aizwys.cn/Article/details/gtnwzhrvgg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.zhengqikj.top/Article/details/gtovcwqlgl.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.nanxinkj.top/Article/details/gtaqjpxffx.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.aibaodan.cn/Article/details/gtfskhgvbm.html

TS:   // 手写 Map<string, number>
来源：http://dali.ppjwa.cn/Article/details/gtrlpimgik.html

Java: // 手写 HashMap
来源：http://dali.tianlin.xyz/Article/details/gtugfgimmt.html

Go:   // 手写 map[int]int
来源：http://dali.haohaochexian.top/Article/details/gtgxktvkwt.html

Ruby: // 手写 Hash
来源：http://dali.chenzaomai.com/Article/details/gtnsmgjuik.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.daxiang520.top/Article/details/gtgscepvtd.html

[N08] 生成全排列
来源：http://dali.316326.xyz/Article/details/gtdiwbpfbj.html

Py:   itertools.permutations(arr)
来源：http://dali.tanke756.top/Article/details/gtuhyiryss.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gtguscqusn.html

JS:   // 手写回溯递归
来源：http://dali.kuanghao11.cn/Article/details/gtjttduzaj.html

TS:   // 手写回溯递归
来源：http://dali.zdqjudy.top/Article/details/gtkyovvctt.html

Java: // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtwyinuvox.html

Go:   // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gtrktvhefr.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gtqhprdmje.html

C#:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gtvqedvuxc.html

[N09] 栈与队列
来源：http://dali.sysykeji.top/Article/details/gtcbdawiwl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcqrweai.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fengsongda.top/Article/details/gtayuupmgr.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ivvv.top/Article/details/gtebfjnnsu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gtevnvgnbo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gttjqxtsxk.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhijiandao.cn/Article/details/gtiuvrbmcr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.birdmap.top/Article/details/gtyjxtjois.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.fengsongda.top/Article/details/gtptgstlqh.html

[N10] 链表节点定义
来源：http://dali.aizwys.cn/Article/details/gtrepjgcxk.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.316326.xyz/Article/details/gtthvqizmn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gtmfwxkmxp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.cqqwz.cn/Article/details/gtfilvjjzx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zhoulong.xyz/Article/details/gtbliczgal.html

Java: class Node { int v; Node next; }
来源：http://dali.ppjwa.cn/Article/details/gtcejzdtry.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.kuanghao11.cn/Article/details/gtdttyycgl.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtunmkhfkj.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sufxvd.cn/Article/details/gtzceziucc.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gtxnphcqfi.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.tian-w.cn/Article/details/gtntyleapu.html

PHP:  // 手写递归函数
来源：http://dali.chenzaomai.com/Article/details/gtfrnflbua.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gtmicqynxf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gtptjzdeem.html

Java: // 手写递归
来源：http://dali.aizwys.cn/Article/details/gtagytxvnm.html

Go:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gttambyhxh.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pengpengdd.cyou/Article/details/gtfsngbrfh.html

C#:   // 手写递归
来源：http://dali.yueranfly.top/Article/details/gthbtnkxmq.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjjjcqan.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.hongshengwenyu.top/Article/details/gtqqqvjwzf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.guowangkeji.top/Article/details/gtyhfgqefn.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.wangdashe.top/Article/details/gtryvmzjet.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtghkkqdib.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbxiobmx.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.mhx1999.top/Article/details/gtpvyuxcfp.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yueranfly.top/Article/details/gtromjrdji.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.meibo888.top/Article/details/gthxqlhgiy.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtypkvkpgu.html

O. 并发与异步
来源：http://dali.yvedp.cn/Article/details/gttukjebjz.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtiuiprwif.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonxjkcxg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hywenlv.cn/Article/details/gttjydprzl.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.daria6918.cn/Article/details/gtqqtxegzo.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.shangyingyoupin.top/Article/details/gtjgflknuv.html

TS:   // 同 JS
来源：http://dali.dashuyun.cn/Article/details/gtxkhzlhdn.html

Java: new Thread(() -> f()).start()
来源：http://dali.0kj1m.cn/Article/details/gtggueqjah.html

Go:   go f()
来源：http://dali.quarkkingdee.top/Article/details/gtztjscujs.html

Ruby: Thread.new { f }
来源：http://dali.redwolf501.top/Article/details/gtgmccaonq.html

C#:   Task.Run(() => F());
来源：http://dali.hnxiangtu.top/Article/details/gtbezfymfg.html

[O02] 使用线程池
来源：http://dali.snrcjt.cn/Article/details/gttnmfpxpm.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.daria6918.cn/Article/details/gtngiimgxg.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigufen.top/Article/details/gtqyutlfpm.html

JS:   // worker_threads 线程池
来源：http://dali.jlsjyb.cn/Article/details/gtcjeepryb.html

TS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gtmbuuvfof.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.xinyue.icu/Article/details/gtwecrvpoa.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.chenlongwang.top/Article/details/gtzbyfltdf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedhggkrc.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnqzz.top/Article/details/gtwvnlpqqb.html

[O03] 加锁保护共享数据
来源：http://dali.shangyingyoupin.top/Article/details/gtzyzflaqy.html

Py:   with lock: shared += 1
来源：http://dali.birdmap.top/Article/details/gttgttuunx.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.nanxuanxn.top/Article/details/gtrprsyioe.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zdqjudy.top/Article/details/gtiuvyxvjr.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtufiwyfsp.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgcrsvon.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hfpthk.cn/Article/details/gtnoaktrcg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylhwvdgo.html

C#:   lock (gate) { shared++; }
来源：http://dali.haohaochexian.top/Article/details/gtpvdyczjr.html

[O04] 定义异步函数并等待
来源：http://dali.feifeiyinyue.top/Article/details/gtxmvtyhmt.html

Py:   async def f():⏎    await g()
来源：http://dali.sweek.top/Article/details/gtnfgdwxby.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.cheryme.top/Article/details/gtvlijdbpy.html

JS:   async function f() { await g(); }
来源：http://dali.hnqzz.top/Article/details/gtewsrmpfe.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.316326.xyz/Article/details/gtrqxnglkg.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tianlin.xyz/Article/details/gtrkuwcgqz.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.nanxinkj.top/Article/details/gtslthaqkx.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.birdmap.top/Article/details/gtpoejkkrn.html

C#:   async Task F() { await G(); }
来源：http://dali.havefunace.top/Article/details/gtmngpchfs.html

[O05] 并发执行并等待全部完成
来源：http://dali.yonumen.top/Article/details/gtdhtxwoqr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guowangkeji.top/Article/details/gtvuxkxgbc.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.dianchejie.cn/Article/details/gthwqnnwld.html

JS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gtbxvjmcqu.html

TS:   await Promise.all(tasks)
来源：http://dali.vqdsnc.cn/Article/details/gtjvsidbtd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.xuetiantiany.cn/Article/details/gteobfyyoe.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.hywenlv.cn/Article/details/gtcetixwoy.html

Ruby: threads.map(&:join)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmpbfhfx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.tian-w.cn/Article/details/gtxdkcmfnm.html

[O06] 使用进程池
来源：http://dali.guowangkeji.top/Article/details/gtsnwvbcze.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.0kj1m.cn/Article/details/gtzwulsxoc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cdnleiting.top/Article/details/gthojqcmdx.html

JS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnuarfybg.html

TS:   // child_process / cluster 模块
来源：http://dali.ehwqpu.com/Article/details/gtkvtqokef.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.cheryme.top/Article/details/gttegvjgdd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sxryk.cn/Article/details/gtskqsmnls.html

Ruby: // fork 块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxxtrhje.html

C#:   Parallel.For
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwagxgoi.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gthdqmgaku.html

P. 常用工具函数
来源：http://dali.yongpay.top/Article/details/gtnqrgrnpz.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxhrjyahp.html

[P01] 生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gtxwamgeul.html

Py:   str(uuid.uuid4())
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhlxuqmm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.birdmap.top/Article/details/gtjqkytrpt.html

JS:   crypto.randomUUID()
来源：http://dali.xziqi.cn/Article/details/gtzaprwxtw.html

TS:   crypto.randomUUID()
来源：http://dali.hammf.cn/Article/details/gtoqnawltv.html

Java: UUID.randomUUID().toString()
来源：http://dali.nwbrower.top/Article/details/gthsknpqco.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigfzy.top/Article/details/gtfgjvqtli.html

Ruby: SecureRandom.uuid
来源：http://dali.9152youxi.cn/Article/details/gtgghxifje.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.hfpthk.cn/Article/details/gtinnrhjlo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shangyingyoupin.top/Article/details/gtyzsnsqdr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.meibo888.top/Article/details/gtevltyryp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.zhixingplan.top/Article/details/gtmduvbwei.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.feifeiyinyue.top/Article/details/gtayvxhetl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxqfgkpu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ivvv.top/Article/details/gtxlkexpyz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.shuidangran.top/Article/details/gtiosobrgj.html


<!-- 参考信息 -->