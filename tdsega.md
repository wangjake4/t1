代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.fzhhl.top/Article/details/gt2qtzdsaaw.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.hammf.cn/Article/details/gt2wmbkuhjy.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.svipenyu.cn/Article/details/gt2aygezrfd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wsacqxiz.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.0kj1m.cn/Article/details/gt2ovuybsoa.html

[K07] 进制转换
来源：http://dali.yj20258.top/Article/details/gt2qegbzlde.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yanxiufei.cn/Article/details/gt2xcoxpati.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.xuetiantiany.cn/Article/details/gt2flgvlezn.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.hywenlv.cn/Article/details/gt2hnkbyftz.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.hfpthk.cn/Article/details/gt2zgdrzdhh.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gt2wvqisupb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qfslglqp.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.vqdsnc.cn/Article/details/gt2xyhnnsqf.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.hysaishi.cn/Article/details/gt2swsoxyvy.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.pycfn.com/Article/details/gt2wmktatkh.html

Py:   pickle.dumps(obj)
来源：http://dali.zhixingplan.top/Article/details/gt2jwrryckp.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.birdmap.top/Article/details/gt2eeuwmncg.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.aizwys.cn/Article/details/gt2hwbrpzfi.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yangfankeji.com/Article/details/gt2qzjqawod.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.iojbl.cn/Article/details/gt2cpvqveix.html

Go:   encoding/gob
来源：http://dali.0kj1m.cn/Article/details/gt2spkaqlpk.html

Ruby: Marshal.dump(obj)
来源：http://dali.yanxiufei.cn/Article/details/gt2tletynef.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.gotoacloud.top/Article/details/gt2zqbhbzee.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ulvoucsi.html

L. 网络请求
来源：http://dali.sweek.top/Article/details/gt2lxuchpzb.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qufqygtr.html

[L01] 发送 GET 请求
来源：http://dali.vqdsnc.cn/Article/details/gt2lwnbmqft.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.cucudq.cn/Article/details/gt2cbgojpcy.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.hnqzz.top/Article/details/gt2pkphcuxj.html

JS:   await fetch(url)
来源：http://dali.316326.xyz/Article/details/gt2fodmvysm.html

TS:   await fetch(url)
来源：http://dali.aizwys.cn/Article/details/gt2qmgiewra.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.hnxiangtu.top/Article/details/gt2rvlfubpd.html

Go:   resp, err := http.Get(url)
来源：http://dali.hysaishi.cn/Article/details/gt2ndmyptxs.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.cheryme.top/Article/details/gt2ddcyrwhz.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.gotoacloud.top/Article/details/gt2mzpisoqb.html

[L02] 发送 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gt2tsosggyy.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.9152youxi.cn/Article/details/gt2nsmvxxte.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.guowangkeji.top/Article/details/gt2xowsygep.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gt2smjfajel.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.fengsongda.top/Article/details/gt2ifgxevbu.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.0kj1m.cn/Article/details/gt2xhbejgpi.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.havefunace.top/Article/details/gt2wlvrtcgy.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.smart0.xyz/Article/details/gt2cyoeyxda.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.aizwys.cn/Article/details/gt2tivuwylj.html

[L03] 设置自定义请求头
来源：http://dali.gzhubu.top/Article/details/gt2ldgobqgc.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zkkeebjs.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.yonumen.top/Article/details/gt2dxhzkhdr.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.xinyue.icu/Article/details/gt2ipirccwg.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.havefunace.top/Article/details/gt2hjwxgqkd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.tian-w.cn/Article/details/gt2anjfwtpy.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.gotoacloud.top/Article/details/gt2qpadztfo.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.cheryme.top/Article/details/gt2qyldcslt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yj202588.top/Article/details/gt2kvpvndfx.html

[L04] 设置超时
来源：http://dali.feifeiyinyue.top/Article/details/gt2uiwamoff.html

Py:   requests.get(url, timeout=5)
来源：http://dali.snrcjt.cn/Article/details/gt2rhmsocck.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.cashguo.top/Article/details/gt2pqvkcjgz.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dianchejie.cn/Article/details/gt2otijnrgp.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gaohongyu789.top/Article/details/gt2orpsyson.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hammf.cn/Article/details/gt2jefkxhnp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.yangfankeji.com/Article/details/gt2hdoqweuq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.gotoacloud.top/Article/details/gt2vdvtryhq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.hammf.cn/Article/details/gt2ndxjtjeg.html

[L05] 上传文件（multipart）
来源：http://dali.zhixingplan.top/Article/details/gt2yxwdflan.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jqgfzy.top/Article/details/gt2dehilyqa.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2axvmrbih.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.gogol.net.cn/Article/details/gt2whwlklgw.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.hysaishi.cn/Article/details/gt2lxtxpjxw.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.redwolf501.top/Article/details/gt2cddtaonv.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.snrcjt.cn/Article/details/gt2xfhlkzkf.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.daxiang520.top/Article/details/gt2hefpthbi.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ifjohcna.html

[L06] 解析响应为 JSON
来源：http://dali.0kj1m.cn/Article/details/gt2tbfzgeel.html

Py:   resp.json()
来源：http://dali.shzxlz.cn/Article/details/gt2jexwoxrq.html

PHP:  json_decode($body, true);
来源：http://dali.mhx1999.top/Article/details/gt2mlrcaoxk.html

JS:   await resp.json()
来源：http://dali.hysaishi.cn/Article/details/gt2jllolgsg.html

TS:   await resp.json()
来源：http://dali.sysykeji.top/Article/details/gt2hguobdvr.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yonumen.top/Article/details/gt2nktqkjjp.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gt2yhrdhaln.html

Ruby: JSON.parse(resp.body)
来源：http://dali.yj20258.top/Article/details/gt2ewhvmqps.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhengqikj.top/Article/details/gt2yqmahffo.html

[L07] 处理 HTTP 状态码
来源：http://dali.xylfe.cn/Article/details/gt2zpczidvv.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.dashuyun.cn/Article/details/gt2efniltxq.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.svipenyu.cn/Article/details/gt2hwnxxbwt.html

JS:   resp.ok;  resp.status
来源：http://dali.wangshuangyany.cn/Article/details/gt2cupwvyww.html

TS:   resp.ok;  resp.status
来源：http://dali.c1oappe.top/Article/details/gt2btqvpcqz.html

Java: resp.statusCode()
来源：http://dali.havefunace.top/Article/details/gt2ecsaqssf.html

Go:   resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gt2uhrkzbqz.html

Ruby: resp.code.to_i
来源：http://dali.hfpthk.cn/Article/details/gt2ejkqsomd.html

C#:   (int)resp.StatusCode
来源：http://dali.yueranfly.top/Article/details/gt2goaxutlp.html

[L08] 并发请求多个地址
来源：http://dali.smart0.xyz/Article/details/gt2ezakzwiy.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xinyue.icu/Article/details/gt2mjyzqgkw.html

PHP:  curl_multi_init() 系列
来源：http://dali.chenlongwang.top/Article/details/gt2etrwjwvc.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hongshengwenyu.top/Article/details/gt2ngvrsidv.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2qiiczfci.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gotoacloud.top/Article/details/gt2luvkplkt.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.hnqzz.top/Article/details/gt2muyulwpb.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.xinyue.icu/Article/details/gt2ckgajvbx.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jiagoushi.top/Article/details/gt2wvafohzp.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2xytdsrsm.html

M. 命令行 / 进程 / 环境
来源：http://dali.wangdashe.top/Article/details/gt2sudlwwmf.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tkkzfqyw.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gt2vptyjncy.html

Py:   sys.argv[1:]
来源：http://dali.kuanghao11.cn/Article/details/gt2zmpdovaq.html

PHP:  $argv;  $argc;
来源：http://dali.quarkkingdee.top/Article/details/gt2qldtoezt.html

JS:   process.argv.slice(2)
来源：http://dali.birdmap.top/Article/details/gt2eiolfyrv.html

TS:   process.argv.slice(2)
来源：http://dali.dianchejie.cn/Article/details/gt2dttxvrji.html

Java: args 数组（main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gt2lmxiwlrc.html

Go:   os.Args[1:]
来源：http://dali.cqqwz.cn/Article/details/gt2bezhpkfb.html

Ruby: ARGV
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2brcpixrv.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zycfv.cn/Article/details/gt2izvnynuc.html

[M02] 读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gt2iyiypwcj.html

Py:   os.environ.get("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2igmhnmat.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yj20258888.top/Article/details/gt2muywayhh.html

JS:   process.env.HOME
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfjssivj.html

TS:   process.env.HOME
来源：http://dali.dashuyun.cn/Article/details/gt2mdrtaiee.html

Java: System.getenv("HOME")
来源：http://dali.zhiwuduotai.top/Article/details/gt2czqjagrz.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ptihnebt.html

Ruby: ENV["HOME"]
来源：http://dali.vqdsnc.cn/Article/details/gt2pqqkhocb.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.meibo888.top/Article/details/gt2hyiodfvo.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yqzqbidc.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.jianghu66.top/Article/details/gt2hqtkxwvc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.fengsongda.top/Article/details/gt2rinwnqpg.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.cucudq.cn/Article/details/gt2dstcsusw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhoulong.xyz/Article/details/gt2gfkrsjts.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.bjfxy.top/Article/details/gt2gtbvmmtf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhongyouzk.top/Article/details/gt2qvexwszd.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgitildj.html

C#:   Process.Start("ls", "-l");
来源：http://dali.xziqi.cn/Article/details/gt2czsrkgxq.html

[M04] 获取当前工作目录
来源：http://dali.hammf.cn/Article/details/gt2bnlddwas.html

Py:   os.getcwd()
来源：http://dali.xziqi.cn/Article/details/gt2xhrkonik.html

PHP:  getcwd();
来源：http://dali.nwbrower.top/Article/details/gt2rwnijbnq.html

JS:   process.cwd()
来源：http://dali.zhixingplan.top/Article/details/gt2pwtodkmf.html

TS:   process.cwd()
来源：http://dali.guowangkeji.top/Article/details/gt2gbhitfrv.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgfzy.top/Article/details/gt2cnvjevsi.html

Go:   os.Getwd()
来源：http://dali.smart0.xyz/Article/details/gt2rnkqirib.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gt2squxlcop.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.kuanghao11.cn/Article/details/gt2xbuowram.html

[M05] 设置退出码
来源：http://dali.chenlongwang.top/Article/details/gt2fmjycwzi.html

Py:   sys.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2eitmifgz.html

PHP:  exit(1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dqbswter.html

JS:   process.exit(1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2gnximguj.html

TS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2itbdvmqa.html

Java: System.exit(1)
来源：http://dali.dashuyun.cn/Article/details/gt2ahdjggkn.html

Go:   os.Exit(1)
来源：http://dali.gotoacloud.top/Article/details/gt2smfxrmsl.html

Ruby: exit 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ihtusnet.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hnxiangtu.top/Article/details/gt2mshatxfq.html

[M06] 向标准错误输出
来源：http://dali.xziqi.cn/Article/details/gt2pruzzoaz.html

Py:   print("err", file=sys.stderr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rtmzeyml.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cashguo.top/Article/details/gt2djrovyuz.html

JS:   console.error("err")
来源：http://dali.ydzc1.top/Article/details/gt2rollhekc.html

TS:   console.error("err")
来源：http://dali.9152youxi.cn/Article/details/gt2fxkiqobf.html

Java: System.err.println("err")
来源：http://dali.c1oappe.top/Article/details/gt2hdtaqqig.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yongpay.top/Article/details/gt2jlflqkei.html

Ruby: warn "err"
来源：http://dali.316326.xyz/Article/details/gt2glajiahn.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.daxiang520.top/Article/details/gt2edqhcplx.html

[M07] 判断是否为主入口
来源：http://dali.gotoacloud.top/Article/details/gt2hamfhfqg.html

Py:   if __name__ == "__main__":
来源：http://dali.gaohongyu789.top/Article/details/gt2fcewyjnt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.316326.xyz/Article/details/gt2wvqlamyp.html

JS:   require.main === module
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ltmjdahg.html

TS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gt2snahoyzg.html

Java: public static void main(String[] args)
来源：http://dali.zdqjudy.top/Article/details/gt2xmcqrjum.html

Go:   func main()
来源：http://dali.aibaodan.cn/Article/details/gt2zsqpqogx.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.vqdsnc.cn/Article/details/gt2hokbhtme.html

C#:   static void Main(string[] args)
来源：http://dali.yueranfly.top/Article/details/gt2xxxjoyge.html

[M08] 获取系统与运行时信息
来源：http://dali.havefunace.top/Article/details/gt2awpeycbe.html

Py:   platform.system();  platform.python_version()
来源：http://dali.hywenlv.cn/Article/details/gt2fqqoidbt.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.haohaochexian.top/Article/details/gt2pvwysbnx.html

JS:   process.platform;  process.version
来源：http://dali.dianchejie.cn/Article/details/gt2uxlutjun.html

TS:   process.platform;  process.version
来源：http://dali.zhoulong.xyz/Article/details/gt2sypkeens.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.xuanzx.com/Article/details/gt2qowpysyw.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.gotoacloud.top/Article/details/gt2cwptuvfn.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.havefunace.top/Article/details/gt2vyntbxvq.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gt2buxelbek.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2mlpbpiqb.html

N. 数据结构与算法
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgydynsj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2ytllawqd.html

[N01] 二分查找（有序数组）
来源：http://dali.aizwys.cn/Article/details/gt2hdrpcuad.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2uuveuysm.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wquvpagb.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.ivvv.top/Article/details/gt2izxcxfxl.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.andypj.xyz/Article/details/gt2kqwnihyk.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2pasqpkae.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2ooirqpgd.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.xinyue.icu/Article/details/gt2esxxboxx.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.yuxming.cn/Article/details/gt2aaiuaoly.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.yueranfly.top/Article/details/gt2ajphewop.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gt2ujxtpqir.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gt2ksplbdqr.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gt2zqhgpzlg.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.svipenyu.cn/Article/details/gt2ddmcsjmg.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.bjfxy.top/Article/details/gt2sbgkidni.html

Go:   slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gt2sroeppgq.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gt2vtarmvrz.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.jqgfzy.top/Article/details/gt2awpznvut.html

[N03] 快速排序（分治示例）
来源：http://dali.zhengqikj.top/Article/details/gt2btkcoygy.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zvejojsb.html

PHP:  // 递归实现，或用 usort
来源：http://dali.iojbl.cn/Article/details/gt2kivtzyjb.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.hongshengwenyu.top/Article/details/gt2psaudiev.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.nwbrower.top/Article/details/gt2aroelcip.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.svipenyu.cn/Article/details/gt2shvjruvw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.0kj1m.cn/Article/details/gt2ufaxhsiz.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.chenzaomai.com/Article/details/gt2pxtzkata.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.jqgufenzy.top/Article/details/gt2tgqfdabu.html

[N04] 斐波那契数列
来源：http://dali.jiagoushi.top/Article/details/gt2gdtfdjrc.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.ybcxt.top/Article/details/gt2bcjcvukv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2htftyzbt.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hywenlv.cn/Article/details/gt2zrhmmslh.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.birdmap.top/Article/details/gt2olhapghh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vyivoxoq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.pycfn.com/Article/details/gt2xofitpzs.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.cashguo.top/Article/details/gt2togthdui.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evjxucpy.html

[N05] 最大公约数
来源：http://dali.jqgufenzy.top/Article/details/gt2yugqktjc.html

Py:   math.gcd(a, b)
来源：http://dali.haohaochexian.top/Article/details/gt2carfiehd.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2rvwafyls.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.xuanzx.com/Article/details/gt2ivsasdvg.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.yvedp.cn/Article/details/gt2gnvhbwcc.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.chenjidiqi.icu/Article/details/gt2joaomzdj.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.dianchejie.cn/Article/details/gt2uuetnqce.html

Ruby: a.gcd(b)
来源：http://dali.fengsongda.top/Article/details/gt2utfrmqga.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ankqhdni.html

[N06] 判断回文字符串
来源：http://dali.zhengqikj.top/Article/details/gt2tqcsuxyo.html

Py:   s == s[::-1]
来源：http://dali.sxryk.cn/Article/details/gt2pnkuiqvi.html

PHP:  $s === strrev($s);
来源：http://dali.birdmap.top/Article/details/gt2jcccyvxt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gt2senlbyol.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2thgyqork.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.vqdsnc.cn/Article/details/gt2zywykjzq.html

Go:   // 双指针从两端比较
来源：http://dali.guowangkeji.top/Article/details/gt2zehdpptr.html

Ruby: s == s.reverse
来源：http://dali.shzxlz.cn/Article/details/gt2esmtastl.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.iojbl.cn/Article/details/gt2dsquczpz.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gt2tbwhmmmm.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sxryk.cn/Article/details/gt2yckdourk.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.shangyingyoupin.top/Article/details/gt2hiihmjqy.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yuanzhike.top/Article/details/gt2oqekvewa.html

TS:   // 手写 Map<string, number>
来源：http://dali.hnqzz.top/Article/details/gt2vtucrcum.html

Java: // 手写 HashMap
来源：http://dali.shzxlz.cn/Article/details/gt2tpsuzyas.html

Go:   // 手写 map[int]int
来源：http://dali.9152youxi.cn/Article/details/gt2nzqnyqgm.html

Ruby: // 手写 Hash
来源：http://dali.smart0.xyz/Article/details/gt2wwpsokto.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.hnxiangtu.top/Article/details/gt2zrdbomru.html

[N08] 生成全排列
来源：http://dali.aizwys.cn/Article/details/gt2cipfvqlk.html

Py:   itertools.permutations(arr)
来源：http://dali.daxiang520.top/Article/details/gt2vnkzsuws.html

PHP:  // 手写递归交换
来源：http://dali.hongshengwenyu.top/Article/details/gt2kvslihyg.html

JS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2htoqmbwj.html

TS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gt2rvjkecpp.html

Java: // 手写回溯递归
来源：http://dali.nanxinkj.top/Article/details/gt2umnmneuh.html

Go:   // 手写回溯递归
来源：http://dali.shuidangran.top/Article/details/gt2hpbxfwnu.html

Ruby: arr.permutation.to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vfiptxni.html

C#:   // 手写回溯递归
来源：http://dali.gotoacloud.top/Article/details/gt2iarwygff.html

[N09] 栈与队列
来源：http://dali.ybcxt.top/Article/details/gt2stbocxgt.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.fzhhl.top/Article/details/gt2psduwiqj.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.daria6918.cn/Article/details/gt2ufmabhlj.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2dcnggvzm.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.nanxuanxn.top/Article/details/gt2dovllgyf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.xylfe.cn/Article/details/gt2jupvsdqi.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.quarkkingdee.top/Article/details/gt2tmwqljvj.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gt2goumxdyo.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zdqjudy.top/Article/details/gt2kvzirchg.html

[N10] 链表节点定义
来源：http://dali.cdnleiting.top/Article/details/gt2niqyqmzm.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.tian-w.cn/Article/details/gt2ndopytjm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jqgfzy.top/Article/details/gt2hqwtontp.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ddglldkt.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jinqigfzy.top/Article/details/gt2aktseeqn.html

Java: class Node { int v; Node next; }
来源：http://dali.xziqi.cn/Article/details/gt2rigvoijf.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yangfankeji.com/Article/details/gt2biddougd.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vvxjktjn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.yuxming.cn/Article/details/gt2flmghwva.html

[N11] 二叉树中序遍历
来源：http://dali.hnqzz.top/Article/details/gt2eohrvaun.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.jinghuilouyu.cn/Article/details/gt2waubsbpo.html

PHP:  // 手写递归函数
来源：http://dali.daxiang520.top/Article/details/gt2ytscclhf.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.cucudq.cn/Article/details/gt2gwhjyeju.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gt2fkoejqos.html

Java: // 手写递归
来源：http://dali.pycfn.com/Article/details/gt2iubqsqqj.html

Go:   // 手写递归
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bjvqwmzp.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.bjfxy.top/Article/details/gt2ddyxwdjo.html

C#:   // 手写递归
来源：http://dali.yuxming.cn/Article/details/gt2bpnltbhb.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gzhubu.top/Article/details/gt2phmkhezv.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.jinqigufen.top/Article/details/gt2zskbewas.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.feifeiyinyue.top/Article/details/gt2aiqlreja.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yj20258.top/Article/details/gt2khmdcgrg.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.yuxming.cn/Article/details/gt2ubnsoefs.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.pengpengdd.cyou/Article/details/gt2wlhxdvxn.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.cdnleiting.top/Article/details/gt2qgkktgrv.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2pfdbmgvl.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hfpthk.cn/Article/details/gt2ctcmbfug.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2kbdjehyq.html

O. 并发与异步
来源：http://dali.zhongyouzk.top/Article/details/gt2aczlrehn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ennflpto.html

[O01] 启动一个线程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2illdeluu.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.zhiwuduotai.top/Article/details/gt2lyjllwsq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2etozvrwp.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.snrcjt.cn/Article/details/gt2ilnjhhsk.html

TS:   // 同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrqiues.html

Java: new Thread(() -> f()).start()
来源：http://dali.aibaodan.cn/Article/details/gt2sowhfbse.html

Go:   go f()
来源：http://dali.jiagoushi.top/Article/details/gt2qjchnhxn.html

Ruby: Thread.new { f }
来源：http://dali.ppjwa.cn/Article/details/gt2zuqqgozk.html

C#:   Task.Run(() => F());
来源：http://dali.xylfe.cn/Article/details/gt2kczrwzkh.html

[O02] 使用线程池
来源：http://dali.shzxlz.cn/Article/details/gt2eiwnrctp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hammf.cn/Article/details/gt2hhdhqvrf.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.zhoulong.xyz/Article/details/gt2kmjnpulw.html

JS:   // worker_threads 线程池
来源：http://dali.yj20258.top/Article/details/gt2tnyxztye.html


<!-- 参考信息 -->