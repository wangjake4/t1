代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.ybcxt.top/Article/details/gt2pxiodoph.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.yongpay.top/Article/details/gt2nogeqflg.html

[L05] 上传文件（multipart）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ajkjwjmr.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.haohaochexian.top/Article/details/gt2vhffpnxe.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2pmxcxxcp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gt2ncnhsjjz.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jinqigufen.top/Article/details/gt2blxtgxpj.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.daxiang520.top/Article/details/gt2kssacdvl.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2samtwzdz.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jinqigfzy.top/Article/details/gt2fwcjjdyz.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2pyzcdrlh.html

[L06] 解析响应为 JSON
来源：http://dali.chenzaomai.com/Article/details/gt2yxqcxxac.html

Py:   resp.json()
来源：http://dali.yj20258.top/Article/details/gt2pzrggcrz.html

PHP:  json_decode($body, true);
来源：http://dali.dianchejie.cn/Article/details/gt2qyyufpqc.html

JS:   await resp.json()
来源：http://dali.chenjidiqi.icu/Article/details/gt2scenlbkp.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2nftjtvmj.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.xylfe.cn/Article/details/gt2xahrzlbm.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.9152youxi.cn/Article/details/gt2omucpakr.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jinqigfzy.top/Article/details/gt2ecvixqvr.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.cdnleiting.top/Article/details/gt2toacrfnd.html

[L07] 处理 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2zkunozna.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpoyxrpg.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.daria6918.cn/Article/details/gt2kyogqkfp.html

JS:   resp.ok;  resp.status
来源：http://dali.cheryme.top/Article/details/gt2wfwhytjv.html

TS:   resp.ok;  resp.status
来源：http://dali.sxryk.cn/Article/details/gt2jvqidfju.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gt2nqcdgxux.html

Go:   resp.StatusCode
来源：http://dali.tian-w.cn/Article/details/gt2rietgeaf.html

Ruby: resp.code.to_i
来源：http://dali.sufxvd.cn/Article/details/gt2pgdgpkyn.html

C#:   (int)resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gt2mdgwglor.html

[L08] 并发请求多个地址
来源：http://dali.yvedp.cn/Article/details/gt2awgnuprn.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.aizwys.cn/Article/details/gt2kmviraoe.html

PHP:  curl_multi_init() 系列
来源：http://dali.zdqjudy.top/Article/details/gt2uniclowz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pupavdqt.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mygizhxq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.daxiang520.top/Article/details/gt2llckdajy.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.chenzaomai.com/Article/details/gt2rjcxlwjt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ydzc1.top/Article/details/gt2gkecxjsw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.redwolf501.top/Article/details/gt2vigkrpca.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2bxyursfc.html

M. 命令行 / 进程 / 环境
来源：http://dali.mhx1999.top/Article/details/gt2odyrucab.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2nldrzubk.html

[M01] 读取命令行参数
来源：http://dali.gogol.net.cn/Article/details/gt2dgnwikpx.html

Py:   sys.argv[1:]
来源：http://dali.vqdsnc.cn/Article/details/gt2wqqnvwhi.html

PHP:  $argv;  $argc;
来源：http://dali.sweek.top/Article/details/gt2bifhdgqm.html

JS:   process.argv.slice(2)
来源：http://dali.zhixingplan.top/Article/details/gt2kbhmbhry.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gt2xfjueawz.html

Java: args 数组（main 方法参数）
来源：http://dali.shuidangran.top/Article/details/gt2fveajitf.html

Go:   os.Args[1:]
来源：http://dali.tianlin.xyz/Article/details/gt2ksijovbp.html

Ruby: ARGV
来源：http://dali.mhx1999.top/Article/details/gt2slrwbqjx.html

C#:   args 数组（Main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gt2jxjlcglj.html

[M02] 读取环境变量
来源：http://dali.zhengqikj.top/Article/details/gt2cuifgivr.html

Py:   os.environ.get("HOME")
来源：http://dali.jlsjyb.cn/Article/details/gt2afpksjtv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.sxryk.cn/Article/details/gt2nuawxzuk.html

JS:   process.env.HOME
来源：http://dali.cashguo.top/Article/details/gt2yiqbmoyz.html

TS:   process.env.HOME
来源：http://dali.ppjwa.cn/Article/details/gt2ylcigfvc.html

Java: System.getenv("HOME")
来源：http://dali.daxiang520.top/Article/details/gt2rypnieli.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.yangfankeji.com/Article/details/gt2otpljikv.html

Ruby: ENV["HOME"]
来源：http://dali.quarkkingdee.top/Article/details/gt2vxzaxzds.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2bdjjienl.html

[M03] 执行外部命令
来源：http://dali.svipenyu.cn/Article/details/gt2clgunoap.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gt2inxmykak.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.yj20258888.top/Article/details/gt2ihmpwstg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgfzy.top/Article/details/gt2ehsndixb.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.shzxlz.cn/Article/details/gt2qinvybdh.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gt2uyaiysfj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.ivvv.top/Article/details/gt2nxxtfpdc.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzcxfyan.html

C#:   Process.Start("ls", "-l");
来源：http://dali.cdnleiting.top/Article/details/gt2omojkkpi.html

[M04] 获取当前工作目录
来源：http://dali.gotoacloud.top/Article/details/gt2wqevazfw.html

Py:   os.getcwd()
来源：http://dali.hammf.cn/Article/details/gt2boowbvqk.html

PHP:  getcwd();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zqwhxbnx.html

JS:   process.cwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2trjekwbc.html

TS:   process.cwd()
来源：http://dali.snrcjt.cn/Article/details/gt2mgwcdqvc.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenzaomai.com/Article/details/gt2cmvoxgcn.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2iezvfqlc.html

Ruby: Dir.pwd
来源：http://dali.ppjwa.cn/Article/details/gt2jbgtashg.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.tanke756.top/Article/details/gt2zqisndmv.html

[M05] 设置退出码
来源：http://dali.jiagoushi.top/Article/details/gt2itddzlsu.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2ukbelnzq.html

PHP:  exit(1);
来源：http://dali.hnxiangtu.top/Article/details/gt2jsqsmqjm.html

JS:   process.exit(1)
来源：http://dali.tianlin.xyz/Article/details/gt2ajqoxzxt.html

TS:   process.exit(1)
来源：http://dali.aibaodan.cn/Article/details/gt2dkucdrts.html

Java: System.exit(1)
来源：http://dali.xinyue.icu/Article/details/gt2fuhkbjxt.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dtakkrxe.html

Ruby: exit 1
来源：http://dali.shangyingyoupin.top/Article/details/gt2mwiriehb.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.pengpengdd.cyou/Article/details/gt2yzqxdpfx.html

[M06] 向标准错误输出
来源：http://dali.dashuyun.cn/Article/details/gt2kubnebqk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gt2lfnldnvo.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.jqgufenzy.top/Article/details/gt2ptqyfivl.html

JS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gt2qymocelt.html

TS:   console.error("err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2hsxjdere.html

Java: System.err.println("err")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukehbjkd.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hywenlv.cn/Article/details/gt2jbokqdzj.html

Ruby: warn "err"
来源：http://dali.bjfxy.top/Article/details/gt2fypdncjd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.tianlin.xyz/Article/details/gt2xdpjgaee.html

[M07] 判断是否为主入口
来源：http://dali.yuanzhike.top/Article/details/gt2uiikakvv.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gt2wxwvsqqx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.c1oappe.top/Article/details/gt2jsxkdyrg.html

JS:   require.main === module
来源：http://dali.zhixingplan.top/Article/details/gt2vhjamhjt.html

TS:   require.main === module
来源：http://dali.dashuyun.cn/Article/details/gt2urhqasni.html

Java: public static void main(String[] args)
来源：http://dali.mhx1999.top/Article/details/gt2ikrcpvsn.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gt2tqzohgfo.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.chenzaomai.com/Article/details/gt2jiffxdzg.html

C#:   static void Main(string[] args)
来源：http://dali.meibo888.top/Article/details/gt2otxqzfrq.html

[M08] 获取系统与运行时信息
来源：http://dali.jqgufenzy.top/Article/details/gt2bgexyijs.html

Py:   platform.system();  platform.python_version()
来源：http://dali.ybcxt.top/Article/details/gt2ypgkysda.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.meibo888.top/Article/details/gt2uojajtel.html

JS:   process.platform;  process.version
来源：http://dali.zhixingplan.top/Article/details/gt2onttlvte.html

TS:   process.platform;  process.version
来源：http://dali.meibo888.top/Article/details/gt2aopsggjv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.andypj.xyz/Article/details/gt2ojmvkfqb.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.birdmap.top/Article/details/gt2sprcznzg.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.feifeiyinyue.top/Article/details/gt2ixfmgsra.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.snrcjt.cn/Article/details/gt2twloxlrn.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2senukvis.html

N. 数据结构与算法
来源：http://dali.sweek.top/Article/details/gt2rmzgbdml.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2psqupckr.html

[N01] 二分查找（有序数组）
来源：http://dali.ehwqpu.com/Article/details/gt2wwphsskk.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2ymshqzar.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2addayenc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinqigufen.top/Article/details/gt2bmwnotnj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gt2ssotewfy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2tvsgptxz.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ivvv.top/Article/details/gt2clprswha.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.tianlin.xyz/Article/details/gt2eahqeyyg.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.meibo888.top/Article/details/gt2zpqmcgvj.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhoulong.xyz/Article/details/gt2kzzyqrem.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gt2lwhrgbqb.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ioiumogw.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ewrhpupo.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gt2xkzfbjlx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2symqvuyi.html

Go:   slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2vzkgwvhg.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gt2rketklum.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.quarkkingdee.top/Article/details/gt2iqhgvvnb.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2iegmuwip.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhixingplan.top/Article/details/gt2gqhfoqka.html

PHP:  // 递归实现，或用 usort
来源：http://dali.dashuyun.cn/Article/details/gt2esvldjax.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dtwbwhzv.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuxming.cn/Article/details/gt2wqrgvucq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2okzcefoy.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hongshengwenyu.top/Article/details/gt2rpwrgzjr.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gt2kxwcqpcz.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gogol.net.cn/Article/details/gt2wpvomssy.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gt2vjvbbdqf.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hfpthk.cn/Article/details/gt2iavnkeil.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.ehwqpu.com/Article/details/gt2mwzijviw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigfzy.top/Article/details/gt2gajsezoh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.aizwys.cn/Article/details/gt2ygnjejsp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.yuxming.cn/Article/details/gt2izcnrpej.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ixkykhah.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.iojbl.cn/Article/details/gt2bwveaoup.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.bjfxy.top/Article/details/gt2rlwioxmo.html

[N05] 最大公约数
来源：http://dali.yueranfly.top/Article/details/gt2cfgtbxxb.html

Py:   math.gcd(a, b)
来源：http://dali.zhengqikj.top/Article/details/gt2ipmponah.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.jinqigfzy.top/Article/details/gt2junrhvlj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daxiang520.top/Article/details/gt2dnrlifdl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xinyue.icu/Article/details/gt2zihzgxxs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.guowangkeji.top/Article/details/gt2lwwzrgzc.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yuanzhike.top/Article/details/gt2hkvegqpf.html

Ruby: a.gcd(b)
来源：http://dali.havefunace.top/Article/details/gt2yzazdlfp.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.fengsongda.top/Article/details/gt2uizfpoyn.html

[N06] 判断回文字符串
来源：http://dali.birdmap.top/Article/details/gt2gblyqufn.html

Py:   s == s[::-1]
来源：http://dali.tianlin.xyz/Article/details/gt2lvqnolzm.html

PHP:  $s === strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gt2vnsxbxaw.html

JS:   s === [...s].reverse().join("")
来源：http://dali.havefunace.top/Article/details/gt2zkntodev.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nlqkujyg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.meibo888.top/Article/details/gt2rpeofcuh.html

Go:   // 双指针从两端比较
来源：http://dali.aibaodan.cn/Article/details/gt2qnmqhqgf.html

Ruby: s == s.reverse
来源：http://dali.sufxvd.cn/Article/details/gt2cjrrikdb.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.shuidangran.top/Article/details/gt2xjvwwkwt.html

[N07] 两数之和（返回下标）
来源：http://dali.zhongyouzk.top/Article/details/gt2xggsmsxt.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.jqgufenzy.top/Article/details/gt2hnfsgbmy.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.sxryk.cn/Article/details/gt2anftydcl.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.bjfxy.top/Article/details/gt2xupqfnvd.html

TS:   // 手写 Map<string, number>
来源：http://dali.kuanghao11.cn/Article/details/gt2yiykirux.html

Java: // 手写 HashMap
来源：http://dali.zhongyouzk.top/Article/details/gt2kldpxmyg.html

Go:   // 手写 map[int]int
来源：http://dali.cqqwz.cn/Article/details/gt2hsllskuh.html

Ruby: // 手写 Hash
来源：http://dali.zhiwuduotai.top/Article/details/gt2wxiwolqu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ocfesier.html

[N08] 生成全排列
来源：http://dali.316326.xyz/Article/details/gt2llrvqdnc.html

Py:   itertools.permutations(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2outfloqc.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gt2rwwrpbbl.html

JS:   // 手写回溯递归
来源：http://dali.9152youxi.cn/Article/details/gt2juyawsjr.html

TS:   // 手写回溯递归
来源：http://dali.ydzc1.top/Article/details/gt2wklqstyx.html

Java: // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2bgivgtdm.html

Go:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2dsnnahoa.html

Ruby: arr.permutation.to_a
来源：http://dali.jqgfzy.top/Article/details/gt2zkmkjmqy.html

C#:   // 手写回溯递归
来源：http://dali.chenzaomai.com/Article/details/gt2syoejfqj.html

[N09] 栈与队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pxixclwl.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hzxrisvo.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jiagoushi.top/Article/details/gt2wohxwiaq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.yvedp.cn/Article/details/gt2mgkyatdr.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jianghu66.top/Article/details/gt2ihpiciqi.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.dashuyun.cn/Article/details/gt2zfrwxazu.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangshuangyany.cn/Article/details/gt2mzmqkydm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.cdnleiting.top/Article/details/gt2qnpcjwgj.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pycfn.com/Article/details/gt2sgwmogqc.html

[N10] 链表节点定义
来源：http://dali.pengpengdd.cyou/Article/details/gt2xluoxpxn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.redwolf501.top/Article/details/gt2iawirnwt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.cdnleiting.top/Article/details/gt2tawznknj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.ydzc1.top/Article/details/gt2lnwqmtzl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.ybcxt.top/Article/details/gt2akfrptoh.html

Java: class Node { int v; Node next; }
来源：http://dali.vqdsnc.cn/Article/details/gt2pmwhasdq.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sweek.top/Article/details/gt2aujkriug.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.ivvv.top/Article/details/gt2thtngrhw.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.ivvv.top/Article/details/gt2pfnveytc.html

[N11] 二叉树中序遍历
来源：http://dali.xinyue.icu/Article/details/gt2knwsvptw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jlsjyb.cn/Article/details/gt2qsmlbbyj.html

PHP:  // 手写递归函数
来源：http://dali.meibo888.top/Article/details/gt2epqqoeah.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xziqi.cn/Article/details/gt2xwntffvv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yongpay.top/Article/details/gt2pehheogv.html

Java: // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2bpqrjamz.html

Go:   // 手写递归
来源：http://dali.jiagoushi.top/Article/details/gt2ardmgdiw.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yj202588.top/Article/details/gt2himeukpa.html

C#:   // 手写递归
来源：http://dali.yuanzhike.top/Article/details/gt2jfsykzzc.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfzjkca.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cashguo.top/Article/details/gt2wnzeiodt.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jianghu66.top/Article/details/gt2mkdpueei.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuetiantiany.cn/Article/details/gt2jslqkjxe.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.meibo888.top/Article/details/gt2ggatmjcr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.quarkkingdee.top/Article/details/gt2qysmswgd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.yanxiufei.cn/Article/details/gt2cacbdajn.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2qfdzwvmu.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhengqikj.top/Article/details/gt2pniadxat.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2gsaipohn.html

O. 并发与异步
来源：http://dali.hfpthk.cn/Article/details/gt2byanyktu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2htgmeerl.html

[O01] 启动一个线程
来源：http://dali.fzhhl.top/Article/details/gt2btupdnhi.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.redwolf501.top/Article/details/gt2tfsuijpd.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cqqwz.cn/Article/details/gt2xfzsirsv.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.chenzaomai.com/Article/details/gt2mlqxvecq.html

TS:   // 同 JS
来源：http://dali.jiagoushi.top/Article/details/gt2qxyxafqn.html

Java: new Thread(() -> f()).start()
来源：http://dali.yj20258888.top/Article/details/gt2gukrzlcq.html

Go:   go f()
来源：http://dali.9152youxi.cn/Article/details/gt2yqxxgckj.html

Ruby: Thread.new { f }
来源：http://dali.snrcjt.cn/Article/details/gt2bicvpssn.html

C#:   Task.Run(() => F());
来源：http://dali.gzhubu.top/Article/details/gt2ysjxlqpp.html

[O02] 使用线程池
来源：http://dali.aizwys.cn/Article/details/gt2onimzien.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.iojbl.cn/Article/details/gt2euswjsbi.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.gogol.net.cn/Article/details/gt2mzhjciyk.html

JS:   // worker_threads 线程池
来源：http://dali.yanxiufei.cn/Article/details/gt2zqvhyalx.html

TS:   // worker_threads 线程池
来源：http://dali.zhoulong.xyz/Article/details/gt2ubeslccq.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dudjjakm.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.sweek.top/Article/details/gt2wdcxphji.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.nwbrower.top/Article/details/gt2emzfqyjl.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.gotoacloud.top/Article/details/gt2xjxunqfw.html

[O03] 加锁保护共享数据
来源：http://dali.hongshengwenyu.top/Article/details/gt2sowbzmzz.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2msnflvvh.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.fengsongda.top/Article/details/gt2cwztfvim.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jqgfzy.top/Article/details/gt2gnfrxcuu.html

TS:   // 同 JS
来源：http://dali.yangfankeji.com/Article/details/gt2xvahlzdm.html

Java: synchronized (this) { shared++; }
来源：http://dali.nanxinkj.top/Article/details/gt2ewqxeadf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yueranfly.top/Article/details/gt2nwlagryo.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj20258.top/Article/details/gt2lrqthzyd.html

C#:   lock (gate) { shared++; }
来源：http://dali.gotoacloud.top/Article/details/gt2fjxzjgar.html

[O04] 定义异步函数并等待
来源：http://dali.svipenyu.cn/Article/details/gt2tupfpnrz.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258.top/Article/details/gt2bzsgdovx.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gt2bubmtfpl.html

JS:   async function f() { await g(); }
来源：http://dali.zhengqikj.top/Article/details/gt2gezkzunj.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.nanxinkj.top/Article/details/gt2okdrrujn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.cdnleiting.top/Article/details/gt2zyapfhiq.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.sxryk.cn/Article/details/gt2cjuqkwcr.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.haohaochexian.top/Article/details/gt2wdjcseda.html

C#:   async Task F() { await G(); }
来源：http://dali.tanke756.top/Article/details/gt2aajwhzva.html

[O05] 并发执行并等待全部完成
来源：http://dali.fzhhl.top/Article/details/gt2cwnbucey.html

Py:   asyncio.gather(*tasks)
来源：http://dali.guannengcc.top/Article/details/gt2wyshpthl.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinqigufen.top/Article/details/gt2svddzxzy.html

JS:   await Promise.all(tasks)
来源：http://dali.zhiwuduotai.top/Article/details/gt2boimhyfu.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2fzdvbpzr.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.bjfxy.top/Article/details/gt2buxxirdu.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zdqjudy.top/Article/details/gt2ohugxndh.html

Ruby: threads.map(&:join)
来源：http://dali.nanxuanxn.top/Article/details/gt2fzyuvjgx.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qgqedzip.html

[O06] 使用进程池
来源：http://dali.xuanzx.com/Article/details/gt2zamlrdnc.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.ybcxt.top/Article/details/gt2xjnjaoij.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fsbpqpht.html

JS:   // child_process / cluster 模块
来源：http://dali.kuanghao11.cn/Article/details/gt2ulnlmfsv.html

TS:   // child_process / cluster 模块
来源：http://dali.cdnleiting.top/Article/details/gt2lonzcovj.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dianchejie.cn/Article/details/gt2aabzcoew.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.hysaishi.cn/Article/details/gt2vfvoznkq.html

Ruby: // fork 块
来源：http://dali.chenzaomai.com/Article/details/gt2ezryrveb.html

C#:   Parallel.For
来源：http://dali.sxryk.cn/Article/details/gt2wprdrwwx.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2bmdysuxt.html

P. 常用工具函数
来源：http://dali.meibo888.top/Article/details/gt2anhlrykw.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2cccsnrvg.html

[P01] 生成 UUID
来源：http://dali.fengsongda.top/Article/details/gt2lwbbruwz.html

Py:   str(uuid.uuid4())
来源：http://dali.yvedp.cn/Article/details/gt2yhpnxyqy.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.hammf.cn/Article/details/gt2ryugueeb.html

JS:   crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gt2qgcglzue.html

TS:   crypto.randomUUID()
来源：http://dali.jinqigufen.top/Article/details/gt2slwhpacw.html

Java: UUID.randomUUID().toString()
来源：http://dali.xylfe.cn/Article/details/gt2xopndeaq.html

Go:   // 用 github.com/google/uuid
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cqyeebei.html

Ruby: SecureRandom.uuid
来源：http://dali.redwolf501.top/Article/details/gt2unxeezbk.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2elobbkju.html

[P02] MD5 / SHA256 摘要
来源：http://dali.nanxuanxn.top/Article/details/gt2vnlidlhp.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.gaohongyu789.top/Article/details/gt2ylzbpjtt.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.svipenyu.cn/Article/details/gt2gioxcnxv.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.0kj1m.cn/Article/details/gt2kafagpgd.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.chenzaomai.com/Article/details/gt2rboxlosu.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrwhjev.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.jinqigufen.top/Article/details/gt2qjwdhufl.html


<!-- 参考信息 -->