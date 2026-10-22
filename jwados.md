代发 wailian999

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cashguo.top/Article/details/gt2jcimjklv.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2putznjpl.html

[L05] 上传文件（multipart）
来源：http://dali.daria6918.cn/Article/details/gt2onvmejnb.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.smart0.xyz/Article/details/gt2dropowqz.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.cucudq.cn/Article/details/gt2vtiebmkt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.aibaodan.cn/Article/details/gt2elzcdmgo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgufenzy.top/Article/details/gt2lrzdwsqe.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.guowangkeji.top/Article/details/gt2bgvqdpgs.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sufxvd.cn/Article/details/gt2shwhdifm.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.vqdsnc.cn/Article/details/gt2emwrmvxb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2immyhhbs.html

[L06] 解析响应为 JSON
来源：http://dali.yvedp.cn/Article/details/gt2kpfkwsff.html

Py:   resp.json()
来源：http://dali.jiagoushi.top/Article/details/gt2sfxjrxti.html

PHP:  json_decode($body, true);
来源：http://dali.wangdashe.top/Article/details/gt2ybuinwpb.html

JS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fupgxsym.html

TS:   await resp.json()
来源：http://dali.gogol.net.cn/Article/details/gt2kgaaislk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.ppjwa.cn/Article/details/gt2itkuuvni.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.sufxvd.cn/Article/details/gt2gktdaobg.html

Ruby: JSON.parse(resp.body)
来源：http://dali.shzxlz.cn/Article/details/gt2qpzjxxmg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hysaishi.cn/Article/details/gt2pqmaqzio.html

[L07] 处理 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gt2wraxrevg.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.c1oappe.top/Article/details/gt2vlvvtrnj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.wangshuangyany.cn/Article/details/gt2qmfdpuyg.html

JS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gt2ipigoxiu.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gt2yimijbbg.html

Java: resp.statusCode()
来源：http://dali.pycfn.com/Article/details/gt2gfvfacta.html

Go:   resp.StatusCode
来源：http://dali.gotoacloud.top/Article/details/gt2grldgrwp.html

Ruby: resp.code.to_i
来源：http://dali.tanke756.top/Article/details/gt2bdukellx.html

C#:   (int)resp.StatusCode
来源：http://dali.tianlin.xyz/Article/details/gt2hxxrsexv.html

[L08] 并发请求多个地址
来源：http://dali.fzhhl.top/Article/details/gt2kqbmufca.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.jqgufenzy.top/Article/details/gt2ohdepovx.html

PHP:  curl_multi_init() 系列
来源：http://dali.jyoumei.cn/Article/details/gt2utjqegpz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gt2qrqhefec.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2bdzabpnu.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.chenzaomai.com/Article/details/gt2ynhkozud.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258.top/Article/details/gt2xbesiztg.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.dashuyun.cn/Article/details/gt2fzuyvyum.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.kuanghao11.cn/Article/details/gt2teswnrbf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2dvkmzflj.html

M. 命令行 / 进程 / 环境
来源：http://dali.andypj.xyz/Article/details/gt2edsicddr.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mvivlexj.html

[M01] 读取命令行参数
来源：http://dali.jinqigufen.top/Article/details/gt2otkogect.html

Py:   sys.argv[1:]
来源：http://dali.sufxvd.cn/Article/details/gt2bjmaxhao.html

PHP:  $argv;  $argc;
来源：http://dali.hongshengwenyu.top/Article/details/gt2elctqdfo.html

JS:   process.argv.slice(2)
来源：http://dali.jyoumei.cn/Article/details/gt2swmtldno.html

TS:   process.argv.slice(2)
来源：http://dali.xinyue.icu/Article/details/gt2ydftrskt.html

Java: args 数组（main 方法参数）
来源：http://dali.xuanzx.com/Article/details/gt2ulqdgaph.html

Go:   os.Args[1:]
来源：http://dali.quarkkingdee.top/Article/details/gt2ztmbmriu.html

Ruby: ARGV
来源：http://dali.meibo888.top/Article/details/gt2wsqdwnac.html

C#:   args 数组（Main 方法参数）
来源：http://dali.dianchejie.cn/Article/details/gt2uodsmhni.html

[M02] 读取环境变量
来源：http://dali.kuanghao11.cn/Article/details/gt2vrnavnnk.html

Py:   os.environ.get("HOME")
来源：http://dali.quarkkingdee.top/Article/details/gt2bmhwyezj.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhengqikj.top/Article/details/gt2cfuxbcuk.html

JS:   process.env.HOME
来源：http://dali.hywenlv.cn/Article/details/gt2dvltxgom.html

TS:   process.env.HOME
来源：http://dali.cheryme.top/Article/details/gt2tmhvndvk.html

Java: System.getenv("HOME")
来源：http://dali.sysykeji.top/Article/details/gt2ndlztzud.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2wsuqxcvr.html

Ruby: ENV["HOME"]
来源：http://dali.chenlongwang.top/Article/details/gt2mzawcwzw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.ivvv.top/Article/details/gt2wvqmfsdg.html

[M03] 执行外部命令
来源：http://dali.mhx1999.top/Article/details/gt2svmdmiit.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhengqikj.top/Article/details/gt2wcjbuddu.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.shangyingyoupin.top/Article/details/gt2ilixgqik.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cdnleiting.top/Article/details/gt2qdeerqkw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hsuuatru.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.sxryk.cn/Article/details/gt2cjoeottu.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yj202588.top/Article/details/gt2vyypajmk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.0kj1m.cn/Article/details/gt2bncbhmiq.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ckoavyeu.html

[M04] 获取当前工作目录
来源：http://dali.mhx1999.top/Article/details/gt2rsvemsok.html

Py:   os.getcwd()
来源：http://dali.gogol.net.cn/Article/details/gt2gxnciklr.html

PHP:  getcwd();
来源：http://dali.jqgufenzy.top/Article/details/gt2wkafkcxa.html

JS:   process.cwd()
来源：http://dali.hfpthk.cn/Article/details/gt2iezcrsei.html

TS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2wgiemgcb.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.chenjidiqi.icu/Article/details/gt2sgpbfihq.html

Go:   os.Getwd()
来源：http://dali.yj202588.top/Article/details/gt2twbwrnqc.html

Ruby: Dir.pwd
来源：http://dali.zhiwuduotai.top/Article/details/gt2ttyrusxu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.birdmap.top/Article/details/gt2yufecsnt.html

[M05] 设置退出码
来源：http://dali.zhengqikj.top/Article/details/gt2yihadved.html

Py:   sys.exit(1)
来源：http://dali.yj202588.top/Article/details/gt2unmcaatx.html

PHP:  exit(1);
来源：http://dali.tian-w.cn/Article/details/gt2jcqgqvll.html

JS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imntcelp.html

TS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2chmwukwn.html

Java: System.exit(1)
来源：http://dali.hnqzz.top/Article/details/gt2nuakvkez.html

Go:   os.Exit(1)
来源：http://dali.hywenlv.cn/Article/details/gt2jastqqfj.html

Ruby: exit 1
来源：http://dali.guannengcc.top/Article/details/gt2uyyjafts.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gt2pupppbwf.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gt2hmbrcteh.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yj202588.top/Article/details/gt2vygrjjyh.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zdqjudy.top/Article/details/gt2iivwpcyo.html

JS:   console.error("err")
来源：http://dali.redwolf501.top/Article/details/gt2hsfhwzss.html

TS:   console.error("err")
来源：http://dali.pycfn.com/Article/details/gt2hetizgqn.html

Java: System.err.println("err")
来源：http://dali.sweek.top/Article/details/gt2eazybuzn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ybcxt.top/Article/details/gt2sgmxidni.html

Ruby: warn "err"
来源：http://dali.yvedp.cn/Article/details/gt2nnsnvjwd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.nwbrower.top/Article/details/gt2cyuguhbz.html

[M07] 判断是否为主入口
来源：http://dali.xuetiantiany.cn/Article/details/gt2dxdefypv.html

Py:   if __name__ == "__main__":
来源：http://dali.yonumen.top/Article/details/gt2ekcrgmzk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.yanxiufei.cn/Article/details/gt2yaoqlcnf.html

JS:   require.main === module
来源：http://dali.daxiang520.top/Article/details/gt2nedxiwix.html

TS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zrvbdghe.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gt2rrerjqoa.html

Go:   func main()
来源：http://dali.cheryme.top/Article/details/gt2funmmmco.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gt2otukqccl.html

C#:   static void Main(string[] args)
来源：http://dali.zhengqikj.top/Article/details/gt2qfzwtlpm.html

[M08] 获取系统与运行时信息
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tvfatzld.html

Py:   platform.system();  platform.python_version()
来源：http://dali.tianlin.xyz/Article/details/gt2cbiltlys.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.jiagoushi.top/Article/details/gt2myxgmblf.html

JS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2agvbsigs.html

TS:   process.platform;  process.version
来源：http://dali.xuanzx.com/Article/details/gt2ftmipjjw.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.redwolf501.top/Article/details/gt2zhykinhs.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.316326.xyz/Article/details/gt2kigjocec.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuxming.cn/Article/details/gt2eusjfdhz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxklsduz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2ttmetggz.html

N. 数据结构与算法
来源：http://dali.chenzaomai.com/Article/details/gt2eivousax.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2mbolqopy.html

[N01] 二分查找（有序数组）
来源：http://dali.pengpengdd.cyou/Article/details/gt2znhcflya.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gt2iubpqeri.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jiagoushi.top/Article/details/gt2vrztfjro.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yj202588.top/Article/details/gt2bbabjnuj.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.tianlin.xyz/Article/details/gt2pjhunknd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eswnqhpc.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.dashuyun.cn/Article/details/gt2lzrmnpvx.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.aizwys.cn/Article/details/gt2dionvjds.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gt2mlqojawl.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.kuanghao11.cn/Article/details/gt2dqbpotlk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ddzcchdw.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.fengsongda.top/Article/details/gt2ppjxltvu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.smart0.xyz/Article/details/gt2vfbguagi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbekjaem.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gt2dlcrpdrk.html

Go:   slices.Sort(arr)
来源：http://dali.nwbrower.top/Article/details/gt2lkitztfb.html

Ruby: arr.sort
来源：http://dali.ehwqpu.com/Article/details/gt2muhiytrj.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.meibo888.top/Article/details/gt2ikojzqkx.html

[N03] 快速排序（分治示例）
来源：http://dali.yj202588.top/Article/details/gt2labpyzjy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdftnmq.html

PHP:  // 递归实现，或用 usort
来源：http://dali.jlsjyb.cn/Article/details/gt2cednzeql.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cucudq.cn/Article/details/gt2ezgiijvx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jlsjyb.cn/Article/details/gt2ofavrjvg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jyoumei.cn/Article/details/gt2asrctxws.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.gogol.net.cn/Article/details/gt2plycgver.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.sweek.top/Article/details/gt2stcovoof.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.meibo888.top/Article/details/gt2gtyerpbi.html

[N04] 斐波那契数列
来源：http://dali.cqqwz.cn/Article/details/gt2vjvuywzg.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.sufxvd.cn/Article/details/gt2jrncjpul.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yuanzhike.top/Article/details/gt2rqmrwlwk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.smart0.xyz/Article/details/gt2qshsxber.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.xziqi.cn/Article/details/gt2ooqiedpr.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjdeqxby.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.redwolf501.top/Article/details/gt2fbomwtlf.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.c1oappe.top/Article/details/gt2eykmmuvx.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2ebjxikfi.html

[N05] 最大公约数
来源：http://dali.quarkkingdee.top/Article/details/gt2rqpvnadx.html

Py:   math.gcd(a, b)
来源：http://dali.316326.xyz/Article/details/gt2rdbvowoh.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.9152youxi.cn/Article/details/gt2tzmuxvzj.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.c1oappe.top/Article/details/gt2jhgawefl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gt2wrvxfmdk.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zhongyouzk.top/Article/details/gt2dypdsqwo.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daxiang520.top/Article/details/gt2sjaevock.html

Ruby: a.gcd(b)
来源：http://dali.birdmap.top/Article/details/gt2gdtblzib.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yonumen.top/Article/details/gt2jlwbflwu.html

[N06] 判断回文字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2euioztjw.html

Py:   s == s[::-1]
来源：http://dali.kuanghao11.cn/Article/details/gt2dxvupnok.html

PHP:  $s === strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gt2npwvnifl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gt2houcsbud.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gt2xzojorzl.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuanzx.com/Article/details/gt2fzlxbwqt.html

Go:   // 双指针从两端比较
来源：http://dali.xylfe.cn/Article/details/gt2eqafovqn.html

Ruby: s == s.reverse
来源：http://dali.snrcjt.cn/Article/details/gt2ymjbvddu.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.bjfxy.top/Article/details/gt2iiciuwtm.html

[N07] 两数之和（返回下标）
来源：http://dali.sysykeji.top/Article/details/gt2kfkmkmox.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgtrlfbx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.mhx1999.top/Article/details/gt2drkqqeab.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.pycfn.com/Article/details/gt2sjfuxadh.html

TS:   // 手写 Map<string, number>
来源：http://dali.ivvv.top/Article/details/gt2aseywasm.html

Java: // 手写 HashMap
来源：http://dali.xuanzx.com/Article/details/gt2vnublgvl.html

Go:   // 手写 map[int]int
来源：http://dali.shangyingyoupin.top/Article/details/gt2ccabilyn.html

Ruby: // 手写 Hash
来源：http://dali.316326.xyz/Article/details/gt2yrswxyya.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.fzhhl.top/Article/details/gt2cgzxseeb.html

[N08] 生成全排列
来源：http://dali.jqgufenzy.top/Article/details/gt2oqxrntxi.html

Py:   itertools.permutations(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2gdcwenlu.html

PHP:  // 手写递归交换
来源：http://dali.chenlongwang.top/Article/details/gt2pymtoltr.html

JS:   // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2zxseznjw.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2uplnsoac.html

Java: // 手写回溯递归
来源：http://dali.sweek.top/Article/details/gt2etsawoju.html

Go:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2ozvdjkng.html

Ruby: arr.permutation.to_a
来源：http://dali.jyoumei.cn/Article/details/gt2szmswntb.html

C#:   // 手写回溯递归
来源：http://dali.jqgfzy.top/Article/details/gt2xhzgiktd.html

[N09] 栈与队列
来源：http://dali.jlsjyb.cn/Article/details/gt2zdvpftcc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yuanzhike.top/Article/details/gt2zascsghj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2khsanfud.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2iauubhmm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.gzhubu.top/Article/details/gt2qzdztcsh.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ybcxt.top/Article/details/gt2ghvvofnx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.aibaodan.cn/Article/details/gt2xqbenrzt.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gt2lvzzevjy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.svipenyu.cn/Article/details/gt2fvyasgfs.html

[N10] 链表节点定义
来源：http://dali.chenlongwang.top/Article/details/gt2qiacmbtm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.redwolf501.top/Article/details/gt2ijeuihnn.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2geymugse.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj20258888.top/Article/details/gt2qfsehasq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2illvhwbq.html

Java: class Node { int v; Node next; }
来源：http://dali.zhixingplan.top/Article/details/gt2rdryjjor.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gt2zwlzofts.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenlongwang.top/Article/details/gt2ceqajutn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dashuyun.cn/Article/details/gt2lowvwxlu.html

[N11] 二叉树中序遍历
来源：http://dali.guannengcc.top/Article/details/gt2bvprubyv.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.chenlongwang.top/Article/details/gt2pinalega.html

PHP:  // 手写递归函数
来源：http://dali.quarkkingdee.top/Article/details/gt2uuisawxx.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gt2gbtdfqol.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.chenzaomai.com/Article/details/gt2bjwzmzzv.html

Java: // 手写递归
来源：http://dali.redwolf501.top/Article/details/gt2wgxsusvi.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2jywgwwds.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.nanxuanxn.top/Article/details/gt2jjafltbd.html

C#:   // 手写递归
来源：http://dali.dashuyun.cn/Article/details/gt2lfmxvbue.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.yanxiufei.cn/Article/details/gt2xtdkqrgd.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.meibo888.top/Article/details/gt2wcsedecd.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.c1oappe.top/Article/details/gt2keicegey.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gt2zbrtoyzo.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.fzhhl.top/Article/details/gt2rdutskuu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zycfv.cn/Article/details/gt2uduxottg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.bjfxy.top/Article/details/gt2qeemwegd.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.ivvv.top/Article/details/gt2rhqoffhf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.havefunace.top/Article/details/gt2ujonuavd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2vgdfcsvh.html

O. 并发与异步
来源：http://dali.ybcxt.top/Article/details/gt2lxofroxf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ksflwcyo.html

[O01] 启动一个线程
来源：http://dali.yvedp.cn/Article/details/gt2ydzcckqc.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.fzhhl.top/Article/details/gt2lzvbcgdp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.cdnleiting.top/Article/details/gt2utfmuzwr.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.mhx1999.top/Article/details/gt2xnatwfec.html

TS:   // 同 JS
来源：http://dali.ppjwa.cn/Article/details/gt2sjttseih.html

Java: new Thread(() -> f()).start()
来源：http://dali.c1oappe.top/Article/details/gt2eeamnagv.html

Go:   go f()
来源：http://dali.yangfankeji.com/Article/details/gt2ykraavwx.html

Ruby: Thread.new { f }
来源：http://dali.wangdashe.top/Article/details/gt2tvhawnbd.html

C#:   Task.Run(() => F());
来源：http://dali.iojbl.cn/Article/details/gt2nextrluh.html

[O02] 使用线程池
来源：http://dali.dashuyun.cn/Article/details/gt2qynpnvpi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gt2tigmqmuc.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yj20258.top/Article/details/gt2vuipndog.html

JS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2yemkvnko.html

TS:   // worker_threads 线程池
来源：http://dali.shzxlz.cn/Article/details/gt2pieqwdph.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cdnleiting.top/Article/details/gt2vjzmplqx.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.hysaishi.cn/Article/details/gt2vpxjlkuv.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.vqdsnc.cn/Article/details/gt2pyrxayld.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.pengpengdd.cyou/Article/details/gt2vpuprcov.html

[O03] 加锁保护共享数据
来源：http://dali.hongshengwenyu.top/Article/details/gt2yjwocpoq.html

Py:   with lock: shared += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tnodipox.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.guannengcc.top/Article/details/gt2tqqxgwcx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.iojbl.cn/Article/details/gt2edrmnlkb.html

TS:   // 同 JS
来源：http://dali.c1oappe.top/Article/details/gt2xohaylvf.html

Java: synchronized (this) { shared++; }
来源：http://dali.0kj1m.cn/Article/details/gt2tlebulfv.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.hywenlv.cn/Article/details/gt2vgobzdsg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jrljzclz.html

C#:   lock (gate) { shared++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2lebgezbk.html

[O04] 定义异步函数并等待
来源：http://dali.c1oappe.top/Article/details/gt2pausfmcw.html

Py:   async def f():⏎    await g()
来源：http://dali.sysykeji.top/Article/details/gt2ruxsdtwp.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yongpay.top/Article/details/gt2njiqxkof.html

JS:   async function f() { await g(); }
来源：http://dali.sysykeji.top/Article/details/gt2dvjpnhka.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.svipenyu.cn/Article/details/gt2llzkkmtn.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.meibo888.top/Article/details/gt2ivnmbpzc.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.xuetiantiany.cn/Article/details/gt2eoneqjfz.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.ivvv.top/Article/details/gt2lrnmqdlm.html

C#:   async Task F() { await G(); }
来源：http://dali.xinyue.icu/Article/details/gt2itpxocms.html

[O05] 并发执行并等待全部完成
来源：http://dali.yvedp.cn/Article/details/gt2lvcjgrcr.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2flkvbchx.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.ehwqpu.com/Article/details/gt2cqtoldru.html

JS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2jjeupiiq.html

TS:   await Promise.all(tasks)
来源：http://dali.9152youxi.cn/Article/details/gt2addjydee.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.cdnleiting.top/Article/details/gt2hazqszbp.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.zhoulong.xyz/Article/details/gt2ouptdtop.html

Ruby: threads.map(&:join)
来源：http://dali.zhixingplan.top/Article/details/gt2zvvilinr.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.zhoulong.xyz/Article/details/gt2uooskaya.html

[O06] 使用进程池
来源：http://dali.haohaochexian.top/Article/details/gt2kucsjrtn.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.xziqi.cn/Article/details/gt2kjwixkkx.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.aibaodan.cn/Article/details/gt2dxunsrpf.html

JS:   // child_process / cluster 模块
来源：http://dali.zhongyouzk.top/Article/details/gt2reklhwwm.html

TS:   // child_process / cluster 模块
来源：http://dali.sysykeji.top/Article/details/gt2hobziwtq.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gt2mdgevcrz.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yanxiufei.cn/Article/details/gt2iqfuwpcz.html

Ruby: // fork 块
来源：http://dali.cqqwz.cn/Article/details/gt2ysmblara.html

C#:   Parallel.For
来源：http://dali.bjfxy.top/Article/details/gt2wghkygss.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ttmowuwf.html

P. 常用工具函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2qqewadmo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2fdtkypac.html

[P01] 生成 UUID
来源：http://dali.nwbrower.top/Article/details/gt2dxffcchf.html

Py:   str(uuid.uuid4())
来源：http://dali.sweek.top/Article/details/gt2snqgirtm.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.nwbrower.top/Article/details/gt2tzskbqhx.html

JS:   crypto.randomUUID()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymgpywov.html

TS:   crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gt2drpxkwll.html

Java: UUID.randomUUID().toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2wrjaqpju.html

Go:   // 用 github.com/google/uuid
来源：http://dali.yvedp.cn/Article/details/gt2hvhsbvbf.html

Ruby: SecureRandom.uuid
来源：http://dali.havefunace.top/Article/details/gt2zinyoqor.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.nwbrower.top/Article/details/gt2jnewcvjs.html

[P02] MD5 / SHA256 摘要
来源：http://dali.dianchejie.cn/Article/details/gt2qvgqlojb.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.yueranfly.top/Article/details/gt2daqbiywo.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aoawzsvd.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.shuidangran.top/Article/details/gt2nifxoaga.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.shuidangran.top/Article/details/gt2ivpoezyn.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.yongpay.top/Article/details/gt2zpnfssao.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.sxryk.cn/Article/details/gt2wkzszzlz.html


<!-- 参考信息 -->