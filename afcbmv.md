代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yonumen.top/Article/details/gt2kyhvdftl.html

[L04] 设置超时
来源：http://dali.havefunace.top/Article/details/gt2yeiwbcqh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pfcyjxeo.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvowikin.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yvedp.cn/Article/details/gt2dagartkm.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cqlzznuh.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.yonumen.top/Article/details/gt2iuuayhqg.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgufenzy.top/Article/details/gt2oexgnmsd.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tian-w.cn/Article/details/gt2yvmkrjwm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgfzy.top/Article/details/gt2dprzrhlq.html

[L05] 上传文件（multipart）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cffwkxqe.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.tianlin.xyz/Article/details/gt2dqqnjlwd.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jianghu66.top/Article/details/gt2dwtmtqnb.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.jqgfzy.top/Article/details/gt2lecehpir.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daria6918.cn/Article/details/gt2avgbkswv.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.fengsongda.top/Article/details/gt2pahrtqsn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rgmrkvtl.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.ivvv.top/Article/details/gt2gpepnwhq.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.smart0.xyz/Article/details/gt2pwncojck.html

[L06] 解析响应为 JSON
来源：http://dali.ybcxt.top/Article/details/gt2uwuhkdwx.html

Py:   resp.json()
来源：http://dali.aibaodan.cn/Article/details/gt2vtbtqxpn.html

PHP:  json_decode($body, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kuusspgb.html

JS:   await resp.json()
来源：http://dali.dashuyun.cn/Article/details/gt2ypkgljoj.html

TS:   await resp.json()
来源：http://dali.zhixingplan.top/Article/details/gt2jyzhnxfl.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.iojbl.cn/Article/details/gt2xqwluyly.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hysaishi.cn/Article/details/gt2clbnossu.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yuanzhike.top/Article/details/gt2kumydzdf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sweek.top/Article/details/gt2grzmxzgi.html

[L07] 处理 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jjxjlhmk.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gotoacloud.top/Article/details/gt2ymymvrhi.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.aibaodan.cn/Article/details/gt2bszwrfns.html

JS:   resp.ok;  resp.status
来源：http://dali.tianlin.xyz/Article/details/gt2rgnarssx.html

TS:   resp.ok;  resp.status
来源：http://dali.zhoulong.xyz/Article/details/gt2hfzmceoi.html

Java: resp.statusCode()
来源：http://dali.zycfv.cn/Article/details/gt2pnkpqluk.html

Go:   resp.StatusCode
来源：http://dali.xinyue.icu/Article/details/gt2lzakermi.html

Ruby: resp.code.to_i
来源：http://dali.haohaochexian.top/Article/details/gt2xgkblguq.html

C#:   (int)resp.StatusCode
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlikziwn.html

[L08] 并发请求多个地址
来源：http://dali.zycfv.cn/Article/details/gt2lcpcczay.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yangfankeji.com/Article/details/gt2oxkgxkhu.html

PHP:  curl_multi_init() 系列
来源：http://dali.guannengcc.top/Article/details/gt2wrgmiwby.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gt2hoooekgh.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gt2kcitlxff.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.tanke756.top/Article/details/gt2nvjwewuz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgufenzy.top/Article/details/gt2clcxkrxt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gogol.net.cn/Article/details/gt2ndjflwpl.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ydzc1.top/Article/details/gt2ssfwvrdv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2vtbxduxg.html

M. 命令行 / 进程 / 环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kcuoffmi.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmdpxriw.html

[M01] 读取命令行参数
来源：http://dali.yonumen.top/Article/details/gt2lwkqsoep.html

Py:   sys.argv[1:]
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwuzaaoj.html

PHP:  $argv;  $argc;
来源：http://dali.sweek.top/Article/details/gt2ofiwdarv.html

JS:   process.argv.slice(2)
来源：http://dali.ybcxt.top/Article/details/gt2smobfhkd.html

TS:   process.argv.slice(2)
来源：http://dali.zdqjudy.top/Article/details/gt2puinxtnf.html

Java: args 数组（main 方法参数）
来源：http://dali.yueranfly.top/Article/details/gt2tyzschci.html

Go:   os.Args[1:]
来源：http://dali.aizwys.cn/Article/details/gt2ndlzdyai.html

Ruby: ARGV
来源：http://dali.zdqjudy.top/Article/details/gt2bifwfafa.html

C#:   args 数组（Main 方法参数）
来源：http://dali.hammf.cn/Article/details/gt2okcdzjju.html

[M02] 读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gt2lgorvaqa.html

Py:   os.environ.get("HOME")
来源：http://dali.cheryme.top/Article/details/gt2egnouunc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hammf.cn/Article/details/gt2jvuiqeqh.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gt2qttvbwuf.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gt2bkdplfei.html

Java: System.getenv("HOME")
来源：http://dali.yj20258888.top/Article/details/gt2agyccgwo.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gt2zojvqxeb.html

Ruby: ENV["HOME"]
来源：http://dali.guannengcc.top/Article/details/gt2srbwnoxu.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.iojbl.cn/Article/details/gt2oyjyvesu.html

[M03] 执行外部命令
来源：http://dali.zdqjudy.top/Article/details/gt2qxhwmmph.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhengqikj.top/Article/details/gt2faacvhao.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2acfcxtfm.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gt2sfgivxku.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zdqjudy.top/Article/details/gt2rfwzrvol.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2yaootalv.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.sxryk.cn/Article/details/gt2crhxyxrk.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yj20258888.top/Article/details/gt2xrkkdjqz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.daxiang520.top/Article/details/gt2osuhwiua.html

[M04] 获取当前工作目录
来源：http://dali.xuanzx.com/Article/details/gt2emisggky.html

Py:   os.getcwd()
来源：http://dali.nanxinkj.top/Article/details/gt2vimuzoin.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gt2gwfrwret.html

JS:   process.cwd()
来源：http://dali.xylfe.cn/Article/details/gt2akfbyzqn.html

TS:   process.cwd()
来源：http://dali.zhongyouzk.top/Article/details/gt2gqokusvt.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.pycfn.com/Article/details/gt2kjdtaxjc.html

Go:   os.Getwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2vufzgvei.html

Ruby: Dir.pwd
来源：http://dali.9152youxi.cn/Article/details/gt2hyrazfqh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.meibo888.top/Article/details/gt2xgjfehbk.html

[M05] 设置退出码
来源：http://dali.jinqigufen.top/Article/details/gt2kzyfscbq.html

Py:   sys.exit(1)
来源：http://dali.gogol.net.cn/Article/details/gt2nbrbqrlx.html

PHP:  exit(1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pycahort.html

JS:   process.exit(1)
来源：http://dali.redwolf501.top/Article/details/gt2zlqphnta.html

TS:   process.exit(1)
来源：http://dali.pycfn.com/Article/details/gt2pzmjuhyp.html

Java: System.exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2gfgakwkb.html

Go:   os.Exit(1)
来源：http://dali.guowangkeji.top/Article/details/gt2gfmmrtzq.html

Ruby: exit 1
来源：http://dali.vqdsnc.cn/Article/details/gt2inionasr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.sysykeji.top/Article/details/gt2zcyugplx.html

[M06] 向标准错误输出
来源：http://dali.xuetiantiany.cn/Article/details/gt2dtckitfk.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jyoumei.cn/Article/details/gt2tpuhuase.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hongshengwenyu.top/Article/details/gt2joahxnfg.html

JS:   console.error("err")
来源：http://dali.gotoacloud.top/Article/details/gt2eggxohda.html

TS:   console.error("err")
来源：http://dali.gaohongyu789.top/Article/details/gt2wnzawjol.html

Java: System.err.println("err")
来源：http://dali.jlsjyb.cn/Article/details/gt2qofvxury.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yangfankeji.com/Article/details/gt2pvkndsoy.html

Ruby: warn "err"
来源：http://dali.ppjwa.cn/Article/details/gt2iweeywpq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.shuidangran.top/Article/details/gt2gjxnsscd.html

[M07] 判断是否为主入口
来源：http://dali.zhiwuduotai.top/Article/details/gt2pnadtydo.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gt2vmmctqup.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jinqigfzy.top/Article/details/gt2vzsqolix.html

JS:   require.main === module
来源：http://dali.cheryme.top/Article/details/gt2kyozjakf.html

TS:   require.main === module
来源：http://dali.feifeiyinyue.top/Article/details/gt2bkiucewh.html

Java: public static void main(String[] args)
来源：http://dali.wangdashe.top/Article/details/gt2zkddgepy.html

Go:   func main()
来源：http://dali.shuidangran.top/Article/details/gt2zasluxod.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.zhijiandao.cn/Article/details/gt2czgjrhoa.html

C#:   static void Main(string[] args)
来源：http://dali.bjfxy.top/Article/details/gt2uxremroc.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gt2aegfmfns.html

Py:   platform.system();  platform.python_version()
来源：http://dali.sufxvd.cn/Article/details/gt2qinyskfn.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gt2pyhdqupc.html

JS:   process.platform;  process.version
来源：http://dali.cucudq.cn/Article/details/gt2pglwpxzs.html

TS:   process.platform;  process.version
来源：http://dali.yj20258888.top/Article/details/gt2jbakpxpc.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.nanxuanxn.top/Article/details/gt2daaqzmja.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.mhx1999.top/Article/details/gt2qjutqcry.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yuanzhike.top/Article/details/gt2lyiiutao.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.quarkkingdee.top/Article/details/gt2pfozkiwl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2epsjhizp.html

N. 数据结构与算法
来源：http://dali.zhiwuduotai.top/Article/details/gt2gueouubp.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2oporoiau.html

[N01] 二分查找（有序数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aqvuvsfj.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2brycngxt.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.jqgufenzy.top/Article/details/gt2iompalta.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.birdmap.top/Article/details/gt2kryosypi.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2nbolkyxb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.birdmap.top/Article/details/gt2lltxnblt.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2amouswbz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhijiandao.cn/Article/details/gt2gymwfutc.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gt2vwhuxzhy.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sufxvd.cn/Article/details/gt2xkfhzezu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tianlin.xyz/Article/details/gt2jsuqdaud.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.hnqzz.top/Article/details/gt2brpftfld.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cashguo.top/Article/details/gt2wqphhazi.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gt2tlxgrfhi.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jyoumei.cn/Article/details/gt2zjsdafdv.html

Go:   slices.Sort(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2twnxhxwr.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gt2pyghxoyl.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.cashguo.top/Article/details/gt2uqhfvwzz.html

[N03] 快速排序（分治示例）
来源：http://dali.cdnleiting.top/Article/details/gt2xulbjjze.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.svipenyu.cn/Article/details/gt2soowhzyg.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sweek.top/Article/details/gt2jxmefpcs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hnxiangtu.top/Article/details/gt2bpauhkmw.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gt2gchcgaox.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.sufxvd.cn/Article/details/gt2hswgftny.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xcxkxnea.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gt2mfqqdioq.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.tanke756.top/Article/details/gt2fplrxtaz.html

[N04] 斐波那契数列
来源：http://dali.yonumen.top/Article/details/gt2rtpzyocv.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gt2dddootwy.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.quarkkingdee.top/Article/details/gt2btfjhrpw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.pycfn.com/Article/details/gt2kaddudhu.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zdqjudy.top/Article/details/gt2ubcjokfo.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rwlzvtmz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hnqzz.top/Article/details/gt2aavkdllo.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gt2fazymeto.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.cdnleiting.top/Article/details/gt2fsgdpirt.html

[N05] 最大公约数
来源：http://dali.316326.xyz/Article/details/gt2iwmmwsca.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gt2xxpiydaz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.meibo888.top/Article/details/gt2ixrjngmv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gt2cqjzzmxp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2heimswao.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.cucudq.cn/Article/details/gt2ripqmhgj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.xziqi.cn/Article/details/gt2ufsfcaqy.html

Ruby: a.gcd(b)
来源：http://dali.zhixingplan.top/Article/details/gt2gxnbgbmy.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jqgufenzy.top/Article/details/gt2xaaqiejj.html

[N06] 判断回文字符串
来源：http://dali.xylfe.cn/Article/details/gt2vsqubdst.html

Py:   s == s[::-1]
来源：http://dali.sweek.top/Article/details/gt2zqnerncj.html

PHP:  $s === strrev($s);
来源：http://dali.aizwys.cn/Article/details/gt2jdlaujyk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2mxhywpkh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.zycfv.cn/Article/details/gt2fnhgkaww.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.guowangkeji.top/Article/details/gt2jfhcephy.html

Go:   // 双指针从两端比较
来源：http://dali.gotoacloud.top/Article/details/gt2fjjvaezc.html

Ruby: s == s.reverse
来源：http://dali.aibaodan.cn/Article/details/gt2roiuxbtj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.hysaishi.cn/Article/details/gt2xjbzplbh.html

[N07] 两数之和（返回下标）
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpgraui.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ehwqpu.com/Article/details/gt2jneyfwzv.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.zhongyouzk.top/Article/details/gt2hpqcahml.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ydzc1.top/Article/details/gt2ilckcuxa.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gt2cafgbmlh.html

Java: // 手写 HashMap
来源：http://dali.hywenlv.cn/Article/details/gt2hrykmnat.html

Go:   // 手写 map[int]int
来源：http://dali.snrcjt.cn/Article/details/gt2eluokedo.html

Ruby: // 手写 Hash
来源：http://dali.meibo888.top/Article/details/gt2fiaigikh.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.cheryme.top/Article/details/gt2nwufrtud.html

[N08] 生成全排列
来源：http://dali.chenjidiqi.icu/Article/details/gt2rusjovem.html

Py:   itertools.permutations(arr)
来源：http://dali.tian-w.cn/Article/details/gt2ppimxsjx.html

PHP:  // 手写递归交换
来源：http://dali.aizwys.cn/Article/details/gt2bjeongmt.html

JS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2krvyyxvz.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lzrrenci.html

Java: // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2rqusicwh.html

Go:   // 手写回溯递归
来源：http://dali.ivvv.top/Article/details/gt2ovoicvrh.html

Ruby: arr.permutation.to_a
来源：http://dali.yvedp.cn/Article/details/gt2gwnavjdi.html

C#:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2rwahlxbt.html

[N09] 栈与队列
来源：http://dali.andypj.xyz/Article/details/gt2lzwxgdii.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.xinyue.icu/Article/details/gt2hgejbfvn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhongyouzk.top/Article/details/gt2equwwptz.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnqzz.top/Article/details/gt2hlnvrfno.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.cucudq.cn/Article/details/gt2nxtbcprl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.guowangkeji.top/Article/details/gt2turgfjmy.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.redwolf501.top/Article/details/gt2erumnrum.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.shuidangran.top/Article/details/gt2lcyojwnf.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gt2bpisbsqv.html

[N10] 链表节点定义
来源：http://dali.daria6918.cn/Article/details/gt2fuiegayh.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.kuanghao11.cn/Article/details/gt2tjbmvluh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gt2nfkdbpee.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.snrcjt.cn/Article/details/gt2srlslckq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gt2amtihrcs.html

Java: class Node { int v; Node next; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrbjyqzk.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2stctypxk.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.tian-w.cn/Article/details/gt2vxzrebpv.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pqgmsqyc.html

[N11] 二叉树中序遍历
来源：http://dali.zdqjudy.top/Article/details/gt2kizvflup.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhongyouzk.top/Article/details/gt2ikakkskw.html

PHP:  // 手写递归函数
来源：http://dali.xziqi.cn/Article/details/gt2povimgfu.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhongyouzk.top/Article/details/gt2boktkkdz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sxryk.cn/Article/details/gt2uhwetpqj.html

Java: // 手写递归
来源：http://dali.quarkkingdee.top/Article/details/gt2skwrojtg.html

Go:   // 手写递归
来源：http://dali.cashguo.top/Article/details/gt2eytbknvm.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.pycfn.com/Article/details/gt2mkxzbppf.html

C#:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gt2fcxsxdro.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hysaishi.cn/Article/details/gt2fdubjrqq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.bjfxy.top/Article/details/gt2nmaszmry.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.birdmap.top/Article/details/gt2vinfdjbx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.redwolf501.top/Article/details/gt2codgcfem.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.snrcjt.cn/Article/details/gt2vpesdowv.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.andypj.xyz/Article/details/gt2osoimzyg.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.wangdashe.top/Article/details/gt2yoztqbsa.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.quarkkingdee.top/Article/details/gt2yqwglvlv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangshuangyany.cn/Article/details/gt2hulhnwqy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2mimndsdq.html

O. 并发与异步
来源：http://dali.yuxming.cn/Article/details/gt2ospknzan.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2cygqnprq.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gt2zgwgkeki.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.kuanghao11.cn/Article/details/gt2aehpxszj.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.zhixingplan.top/Article/details/gt2dffzodng.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.zhoulong.xyz/Article/details/gt2tobsgirl.html

TS:   // 同 JS
来源：http://dali.hywenlv.cn/Article/details/gt2fmiqdhmf.html

Java: new Thread(() -> f()).start()
来源：http://dali.bjfxy.top/Article/details/gt2mcqtbops.html

Go:   go f()
来源：http://dali.zhiwuduotai.top/Article/details/gt2flvrqpif.html

Ruby: Thread.new { f }
来源：http://dali.chenzaomai.com/Article/details/gt2kffumnpm.html

C#:   Task.Run(() => F());
来源：http://dali.nanxuanxn.top/Article/details/gt2dmwqqgsr.html

[O02] 使用线程池
来源：http://dali.ppjwa.cn/Article/details/gt2ueubutpi.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hnqzz.top/Article/details/gt2yhtlmjin.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.chenjidiqi.icu/Article/details/gt2nccinkox.html

JS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gt2tcxtneyl.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gt2fftgwuqe.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2iixvlbkr.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qtstzesf.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.cashguo.top/Article/details/gt2plexbzky.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.nanxinkj.top/Article/details/gt2fklayciy.html

[O03] 加锁保护共享数据
来源：http://dali.zycfv.cn/Article/details/gt2hchylaek.html

Py:   with lock: shared += 1
来源：http://dali.ybcxt.top/Article/details/gt2xufliibl.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.sxryk.cn/Article/details/gt2bvvkpgok.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.tian-w.cn/Article/details/gt2ykgtgqxb.html

TS:   // 同 JS
来源：http://dali.jinqigufen.top/Article/details/gt2siqmhckc.html

Java: synchronized (this) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gt2qxgbpesh.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.cdnleiting.top/Article/details/gt2kdlpdqzg.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.yj202588.top/Article/details/gt2ywdpiibj.html

C#:   lock (gate) { shared++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2cmnfshtx.html

[O04] 定义异步函数并等待
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrisvcgj.html

Py:   async def f():⏎    await g()
来源：http://dali.fzhhl.top/Article/details/gt2zzfwacul.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sysykeji.top/Article/details/gt2kxxwxmlp.html

JS:   async function f() { await g(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bkkgvmma.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2coowqysr.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hnxiangtu.top/Article/details/gt2vwkxohmv.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.snrcjt.cn/Article/details/gt2uijdawif.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.nanxinkj.top/Article/details/gt2bzmwarmd.html

C#:   async Task F() { await G(); }
来源：http://dali.jlsjyb.cn/Article/details/gt2wypoqjab.html

[O05] 并发执行并等待全部完成
来源：http://dali.zhixingplan.top/Article/details/gt2uebgvxft.html

Py:   asyncio.gather(*tasks)
来源：http://dali.xziqi.cn/Article/details/gt2bcnvhlhf.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmogyoke.html

JS:   await Promise.all(tasks)
来源：http://dali.yj20258.top/Article/details/gt2zzoejnqf.html

TS:   await Promise.all(tasks)
来源：http://dali.hywenlv.cn/Article/details/gt2stlypdsf.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hfpthk.cn/Article/details/gt2mhuzikyw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.yongpay.top/Article/details/gt2moymmptf.html

Ruby: threads.map(&:join)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2krmrhbvd.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.sufxvd.cn/Article/details/gt2wvxmaosk.html

[O06] 使用进程池
来源：http://dali.gotoacloud.top/Article/details/gt2gaqfnyar.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zhongyouzk.top/Article/details/gt2zwrohnep.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.jyoumei.cn/Article/details/gt2blilyrfp.html

JS:   // child_process / cluster 模块
来源：http://dali.redwolf501.top/Article/details/gt2vbmgpucx.html

TS:   // child_process / cluster 模块
来源：http://dali.yonumen.top/Article/details/gt2jrgadtiu.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.hnxiangtu.top/Article/details/gt2mctndrxj.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.aibaodan.cn/Article/details/gt2obzaqaui.html

Ruby: // fork 块
来源：http://dali.xuanzx.com/Article/details/gt2yzarlvfg.html

C#:   Parallel.For
来源：http://dali.yonumen.top/Article/details/gt2wyjbuqie.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2sutslhdm.html

P. 常用工具函数
来源：http://dali.yj202588.top/Article/details/gt2gdcmzogc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2ujmuydyj.html

[P01] 生成 UUID
来源：http://dali.yuanzhike.top/Article/details/gt2seuuxvbk.html

Py:   str(uuid.uuid4())
来源：http://dali.kuanghao11.cn/Article/details/gt2ynjcmkla.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.chenzaomai.com/Article/details/gt2zguvymwy.html

JS:   crypto.randomUUID()
来源：http://dali.gzhubu.top/Article/details/gt2bjowucvg.html

TS:   crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gt2xblakafh.html

Java: UUID.randomUUID().toString()
来源：http://dali.yanxiufei.cn/Article/details/gt2ueduicxh.html

Go:   // 用 github.com/google/uuid
来源：http://dali.0kj1m.cn/Article/details/gt2agxljcyn.html

Ruby: SecureRandom.uuid
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iltmtbfo.html


<!-- 参考信息 -->