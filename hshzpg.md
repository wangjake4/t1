代发 wailian999

Py:   resp.json()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxmyemtu.html

PHP:  json_decode($body, true);
来源：http://dali.dashuyun.cn/Article/details/gt2apfdobss.html

JS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gt2mgumrkch.html

TS:   await resp.json()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jjjgujhm.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.c1oappe.top/Article/details/gt2qxbnodex.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.tianlin.xyz/Article/details/gt2lrscavms.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhongyouzk.top/Article/details/gt2lxhfirvz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.fengsongda.top/Article/details/gt2qhyfwgxd.html

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gt2crhrrtvr.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dianchejie.cn/Article/details/gt2tiwwqipt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yvedp.cn/Article/details/gt2gcbqdvmn.html

JS:   resp.ok;  resp.status
来源：http://dali.hammf.cn/Article/details/gt2nsiihpzi.html

TS:   resp.ok;  resp.status
来源：http://dali.ehwqpu.com/Article/details/gt2wfwwbise.html

Java: resp.statusCode()
来源：http://dali.pengpengdd.cyou/Article/details/gt2rkythkub.html

Go:   resp.StatusCode
来源：http://dali.yangfankeji.com/Article/details/gt2iedojvpq.html

Ruby: resp.code.to_i
来源：http://dali.andypj.xyz/Article/details/gt2acmsjaop.html

C#:   (int)resp.StatusCode
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xousuznh.html

[L08] 并发请求多个地址
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hqpxjvaz.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmyiwczm.html

PHP:  curl_multi_init() 系列
来源：http://dali.ybcxt.top/Article/details/gt2rlnlvytj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hysaishi.cn/Article/details/gt2detnbeaq.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gt2qbgqugkj.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenzaomai.com/Article/details/gt2bxnqykak.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenjidiqi.icu/Article/details/gt2lypwoyus.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.316326.xyz/Article/details/gt2qcckydgb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.hnqzz.top/Article/details/gt2krconamn.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2qbsvsxbp.html

M. 命令行 / 进程 / 环境
来源：http://dali.aibaodan.cn/Article/details/gt2blfynkkv.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2xzfodvdj.html

[M01] 读取命令行参数
来源：http://dali.andypj.xyz/Article/details/gt2fpeyyazv.html

Py:   sys.argv[1:]
来源：http://dali.hongshengwenyu.top/Article/details/gt2kkkufzdd.html

PHP:  $argv;  $argc;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbbnpdte.html

JS:   process.argv.slice(2)
来源：http://dali.zhoulong.xyz/Article/details/gt2qaazvuzs.html

TS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gt2qclxriok.html

Java: args 数组（main 方法参数）
来源：http://dali.pycfn.com/Article/details/gt2rupziqzm.html

Go:   os.Args[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2epwawhdl.html

Ruby: ARGV
来源：http://dali.feifeiyinyue.top/Article/details/gt2ohuarlbp.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hysaishi.cn/Article/details/gt2wpyhnirl.html

[M02] 读取环境变量
来源：http://dali.hammf.cn/Article/details/gt2eeyyhmkb.html

Py:   os.environ.get("HOME")
来源：http://dali.aizwys.cn/Article/details/gt2hnvihobg.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.jianghu66.top/Article/details/gt2hsrqfyns.html

JS:   process.env.HOME
来源：http://dali.zycfv.cn/Article/details/gt2qjacvqju.html

TS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gt2bkczbcqg.html

Java: System.getenv("HOME")
来源：http://dali.chenzaomai.com/Article/details/gt2xkeqlcei.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yj20258.top/Article/details/gt2whixhkgo.html

Ruby: ENV["HOME"]
来源：http://dali.wangshuangyany.cn/Article/details/gt2emdtufjj.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dtyexgso.html

[M03] 执行外部命令
来源：http://dali.havefunace.top/Article/details/gt2ffwemibw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2iznwabtr.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ppjwa.cn/Article/details/gt2srczvswb.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.fzhhl.top/Article/details/gt2tauicbjj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhijiandao.cn/Article/details/gt2jysoopdk.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.haohaochexian.top/Article/details/gt2oiukksax.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhongyouzk.top/Article/details/gt2iigwntuc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ppjwa.cn/Article/details/gt2tcshqimn.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cucudq.cn/Article/details/gt2doorzgzg.html

[M04] 获取当前工作目录
来源：http://dali.sxryk.cn/Article/details/gt2gllavneo.html

Py:   os.getcwd()
来源：http://dali.0kj1m.cn/Article/details/gt2owmfthkn.html

PHP:  getcwd();
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzlksnmo.html

JS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gt2zwfaxwbx.html

TS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gt2anjtzuvv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.yanxiufei.cn/Article/details/gt2sgstsuxu.html

Go:   os.Getwd()
来源：http://dali.havefunace.top/Article/details/gt2vjktylpe.html

Ruby: Dir.pwd
来源：http://dali.tian-w.cn/Article/details/gt2exkwutqi.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.daria6918.cn/Article/details/gt2bugbzccj.html

[M05] 设置退出码
来源：http://dali.daria6918.cn/Article/details/gt2gtfnvxxo.html

Py:   sys.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qcnfaxfg.html

PHP:  exit(1);
来源：http://dali.pycfn.com/Article/details/gt2tpoxuemr.html

JS:   process.exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2fwnqqopv.html

TS:   process.exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2mhsolhen.html

Java: System.exit(1)
来源：http://dali.jqgfzy.top/Article/details/gt2hoboasao.html

Go:   os.Exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2nnuutidq.html

Ruby: exit 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2cwxkmqft.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.yj202588.top/Article/details/gt2znjdwdfi.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gt2fxxtsmbu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gt2bdsdknwx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ybcxt.top/Article/details/gt2tvzebvxz.html

JS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ktnaghvf.html

TS:   console.error("err")
来源：http://dali.yangfankeji.com/Article/details/gt2seeqgyzx.html

Java: System.err.println("err")
来源：http://dali.cqqwz.cn/Article/details/gt2hpztrykt.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.meibo888.top/Article/details/gt2xoqokzcv.html

Ruby: warn "err"
来源：http://dali.zhixingplan.top/Article/details/gt2lkjrkeij.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.c1oappe.top/Article/details/gt2sakaxqrb.html

[M07] 判断是否为主入口
来源：http://dali.dashuyun.cn/Article/details/gt2oucbikgu.html

Py:   if __name__ == "__main__":
来源：http://dali.cdnleiting.top/Article/details/gt2fhcnwxhd.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigufen.top/Article/details/gt2qcigujmw.html

JS:   require.main === module
来源：http://dali.gotoacloud.top/Article/details/gt2idlbqahs.html

TS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gt2qsovbvqo.html

Java: public static void main(String[] args)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ucbmxyro.html

Go:   func main()
来源：http://dali.zhengqikj.top/Article/details/gt2yojvkdju.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhongyouzk.top/Article/details/gt2puxmfwua.html

C#:   static void Main(string[] args)
来源：http://dali.wangdashe.top/Article/details/gt2bizcsmnr.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2icoogvum.html

Py:   platform.system();  platform.python_version()
来源：http://dali.dianchejie.cn/Article/details/gt2aawregge.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhoulong.xyz/Article/details/gt2hznagorp.html

JS:   process.platform;  process.version
来源：http://dali.fengsongda.top/Article/details/gt2ogwfwspi.html

TS:   process.platform;  process.version
来源：http://dali.tianlin.xyz/Article/details/gt2amtrwoyj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gzhubu.top/Article/details/gt2cnnhhdod.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gt2eeezxzbv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.shuidangran.top/Article/details/gt2oajzffds.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xinyue.icu/Article/details/gt2zktcmjzk.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2pfefckmn.html

N. 数据结构与算法
来源：http://dali.jlsjyb.cn/Article/details/gt2mqrtbvri.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ybexvunt.html

[N01] 二分查找（有序数组）
来源：http://dali.cheryme.top/Article/details/gt2cnhmvmfq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.c1oappe.top/Article/details/gt2bppfgnhw.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtkxznsn.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.shzxlz.cn/Article/details/gt2tlwgdean.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnqzz.top/Article/details/gt2vrxqxliv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2zizqbhcn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2onrdyqax.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.jqgfzy.top/Article/details/gt2xssctymh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2zprzvkfw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.chenzaomai.com/Article/details/gt2qsrljaqt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nanxuanxn.top/Article/details/gt2mbaoljpc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sxryk.cn/Article/details/gt2wxkutgkv.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.meibo888.top/Article/details/gt2carufqbs.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gt2zmilvgra.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.tianlin.xyz/Article/details/gt2kykhrfuj.html

Go:   slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2zqphyzsw.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gt2mpqrsfvv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.chenzaomai.com/Article/details/gt2rauysruk.html

[N03] 快速排序（分治示例）
来源：http://dali.sysykeji.top/Article/details/gt2fplotzua.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.dashuyun.cn/Article/details/gt2hztmbwcw.html

PHP:  // 递归实现，或用 usort
来源：http://dali.bjfxy.top/Article/details/gt2nbmffynb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yongpay.top/Article/details/gt2iljbekhj.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gt2pnzhhxfk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.mhx1999.top/Article/details/gt2xinojtit.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.9152youxi.cn/Article/details/gt2fsdolifk.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.guannengcc.top/Article/details/gt2kxbbgvtz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhixingplan.top/Article/details/gt2iffeczcm.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gt2vrjdtfeu.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eirfmgtt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258.top/Article/details/gt2jfjakclo.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xinyue.icu/Article/details/gt2btwhxtpb.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.0kj1m.cn/Article/details/gt2gnlgygdz.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hywenlv.cn/Article/details/gt2tkzgoxxa.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuanzhike.top/Article/details/gt2xjoktrzu.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gt2kmvyfita.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gt2wjqfexsu.html

[N05] 最大公约数
来源：http://dali.c1oappe.top/Article/details/gt2wsfxfmbr.html

Py:   math.gcd(a, b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wnegixqv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.daxiang520.top/Article/details/gt2cjsmzzui.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kxlcidps.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gt2rpkbnybu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.gaohongyu789.top/Article/details/gt2itoxehff.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yvedp.cn/Article/details/gt2stwrykcs.html

Ruby: a.gcd(b)
来源：http://dali.yuanzhike.top/Article/details/gt2fxctqgog.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yonumen.top/Article/details/gt2qikrhhty.html

[N06] 判断回文字符串
来源：http://dali.pycfn.com/Article/details/gt2ytnkoyio.html

Py:   s == s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gt2fdylltwe.html

PHP:  $s === strrev($s);
来源：http://dali.sxryk.cn/Article/details/gt2rehlxwwt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2abcwbwfq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hiuvpmdf.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.zdqjudy.top/Article/details/gt2awkzkxpk.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gt2qxliyttm.html

Ruby: s == s.reverse
来源：http://dali.shzxlz.cn/Article/details/gt2zmlgctni.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gt2jlopgbwy.html

[N07] 两数之和（返回下标）
来源：http://dali.yj20258888.top/Article/details/gt2nzodbwbr.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2alljffff.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.meibo888.top/Article/details/gt2kbvikaqd.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yueranfly.top/Article/details/gt2hdydbesw.html

TS:   // 手写 Map<string, number>
来源：http://dali.gzhubu.top/Article/details/gt2vcurqndk.html

Java: // 手写 HashMap
来源：http://dali.kuanghao11.cn/Article/details/gt2tcikbfsw.html

Go:   // 手写 map[int]int
来源：http://dali.yj20258888.top/Article/details/gt2bzsgzhmh.html

Ruby: // 手写 Hash
来源：http://dali.feifeiyinyue.top/Article/details/gt2vgfjrtgf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dianchejie.cn/Article/details/gt2jznyfhrn.html

[N08] 生成全排列
来源：http://dali.quarkkingdee.top/Article/details/gt2febkzojn.html

Py:   itertools.permutations(arr)
来源：http://dali.cqqwz.cn/Article/details/gt2thwyreyn.html

PHP:  // 手写递归交换
来源：http://dali.yj20258888.top/Article/details/gt2zrnrdxxj.html

JS:   // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2pjzxpmfb.html

TS:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2tkjlyahw.html

Java: // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2oythwhum.html

Go:   // 手写回溯递归
来源：http://dali.yj202588.top/Article/details/gt2bsekhqln.html

Ruby: arr.permutation.to_a
来源：http://dali.jinqigfzy.top/Article/details/gt2dasveycp.html

C#:   // 手写回溯递归
来源：http://dali.sufxvd.cn/Article/details/gt2nhoryclg.html

[N09] 栈与队列
来源：http://dali.wangdashe.top/Article/details/gt2fuqvusuj.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.316326.xyz/Article/details/gt2hsyshpgb.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2cvrcpzab.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gt2fxqiqjyv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yanxiufei.cn/Article/details/gt2celsumgm.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.vqdsnc.cn/Article/details/gt2ztzvvmuz.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jqgufenzy.top/Article/details/gt2yskaclva.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hywenlv.cn/Article/details/gt2yyzxdlqa.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.birdmap.top/Article/details/gt2mwbzzehd.html

[N10] 链表节点定义
来源：http://dali.c1oappe.top/Article/details/gt2suvhqatf.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.guannengcc.top/Article/details/gt2qrbitmlj.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nwbrower.top/Article/details/gt2mvyrsmji.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqjupoun.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.snrcjt.cn/Article/details/gt2yjbxszfa.html

Java: class Node { int v; Node next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qyjjkhnn.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.hnqzz.top/Article/details/gt2hyzodvqe.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangshuangyany.cn/Article/details/gt2auyjkpia.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.sufxvd.cn/Article/details/gt2vfqxebbp.html

[N11] 二叉树中序遍历
来源：http://dali.sweek.top/Article/details/gt2dknwznte.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.dianchejie.cn/Article/details/gt2mqqgzpbp.html

PHP:  // 手写递归函数
来源：http://dali.jiagoushi.top/Article/details/gt2ydhifhox.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gt2vytlbbbq.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jqgfzy.top/Article/details/gt2hazaghcc.html

Java: // 手写递归
来源：http://dali.guannengcc.top/Article/details/gt2mkeoteux.html

Go:   // 手写递归
来源：http://dali.zhixingplan.top/Article/details/gt2qvueygsk.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jiagoushi.top/Article/details/gt2dsugiwrk.html

C#:   // 手写递归
来源：http://dali.kuanghao11.cn/Article/details/gt2gpcklowk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmtqxrxp.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.smart0.xyz/Article/details/gt2ylmkbemz.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigufen.top/Article/details/gt2gvmkyiax.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gzhubu.top/Article/details/gt2bdsedibo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gt2yizirvcy.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gt2syyxpaew.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nlivxfai.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.birdmap.top/Article/details/gt2rszmcqmk.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.c1oappe.top/Article/details/gt2colbmpwp.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2mfgwdgmb.html

O. 并发与异步
来源：http://dali.316326.xyz/Article/details/gt2ccyopanf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2kronnjdw.html

[O01] 启动一个线程
来源：http://dali.hnqzz.top/Article/details/gt2eowijxwi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jdoeephr.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nwbrower.top/Article/details/gt2zylcharu.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.9152youxi.cn/Article/details/gt2piornqro.html

TS:   // 同 JS
来源：http://dali.hammf.cn/Article/details/gt2vzcpmmuz.html

Java: new Thread(() -> f()).start()
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzfpfllb.html

Go:   go f()
来源：http://dali.guowangkeji.top/Article/details/gt2twgornpr.html

Ruby: Thread.new { f }
来源：http://dali.hnqzz.top/Article/details/gt2qbwdifiv.html

C#:   Task.Run(() => F());
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lutejlds.html

[O02] 使用线程池
来源：http://dali.nwbrower.top/Article/details/gt2blaxkcyh.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2xjpvpuhc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.shzxlz.cn/Article/details/gt2uyunbrze.html

JS:   // worker_threads 线程池
来源：http://dali.vqdsnc.cn/Article/details/gt2mujawrit.html

TS:   // worker_threads 线程池
来源：http://dali.yj20258888.top/Article/details/gt2aanpyelp.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.hammf.cn/Article/details/gt2rfgyggmy.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.nanxuanxn.top/Article/details/gt2wynwkloe.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nufyucti.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sysykeji.top/Article/details/gt2swyonaaq.html

[O03] 加锁保护共享数据
来源：http://dali.gotoacloud.top/Article/details/gt2wiyebbqc.html

Py:   with lock: shared += 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2uzblxwvf.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.jianghu66.top/Article/details/gt2roednbls.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.chenlongwang.top/Article/details/gt2vnxtpizw.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2vbhvouri.html

Java: synchronized (this) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kdvbadtz.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.meibo888.top/Article/details/gt2apxzksml.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhengqikj.top/Article/details/gt2kxjuejqg.html

C#:   lock (gate) { shared++; }
来源：http://dali.sufxvd.cn/Article/details/gt2mfudurux.html

[O04] 定义异步函数并等待
来源：http://dali.hammf.cn/Article/details/gt2ymfuxdqn.html

Py:   async def f():⏎    await g()
来源：http://dali.fengsongda.top/Article/details/gt2mrmwgidn.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.bjfxy.top/Article/details/gt2ivbqvspk.html

JS:   async function f() { await g(); }
来源：http://dali.cqqwz.cn/Article/details/gt2zioxauzn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.havefunace.top/Article/details/gt2kstzrjlf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xuanzx.com/Article/details/gt2zhrgwbcq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xylfe.cn/Article/details/gt2jexcpbme.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.yueranfly.top/Article/details/gt2rexuysae.html

C#:   async Task F() { await G(); }
来源：http://dali.cashguo.top/Article/details/gt2zyfegwio.html

[O05] 并发执行并等待全部完成
来源：http://dali.cqqwz.cn/Article/details/gt2bpgbjpee.html

Py:   asyncio.gather(*tasks)
来源：http://dali.hammf.cn/Article/details/gt2fqebrnyh.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwujjiqg.html

JS:   await Promise.all(tasks)
来源：http://dali.jqgufenzy.top/Article/details/gt2eyxrnhvl.html

TS:   await Promise.all(tasks)
来源：http://dali.yuanzhike.top/Article/details/gt2vqfnnltu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cyvnhors.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ppjwa.cn/Article/details/gt2oqszvwxn.html

Ruby: threads.map(&:join)
来源：http://dali.jianghu66.top/Article/details/gt2isfsaeuu.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.birdmap.top/Article/details/gt2yxrtjpvw.html

[O06] 使用进程池
来源：http://dali.ehwqpu.com/Article/details/gt2nwzpuxrg.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yuxming.cn/Article/details/gt2lrfxvale.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.zhengqikj.top/Article/details/gt2xucqptmd.html

JS:   // child_process / cluster 模块
来源：http://dali.jqgfzy.top/Article/details/gt2ayekmdyw.html

TS:   // child_process / cluster 模块
来源：http://dali.yj20258.top/Article/details/gt2ztkhotoy.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.tanke756.top/Article/details/gt2ztkxatcm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.feifeiyinyue.top/Article/details/gt2asdejzho.html

Ruby: // fork 块
来源：http://dali.yongpay.top/Article/details/gt2smbmiooa.html

C#:   Parallel.For
来源：http://dali.aizwys.cn/Article/details/gt2lwkjxnmt.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2fwdqmoms.html

P. 常用工具函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hdinrlaw.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2rownjmjm.html

[P01] 生成 UUID
来源：http://dali.sweek.top/Article/details/gt2nvatbwte.html

Py:   str(uuid.uuid4())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gzkqocil.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.guowangkeji.top/Article/details/gt2esiuesan.html

JS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gt2ehnsntlm.html

TS:   crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gt2xuydttql.html

Java: UUID.randomUUID().toString()
来源：http://dali.jiagoushi.top/Article/details/gt2ougklmwc.html

Go:   // 用 github.com/google/uuid
来源：http://dali.aizwys.cn/Article/details/gt2txvcwwjv.html

Ruby: SecureRandom.uuid
来源：http://dali.jqgufenzy.top/Article/details/gt2ummlcvfs.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.gzhubu.top/Article/details/gt2unfvbxsf.html

[P02] MD5 / SHA256 摘要
来源：http://dali.ydzc1.top/Article/details/gt2cmuesxlr.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.fzhhl.top/Article/details/gt2gyiwpwtr.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.andypj.xyz/Article/details/gt2vjefxdpv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.316326.xyz/Article/details/gt2hjwskmay.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.vqdsnc.cn/Article/details/gt2srdavzyf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.hysaishi.cn/Article/details/gt2gnhkjsch.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.ppjwa.cn/Article/details/gt2nyroznat.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.jiagoushi.top/Article/details/gt2hqbzdnmx.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.daria6918.cn/Article/details/gt2yulbfpcz.html

[P03] 生成短随机字符串
来源：http://dali.jiagoushi.top/Article/details/gt2qbewmjgj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.jianghu66.top/Article/details/gt2hlvbtemu.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.hnqzz.top/Article/details/gt2ybduuxmb.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.sufxvd.cn/Article/details/gt2amwrganv.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhongyouzk.top/Article/details/gt2ertlopaq.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.daria6918.cn/Article/details/gt2mrxfszxy.html

Go:   // crypto/rand 生成随机字节后 base64 或 hex 编码
来源：http://dali.jlsjyb.cn/Article/details/gt2vgwusntf.html

Ruby: SecureRandom.alphanumeric(16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yogckaeh.html

C#:   RandomNumberGenerator.GetHexString(16)     // .NET 8+
来源：http://dali.jianghu66.top/Article/details/gt2pqmpvfqd.html

[P04] 求长度
来源：http://dali.redwolf501.top/Article/details/gt2gmppknkx.html


<!-- 参考信息 -->