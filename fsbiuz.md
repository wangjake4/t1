代发 wailian999

Py:   resp.json()
来源：http://dali.pycfn.com/Article/details/gtwsnccztf.html

PHP:  json_decode($body, true);
来源：http://dali.316326.xyz/Article/details/gtoevhfxkz.html

JS:   await resp.json()
来源：http://dali.shangyingyoupin.top/Article/details/gtlsuubrbk.html

TS:   await resp.json()
来源：http://dali.cucudq.cn/Article/details/gtrtdalvxv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xuetiantiany.cn/Article/details/gthxvpylsp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tian-w.cn/Article/details/gtrkgfoizh.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gtnznhjerk.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.dashuyun.cn/Article/details/gtsqjnkptz.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinqigufen.top/Article/details/gtjewbcwah.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gzhubu.top/Article/details/gtcchzsjtw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.sufxvd.cn/Article/details/gtkxxmkzbw.html

JS:   resp.ok;  resp.status
来源：http://dali.chenjidiqi.icu/Article/details/gteentvoca.html

TS:   resp.ok;  resp.status
来源：http://dali.meibo888.top/Article/details/gtkwmqskdi.html

Java: resp.statusCode()
来源：http://dali.yj202588.top/Article/details/gtxfoezuok.html

Go:   resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gttzfnaivl.html

Ruby: resp.code.to_i
来源：http://dali.yj20258.top/Article/details/gtdgpsnymk.html

C#:   (int)resp.StatusCode
来源：http://dali.gzhubu.top/Article/details/gtmtcrrbrn.html

[L08] 并发请求多个地址
来源：http://dali.birdmap.top/Article/details/gtofmnldqg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gtexfkunba.html

PHP:  curl_multi_init() 系列
来源：http://dali.zhiwuduotai.top/Article/details/gtqwdqhixy.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shzxlz.cn/Article/details/gtlrtlbvwa.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hammf.cn/Article/details/gtpitwycoi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.xziqi.cn/Article/details/gtzhgripri.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.bjfxy.top/Article/details/gtgyxpjidz.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.nanxinkj.top/Article/details/gtwjgvyvnk.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gtauzehzst.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtynjyxdiv.html

M. 命令行 / 进程 / 环境
来源：http://dali.sysykeji.top/Article/details/gtgvwbvgdx.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gteabwakru.html

[M01] 读取命令行参数
来源：http://dali.wangdashe.top/Article/details/gthlivaucr.html

Py:   sys.argv[1:]
来源：http://dali.hnxiangtu.top/Article/details/gtrgesdsuh.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gtmlufzqjl.html

JS:   process.argv.slice(2)
来源：http://dali.hnxiangtu.top/Article/details/gtsvrditfj.html

TS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gtfomawpeg.html

Java: args 数组（main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtkkccxvcc.html

Go:   os.Args[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvqyizxu.html

Ruby: ARGV
来源：http://dali.gogol.net.cn/Article/details/gtlbzruacm.html

C#:   args 数组（Main 方法参数）
来源：http://dali.vqdsnc.cn/Article/details/gtxlfnlpak.html

[M02] 读取环境变量
来源：http://dali.zdqjudy.top/Article/details/gtwpwjedco.html

Py:   os.environ.get("HOME")
来源：http://dali.chenlongwang.top/Article/details/gtunschtar.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.redwolf501.top/Article/details/gtcadszfwb.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gtnubqmeuy.html

TS:   process.env.HOME
来源：http://dali.chenzaomai.com/Article/details/gtklcbegnd.html

Java: System.getenv("HOME")
来源：http://dali.cdnleiting.top/Article/details/gtmeomyfsu.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.9152youxi.cn/Article/details/gtaeetfmfj.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gtbanhgcrk.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yueranfly.top/Article/details/gtymjirrgd.html

[M03] 执行外部命令
来源：http://dali.yangfankeji.com/Article/details/gtsdvtzijt.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.ydzc1.top/Article/details/gtjhchulat.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhengqikj.top/Article/details/gtnaoqrnvp.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.0kj1m.cn/Article/details/gtknrasrss.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtjsiomvaw.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthffwiqsz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxinkj.top/Article/details/gtaxncofvo.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuanzhike.top/Article/details/gtxupevzkq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ybcxt.top/Article/details/gtemyyazpo.html

[M04] 获取当前工作目录
来源：http://dali.iojbl.cn/Article/details/gtlyumbrsw.html

Py:   os.getcwd()
来源：http://dali.xinyue.icu/Article/details/gtzyiyiqia.html

PHP:  getcwd();
来源：http://dali.guowangkeji.top/Article/details/gtmchpznfk.html

JS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gtpgeuetie.html

TS:   process.cwd()
来源：http://dali.pengpengdd.cyou/Article/details/gtpbrdqgoy.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.cashguo.top/Article/details/gtvfnielhk.html

Go:   os.Getwd()
来源：http://dali.kuanghao11.cn/Article/details/gtfjarcsgy.html

Ruby: Dir.pwd
来源：http://dali.zycfv.cn/Article/details/gtcjmvctph.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.redwolf501.top/Article/details/gtdokufetm.html

[M05] 设置退出码
来源：http://dali.cdnleiting.top/Article/details/gtyxerldjl.html

Py:   sys.exit(1)
来源：http://dali.smart0.xyz/Article/details/gtikmaorqy.html

PHP:  exit(1);
来源：http://dali.havefunace.top/Article/details/gtvhtwmtil.html

JS:   process.exit(1)
来源：http://dali.xuanzx.com/Article/details/gtyvnqnuwp.html

TS:   process.exit(1)
来源：http://dali.c1oappe.top/Article/details/gtuetxyryc.html

Java: System.exit(1)
来源：http://dali.guannengcc.top/Article/details/gtpwxufjdz.html

Go:   os.Exit(1)
来源：http://dali.zycfv.cn/Article/details/gtamuvwthn.html

Ruby: exit 1
来源：http://dali.hammf.cn/Article/details/gtrfxzlqoq.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jlsjyb.cn/Article/details/gtudzsczfa.html

[M06] 向标准错误输出
来源：http://dali.nwbrower.top/Article/details/gtitivxxhv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gtxpelwwya.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jianghu66.top/Article/details/gtpckbtrwa.html

JS:   console.error("err")
来源：http://dali.jyoumei.cn/Article/details/gtbyndhhzk.html

TS:   console.error("err")
来源：http://dali.vqdsnc.cn/Article/details/gtilukdirm.html

Java: System.err.println("err")
来源：http://dali.svipenyu.cn/Article/details/gtgdtrmotr.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.9152youxi.cn/Article/details/gtysyfcxmv.html

Ruby: warn "err"
来源：http://dali.mhx1999.top/Article/details/gtxqqamhaz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guowangkeji.top/Article/details/gtkwoleerc.html

[M07] 判断是否为主入口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwnnvrmq.html

Py:   if __name__ == "__main__":
来源：http://dali.zhoulong.xyz/Article/details/gtxiyphtuk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.havefunace.top/Article/details/gtdlgepfvz.html

JS:   require.main === module
来源：http://dali.hysaishi.cn/Article/details/gtwtioebgo.html

TS:   require.main === module
来源：http://dali.aizwys.cn/Article/details/gtfbyuektn.html

Java: public static void main(String[] args)
来源：http://dali.jlsjyb.cn/Article/details/gtipamlmeh.html

Go:   func main()
来源：http://dali.yueranfly.top/Article/details/gtmclwadci.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.feifeiyinyue.top/Article/details/gtmurxyqko.html

C#:   static void Main(string[] args)
来源：http://dali.smart0.xyz/Article/details/gttwpmwxwi.html

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gtkkhtidnu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoqgjpogz.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.c1oappe.top/Article/details/gtpetltuwh.html

JS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gtiwamvfjy.html

TS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gttwlpmtoz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gtmeoshhoq.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zhengqikj.top/Article/details/gtmobvfpto.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.ivvv.top/Article/details/gttogqmomo.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.aizwys.cn/Article/details/gtubenjftx.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtdhvldbuv.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gtffvnoaeu.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtcqkgfcni.html

[N01] 二分查找（有序数组）
来源：http://dali.ppjwa.cn/Article/details/gtmddkdhdn.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.birdmap.top/Article/details/gtmenhrbrp.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cashguo.top/Article/details/gtbcjdlafo.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guowangkeji.top/Article/details/gtlavtqunv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gtikrkcmbv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtttmyynpz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yj20258.top/Article/details/gtxjuvxfmy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.iojbl.cn/Article/details/gtwlkfxdmk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtctopeher.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hywenlv.cn/Article/details/gtkjvtqebz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtsoleruef.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenzaomai.com/Article/details/gthxwztcxx.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yj202588.top/Article/details/gtntqinitd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuddzoru.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.feifeiyinyue.top/Article/details/gtytpklywa.html

Go:   slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtbxdnpzmg.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtuffahioz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtqlfgvqqi.html

[N03] 快速排序（分治示例）
来源：http://dali.cqqwz.cn/Article/details/gtnaokvlho.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhoulong.xyz/Article/details/gtbhozcgql.html

PHP:  // 递归实现，或用 usort
来源：http://dali.daria6918.cn/Article/details/gtphqhawgl.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xylfe.cn/Article/details/gtpaidtbjo.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.fzhhl.top/Article/details/gtmccrljuv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtualvaskl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.mhx1999.top/Article/details/gtinncjwma.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dashuyun.cn/Article/details/gtrxzcorik.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gthysuhzwh.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gtsdprrkjp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.nanxinkj.top/Article/details/gtxyanfhdb.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gtmbfhohwd.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nwbrower.top/Article/details/gttemqcvbh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gttqqdpaqq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.9152youxi.cn/Article/details/gtodugjhkt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hywenlv.cn/Article/details/gtrejufkeo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gtpezfkiop.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gtynywgskm.html

[N05] 最大公约数
来源：http://dali.mhx1999.top/Article/details/gtduppgwcj.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gtpreicpic.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhijiandao.cn/Article/details/gtjsebcbjf.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gtokdbbonn.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.vqdsnc.cn/Article/details/gtuggpbclf.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.haohaochexian.top/Article/details/gtkjghbnjn.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdulpnglj.html

Ruby: a.gcd(b)
来源：http://dali.yuanzhike.top/Article/details/gtozeuuwpz.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuanzx.com/Article/details/gtxwzgbwin.html

[N06] 判断回文字符串
来源：http://dali.xinyue.icu/Article/details/gtaifdnifx.html

Py:   s == s[::-1]
来源：http://dali.hnqzz.top/Article/details/gthjsvvunh.html

PHP:  $s === strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtbcuvxnnv.html

JS:   s === [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gtfuypmbit.html

TS:   s === [...s].reverse().join("")
来源：http://dali.daria6918.cn/Article/details/gtxszpxnwg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cashguo.top/Article/details/gtxlwwgryj.html

Go:   // 双指针从两端比较
来源：http://dali.ppjwa.cn/Article/details/gtzxxxdlyu.html

Ruby: s == s.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtqejfdvdu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xinyue.icu/Article/details/gtgwiywkxm.html

[N07] 两数之和（返回下标）
来源：http://dali.yj202588.top/Article/details/gtnbvhjzko.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guowangkeji.top/Article/details/gtmikwbooq.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.0kj1m.cn/Article/details/gtlbjirslf.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtveymqkmh.html

TS:   // 手写 Map<string, number>
来源：http://dali.jqgufenzy.top/Article/details/gtblgrgcyp.html

Java: // 手写 HashMap
来源：http://dali.shuidangran.top/Article/details/gtkuqexlys.html

Go:   // 手写 map[int]int
来源：http://dali.yonumen.top/Article/details/gtyizphqty.html

Ruby: // 手写 Hash
来源：http://dali.jiagoushi.top/Article/details/gtebhrkqfn.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.chenlongwang.top/Article/details/gtbidufqwn.html

[N08] 生成全排列
来源：http://dali.fengsongda.top/Article/details/gtamxuosgn.html

Py:   itertools.permutations(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjiqagpbr.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsannsvdy.html

JS:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtslsuexmf.html

TS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtrlxtymwe.html

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtzexhnrum.html

Go:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gtosbkkizc.html

Ruby: arr.permutation.to_a
来源：http://dali.pengpengdd.cyou/Article/details/gthincacxw.html

C#:   // 手写回溯递归
来源：http://dali.wangdashe.top/Article/details/gtdufgkxgo.html

[N09] 栈与队列
来源：http://dali.cheryme.top/Article/details/gtdugllsai.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.sxryk.cn/Article/details/gtdqfbuqnp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gtrdqjexri.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtkprfaxmv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.dianchejie.cn/Article/details/gtsfjyzvin.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.c1oappe.top/Article/details/gtfqljsarj.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.dashuyun.cn/Article/details/gtplhdcxpz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gtenlvlyrb.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.cqqwz.cn/Article/details/gtcwyupntu.html

[N10] 链表节点定义
来源：http://dali.redwolf501.top/Article/details/gtbmyrchxg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.316326.xyz/Article/details/gttscskgfs.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhengqikj.top/Article/details/gtnzxaogql.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.9152youxi.cn/Article/details/gttcczhzdv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.wangshuangyany.cn/Article/details/gtgkehvnzj.html

Java: class Node { int v; Node next; }
来源：http://dali.yuxming.cn/Article/details/gttczazwdk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sufxvd.cn/Article/details/gtoyhnnhro.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenlongwang.top/Article/details/gtwemqohol.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnxwyllnj.html

[N11] 二叉树中序遍历
来源：http://dali.gzhubu.top/Article/details/gtfkxfooob.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zdqjudy.top/Article/details/gtifeigkkr.html

PHP:  // 手写递归函数
来源：http://dali.9152youxi.cn/Article/details/gtczwveopo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gttfdvgcei.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yonumen.top/Article/details/gtbyuxmift.html

Java: // 手写递归
来源：http://dali.jyoumei.cn/Article/details/gtwbopofnh.html

Go:   // 手写递归
来源：http://dali.cqqwz.cn/Article/details/gtjbzzbcip.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqjfiaun.html

C#:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gtjgiwmcss.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.nanxuanxn.top/Article/details/gtkueslwgr.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shzxlz.cn/Article/details/gtifetbghv.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gtchtogbvi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.0kj1m.cn/Article/details/gthjfqgptr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gtqamogxrh.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gtkukovkpv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtleyqenhe.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gtbsmeldsv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gtkqptzphg.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtwkdbzrpt.html

O. 并发与异步
来源：http://dali.mhx1999.top/Article/details/gtoutclitb.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtaixthfmr.html

[O01] 启动一个线程
来源：http://dali.xylfe.cn/Article/details/gtctcjrgrt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fzhhl.top/Article/details/gtbtekbxfw.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.ivvv.top/Article/details/gtnkqewdny.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ydzc1.top/Article/details/gtxwojpico.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gtedqayrvx.html

Java: new Thread(() -> f()).start()
来源：http://dali.zdqjudy.top/Article/details/gthbqrkzcw.html

Go:   go f()
来源：http://dali.pycfn.com/Article/details/gtxvpljgoj.html

Ruby: Thread.new { f }
来源：http://dali.zhongyouzk.top/Article/details/gtlzhnzhnh.html

C#:   Task.Run(() => F());
来源：http://dali.ivvv.top/Article/details/gtrzyzekas.html

[O02] 使用线程池
来源：http://dali.shanyushiyangtech.top/Article/details/gtcztaxojv.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.sufxvd.cn/Article/details/gtqocuvmsq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jinqigfzy.top/Article/details/gtqoywdmun.html

JS:   // worker_threads 线程池
来源：http://dali.iojbl.cn/Article/details/gtpdlbwkbf.html

TS:   // worker_threads 线程池
来源：http://dali.c1oappe.top/Article/details/gtbaiwzdgd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zycfv.cn/Article/details/gtvwlodvgq.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.snrcjt.cn/Article/details/gtvfggrxej.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.mhx1999.top/Article/details/gtlaukgdgn.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gotoacloud.top/Article/details/gtjwxvwoav.html

[O03] 加锁保护共享数据
来源：http://dali.316326.xyz/Article/details/gtvfpxcjzh.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gthmysbjry.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.havefunace.top/Article/details/gtfwtngyjv.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.shuidangran.top/Article/details/gtybmgmoub.html

TS:   // 同 JS
来源：http://dali.snrcjt.cn/Article/details/gtvboulbsj.html

Java: synchronized (this) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtmvuafgor.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nanxuanxn.top/Article/details/gtwpbfbbml.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.andypj.xyz/Article/details/gtgmdswfhx.html

C#:   lock (gate) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtsgkbwenf.html

[O04] 定义异步函数并等待
来源：http://dali.yj20258.top/Article/details/gtlfiswfiv.html

Py:   async def f():⏎    await g()
来源：http://dali.ybcxt.top/Article/details/gtyellcgpj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.daria6918.cn/Article/details/gtsgtgszdn.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtcajjxmkn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gtpqytwjqc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.birdmap.top/Article/details/gtyxjzpcuk.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jqgfzy.top/Article/details/gtxzhfjvnh.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jlsjyb.cn/Article/details/gtdlmekikm.html

C#:   async Task F() { await G(); }
来源：http://dali.aizwys.cn/Article/details/gtssqfvpko.html

[O05] 并发执行并等待全部完成
来源：http://dali.aizwys.cn/Article/details/gtlhrlvdqp.html

Py:   asyncio.gather(*tasks)
来源：http://dali.svipenyu.cn/Article/details/gtzgdmxgra.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ivvv.top/Article/details/gtaajvoijb.html

JS:   await Promise.all(tasks)
来源：http://dali.ivvv.top/Article/details/gtnaqjjhya.html

TS:   await Promise.all(tasks)
来源：http://dali.andypj.xyz/Article/details/gtpxdlknuf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sufxvd.cn/Article/details/gtozdsvtxb.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yueranfly.top/Article/details/gtgqmlhwgl.html

Ruby: threads.map(&:join)
来源：http://dali.hnxiangtu.top/Article/details/gtgwqgquix.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.nanxinkj.top/Article/details/gtqrppzjko.html

[O06] 使用进程池
来源：http://dali.cqqwz.cn/Article/details/gtrbdvdzne.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.guannengcc.top/Article/details/gtjdbmfyil.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdaulgcm.html

JS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpexudgyf.html

TS:   // child_process / cluster 模块
来源：http://dali.quarkkingdee.top/Article/details/gtbyyorurn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.xuetiantiany.cn/Article/details/gtragxfajx.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.chenzaomai.com/Article/details/gtoxcuphlh.html

Ruby: // fork 块
来源：http://dali.vqdsnc.cn/Article/details/gttrgfkded.html

C#:   Parallel.For
来源：http://dali.ybcxt.top/Article/details/gtscnfwipv.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtefivdczj.html

P. 常用工具函数
来源：http://dali.mhx1999.top/Article/details/gtrdeqfcty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtdlmnkpym.html

[P01] 生成 UUID
来源：http://dali.ydzc1.top/Article/details/gtrtbkzqok.html

Py:   str(uuid.uuid4())
来源：http://dali.xuanzx.com/Article/details/gtqvrpngre.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nwbrower.top/Article/details/gtfnowamzw.html

JS:   crypto.randomUUID()
来源：http://dali.chenjidiqi.icu/Article/details/gtxtsxqmqj.html

TS:   crypto.randomUUID()
来源：http://dali.gogol.net.cn/Article/details/gttwufgdzf.html

Java: UUID.randomUUID().toString()
来源：http://dali.hywenlv.cn/Article/details/gtxmbewfkn.html

Go:   // 用 github.com/google/uuid
来源：http://dali.smart0.xyz/Article/details/gtgvxcgduv.html

Ruby: SecureRandom.uuid
来源：http://dali.nanxuanxn.top/Article/details/gtonwrrvxr.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yangfankeji.com/Article/details/gtjveocsji.html

[P02] MD5 / SHA256 摘要
来源：http://dali.jinqigufen.top/Article/details/gtemuzmxlt.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.redwolf501.top/Article/details/gtvpngsxcq.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.tanke756.top/Article/details/gtwzazrfxr.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gaohongyu789.top/Article/details/gtceedgpgl.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.birdmap.top/Article/details/gteobqpqob.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.sweek.top/Article/details/gtymvvhpux.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gtwglpmtez.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.tianlin.xyz/Article/details/gtjvqpmqxg.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.hongshengwenyu.top/Article/details/gtqeettrjp.html

[P03] 生成短随机字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtltvyqpmm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.0kj1m.cn/Article/details/gthmogqebz.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.tianlin.xyz/Article/details/gtwrmddkdt.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zycfv.cn/Article/details/gtgpzyyvhn.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.andypj.xyz/Article/details/gtizmbhpiw.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.chenjidiqi.icu/Article/details/gtffuecprj.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.hnxiangtu.top/Article/details/gtqmrqeiwz.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.gotoacloud.top/Article/details/gtgdjfuvft.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jiagoushi.top/Article/details/gtamzxedbd.html

[P04] 求长度
来源：http://dali.yj20258.top/Article/details/gtgppgmrbo.html


<!-- 参考信息 -->