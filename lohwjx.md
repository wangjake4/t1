代发 wailian999

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jiagoushi.top/Article/details/gtypnkdbgj.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.gotoacloud.top/Article/details/gtazoeifew.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.bjfxy.top/Article/details/gtgoknxzfp.html

[L06] 解析响应为 JSON
来源：http://dali.cdnleiting.top/Article/details/gtossmmxnl.html

Py:   resp.json()
来源：http://dali.hnxiangtu.top/Article/details/gtmdewumua.html

PHP:  json_decode($body, true);
来源：http://dali.chenlongwang.top/Article/details/gtfuutrmfh.html

JS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gtkebrsxqh.html

TS:   await resp.json()
来源：http://dali.yongpay.top/Article/details/gtrayjrgzs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gtmqtvdvkj.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnoweokb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.nwbrower.top/Article/details/gthrxthdnn.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangdashe.top/Article/details/gtitvnnpfj.html

[L07] 处理 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gtpyvjtrfs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.guowangkeji.top/Article/details/gtqxurdvjt.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aizwys.cn/Article/details/gtnzeqblbq.html

JS:   resp.ok;  resp.status
来源：http://dali.zycfv.cn/Article/details/gtdnbfnkuy.html

TS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtxoifwhmt.html

Java: resp.statusCode()
来源：http://dali.xuetiantiany.cn/Article/details/gtudnpnuvu.html

Go:   resp.StatusCode
来源：http://dali.aibaodan.cn/Article/details/gtzkssrpqt.html

Ruby: resp.code.to_i
来源：http://dali.tianlin.xyz/Article/details/gtvazfaqvl.html

C#:   (int)resp.StatusCode
来源：http://dali.vqdsnc.cn/Article/details/gtqxbcbxos.html

[L08] 并发请求多个地址
来源：http://dali.bjfxy.top/Article/details/gtfooiewhk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ybcxt.top/Article/details/gtqhxscqil.html

PHP:  curl_multi_init() 系列
来源：http://dali.ybcxt.top/Article/details/gtvpvhcyrj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gtpuuqboax.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gtdquufabx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.jqgufenzy.top/Article/details/gtjlstigih.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenjidiqi.icu/Article/details/gttdphypsm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.svipenyu.cn/Article/details/gtdphqruab.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.tian-w.cn/Article/details/gtiuxsoiju.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtedmckamf.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gtcpgyryhz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtrexcgdcg.html

[M01] 读取命令行参数
来源：http://dali.guannengcc.top/Article/details/gtksklrtyn.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtdopiibnz.html

PHP:  $argv;  $argc;
来源：http://dali.meibo888.top/Article/details/gtcphcqwgx.html

JS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gtjlbygvnk.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtqvnyzgjo.html

Java: args 数组（main 方法参数）
来源：http://dali.quarkkingdee.top/Article/details/gtcnsxtpve.html

Go:   os.Args[1:]
来源：http://dali.wangdashe.top/Article/details/gtglieiqej.html

Ruby: ARGV
来源：http://dali.yonumen.top/Article/details/gtuckqiyqr.html

C#:   args 数组（Main 方法参数）
来源：http://dali.svipenyu.cn/Article/details/gtooectpiq.html

[M02] 读取环境变量
来源：http://dali.jianghu66.top/Article/details/gtcfixvkkf.html

Py:   os.environ.get("HOME")
来源：http://dali.smart0.xyz/Article/details/gtuqcezvun.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gtqpvprlcd.html

JS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gtfvtqljpy.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtbbxdeyid.html

Java: System.getenv("HOME")
来源：http://dali.zhoulong.xyz/Article/details/gtwzutoyze.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gtqenutrln.html

Ruby: ENV["HOME"]
来源：http://dali.haohaochexian.top/Article/details/gtvjnjsszi.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hnqzz.top/Article/details/gtfjayzayz.html

[M03] 执行外部命令
来源：http://dali.fzhhl.top/Article/details/gtlykppacu.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.mhx1999.top/Article/details/gtqczhgron.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.nanxuanxn.top/Article/details/gtkfdtvnav.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ivvv.top/Article/details/gtheskdjvn.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtmrcjidgo.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.birdmap.top/Article/details/gtsemepqsg.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.jinqigufen.top/Article/details/gtigukjphk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yangfankeji.com/Article/details/gtdendimac.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnxiangtu.top/Article/details/gtdcthxhyz.html

[M04] 获取当前工作目录
来源：http://dali.zhengqikj.top/Article/details/gtctopqjyg.html

Py:   os.getcwd()
来源：http://dali.c1oappe.top/Article/details/gtghjkpruk.html

PHP:  getcwd();
来源：http://dali.0kj1m.cn/Article/details/gtlnkramib.html

JS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtgwqwphvj.html

TS:   process.cwd()
来源：http://dali.wangshuangyany.cn/Article/details/gterndgbfb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgufenzy.top/Article/details/gtbjqzysfj.html

Go:   os.Getwd()
来源：http://dali.yanxiufei.cn/Article/details/gtnlpogaas.html

Ruby: Dir.pwd
来源：http://dali.316326.xyz/Article/details/gtgepnikoo.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxuanxn.top/Article/details/gtqbfgxbnk.html

[M05] 设置退出码
来源：http://dali.jinghuilouyu.cn/Article/details/gtiizuwnhk.html

Py:   sys.exit(1)
来源：http://dali.zhixingplan.top/Article/details/gteswoibgf.html

PHP:  exit(1);
来源：http://dali.cheryme.top/Article/details/gtkwooxazf.html

JS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtkrgliaxh.html

TS:   process.exit(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtwnyozawe.html

Java: System.exit(1)
来源：http://dali.tian-w.cn/Article/details/gtrtyumopy.html

Go:   os.Exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthizliszu.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gtprqovwxp.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.tianlin.xyz/Article/details/gtulabuamx.html

[M06] 向标准错误输出
来源：http://dali.cqqwz.cn/Article/details/gtdsfjnups.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecdjovre.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuanzx.com/Article/details/gtcjruxdue.html

JS:   console.error("err")
来源：http://dali.cdnleiting.top/Article/details/gttddrejhs.html

TS:   console.error("err")
来源：http://dali.guannengcc.top/Article/details/gtxoperpko.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gtubyvsnni.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gzhubu.top/Article/details/gtknirabga.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gtgnkhlmyd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.yuanzhike.top/Article/details/gtnqeyanox.html

[M07] 判断是否为主入口
来源：http://dali.ehwqpu.com/Article/details/gtaggfnqzj.html

Py:   if __name__ == "__main__":
来源：http://dali.tian-w.cn/Article/details/gtyhcqhdqp.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuvtosjk.html

JS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gtvjkngtjm.html

TS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gttfyranfs.html

Java: public static void main(String[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gtyjvizlvj.html

Go:   func main()
来源：http://dali.meibo888.top/Article/details/gteehqvofw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.quarkkingdee.top/Article/details/gtryfygksb.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxmorvgh.html

[M08] 获取系统与运行时信息
来源：http://dali.tian-w.cn/Article/details/gtyrrhklut.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gtdkqgavvg.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zdqjudy.top/Article/details/gtydczqusk.html

JS:   process.platform;  process.version
来源：http://dali.cheryme.top/Article/details/gtixyhrrhc.html

TS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gtegdjiqsq.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jlsjyb.cn/Article/details/gtgjyfzmbu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzjnlugb.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.guowangkeji.top/Article/details/gtmtagqdvr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cdnleiting.top/Article/details/gtslasddnk.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtmsqngena.html

N. 数据结构与算法
来源：http://dali.jianghu66.top/Article/details/gtcbznohgc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtbpnnztjd.html

[N01] 二分查找（有序数组）
来源：http://dali.xinyue.icu/Article/details/gtpgrkmssz.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtrgqdpupa.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gtxnsktuis.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ydzc1.top/Article/details/gtlqrtusno.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhoulong.xyz/Article/details/gtnrsjjsgn.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtyltbozqn.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtrmfukgpk.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ppjwa.cn/Article/details/gtfrzagtrf.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhixingplan.top/Article/details/gtopdqgkpy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.9152youxi.cn/Article/details/gtxybwktoo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtinllstzt.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yj20258888.top/Article/details/gtqdgxfxdp.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.feifeiyinyue.top/Article/details/gtpwmemviy.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ydzc1.top/Article/details/gtwenbpyja.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigfzy.top/Article/details/gtzrrxvpqt.html

Go:   slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gttuyydylh.html

Ruby: arr.sort
来源：http://dali.hongshengwenyu.top/Article/details/gtnmknddqj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.wangdashe.top/Article/details/gtaleldzxv.html

[N03] 快速排序（分治示例）
来源：http://dali.hnqzz.top/Article/details/gthefxyjqx.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.meibo888.top/Article/details/gtopqpzsxf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hnqzz.top/Article/details/gtipyovsac.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.shzxlz.cn/Article/details/gtmaenfsla.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.iojbl.cn/Article/details/gtefrdpbuv.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgpzgmnls.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yanxiufei.cn/Article/details/gtlcjyztoq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gthicwzsgm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.xuanzx.com/Article/details/gtljhywegf.html

[N04] 斐波那契数列
来源：http://dali.nanxuanxn.top/Article/details/gtyjvjwdtw.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yvedp.cn/Article/details/gtoxjrzhmt.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.xuanzx.com/Article/details/gtvsjxlgiy.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gtzleyhaio.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtcjcrnetp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yj20258888.top/Article/details/gtmidqcgmt.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yuxming.cn/Article/details/gtiihjunon.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsudkxpuc.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.vqdsnc.cn/Article/details/gtwxmjmpwv.html

[N05] 最大公约数
来源：http://dali.yonumen.top/Article/details/gtdgyybnmh.html

Py:   math.gcd(a, b)
来源：http://dali.jiagoushi.top/Article/details/gtspqujcfe.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.sufxvd.cn/Article/details/gthdeqnexg.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jianghu66.top/Article/details/gtlhaoeeul.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yangfankeji.com/Article/details/gtghpikrok.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ybcxt.top/Article/details/gtebnukxfi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.quarkkingdee.top/Article/details/gthxmkbqee.html

Ruby: a.gcd(b)
来源：http://dali.dianchejie.cn/Article/details/gtkidfggup.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.hongshengwenyu.top/Article/details/gtkvooauit.html

[N06] 判断回文字符串
来源：http://dali.sweek.top/Article/details/gtajvvfveo.html

Py:   s == s[::-1]
来源：http://dali.yvedp.cn/Article/details/gtcdghldzj.html

PHP:  $s === strrev($s);
来源：http://dali.gaohongyu789.top/Article/details/gtdicgbdty.html

JS:   s === [...s].reverse().join("")
来源：http://dali.gzhubu.top/Article/details/gtfybhlseg.html

TS:   s === [...s].reverse().join("")
来源：http://dali.svipenyu.cn/Article/details/gtatmzraog.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hammf.cn/Article/details/gtdjhifhcg.html

Go:   // 双指针从两端比较
来源：http://dali.mhx1999.top/Article/details/gtzcnmrxxe.html

Ruby: s == s.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtlldelbnb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gtmvislxqk.html

[N07] 两数之和（返回下标）
来源：http://dali.daria6918.cn/Article/details/gtzepwuuvn.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.pycfn.com/Article/details/gtumaguzxz.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqgdguux.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fzhhl.top/Article/details/gtghykzqvt.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhijiandao.cn/Article/details/gtdoswmufi.html

Java: // 手写 HashMap
来源：http://dali.yuxming.cn/Article/details/gtmempacqh.html

Go:   // 手写 map[int]int
来源：http://dali.xuanzx.com/Article/details/gtazliyvah.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gtmwnqemzt.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fzhhl.top/Article/details/gtdonuoybn.html

[N08] 生成全排列
来源：http://dali.yj20258.top/Article/details/gthltyjyny.html

Py:   itertools.permutations(arr)
来源：http://dali.hfpthk.cn/Article/details/gtopfsjlvi.html

PHP:  // 手写递归交换
来源：http://dali.yvedp.cn/Article/details/gtcycuyvup.html

JS:   // 手写回溯递归
来源：http://dali.zhixingplan.top/Article/details/gtxrrvfqqs.html

TS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtezumnmig.html

Java: // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gtflqqusck.html

Go:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gtbsbwfaun.html

Ruby: arr.permutation.to_a
来源：http://dali.haohaochexian.top/Article/details/gtitmpujuj.html

C#:   // 手写回溯递归
来源：http://dali.nanxuanxn.top/Article/details/gthpzczwhm.html

[N09] 栈与队列
来源：http://dali.sweek.top/Article/details/gttfwrwazw.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.aibaodan.cn/Article/details/gthbogqmxr.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ybcxt.top/Article/details/gtqmlbiwps.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hongshengwenyu.top/Article/details/gtbajuwnbv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gaohongyu789.top/Article/details/gtwuajlkua.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangdashe.top/Article/details/gtwphmjimo.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.c1oappe.top/Article/details/gtxxiguvnl.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.daria6918.cn/Article/details/gtztdkoals.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.wangdashe.top/Article/details/gtpmxhmeud.html

[N10] 链表节点定义
来源：http://dali.fengsongda.top/Article/details/gtjavkwbgc.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.zhixingplan.top/Article/details/gtwabznbwy.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwuvzqafo.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnqzz.top/Article/details/gtizjmuyzu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.aizwys.cn/Article/details/gtpwbyuwyn.html

Java: class Node { int v; Node next; }
来源：http://dali.guannengcc.top/Article/details/gtprtjdfrg.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.c1oappe.top/Article/details/gtubnukkxm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yuxming.cn/Article/details/gtmemtupml.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tanke756.top/Article/details/gtewycwjcm.html

[N11] 二叉树中序遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtgxgojpef.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cqqwz.cn/Article/details/gtzpoayysr.html

PHP:  // 手写递归函数
来源：http://dali.cdnleiting.top/Article/details/gtcbatmfja.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hysaishi.cn/Article/details/gtwicpulrx.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gtwggxosqt.html

Java: // 手写递归
来源：http://dali.yonumen.top/Article/details/gtytlimqid.html

Go:   // 手写递归
来源：http://dali.ivvv.top/Article/details/gttcwppfgx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.aizwys.cn/Article/details/gtrynfjwjk.html

C#:   // 手写递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtdaxoimxp.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.daxiang520.top/Article/details/gtqvvrermb.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cheryme.top/Article/details/gtivuvntcd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.hnqzz.top/Article/details/gtqkjqoptu.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gotoacloud.top/Article/details/gtdqfvbdbs.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.hongshengwenyu.top/Article/details/gthgrzjubl.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyritzecb.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jianghu66.top/Article/details/gtonrazprk.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.chenzaomai.com/Article/details/gtxzypzeyj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvfxotqc.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtikkcqpgu.html

O. 并发与异步
来源：http://dali.haohaochexian.top/Article/details/gtiiagxpce.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtrxwuusya.html

[O01] 启动一个线程
来源：http://dali.9152youxi.cn/Article/details/gtmmrdpqxa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.guowangkeji.top/Article/details/gtyhmnjiuy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258888.top/Article/details/gtwxhzznho.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.andypj.xyz/Article/details/gtzztnfsfh.html

TS:   // 同 JS
来源：http://dali.shuidangran.top/Article/details/gtsgvoupca.html

Java: new Thread(() -> f()).start()
来源：http://dali.zhengqikj.top/Article/details/gtnsqooycd.html

Go:   go f()
来源：http://dali.sxryk.cn/Article/details/gtmyoqywme.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmdwoqzil.html

C#:   Task.Run(() => F());
来源：http://dali.tianlin.xyz/Article/details/gtxvbxjkfk.html

[O02] 使用线程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotitcoon.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvarjget.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gotoacloud.top/Article/details/gtlmjokpbx.html

JS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gtyxhuzqcn.html

TS:   // worker_threads 线程池
来源：http://dali.nwbrower.top/Article/details/gtybwroeby.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zdqjudy.top/Article/details/gtgwntmlsr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.redwolf501.top/Article/details/gtlzqggqsv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.9152youxi.cn/Article/details/gtmmzmpbng.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.9152youxi.cn/Article/details/gttaosripb.html

[O03] 加锁保护共享数据
来源：http://dali.cashguo.top/Article/details/gtwlnsuppl.html

Py:   with lock: shared += 1
来源：http://dali.aibaodan.cn/Article/details/gtlbkifhme.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.zycfv.cn/Article/details/gtpsplftyy.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.c1oappe.top/Article/details/gtejljnxvt.html

TS:   // 同 JS
来源：http://dali.cashguo.top/Article/details/gtzmmsuscr.html

Java: synchronized (this) { shared++; }
来源：http://dali.bjfxy.top/Article/details/gtchlrcgdu.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sxryk.cn/Article/details/gtkxfrzagl.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.havefunace.top/Article/details/gtzpayyqin.html

C#:   lock (gate) { shared++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzmznxlen.html

[O04] 定义异步函数并等待
来源：http://dali.jlsjyb.cn/Article/details/gtairdrrrb.html

Py:   async def f():⏎    await g()
来源：http://dali.yuxming.cn/Article/details/gtqbddtvnj.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.jlsjyb.cn/Article/details/gtwpdvsfgx.html

JS:   async function f() { await g(); }
来源：http://dali.snrcjt.cn/Article/details/gtumlhvkoy.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtjgsphmhf.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.pengpengdd.cyou/Article/details/gtzowxsyaf.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.hywenlv.cn/Article/details/gtpffrsqwp.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.tianlin.xyz/Article/details/gtgqmcmitx.html

C#:   async Task F() { await G(); }
来源：http://dali.9152youxi.cn/Article/details/gtnncmvezh.html

[O05] 并发执行并等待全部完成
来源：http://dali.redwolf501.top/Article/details/gtmgxcsdmw.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xuetiantiany.cn/Article/details/gthfihzmyv.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.yuxming.cn/Article/details/gtimjehhzv.html

JS:   await Promise.all(tasks)
来源：http://dali.nanxinkj.top/Article/details/gtumdzvjzp.html

TS:   await Promise.all(tasks)
来源：http://dali.yangfankeji.com/Article/details/gttjpfuzkm.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gtjlxegokn.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.ivvv.top/Article/details/gtzghrceyd.html

Ruby: threads.map(&:join)
来源：http://dali.hywenlv.cn/Article/details/gtdmzccdwj.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.dianchejie.cn/Article/details/gtvihbuqsc.html

[O06] 使用进程池
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnmxuqqid.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.cucudq.cn/Article/details/gtktptaubj.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.mhx1999.top/Article/details/gtfhpdtugw.html

JS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gtzpurtzas.html

TS:   // child_process / cluster 模块
来源：http://dali.yvedp.cn/Article/details/gtmmkicfkz.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.snrcjt.cn/Article/details/gtyyevwhlm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.316326.xyz/Article/details/gtasqpnpbp.html

Ruby: // fork 块
来源：http://dali.0kj1m.cn/Article/details/gtfifsbyai.html

C#:   Parallel.For
来源：http://dali.0kj1m.cn/Article/details/gttzhctuuf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gthsvxlpnw.html

P. 常用工具函数
来源：http://dali.sufxvd.cn/Article/details/gtyrwjbyfo.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtxdkgxzqp.html

[P01] 生成 UUID
来源：http://dali.xylfe.cn/Article/details/gtpsqkelsv.html

Py:   str(uuid.uuid4())
来源：http://dali.hnxiangtu.top/Article/details/gtqujjbtwz.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.aibaodan.cn/Article/details/gtxertvjnj.html

JS:   crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtsuqrgasl.html

TS:   crypto.randomUUID()
来源：http://dali.yanxiufei.cn/Article/details/gtlzcrpnmx.html

Java: UUID.randomUUID().toString()
来源：http://dali.yuanzhike.top/Article/details/gtsstlqvid.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinqigfzy.top/Article/details/gtwjiqmkoz.html

Ruby: SecureRandom.uuid
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjtrzwnn.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.cheryme.top/Article/details/gthdcqhsxa.html

[P02] MD5 / SHA256 摘要
来源：http://dali.yvedp.cn/Article/details/gtrchtmwiz.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.0kj1m.cn/Article/details/gtoetzdrhg.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxinkj.top/Article/details/gtoxpbivxc.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yvedp.cn/Article/details/gtrhsphwyq.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.tanke756.top/Article/details/gtsgyylgtf.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.xuanzx.com/Article/details/gthhmvunto.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.redwolf501.top/Article/details/gtqnxzkrpy.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.yongpay.top/Article/details/gtwinbhicl.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.sweek.top/Article/details/gtdutzdbwm.html

[P03] 生成短随机字符串
来源：http://dali.xuanzx.com/Article/details/gtjkfcdglr.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yangfankeji.com/Article/details/gtrktitlws.html

PHP:  substr(str_shuffle(str_repeat("abcdefghijklmnopqrstuvwxyz0123456789", 2)), 0, 16);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnxleure.html

JS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.tanke756.top/Article/details/gtrwhggquz.html

TS:   [...crypto.getRandomValues(new Uint8Array(16))].map(b => (b % 36).toString(36)).join("")
来源：http://dali.zhixingplan.top/Article/details/gtllmkhrna.html

Java: new BigInteger(130, new SecureRandom()).toString(36).substring(0, 16)
来源：http://dali.cashguo.top/Article/details/gtkqhukkra.html


<!-- 参考信息 -->