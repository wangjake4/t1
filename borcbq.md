代发 wailian999

Py:   resp.json()
来源：http://dali.dashuyun.cn/Article/details/gtwksvtovr.html

PHP:  json_decode($body, true);
来源：http://dali.daxiang520.top/Article/details/gtkseebwsi.html

JS:   await resp.json()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzcbcdub.html

TS:   await resp.json()
来源：http://dali.daxiang520.top/Article/details/gtasqekglf.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gtaurvwkzh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aizwys.cn/Article/details/gtctmfvkyz.html

Ruby: JSON.parse(resp.body)
来源：http://dali.chenzaomai.com/Article/details/gtlrtedbya.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daria6918.cn/Article/details/gtwbvbpouq.html

[L07] 处理 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtmukqejlt.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.kuanghao11.cn/Article/details/gtazrpulxp.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.meibo888.top/Article/details/gtbcixbjxh.html

JS:   resp.ok;  resp.status
来源：http://dali.cucudq.cn/Article/details/gtptfadvtq.html

TS:   resp.ok;  resp.status
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfdybcqy.html

Java: resp.statusCode()
来源：http://dali.hnqzz.top/Article/details/gtwmlgndpw.html

Go:   resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gtxvjupahb.html

Ruby: resp.code.to_i
来源：http://dali.sysykeji.top/Article/details/gtkcghsoiq.html

C#:   (int)resp.StatusCode
来源：http://dali.tanke756.top/Article/details/gtasjlisrf.html

[L08] 并发请求多个地址
来源：http://dali.tianlin.xyz/Article/details/gtvklvajfc.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhoulong.xyz/Article/details/gtsxozluwq.html

PHP:  curl_multi_init() 系列
来源：http://dali.zdqjudy.top/Article/details/gtvehkztce.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jyoumei.cn/Article/details/gtndcbkrre.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzebcsotk.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.redwolf501.top/Article/details/gtqcqssoqj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.gzhubu.top/Article/details/gttygavves.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gtggfqdwep.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xziqi.cn/Article/details/gtqbgayohl.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtqsdeyywj.html

M. 命令行 / 进程 / 环境
来源：http://dali.svipenyu.cn/Article/details/gtmfffucyq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtnpaahbmu.html

[M01] 读取命令行参数
来源：http://dali.cashguo.top/Article/details/gtmkhrqlmk.html

Py:   sys.argv[1:]
来源：http://dali.jqgfzy.top/Article/details/gtlvmertkp.html

PHP:  $argv;  $argc;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxkjfony.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtfytbfciu.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtetrlfyod.html

Java: args 数组（main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtmwkygpfl.html

Go:   os.Args[1:]
来源：http://dali.jyoumei.cn/Article/details/gtouutpbcs.html

Ruby: ARGV
来源：http://dali.316326.xyz/Article/details/gthuvjawwh.html

C#:   args 数组（Main 方法参数）
来源：http://dali.iojbl.cn/Article/details/gtnritvakm.html

[M02] 读取环境变量
来源：http://dali.yangfankeji.com/Article/details/gthnrcjcta.html

Py:   os.environ.get("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvknpfrvj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.vqdsnc.cn/Article/details/gtqdlybjmj.html

JS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogtuvxqa.html

TS:   process.env.HOME
来源：http://dali.pengpengdd.cyou/Article/details/gtbaqyctbc.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gtddlfuart.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jqgfzy.top/Article/details/gthrhjmfel.html

Ruby: ENV["HOME"]
来源：http://dali.cqqwz.cn/Article/details/gtqkevbbof.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yj20258.top/Article/details/gtxylvnncx.html

[M03] 执行外部命令
来源：http://dali.cashguo.top/Article/details/gtbjooffif.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cdnleiting.top/Article/details/gtsyzebgzw.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fzhhl.top/Article/details/gtnrugsqkn.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gtytfzcoin.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.smart0.xyz/Article/details/gttafdeivv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pengpengdd.cyou/Article/details/gtcbfrymrt.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.hammf.cn/Article/details/gtkdpdvdhu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zdqjudy.top/Article/details/gtttbasjhj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.jqgfzy.top/Article/details/gtxswricyt.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gtckjjguye.html

Py:   os.getcwd()
来源：http://dali.aizwys.cn/Article/details/gtrdkqvpwc.html

PHP:  getcwd();
来源：http://dali.yanxiufei.cn/Article/details/gtrtdsewca.html

JS:   process.cwd()
来源：http://dali.wangdashe.top/Article/details/gtvjfdvhok.html

TS:   process.cwd()
来源：http://dali.0kj1m.cn/Article/details/gtggqxngpd.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.hnqzz.top/Article/details/gtsduumkwp.html

Go:   os.Getwd()
来源：http://dali.gaohongyu789.top/Article/details/gtkjydjgfr.html

Ruby: Dir.pwd
来源：http://dali.shuidangran.top/Article/details/gtgixkedav.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.316326.xyz/Article/details/gtcanlqjfw.html

[M05] 设置退出码
来源：http://dali.xuetiantiany.cn/Article/details/gtkgxaifjd.html

Py:   sys.exit(1)
来源：http://dali.sufxvd.cn/Article/details/gtjxxjjshw.html

PHP:  exit(1);
来源：http://dali.yueranfly.top/Article/details/gtxjzwukyw.html

JS:   process.exit(1)
来源：http://dali.sxryk.cn/Article/details/gtuutxdwvk.html

TS:   process.exit(1)
来源：http://dali.0kj1m.cn/Article/details/gtluceqdxm.html

Java: System.exit(1)
来源：http://dali.aizwys.cn/Article/details/gttdcqcnzr.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gtslmhzeuk.html

Ruby: exit 1
来源：http://dali.zhengqikj.top/Article/details/gtfpdzbnxp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.zycfv.cn/Article/details/gtolchxhhn.html

[M06] 向标准错误输出
来源：http://dali.hywenlv.cn/Article/details/gtdbfimdsu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gtlbfaduse.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sysykeji.top/Article/details/gtkzxhbpzu.html

JS:   console.error("err")
来源：http://dali.zhengqikj.top/Article/details/gtceaewtsp.html

TS:   console.error("err")
来源：http://dali.xuanzx.com/Article/details/gtglrfiawc.html

Java: System.err.println("err")
来源：http://dali.chenlongwang.top/Article/details/gtacbyoojb.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.svipenyu.cn/Article/details/gtdkygvlbc.html

Ruby: warn "err"
来源：http://dali.zdqjudy.top/Article/details/gtjnifkhdw.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gtougzhphh.html

[M07] 判断是否为主入口
来源：http://dali.snrcjt.cn/Article/details/gtxydqccrd.html

Py:   if __name__ == "__main__":
来源：http://dali.zhongyouzk.top/Article/details/gtrpvmmjpk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yuxming.cn/Article/details/gtaugtsrqs.html

JS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gtzckpynqq.html

TS:   require.main === module
来源：http://dali.aibaodan.cn/Article/details/gthmutdwxa.html

Java: public static void main(String[] args)
来源：http://dali.quarkkingdee.top/Article/details/gtpdvuxvih.html

Go:   func main()
来源：http://dali.yuanzhike.top/Article/details/gticywwhiv.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zycfv.cn/Article/details/gtebrntwly.html

C#:   static void Main(string[] args)
来源：http://dali.ehwqpu.com/Article/details/gtlfjmuzld.html

[M08] 获取系统与运行时信息
来源：http://dali.nwbrower.top/Article/details/gtmsatjeiq.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sxryk.cn/Article/details/gtpkaurxtd.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkxmsgpsx.html

JS:   process.platform;  process.version
来源：http://dali.pycfn.com/Article/details/gtwqezderq.html

TS:   process.platform;  process.version
来源：http://dali.hfpthk.cn/Article/details/gtwbahxolb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.guowangkeji.top/Article/details/gtotkvvndw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.c1oappe.top/Article/details/gtdrgsfnta.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.sufxvd.cn/Article/details/gteildjntd.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.smart0.xyz/Article/details/gtapfksyqu.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtwvsfgeah.html

N. 数据结构与算法
来源：http://dali.jqgfzy.top/Article/details/gtjcylfjbd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtlmvcylpt.html

[N01] 二分查找（有序数组）
来源：http://dali.wangshuangyany.cn/Article/details/gtbhrsubty.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gtpcgolmcc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.daria6918.cn/Article/details/gttzrxqvul.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gtvhsenmzy.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.316326.xyz/Article/details/gtznykvdsl.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtqbqbiujp.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gtiqbokjyh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jlsjyb.cn/Article/details/gtcdcbgcbg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zycfv.cn/Article/details/gteqemxzha.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cucudq.cn/Article/details/gtekgfmfna.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarphzpbj.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenzaomai.com/Article/details/gtrditpcap.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yvedp.cn/Article/details/gtrmlxfwsd.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gtibuwgcjz.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtidhifrkk.html

Go:   slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gtidhotupm.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gthkgmvkbj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.ivvv.top/Article/details/gtbvfymqou.html

[N03] 快速排序（分治示例）
来源：http://dali.sufxvd.cn/Article/details/gtsnmftupi.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.cheryme.top/Article/details/gtgxdgazie.html

PHP:  // 递归实现，或用 usort
来源：http://dali.kuanghao11.cn/Article/details/gthunvdbfh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gtlgoxkdup.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyabpjzfn.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.gotoacloud.top/Article/details/gthexrblsq.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jianghu66.top/Article/details/gtpmqqikyt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.wangdashe.top/Article/details/gtnqifvscb.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuetiantiany.cn/Article/details/gtufuclvbk.html

[N04] 斐波那契数列
来源：http://dali.yueranfly.top/Article/details/gtbylknbkc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtxvlozjrt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sysykeji.top/Article/details/gtnalpczff.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtiwjtuhto.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtytmmrihg.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtigvxirrc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhiwuduotai.top/Article/details/gtdgfmjrqj.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtatzuwhgo.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shuidangran.top/Article/details/gtoutbsrah.html

[N05] 最大公约数
来源：http://dali.zhongyouzk.top/Article/details/gtgynmbequ.html

Py:   math.gcd(a, b)
来源：http://dali.yuanzhike.top/Article/details/gtpiaiexkb.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.tian-w.cn/Article/details/gtrdysqdym.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtngtrhxid.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gtlnemxbok.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hysaishi.cn/Article/details/gtrqxzpmwz.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.nanxuanxn.top/Article/details/gtljmyzzvg.html

Ruby: a.gcd(b)
来源：http://dali.wangdashe.top/Article/details/gtgpfahsny.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.havefunace.top/Article/details/gtklcxebin.html

[N06] 判断回文字符串
来源：http://dali.pycfn.com/Article/details/gtswekankv.html

Py:   s == s[::-1]
来源：http://dali.zhengqikj.top/Article/details/gtuzufqzsv.html

PHP:  $s === strrev($s);
来源：http://dali.nanxinkj.top/Article/details/gtzwgwlfex.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gaohongyu789.top/Article/details/gtngytwwll.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtxlzhpztz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.svipenyu.cn/Article/details/gtwgxofriu.html

Go:   // 双指针从两端比较
来源：http://dali.jiagoushi.top/Article/details/gtpuoymbgt.html

Ruby: s == s.reverse
来源：http://dali.ydzc1.top/Article/details/gtlobrhdzv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzdlnkdgc.html

[N07] 两数之和（返回下标）
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcbtpbea.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tanke756.top/Article/details/gtdxfwppvw.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.jyoumei.cn/Article/details/gtirvhysak.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guannengcc.top/Article/details/gtvqwromij.html

TS:   // 手写 Map<string, number>
来源：http://dali.pengpengdd.cyou/Article/details/gtapslbrvq.html

Java: // 手写 HashMap
来源：http://dali.cdnleiting.top/Article/details/gthbmfcwoa.html

Go:   // 手写 map[int]int
来源：http://dali.jqgfzy.top/Article/details/gtmgrqubka.html

Ruby: // 手写 Hash
来源：http://dali.daxiang520.top/Article/details/gtcxriiumb.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkylyfaao.html

[N08] 生成全排列
来源：http://dali.andypj.xyz/Article/details/gtwecciyfg.html

Py:   itertools.permutations(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehbyjdfh.html

PHP:  // 手写递归交换
来源：http://dali.aibaodan.cn/Article/details/gtpjkechyz.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gtznpwjhbw.html

TS:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gtzhellyjg.html

Java: // 手写回溯递归
来源：http://dali.chenjidiqi.icu/Article/details/gteprwpzqg.html

Go:   // 手写回溯递归
来源：http://dali.fengsongda.top/Article/details/gtmjoflzci.html

Ruby: arr.permutation.to_a
来源：http://dali.sufxvd.cn/Article/details/gtyckshemy.html

C#:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gtnkudycgz.html

[N09] 栈与队列
来源：http://dali.yonumen.top/Article/details/gtufjnhhlk.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwcheggtv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcszstmg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cheryme.top/Article/details/gtbdyspwbn.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.bjfxy.top/Article/details/gtaddcjyvi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gtyqpfjdme.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.chenzaomai.com/Article/details/gtegghvltm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.yuxming.cn/Article/details/gtmwnhtfwa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yj202588.top/Article/details/gtmruoyktj.html

[N10] 链表节点定义
来源：http://dali.nanxuanxn.top/Article/details/gtnafmlksp.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.ehwqpu.com/Article/details/gtohixkaet.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.vqdsnc.cn/Article/details/gtngnulriq.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zhijiandao.cn/Article/details/gtlwzorebb.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.fengsongda.top/Article/details/gtbamnjcrj.html

Java: class Node { int v; Node next; }
来源：http://dali.yj202588.top/Article/details/gtjhjvrmgh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.dashuyun.cn/Article/details/gtphbaekak.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jinqigfzy.top/Article/details/gtfbeodotq.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gtnztauxmb.html

[N11] 二叉树中序遍历
来源：http://dali.ivvv.top/Article/details/gtiviopfmb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fzhhl.top/Article/details/gthxaefexh.html

PHP:  // 手写递归函数
来源：http://dali.aizwys.cn/Article/details/gtgpjsjiig.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yanxiufei.cn/Article/details/gtgosmvkmv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gtctcfdcfj.html

Java: // 手写递归
来源：http://dali.haohaochexian.top/Article/details/gtdrqaoflc.html

Go:   // 手写递归
来源：http://dali.xziqi.cn/Article/details/gtfkupzdkc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zycfv.cn/Article/details/gtvfusfzlv.html

C#:   // 手写递归
来源：http://dali.sysykeji.top/Article/details/gtpceujmxs.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yongpay.top/Article/details/gtruwlwyoy.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.pengpengdd.cyou/Article/details/gtyqebfzdb.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.cdnleiting.top/Article/details/gtupkjpbmo.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.birdmap.top/Article/details/gtsljntbof.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gtsravpnlz.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gttppptcna.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yangfankeji.com/Article/details/gtascwhqln.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.aizwys.cn/Article/details/gthngqhqpj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gtnestnnmi.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthylnnudq.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gtitejrjpi.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrwxwnzj.html

[O01] 启动一个线程
来源：http://dali.ehwqpu.com/Article/details/gtvulkrumt.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.9152youxi.cn/Article/details/gtykdzslss.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.hnqzz.top/Article/details/gtljvkpefq.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.316326.xyz/Article/details/gtnvhlzsby.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtbzysepfg.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhengqikj.top/Article/details/gtfrdeswcm.html

Go:   go f()
来源：http://dali.birdmap.top/Article/details/gtbkswcepx.html

Ruby: Thread.new { f }
来源：http://dali.zhiwuduotai.top/Article/details/gtlhawxjbf.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gtrdlcxkfo.html

[O02] 使用线程池
来源：http://dali.svipenyu.cn/Article/details/gtwafvxhtx.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.9152youxi.cn/Article/details/gtqznzwpjb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.hywenlv.cn/Article/details/gtjeauslxa.html

JS:   // worker_threads 线程池
来源：http://dali.zhengqikj.top/Article/details/gtgdpmcbyq.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtiuaagohz.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.wangdashe.top/Article/details/gtdshtjhjm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.xuetiantiany.cn/Article/details/gtxgvjjmeo.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.0kj1m.cn/Article/details/gtzyqxymcz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xinyue.icu/Article/details/gtayeeumzb.html

[O03] 加锁保护共享数据
来源：http://dali.yueranfly.top/Article/details/gtyzdjcicc.html

Py:   with lock: shared += 1
来源：http://dali.yj202588.top/Article/details/gttsoacwni.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jlsjyb.cn/Article/details/gtfwentryf.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.xylfe.cn/Article/details/gtgtigfgmv.html

TS:   // 同 JS
来源：http://dali.zhiwuduotai.top/Article/details/gtheoyqrji.html

Java: synchronized (this) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxumcxrzg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.zhongyouzk.top/Article/details/gtobdblxlx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gtkkbxtkjz.html

C#:   lock (gate) { shared++; }
来源：http://dali.sysykeji.top/Article/details/gtvwuxvrsr.html

[O04] 定义异步函数并等待
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmrlfozt.html

Py:   async def f():⏎    await g()
来源：http://dali.fzhhl.top/Article/details/gtzzxhljeb.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.havefunace.top/Article/details/gtutwbgtoc.html

JS:   async function f() { await g(); }
来源：http://dali.c1oappe.top/Article/details/gtqhaymyls.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.dianchejie.cn/Article/details/gtwulohqlr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yvedp.cn/Article/details/gtakkpqewb.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cdnleiting.top/Article/details/gthbfvuwzk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.shangyingyoupin.top/Article/details/gtgxnhdhje.html

C#:   async Task F() { await G(); }
来源：http://dali.bjfxy.top/Article/details/gtcugrhkup.html

[O05] 并发执行并等待全部完成
来源：http://dali.sweek.top/Article/details/gtajcikgca.html

Py:   asyncio.gather(*tasks)
来源：http://dali.yj202588.top/Article/details/gtotyigami.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.fzhhl.top/Article/details/gtxdoaruqx.html

JS:   await Promise.all(tasks)
来源：http://dali.hongshengwenyu.top/Article/details/gtgounlshl.html

TS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gtbbodjshj.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.zhijiandao.cn/Article/details/gtvwrptkoz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ivvv.top/Article/details/gtwlfljhmm.html

Ruby: threads.map(&:join)
来源：http://dali.jqgufenzy.top/Article/details/gtwwlaveqm.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jinqigfzy.top/Article/details/gtsefwsjve.html

[O06] 使用进程池
来源：http://dali.nanxuanxn.top/Article/details/gttblrhxuu.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.birdmap.top/Article/details/gtpocvqfmy.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zycfv.cn/Article/details/gtlypwdqcy.html

JS:   // child_process / cluster 模块
来源：http://dali.iojbl.cn/Article/details/gtsehlewtn.html

TS:   // child_process / cluster 模块
来源：http://dali.dianchejie.cn/Article/details/gtoaxpfcbn.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zycfv.cn/Article/details/gtyktwairl.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zhiwuduotai.top/Article/details/gtuskzruwi.html

Ruby: // fork 块
来源：http://dali.gzhubu.top/Article/details/gtaufrvtdz.html

C#:   Parallel.For
来源：http://dali.jianghu66.top/Article/details/gtzmsmcpgp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtnotpkdej.html

P. 常用工具函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstldayds.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtklatcure.html

[P01] 生成 UUID
来源：http://dali.jianghu66.top/Article/details/gtkmcdxjcr.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gtbagtzdfz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.iojbl.cn/Article/details/gtlalluews.html

JS:   crypto.randomUUID()
来源：http://dali.ehwqpu.com/Article/details/gtwlhduajm.html

TS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtcozksbyv.html

Java: UUID.randomUUID().toString()
来源：http://dali.yongpay.top/Article/details/gtxsquxlps.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nwbrower.top/Article/details/gtzhbyqrog.html

Ruby: SecureRandom.uuid
来源：http://dali.ehwqpu.com/Article/details/gtrgdqbiyv.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jiagoushi.top/Article/details/gtvlfewtwf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.haohaochexian.top/Article/details/gtnmlseieb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jinqigufen.top/Article/details/gtoxsvotig.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.fengsongda.top/Article/details/gtjhjrymoz.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.gaohongyu789.top/Article/details/gtvsjvtayo.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.nwbrower.top/Article/details/gtqkxgldrs.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.ivvv.top/Article/details/gtmujfifyo.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.havefunace.top/Article/details/gtxnydewrn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.hongshengwenyu.top/Article/details/gteflhhzdl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.jlsjyb.cn/Article/details/gtrgpnixwc.html

[P03] 生成短随机字符串
来源：http://dali.xylfe.cn/Article/details/gteejlesvs.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.0kj1m.cn/Article/details/gtgvkzcixu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.wangdashe.top/Article/details/gtxiqmtonr.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtydwnahel.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.cashguo.top/Article/details/gtrcwnzoke.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.jqgufenzy.top/Article/details/gthhwffqpe.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.tian-w.cn/Article/details/gtjbieaxqv.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtqkxnsugz.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.sxryk.cn/Article/details/gttynydkub.html

[P04] 求长度
来源：http://dali.zhijiandao.cn/Article/details/gtpbymvkux.html


<!-- 参考信息 -->