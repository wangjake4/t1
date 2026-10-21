代发 wailian999

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjdaqbge.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.gzhubu.top/Article/details/gtluuqgdva.html

Ruby: JSON.parse(resp.body)
来源：http://dali.svipenyu.cn/Article/details/gtkhdfxmnx.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.bjfxy.top/Article/details/gtximutuqs.html

[L07] 处理 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtwlvvyrlv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.wangdashe.top/Article/details/gtunogptvw.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.ivvv.top/Article/details/gtmdwcoyqc.html

JS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gtmhiqtwjb.html

TS:   resp.ok;  resp.status
来源：http://dali.yj202588.top/Article/details/gtojlzdmre.html

Java: resp.statusCode()
来源：http://dali.ybcxt.top/Article/details/gtgzaqvkxz.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gtmoxkkikz.html

Ruby: resp.code.to_i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlobyraoj.html

C#:   (int)resp.StatusCode
来源：http://dali.yonumen.top/Article/details/gtngrtbsay.html

[L08] 并发请求多个地址
来源：http://dali.ivvv.top/Article/details/gtgdvnjpjm.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.sxryk.cn/Article/details/gtocmsaexq.html

PHP:  curl_multi_init() 系列
来源：http://dali.haohaochexian.top/Article/details/gtevgmlvja.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gtzhjrhkeg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pengpengdd.cyou/Article/details/gtklrpdjsd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.vqdsnc.cn/Article/details/gtusxiohwa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ppjwa.cn/Article/details/gtjjtvqjri.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhijiandao.cn/Article/details/gtlwmnhedh.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.316326.xyz/Article/details/gtalvggbru.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtzgtxpqla.html

M. 命令行 / 进程 / 环境
来源：http://dali.zhongyouzk.top/Article/details/gtoyukfxsj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtztjsyejo.html

[M01] 读取命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtqfekqmyb.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gtwtvlpznp.html

PHP:  $argv;  $argc;
来源：http://dali.hnxiangtu.top/Article/details/gtyuzprqhg.html

JS:   process.argv.slice(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtkvnjwirf.html

TS:   process.argv.slice(2)
来源：http://dali.sufxvd.cn/Article/details/gtnbjjryrz.html

Java: args 数组（main 方法参数）
来源：http://dali.pycfn.com/Article/details/gtiqjzaglj.html

Go:   os.Args[1:]
来源：http://dali.zycfv.cn/Article/details/gtwfebvihk.html

Ruby: ARGV
来源：http://dali.yvedp.cn/Article/details/gtvmfdapuw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gtnltehsjn.html

[M02] 读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtkxjcmotr.html

Py:   os.environ.get("HOME")
来源：http://dali.xylfe.cn/Article/details/gtmtilstfa.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.0kj1m.cn/Article/details/gthaaaasuf.html

JS:   process.env.HOME
来源：http://dali.9152youxi.cn/Article/details/gtnjunihgf.html

TS:   process.env.HOME
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvtbxccv.html

Java: System.getenv("HOME")
来源：http://dali.yanxiufei.cn/Article/details/gtbsqnoqli.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.wangshuangyany.cn/Article/details/gtatlivyss.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gtkwrdcxlj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yangfankeji.com/Article/details/gthjlwhhyf.html

[M03] 执行外部命令
来源：http://dali.nanxinkj.top/Article/details/gtruvhjmzh.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.daxiang520.top/Article/details/gtwgaqacbp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daria6918.cn/Article/details/gtjehylhtq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.quarkkingdee.top/Article/details/gtgblrwkxt.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.haohaochexian.top/Article/details/gtgsjebwkn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangdashe.top/Article/details/gtjrcufksh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zdqjudy.top/Article/details/gtxqfsgixa.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhiwuduotai.top/Article/details/gtervsziii.html

C#:   Process.Start("ls", "-l");
来源：http://dali.yj202588.top/Article/details/gtdvrdkgxu.html

[M04] 获取当前工作目录
来源：http://dali.feifeiyinyue.top/Article/details/gtztbfmhxg.html

Py:   os.getcwd()
来源：http://dali.nanxuanxn.top/Article/details/gtflainiik.html

PHP:  getcwd();
来源：http://dali.zhoulong.xyz/Article/details/gtxvmgkwgg.html

JS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gtpldkigzy.html

TS:   process.cwd()
来源：http://dali.ivvv.top/Article/details/gtqjmqtzki.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zycfv.cn/Article/details/gttondllqv.html

Go:   os.Getwd()
来源：http://dali.yuanzhike.top/Article/details/gtrodtbivf.html

Ruby: Dir.pwd
来源：http://dali.jinqigfzy.top/Article/details/gtpenyksdd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.fengsongda.top/Article/details/gtinwtmqdy.html

[M05] 设置退出码
来源：http://dali.pycfn.com/Article/details/gtbxyqquqq.html

Py:   sys.exit(1)
来源：http://dali.dianchejie.cn/Article/details/gtnoqpwqbg.html

PHP:  exit(1);
来源：http://dali.wangdashe.top/Article/details/gtdocurxpa.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gtzruzwkxr.html

TS:   process.exit(1)
来源：http://dali.xylfe.cn/Article/details/gteyjvhhtz.html

Java: System.exit(1)
来源：http://dali.yj202588.top/Article/details/gtupovsczk.html

Go:   os.Exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gtoraepkjv.html

Ruby: exit 1
来源：http://dali.zdqjudy.top/Article/details/gtabihsdnp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tian-w.cn/Article/details/gtwkmvypkx.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gttbbkzqyn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.316326.xyz/Article/details/gtotrchnph.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenjidiqi.icu/Article/details/gttkhttiba.html

JS:   console.error("err")
来源：http://dali.gzhubu.top/Article/details/gtsdgvzssr.html

TS:   console.error("err")
来源：http://dali.iojbl.cn/Article/details/gtcblrobii.html

Java: System.err.println("err")
来源：http://dali.zhiwuduotai.top/Article/details/gtqjjuzyum.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gtypboawfq.html

Ruby: warn "err"
来源：http://dali.pengpengdd.cyou/Article/details/gtmwwxapsz.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shuidangran.top/Article/details/gtmnzbajyx.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gtpxkoopuh.html

Py:   if __name__ == "__main__":
来源：http://dali.guannengcc.top/Article/details/gtcrktgvsu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dianchejie.cn/Article/details/gtaapzfbqf.html

JS:   require.main === module
来源：http://dali.fengsongda.top/Article/details/gtoqdrsipq.html

TS:   require.main === module
来源：http://dali.sysykeji.top/Article/details/gtsiiiewsc.html

Java: public static void main(String[] args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqbpaddy.html

Go:   func main()
来源：http://dali.kuanghao11.cn/Article/details/gtisxgzrzq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.snrcjt.cn/Article/details/gtgwpfilzx.html

C#:   static void Main(string[] args)
来源：http://dali.andypj.xyz/Article/details/gtseqwpuqc.html

[M08] 获取系统与运行时信息
来源：http://dali.ybcxt.top/Article/details/gtnwlerknu.html

Py:   platform.system();  platform.python_version()
来源：http://dali.mhx1999.top/Article/details/gtzuedblgt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfmalfqmo.html

JS:   process.platform;  process.version
来源：http://dali.redwolf501.top/Article/details/gtruwzjavr.html

TS:   process.platform;  process.version
来源：http://dali.mhx1999.top/Article/details/gtxgqgdbpz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.dashuyun.cn/Article/details/gtulbdstve.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.316326.xyz/Article/details/gtejrldhno.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.svipenyu.cn/Article/details/gtvftgnihi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.jinqigufen.top/Article/details/gtylbdknsk.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvpwzgma.html

N. 数据结构与算法
来源：http://dali.cucudq.cn/Article/details/gtfhgjmgiz.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjmmfdve.html

[N01] 二分查找（有序数组）
来源：http://dali.meibo888.top/Article/details/gthrsjwqqq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakuexffr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yanxiufei.cn/Article/details/gthsyumkfe.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gtitfqylyg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.guannengcc.top/Article/details/gtdrwsmvts.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtkxbbebsl.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtqkwcwhmx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gtwuycmvnv.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtrxdluzfz.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.tianlin.xyz/Article/details/gtdnubiaup.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmonzbjzz.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shuidangran.top/Article/details/gtvixrmdff.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtfeeabufo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gteuauhkuc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gtjikdanht.html

Go:   slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gtxpywjmhh.html

Ruby: arr.sort
来源：http://dali.bjfxy.top/Article/details/gtrpvexzns.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.quarkkingdee.top/Article/details/gtqchtygey.html

[N03] 快速排序（分治示例）
来源：http://dali.aizwys.cn/Article/details/gtnjpzwinm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhengqikj.top/Article/details/gtnrzalkfq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.zhoulong.xyz/Article/details/gtnkjeouit.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gtwmyjnmoy.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gtyoajroej.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.andypj.xyz/Article/details/gtvedcnslx.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.jinqigufen.top/Article/details/gtzvlpwtfa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhiwuduotai.top/Article/details/gtsohnrdij.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ybcxt.top/Article/details/gtboyfpdbs.html

[N04] 斐波那契数列
来源：http://dali.dashuyun.cn/Article/details/gtwhggbdjz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tianlin.xyz/Article/details/gtnbhmdqek.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ppjwa.cn/Article/details/gtwefjmllo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.iojbl.cn/Article/details/gtdxiuuwhx.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gtynmnjpph.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zdqjudy.top/Article/details/gtrtirdasl.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hysaishi.cn/Article/details/gtjljpfjyl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nanxuanxn.top/Article/details/gthtdawass.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtxxkjqvgh.html

[N05] 最大公约数
来源：http://dali.ydzc1.top/Article/details/gtgoyxmraf.html

Py:   math.gcd(a, b)
来源：http://dali.ehwqpu.com/Article/details/gtvrxxsphq.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yj20258.top/Article/details/gtaillfcxc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.iojbl.cn/Article/details/gtfgnqgxcm.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.snrcjt.cn/Article/details/gtarayhlwl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cucudq.cn/Article/details/gtbffwawzu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.bjfxy.top/Article/details/gtdccngpab.html

Ruby: a.gcd(b)
来源：http://dali.hfpthk.cn/Article/details/gtiqwayqjw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.xuanzx.com/Article/details/gtyeyocaro.html

[N06] 判断回文字符串
来源：http://dali.aibaodan.cn/Article/details/gtwmvddxki.html

Py:   s == s[::-1]
来源：http://dali.chenjidiqi.icu/Article/details/gttdtiudpe.html

PHP:  $s === strrev($s);
来源：http://dali.cheryme.top/Article/details/gtskjajsmd.html

JS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtfhjnwbji.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtmacifvfq.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.aizwys.cn/Article/details/gttetsypct.html

Go:   // 双指针从两端比较
来源：http://dali.nanxuanxn.top/Article/details/gtlurkdnyv.html

Ruby: s == s.reverse
来源：http://dali.andypj.xyz/Article/details/gtwudvwilv.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.pycfn.com/Article/details/gtvpgpswcn.html

[N07] 两数之和（返回下标）
来源：http://dali.shzxlz.cn/Article/details/gtijfhnypd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.tianlin.xyz/Article/details/gtabvrgxps.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.kuanghao11.cn/Article/details/gtjjcmkwsj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.sxryk.cn/Article/details/gtyleyfhzq.html

TS:   // 手写 Map<string, number>
来源：http://dali.cdnleiting.top/Article/details/gtccxawsup.html

Java: // 手写 HashMap
来源：http://dali.pycfn.com/Article/details/gtwvltqsdc.html

Go:   // 手写 map[int]int
来源：http://dali.xuetiantiany.cn/Article/details/gtqkaeplpm.html

Ruby: // 手写 Hash
来源：http://dali.hnqzz.top/Article/details/gteicriuoa.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.guowangkeji.top/Article/details/gtjngqcjln.html

[N08] 生成全排列
来源：http://dali.yangfankeji.com/Article/details/gtjxoeidhe.html

Py:   itertools.permutations(arr)
来源：http://dali.gotoacloud.top/Article/details/gteoyikuls.html

PHP:  // 手写递归交换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawxuiqlv.html

JS:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gtwiwazkzx.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gtmrfqnzbs.html

Java: // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtsuhamkbd.html

Go:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gteuktsosa.html

Ruby: arr.permutation.to_a
来源：http://dali.cheryme.top/Article/details/gtnxsyaeyd.html

C#:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gtgokioxqf.html

[N09] 栈与队列
来源：http://dali.yj202588.top/Article/details/gtkoeokokh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhijiandao.cn/Article/details/gtwvymvqar.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenzaomai.com/Article/details/gtsqmzvuxb.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.jqgfzy.top/Article/details/gtvqrmqxav.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.9152youxi.cn/Article/details/gtfqbkpxcy.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.bjfxy.top/Article/details/gtptfpbuyv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yueranfly.top/Article/details/gtbgokgjrs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gtjsmjundt.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.9152youxi.cn/Article/details/gtfckybspn.html

[N10] 链表节点定义
来源：http://dali.yj20258888.top/Article/details/gtbopnosnv.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.hywenlv.cn/Article/details/gtezyrwmru.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.dianchejie.cn/Article/details/gtdkgvleha.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xinyue.icu/Article/details/gtztrplbxj.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yj20258.top/Article/details/gtlefzggof.html

Java: class Node { int v; Node next; }
来源：http://dali.yj20258.top/Article/details/gtgsatenxj.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylfshrra.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.zhongyouzk.top/Article/details/gtxvurmvii.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gtrskkrvxd.html

[N11] 二叉树中序遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvcekxxq.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ppjwa.cn/Article/details/gtzacghdzm.html

PHP:  // 手写递归函数
来源：http://dali.yj20258888.top/Article/details/gtqsphxsnr.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gtsptitiwe.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnqzz.top/Article/details/gttqmcpjpk.html

Java: // 手写递归
来源：http://dali.daria6918.cn/Article/details/gtosccofvw.html

Go:   // 手写递归
来源：http://dali.zycfv.cn/Article/details/gtsphjzfjz.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aizwys.cn/Article/details/gtamustqsu.html

C#:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gttfhjgouk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.iojbl.cn/Article/details/gtibzvvwkh.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.vqdsnc.cn/Article/details/gtaijnncro.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gtkedyxzps.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.chenlongwang.top/Article/details/gtblbsodlg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhengqikj.top/Article/details/gtahvuutqu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.snrcjt.cn/Article/details/gtedxghjhp.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.feifeiyinyue.top/Article/details/gtawcmfstq.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqjvwbbxy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shangyingyoupin.top/Article/details/gtapvkunwb.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtnzfvhmfe.html

O. 并发与异步
来源：http://dali.daria6918.cn/Article/details/gtdachbvpb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtmmkthusv.html

[O01] 启动一个线程
来源：http://dali.havefunace.top/Article/details/gtrienmkmg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.xylfe.cn/Article/details/gtuhgdbxuq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhiwuduotai.top/Article/details/gtmssscpqb.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zycfv.cn/Article/details/gtcqotcnzi.html

TS:   // 同 JS
来源：http://dali.smart0.xyz/Article/details/gtyiqvztmr.html

Java: new Thread(() -> f()).start()
来源：http://dali.xylfe.cn/Article/details/gtksgobvbw.html

Go:   go f()
来源：http://dali.iojbl.cn/Article/details/gtvbmdkyfj.html

Ruby: Thread.new { f }
来源：http://dali.yuanzhike.top/Article/details/gtoaxhlgis.html

C#:   Task.Run(() => F());
来源：http://dali.daria6918.cn/Article/details/gtgxaipevw.html

[O02] 使用线程池
来源：http://dali.chenjidiqi.icu/Article/details/gtfjnmtwor.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gtyrnyylvx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zycfv.cn/Article/details/gtcqhlzsdc.html

JS:   // worker_threads 线程池
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpamkcpd.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gtmfpwjpyy.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.yueranfly.top/Article/details/gtcyynwhdc.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.gotoacloud.top/Article/details/gtgrfmfzfd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuzifivj.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xuanzx.com/Article/details/gtfqxnposr.html

[O03] 加锁保护共享数据
来源：http://dali.ivvv.top/Article/details/gtfndrffwv.html

Py:   with lock: shared += 1
来源：http://dali.daria6918.cn/Article/details/gtsppagwzp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yanxiufei.cn/Article/details/gthztxjhvn.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhiwuduotai.top/Article/details/gtwlhptntk.html

TS:   // 同 JS
来源：http://dali.sweek.top/Article/details/gtonbxqunj.html

Java: synchronized (this) { shared++; }
来源：http://dali.vqdsnc.cn/Article/details/gtfurldygi.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.nwbrower.top/Article/details/gthdbykgxe.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yongpay.top/Article/details/gtpvxlrdqd.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gtebtcjahc.html

[O04] 定义异步函数并等待
来源：http://dali.yj202588.top/Article/details/gthuydsmwr.html

Py:   async def f():⏎    await g()
来源：http://dali.aibaodan.cn/Article/details/gtjfdabpws.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.zhijiandao.cn/Article/details/gtlogevybv.html

JS:   async function f() { await g(); }
来源：http://dali.ehwqpu.com/Article/details/gtywyoddrv.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yj202588.top/Article/details/gtlriczrhc.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.sweek.top/Article/details/gtcsbgfztt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.jinqigufen.top/Article/details/gttodctcvp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yanxiufei.cn/Article/details/gtjsaijomh.html

C#:   async Task F() { await G(); }
来源：http://dali.zdqjudy.top/Article/details/gtdtbdtlbg.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhongyouzk.top/Article/details/gtdvxsjptr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.kuanghao11.cn/Article/details/gtczimqcan.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.haohaochexian.top/Article/details/gtjbqgrxor.html

JS:   await Promise.all(tasks)
来源：http://dali.cucudq.cn/Article/details/gtzkxkoqqs.html

TS:   await Promise.all(tasks)
来源：http://dali.chenlongwang.top/Article/details/gtvvkouyvp.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fzhhl.top/Article/details/gtfvseculz.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.wangshuangyany.cn/Article/details/gtrobbeeqo.html

Ruby: threads.map(&:join)
来源：http://dali.gogol.net.cn/Article/details/gtgaxthzkp.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.c1oappe.top/Article/details/gtnaffayln.html

[O06] 使用进程池
来源：http://dali.xylfe.cn/Article/details/gtdbvbifch.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zdqjudy.top/Article/details/gtidrskfup.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jinqigfzy.top/Article/details/gtfmjtzebw.html

JS:   // child_process / cluster 模块
来源：http://dali.zhoulong.xyz/Article/details/gtwwclaqpy.html

TS:   // child_process / cluster 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxsobcytm.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.ywan-chungtsiang.top/Article/details/gtofhxxheo.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yongpay.top/Article/details/gtosmadrjo.html

Ruby: // fork 块
来源：http://dali.sxryk.cn/Article/details/gtsknzpozk.html

C#:   Parallel.For
来源：http://dali.haohaochexian.top/Article/details/gteoxnnnrw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtkgrisnjv.html

P. 常用工具函数
来源：http://dali.hywenlv.cn/Article/details/gtalqpuysu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtpicrlhzt.html

[P01] 生成 UUID
来源：http://dali.hfpthk.cn/Article/details/gtwlvsrmvn.html

Py:   str(uuid.uuid4())
来源：http://dali.tian-w.cn/Article/details/gthzoownpf.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.daria6918.cn/Article/details/gtnpzosovt.html

JS:   crypto.randomUUID()
来源：http://dali.smart0.xyz/Article/details/gtvzishjna.html

TS:   crypto.randomUUID()
来源：http://dali.yj20258888.top/Article/details/gtjyupislc.html

Java: UUID.randomUUID().toString()
来源：http://dali.zhoulong.xyz/Article/details/gtfuqnjvuy.html

Go:   // 用 github.com/google/uuid
来源：http://dali.dashuyun.cn/Article/details/gtwbqhmwtu.html

Ruby: SecureRandom.uuid
来源：http://dali.dashuyun.cn/Article/details/gtsidvovch.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.feifeiyinyue.top/Article/details/gtikkczmnb.html

[P02] MD5 / SHA256 摘要
来源：http://dali.tian-w.cn/Article/details/gtcxvbwimf.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yuxming.cn/Article/details/gtkmjyofzp.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjaexrzsa.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hongshengwenyu.top/Article/details/gtgblhnzsn.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yonumen.top/Article/details/gtnpkzpugz.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.gogol.net.cn/Article/details/gtsfhoersv.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.iojbl.cn/Article/details/gtylwngrjm.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yuanzhike.top/Article/details/gtztvsjzma.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.vqdsnc.cn/Article/details/gtyamwobip.html

[P03] 生成短随机字符串
来源：http://dali.sufxvd.cn/Article/details/gtoorajqow.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.meibo888.top/Article/details/gtpavpftpv.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.feifeiyinyue.top/Article/details/gtbkinzxwg.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.ydzc1.top/Article/details/gtlgofklud.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.yongpay.top/Article/details/gtxxcpzxbz.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtskwaelog.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.chenjidiqi.icu/Article/details/gthvcmqwbe.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.feifeiyinyue.top/Article/details/gtndcrzrvi.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.yonumen.top/Article/details/gtbldfsueu.html

[P04] 求长度
来源：http://dali.cqqwz.cn/Article/details/gtrqjdppnw.html

Py:   len(x)            # 字符串、列表、字典通用
来源：http://dali.nanxuanxn.top/Article/details/gtanplzzbg.html

PHP:  count($arr);  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgsjrobhq.html

JS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.tanke756.top/Article/details/gtvwxfnpty.html

TS:   Array.isArray(x) ? x.length : Object.keys(x).length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuenfmqix.html


<!-- 参考信息 -->