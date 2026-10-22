代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jyoumei.cn/Article/details/gt2ktceambw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.hfpthk.cn/Article/details/gt2rizegfrc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.shangyingyoupin.top/Article/details/gt2skisenld.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yanxiufei.cn/Article/details/gt2vcyeyaky.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jqgfzy.top/Article/details/gt2qxppnsxs.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.havefunace.top/Article/details/gt2tszneisw.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yvedp.cn/Article/details/gt2bciilzyn.html

[L06] 解析响应为 JSON
来源：http://dali.yuanzhike.top/Article/details/gt2njdctdqv.html

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gt2ldyrwegr.html

PHP:  json_decode($body, true);
来源：http://dali.hnxiangtu.top/Article/details/gt2ppdoxtua.html

JS:   await resp.json()
来源：http://dali.gotoacloud.top/Article/details/gt2qqagvbqn.html

TS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gt2yvkhoail.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tian-w.cn/Article/details/gt2lczntytt.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xinyue.icu/Article/details/gt2rpmwmlzf.html

Ruby: JSON.parse(resp.body)
来源：http://dali.sweek.top/Article/details/gt2zmabwcxu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.daxiang520.top/Article/details/gt2oztupmfn.html

[L07] 处理 HTTP 状态码
来源：http://dali.hysaishi.cn/Article/details/gt2olijneyu.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cashguo.top/Article/details/gt2qrttndvi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.cqqwz.cn/Article/details/gt2pnmkgagi.html

JS:   resp.ok;  resp.status
来源：http://dali.shangyingyoupin.top/Article/details/gt2mbgqvlgg.html

TS:   resp.ok;  resp.status
来源：http://dali.vqdsnc.cn/Article/details/gt2fnwqobyz.html

Java: resp.statusCode()
来源：http://dali.sxryk.cn/Article/details/gt2yirypjav.html

Go:   resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gt2ojnncvwp.html

Ruby: resp.code.to_i
来源：http://dali.wangshuangyany.cn/Article/details/gt2jenhskns.html

C#:   (int)resp.StatusCode
来源：http://dali.daxiang520.top/Article/details/gt2hrinoerb.html

[L08] 并发请求多个地址
来源：http://dali.nanxuanxn.top/Article/details/gt2pnzebbcw.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srotvfzp.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gt2wvzklnih.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yuanzhike.top/Article/details/gt2lxuzdynd.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gt2ryisdfvi.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.snrcjt.cn/Article/details/gt2zfoydnwo.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yueranfly.top/Article/details/gt2qswnhxct.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.cucudq.cn/Article/details/gt2gufevfcb.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.gzhubu.top/Article/details/gt2sqysokjl.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2mviggcub.html

M. 命令行 / 进程 / 环境
来源：http://dali.yuanzhike.top/Article/details/gt2lltswvjb.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2bietfmtr.html

[M01] 读取命令行参数
来源：http://dali.aizwys.cn/Article/details/gt2yhjdrmja.html

Py:   sys.argv[1:]
来源：http://dali.meibo888.top/Article/details/gt2pkxwthvd.html

PHP:  $argv;  $argc;
来源：http://dali.chenzaomai.com/Article/details/gt2lufwzokq.html

JS:   process.argv.slice(2)
来源：http://dali.iojbl.cn/Article/details/gt2gukohwpf.html

TS:   process.argv.slice(2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfcxvsbu.html

Java: args 数组（main 方法参数）
来源：http://dali.chenzaomai.com/Article/details/gt2hpskmomr.html

Go:   os.Args[1:]
来源：http://dali.pycfn.com/Article/details/gt2hkdsazfk.html

Ruby: ARGV
来源：http://dali.xinyue.icu/Article/details/gt2ovlxbwip.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hnqzz.top/Article/details/gt2frfgaunm.html

[M02] 读取环境变量
来源：http://dali.hnqzz.top/Article/details/gt2iyjaifcx.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2fanostvi.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.chenjidiqi.icu/Article/details/gt2oaugxajn.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gt2cwexslga.html

TS:   process.env.HOME
来源：http://dali.fzhhl.top/Article/details/gt2omfaaksh.html

Java: System.getenv("HOME")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bhpbdlnr.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.andypj.xyz/Article/details/gt2zzwlwsle.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gt2otlopdkv.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zycfv.cn/Article/details/gt2mwcuyfvn.html

[M03] 执行外部命令
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwoeudmv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2zbhpabrc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xziqi.cn/Article/details/gt2ltavovsw.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jianghu66.top/Article/details/gt2wjninmhi.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gt2kxomiskn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.ppjwa.cn/Article/details/gt2tjzxzudf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aizwys.cn/Article/details/gt2uajbkqct.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yvedp.cn/Article/details/gt2cupvtvmt.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dpgfgott.html

[M04] 获取当前工作目录
来源：http://dali.fengsongda.top/Article/details/gt2yahacumf.html

Py:   os.getcwd()
来源：http://dali.snrcjt.cn/Article/details/gt2yfelefhb.html

PHP:  getcwd();
来源：http://dali.shzxlz.cn/Article/details/gt2aobouoak.html

JS:   process.cwd()
来源：http://dali.nanxinkj.top/Article/details/gt2aknxtkxy.html

TS:   process.cwd()
来源：http://dali.ydzc1.top/Article/details/gt2ibfwnste.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.316326.xyz/Article/details/gt2rqyejxoq.html

Go:   os.Getwd()
来源：http://dali.cheryme.top/Article/details/gt2mpfrppbd.html

Ruby: Dir.pwd
来源：http://dali.cashguo.top/Article/details/gt2kllpwzuv.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.aizwys.cn/Article/details/gt2dqakvxfz.html

[M05] 设置退出码
来源：http://dali.fzhhl.top/Article/details/gt2lpvwqmvs.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2fjhqtpdf.html

PHP:  exit(1);
来源：http://dali.tian-w.cn/Article/details/gt2mhwphybi.html

JS:   process.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2uiwrrxdw.html

TS:   process.exit(1)
来源：http://dali.aizwys.cn/Article/details/gt2ivxivlma.html

Java: System.exit(1)
来源：http://dali.xuanzx.com/Article/details/gt2qiefwmom.html

Go:   os.Exit(1)
来源：http://dali.316326.xyz/Article/details/gt2lmuieyir.html

Ruby: exit 1
来源：http://dali.hfpthk.cn/Article/details/gt2ztooozcn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gotoacloud.top/Article/details/gt2ttnalsgf.html

[M06] 向标准错误输出
来源：http://dali.cucudq.cn/Article/details/gt2xnquzfkc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gt2vjpaihpf.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sysykeji.top/Article/details/gt2aenezmgu.html

JS:   console.error("err")
来源：http://dali.mhx1999.top/Article/details/gt2uoabunjj.html

TS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gt2nqcqrjvb.html

Java: System.err.println("err")
来源：http://dali.dianchejie.cn/Article/details/gt2odcnodny.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvwgnrju.html

Ruby: warn "err"
来源：http://dali.daxiang520.top/Article/details/gt2mtcbiboq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.cqqwz.cn/Article/details/gt2glguvjhv.html

[M07] 判断是否为主入口
来源：http://dali.pycfn.com/Article/details/gt2mxysdtbe.html

Py:   if __name__ == "__main__":
来源：http://dali.hammf.cn/Article/details/gt2ucbtznka.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.fzhhl.top/Article/details/gt2aimhmusr.html

JS:   require.main === module
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hhwfosdd.html

TS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ryzegocc.html

Java: public static void main(String[] args)
来源：http://dali.hysaishi.cn/Article/details/gt2ltcxlmut.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gt2zjqpgvca.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yonumen.top/Article/details/gt2setsgkch.html

C#:   static void Main(string[] args)
来源：http://dali.hfpthk.cn/Article/details/gt2ltrnovrr.html

[M08] 获取系统与运行时信息
来源：http://dali.zhengqikj.top/Article/details/gt2wafcardi.html

Py:   platform.system();  platform.python_version()
来源：http://dali.xziqi.cn/Article/details/gt2wtjmlchm.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.tanke756.top/Article/details/gt2gaktdaza.html

JS:   process.platform;  process.version
来源：http://dali.316326.xyz/Article/details/gt2tihzuyed.html

TS:   process.platform;  process.version
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkrkrfhp.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.sxryk.cn/Article/details/gt2neevvhff.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.zycfv.cn/Article/details/gt2xtgrqota.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hywenlv.cn/Article/details/gt2jfiapwvm.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj20258.top/Article/details/gt2wvennnmq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2lmolxukz.html

N. 数据结构与算法
来源：http://dali.9152youxi.cn/Article/details/gt2blzqorrt.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2gxpssjdd.html

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gt2ltxrmfqi.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gt2ifvomptr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.dashuyun.cn/Article/details/gt2chhtcuop.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.quarkkingdee.top/Article/details/gt2domnzesg.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.yonumen.top/Article/details/gt2oborrmni.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ynmwcvhv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cheryme.top/Article/details/gt2xpgddbom.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.9152youxi.cn/Article/details/gt2pwbpqltp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2btcmxjut.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yj20258888.top/Article/details/gt2qkyphkwf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gt2nxrxazcq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hammf.cn/Article/details/gt2yjcwpnvo.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xinyue.icu/Article/details/gt2zeetbzkk.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gt2ntjcxrsp.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eleyintn.html

Go:   slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gt2tacrphaa.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gt2wxmxpzoh.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.havefunace.top/Article/details/gt2phizaxyd.html

[N03] 快速排序（分治示例）
来源：http://dali.wangdashe.top/Article/details/gt2gjksqanl.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hysaishi.cn/Article/details/gt2etoicogf.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gt2skejomxh.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gt2ljzkcpcg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hfpthk.cn/Article/details/gt2otsicspw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.0kj1m.cn/Article/details/gt2tmasohqn.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj20258888.top/Article/details/gt2tadxlwke.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.ydzc1.top/Article/details/gt2mpwnkwle.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yvedp.cn/Article/details/gt2incjqbqc.html

[N04] 斐波那契数列
来源：http://dali.yj20258.top/Article/details/gt2gwjrocar.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gt2jyfoavlu.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2ovsrgydu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gt2xzwmufxe.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gt2tzvgjllt.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hysaishi.cn/Article/details/gt2tfqgqttc.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.vqdsnc.cn/Article/details/gt2pbvnbdoy.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.316326.xyz/Article/details/gt2rexxewan.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gt2qvflfxeu.html

[N05] 最大公约数
来源：http://dali.gogol.net.cn/Article/details/gt2remdgxrk.html

Py:   math.gcd(a, b)
来源：http://dali.yuxming.cn/Article/details/gt2cvxblelg.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndcigfco.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yj202588.top/Article/details/gt2vcatpetl.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gt2zdnetngl.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.zycfv.cn/Article/details/gt2ezgdlewu.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.gogol.net.cn/Article/details/gt2gpcmbwei.html

Ruby: a.gcd(b)
来源：http://dali.yuanzhike.top/Article/details/gt2omrvkcqo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lzjfnzch.html

[N06] 判断回文字符串
来源：http://dali.yongpay.top/Article/details/gt2jkwqeirx.html

Py:   s == s[::-1]
来源：http://dali.xuanzx.com/Article/details/gt2rsraliqe.html

PHP:  $s === strrev($s);
来源：http://dali.jqgfzy.top/Article/details/gt2tkurbyds.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gt2dnynmenv.html

TS:   s === [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2nxbikzlb.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gt2rotbzcco.html

Go:   // 双指针从两端比较
来源：http://dali.jqgfzy.top/Article/details/gt2yskcayfj.html

Ruby: s == s.reverse
来源：http://dali.yuxming.cn/Article/details/gt2hbwesshd.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.gotoacloud.top/Article/details/gt2skaxfvas.html

[N07] 两数之和（返回下标）
来源：http://dali.dashuyun.cn/Article/details/gt2yxvwjcvb.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gogol.net.cn/Article/details/gt2gpijpece.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvfgwvlj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.xinyue.icu/Article/details/gt2mcfitiqf.html

TS:   // 手写 Map<string, number>
来源：http://dali.haohaochexian.top/Article/details/gt2tfvjdfbp.html

Java: // 手写 HashMap
来源：http://dali.chenzaomai.com/Article/details/gt2pmirmxsk.html

Go:   // 手写 map[int]int
来源：http://dali.9152youxi.cn/Article/details/gt2gdkwxoaq.html

Ruby: // 手写 Hash
来源：http://dali.cdnleiting.top/Article/details/gt2dhkbxkij.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.zycfv.cn/Article/details/gt2qksdnmov.html

[N08] 生成全排列
来源：http://dali.zycfv.cn/Article/details/gt2paptmssw.html

Py:   itertools.permutations(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmjfmogw.html

PHP:  // 手写递归交换
来源：http://dali.cqqwz.cn/Article/details/gt2kxgutwlz.html

JS:   // 手写回溯递归
来源：http://dali.jyoumei.cn/Article/details/gt2pvtjckea.html

TS:   // 手写回溯递归
来源：http://dali.birdmap.top/Article/details/gt2xsylmcen.html

Java: // 手写回溯递归
来源：http://dali.shangyingyoupin.top/Article/details/gt2ezizpyoh.html

Go:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2ygfadisd.html

Ruby: arr.permutation.to_a
来源：http://dali.vqdsnc.cn/Article/details/gt2gujwcaul.html

C#:   // 手写回溯递归
来源：http://dali.xylfe.cn/Article/details/gt2mrspvipm.html

[N09] 栈与队列
来源：http://dali.yuanzhike.top/Article/details/gt2chyljxgc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2diqqatkh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.yueranfly.top/Article/details/gt2ythheodx.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gt2cfoxwfpc.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cheryme.top/Article/details/gt2agtnkyqw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yueranfly.top/Article/details/gt2ekivynxv.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.wangdashe.top/Article/details/gt2nuvacemr.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2wzpmfogx.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.haohaochexian.top/Article/details/gt2xdqlbvgp.html

[N10] 链表节点定义
来源：http://dali.hammf.cn/Article/details/gt2hphqtenl.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shuidangran.top/Article/details/gt2gpzxijtz.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj202588.top/Article/details/gt2cwsxvodu.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yonumen.top/Article/details/gt2uagxgnfx.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.meibo888.top/Article/details/gt2whinezax.html

Java: class Node { int v; Node next; }
来源：http://dali.yvedp.cn/Article/details/gt2nfdjavia.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cxtrnfwi.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tanke756.top/Article/details/gt2avtesexh.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tianlin.xyz/Article/details/gt2ekalcujd.html

[N11] 二叉树中序遍历
来源：http://dali.redwolf501.top/Article/details/gt2lbfllihc.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhiwuduotai.top/Article/details/gt2apbyystl.html

PHP:  // 手写递归函数
来源：http://dali.yj202588.top/Article/details/gt2omfaleqj.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2zijxshok.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cheryme.top/Article/details/gt2vfiyuqfj.html

Java: // 手写递归
来源：http://dali.yueranfly.top/Article/details/gt2rqcdjutr.html

Go:   // 手写递归
来源：http://dali.fzhhl.top/Article/details/gt2dklqwsrg.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hywenlv.cn/Article/details/gt2fxjsipld.html

C#:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gt2drchqgpk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.wangshuangyany.cn/Article/details/gt2kffbqggu.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.ybcxt.top/Article/details/gt2qgjbomqm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfizhix.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zycfv.cn/Article/details/gt2ggdbmvby.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gt2tfgrakqn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sysykeji.top/Article/details/gt2itccfwda.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txqoojrf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.mhx1999.top/Article/details/gt2aqncxbjy.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhixingplan.top/Article/details/gt2oimmroej.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ewxbremt.html

O. 并发与异步
来源：http://dali.guowangkeji.top/Article/details/gt2fhnzsgdo.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2wcsnenof.html

[O01] 启动一个线程
来源：http://dali.jyoumei.cn/Article/details/gt2dtmctwaw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.hnxiangtu.top/Article/details/gt2phlddbhv.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.gogol.net.cn/Article/details/gt2wcbailty.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.smart0.xyz/Article/details/gt2gekuqqlv.html

TS:   // 同 JS
来源：http://dali.yj20258888.top/Article/details/gt2orcdxliy.html

Java: new Thread(() -> f()).start()
来源：http://dali.yuanzhike.top/Article/details/gt2izjlhrav.html

Go:   go f()
来源：http://dali.jinqigufen.top/Article/details/gt2lrndjhsq.html

Ruby: Thread.new { f }
来源：http://dali.yonumen.top/Article/details/gt2egjaenma.html

C#:   Task.Run(() => F());
来源：http://dali.hammf.cn/Article/details/gt2ipxuffdm.html

[O02] 使用线程池
来源：http://dali.jlsjyb.cn/Article/details/gt2gmtxoouu.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.svipenyu.cn/Article/details/gt2iguvnnil.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yvedp.cn/Article/details/gt2wniddunl.html

JS:   // worker_threads 线程池
来源：http://dali.smart0.xyz/Article/details/gt2lhyasiuq.html

TS:   // worker_threads 线程池
来源：http://dali.redwolf501.top/Article/details/gt2kfpozpdf.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.dianchejie.cn/Article/details/gt2hixtlbtw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.aibaodan.cn/Article/details/gt2okgpqsvz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shzxlz.cn/Article/details/gt2yvsvltav.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.hnxiangtu.top/Article/details/gt2tdmxwdrj.html

[O03] 加锁保护共享数据
来源：http://dali.dianchejie.cn/Article/details/gt2ifjpneyg.html

Py:   with lock: shared += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2thoyehfy.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.shangyingyoupin.top/Article/details/gt2wtbhwumz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gt2slyuswhw.html

TS:   // 同 JS
来源：http://dali.jlsjyb.cn/Article/details/gt2jqviyves.html

Java: synchronized (this) { shared++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2seoiaywa.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.birdmap.top/Article/details/gt2autkpmdx.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nbzrgvml.html

C#:   lock (gate) { shared++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iiwnzvwi.html

[O04] 定义异步函数并等待
来源：http://dali.cucudq.cn/Article/details/gt2wvxdzpwx.html

Py:   async def f():⏎    await g()
来源：http://dali.hnxiangtu.top/Article/details/gt2qjaibprm.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.feifeiyinyue.top/Article/details/gt2fsmzzwtk.html

JS:   async function f() { await g(); }
来源：http://dali.yuanzhike.top/Article/details/gt2xraugavn.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.chenzaomai.com/Article/details/gt2hgatfaog.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.xinyue.icu/Article/details/gt2tuumomtt.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.feifeiyinyue.top/Article/details/gt2nptzkhpy.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.zhoulong.xyz/Article/details/gt2rfsdamhr.html

C#:   async Task F() { await G(); }
来源：http://dali.zhengqikj.top/Article/details/gt2wjwzcqtq.html

[O05] 并发执行并等待全部完成
来源：http://dali.jqgfzy.top/Article/details/gt2txcvokba.html

Py:   asyncio.gather(*tasks)
来源：http://dali.ppjwa.cn/Article/details/gt2hygkugzi.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.daria6918.cn/Article/details/gt2aqmvmvjc.html

JS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gt2ydylspaa.html

TS:   await Promise.all(tasks)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcuznoos.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.sweek.top/Article/details/gt2xgjmlipd.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjsalfcu.html

Ruby: threads.map(&:join)
来源：http://dali.dashuyun.cn/Article/details/gt2ybqvkcgb.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.jlsjyb.cn/Article/details/gt2hycdsbrr.html

[O06] 使用进程池
来源：http://dali.iojbl.cn/Article/details/gt2pgjhttwh.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yonumen.top/Article/details/gt2fqhnlhcb.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.9152youxi.cn/Article/details/gt2aencdxls.html

JS:   // child_process / cluster 模块
来源：http://dali.birdmap.top/Article/details/gt2ladfaais.html

TS:   // child_process / cluster 模块
来源：http://dali.gogol.net.cn/Article/details/gt2bvvffakw.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.yanxiufei.cn/Article/details/gt2crromewg.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.vqdsnc.cn/Article/details/gt2suurwixx.html

Ruby: // fork 块
来源：http://dali.mhx1999.top/Article/details/gt2ezyhqsrh.html

C#:   Parallel.For
来源：http://dali.shangyingyoupin.top/Article/details/gt2pwtuzwxs.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2cjqxkorn.html

P. 常用工具函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2lrptkwxx.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2oyyknnup.html

[P01] 生成 UUID
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqwyjqql.html

Py:   str(uuid.uuid4())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvdivgdr.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2conjkyvp.html

JS:   crypto.randomUUID()
来源：http://dali.zhixingplan.top/Article/details/gt2gilhcssr.html

TS:   crypto.randomUUID()
来源：http://dali.zhongyouzk.top/Article/details/gt2uexoezir.html

Java: UUID.randomUUID().toString()
来源：http://dali.svipenyu.cn/Article/details/gt2jybohpmo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.vqdsnc.cn/Article/details/gt2zmnnlzjv.html

Ruby: SecureRandom.uuid
来源：http://dali.aibaodan.cn/Article/details/gt2rziboioa.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.316326.xyz/Article/details/gt2dbiejgbw.html

[P02] MD5 / SHA256 摘要
来源：http://dali.andypj.xyz/Article/details/gt2dclsddlo.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxskpojd.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.nanxinkj.top/Article/details/gt2kdbstamh.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mmmifmtg.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.hnqzz.top/Article/details/gt2exouzcul.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.dianchejie.cn/Article/details/gt2ammiqkpu.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.kuanghao11.cn/Article/details/gt2emxmvobn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vwerhpbj.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.meibo888.top/Article/details/gt2wgukhhyk.html

[P03] 生成短随机字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2khjxgwmi.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yanxiufei.cn/Article/details/gt2tuiisjqy.html


<!-- 参考信息 -->