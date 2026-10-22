代发 wailian999

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.birdmap.top/Article/details/gt2lvvypois.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rqxdxeff.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.zycfv.cn/Article/details/gt2jangejto.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.0kj1m.cn/Article/details/gt2yayizxxw.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.aizwys.cn/Article/details/gt2qrhpgrpg.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.mhx1999.top/Article/details/gt2vqcwnftb.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.vqdsnc.cn/Article/details/gt2zsotunnt.html

Py:   pickle.dumps(obj)
来源：http://dali.daria6918.cn/Article/details/gt2brpgrtye.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.kuanghao11.cn/Article/details/gt2cugphhqg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.pycfn.com/Article/details/gt2ikthegwl.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.redwolf501.top/Article/details/gt2rfnmtcyv.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ybcxt.top/Article/details/gt2haflehkd.html

Go:   encoding/gob
来源：http://dali.ivvv.top/Article/details/gt2avibhvje.html

Ruby: Marshal.dump(obj)
来源：http://dali.yuxming.cn/Article/details/gt2tvkvxrwc.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.yj20258888.top/Article/details/gt2krykkpac.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2ipwcztos.html

L. 网络请求
来源：http://dali.kuanghao11.cn/Article/details/gt2amfkoooc.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2sdbjkwax.html

[L01] 发送 GET 请求
来源：http://dali.hysaishi.cn/Article/details/gt2condkrfx.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.smart0.xyz/Article/details/gt2crovtiig.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhixingplan.top/Article/details/gt2nldkkbnn.html

JS:   await fetch(url)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jngphwzv.html

TS:   await fetch(url)
来源：http://dali.daria6918.cn/Article/details/gt2oteieskn.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jiagoushi.top/Article/details/gt2cylnrzlc.html

Go:   resp, err := http.Get(url)
来源：http://dali.quarkkingdee.top/Article/details/gt2epgdxxne.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.yj202588.top/Article/details/gt2gubyvguo.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.guannengcc.top/Article/details/gt2jozxesnh.html

[L02] 发送 POST JSON
来源：http://dali.wangdashe.top/Article/details/gt2kkwxsvzk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nogskscp.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.hywenlv.cn/Article/details/gt2ppzqaztc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.hnxiangtu.top/Article/details/gt2evtdbcas.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.jqgfzy.top/Article/details/gt2pxkkjklt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.yonumen.top/Article/details/gt2iicvbsms.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinqigfzy.top/Article/details/gt2txcmswuz.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhiwuduotai.top/Article/details/gt2vlxeirot.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.yonumen.top/Article/details/gt2muetvowx.html

[L03] 设置自定义请求头
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvftuvzy.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wukrwmmw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.cashguo.top/Article/details/gt2ytstytrx.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.gotoacloud.top/Article/details/gt2qmayxtvk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.guannengcc.top/Article/details/gt2jcbetmxq.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cucudq.cn/Article/details/gt2ezwoxtke.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ffpxkugd.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.andypj.xyz/Article/details/gt2lsibplzn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gt2deevitwm.html

[L04] 设置超时
来源：http://dali.guowangkeji.top/Article/details/gt2mzgvoetn.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hfpthk.cn/Article/details/gt2mkftmymj.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cforoinz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.jqgufenzy.top/Article/details/gt2tzwfwgri.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.feifeiyinyue.top/Article/details/gt2tlyvbtjb.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.316326.xyz/Article/details/gt2ocyeciqz.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.chenzaomai.com/Article/details/gt2qxomnrsb.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gt2fgmvgirn.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.redwolf501.top/Article/details/gt2ykqverus.html

[L05] 上传文件（multipart）
来源：http://dali.vqdsnc.cn/Article/details/gt2fkinpnnj.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhixingplan.top/Article/details/gt2taersicl.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.smart0.xyz/Article/details/gt2mwoefesg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yueranfly.top/Article/details/gt2amicmcxv.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.tian-w.cn/Article/details/gt2rmfpviod.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.jiagoushi.top/Article/details/gt2stadxsfn.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gt2vhisqsmp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shuidangran.top/Article/details/gt2wzbrzbju.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2knzmukpa.html

[L06] 解析响应为 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2speccyos.html

Py:   resp.json()
来源：http://dali.zycfv.cn/Article/details/gt2rocjeymh.html

PHP:  json_decode($body, true);
来源：http://dali.zhongyouzk.top/Article/details/gt2zpiotsue.html

JS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gt2xryfpxjc.html

TS:   await resp.json()
来源：http://dali.zhiwuduotai.top/Article/details/gt2kuaknbbs.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.birdmap.top/Article/details/gt2vurxychk.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.hfpthk.cn/Article/details/gt2jooqnirx.html

Ruby: JSON.parse(resp.body)
来源：http://dali.quarkkingdee.top/Article/details/gt2udbhxfsu.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gt2lvsunald.html

[L07] 处理 HTTP 状态码
来源：http://dali.zdqjudy.top/Article/details/gt2neqybtib.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.gotoacloud.top/Article/details/gt2qfkdgpfj.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vnhjowla.html

JS:   resp.ok;  resp.status
来源：http://dali.0kj1m.cn/Article/details/gt2zdihrtbj.html

TS:   resp.ok;  resp.status
来源：http://dali.yonumen.top/Article/details/gt2wvldftmt.html

Java: resp.statusCode()
来源：http://dali.xziqi.cn/Article/details/gt2ubfsulmh.html

Go:   resp.StatusCode
来源：http://dali.iojbl.cn/Article/details/gt2sxbzvtdm.html

Ruby: resp.code.to_i
来源：http://dali.fzhhl.top/Article/details/gt2spoirigz.html

C#:   (int)resp.StatusCode
来源：http://dali.zycfv.cn/Article/details/gt2wazoeaoe.html

[L08] 并发请求多个地址
来源：http://dali.yangfankeji.com/Article/details/gt2otqdrkad.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.pengpengdd.cyou/Article/details/gt2aheppolu.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenlongwang.top/Article/details/gt2kigynttz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gt2bqfrkufg.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.fzhhl.top/Article/details/gt2tjvzscrd.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.hysaishi.cn/Article/details/gt2woubgxun.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.pengpengdd.cyou/Article/details/gt2kmxpclob.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yuanzhike.top/Article/details/gt2mgcfdsfp.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.fengsongda.top/Article/details/gt2lcjnzqlb.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2movjxdyr.html

M. 命令行 / 进程 / 环境
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aoupdvvi.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2pegdylsm.html

[M01] 读取命令行参数
来源：http://dali.hywenlv.cn/Article/details/gt2qlueoord.html

Py:   sys.argv[1:]
来源：http://dali.andypj.xyz/Article/details/gt2kbojpmhw.html

PHP:  $argv;  $argc;
来源：http://dali.cqqwz.cn/Article/details/gt2sfeqextl.html

JS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gt2fyoxxjdz.html

TS:   process.argv.slice(2)
来源：http://dali.meibo888.top/Article/details/gt2acbnucue.html

Java: args 数组（main 方法参数）
来源：http://dali.guannengcc.top/Article/details/gt2pcwubuqf.html

Go:   os.Args[1:]
来源：http://dali.gaohongyu789.top/Article/details/gt2jzxpcydh.html

Ruby: ARGV
来源：http://dali.shangyingyoupin.top/Article/details/gt2bnsarrcw.html

C#:   args 数组（Main 方法参数）
来源：http://dali.chenlongwang.top/Article/details/gt2ectmvnph.html

[M02] 读取环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2szlrsvai.html

Py:   os.environ.get("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2uspkppdx.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.aibaodan.cn/Article/details/gt2ssffbzrs.html

JS:   process.env.HOME
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtftfvjw.html

TS:   process.env.HOME
来源：http://dali.xinyue.icu/Article/details/gt2vvmushdx.html

Java: System.getenv("HOME")
来源：http://dali.ehwqpu.com/Article/details/gt2kcqysrtp.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gotoacloud.top/Article/details/gt2qdsjujbg.html

Ruby: ENV["HOME"]
来源：http://dali.chenjidiqi.icu/Article/details/gt2dkvszxfs.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gt2scfwtiuj.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jehqebop.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.tian-w.cn/Article/details/gt2pzqwqfzk.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rrdgvvzs.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hfpthk.cn/Article/details/gt2rjpecdui.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.iojbl.cn/Article/details/gt2mlclncho.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yonumen.top/Article/details/gt2ouvojscd.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhiwuduotai.top/Article/details/gt2gmwakjon.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.jinghuilouyu.cn/Article/details/gt2knwshwnc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hnqzz.top/Article/details/gt2fzwuxfav.html

[M04] 获取当前工作目录
来源：http://dali.gogol.net.cn/Article/details/gt2lojaioeo.html

Py:   os.getcwd()
来源：http://dali.aizwys.cn/Article/details/gt2rjunbdsp.html

PHP:  getcwd();
来源：http://dali.snrcjt.cn/Article/details/gt2qotpprnn.html

JS:   process.cwd()
来源：http://dali.c1oappe.top/Article/details/gt2vbhqejjm.html

TS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gt2hvmnanba.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.zhoulong.xyz/Article/details/gt2wxgpqpnu.html

Go:   os.Getwd()
来源：http://dali.wangdashe.top/Article/details/gt2uwkmyjxw.html

Ruby: Dir.pwd
来源：http://dali.zhixingplan.top/Article/details/gt2iimdclxb.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.chenzaomai.com/Article/details/gt2qiorpymf.html

[M05] 设置退出码
来源：http://dali.zycfv.cn/Article/details/gt2xtrotzdz.html

Py:   sys.exit(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wcsodorz.html

PHP:  exit(1);
来源：http://dali.zhoulong.xyz/Article/details/gt2qdqazxrw.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2jttcelwr.html

TS:   process.exit(1)
来源：http://dali.tanke756.top/Article/details/gt2cuzjdzuk.html

Java: System.exit(1)
来源：http://dali.guannengcc.top/Article/details/gt2fxxapyox.html

Go:   os.Exit(1)
来源：http://dali.meibo888.top/Article/details/gt2sepwhyji.html

Ruby: exit 1
来源：http://dali.gzhubu.top/Article/details/gt2nlrhbaoh.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lbhajtzf.html

[M06] 向标准错误输出
来源：http://dali.zhixingplan.top/Article/details/gt2dzzlokdp.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gt2vnrbryon.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.sweek.top/Article/details/gt2ihiqpppj.html

JS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gt2gzmomckp.html

TS:   console.error("err")
来源：http://dali.hysaishi.cn/Article/details/gt2dltofugf.html

Java: System.err.println("err")
来源：http://dali.wangdashe.top/Article/details/gt2rtrnbmjs.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.gaohongyu789.top/Article/details/gt2fcpchuoz.html

Ruby: warn "err"
来源：http://dali.cashguo.top/Article/details/gt2qexfvoil.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.aibaodan.cn/Article/details/gt2kzfeyuoc.html

[M07] 判断是否为主入口
来源：http://dali.yanxiufei.cn/Article/details/gt2gucwbpfb.html

Py:   if __name__ == "__main__":
来源：http://dali.hysaishi.cn/Article/details/gt2agduzxcg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sweek.top/Article/details/gt2egadeqvr.html

JS:   require.main === module
来源：http://dali.quarkkingdee.top/Article/details/gt2bdbbihas.html

TS:   require.main === module
来源：http://dali.redwolf501.top/Article/details/gt2lxsefinw.html

Java: public static void main(String[] args)
来源：http://dali.redwolf501.top/Article/details/gt2ytxlpcbh.html

Go:   func main()
来源：http://dali.c1oappe.top/Article/details/gt2xrexfcah.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.shzxlz.cn/Article/details/gt2dgxbfykv.html

C#:   static void Main(string[] args)
来源：http://dali.xylfe.cn/Article/details/gt2idrijprr.html

[M08] 获取系统与运行时信息
来源：http://dali.xuetiantiany.cn/Article/details/gt2hwzpepfx.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cashguo.top/Article/details/gt2hfvlouwr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.kuanghao11.cn/Article/details/gt2ucesqadt.html

JS:   process.platform;  process.version
来源：http://dali.jqgfzy.top/Article/details/gt2aexowvuz.html

TS:   process.platform;  process.version
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hzuvnrtv.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hywenlv.cn/Article/details/gt2byuodaee.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.iojbl.cn/Article/details/gt2seuniibs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.yanxiufei.cn/Article/details/gt2wbntfzya.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.9152youxi.cn/Article/details/gt2yapopgfa.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2vmylyzhh.html

N. 数据结构与算法
来源：http://dali.sxryk.cn/Article/details/gt2vhewrdiv.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2cbnagpgo.html

[N01] 二分查找（有序数组）
来源：http://dali.yj20258888.top/Article/details/gt2jhckhpfy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqbgulka.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj202588.top/Article/details/gt2cbypxmev.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gt2welmpael.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zycfv.cn/Article/details/gt2qazakmcb.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2keccthad.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.daxiang520.top/Article/details/gt2ogmudreb.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.wangdashe.top/Article/details/gt2ynhxpsgn.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pvxhqall.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.zhengqikj.top/Article/details/gt2helfbcur.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gt2zxzgxzff.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.sysykeji.top/Article/details/gt2ikwgxsej.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.ivvv.top/Article/details/gt2yxfwnyes.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gt2rzcpoflv.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxilnbiy.html

Go:   slices.Sort(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2acugglzy.html

Ruby: arr.sort
来源：http://dali.havefunace.top/Article/details/gt2ndlnzdsk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.fengsongda.top/Article/details/gt2lzrlseic.html

[N03] 快速排序（分治示例）
来源：http://dali.gogol.net.cn/Article/details/gt2mewniylz.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.daria6918.cn/Article/details/gt2taunqbfv.html

PHP:  // 递归实现，或用 usort
来源：http://dali.feifeiyinyue.top/Article/details/gt2ahfosktx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.vqdsnc.cn/Article/details/gt2psnjrtez.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gt2esvklrnc.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.ehwqpu.com/Article/details/gt2hbdzonxj.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gt2zfzyighw.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxykwjog.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.feifeiyinyue.top/Article/details/gt2enbvcfzc.html

[N04] 斐波那契数列
来源：http://dali.gogol.net.cn/Article/details/gt2pjwlineb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.meibo888.top/Article/details/gt2awfptljr.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2byfdijag.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.ybcxt.top/Article/details/gt2exhbraue.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhengqikj.top/Article/details/gt2nusznxsq.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.pycfn.com/Article/details/gt2pjjyidrr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.zhengqikj.top/Article/details/gt2ddtzctry.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2illkveks.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shzxlz.cn/Article/details/gt2vmkwyzds.html

[N05] 最大公约数
来源：http://dali.zhiwuduotai.top/Article/details/gt2odfnpbtj.html

Py:   math.gcd(a, b)
来源：http://dali.jianghu66.top/Article/details/gt2zlnamqlz.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.aibaodan.cn/Article/details/gt2qgplwwta.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gt2haivgjae.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.tianlin.xyz/Article/details/gt2agxpilbj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zbpzvaan.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.kuanghao11.cn/Article/details/gt2ydwudzgx.html

Ruby: a.gcd(b)
来源：http://dali.cqqwz.cn/Article/details/gt2aweyvpbi.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yvedp.cn/Article/details/gt2puwnhnmc.html

[N06] 判断回文字符串
来源：http://dali.yj20258888.top/Article/details/gt2dquguvng.html

Py:   s == s[::-1]
来源：http://dali.sysykeji.top/Article/details/gt2baenpgho.html

PHP:  $s === strrev($s);
来源：http://dali.yonumen.top/Article/details/gt2tirrvovh.html

JS:   s === [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2clegiqyi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gt2lbejvzno.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jyoumei.cn/Article/details/gt2wrlxolex.html

Go:   // 双指针从两端比较
来源：http://dali.daria6918.cn/Article/details/gt2xublcfdy.html

Ruby: s == s.reverse
来源：http://dali.gzhubu.top/Article/details/gt2fqazuopk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gt2neruerhk.html

[N07] 两数之和（返回下标）
来源：http://dali.iojbl.cn/Article/details/gt2wgfvupqd.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ydzc1.top/Article/details/gt2sxrxbrnr.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.c1oappe.top/Article/details/gt2goebtehu.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.shuidangran.top/Article/details/gt2uqhdeeip.html

TS:   // 手写 Map<string, number>
来源：http://dali.ehwqpu.com/Article/details/gt2pdtjebwo.html

Java: // 手写 HashMap
来源：http://dali.hongshengwenyu.top/Article/details/gt2pgicarzv.html

Go:   // 手写 map[int]int
来源：http://dali.ppjwa.cn/Article/details/gt2gosdxpeq.html

Ruby: // 手写 Hash
来源：http://dali.smart0.xyz/Article/details/gt2upqbljbl.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.gogol.net.cn/Article/details/gt2fwmuudyn.html

[N08] 生成全排列
来源：http://dali.jyoumei.cn/Article/details/gt2ndggdgjx.html

Py:   itertools.permutations(arr)
来源：http://dali.daria6918.cn/Article/details/gt2zojwfdch.html

PHP:  // 手写递归交换
来源：http://dali.yueranfly.top/Article/details/gt2cigatnhf.html

JS:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2jelztxef.html

TS:   // 手写回溯递归
来源：http://dali.zycfv.cn/Article/details/gt2khjlvryk.html

Java: // 手写回溯递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2zkrsnbzw.html

Go:   // 手写回溯递归
来源：http://dali.jlsjyb.cn/Article/details/gt2djmbryob.html

Ruby: arr.permutation.to_a
来源：http://dali.yangfankeji.com/Article/details/gt2jsbjfijv.html

C#:   // 手写回溯递归
来源：http://dali.xuanzx.com/Article/details/gt2zgvnpoik.html

[N09] 栈与队列
来源：http://dali.gogol.net.cn/Article/details/gt2gczsngln.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.shangyingyoupin.top/Article/details/gt2tfcnpfdn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fengsongda.top/Article/details/gt2atknehjv.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hysaishi.cn/Article/details/gt2mjpkhdvg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.redwolf501.top/Article/details/gt2bpdllvpe.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.yongpay.top/Article/details/gt2twvozgnc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.andypj.xyz/Article/details/gt2wcwsrxgz.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.andypj.xyz/Article/details/gt2unotlpjr.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knsnxyao.html

[N10] 链表节点定义
来源：http://dali.yuanzhike.top/Article/details/gt2fimzvprn.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.jyoumei.cn/Article/details/gt2zjkvpwek.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.yj20258888.top/Article/details/gt2tkljkntd.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.yj202588.top/Article/details/gt2yttsuono.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.mhx1999.top/Article/details/gt2baueufcd.html

Java: class Node { int v; Node next; }
来源：http://dali.sweek.top/Article/details/gt2dcjwanac.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.sufxvd.cn/Article/details/gt2smklyzca.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yanxiufei.cn/Article/details/gt2xzfliphx.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.jlsjyb.cn/Article/details/gt2okaoslev.html

[N11] 二叉树中序遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbzfxzwz.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhijiandao.cn/Article/details/gt2hwutapge.html

PHP:  // 手写递归函数
来源：http://dali.tian-w.cn/Article/details/gt2arzxkssf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.yj20258.top/Article/details/gt2zmbybxpv.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ivvv.top/Article/details/gt2kxhoaocq.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tocebljn.html

Go:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gt2qjqcwqcd.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hongshengwenyu.top/Article/details/gt2olsmiywt.html

C#:   // 手写递归
来源：http://dali.jianghu66.top/Article/details/gt2ftpucfgb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.cqqwz.cn/Article/details/gt2hddlvkol.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.wangdashe.top/Article/details/gt2hlcgxras.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jqgfzy.top/Article/details/gt2kcczfuvx.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gt2zenpiqcz.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jianghu66.top/Article/details/gt2viwnvjnd.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.cheryme.top/Article/details/gt2sidxdhum.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmdorblf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2budyhngm.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.vqdsnc.cn/Article/details/gt2wytiwxtn.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2kpztmfds.html

O. 并发与异步
来源：http://dali.hnxiangtu.top/Article/details/gt2tufdvvql.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2tojicztm.html

[O01] 启动一个线程
来源：http://dali.zhongyouzk.top/Article/details/gt2eawrblvq.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.nwbrower.top/Article/details/gt2ykoakeue.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xylfe.cn/Article/details/gt2mbvwjyun.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.ybcxt.top/Article/details/gt2lmzpiwab.html

TS:   // 同 JS
来源：http://dali.andypj.xyz/Article/details/gt2gpqtaqfe.html

Java: new Thread(() -> f()).start()
来源：http://dali.andypj.xyz/Article/details/gt2dgkljepk.html

Go:   go f()
来源：http://dali.chenlongwang.top/Article/details/gt2suupzekb.html

Ruby: Thread.new { f }
来源：http://dali.hywenlv.cn/Article/details/gt2yaybfouy.html

C#:   Task.Run(() => F());
来源：http://dali.nanxinkj.top/Article/details/gt2ojzjhayu.html

[O02] 使用线程池
来源：http://dali.kuanghao11.cn/Article/details/gt2fljrdbpn.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jiagoushi.top/Article/details/gt2plrseybs.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.nwbrower.top/Article/details/gt2vdcogbmg.html

JS:   // worker_threads 线程池
来源：http://dali.sysykeji.top/Article/details/gt2uqqivmfy.html

TS:   // worker_threads 线程池
来源：http://dali.cdnleiting.top/Article/details/gt2midcsobt.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.nanxinkj.top/Article/details/gt2kgkifqag.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwvxbpgd.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.zhoulong.xyz/Article/details/gt2qiswpqsy.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.zhoulong.xyz/Article/details/gt2nvueocdu.html

[O03] 加锁保护共享数据
来源：http://dali.cucudq.cn/Article/details/gt2lnmvedzs.html

Py:   with lock: shared += 1
来源：http://dali.yangfankeji.com/Article/details/gt2qmqyycyu.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ghnbfajq.html


<!-- 参考信息 -->