代发 wailian999

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.chenlongwang.top/Article/details/gt2ejnnnvrv.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gt2jkhjtkup.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gt2hrbwbeil.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.ybcxt.top/Article/details/gt2kopffzis.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.tian-w.cn/Article/details/gt2lcvspvnq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.tian-w.cn/Article/details/gt2pobfkufj.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2rkedmopy.html

[L06] 解析响应为 JSON
来源：http://dali.yuxming.cn/Article/details/gt2lekpotwy.html

Py:   resp.json()
来源：http://dali.yonumen.top/Article/details/gt2gzvvxtde.html

PHP:  json_decode($body, true);
来源：http://dali.zhiwuduotai.top/Article/details/gt2rktwafkc.html

JS:   await resp.json()
来源：http://dali.hammf.cn/Article/details/gt2lbvlpwjl.html

TS:   await resp.json()
来源：http://dali.quarkkingdee.top/Article/details/gt2oaohrhjl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mbvvliwu.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hywenlv.cn/Article/details/gt2mmunvnqb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuxming.cn/Article/details/gt2vmktvirm.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2itpdmrmr.html

[L07] 处理 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gt2nawevsaf.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cucudq.cn/Article/details/gt2xkclrxns.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.nwbrower.top/Article/details/gt2kcnsydxb.html

JS:   resp.ok;  resp.status
来源：http://dali.quarkkingdee.top/Article/details/gt2hkiultec.html

TS:   resp.ok;  resp.status
来源：http://dali.snrcjt.cn/Article/details/gt2uwatjthp.html

Java: resp.statusCode()
来源：http://dali.haohaochexian.top/Article/details/gt2ocjkzoqf.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gt2puzwdywx.html

Ruby: resp.code.to_i
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xmmkeimb.html

C#:   (int)resp.StatusCode
来源：http://dali.cheryme.top/Article/details/gt2wyxbwefh.html

[L08] 并发请求多个地址
来源：http://dali.xinyue.icu/Article/details/gt2doyqjujb.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ibxipmsx.html

PHP:  curl_multi_init() 系列
来源：http://dali.hnxiangtu.top/Article/details/gt2vxpjutfs.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.bjfxy.top/Article/details/gt2jodxfsli.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xmforben.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.cucudq.cn/Article/details/gt2ecprjufa.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.tianlin.xyz/Article/details/gt2fajethtl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hywenlv.cn/Article/details/gt2liluvhgl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.zdqjudy.top/Article/details/gt2vwghjycy.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2tduyslqo.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenzaomai.com/Article/details/gt2ljetfnvc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqhrtly.html

[M01] 读取命令行参数
来源：http://dali.jqgfzy.top/Article/details/gt2qrrbetmi.html

Py:   sys.argv[1:]
来源：http://dali.redwolf501.top/Article/details/gt2zizmkimf.html

PHP:  $argv;  $argc;
来源：http://dali.hywenlv.cn/Article/details/gt2ipsydaxp.html

JS:   process.argv.slice(2)
来源：http://dali.tianlin.xyz/Article/details/gt2ngwjfojg.html

TS:   process.argv.slice(2)
来源：http://dali.shzxlz.cn/Article/details/gt2hfswfhwq.html

Java: args 数组（main 方法参数）
来源：http://dali.yj20258.top/Article/details/gt2witilsco.html

Go:   os.Args[1:]
来源：http://dali.yj20258.top/Article/details/gt2aywjqxpm.html

Ruby: ARGV
来源：http://dali.redwolf501.top/Article/details/gt2cefnyjll.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jyoumei.cn/Article/details/gt2aksakshc.html

[M02] 读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2ykxbdmda.html

Py:   os.environ.get("HOME")
来源：http://dali.hysaishi.cn/Article/details/gt2pwfbgpww.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.kuanghao11.cn/Article/details/gt2yluwlyku.html

JS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gt2oibntyan.html

TS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gt2rujlutzm.html

Java: System.getenv("HOME")
来源：http://dali.cheryme.top/Article/details/gt2vochbysl.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gaohongyu789.top/Article/details/gt2ltvvyryt.html

Ruby: ENV["HOME"]
来源：http://dali.yonumen.top/Article/details/gt2uikdhitq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.guannengcc.top/Article/details/gt2hrtjyfln.html

[M03] 执行外部命令
来源：http://dali.gotoacloud.top/Article/details/gt2qfnumvxs.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jinqigfzy.top/Article/details/gt2rsfeurth.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.xinyue.icu/Article/details/gt2vblazpca.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.gogol.net.cn/Article/details/gt2aomndzuh.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gt2girstswj.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2znybjwdb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.aibaodan.cn/Article/details/gt2puytdpds.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuanzhike.top/Article/details/gt2tmzgsiaa.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aizwys.cn/Article/details/gt2avbwpqua.html

[M04] 获取当前工作目录
来源：http://dali.hammf.cn/Article/details/gt2lgflgisd.html

Py:   os.getcwd()
来源：http://dali.kuanghao11.cn/Article/details/gt2hepvhpmr.html

PHP:  getcwd();
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdalijuf.html

JS:   process.cwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2sqfgaypy.html

TS:   process.cwd()
来源：http://dali.meibo888.top/Article/details/gt2bnlfwgze.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.ppjwa.cn/Article/details/gt2teznqgdj.html

Go:   os.Getwd()
来源：http://dali.jlsjyb.cn/Article/details/gt2gbwwptld.html

Ruby: Dir.pwd
来源：http://dali.hnxiangtu.top/Article/details/gt2pwtxkeno.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.gotoacloud.top/Article/details/gt2kysnyobi.html

[M05] 设置退出码
来源：http://dali.ybcxt.top/Article/details/gt2mmzixjbg.html

Py:   sys.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gt2bakdrhgv.html

PHP:  exit(1);
来源：http://dali.havefunace.top/Article/details/gt2tbnlxpnv.html

JS:   process.exit(1)
来源：http://dali.jlsjyb.cn/Article/details/gt2vsagoieg.html

TS:   process.exit(1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2fspjyqtl.html

Java: System.exit(1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bufzeimp.html

Go:   os.Exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjisbpbd.html

Ruby: exit 1
来源：http://dali.hysaishi.cn/Article/details/gt2onavrsnd.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenlongwang.top/Article/details/gt2unsedzjd.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gt2xzpcbvks.html

Py:   print("err", file=sys.stderr)
来源：http://dali.tianlin.xyz/Article/details/gt2smzcbsfz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuetiantiany.cn/Article/details/gt2ffljiazb.html

JS:   console.error("err")
来源：http://dali.zdqjudy.top/Article/details/gt2fmnrhofd.html

TS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gt2lwmppxwp.html

Java: System.err.println("err")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxtbctvn.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.xinyue.icu/Article/details/gt2jycubeqp.html

Ruby: warn "err"
来源：http://dali.yongpay.top/Article/details/gt2tvvtajbi.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zdqjudy.top/Article/details/gt2wbqrkmun.html

[M07] 判断是否为主入口
来源：http://dali.bjfxy.top/Article/details/gt2eozszscr.html

Py:   if __name__ == "__main__":
来源：http://dali.9152youxi.cn/Article/details/gt2yesyuvij.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jdslvuta.html

JS:   require.main === module
来源：http://dali.pengpengdd.cyou/Article/details/gt2lepybmov.html

TS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gt2yjbfmqak.html

Java: public static void main(String[] args)
来源：http://dali.daxiang520.top/Article/details/gt2ulvouozm.html

Go:   func main()
来源：http://dali.jianghu66.top/Article/details/gt2epumktno.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.iojbl.cn/Article/details/gt2bdhtqwod.html

C#:   static void Main(string[] args)
来源：http://dali.yueranfly.top/Article/details/gt2wynsqoxg.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gt2pulfjcds.html

Py:   platform.system();  platform.python_version()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nyihvsor.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.shuidangran.top/Article/details/gt2ylnaitcp.html

JS:   process.platform;  process.version
来源：http://dali.gzhubu.top/Article/details/gt2yhaxdewg.html

TS:   process.platform;  process.version
来源：http://dali.cashguo.top/Article/details/gt2daomgkiz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhijiandao.cn/Article/details/gt2jneqzuqy.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gogol.net.cn/Article/details/gt2mncnwdbp.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gt2knfzccga.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.cqqwz.cn/Article/details/gt2gokcouoi.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2trcpqpka.html

N. 数据结构与算法
来源：http://dali.kuanghao11.cn/Article/details/gt2dotetfcn.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2tilvebbx.html

[N01] 二分查找（有序数组）
来源：http://dali.redwolf501.top/Article/details/gt2ghemckic.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.gzhubu.top/Article/details/gt2axhdatuq.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yuanzhike.top/Article/details/gt2ceypghbb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ixwkjsix.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.xylfe.cn/Article/details/gt2fzbtftks.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2txxyoxae.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2fcckusde.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yanxiufei.cn/Article/details/gt2vfcdvjxk.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2glfneduq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hnxiangtu.top/Article/details/gt2tdxdtwhm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gt2qnmwmacc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jhtqljsu.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yanxiufei.cn/Article/details/gt2ahhjpixe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.tianlin.xyz/Article/details/gt2ffbwxfqn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.xuetiantiany.cn/Article/details/gt2vglqkwpc.html

Go:   slices.Sort(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qulsbpxc.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gt2yvsvlxsi.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zhengqikj.top/Article/details/gt2vtbuoqbg.html

[N03] 快速排序（分治示例）
来源：http://dali.zhijiandao.cn/Article/details/gt2mchjuouo.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.0kj1m.cn/Article/details/gt2pzyjxobh.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sxryk.cn/Article/details/gt2husblfxp.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gotoacloud.top/Article/details/gt2grrytmgk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yonumen.top/Article/details/gt2nwfgxqwy.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.wangdashe.top/Article/details/gt2koxpirmp.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.hysaishi.cn/Article/details/gt2tnjylprq.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.nanxinkj.top/Article/details/gt2spbpompw.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jlsjyb.cn/Article/details/gt2dbfwhdyu.html

[N04] 斐波那契数列
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbcysvv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.dashuyun.cn/Article/details/gt2vqjnzxex.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.fengsongda.top/Article/details/gt2utmpocdx.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gt2zqztsanc.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.gzhubu.top/Article/details/gt2bjaayrrk.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gt2svojgwqb.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bzzzioxv.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.nwbrower.top/Article/details/gt2lrhborfg.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gt2tjxynyej.html

[N05] 最大公约数
来源：http://dali.hfpthk.cn/Article/details/gt2dbvcrzis.html

Py:   math.gcd(a, b)
来源：http://dali.0kj1m.cn/Article/details/gt2uohhqdub.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2npqznbpq.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2lddwmoiw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nanxuanxn.top/Article/details/gt2vtlkjerm.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.fengsongda.top/Article/details/gt2qselcjqb.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.meibo888.top/Article/details/gt2wuvaczie.html

Ruby: a.gcd(b)
来源：http://dali.zhengqikj.top/Article/details/gt2fwhmbucn.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.guowangkeji.top/Article/details/gt2pnjraywo.html

[N06] 判断回文字符串
来源：http://dali.havefunace.top/Article/details/gt2tbgtkfmm.html

Py:   s == s[::-1]
来源：http://dali.jinqigfzy.top/Article/details/gt2jjgxeons.html

PHP:  $s === strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gt2zebkuika.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yongpay.top/Article/details/gt2kvxmpatq.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gt2opnvtacz.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.dianchejie.cn/Article/details/gt2djivfbgt.html

Go:   // 双指针从两端比较
来源：http://dali.shangyingyoupin.top/Article/details/gt2webceyiz.html

Ruby: s == s.reverse
来源：http://dali.yangfankeji.com/Article/details/gt2dyiemwaq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gt2udtdqulz.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgfzy.top/Article/details/gt2tpevknve.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.havefunace.top/Article/details/gt2gtpvlhiv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yonumen.top/Article/details/gt2luexqyjm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.316326.xyz/Article/details/gt2dspgjbnk.html

TS:   // 手写 Map<string, number>
来源：http://dali.yongpay.top/Article/details/gt2cnqkgxzw.html

Java: // 手写 HashMap
来源：http://dali.ehwqpu.com/Article/details/gt2ivfawmjh.html

Go:   // 手写 map[int]int
来源：http://dali.sysykeji.top/Article/details/gt2fricnvxb.html

Ruby: // 手写 Hash
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zmedfpaf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shzxlz.cn/Article/details/gt2eoarhzal.html

[N08] 生成全排列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pafcsiva.html

Py:   itertools.permutations(arr)
来源：http://dali.yueranfly.top/Article/details/gt2kkqehczn.html

PHP:  // 手写递归交换
来源：http://dali.zhixingplan.top/Article/details/gt2hkbsmuyp.html

JS:   // 手写回溯递归
来源：http://dali.jianghu66.top/Article/details/gt2dvobrbsg.html

TS:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2yubkjdin.html

Java: // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gt2dxvscnvh.html

Go:   // 手写回溯递归
来源：http://dali.yuxming.cn/Article/details/gt2knyzhbjm.html

Ruby: arr.permutation.to_a
来源：http://dali.shzxlz.cn/Article/details/gt2ikdsuxll.html

C#:   // 手写回溯递归
来源：http://dali.pycfn.com/Article/details/gt2fengkuvs.html

[N09] 栈与队列
来源：http://dali.dashuyun.cn/Article/details/gt2zwkzdhfv.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.jlsjyb.cn/Article/details/gt2eaizqqxp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.gaohongyu789.top/Article/details/gt2srraqipg.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.shzxlz.cn/Article/details/gt2nwnekhst.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.wangdashe.top/Article/details/gt2dadqwtcw.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.ydzc1.top/Article/details/gt2putggvkw.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jlsjyb.cn/Article/details/gt2xuiculcm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.pengpengdd.cyou/Article/details/gt2bfwetbxe.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.quarkkingdee.top/Article/details/gt2fjybagjz.html

[N10] 链表节点定义
来源：http://dali.feifeiyinyue.top/Article/details/gt2rgopjbpi.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.yuxming.cn/Article/details/gt2gjcpnpfd.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.c1oappe.top/Article/details/gt2qunrzlgy.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dqwnchim.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.hnxiangtu.top/Article/details/gt2inccnivu.html

Java: class Node { int v; Node next; }
来源：http://dali.nwbrower.top/Article/details/gt2spkmsqvt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gzhubu.top/Article/details/gt2bnfdxjlj.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sysykeji.top/Article/details/gt2irgnwyfk.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aibaodan.cn/Article/details/gt2vgbvfvpg.html

[N11] 二叉树中序遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2sprvscst.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.fzhhl.top/Article/details/gt2bpeuvqjg.html

PHP:  // 手写递归函数
来源：http://dali.gaohongyu789.top/Article/details/gt2ngjcpkfp.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jiagoushi.top/Article/details/gt2abfhidzz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hnxiangtu.top/Article/details/gt2xjdrvbtf.html

Java: // 手写递归
来源：http://dali.zycfv.cn/Article/details/gt2vjmkesfy.html

Go:   // 手写递归
来源：http://dali.feifeiyinyue.top/Article/details/gt2sqjgmwqi.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.bjfxy.top/Article/details/gt2ctyeqdkg.html

C#:   // 手写递归
来源：http://dali.iojbl.cn/Article/details/gt2fsdezivm.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.snrcjt.cn/Article/details/gt2vvxgwbio.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.cheryme.top/Article/details/gt2rbvegmya.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcpodcgf.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aibaodan.cn/Article/details/gt2iesjsmzd.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gogol.net.cn/Article/details/gt2hnjwbjwr.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenlongwang.top/Article/details/gt2vkhnxvqr.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.jianghu66.top/Article/details/gt2isvlgbds.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zpolbjpa.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.nwbrower.top/Article/details/gt2lrawzmki.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2kmwzkkvj.html

O. 并发与异步
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dzitxurr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2qhfxrpwa.html

[O01] 启动一个线程
来源：http://dali.xinyue.icu/Article/details/gt2znqgqopa.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jsnkhswg.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jqgfzy.top/Article/details/gt2zzhgqedw.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.jiagoushi.top/Article/details/gt2paobldpc.html

TS:   // 同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gttvhemx.html

Java: new Thread(() -> f()).start()
来源：http://dali.daria6918.cn/Article/details/gt2icetgryx.html

Go:   go f()
来源：http://dali.gogol.net.cn/Article/details/gt2ktumzfke.html

Ruby: Thread.new { f }
来源：http://dali.cucudq.cn/Article/details/gt2nivwuvkj.html

C#:   Task.Run(() => F());
来源：http://dali.tianlin.xyz/Article/details/gt2sruiepie.html

[O02] 使用线程池
来源：http://dali.ivvv.top/Article/details/gt2ogvhauks.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydoaiapl.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.xinyue.icu/Article/details/gt2mkihndmp.html

JS:   // worker_threads 线程池
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxqdvmqo.html

TS:   // worker_threads 线程池
来源：http://dali.yuanzhike.top/Article/details/gt2jzwdnjsr.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ivvv.top/Article/details/gt2uxynkcsf.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.bjfxy.top/Article/details/gt2eawdtfxn.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xzakabuo.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.birdmap.top/Article/details/gt2ozjdwocq.html

[O03] 加锁保护共享数据
来源：http://dali.sufxvd.cn/Article/details/gt2lferpjdu.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gt2kpfsfkfq.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.wangshuangyany.cn/Article/details/gt2okbxgbfr.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.jianghu66.top/Article/details/gt2xmheebui.html

TS:   // 同 JS
来源：http://dali.xuanzx.com/Article/details/gt2hfwvfzzi.html

Java: synchronized (this) { shared++; }
来源：http://dali.c1oappe.top/Article/details/gt2sctnxtyb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.yuxming.cn/Article/details/gt2psrcmjtt.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.sxryk.cn/Article/details/gt2canttisb.html

C#:   lock (gate) { shared++; }
来源：http://dali.hammf.cn/Article/details/gt2hhlgqxap.html

[O04] 定义异步函数并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gteabmpp.html

Py:   async def f():⏎    await g()
来源：http://dali.hfpthk.cn/Article/details/gt2cbuvnlxs.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.yj202588.top/Article/details/gt2utptxtnj.html

JS:   async function f() { await g(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2grxtqrls.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.sufxvd.cn/Article/details/gt2ypxuzuge.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.jlsjyb.cn/Article/details/gt2kzctbemu.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.birdmap.top/Article/details/gt2bplptzmk.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.hnxiangtu.top/Article/details/gt2ekfvaoqf.html

C#:   async Task F() { await G(); }
来源：http://dali.ybcxt.top/Article/details/gt2mjujiwtl.html

[O05] 并发执行并等待全部完成
来源：http://dali.shangyingyoupin.top/Article/details/gt2thspytcq.html

Py:   asyncio.gather(*tasks)
来源：http://dali.jianghu66.top/Article/details/gt2lejoawvm.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sxryk.cn/Article/details/gt2ncczpdbq.html

JS:   await Promise.all(tasks)
来源：http://dali.zycfv.cn/Article/details/gt2biblfcek.html

TS:   await Promise.all(tasks)
来源：http://dali.shangyingyoupin.top/Article/details/gt2iifsesxu.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.gaohongyu789.top/Article/details/gt2znmyxndy.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yueranfly.top/Article/details/gt2qxywgtcu.html

Ruby: threads.map(&:join)
来源：http://dali.hywenlv.cn/Article/details/gt2sbjdsygf.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.quarkkingdee.top/Article/details/gt2spwgtcur.html

[O06] 使用进程池
来源：http://dali.hammf.cn/Article/details/gt2wnilqfgo.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.yj20258888.top/Article/details/gt2dpaicrbn.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jqgfzy.top/Article/details/gt2yptkytoj.html

JS:   // child_process / cluster 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpoflnfr.html

TS:   // child_process / cluster 模块
来源：http://dali.tanke756.top/Article/details/gt2jubinppg.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.zhengqikj.top/Article/details/gt2szetpmuk.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.sufxvd.cn/Article/details/gt2muwrdjui.html

Ruby: // fork 块
来源：http://dali.shangyingyoupin.top/Article/details/gt2jyryybcz.html

C#:   Parallel.For
来源：http://dali.sysykeji.top/Article/details/gt2lblgakax.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2flfbrcuz.html

P. 常用工具函数
来源：http://dali.aizwys.cn/Article/details/gt2jcqoalzh.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2sxorrhfl.html

[P01] 生成 UUID
来源：http://dali.cheryme.top/Article/details/gt2mvmyqqkv.html

Py:   str(uuid.uuid4())
来源：http://dali.xinyue.icu/Article/details/gt2cujonmwt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.xuanzx.com/Article/details/gt2kjbdtapu.html

JS:   crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gt2qydhgkci.html

TS:   crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gt2hwykhjkw.html

Java: UUID.randomUUID().toString()
来源：http://dali.jiagoushi.top/Article/details/gt2qiaqwyhk.html

Go:   // 用 github.com/google/uuid
来源：http://dali.cdnleiting.top/Article/details/gt2uwjekxns.html

Ruby: SecureRandom.uuid
来源：http://dali.cucudq.cn/Article/details/gt2yybjwwxl.html

C#:   Guid.NewGuid().ToString()
来源：http://dali.andypj.xyz/Article/details/gt2vtxlrrlo.html

[P02] MD5 / SHA256 摘要
来源：http://dali.wangshuangyany.cn/Article/details/gt2hyjdvikv.html

Py:   hashlib.sha256(b).hexdigest();  hashlib.md5(b).hexdigest()
来源：http://dali.jianghu66.top/Article/details/gt2zsdlqdou.html

PHP:  hash("sha256", $s);  md5($s);
来源：http://dali.cdnleiting.top/Article/details/gt2krtcejmn.html

JS:   crypto.createHash("sha256").update(s).digest("hex")     // Node
来源：http://dali.yonumen.top/Article/details/gt2jmpdjfah.html

TS:   crypto.createHash("sha256").update(s).digest("hex")
来源：http://dali.yueranfly.top/Article/details/gt2gxjmdnos.html

Java: MessageDigest.getInstance("SHA-256").digest(bytes)
来源：http://dali.shzxlz.cn/Article/details/gt2imirzcur.html

Go:   fmt.Sprintf("%x", sha256.Sum256([]byte(s)))
来源：http://dali.guowangkeji.top/Article/details/gt2ymaqkout.html

Ruby: Digest::SHA256.hexdigest(s)
来源：http://dali.dashuyun.cn/Article/details/gt2jagqjgyi.html

C#:   Convert.ToHexString(SHA256.HashData(bytes))
来源：http://dali.guannengcc.top/Article/details/gt2vwciavyz.html

[P03] 生成短随机字符串
来源：http://dali.tanke756.top/Article/details/gt2jppvlnhm.html

Py:   "".join(random.choices(string.ascii_letters + string.digits, k=16))
来源：http://dali.yongpay.top/Article/details/gt2iizwgdcx.html


<!-- 参考信息 -->