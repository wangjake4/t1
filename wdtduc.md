代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.daria6918.cn/Article/details/gt2zklpjvbt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cucudq.cn/Article/details/gt2zrfntgff.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.fengsongda.top/Article/details/gt2gqteosih.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yonumen.top/Article/details/gt2pwjpiara.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yvedp.cn/Article/details/gt2kzertefq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.sysykeji.top/Article/details/gt2hgilmlch.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2oxpxsled.html

[L06] 解析响应为 JSON
来源：http://dali.ivvv.top/Article/details/gt2iijxzhkd.html

Py:   resp.json()
来源：http://dali.jlsjyb.cn/Article/details/gt2ywsvbvbv.html

PHP:  json_decode($body, true);
来源：http://dali.pycfn.com/Article/details/gt2nkqrgfvg.html

JS:   await resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2qtgzpxsn.html

TS:   await resp.json()
来源：http://dali.9152youxi.cn/Article/details/gt2vjxpgwnx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.gzhubu.top/Article/details/gt2bmfvudmq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykjrzncw.html

Ruby: JSON.parse(resp.body)
来源：http://dali.snrcjt.cn/Article/details/gt2etbikyxs.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.havefunace.top/Article/details/gt2puuozahp.html

[L07] 处理 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gt2lsgsrhfs.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cqqwz.cn/Article/details/gt2cejmnwan.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.9152youxi.cn/Article/details/gt2ngjdbkac.html

JS:   resp.ok;  resp.status
来源：http://dali.xziqi.cn/Article/details/gt2txcmgiee.html

TS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gt2ydchmqxn.html

Java: resp.statusCode()
来源：http://dali.dianchejie.cn/Article/details/gt2ktrfsrud.html

Go:   resp.StatusCode
来源：http://dali.gaohongyu789.top/Article/details/gt2czjprppx.html

Ruby: resp.code.to_i
来源：http://dali.nanxuanxn.top/Article/details/gt2fpvrqdpn.html

C#:   (int)resp.StatusCode
来源：http://dali.pycfn.com/Article/details/gt2hychwxzg.html

[L08] 并发请求多个地址
来源：http://dali.quarkkingdee.top/Article/details/gt2wsasmahk.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.chenjidiqi.icu/Article/details/gt2kfbhhdqr.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnxiangtu.top/Article/details/gt2katzngaj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gt2auautrdm.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tianlin.xyz/Article/details/gt2trljrxkl.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hfpthk.cn/Article/details/gt2zetflevp.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vswuzxtr.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.316326.xyz/Article/details/gt2uiidxnya.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gt2wbmwdvno.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2riygnqdr.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gt2hdsiqyuo.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ojlmhqcz.html

[M01] 读取命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gt2tdnfqkcb.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2wqsrtsec.html

PHP:  $argv;  $argc;
来源：http://dali.andypj.xyz/Article/details/gt2rsspopjw.html

JS:   process.argv.slice(2)
来源：http://dali.sxryk.cn/Article/details/gt2owloplsj.html

TS:   process.argv.slice(2)
来源：http://dali.nanxuanxn.top/Article/details/gt2bptfrmjc.html

Java: args 数组（main 方法参数）
来源：http://dali.jianghu66.top/Article/details/gt2wogifcry.html

Go:   os.Args[1:]
来源：http://dali.hfpthk.cn/Article/details/gt2aplggddj.html

Ruby: ARGV
来源：http://dali.zhixingplan.top/Article/details/gt2ojbbnyok.html

C#:   args 数组（Main 方法参数）
来源：http://dali.tian-w.cn/Article/details/gt2jjwglbru.html

[M02] 读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gt2zcxqvoqh.html

Py:   os.environ.get("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2lvnurils.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gt2gawvkjfk.html

JS:   process.env.HOME
来源：http://dali.hfpthk.cn/Article/details/gt2raewqvcg.html

TS:   process.env.HOME
来源：http://dali.tanke756.top/Article/details/gt2ljcckmnj.html

Java: System.getenv("HOME")
来源：http://dali.jinqigufen.top/Article/details/gt2ufddbnxw.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.tanke756.top/Article/details/gt2pcwakypq.html

Ruby: ENV["HOME"]
来源：http://dali.9152youxi.cn/Article/details/gt2jxnyolzu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2gqrgcsui.html

[M03] 执行外部命令
来源：http://dali.c1oappe.top/Article/details/gt2eefqhqvg.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.0kj1m.cn/Article/details/gt2zzeiazrv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.tianlin.xyz/Article/details/gt2wxrgnigz.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gt2coumvryj.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gt2qnmokony.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jcpuiskj.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.kuanghao11.cn/Article/details/gt2ggbhrkpm.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.hnqzz.top/Article/details/gt2gtlrncce.html

C#:   Process.Start("ls", "-l");
来源：http://dali.ppjwa.cn/Article/details/gt2icydsheq.html

[M04] 获取当前工作目录
来源：http://dali.yangfankeji.com/Article/details/gt2ydlvmdrz.html

Py:   os.getcwd()
来源：http://dali.vqdsnc.cn/Article/details/gt2zatcflhv.html

PHP:  getcwd();
来源：http://dali.birdmap.top/Article/details/gt2prpteuzd.html

JS:   process.cwd()
来源：http://dali.yongpay.top/Article/details/gt2xjsodufc.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gt2owwzpghu.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gt2nfsvkmdk.html

Go:   os.Getwd()
来源：http://dali.fengsongda.top/Article/details/gt2koczozeu.html

Ruby: Dir.pwd
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iwouiljq.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.shzxlz.cn/Article/details/gt2eeskougk.html

[M05] 设置退出码
来源：http://dali.zycfv.cn/Article/details/gt2pnsrpgli.html

Py:   sys.exit(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2sjgrmprf.html

PHP:  exit(1);
来源：http://dali.birdmap.top/Article/details/gt2kbnkkosa.html

JS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2gyufsgao.html

TS:   process.exit(1)
来源：http://dali.zhongyouzk.top/Article/details/gt2tabluplo.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2ovmwfdbe.html

Go:   os.Exit(1)
来源：http://dali.yj20258.top/Article/details/gt2ftuvykre.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gt2muiwbjve.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.daxiang520.top/Article/details/gt2lbqxyctl.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gt2hgiaxyuv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xliyodzi.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.chenzaomai.com/Article/details/gt2taapmkrh.html

JS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ierzfkmn.html

TS:   console.error("err")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kxcisvbe.html

Java: System.err.println("err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2baglrkte.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2piericfl.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gt2jyikkigb.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.meibo888.top/Article/details/gt2gwqjzqrw.html

[M07] 判断是否为主入口
来源：http://dali.yuxming.cn/Article/details/gt2khbfdyxi.html

Py:   if __name__ == "__main__":
来源：http://dali.ehwqpu.com/Article/details/gt2iaiixibi.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.wangdashe.top/Article/details/gt2bwsiswqj.html

JS:   require.main === module
来源：http://dali.hywenlv.cn/Article/details/gt2olbvqndx.html

TS:   require.main === module
来源：http://dali.jqgufenzy.top/Article/details/gt2ujjgiurn.html

Java: public static void main(String[] args)
来源：http://dali.yanxiufei.cn/Article/details/gt2fegcogze.html

Go:   func main()
来源：http://dali.chenjidiqi.icu/Article/details/gt2tytkbtho.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.xylfe.cn/Article/details/gt2iqrajthh.html

C#:   static void Main(string[] args)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oektmxht.html

[M08] 获取系统与运行时信息
来源：http://dali.chenlongwang.top/Article/details/gt2cidusoyy.html

Py:   platform.system();  platform.python_version()
来源：http://dali.guowangkeji.top/Article/details/gt2trpvwqja.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.sufxvd.cn/Article/details/gt2nqyggjgh.html

JS:   process.platform;  process.version
来源：http://dali.hysaishi.cn/Article/details/gt2noetttie.html

TS:   process.platform;  process.version
来源：http://dali.yangfankeji.com/Article/details/gt2mqapafil.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.aizwys.cn/Article/details/gt2urkgcgpo.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.aibaodan.cn/Article/details/gt2tdlsauos.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigufen.top/Article/details/gt2rmnyttta.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.zhoulong.xyz/Article/details/gt2yuotxbpf.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2edaabidv.html

N. 数据结构与算法
来源：http://dali.svipenyu.cn/Article/details/gt2kroalczr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2sspamqmv.html

[N01] 二分查找（有序数组）
来源：http://dali.iojbl.cn/Article/details/gt2gtdectve.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2ukbwamlj.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.nwbrower.top/Article/details/gt2forfmntw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2wmxlsoge.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.chenlongwang.top/Article/details/gt2chdsoqgi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2ovzszqcm.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2lnzvlltc.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.quarkkingdee.top/Article/details/gt2zmzsoobh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2rpwtazqi.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cashguo.top/Article/details/gt2tbsljwlh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gt2srjvdfwi.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jqgfzy.top/Article/details/gt2jyafhkok.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gt2grwckquu.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gt2tsgofuju.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2deuqskcs.html

Go:   slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gt2higaziwc.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gt2ylyuvqoc.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jiagoushi.top/Article/details/gt2qumkdmdu.html

[N03] 快速排序（分治示例）
来源：http://dali.mhx1999.top/Article/details/gt2wcfrkxif.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.xuanzx.com/Article/details/gt2zqrnudss.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eworunlf.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gt2ixbgmebp.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hammf.cn/Article/details/gt2ichjvtrq.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2danbxhog.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.9152youxi.cn/Article/details/gt2iyuprdlb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.jinqigufen.top/Article/details/gt2wgdosplk.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.zhongyouzk.top/Article/details/gt2xekzckgg.html

[N04] 斐波那契数列
来源：http://dali.aizwys.cn/Article/details/gt2pqtaolmh.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwuxgsad.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jcybvmhn.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.316326.xyz/Article/details/gt2hvmazzbr.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jinqigufen.top/Article/details/gt2pmoylvfp.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xuanzx.com/Article/details/gt2gvpmgycf.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jlsjyb.cn/Article/details/gt2uafrvjkm.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zntglheq.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yj20258888.top/Article/details/gt2lyagwdun.html

[N05] 最大公约数
来源：http://dali.yueranfly.top/Article/details/gt2cmjtwdnh.html

Py:   math.gcd(a, b)
来源：http://dali.aizwys.cn/Article/details/gt2lzaexxpt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2puhrdasn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gt2pmlmwlel.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tian-w.cn/Article/details/gt2sexkzdqm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.kuanghao11.cn/Article/details/gt2nwstvgfb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.daria6918.cn/Article/details/gt2tfntkdfc.html

Ruby: a.gcd(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2ttsrgtdx.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.aibaodan.cn/Article/details/gt2wjvsnttr.html

[N06] 判断回文字符串
来源：http://dali.chenlongwang.top/Article/details/gt2covbxwiu.html

Py:   s == s[::-1]
来源：http://dali.zhijiandao.cn/Article/details/gt2thpaqdiz.html

PHP:  $s === strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gnbwgrbn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zdqjudy.top/Article/details/gt2ektdiczw.html

TS:   s === [...s].reverse().join("")
来源：http://dali.redwolf501.top/Article/details/gt2eyumyckx.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hnxiangtu.top/Article/details/gt2dokzqwxu.html

Go:   // 双指针从两端比较
来源：http://dali.zhiwuduotai.top/Article/details/gt2gaiimpyl.html

Ruby: s == s.reverse
来源：http://dali.andypj.xyz/Article/details/gt2yrcbggrr.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.chenjidiqi.icu/Article/details/gt2xadfldut.html

[N07] 两数之和（返回下标）
来源：http://dali.zhongyouzk.top/Article/details/gt2srasvklg.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.gzhubu.top/Article/details/gt2rfsypwrt.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258.top/Article/details/gt2kvrpvgao.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shzxlz.cn/Article/details/gt2cftrvddb.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangshuangyany.cn/Article/details/gt2xmeosxsv.html

Java: // 手写 HashMap
来源：http://dali.bjfxy.top/Article/details/gt2vqfbbtxu.html

Go:   // 手写 map[int]int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2agtavunm.html

Ruby: // 手写 Hash
来源：http://dali.cqqwz.cn/Article/details/gt2ecypfpvy.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aibaodan.cn/Article/details/gt2ywgjmpjb.html

[N08] 生成全排列
来源：http://dali.birdmap.top/Article/details/gt2kbytlezb.html

Py:   itertools.permutations(arr)
来源：http://dali.xuanzx.com/Article/details/gt2skebuhng.html

PHP:  // 手写递归交换
来源：http://dali.jiagoushi.top/Article/details/gt2fotrosdy.html

JS:   // 手写回溯递归
来源：http://dali.dianchejie.cn/Article/details/gt2jypjshqp.html

TS:   // 手写回溯递归
来源：http://dali.yongpay.top/Article/details/gt2iplfqimq.html

Java: // 手写回溯递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2pziwmecu.html

Go:   // 手写回溯递归
来源：http://dali.vqdsnc.cn/Article/details/gt2qhgijvdx.html

Ruby: arr.permutation.to_a
来源：http://dali.yj20258888.top/Article/details/gt2iwrdxpim.html

C#:   // 手写回溯递归
来源：http://dali.cdnleiting.top/Article/details/gt2rnhebvfc.html

[N09] 栈与队列
来源：http://dali.hfpthk.cn/Article/details/gt2iramrihm.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.guannengcc.top/Article/details/gt2qqlqqzmc.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mesbmnbh.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ybcxt.top/Article/details/gt2pwylwlxm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yj20258888.top/Article/details/gt2cktisytd.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jyoumei.cn/Article/details/gt2vhkjwbot.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yj20258888.top/Article/details/gt2ypnhoqor.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.feifeiyinyue.top/Article/details/gt2ypprapmf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zfmtdlhd.html

[N10] 链表节点定义
来源：http://dali.cdnleiting.top/Article/details/gt2ofxjyebd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yj20258888.top/Article/details/gt2awgpsspo.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.xinyue.icu/Article/details/gt2ejdnxwuj.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgufenzy.top/Article/details/gt2drvwhvpl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rplnqozy.html

Java: class Node { int v; Node next; }
来源：http://dali.havefunace.top/Article/details/gt2hfyotcbw.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258888.top/Article/details/gt2zlybfcpf.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.shangyingyoupin.top/Article/details/gt2vvbaibku.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.chenzaomai.com/Article/details/gt2syejwiof.html

[N11] 二叉树中序遍历
来源：http://dali.nanxinkj.top/Article/details/gt2ehbhgwli.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ydzc1.top/Article/details/gt2yozgyyzc.html

PHP:  // 手写递归函数
来源：http://dali.ivvv.top/Article/details/gt2pyeqjdjo.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cdnleiting.top/Article/details/gt2mvqbyifu.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.andypj.xyz/Article/details/gt2fvljhhue.html

Java: // 手写递归
来源：http://dali.shuidangran.top/Article/details/gt2eiursgnt.html

Go:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gt2voikaxyy.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.jinqigufen.top/Article/details/gt2xkcfdjaw.html

C#:   // 手写递归
来源：http://dali.yonumen.top/Article/details/gt2ofcxqnim.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.chenlongwang.top/Article/details/gt2lojvabmw.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.316326.xyz/Article/details/gt2hchngbuf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.daria6918.cn/Article/details/gt2jazecefs.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daxiang520.top/Article/details/gt2yieswjtr.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jqgfzy.top/Article/details/gt2owfmsxda.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rcswygoo.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cheryme.top/Article/details/gt2hohnjgfx.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.nwbrower.top/Article/details/gt2sxzsnvcb.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjhaflxj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2owxzjyfs.html

O. 并发与异步
来源：http://dali.yuanzhike.top/Article/details/gt2rjsacdfw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2bjbxhedn.html

[O01] 启动一个线程
来源：http://dali.yangfankeji.com/Article/details/gt2mzskphrg.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.yj20258.top/Article/details/gt2zhzgklre.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.aibaodan.cn/Article/details/gt2anokreon.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ivvv.top/Article/details/gt2jbtorvjq.html

TS:   // 同 JS
来源：http://dali.gotoacloud.top/Article/details/gt2lhwksway.html

Java: new Thread(() -> f()).start()
来源：http://dali.birdmap.top/Article/details/gt2dlmkcswt.html

Go:   go f()
来源：http://dali.haohaochexian.top/Article/details/gt2hodhhsxy.html

Ruby: Thread.new { f }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hrbefmxt.html

C#:   Task.Run(() => F());
来源：http://dali.hysaishi.cn/Article/details/gt2dytdcmuc.html

[O02] 使用线程池
来源：http://dali.aibaodan.cn/Article/details/gt2vdbpjika.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.zdqjudy.top/Article/details/gt2xaeusvmb.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.ivvv.top/Article/details/gt2tgslkopu.html

JS:   // worker_threads 线程池
来源：http://dali.chenzaomai.com/Article/details/gt2afqpenor.html

TS:   // worker_threads 线程池
来源：http://dali.andypj.xyz/Article/details/gt2zqdxkznd.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qqgmolbw.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.ybcxt.top/Article/details/gt2ktuzjqyt.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.gaohongyu789.top/Article/details/gt2cysfaxvk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.yj20258.top/Article/details/gt2nzrfpgnc.html

[O03] 加锁保护共享数据
来源：http://dali.redwolf501.top/Article/details/gt2danmitzy.html

Py:   with lock: shared += 1
来源：http://dali.tianlin.xyz/Article/details/gt2waclvubc.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yongpay.top/Article/details/gt2jucdbuiz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hnqzz.top/Article/details/gt2fpyqhohz.html

TS:   // 同 JS
来源：http://dali.jqgfzy.top/Article/details/gt2mpxypkgt.html

Java: synchronized (this) { shared++; }
来源：http://dali.9152youxi.cn/Article/details/gt2fzaouhvr.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.dashuyun.cn/Article/details/gt2xiwmozok.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.cheryme.top/Article/details/gt2lqdktbut.html

C#:   lock (gate) { shared++; }
来源：http://dali.smart0.xyz/Article/details/gt2yjhrtnra.html

[O04] 定义异步函数并等待
来源：http://dali.zycfv.cn/Article/details/gt2etkrdpbl.html

Py:   async def f():⏎    await g()
来源：http://dali.zhiwuduotai.top/Article/details/gt2upbgjgra.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yonumen.top/Article/details/gt2ifepygpd.html

JS:   async function f() { await g(); }
来源：http://dali.tian-w.cn/Article/details/gt2luybwohf.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.ivvv.top/Article/details/gt2zmqyycim.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.tian-w.cn/Article/details/gt2gfaychci.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.yj20258888.top/Article/details/gt2izicpbmi.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.chenlongwang.top/Article/details/gt2stmgptfy.html

C#:   async Task F() { await G(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pudzgffa.html

[O05] 并发执行并等待全部完成
来源：http://dali.0kj1m.cn/Article/details/gt2srrvsdgk.html

Py:   asyncio.gather(*tasks)
来源：http://dali.chenzaomai.com/Article/details/gt2lszgehud.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.zdqjudy.top/Article/details/gt2yshftyna.html

JS:   await Promise.all(tasks)
来源：http://dali.hnqzz.top/Article/details/gt2riitmbrx.html

TS:   await Promise.all(tasks)
来源：http://dali.ppjwa.cn/Article/details/gt2rnswwhcd.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.fzhhl.top/Article/details/gt2nfwikqng.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.guowangkeji.top/Article/details/gt2qoczjzut.html

Ruby: threads.map(&:join)
来源：http://dali.316326.xyz/Article/details/gt2czwqrvjz.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qqkmsddx.html

[O06] 使用进程池
来源：http://dali.c1oappe.top/Article/details/gt2gtmwbszb.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.chenzaomai.com/Article/details/gt2qhfrlhjc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.cqqwz.cn/Article/details/gt2tollaqrn.html

JS:   // child_process / cluster 模块
来源：http://dali.shangyingyoupin.top/Article/details/gt2hljdelws.html

TS:   // child_process / cluster 模块
来源：http://dali.zhixingplan.top/Article/details/gt2vvtgowuk.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.jinqigfzy.top/Article/details/gt2inkjixvi.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.zdqjudy.top/Article/details/gt2rcakhceq.html

Ruby: // fork 块
来源：http://dali.gaohongyu789.top/Article/details/gt2pnkrbvqz.html

C#:   Parallel.For
来源：http://dali.sufxvd.cn/Article/details/gt2vkwhoznt.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2thmgdjfy.html

P. 常用工具函数
来源：http://dali.gogol.net.cn/Article/details/gt2dojwgmyr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2fogrdwph.html

[P01] 生成 UUID
来源：http://dali.zhijiandao.cn/Article/details/gt2lnxthtaa.html

Py:   str(uuid.uuid4())
来源：http://dali.9152youxi.cn/Article/details/gt2owwswppp.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.wangdashe.top/Article/details/gt2djupgvzq.html

JS:   crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gt2sirlwgts.html

TS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2qvhusunk.html

Java: UUID.randomUUID().toString()
来源：http://dali.havefunace.top/Article/details/gt2jsyamdgk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.shzxlz.cn/Article/details/gt2cmpgfiuq.html

Ruby: SecureRandom.uuid
来源：http://dali.shangyingyoupin.top/Article/details/gt2lofqzeir.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.yj20258.top/Article/details/gt2sotpuhjy.html

[P02] MD5 / SHA256 摘要
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nijwkfdj.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.bjfxy.top/Article/details/gt2xptqyvfj.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.chenlongwang.top/Article/details/gt2qisqqibl.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.hnqzz.top/Article/details/gt2nktzqsav.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yvedp.cn/Article/details/gt2pfddimfx.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.316326.xyz/Article/details/gt2gisiyfbf.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.hnqzz.top/Article/details/gt2ggjkztmn.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.kuanghao11.cn/Article/details/gt2uplivpar.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.ppjwa.cn/Article/details/gt2qxwncefi.html

[P03] 生成短随机字符串
来源：http://dali.nwbrower.top/Article/details/gt2xbxrmzkj.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.gaohongyu789.top/Article/details/gt2vnposmmo.html


<!-- 参考信息 -->