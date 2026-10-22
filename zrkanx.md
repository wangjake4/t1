代发 wailian999

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shuidangran.top/Article/details/gt2nppvpvhu.html

[L04] 设置超时
来源：http://dali.jinqigufen.top/Article/details/gt2slbjftsd.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rixcvtja.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cqfbxheo.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jyoumei.cn/Article/details/gt2maiyrrqr.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.yj20258888.top/Article/details/gt2aahhqoui.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.sufxvd.cn/Article/details/gt2wrycxatn.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jqgfzy.top/Article/details/gt2auglcdek.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.vqdsnc.cn/Article/details/gt2gudgprfm.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.meibo888.top/Article/details/gt2xptxsqli.html

[L05] 上传文件（multipart）
来源：http://dali.9152youxi.cn/Article/details/gt2zapbclmx.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.ppjwa.cn/Article/details/gt2vjrxhdui.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxuanxn.top/Article/details/gt2ffiftsgw.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.snrcjt.cn/Article/details/gt2wuolqmhp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.pycfn.com/Article/details/gt2mwqfjdix.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yj20258888.top/Article/details/gt2zhipcngf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2suyvkqrw.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.hongshengwenyu.top/Article/details/gt2iwkpcsps.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kodbpgsj.html

[L06] 解析响应为 JSON
来源：http://dali.pycfn.com/Article/details/gt2tmzydqvu.html

Py:   resp.json()
来源：http://dali.meibo888.top/Article/details/gt2eizbrugm.html

PHP:  json_decode($body, true);
来源：http://dali.yj20258.top/Article/details/gt2ogbxfcdj.html

JS:   await resp.json()
来源：http://dali.redwolf501.top/Article/details/gt2kaoqiocv.html

TS:   await resp.json()
来源：http://dali.hongshengwenyu.top/Article/details/gt2limrbtlx.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hammf.cn/Article/details/gt2ckilbljn.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ujythbdv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgdiwnmv.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ofnucefk.html

[L07] 处理 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gt2gwsyccej.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.pycfn.com/Article/details/gt2tcbvwcah.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258.top/Article/details/gt2ttetcclf.html

JS:   resp.ok;  resp.status
来源：http://dali.redwolf501.top/Article/details/gt2sydfnmsy.html

TS:   resp.ok;  resp.status
来源：http://dali.dashuyun.cn/Article/details/gt2qsozbgft.html

Java: resp.statusCode()
来源：http://dali.gotoacloud.top/Article/details/gt2erdkuseo.html

Go:   resp.StatusCode
来源：http://dali.yuanzhike.top/Article/details/gt2kbtdibyw.html

Ruby: resp.code.to_i
来源：http://dali.yangfankeji.com/Article/details/gt2qeduymhn.html

C#:   (int)resp.StatusCode
来源：http://dali.xziqi.cn/Article/details/gt2mrqqxcgw.html

[L08] 并发请求多个地址
来源：http://dali.cucudq.cn/Article/details/gt2qfpmcdkp.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuxming.cn/Article/details/gt2jawwrtaa.html

PHP:  curl_multi_init() 系列
来源：http://dali.zycfv.cn/Article/details/gt2kzsaeqnb.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sysykeji.top/Article/details/gt2papcoqun.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhiwuduotai.top/Article/details/gt2nktalpej.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.ybcxt.top/Article/details/gt2prcscljz.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yangfankeji.com/Article/details/gt2ulxcbsbk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.birdmap.top/Article/details/gt2bpvgriir.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.xuanzx.com/Article/details/gt2uzvijweh.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2nfcdwypo.html

M. 命令行 / 进程 / 环境
来源：http://dali.gotoacloud.top/Article/details/gt2mzrwdlhq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2tlprupsg.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gt2yrcrpgsl.html

Py:   sys.argv[1:]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hrdkiqua.html

PHP:  $argv;  $argc;
来源：http://dali.ivvv.top/Article/details/gt2solqaycp.html

JS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gt2qserhaud.html

TS:   process.argv.slice(2)
来源：http://dali.0kj1m.cn/Article/details/gt2hbbnkoiu.html

Java: args 数组（main 方法参数）
来源：http://dali.zdqjudy.top/Article/details/gt2ntyrvmnf.html

Go:   os.Args[1:]
来源：http://dali.tian-w.cn/Article/details/gt2xrazzazj.html

Ruby: ARGV
来源：http://dali.ehwqpu.com/Article/details/gt2tlsvyqum.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jinqigufen.top/Article/details/gt2gurjyovp.html

[M02] 读取环境变量
来源：http://dali.yangfankeji.com/Article/details/gt2kevtegsg.html

Py:   os.environ.get("HOME")
来源：http://dali.ivvv.top/Article/details/gt2pqlyivrt.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jaietqgb.html

JS:   process.env.HOME
来源：http://dali.xylfe.cn/Article/details/gt2tmrjuswx.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gt2hvjiryqk.html

Java: System.getenv("HOME")
来源：http://dali.dianchejie.cn/Article/details/gt2pdctkydb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fbnmvvzh.html

Ruby: ENV["HOME"]
来源：http://dali.ybcxt.top/Article/details/gt2nodkufnx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2oajxyhjw.html

[M03] 执行外部命令
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kujyiwne.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.zhoulong.xyz/Article/details/gt2wwhuuszl.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhijiandao.cn/Article/details/gt2pngskobu.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.birdmap.top/Article/details/gt2eripqlaa.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gt2aqhhgdnb.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.cashguo.top/Article/details/gt2glmworsa.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.yvedp.cn/Article/details/gt2ukybujwq.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.quarkkingdee.top/Article/details/gt2lcewoeij.html

C#:   Process.Start("ls", "-l");
来源：http://dali.kuanghao11.cn/Article/details/gt2fwkyjymy.html

[M04] 获取当前工作目录
来源：http://dali.jianghu66.top/Article/details/gt2fknmbzpj.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2oybthfvs.html

PHP:  getcwd();
来源：http://dali.meibo888.top/Article/details/gt2extrnxud.html

JS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gt2thbbgphh.html

TS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gt2fsutoadw.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.c1oappe.top/Article/details/gt2cxjaohmt.html

Go:   os.Getwd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bxktxfpg.html

Ruby: Dir.pwd
来源：http://dali.jqgfzy.top/Article/details/gt2lyimolsc.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.0kj1m.cn/Article/details/gt2utxndlbv.html

[M05] 设置退出码
来源：http://dali.cashguo.top/Article/details/gt2englkdfu.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2ndgfbkar.html

PHP:  exit(1);
来源：http://dali.hywenlv.cn/Article/details/gt2rskgulzw.html

JS:   process.exit(1)
来源：http://dali.yuanzhike.top/Article/details/gt2iylodmbr.html

TS:   process.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2zgfhvpia.html

Java: System.exit(1)
来源：http://dali.yj20258888.top/Article/details/gt2rrtvsjyz.html

Go:   os.Exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nrsonspo.html

Ruby: exit 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xwudkzxz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.vqdsnc.cn/Article/details/gt2ewvuewud.html

[M06] 向标准错误输出
来源：http://dali.quarkkingdee.top/Article/details/gt2jxulrdtv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gt2hpaxmcps.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cheryme.top/Article/details/gt2kdgwmfcw.html

JS:   console.error("err")
来源：http://dali.aizwys.cn/Article/details/gt2vuckkiet.html

TS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkzchchb.html

Java: System.err.println("err")
来源：http://dali.snrcjt.cn/Article/details/gt2lwefrsuh.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yonumen.top/Article/details/gt2azdabacw.html

Ruby: warn "err"
来源：http://dali.hammf.cn/Article/details/gt2lsbmbewk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.xuetiantiany.cn/Article/details/gt2xzwxxufn.html

[M07] 判断是否为主入口
来源：http://dali.tianlin.xyz/Article/details/gt2tzirrkvf.html

Py:   if __name__ == "__main__":
来源：http://dali.feifeiyinyue.top/Article/details/gt2qsgxkqsk.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.aibaodan.cn/Article/details/gt2nlqpqebo.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gt2xcotbmad.html

TS:   require.main === module
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fnthvhbo.html

Java: public static void main(String[] args)
来源：http://dali.bjfxy.top/Article/details/gt2ftukeved.html

Go:   func main()
来源：http://dali.hysaishi.cn/Article/details/gt2aafdngsx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.birdmap.top/Article/details/gt2jtcbmayk.html

C#:   static void Main(string[] args)
来源：http://dali.nanxuanxn.top/Article/details/gt2tribqras.html

[M08] 获取系统与运行时信息
来源：http://dali.0kj1m.cn/Article/details/gt2tgwrhqie.html

Py:   platform.system();  platform.python_version()
来源：http://dali.daxiang520.top/Article/details/gt2xnpuyeac.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhengqikj.top/Article/details/gt2wrcyybru.html

JS:   process.platform;  process.version
来源：http://dali.wangshuangyany.cn/Article/details/gt2aoygcbkz.html

TS:   process.platform;  process.version
来源：http://dali.jiagoushi.top/Article/details/gt2kleifung.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xylfe.cn/Article/details/gt2slcnupcx.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.feifeiyinyue.top/Article/details/gt2kmhozyrx.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yonumen.top/Article/details/gt2zhqlmhhy.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yj202588.top/Article/details/gt2itjmqxqz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2kaommkwq.html

N. 数据结构与算法
来源：http://dali.haohaochexian.top/Article/details/gt2srdahcxe.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2qfnsnzdp.html

[N01] 二分查找（有序数组）
来源：http://dali.xziqi.cn/Article/details/gt2frdsgfhv.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2mjdxvyhc.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.cdnleiting.top/Article/details/gt2evwnbuhz.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.svipenyu.cn/Article/details/gt2hlvkxfew.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hammf.cn/Article/details/gt2gbxbntft.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yueranfly.top/Article/details/gt2iqnvecyq.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2wlfuybyv.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.zhengqikj.top/Article/details/gt2nghmpsid.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2iducuyfo.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.guowangkeji.top/Article/details/gt2avslatts.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj202588.top/Article/details/gt2clbekmng.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2afphxgvn.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rpffdzaz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.mhx1999.top/Article/details/gt2plzflffx.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jiagoushi.top/Article/details/gt2eixxycqq.html

Go:   slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gt2vpzynutv.html

Ruby: arr.sort
来源：http://dali.andypj.xyz/Article/details/gt2didgdqaf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zdqjudy.top/Article/details/gt2ezrflftg.html

[N03] 快速排序（分治示例）
来源：http://dali.snrcjt.cn/Article/details/gt2eltylvje.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.nanxinkj.top/Article/details/gt2mworlzrx.html

PHP:  // 递归实现，或用 usort
来源：http://dali.hysaishi.cn/Article/details/gt2vbbcgxce.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gt2qasduwqk.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.c1oappe.top/Article/details/gt2wukythdw.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.dashuyun.cn/Article/details/gt2xhkqxmxu.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.tanke756.top/Article/details/gt2nadfblfs.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.aizwys.cn/Article/details/gt2fybxdmvn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.hywenlv.cn/Article/details/gt2kydnykus.html

[N04] 斐波那契数列
来源：http://dali.havefunace.top/Article/details/gt2nqwmlolc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.guannengcc.top/Article/details/gt2xxhxahmn.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.yj20258888.top/Article/details/gt2yvnlrjoi.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.meibo888.top/Article/details/gt2bwywwagh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2dmdevjra.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xinyue.icu/Article/details/gt2wnwlhejz.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.andypj.xyz/Article/details/gt2youopvau.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gt2daljzcfl.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.gotoacloud.top/Article/details/gt2xgmtwiyc.html

[N05] 最大公约数
来源：http://dali.cashguo.top/Article/details/gt2ifgjaxuc.html

Py:   math.gcd(a, b)
来源：http://dali.cucudq.cn/Article/details/gt2jejgtihy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.hnxiangtu.top/Article/details/gt2qgjezqnp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gt2ezzyawrx.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cdnleiting.top/Article/details/gt2ioehlwxg.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jiagoushi.top/Article/details/gt2hiobcnuw.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zuwfvyyd.html

Ruby: a.gcd(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2sgezyhbd.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpnibwlq.html

[N06] 判断回文字符串
来源：http://dali.ydzc1.top/Article/details/gt2nyressgo.html

Py:   s == s[::-1]
来源：http://dali.jqgufenzy.top/Article/details/gt2neykafmc.html

PHP:  $s === strrev($s);
来源：http://dali.xuanzx.com/Article/details/gt2oazqlszz.html

JS:   s === [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2sletkbef.html

TS:   s === [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gt2kulxfrrg.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.cucudq.cn/Article/details/gt2siwrugxw.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jegszrlk.html

Ruby: s == s.reverse
来源：http://dali.nanxinkj.top/Article/details/gt2hduiiuxf.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.jqgufenzy.top/Article/details/gt2eajgvztw.html

[N07] 两数之和（返回下标）
来源：http://dali.cqqwz.cn/Article/details/gt2awyodmoz.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.guannengcc.top/Article/details/gt2oirczova.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.fzhhl.top/Article/details/gt2wytjykls.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yangfankeji.com/Article/details/gt2gkqmlnyp.html

TS:   // 手写 Map<string, number>
来源：http://dali.zhixingplan.top/Article/details/gt2jssfycqp.html

Java: // 手写 HashMap
来源：http://dali.xuanzx.com/Article/details/gt2ibueevhh.html

Go:   // 手写 map[int]int
来源：http://dali.xuanzx.com/Article/details/gt2pxxjdqzp.html

Ruby: // 手写 Hash
来源：http://dali.yangfankeji.com/Article/details/gt2wbladuwl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.ybcxt.top/Article/details/gt2savdcumm.html

[N08] 生成全排列
来源：http://dali.meibo888.top/Article/details/gt2xpajmeqv.html

Py:   itertools.permutations(arr)
来源：http://dali.ivvv.top/Article/details/gt2jtamoird.html

PHP:  // 手写递归交换
来源：http://dali.cqqwz.cn/Article/details/gt2fcuafdfz.html

JS:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gt2ptvmvekf.html

TS:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywjnwdur.html

Java: // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2enofuyel.html

Go:   // 手写回溯递归
来源：http://dali.316326.xyz/Article/details/gt2nyfgmtsc.html

Ruby: arr.permutation.to_a
来源：http://dali.gaohongyu789.top/Article/details/gt2vgfiesil.html

C#:   // 手写回溯递归
来源：http://dali.aizwys.cn/Article/details/gt2uzlouifd.html

[N09] 栈与队列
来源：http://dali.redwolf501.top/Article/details/gt2itkdjesy.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2yhxpvvtk.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pycfn.com/Article/details/gt2jgnqafnu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.dianchejie.cn/Article/details/gt2jhzccqsx.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jinqigufen.top/Article/details/gt2qppyzhcf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gt2tjzwdehx.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.hfpthk.cn/Article/details/gt2panccexd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.ehwqpu.com/Article/details/gt2xizwxqxd.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmpissgk.html

[N10] 链表节点定义
来源：http://dali.jlsjyb.cn/Article/details/gt2wxtlgliz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.daria6918.cn/Article/details/gt2vyftzrfc.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.quarkkingdee.top/Article/details/gt2xhsxntvi.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfqbiivu.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2skzofjbs.html

Java: class Node { int v; Node next; }
来源：http://dali.mhx1999.top/Article/details/gt2siidploa.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.gaohongyu789.top/Article/details/gt2temrvyhy.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.nanxinkj.top/Article/details/gt2dlhecqqg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuanzhike.top/Article/details/gt2pnnvkkkh.html

[N11] 二叉树中序遍历
来源：http://dali.nwbrower.top/Article/details/gt2zgercdmy.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.bjfxy.top/Article/details/gt2nenvsbrl.html

PHP:  // 手写递归函数
来源：http://dali.zhijiandao.cn/Article/details/gt2imnxuhxh.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.guowangkeji.top/Article/details/gt2opisxxzp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggcjyboj.html

Java: // 手写递归
来源：http://dali.xuanzx.com/Article/details/gt2rwlvhjpr.html

Go:   // 手写递归
来源：http://dali.gaohongyu789.top/Article/details/gt2lofyvxus.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gt2wibyypze.html

C#:   // 手写递归
来源：http://dali.yongpay.top/Article/details/gt2cdxikshx.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.sweek.top/Article/details/gt2dnnytduq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.9152youxi.cn/Article/details/gt2lchdhecs.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.haohaochexian.top/Article/details/gt2msankyxt.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuanzhike.top/Article/details/gt2kkmsvypm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nanxuanxn.top/Article/details/gt2yhzlewok.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.wangdashe.top/Article/details/gt2nzmbpxmn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mupgisvy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.hnxiangtu.top/Article/details/gt2eshecedp.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinqigufen.top/Article/details/gt2vcuzccyk.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2uzpzelbe.html

O. 并发与异步
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zsnbxdpq.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2zxziyczb.html

[O01] 启动一个线程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qtudkvvq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangshuangyany.cn/Article/details/gt2fimsolfp.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vxnqkten.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.bjfxy.top/Article/details/gt2pnmmpuxs.html

TS:   // 同 JS
来源：http://dali.nanxinkj.top/Article/details/gt2avdzolfd.html

Java: new Thread(() -> f()).start()
来源：http://dali.quarkkingdee.top/Article/details/gt2lovzltji.html

Go:   go f()
来源：http://dali.ybcxt.top/Article/details/gt2zesigjow.html

Ruby: Thread.new { f }
来源：http://dali.cheryme.top/Article/details/gt2sklbmsrr.html

C#:   Task.Run(() => F());
来源：http://dali.nwbrower.top/Article/details/gt2gzkcxicx.html

[O02] 使用线程池
来源：http://dali.yuanzhike.top/Article/details/gt2pzyvaeto.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.wangdashe.top/Article/details/gt2mtxvulfx.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.jqgufenzy.top/Article/details/gt2bepyarcl.html

JS:   // worker_threads 线程池
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxbgaudz.html

TS:   // worker_threads 线程池
来源：http://dali.kuanghao11.cn/Article/details/gt2jlxalqza.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.316326.xyz/Article/details/gt2miyigtxk.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkpmhvxz.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.hywenlv.cn/Article/details/gt2bypwqmbq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.smart0.xyz/Article/details/gt2idiyhqrw.html

[O03] 加锁保护共享数据
来源：http://dali.tanke756.top/Article/details/gt2yuibmcki.html

Py:   with lock: shared += 1
来源：http://dali.cashguo.top/Article/details/gt2hcsflvxz.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.andypj.xyz/Article/details/gt2xknkkcuh.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.hongshengwenyu.top/Article/details/gt2zvzkmixa.html

TS:   // 同 JS
来源：http://dali.yanxiufei.cn/Article/details/gt2tdbnyaqt.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ngqdjilw.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.aibaodan.cn/Article/details/gt2wajaczmq.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bwgmqicz.html

C#:   lock (gate) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gt2igxumltx.html

[O04] 定义异步函数并等待
来源：http://dali.mhx1999.top/Article/details/gt2apfvcatf.html

Py:   async def f():⏎    await g()
来源：http://dali.daria6918.cn/Article/details/gt2qonlkyxw.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.mhx1999.top/Article/details/gt2pjucttuw.html

JS:   async function f() { await g(); }
来源：http://dali.yj202588.top/Article/details/gt2ehfjuuod.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2vikwtqyt.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.yj20258888.top/Article/details/gt2uhtoynki.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.aibaodan.cn/Article/details/gt2wmjjjpiw.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.gogol.net.cn/Article/details/gt2tqfzetgv.html

C#:   async Task F() { await G(); }
来源：http://dali.aibaodan.cn/Article/details/gt2nwxpphbe.html

[O05] 并发执行并等待全部完成
来源：http://dali.andypj.xyz/Article/details/gt2tizufxkd.html

Py:   asyncio.gather(*tasks)
来源：http://dali.nwbrower.top/Article/details/gt2xlwbpwoz.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.sxryk.cn/Article/details/gt2ysxscznw.html

JS:   await Promise.all(tasks)
来源：http://dali.fengsongda.top/Article/details/gt2ejatetmw.html

TS:   await Promise.all(tasks)
来源：http://dali.316326.xyz/Article/details/gt2evvzchdy.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.dashuyun.cn/Article/details/gt2dlfxrtnj.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.sysykeji.top/Article/details/gt2xqfvijlr.html

Ruby: threads.map(&:join)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhbhziii.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yongpay.top/Article/details/gt2usvziuly.html

[O06] 使用进程池
来源：http://dali.birdmap.top/Article/details/gt2nbavdtuf.html

Py:   concurrent.futures.ProcessPoolExecutor()
来源：http://dali.zycfv.cn/Article/details/gt2avgbyqbc.html

PHP:  // pcntl_fork 或多进程队列
来源：http://dali.vqdsnc.cn/Article/details/gt2dnpudxuj.html

JS:   // child_process / cluster 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tspssqup.html

TS:   // child_process / cluster 模块
来源：http://dali.daxiang520.top/Article/details/gt2okbxwbud.html

Java: // ForkJoinPool 或 ProcessBuilder
来源：http://dali.dashuyun.cn/Article/details/gt2dsbmtikm.html

Go:   // goroutine 已占用多核，直接并发即可
来源：http://dali.yangfankeji.com/Article/details/gt2celnybiw.html

Ruby: // fork 块
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvbmlbmo.html

C#:   Parallel.For
来源：http://dali.yanxiufei.cn/Article/details/gt2ujyusdsm.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eqyoftjm.html

P. 常用工具函数
来源：http://dali.hammf.cn/Article/details/gt2xyqklvfg.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2gggtxdhz.html

[P01] 生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gt2mkulazqi.html

Py:   str(uuid.uuid4())
来源：http://dali.hammf.cn/Article/details/gt2tbdihnkt.html

PHP:  bin2hex(random_bytes(16));        // 或 ramsey/uuid
来源：http://dali.cdnleiting.top/Article/details/gt2fmbjmisg.html

JS:   crypto.randomUUID()
来源：http://dali.cqqwz.cn/Article/details/gt2xdhwdpqm.html

TS:   crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lkkrahds.html

Java: UUID.randomUUID().toString()
来源：http://dali.sufxvd.cn/Article/details/gt2shciupjo.html

Go:   // 用 github.com/google/uuid
来源：http://dali.nanxuanxn.top/Article/details/gt2ciohiwpd.html

Ruby: SecureRandom.uuid
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hrtrquyq.html


<!-- 参考信息 -->