代发 wailian999

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.cashguo.top/Article/details/gt2xaqiyins.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2lhpflbrg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2apxuipnj.html

Py:   pickle.dumps(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlubwzjz.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gt2whmustcr.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.tian-w.cn/Article/details/gt2odanwwvw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.nanxuanxn.top/Article/details/gt2wwoulmtc.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yonumen.top/Article/details/gt2rryilcex.html

Go:   encoding/gob
来源：http://dali.yangfankeji.com/Article/details/gt2ufmbgfma.html

Ruby: Marshal.dump(obj)
来源：http://dali.cqqwz.cn/Article/details/gt2qbdqfzfo.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.quarkkingdee.top/Article/details/gt2ekrjgino.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2pomdxgru.html

L. 网络请求
来源：http://dali.yonumen.top/Article/details/gt2ilgkaqxu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2xdbypuzt.html

[L01] 发送 GET 请求
来源：http://dali.gotoacloud.top/Article/details/gt2ugincxgw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.svipenyu.cn/Article/details/gt2litdstyg.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.havefunace.top/Article/details/gt2vtkilwle.html

JS:   await fetch(url)
来源：http://dali.xylfe.cn/Article/details/gt2kxstxvxn.html

TS:   await fetch(url)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2imulsihz.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.guowangkeji.top/Article/details/gt2ghjdamfw.html

Go:   resp, err := http.Get(url)
来源：http://dali.hfpthk.cn/Article/details/gt2aevcpqmh.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.tanke756.top/Article/details/gt2xzqzgdzj.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.chenjidiqi.icu/Article/details/gt2laygaqpk.html

[L02] 发送 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gt2ipjqomhh.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.smart0.xyz/Article/details/gt2isnssdov.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.smart0.xyz/Article/details/gt2ghjsyety.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.nanxuanxn.top/Article/details/gt2gupvpbac.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gt2vegmpnhp.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinqigufen.top/Article/details/gt2yntztvtq.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gaohongyu789.top/Article/details/gt2aoldnekp.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.andypj.xyz/Article/details/gt2rjksqdon.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.hywenlv.cn/Article/details/gt2lihbzhzo.html

[L03] 设置自定义请求头
来源：http://dali.gogol.net.cn/Article/details/gt2mgdwgxks.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhongyouzk.top/Article/details/gt2eswrqznq.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.andypj.xyz/Article/details/gt2sgopcjuz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gaohongyu789.top/Article/details/gt2ibaabafn.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.tianlin.xyz/Article/details/gt2rfenofkg.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258888.top/Article/details/gt2bcuetvbu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.yuanzhike.top/Article/details/gt2rszxhfdr.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nztlpyev.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.ppjwa.cn/Article/details/gt2uvyyxhes.html

[L04] 设置超时
来源：http://dali.xziqi.cn/Article/details/gt2ihxxrjvl.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sxryk.cn/Article/details/gt2coeuugue.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.kuanghao11.cn/Article/details/gt2cortvbqr.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ppjwa.cn/Article/details/gt2tltuunpi.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gt2dhmneoau.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.guowangkeji.top/Article/details/gt2fadafllz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ydzc1.top/Article/details/gt2vyhsckyi.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfwgoquc.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jyoumei.cn/Article/details/gt2tojvdmxn.html

[L05] 上传文件（multipart）
来源：http://dali.9152youxi.cn/Article/details/gt2lngrrgvj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.daria6918.cn/Article/details/gt2xezsmbvh.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj202588.top/Article/details/gt2orhtkngl.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.cdnleiting.top/Article/details/gt2vhpiburp.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.guannengcc.top/Article/details/gt2olwndqdn.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hywenlv.cn/Article/details/gt2tqmhuela.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.dianchejie.cn/Article/details/gt2iasmmjed.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.jqgfzy.top/Article/details/gt2onhvoyhb.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2qaifwxqc.html

[L06] 解析响应为 JSON
来源：http://dali.zhengqikj.top/Article/details/gt2tjnrnebx.html

Py:   resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gt2lhzzjkki.html

PHP:  json_decode($body, true);
来源：http://dali.sweek.top/Article/details/gt2zyfqrxob.html

JS:   await resp.json()
来源：http://dali.ydzc1.top/Article/details/gt2hcvskoci.html

TS:   await resp.json()
来源：http://dali.xziqi.cn/Article/details/gt2sfdltrmp.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sexumgqc.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.redwolf501.top/Article/details/gt2mxvfwmsl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.jqgfzy.top/Article/details/gt2qjcejnct.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.jlsjyb.cn/Article/details/gt2wnvfgxvd.html

[L07] 处理 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gt2qyzujxxv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2miuzfxmh.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gt2olqkgqoc.html

JS:   resp.ok;  resp.status
来源：http://dali.xylfe.cn/Article/details/gt2wkrfhenx.html

TS:   resp.ok;  resp.status
来源：http://dali.9152youxi.cn/Article/details/gt2xsunsneq.html

Java: resp.statusCode()
来源：http://dali.yangfankeji.com/Article/details/gt2ehghjeeh.html

Go:   resp.StatusCode
来源：http://dali.cdnleiting.top/Article/details/gt2ukcubrph.html

Ruby: resp.code.to_i
来源：http://dali.nanxuanxn.top/Article/details/gt2iolcwlil.html

C#:   (int)resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gt2rvjcabtq.html

[L08] 并发请求多个地址
来源：http://dali.kuanghao11.cn/Article/details/gt2ansqsjnt.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xuanzx.com/Article/details/gt2tunggsqa.html

PHP:  curl_multi_init() 系列
来源：http://dali.meibo888.top/Article/details/gt2wfduyajc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.guowangkeji.top/Article/details/gt2flheljsf.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gt2sjpofjmx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.vqdsnc.cn/Article/details/gt2nirtiwse.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zeqwpewm.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.ehwqpu.com/Article/details/gt2xiqxvmgw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cashguo.top/Article/details/gt2jwnzwytl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2gyvyjepr.html

M. 命令行 / 进程 / 环境
来源：http://dali.pengpengdd.cyou/Article/details/gt2iekjwljw.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2qecpuiug.html

[M01] 读取命令行参数
来源：http://dali.dashuyun.cn/Article/details/gt2zrihnrwa.html

Py:   sys.argv[1:]
来源：http://dali.ppjwa.cn/Article/details/gt2qassykis.html

PHP:  $argv;  $argc;
来源：http://dali.zhongyouzk.top/Article/details/gt2wjurrrnp.html

JS:   process.argv.slice(2)
来源：http://dali.yuxming.cn/Article/details/gt2vulkquuq.html

TS:   process.argv.slice(2)
来源：http://dali.xziqi.cn/Article/details/gt2bmojobld.html

Java: args 数组（main 方法参数）
来源：http://dali.birdmap.top/Article/details/gt2nxjrxygw.html

Go:   os.Args[1:]
来源：http://dali.gzhubu.top/Article/details/gt2ilduuzuz.html

Ruby: ARGV
来源：http://dali.wangdashe.top/Article/details/gt2hwjymvzw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.shzxlz.cn/Article/details/gt2dbziqjex.html

[M02] 读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gt2ptbohubn.html

Py:   os.environ.get("HOME")
来源：http://dali.hongshengwenyu.top/Article/details/gt2fyttvmpx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gt2evqfosyb.html

JS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gt2yieknyib.html

TS:   process.env.HOME
来源：http://dali.yvedp.cn/Article/details/gt2ycgkzyfw.html

Java: System.getenv("HOME")
来源：http://dali.yueranfly.top/Article/details/gt2gqrsugmd.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xinyue.icu/Article/details/gt2yqwgpmqt.html

Ruby: ENV["HOME"]
来源：http://dali.yvedp.cn/Article/details/gt2njvcxlpq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.yuxming.cn/Article/details/gt2gdylfufi.html

[M03] 执行外部命令
来源：http://dali.hammf.cn/Article/details/gt2atwkldxv.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.smart0.xyz/Article/details/gt2ziwzipbt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenlongwang.top/Article/details/gt2wkwpeufo.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.dianchejie.cn/Article/details/gt2owksfhqo.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.svipenyu.cn/Article/details/gt2ntymtwrs.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gt2nnwrwlxm.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhixingplan.top/Article/details/gt2ewxlshca.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.yuanzhike.top/Article/details/gt2wjmkxubp.html

C#:   Process.Start("ls", "-l");
来源：http://dali.aibaodan.cn/Article/details/gt2bqdqqees.html

[M04] 获取当前工作目录
来源：http://dali.haohaochexian.top/Article/details/gt2kcotjsfk.html

Py:   os.getcwd()
来源：http://dali.yanxiufei.cn/Article/details/gt2ozwcjfbg.html

PHP:  getcwd();
来源：http://dali.c1oappe.top/Article/details/gt2zmqmtzyx.html

JS:   process.cwd()
来源：http://dali.sweek.top/Article/details/gt2pckmkkzs.html

TS:   process.cwd()
来源：http://dali.tianlin.xyz/Article/details/gt2sjzqnrih.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.guowangkeji.top/Article/details/gt2ynwahpzf.html

Go:   os.Getwd()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qznfluxt.html

Ruby: Dir.pwd
来源：http://dali.shangyingyoupin.top/Article/details/gt2ippcgieh.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.cqqwz.cn/Article/details/gt2axorgrsi.html

[M05] 设置退出码
来源：http://dali.zhijiandao.cn/Article/details/gt2ayuauduw.html

Py:   sys.exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2bxauijgp.html

PHP:  exit(1);
来源：http://dali.jiagoushi.top/Article/details/gt2opfcnzyu.html

JS:   process.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2zhlqwail.html

TS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2xdqzipcp.html

Java: System.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ncjudjiv.html

Go:   os.Exit(1)
来源：http://dali.zycfv.cn/Article/details/gt2gxdhonqh.html

Ruby: exit 1
来源：http://dali.zhixingplan.top/Article/details/gt2mgzmcwsz.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.bjfxy.top/Article/details/gt2xnicrlka.html

[M06] 向标准错误输出
来源：http://dali.kuanghao11.cn/Article/details/gt2ylvunzbg.html

Py:   print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ermjgwry.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tmqdjcmr.html

JS:   console.error("err")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hiuuissw.html

TS:   console.error("err")
来源：http://dali.yongpay.top/Article/details/gt2hvujgnpb.html

Java: System.err.println("err")
来源：http://dali.yj20258888.top/Article/details/gt2xeitgxte.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.dianchejie.cn/Article/details/gt2ybybljtv.html

Ruby: warn "err"
来源：http://dali.xuetiantiany.cn/Article/details/gt2karzpvyd.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.svipenyu.cn/Article/details/gt2ulovpczi.html

[M07] 判断是否为主入口
来源：http://dali.sxryk.cn/Article/details/gt2aydtngon.html

Py:   if __name__ == "__main__":
来源：http://dali.c1oappe.top/Article/details/gt2ywyhttcx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.jqgfzy.top/Article/details/gt2iodqqicx.html

JS:   require.main === module
来源：http://dali.jinqigufen.top/Article/details/gt2wqxprgcx.html

TS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gt2eotshjws.html

Java: public static void main(String[] args)
来源：http://dali.vqdsnc.cn/Article/details/gt2hhxdxqfp.html

Go:   func main()
来源：http://dali.gaohongyu789.top/Article/details/gt2yqmcuwai.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.nanxuanxn.top/Article/details/gt2bxtpcejd.html

C#:   static void Main(string[] args)
来源：http://dali.hfpthk.cn/Article/details/gt2apjykjgb.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gt2scubqnsk.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hfpthk.cn/Article/details/gt2sollqpod.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gt2ewsquscf.html

JS:   process.platform;  process.version
来源：http://dali.bjfxy.top/Article/details/gt2mtctnikf.html

TS:   process.platform;  process.version
来源：http://dali.yanxiufei.cn/Article/details/gt2iatxxdvl.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jinqigfzy.top/Article/details/gt2diwrwwhc.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.wangdashe.top/Article/details/gt2ohhhcjyi.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.hnxiangtu.top/Article/details/gt2mdohjqrk.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yongpay.top/Article/details/gt2yddiasnk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2spbfjeqr.html

N. 数据结构与算法
来源：http://dali.jqgufenzy.top/Article/details/gt2nuibaqtz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2eqkttzfe.html

[N01] 二分查找（有序数组）
来源：http://dali.jinqigufen.top/Article/details/gt2yaxpqbct.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2yiardhbz.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ydzc1.top/Article/details/gt2knyioabu.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gaohongyu789.top/Article/details/gt2vwmanhgx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hysaishi.cn/Article/details/gt2dllsewpb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2hwpgjdvo.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.iojbl.cn/Article/details/gt2bkufvize.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.smart0.xyz/Article/details/gt2ybxxgtmh.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gt2jjdplvco.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhixingplan.top/Article/details/gt2kvioplka.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2owkhhzhl.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2napzbnmt.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gt2sqkcsbtx.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2zeezwdgv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.kuanghao11.cn/Article/details/gt2qndhnaqo.html

Go:   slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gt2xmqshbuk.html

Ruby: arr.sort
来源：http://dali.jyoumei.cn/Article/details/gt2bjklrqmq.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.gzhubu.top/Article/details/gt2flqvzwzg.html

[N03] 快速排序（分治示例）
来源：http://dali.wangshuangyany.cn/Article/details/gt2iybcubbs.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.tianlin.xyz/Article/details/gt2tgbkkczz.html

PHP:  // 递归实现，或用 usort
来源：http://dali.shzxlz.cn/Article/details/gt2xnwudvhs.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.aizwys.cn/Article/details/gt2egebyudc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tianlin.xyz/Article/details/gt2vsdksofc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gt2onibozlw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.316326.xyz/Article/details/gt2aazryswt.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.birdmap.top/Article/details/gt2fdrzdrpx.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.gzhubu.top/Article/details/gt2ywcgpyxn.html

[N04] 斐波那契数列
来源：http://dali.cheryme.top/Article/details/gt2lhrpavqe.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.tian-w.cn/Article/details/gt2ptqleysc.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sweek.top/Article/details/gt2zofptrzf.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.yongpay.top/Article/details/gt2awacdfwt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gt2btdfpsut.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.xziqi.cn/Article/details/gt2zxbifzur.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.xylfe.cn/Article/details/gt2iyvecmfd.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2exljsbge.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.mhx1999.top/Article/details/gt2auorrksa.html

[N05] 最大公约数
来源：http://dali.c1oappe.top/Article/details/gt2ldcmcbse.html

Py:   math.gcd(a, b)
来源：http://dali.xinyue.icu/Article/details/gt2aiuydgjx.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.gotoacloud.top/Article/details/gt2lspdxcsn.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tanke756.top/Article/details/gt2jgytgtgp.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yueranfly.top/Article/details/gt2chmaxhzi.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daxiang520.top/Article/details/gt2obisxyvs.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.yueranfly.top/Article/details/gt2xbsuwvqo.html

Ruby: a.gcd(b)
来源：http://dali.aibaodan.cn/Article/details/gt2yrfvjtjo.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gt2tpszjcoy.html

[N06] 判断回文字符串
来源：http://dali.ivvv.top/Article/details/gt2rgaugeis.html

Py:   s == s[::-1]
来源：http://dali.jqgfzy.top/Article/details/gt2pplponjy.html

PHP:  $s === strrev($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ihhjdbdl.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gt2alqygdip.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2lyukmfwr.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.xuetiantiany.cn/Article/details/gt2axyeftsu.html

Go:   // 双指针从两端比较
来源：http://dali.daxiang520.top/Article/details/gt2ggdwlcff.html

Ruby: s == s.reverse
来源：http://dali.fengsongda.top/Article/details/gt2mjjuukjp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gt2vuyogqup.html

[N07] 两数之和（返回下标）
来源：http://dali.sxryk.cn/Article/details/gt2fliqipjs.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jbjaflms.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.dashuyun.cn/Article/details/gt2srtbdrvi.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.ydzc1.top/Article/details/gt2ejrefhis.html

TS:   // 手写 Map<string, number>
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmsugdks.html

Java: // 手写 HashMap
来源：http://dali.daria6918.cn/Article/details/gt2jenzprcr.html

Go:   // 手写 map[int]int
来源：http://dali.quarkkingdee.top/Article/details/gt2wfuvspij.html

Ruby: // 手写 Hash
来源：http://dali.jinghuilouyu.cn/Article/details/gt2okdopvif.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shangyingyoupin.top/Article/details/gt2nzgxlepr.html

[N08] 生成全排列
来源：http://dali.hywenlv.cn/Article/details/gt2tsvyxtks.html

Py:   itertools.permutations(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brwrtsvd.html

PHP:  // 手写递归交换
来源：http://dali.nanxinkj.top/Article/details/gt2cirsjooh.html

JS:   // 手写回溯递归
来源：http://dali.ehwqpu.com/Article/details/gt2kyplvbbi.html

TS:   // 手写回溯递归
来源：http://dali.chenlongwang.top/Article/details/gt2ljisxjzq.html

Java: // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2fnotxwbo.html

Go:   // 手写回溯递归
来源：http://dali.haohaochexian.top/Article/details/gt2expwahrj.html

Ruby: arr.permutation.to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opfocpes.html

C#:   // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jqlzbwut.html

[N09] 栈与队列
来源：http://dali.daria6918.cn/Article/details/gt2infduejx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.bjfxy.top/Article/details/gt2zaexmioh.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmkjyrez.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.bjfxy.top/Article/details/gt2epxaapqv.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.yvedp.cn/Article/details/gt2bqlkoiyo.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.aibaodan.cn/Article/details/gt2xslfbqra.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.yonumen.top/Article/details/gt2rzrsndra.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.hfpthk.cn/Article/details/gt2ntqsvziy.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgjdngvx.html

[N10] 链表节点定义
来源：http://dali.xinyue.icu/Article/details/gt2euhjyixd.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.feifeiyinyue.top/Article/details/gt2xqzuzdnt.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgufenzy.top/Article/details/gt2nutkefrd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.wangdashe.top/Article/details/gt2swrrhdrk.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.shuidangran.top/Article/details/gt2zthrdbam.html

Java: class Node { int v; Node next; }
来源：http://dali.bjfxy.top/Article/details/gt2qlmaxsnp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.guannengcc.top/Article/details/gt2wbtphlon.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.quarkkingdee.top/Article/details/gt2eiiruvzc.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.svipenyu.cn/Article/details/gt2oqgqcwzk.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gt2gniqyqtj.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.shzxlz.cn/Article/details/gt2glyaybzf.html

PHP:  // 手写递归函数
来源：http://dali.birdmap.top/Article/details/gt2auvchenq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ppjwa.cn/Article/details/gt2jpfdrhgc.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.zhoulong.xyz/Article/details/gt2jrawnsap.html

Java: // 手写递归
来源：http://dali.ybcxt.top/Article/details/gt2ksbpawpw.html

Go:   // 手写递归
来源：http://dali.zdqjudy.top/Article/details/gt2rpisbnij.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hammf.cn/Article/details/gt2wfovrwid.html

C#:   // 手写递归
来源：http://dali.nanxinkj.top/Article/details/gt2qcgchbsr.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jqgfzy.top/Article/details/gt2wdajvcnc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.zdqjudy.top/Article/details/gt2bxzmhsjf.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.redwolf501.top/Article/details/gt2lagmmdek.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.guannengcc.top/Article/details/gt2wbiqvjnq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinqigufen.top/Article/details/gt2pmjgjbes.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hammf.cn/Article/details/gt2wwlxxdnv.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.hnqzz.top/Article/details/gt2cunykyvj.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yuanzhike.top/Article/details/gt2jaxegbdv.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.guowangkeji.top/Article/details/gt2srhgixvf.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2ukfyjccf.html

O. 并发与异步
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvqkopje.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2umbcmpag.html

[O01] 启动一个线程
来源：http://dali.yvedp.cn/Article/details/gt2ypazqeyw.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhiwuduotai.top/Article/details/gt2xsrkdvhy.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.nanxinkj.top/Article/details/gt2tpzpwstx.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.quarkkingdee.top/Article/details/gt2rfgucdjr.html

TS:   // 同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2mrfegdzl.html

Java: new Thread(() -> f()).start()
来源：http://dali.pengpengdd.cyou/Article/details/gt2weingzlq.html

Go:   go f()
来源：http://dali.shuidangran.top/Article/details/gt2obcgbqob.html

Ruby: Thread.new { f }
来源：http://dali.gotoacloud.top/Article/details/gt2iqgsaevn.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gt2isedoidc.html

[O02] 使用线程池
来源：http://dali.hfpthk.cn/Article/details/gt2qsmyjimr.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.ppjwa.cn/Article/details/gt2wiwxsciv.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yongpay.top/Article/details/gt2shbaxxsm.html

JS:   // worker_threads 线程池
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2angbhmit.html

TS:   // worker_threads 线程池
来源：http://dali.jianghu66.top/Article/details/gt2qgjpkwbl.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ivvv.top/Article/details/gt2osvpzdbl.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.snrcjt.cn/Article/details/gt2pppvarmc.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.yj20258.top/Article/details/gt2xhrnvjcz.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.sufxvd.cn/Article/details/gt2kygyncmj.html

[O03] 加锁保护共享数据
来源：http://dali.hnqzz.top/Article/details/gt2boeaxlag.html

Py:   with lock: shared += 1
来源：http://dali.jlsjyb.cn/Article/details/gt2nvjfrgpp.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.yonumen.top/Article/details/gt2jdxfxpzz.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.zhixingplan.top/Article/details/gt2bzwptmsc.html

TS:   // 同 JS
来源：http://dali.ehwqpu.com/Article/details/gt2utxvgjks.html

Java: synchronized (this) { shared++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ondoenjb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.sufxvd.cn/Article/details/gt2meqhmorn.html


<!-- 参考信息 -->