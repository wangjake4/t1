代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gtarwvlavp.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yangfankeji.com/Article/details/gtaapvlxvp.html

[L05] 上传文件（multipart）
来源：http://dali.316326.xyz/Article/details/gtmpiipvbj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdjgbxdjk.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoivuyiln.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cashguo.top/Article/details/gtpoectipi.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jiagoushi.top/Article/details/gtfinggwyk.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj202588.top/Article/details/gtdrulltzk.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinqigufen.top/Article/details/gtnsqtyceh.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.yanxiufei.cn/Article/details/gtogqfuwxc.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtyfbnrnyi.html

[L06] 解析响应为 JSON
来源：http://dali.fengsongda.top/Article/details/gtpqawglbc.html

Py:   resp.json()
来源：http://dali.0kj1m.cn/Article/details/gtvphhfske.html

PHP:  json_decode($body, true);
来源：http://dali.jlsjyb.cn/Article/details/gtgddprirj.html

JS:   await resp.json()
来源：http://dali.gzhubu.top/Article/details/gtcaetzvdm.html

TS:   await resp.json()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjoiqjxj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.sxryk.cn/Article/details/gtvnjtttsy.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xuetiantiany.cn/Article/details/gtfzairysf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhixingplan.top/Article/details/gtcranfncr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gtsrdmkerh.html

[L07] 处理 HTTP 状态码
来源：http://dali.xziqi.cn/Article/details/gtjzgrvwsz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.feifeiyinyue.top/Article/details/gtrromwrny.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhongyouzk.top/Article/details/gtnugwpupg.html

JS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gtqgksfvvh.html

TS:   resp.ok;  resp.status
来源：http://dali.zhengqikj.top/Article/details/gtqygstzqr.html

Java: resp.statusCode()
来源：http://dali.shanyushiyangtech.top/Article/details/gtckwlmyrn.html

Go:   resp.StatusCode
来源：http://dali.wangdashe.top/Article/details/gtraqfexbn.html

Ruby: resp.code.to_i
来源：http://dali.zhongyouzk.top/Article/details/gtzqybajhc.html

C#:   (int)resp.StatusCode
来源：http://dali.jianghu66.top/Article/details/gtjtanixar.html

[L08] 并发请求多个地址
来源：http://dali.jyoumei.cn/Article/details/gtjyzfdjgq.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.gotoacloud.top/Article/details/gtbjzjqjbv.html

PHP:  curl_multi_init() 系列
来源：http://dali.hfpthk.cn/Article/details/gtmdqjyyxj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dashuyun.cn/Article/details/gtyybnnjql.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gtlttabzvn.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tanke756.top/Article/details/gtekjhnnmd.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinqigfzy.top/Article/details/gtitqaeeod.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.kuanghao11.cn/Article/details/gthchuxuxg.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.guowangkeji.top/Article/details/gtujtekgtg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtkeryxyty.html

M. 命令行 / 进程 / 环境
来源：http://dali.zycfv.cn/Article/details/gtfeovroid.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtqiicppoi.html

[M01] 读取命令行参数
来源：http://dali.daxiang520.top/Article/details/gtydejeukx.html

Py:   sys.argv[1:]
来源：http://dali.pengpengdd.cyou/Article/details/gtmzxmmbnh.html

PHP:  $argv;  $argc;
来源：http://dali.daria6918.cn/Article/details/gtvrjcbnht.html

JS:   process.argv.slice(2)
来源：http://dali.xuetiantiany.cn/Article/details/gtsixhcksm.html

TS:   process.argv.slice(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmbzusou.html

Java: args 数组（main 方法参数）
来源：http://dali.fzhhl.top/Article/details/gtvfcglrzu.html

Go:   os.Args[1:]
来源：http://dali.fzhhl.top/Article/details/gtkivbmqwb.html

Ruby: ARGV
来源：http://dali.cdnleiting.top/Article/details/gtfiwgtccs.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gtdzwmvmpr.html

[M02] 读取环境变量
来源：http://dali.tian-w.cn/Article/details/gtltjggixa.html

Py:   os.environ.get("HOME")
来源：http://dali.sxryk.cn/Article/details/gtxsdkjywq.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hysaishi.cn/Article/details/gtjqqwtwev.html

JS:   process.env.HOME
来源：http://dali.shangyingyoupin.top/Article/details/gtgpyxhkfk.html

TS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtkrjcgkjx.html

Java: System.getenv("HOME")
来源：http://dali.zhixingplan.top/Article/details/gtuaazsjja.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yonumen.top/Article/details/gthbuuvafz.html

Ruby: ENV["HOME"]
来源：http://dali.aibaodan.cn/Article/details/gtytvrawge.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtrdahbkfh.html

[M03] 执行外部命令
来源：http://dali.nwbrower.top/Article/details/gtnpkrrrlc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jlsjyb.cn/Article/details/gthiveejin.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fengsongda.top/Article/details/gtpoyupfag.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.bjfxy.top/Article/details/gtzjwkkalj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimluhxma.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.aizwys.cn/Article/details/gtvudqnosm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zdqjudy.top/Article/details/gtluqymgnl.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.9152youxi.cn/Article/details/gtrucemznp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yueranfly.top/Article/details/gtnukufqdw.html

[M04] 获取当前工作目录
来源：http://dali.c1oappe.top/Article/details/gtfkulcuni.html

Py:   os.getcwd()
来源：http://dali.cdnleiting.top/Article/details/gtmzkaflfk.html

PHP:  getcwd();
来源：http://dali.quarkkingdee.top/Article/details/gtckoycubt.html

JS:   process.cwd()
来源：http://dali.hywenlv.cn/Article/details/gtftxbhsar.html

TS:   process.cwd()
来源：http://dali.feifeiyinyue.top/Article/details/gtkilmywyl.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenlongwang.top/Article/details/gtlwmvyyiz.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gteqckmzbz.html

Ruby: Dir.pwd
来源：http://dali.zhixingplan.top/Article/details/gtkmxpqxut.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.9152youxi.cn/Article/details/gtznraieid.html

[M05] 设置退出码
来源：http://dali.jianghu66.top/Article/details/gthofgbitd.html

Py:   sys.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtwyvgujoz.html

PHP:  exit(1);
来源：http://dali.sweek.top/Article/details/gtmkopboep.html

JS:   process.exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtufpbykso.html

TS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gtfxqsjyoa.html

Java: System.exit(1)
来源：http://dali.316326.xyz/Article/details/gttmhnrivo.html

Go:   os.Exit(1)
来源：http://dali.aibaodan.cn/Article/details/gtoerflpai.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gtpvleoaah.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwghqvzt.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gtwrwbyjvn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gtiawjtnnr.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgufenzy.top/Article/details/gtrtzzhwcj.html

JS:   console.error("err")
来源：http://dali.snrcjt.cn/Article/details/gtkrabanlz.html

TS:   console.error("err")
来源：http://dali.ppjwa.cn/Article/details/gtbgjjukuo.html

Java: System.err.println("err")
来源：http://dali.xziqi.cn/Article/details/gtuqsulooc.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbkdufus.html

Ruby: warn "err"
来源：http://dali.pycfn.com/Article/details/gtvmizwvle.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.wangdashe.top/Article/details/gtuxdtnacd.html

[M07] 判断是否为主入口
来源：http://dali.sysykeji.top/Article/details/gtofoodszm.html

Py:   if __name__ == "__main__":
来源：http://dali.haohaochexian.top/Article/details/gtpmjibsgk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwtozkii.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtjtucrswg.html

TS:   require.main === module
来源：http://dali.9152youxi.cn/Article/details/gttgxnummu.html

Java: public static void main(String[] args)
来源：http://dali.ydzc1.top/Article/details/gtsvokewqg.html

Go:   func main()
来源：http://dali.hnqzz.top/Article/details/gtiwhtvizz.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.hysaishi.cn/Article/details/gthzcuyrno.html

C#:   static void Main(string[] args)
来源：http://dali.gzhubu.top/Article/details/gtadyhvbur.html

[M08] 获取系统与运行时信息
来源：http://dali.vqdsnc.cn/Article/details/gturhtdjmx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.nanxinkj.top/Article/details/gtqjzyyiwx.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tianlin.xyz/Article/details/gtazikrptv.html

JS:   process.platform;  process.version
来源：http://dali.xylfe.cn/Article/details/gthmzbqaok.html

TS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gthdrzgmhw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hnqzz.top/Article/details/gttmbasjig.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.chenlongwang.top/Article/details/gtfkrdvoez.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.zhongyouzk.top/Article/details/gtqadxckez.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.bjfxy.top/Article/details/gtpnagsjnc.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsuzajgm.html

N. 数据结构与算法
来源：http://dali.yuanzhike.top/Article/details/gtspfjimes.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtsvevmsio.html

[N01] 二分查找（有序数组）
来源：http://dali.yanxiufei.cn/Article/details/gtayqxzsng.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.birdmap.top/Article/details/gtqiiztkor.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gtnkwrlkgo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yuanzhike.top/Article/details/gtgnfomusb.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gtwearzmll.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtzjzkgeiu.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.iojbl.cn/Article/details/gtuzzgvdaq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxinkj.top/Article/details/gttweuhagn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtfsovjxoh.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gzhubu.top/Article/details/gtdcjxylar.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.birdmap.top/Article/details/gtrkaahvsj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sufxvd.cn/Article/details/gtzlltmnwp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gtlhrcnzzm.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.guowangkeji.top/Article/details/gtiuwbfvpy.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.nwbrower.top/Article/details/gtdrmvmkut.html

Go:   slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gtrjmsmfek.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gtokmfretb.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gttvubvzbi.html

[N03] 快速排序（分治示例）
来源：http://dali.shuidangran.top/Article/details/gtuswrahag.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gogol.net.cn/Article/details/gtdanrdrmc.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yvedp.cn/Article/details/gtjsqxoeet.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.birdmap.top/Article/details/gttsjlthuq.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtwcwlqtex.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jianghu66.top/Article/details/gtcxxmprws.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gzhubu.top/Article/details/gtvbejivum.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.gotoacloud.top/Article/details/gtbughhhdd.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.bjfxy.top/Article/details/gtexwcflvo.html

[N04] 斐波那契数列
来源：http://dali.shangyingyoupin.top/Article/details/gtxicnlccr.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gtfwlldyyl.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ivvv.top/Article/details/gtrkgdedcl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.daxiang520.top/Article/details/gtgotwqbgm.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gogol.net.cn/Article/details/gtulxytzbn.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gtefgovric.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.gzhubu.top/Article/details/gtlggvuqlg.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yuanzhike.top/Article/details/gtkiqbplsz.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.zycfv.cn/Article/details/gtyykzativ.html

[N05] 最大公约数
来源：http://dali.ppjwa.cn/Article/details/gtxcoojgxw.html

Py:   math.gcd(a, b)
来源：http://dali.zhixingplan.top/Article/details/gtfqfpnyin.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sufxvd.cn/Article/details/gtwuascilg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsoxkjfyq.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtrqdqwcjp.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.smart0.xyz/Article/details/gtzsqyapvr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.ppjwa.cn/Article/details/gtbvpnpuan.html

Ruby: a.gcd(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyftojmrp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhongyouzk.top/Article/details/gtgmaiicll.html

[N06] 判断回文字符串
来源：http://dali.gzhubu.top/Article/details/gtmyrhhsoz.html

Py:   s == s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gttycstuiy.html

PHP:  $s === strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtxgddskgz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xinyue.icu/Article/details/gtlrupboym.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ivvv.top/Article/details/gtffoehefk.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.shangyingyoupin.top/Article/details/gtkfhirzfj.html

Go:   // 双指针从两端比较
来源：http://dali.iojbl.cn/Article/details/gtqwotujqo.html

Ruby: s == s.reverse
来源：http://dali.wangdashe.top/Article/details/gtmgfrvuhx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.dianchejie.cn/Article/details/gttytinckl.html

[N07] 两数之和（返回下标）
来源：http://dali.chenlongwang.top/Article/details/gtgbliyyqy.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.dashuyun.cn/Article/details/gtlfoatrob.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.iojbl.cn/Article/details/gtjtjpdzng.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ehwqpu.com/Article/details/gtfdxyvkfk.html

TS:   // 手写 Map<string, number>
来源：http://dali.fengsongda.top/Article/details/gtinptgfve.html

Java: // 手写 HashMap
来源：http://dali.zhijiandao.cn/Article/details/gtqnzgobxa.html

Go:   // 手写 map[int]int
来源：http://dali.dashuyun.cn/Article/details/gtjnkgdccn.html

Ruby: // 手写 Hash
来源：http://dali.sysykeji.top/Article/details/gtxvxnisfk.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.smart0.xyz/Article/details/gtlbbqcncz.html

[N08] 生成全排列
来源：http://dali.cqqwz.cn/Article/details/gtnueszxsp.html

Py:   itertools.permutations(arr)
来源：http://dali.gotoacloud.top/Article/details/gtnloxobey.html

PHP:  // 手写递归交换
来源：http://dali.xinyue.icu/Article/details/gteiugclsg.html

JS:   // 手写回溯递归
来源：http://dali.meibo888.top/Article/details/gtuxzscqcg.html

TS:   // 手写回溯递归
来源：http://dali.0kj1m.cn/Article/details/gtjecpaoxg.html

Java: // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtjvkrqmyj.html

Go:   // 手写回溯递归
来源：http://dali.yanxiufei.cn/Article/details/gtoporfiai.html

Ruby: arr.permutation.to_a
来源：http://dali.hnqzz.top/Article/details/gtjzqcplak.html

C#:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gtgepglobz.html

[N09] 栈与队列
来源：http://dali.shuidangran.top/Article/details/gtcwzhpzqf.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.cdnleiting.top/Article/details/gtlufeoeyj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.quarkkingdee.top/Article/details/gtshiidzpt.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hammf.cn/Article/details/gtewvpeljg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.sufxvd.cn/Article/details/gtzqsugdsz.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ivvv.top/Article/details/gtkhtcpnqc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.guannengcc.top/Article/details/gtwzxaofuu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yangfankeji.com/Article/details/gtvevfrujh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.nwbrower.top/Article/details/gthgbjpmiu.html

[N10] 链表节点定义
来源：http://dali.xuetiantiany.cn/Article/details/gtuugdurmd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.wangshuangyany.cn/Article/details/gtrehstkfm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.chenlongwang.top/Article/details/gttfucyxgu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.meibo888.top/Article/details/gtmerognlt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.guannengcc.top/Article/details/gtznltpixu.html

Java: class Node { int v; Node next; }
来源：http://dali.yvedp.cn/Article/details/gtgiqumgqh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhiwuduotai.top/Article/details/gtetuggkgb.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jiagoushi.top/Article/details/gtzkrhwdji.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jqgfzy.top/Article/details/gtchhxdzux.html

[N11] 二叉树中序遍历
来源：http://dali.aizwys.cn/Article/details/gtnlcfvfpu.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.meibo888.top/Article/details/gtolkakgtm.html

PHP:  // 手写递归函数
来源：http://dali.yangfankeji.com/Article/details/gtldjomqjk.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtfleeknxy.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.fzhhl.top/Article/details/gthpsxhmqp.html

Java: // 手写递归
来源：http://dali.jqgfzy.top/Article/details/gttoxgtlgk.html

Go:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtfdnighek.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ehwqpu.com/Article/details/gtmtpjyxbd.html

C#:   // 手写递归
来源：http://dali.gotoacloud.top/Article/details/gtdckrpsuw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gzhubu.top/Article/details/gtjpqsplla.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shangyingyoupin.top/Article/details/gtctpexscp.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.wangshuangyany.cn/Article/details/gtkliujdti.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gtrsikvepa.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtudgcjlxc.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.tian-w.cn/Article/details/gthwcupguz.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dianchejie.cn/Article/details/gtxwjeitrq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gtrcdpfkyn.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gtbzqxkrmx.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtpaudryho.html

O. 并发与异步
来源：http://dali.c1oappe.top/Article/details/gtidigiail.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtpslpamdf.html

[O01] 启动一个线程
来源：http://dali.yj202588.top/Article/details/gtbjawzzlo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcoqbbuqq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhengqikj.top/Article/details/gthasjsnlp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.yj202588.top/Article/details/gtjpecjccn.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gteiyurspa.html

Java: new Thread(() -> f()).start()
来源：http://dali.guannengcc.top/Article/details/gtzdcgjkym.html

Go:   go f()
来源：http://dali.yj20258.top/Article/details/gtklbzaavz.html

Ruby: Thread.new { f }
来源：http://dali.jianghu66.top/Article/details/gtppsrfwey.html

C#:   Task.Run(() => F());
来源：http://dali.ivvv.top/Article/details/gtwjzjnvwc.html

[O02] 使用线程池
来源：http://dali.vqdsnc.cn/Article/details/gtegcisfjs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zycfv.cn/Article/details/gtmugqcgha.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jianghu66.top/Article/details/gtauehtqma.html

JS:   // worker_threads 线程池
来源：http://dali.ydzc1.top/Article/details/gtjkdshrpy.html

TS:   // worker_threads 线程池
来源：http://dali.aibaodan.cn/Article/details/gtrdcuftvy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.gaohongyu789.top/Article/details/gtqosmdkol.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yj202588.top/Article/details/gtxaumznis.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hysaishi.cn/Article/details/gtjsrhfiyu.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.chenzaomai.com/Article/details/gtdbdtbdhk.html

[O03] 加锁保护共享数据
来源：http://dali.xuanzx.com/Article/details/gtsghmwbzo.html

Py:   with lock: shared += 1
来源：http://dali.ydzc1.top/Article/details/gteiimkgbz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gtqipcigqf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nanxuanxn.top/Article/details/gtolzaaxak.html

TS:   // 同 JS
来源：http://dali.jinqigfzy.top/Article/details/gtfshddqhm.html

Java: synchronized (this) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gtelngmmyx.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hnqzz.top/Article/details/gtcpfectvo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.haohaochexian.top/Article/details/gtroqgektu.html

C#:   lock (gate) { shared++; }
来源：http://dali.kuanghao11.cn/Article/details/gtfmyzypju.html

[O04] 定义异步函数并等待
来源：http://dali.nanxuanxn.top/Article/details/gtipkkajlq.html

Py:   async def f():⏎    await g()
来源：http://dali.xuanzx.com/Article/details/gtqecebgmu.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.xuetiantiany.cn/Article/details/gtrwaoxyct.html

JS:   async function f() { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtpcxtefkn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zycfv.cn/Article/details/gtxwaruzsx.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.zhiwuduotai.top/Article/details/gttzbmoyye.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzledvdt.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenzaomai.com/Article/details/gtbztvwpnl.html

C#:   async Task F() { await G(); }
来源：http://dali.quarkkingdee.top/Article/details/gtmhknvqaj.html

[O05] 并发执行并等待全部完成
来源：http://dali.sufxvd.cn/Article/details/gtspujgzrs.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nanxuanxn.top/Article/details/gtvpszwbag.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xziqi.cn/Article/details/gtykcmusrb.html

JS:   await Promise.all(tasks)
来源：http://dali.yueranfly.top/Article/details/gtavulktry.html

TS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gtcpjokdwt.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.yongpay.top/Article/details/gtyabpcgeb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.jianghu66.top/Article/details/gtyvntezha.html

Ruby: threads.map(&:join)
来源：http://dali.0kj1m.cn/Article/details/gtnfgabdpm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nwbrower.top/Article/details/gthxvspnpw.html

[O06] 使用进程池
来源：http://dali.wangdashe.top/Article/details/gthepbmegv.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ydzc1.top/Article/details/gtnhsmnrlo.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.wangshuangyany.cn/Article/details/gtueuaaerk.html

JS:   // child_process / cluster 模块
来源：http://dali.aibaodan.cn/Article/details/gtzwdgnrcv.html

TS:   // child_process / cluster 模块
来源：http://dali.zhengqikj.top/Article/details/gtlrgpxttv.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gttikjgmtd.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zycfv.cn/Article/details/gtshglockx.html

Ruby: // fork 块
来源：http://dali.mhx1999.top/Article/details/gtyaycegbw.html

C#:   Parallel.For
来源：http://dali.feifeiyinyue.top/Article/details/gtuhojkvld.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gthngraanj.html

P. 常用工具函数
来源：http://dali.yuxming.cn/Article/details/gtofpcuabo.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkreguhxp.html

[P01] 生成 UUID
来源：http://dali.aizwys.cn/Article/details/gtwoqdwuwo.html

Py:   str(uuid.uuid4())
来源：http://dali.gaohongyu789.top/Article/details/gtmyiqgimn.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangdashe.top/Article/details/gttatzgydj.html

JS:   crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtwdhyelzx.html

TS:   crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gtkyxrwpzv.html

Java: UUID.randomUUID().toString()
来源：http://dali.aizwys.cn/Article/details/gtwafsndfw.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cheryme.top/Article/details/gtrxzddvvx.html

Ruby: SecureRandom.uuid
来源：http://dali.xylfe.cn/Article/details/gtijzmxrgg.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gaohongyu789.top/Article/details/gtfrzhypsc.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tian-w.cn/Article/details/gtcmwkwjyf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.quarkkingdee.top/Article/details/gtdffmulln.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.yongpay.top/Article/details/gthuruvmhm.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.havefunace.top/Article/details/gtlaobksww.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkbuusgd.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtyjcycxvz.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.yvedp.cn/Article/details/gtyqyjacts.html


<!-- 参考信息 -->