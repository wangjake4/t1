代发 wailian999

Go:   encoding/gob
来源：http://dali.0kj1m.cn/Article/details/gt2ztgailmn.html

Ruby: Marshal.dump(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2bfiuhnsi.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.jqgufenzy.top/Article/details/gt2wuzbxtru.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odugnooz.html

L. 网络请求
来源：http://dali.svipenyu.cn/Article/details/gt2rclhdkhc.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2mkeracke.html

[L01] 发送 GET 请求
来源：http://dali.wangdashe.top/Article/details/gt2kfmaaudm.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yueranfly.top/Article/details/gt2ogypgbcw.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daria6918.cn/Article/details/gt2sblbbcix.html

JS:   await fetch(url)
来源：http://dali.jlsjyb.cn/Article/details/gt2jjhkxfxu.html

TS:   await fetch(url)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eyeiqwqp.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnqzz.top/Article/details/gt2dkstfzbb.html

Go:   resp, err := http.Get(url)
来源：http://dali.ppjwa.cn/Article/details/gt2qjslrngv.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgqcosxq.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.andypj.xyz/Article/details/gt2syhjmehd.html

[L02] 发送 POST JSON
来源：http://dali.yangfankeji.com/Article/details/gt2kexwmynh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shuidangran.top/Article/details/gt2jnyjtykh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.birdmap.top/Article/details/gt2uvlrcvzy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.chenjidiqi.icu/Article/details/gt2nacozihu.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ygezoqjq.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2btvgaazl.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gogol.net.cn/Article/details/gt2mpbjpjux.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xziqi.cn/Article/details/gt2vgqczcqt.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.snrcjt.cn/Article/details/gt2jbtoewkj.html

[L03] 设置自定义请求头
来源：http://dali.hongshengwenyu.top/Article/details/gt2xmmybcxn.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.guannengcc.top/Article/details/gt2vkhwfrbf.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.nwbrower.top/Article/details/gt2wdthbfpg.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cheryme.top/Article/details/gt2dnowiihb.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fedsopff.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.gotoacloud.top/Article/details/gt2vpinincl.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gt2ouprnihd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yanxiufei.cn/Article/details/gt2oxajlixx.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.0kj1m.cn/Article/details/gt2asojfsbx.html

[L04] 设置超时
来源：http://dali.yuanzhike.top/Article/details/gt2xhmpnjba.html

Py:   requests.get(url, timeout=5)
来源：http://dali.chenzaomai.com/Article/details/gt2qxulsxnc.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2akdaplfp.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gt2ewwcitef.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhcxpty.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jyoumei.cn/Article/details/gt2kossrzfk.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.quarkkingdee.top/Article/details/gt2iogcrlzq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.sxryk.cn/Article/details/gt2pfdpootc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.cdnleiting.top/Article/details/gt2wzjnkmqu.html

[L05] 上传文件（multipart）
来源：http://dali.hongshengwenyu.top/Article/details/gt2roiavcch.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.hywenlv.cn/Article/details/gt2wwtbfklh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.aibaodan.cn/Article/details/gt2wfkmkrqp.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gt2zpemluhd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhixingplan.top/Article/details/gt2vhdkivve.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xylfe.cn/Article/details/gt2znlhmdzt.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.yj20258888.top/Article/details/gt2buqfhpnv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrwftdt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2zgedkapz.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gt2rdmtzyqx.html

Py:   resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2lirouijj.html

PHP:  json_decode($body, true);
来源：http://dali.chenzaomai.com/Article/details/gt2dlqmiulh.html

JS:   await resp.json()
来源：http://dali.xuetiantiany.cn/Article/details/gt2dtfkimfm.html

TS:   await resp.json()
来源：http://dali.snrcjt.cn/Article/details/gt2twmyomtd.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.hysaishi.cn/Article/details/gt2dmbogaqz.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.meibo888.top/Article/details/gt2lslsdgwy.html

Ruby: JSON.parse(resp.body)
来源：http://dali.daria6918.cn/Article/details/gt2ttewiszj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpshzhxu.html

[L07] 处理 HTTP 状态码
来源：http://dali.ybcxt.top/Article/details/gt2fulkufee.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gt2aghhljsm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmdqebjr.html

JS:   resp.ok;  resp.status
来源：http://dali.tanke756.top/Article/details/gt2yyjgjvea.html

TS:   resp.ok;  resp.status
来源：http://dali.sysykeji.top/Article/details/gt2qvjzcxsb.html

Java: resp.statusCode()
来源：http://dali.aibaodan.cn/Article/details/gt2dbqasepd.html

Go:   resp.StatusCode
来源：http://dali.wangshuangyany.cn/Article/details/gt2cpxeswtn.html

Ruby: resp.code.to_i
来源：http://dali.mhx1999.top/Article/details/gt2gdpcnwcy.html

C#:   (int)resp.StatusCode
来源：http://dali.hnqzz.top/Article/details/gt2gvngokft.html

[L08] 并发请求多个地址
来源：http://dali.yj202588.top/Article/details/gt2eyouphta.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.cqqwz.cn/Article/details/gt2ivhxslev.html

PHP:  curl_multi_init() 系列
来源：http://dali.feifeiyinyue.top/Article/details/gt2aojgzdrj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gt2bgpznxgr.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.redwolf501.top/Article/details/gt2ortksunq.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nanxinkj.top/Article/details/gt2efhdmzta.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.zhixingplan.top/Article/details/gt2aynlpyhu.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.chenzaomai.com/Article/details/gt2wqwcgygq.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yonumen.top/Article/details/gt2kfboqkbl.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2wkybmmvs.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxuanxn.top/Article/details/gt2ddfycxln.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2vvgsmotl.html

[M01] 读取命令行参数
来源：http://dali.ybcxt.top/Article/details/gt2gjjgrqad.html

Py:   sys.argv[1:]
来源：http://dali.yonumen.top/Article/details/gt2nassjglq.html

PHP:  $argv;  $argc;
来源：http://dali.zhoulong.xyz/Article/details/gt2leumpklj.html

JS:   process.argv.slice(2)
来源：http://dali.hysaishi.cn/Article/details/gt2akyscehx.html

TS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gt2fupxgvkh.html

Java: args 数组（main 方法参数）
来源：http://dali.hywenlv.cn/Article/details/gt2ugghczij.html

Go:   os.Args[1:]
来源：http://dali.jinqigfzy.top/Article/details/gt2ogxvaguj.html

Ruby: ARGV
来源：http://dali.zhongyouzk.top/Article/details/gt2fvhniapf.html

C#:   args 数组（Main 方法参数）
来源：http://dali.0kj1m.cn/Article/details/gt2onbfvxdt.html

[M02] 读取环境变量
来源：http://dali.jinqigfzy.top/Article/details/gt2lidpldhf.html

Py:   os.environ.get("HOME")
来源：http://dali.zhixingplan.top/Article/details/gt2jhtxafxx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uovkbgpw.html

JS:   process.env.HOME
来源：http://dali.nanxinkj.top/Article/details/gt2jctlejxa.html

TS:   process.env.HOME
来源：http://dali.yuxming.cn/Article/details/gt2mhceifew.html

Java: System.getenv("HOME")
来源：http://dali.nanxinkj.top/Article/details/gt2iluicscz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hnqzz.top/Article/details/gt2avvnsmol.html

Ruby: ENV["HOME"]
来源：http://dali.zhoulong.xyz/Article/details/gt2mnmncypx.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shangyingyoupin.top/Article/details/gt2lydncgmg.html

[M03] 执行外部命令
来源：http://dali.haohaochexian.top/Article/details/gt2iiheivke.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.aibaodan.cn/Article/details/gt2yhtuuedp.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ppjwa.cn/Article/details/gt2uavkjoxx.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.daria6918.cn/Article/details/gt2vahntlec.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gt2ulzqbwms.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.c1oappe.top/Article/details/gt2ctxurhbh.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.tian-w.cn/Article/details/gt2qqfwkmce.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.cucudq.cn/Article/details/gt2pavtvcpe.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xinyue.icu/Article/details/gt2jlelngfl.html

[M04] 获取当前工作目录
来源：http://dali.yj20258.top/Article/details/gt2bmkwxnsa.html

Py:   os.getcwd()
来源：http://dali.jyoumei.cn/Article/details/gt2oahazipj.html

PHP:  getcwd();
来源：http://dali.xuetiantiany.cn/Article/details/gt2hcwmunzz.html

JS:   process.cwd()
来源：http://dali.jinqigfzy.top/Article/details/gt2hiwsukjk.html

TS:   process.cwd()
来源：http://dali.redwolf501.top/Article/details/gt2bftjqjtx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zdqjudy.top/Article/details/gt2zznssypp.html

Go:   os.Getwd()
来源：http://dali.cqqwz.cn/Article/details/gt2zfmrxmun.html

Ruby: Dir.pwd
来源：http://dali.cheryme.top/Article/details/gt2zmjjogxp.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.jianghu66.top/Article/details/gt2uddbfzjb.html

[M05] 设置退出码
来源：http://dali.smart0.xyz/Article/details/gt2asjgljvz.html

Py:   sys.exit(1)
来源：http://dali.gzhubu.top/Article/details/gt2xiozzhvg.html

PHP:  exit(1);
来源：http://dali.redwolf501.top/Article/details/gt2vmroctuu.html

JS:   process.exit(1)
来源：http://dali.yvedp.cn/Article/details/gt2brfjfnsc.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2rqnmpjyw.html

Java: System.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2jzsirnbu.html

Go:   os.Exit(1)
来源：http://dali.dianchejie.cn/Article/details/gt2ntvlezzx.html

Ruby: exit 1
来源：http://dali.smart0.xyz/Article/details/gt2haaldqlr.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.gzhubu.top/Article/details/gt2fyqyldem.html

[M06] 向标准错误输出
来源：http://dali.gogol.net.cn/Article/details/gt2gawelprd.html

Py:   print("err", file=sys.stderr)
来源：http://dali.nanxuanxn.top/Article/details/gt2imspdcie.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.guannengcc.top/Article/details/gt2tjdflrtk.html

JS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gt2fevkrvxy.html

TS:   console.error("err")
来源：http://dali.dianchejie.cn/Article/details/gt2lewqwdes.html

Java: System.err.println("err")
来源：http://dali.tianlin.xyz/Article/details/gt2ywpbrmjs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.hammf.cn/Article/details/gt2zawgqrcy.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gt2ptrhporo.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.quarkkingdee.top/Article/details/gt2elhivzrs.html

[M07] 判断是否为主入口
来源：http://dali.zhoulong.xyz/Article/details/gt2guupsxnw.html

Py:   if __name__ == "__main__":
来源：http://dali.jianghu66.top/Article/details/gt2jpkfpuac.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.xuanzx.com/Article/details/gt2vwkzfndt.html

JS:   require.main === module
来源：http://dali.yj20258.top/Article/details/gt2ezyomnku.html

TS:   require.main === module
来源：http://dali.daria6918.cn/Article/details/gt2jdesdczk.html

Java: public static void main(String[] args)
来源：http://dali.zhijiandao.cn/Article/details/gt2bffzqelq.html

Go:   func main()
来源：http://dali.hywenlv.cn/Article/details/gt2rmjrekpe.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.yj202588.top/Article/details/gt2auivtuqw.html

C#:   static void Main(string[] args)
来源：http://dali.aizwys.cn/Article/details/gt2mzupebbe.html

[M08] 获取系统与运行时信息
来源：http://dali.snrcjt.cn/Article/details/gt2pofjzvvw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jqgfzy.top/Article/details/gt2ftgjsvpk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.andypj.xyz/Article/details/gt2ezhnzzdy.html

JS:   process.platform;  process.version
来源：http://dali.aizwys.cn/Article/details/gt2jmkfhcjq.html

TS:   process.platform;  process.version
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yaeewpnz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.pycfn.com/Article/details/gt2rnoajxyg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yueranfly.top/Article/details/gt2mwcwbyzk.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinqigufen.top/Article/details/gt2apqnzduw.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.nanxinkj.top/Article/details/gt2wcthhopj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2ikxcjeyk.html

N. 数据结构与算法
来源：http://dali.gzhubu.top/Article/details/gt2nxolrktd.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2btfploge.html

[N01] 二分查找（有序数组）
来源：http://dali.smart0.xyz/Article/details/gt2yqrxvbub.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.cqqwz.cn/Article/details/gt2isatfblb.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.chenjidiqi.icu/Article/details/gt2iaoqutgw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2ktxasewn.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhwemywk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqwhtpll.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2wlnxhzmh.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.yj20258888.top/Article/details/gt2iecrpobl.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2jzhqxggw.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ybcxt.top/Article/details/gt2qlvsmgkc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zycfv.cn/Article/details/gt2woddrllv.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhengqikj.top/Article/details/gt2nbyvvgul.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yywifuyt.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jlsjyb.cn/Article/details/gt2lurnvykr.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.yangfankeji.com/Article/details/gt2xrcbtiua.html

Go:   slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gt2abcxogpd.html

Ruby: arr.sort
来源：http://dali.xinyue.icu/Article/details/gt2cgkalwbo.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gt2vzbzalgw.html

[N03] 快速排序（分治示例）
来源：http://dali.sysykeji.top/Article/details/gt2bsaqwfdd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.gogol.net.cn/Article/details/gt2uhludvhm.html

PHP:  // 递归实现，或用 usort
来源：http://dali.yongpay.top/Article/details/gt2sjkwujlt.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gt2vnyqefjr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yangfankeji.com/Article/details/gt2ojvlrcdc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.nanxinkj.top/Article/details/gt2kbyexdxi.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khdobpxi.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yanxiufei.cn/Article/details/gt2flquoiju.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihdwvhyr.html

[N04] 斐波那契数列
来源：http://dali.jqgfzy.top/Article/details/gt2tfsjnpls.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2bgntyppc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shzxlz.cn/Article/details/gt2tchqzhwj.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gt2rifnvlgg.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.tianlin.xyz/Article/details/gt2nmzsxpgv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnqzz.top/Article/details/gt2pyejksxv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.dashuyun.cn/Article/details/gt2terpnvgp.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.zdqjudy.top/Article/details/gt2cclwshet.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gt2koejjabh.html

[N05] 最大公约数
来源：http://dali.cqqwz.cn/Article/details/gt2uvjzqxhu.html

Py:   math.gcd(a, b)
来源：http://dali.yangfankeji.com/Article/details/gt2hketgvvv.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aizwys.cn/Article/details/gt2ppvcmifn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jyoumei.cn/Article/details/gt2xlonlwao.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gt2svkpcutu.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.aibaodan.cn/Article/details/gt2wukexxtp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.hnxiangtu.top/Article/details/gt2tpxslrje.html

Ruby: a.gcd(b)
来源：http://dali.ybcxt.top/Article/details/gt2dxmeifyw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2csafivil.html

[N06] 判断回文字符串
来源：http://dali.tian-w.cn/Article/details/gt2uftuqhqi.html

Py:   s == s[::-1]
来源：http://dali.ehwqpu.com/Article/details/gt2rkmoaocb.html

PHP:  $s === strrev($s);
来源：http://dali.ppjwa.cn/Article/details/gt2clnlymag.html

JS:   s === [...s].reverse().join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2vhtfszdb.html

TS:   s === [...s].reverse().join("")
来源：http://dali.9152youxi.cn/Article/details/gt2ceyzjasn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xylfe.cn/Article/details/gt2girukxju.html

Go:   // 双指针从两端比较
来源：http://dali.yj202588.top/Article/details/gt2ursonznv.html

Ruby: s == s.reverse
来源：http://dali.jinqigfzy.top/Article/details/gt2vmljmiwq.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.nanxinkj.top/Article/details/gt2tkuaqzgu.html

[N07] 两数之和（返回下标）
来源：http://dali.havefunace.top/Article/details/gt2sjydzrsh.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.cqqwz.cn/Article/details/gt2paqimqvs.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gotoacloud.top/Article/details/gt2sfojqilj.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.fengsongda.top/Article/details/gt2uqzeghvu.html

TS:   // 手写 Map<string, number>
来源：http://dali.smart0.xyz/Article/details/gt2cslibhsb.html

Java: // 手写 HashMap
来源：http://dali.xinyue.icu/Article/details/gt2uavzzpvu.html

Go:   // 手写 map[int]int
来源：http://dali.xylfe.cn/Article/details/gt2zbnhaank.html

Ruby: // 手写 Hash
来源：http://dali.zycfv.cn/Article/details/gt2zjcgjiyj.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.xuetiantiany.cn/Article/details/gt2edslrnxp.html

[N08] 生成全排列
来源：http://dali.gogol.net.cn/Article/details/gt2qhpdwpxx.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gt2febxcwlx.html

PHP:  // 手写递归交换
来源：http://dali.yonumen.top/Article/details/gt2qrmaxxre.html

JS:   // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jukzawtd.html

TS:   // 手写回溯递归
来源：http://dali.jqgufenzy.top/Article/details/gt2wmvoamgs.html

Java: // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2bzpygtht.html

Go:   // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2mtmwvygq.html

Ruby: arr.permutation.to_a
来源：http://dali.zhoulong.xyz/Article/details/gt2qkuptopx.html

C#:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2qqhukizz.html

[N09] 栈与队列
来源：http://dali.zhoulong.xyz/Article/details/gt2poctrlly.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zycfv.cn/Article/details/gt2ynjqiers.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.pycfn.com/Article/details/gt2pvzqhouq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.iojbl.cn/Article/details/gt2laescsep.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nwbrower.top/Article/details/gt2epbbnzxl.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.sweek.top/Article/details/gt2clbhfsni.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cashguo.top/Article/details/gt2vjkilqga.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.tanke756.top/Article/details/gt2rpgzzhue.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.xziqi.cn/Article/details/gt2yhhcsllq.html

[N10] 链表节点定义
来源：http://dali.meibo888.top/Article/details/gt2rtottoax.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.cashguo.top/Article/details/gt2gklzaodp.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gt2vmqwpswt.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.zycfv.cn/Article/details/gt2ndypyrfl.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gt2pbsrdwkq.html

Java: class Node { int v; Node next; }
来源：http://dali.sxryk.cn/Article/details/gt2piqbswka.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.aizwys.cn/Article/details/gt2vvulrldg.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.jlsjyb.cn/Article/details/gt2zvjjohfz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.tianlin.xyz/Article/details/gt2grhbcfhl.html

[N11] 二叉树中序遍历
来源：http://dali.pycfn.com/Article/details/gt2xqtsvhpn.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.yonumen.top/Article/details/gt2uiexppis.html

PHP:  // 手写递归函数
来源：http://dali.jianghu66.top/Article/details/gt2anwdrsjv.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.sweek.top/Article/details/gt2aenfqfaz.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gotoacloud.top/Article/details/gt2hzrvgpqv.html

Java: // 手写递归
来源：http://dali.cheryme.top/Article/details/gt2lusaugbb.html

Go:   // 手写递归
来源：http://dali.yangfankeji.com/Article/details/gt2rtgojoqe.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.ydzc1.top/Article/details/gt2fnmrhwop.html

C#:   // 手写递归
来源：http://dali.pengpengdd.cyou/Article/details/gt2znltxzcv.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.haohaochexian.top/Article/details/gt2nbckdxpl.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.mhx1999.top/Article/details/gt2efxxifrj.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zhiwuduotai.top/Article/details/gt2osbhahbi.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.aizwys.cn/Article/details/gt2ucfawghu.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigfzy.top/Article/details/gt2rbnumnqa.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.gaohongyu789.top/Article/details/gt2ardnhrrc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.tianlin.xyz/Article/details/gt2icdsfcos.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zycfv.cn/Article/details/gt2xcvsrqcs.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.sxryk.cn/Article/details/gt2wdlivbth.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2hheeblof.html

O. 并发与异步
来源：http://dali.chenjidiqi.icu/Article/details/gt2oabpsnec.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2rsywoqds.html

[O01] 启动一个线程
来源：http://dali.chenjidiqi.icu/Article/details/gt2akjbwerr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ltbrgjuu.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.chenlongwang.top/Article/details/gt2jrbvyknt.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.snrcjt.cn/Article/details/gt2sijedsml.html

TS:   // 同 JS
来源：http://dali.cdnleiting.top/Article/details/gt2zzaksiyc.html

Java: new Thread(() -> f()).start()
来源：http://dali.aibaodan.cn/Article/details/gt2iooyivyg.html

Go:   go f()
来源：http://dali.xziqi.cn/Article/details/gt2wfuferft.html

Ruby: Thread.new { f }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qtmxvzks.html

C#:   Task.Run(() => F());
来源：http://dali.meibo888.top/Article/details/gt2vlekeqqy.html

[O02] 使用线程池
来源：http://dali.jlsjyb.cn/Article/details/gt2qqsudfyc.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.0kj1m.cn/Article/details/gt2lylrflzt.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.smart0.xyz/Article/details/gt2oviwujmj.html

JS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2fnpzazfu.html

TS:   // worker_threads 线程池
来源：http://dali.pengpengdd.cyou/Article/details/gt2brgjzswi.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.cdnleiting.top/Article/details/gt2yunbvbbd.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.yongpay.top/Article/details/gt2mxvciktr.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ixkuudoq.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.xziqi.cn/Article/details/gt2qdafbsns.html

[O03] 加锁保护共享数据
来源：http://dali.gogol.net.cn/Article/details/gt2qddefxae.html

Py:   with lock: shared += 1
来源：http://dali.yongpay.top/Article/details/gt2tgxkrccs.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.haohaochexian.top/Article/details/gt2lhwvbyje.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.0kj1m.cn/Article/details/gt2iuuxnkld.html

TS:   // 同 JS
来源：http://dali.zycfv.cn/Article/details/gt2etemsxcu.html

Java: synchronized (this) { shared++; }
来源：http://dali.chenlongwang.top/Article/details/gt2eaykbdaf.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.kuanghao11.cn/Article/details/gt2frgozzal.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.dianchejie.cn/Article/details/gt2jtlgjdfz.html

C#:   lock (gate) { shared++; }
来源：http://dali.ybcxt.top/Article/details/gt2zpbgkvxt.html

[O04] 定义异步函数并等待
来源：http://dali.nwbrower.top/Article/details/gt2ugzjbweb.html

Py:   async def f():⏎    await g()
来源：http://dali.0kj1m.cn/Article/details/gt2tunzjgsh.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.sweek.top/Article/details/gt2ccezdijj.html

JS:   async function f() { await g(); }
来源：http://dali.mhx1999.top/Article/details/gt2ybapfvzp.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.tianlin.xyz/Article/details/gt2oatogtmw.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntidlkky.html


<!-- 参考信息 -->