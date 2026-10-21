代发 wailian999

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.andypj.xyz/Article/details/gtlvxvhgnr.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.nanxuanxn.top/Article/details/gtswllnrfn.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtgskilgkg.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.shuidangran.top/Article/details/gtqfyafqie.html

[K06] 解析 URL 查询串
来源：http://dali.c1oappe.top/Article/details/gtgpehbzex.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.redwolf501.top/Article/details/gtotjtjeer.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.cucudq.cn/Article/details/gtfdqgjmuj.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.daxiang520.top/Article/details/gtkmrfpsbd.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.chenzaomai.com/Article/details/gtxbtzfoip.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.jinqigfzy.top/Article/details/gtwyhpzlam.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.cashguo.top/Article/details/gtxxxjhiis.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.9152youxi.cn/Article/details/gtfqhehtsd.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.ppjwa.cn/Article/details/gthfojudby.html

[K07] 进制转换
来源：http://dali.zhijiandao.cn/Article/details/gtxgptcbxk.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.0kj1m.cn/Article/details/gttatwibqc.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.dashuyun.cn/Article/details/gtrrvopkbo.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.zhixingplan.top/Article/details/gtukojipzt.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.yj20258888.top/Article/details/gtnkqwmxhm.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.cheryme.top/Article/details/gtzhcvacma.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.cheryme.top/Article/details/gtkcbznnun.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.yangfankeji.com/Article/details/gtqsssfbbp.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.gogol.net.cn/Article/details/gtfstcwgdg.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhixingplan.top/Article/details/gthdfrmlbd.html

Py:   pickle.dumps(obj)
来源：http://dali.guowangkeji.top/Article/details/gtfcayrlri.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.ydzc1.top/Article/details/gtejjsdokk.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtwzdjemut.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.mhx1999.top/Article/details/gtmujvaswa.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.meibo888.top/Article/details/gtecmmdgxo.html

Go:   encoding/gob
来源：http://dali.haohaochexian.top/Article/details/gtpjquenzh.html

Ruby: Marshal.dump(obj)
来源：http://dali.chenzaomai.com/Article/details/gtfrhrfzxe.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.hongshengwenyu.top/Article/details/gtpfqzxcnr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gthierxmbc.html

L. 网络请求
来源：http://dali.yuxming.cn/Article/details/gtnwdkmmjo.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtswlcvzxn.html

[L01] 发送 GET 请求
来源：http://dali.hnxiangtu.top/Article/details/gtdoyyzeba.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sxryk.cn/Article/details/gtveschnfl.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.gotoacloud.top/Article/details/gtfmsgrlpf.html

JS:   await fetch(url)
来源：http://dali.jianghu66.top/Article/details/gtcxahmrhn.html

TS:   await fetch(url)
来源：http://dali.daxiang520.top/Article/details/gtiocrlipx.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhoulong.xyz/Article/details/gtfemuqxar.html

Go:   resp, err := http.Get(url)
来源：http://dali.hnxiangtu.top/Article/details/gtvpyacdln.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.jqgfzy.top/Article/details/gthstzbuku.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.wangshuangyany.cn/Article/details/gtglpjmyuk.html

[L02] 发送 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsepocbpl.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.sysykeji.top/Article/details/gtpsisxeea.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.yvedp.cn/Article/details/gttvphmotd.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.cheryme.top/Article/details/gtmslrwzrt.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.c1oappe.top/Article/details/gtlbunhqrv.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyltecyb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.wangshuangyany.cn/Article/details/gtekgdbagi.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvbxzeeq.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.snrcjt.cn/Article/details/gtfznbkkvs.html

[L03] 设置自定义请求头
来源：http://dali.chenjidiqi.icu/Article/details/gtigeluvnm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.yonumen.top/Article/details/gtbewbozpi.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.andypj.xyz/Article/details/gtreqahljs.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yanxiufei.cn/Article/details/gtivfpkwcq.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.daxiang520.top/Article/details/gteyexinru.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.cashguo.top/Article/details/gtltdfqdtf.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jyoumei.cn/Article/details/gtycccvhsz.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yangfankeji.com/Article/details/gtvtgamknt.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.pengpengdd.cyou/Article/details/gtkqotduih.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gtdeynrccb.html

Py:   requests.get(url, timeout=5)
来源：http://dali.bjfxy.top/Article/details/gtnezkhmtt.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzpghsrx.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cdnleiting.top/Article/details/gtwajiwhbj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.birdmap.top/Article/details/gthadultyv.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.zhongyouzk.top/Article/details/gtrjjlfsgj.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hywenlv.cn/Article/details/gtkrsdvipq.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.tanke756.top/Article/details/gtkiyjtwhr.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jiagoushi.top/Article/details/gttmuzegof.html

[L05] 上传文件（multipart）
来源：http://dali.kuanghao11.cn/Article/details/gtlizefecv.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.havefunace.top/Article/details/gtpuovldyg.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.yj20258888.top/Article/details/gtzwzboqzm.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.smart0.xyz/Article/details/gtgjmngugu.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gtxxygbgye.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.snrcjt.cn/Article/details/gtmvpmcbvj.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvpkpybeu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cucudq.cn/Article/details/gtvvnsdcvp.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.yj20258888.top/Article/details/gtvqwjpdtk.html

[L06] 解析响应为 JSON
来源：http://dali.yj20258.top/Article/details/gtmvzdkegg.html

Py:   resp.json()
来源：http://dali.ivvv.top/Article/details/gtpxcuvvmc.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gthzjdnage.html

JS:   await resp.json()
来源：http://dali.tianlin.xyz/Article/details/gthwlgslql.html

TS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtfabtkxel.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj202588.top/Article/details/gtjemkdcrd.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.chenjidiqi.icu/Article/details/gtzcihljeb.html

Ruby: JSON.parse(resp.body)
来源：http://dali.wangshuangyany.cn/Article/details/gtlnivarlf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.hnqzz.top/Article/details/gtozgegmnc.html

[L07] 处理 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtpqphgkyz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.sxryk.cn/Article/details/gtdozbddic.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.316326.xyz/Article/details/gtekrdyath.html

JS:   resp.ok;  resp.status
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxbrualr.html

TS:   resp.ok;  resp.status
来源：http://dali.dianchejie.cn/Article/details/gtyvkqnfvh.html

Java: resp.statusCode()
来源：http://dali.jiagoushi.top/Article/details/gthkissahg.html

Go:   resp.StatusCode
来源：http://dali.havefunace.top/Article/details/gtdyazwbyo.html

Ruby: resp.code.to_i
来源：http://dali.gzhubu.top/Article/details/gtcsrrcvrl.html

C#:   (int)resp.StatusCode
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpuyskcc.html

[L08] 并发请求多个地址
来源：http://dali.ydzc1.top/Article/details/gtttqloptx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.shzxlz.cn/Article/details/gtzruenjyw.html

PHP:  curl_multi_init() 系列
来源：http://dali.birdmap.top/Article/details/gtlhplifld.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhixingplan.top/Article/details/gtqkixkgpz.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxuanxn.top/Article/details/gtwsctxcum.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhengqikj.top/Article/details/gtwywmfgwl.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.andypj.xyz/Article/details/gtjmxzolqo.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.yangfankeji.com/Article/details/gtuxmrgjmr.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ybcxt.top/Article/details/gtfudfwdor.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtjoygdiwg.html

M. 命令行 / 进程 / 环境
来源：http://dali.jqgufenzy.top/Article/details/gtkglzrscq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvpsfqdiy.html

[M01] 读取命令行参数
来源：http://dali.snrcjt.cn/Article/details/gtsrzjnavj.html

Py:   sys.argv[1:]
来源：http://dali.sxryk.cn/Article/details/gtmjqkkrre.html

PHP:  $argv;  $argc;
来源：http://dali.hammf.cn/Article/details/gtdrfoknzs.html

JS:   process.argv.slice(2)
来源：http://dali.zhengqikj.top/Article/details/gtmxgyatkw.html

TS:   process.argv.slice(2)
来源：http://dali.haohaochexian.top/Article/details/gtlxcgzniz.html

Java: args 数组（main 方法参数）
来源：http://dali.yonumen.top/Article/details/gthntdqxud.html

Go:   os.Args[1:]
来源：http://dali.xuanzx.com/Article/details/gtbvowklfp.html

Ruby: ARGV
来源：http://dali.hysaishi.cn/Article/details/gtjgrqvcot.html

C#:   args 数组（Main 方法参数）
来源：http://dali.c1oappe.top/Article/details/gtppndxdrv.html

[M02] 读取环境变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtheschwbj.html

Py:   os.environ.get("HOME")
来源：http://dali.xuanzx.com/Article/details/gtbvsfvfez.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.iojbl.cn/Article/details/gtrtogtkac.html

JS:   process.env.HOME
来源：http://dali.ehwqpu.com/Article/details/gtnmpnkogv.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gtmqqxvyjv.html

Java: System.getenv("HOME")
来源：http://dali.zycfv.cn/Article/details/gtaunchiou.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.chenjidiqi.icu/Article/details/gtpwpphlim.html

Ruby: ENV["HOME"]
来源：http://dali.sysykeji.top/Article/details/gtplupwcyn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.shuidangran.top/Article/details/gtnvxbniww.html

[M03] 执行外部命令
来源：http://dali.zhixingplan.top/Article/details/gtogwpphjk.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtfjjusmtv.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.9152youxi.cn/Article/details/gtqoajjuug.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hnxiangtu.top/Article/details/gtnlxixjvu.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.sysykeji.top/Article/details/gtxfvgexjn.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zycfv.cn/Article/details/gtpsdgmzdw.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.feifeiyinyue.top/Article/details/gtoooytdqb.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gtedbzomzs.html

C#:   Process.Start("ls", "-l");
来源：http://dali.sysykeji.top/Article/details/gtgmockeke.html

[M04] 获取当前工作目录
来源：http://dali.yvedp.cn/Article/details/gtbuchllpv.html

Py:   os.getcwd()
来源：http://dali.jqgufenzy.top/Article/details/gtxsjkttlk.html

PHP:  getcwd();
来源：http://dali.zycfv.cn/Article/details/gtvkohagmi.html

JS:   process.cwd()
来源：http://dali.andypj.xyz/Article/details/gtgreyjvzj.html

TS:   process.cwd()
来源：http://dali.svipenyu.cn/Article/details/gtklpnenjj.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jqgfzy.top/Article/details/gtaqanllfz.html

Go:   os.Getwd()
来源：http://dali.xuetiantiany.cn/Article/details/gtyvxicxoo.html

Ruby: Dir.pwd
来源：http://dali.gogol.net.cn/Article/details/gtpjkdabgu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zhongyouzk.top/Article/details/gtayfuldrm.html

[M05] 设置退出码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsiuyovz.html

Py:   sys.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtnrpfuxpj.html

PHP:  exit(1);
来源：http://dali.chenjidiqi.icu/Article/details/gtfoslndoy.html

JS:   process.exit(1)
来源：http://dali.zhengqikj.top/Article/details/gtyeojyifb.html

TS:   process.exit(1)
来源：http://dali.hnxiangtu.top/Article/details/gtibobjesa.html

Java: System.exit(1)
来源：http://dali.ybcxt.top/Article/details/gtyxqfmkit.html

Go:   os.Exit(1)
来源：http://dali.zhijiandao.cn/Article/details/gtbxjnfwpe.html

Ruby: exit 1
来源：http://dali.sysykeji.top/Article/details/gtyapvppdn.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ehwqpu.com/Article/details/gtantyhtdf.html

[M06] 向标准错误输出
来源：http://dali.hnqzz.top/Article/details/gtphutruln.html

Py:   print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gtdaizyfnu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.yuanzhike.top/Article/details/gtlprrkosl.html

JS:   console.error("err")
来源：http://dali.sysykeji.top/Article/details/gtwbkfenhm.html

TS:   console.error("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtkueglqkp.html

Java: System.err.println("err")
来源：http://dali.yuanzhike.top/Article/details/gtzvqaylcg.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.kuanghao11.cn/Article/details/gtzucayydk.html

Ruby: warn "err"
来源：http://dali.sysykeji.top/Article/details/gtoewcmixk.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.havefunace.top/Article/details/gtopycszxj.html

[M07] 判断是否为主入口
来源：http://dali.xziqi.cn/Article/details/gtfnctzhcg.html

Py:   if __name__ == "__main__":
来源：http://dali.ydzc1.top/Article/details/gtskpeklqx.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.tian-w.cn/Article/details/gtxialkhca.html

JS:   require.main === module
来源：http://dali.ybcxt.top/Article/details/gtejkwfhhs.html

TS:   require.main === module
来源：http://dali.jinghuilouyu.cn/Article/details/gtvaoevjjv.html

Java: public static void main(String[] args)
来源：http://dali.havefunace.top/Article/details/gtuwxdutpl.html

Go:   func main()
来源：http://dali.gogol.net.cn/Article/details/gtapykqrnw.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sweek.top/Article/details/gtseciqgra.html

C#:   static void Main(string[] args)
来源：http://dali.redwolf501.top/Article/details/gteqkujfsm.html

[M08] 获取系统与运行时信息
来源：http://dali.ehwqpu.com/Article/details/gtbczwdvqw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gaohongyu789.top/Article/details/gtmluhajys.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.chenlongwang.top/Article/details/gtspkhpcdu.html

JS:   process.platform;  process.version
来源：http://dali.jianghu66.top/Article/details/gttvgqhzvd.html

TS:   process.platform;  process.version
来源：http://dali.hammf.cn/Article/details/gtlngxcuww.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.gzhubu.top/Article/details/gtjyvkmlpj.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcrfbjkv.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.redwolf501.top/Article/details/gtcovksgjz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hfpthk.cn/Article/details/gtahhcjztc.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwlazrijq.html

N. 数据结构与算法
来源：http://dali.shzxlz.cn/Article/details/gtsihdwwhd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtxasdmzrs.html

[N01] 二分查找（有序数组）
来源：http://dali.chenzaomai.com/Article/details/gtmyusqaco.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.andypj.xyz/Article/details/gtzaqqsith.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.sysykeji.top/Article/details/gtliykzwhw.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzmjnefz.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.mhx1999.top/Article/details/gtcyhohkyy.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdlbfpph.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.cucudq.cn/Article/details/gtkumlrhup.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.vqdsnc.cn/Article/details/gtgbwwefvt.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.c1oappe.top/Article/details/gtvawounkt.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.dashuyun.cn/Article/details/gtszspovee.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gtbtfvufiq.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.jinqigufen.top/Article/details/gtzdeyyxme.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.aizwys.cn/Article/details/gtbgwukgsp.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.sysykeji.top/Article/details/gttutnwksu.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.jinqigfzy.top/Article/details/gthyhpclta.html

Go:   slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtcljsoduo.html

Ruby: arr.sort
来源：http://dali.cqqwz.cn/Article/details/gtfbjhyqsf.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.dashuyun.cn/Article/details/gtdhvhjoze.html

[N03] 快速排序（分治示例）
来源：http://dali.jinqigufen.top/Article/details/gtabvxaywh.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.quarkkingdee.top/Article/details/gtrblvpalo.html

PHP:  // 递归实现，或用 usort
来源：http://dali.kuanghao11.cn/Article/details/gtxtngqnbc.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yuanzhike.top/Article/details/gtzvvgnnqx.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.316326.xyz/Article/details/gtnukbhoqa.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yanxiufei.cn/Article/details/gtlhicfbgw.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.havefunace.top/Article/details/gtbwsblack.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.hammf.cn/Article/details/gtnpptczqa.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yongpay.top/Article/details/gtrjexsfah.html

[N04] 斐波那契数列
来源：http://dali.c1oappe.top/Article/details/gtyustuuqn.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.redwolf501.top/Article/details/gtjnlkxraa.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.sysykeji.top/Article/details/gtngvvocbk.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gtejdnctes.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cucudq.cn/Article/details/gtjwfjtjao.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.gogol.net.cn/Article/details/gttqsvhpiq.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yonumen.top/Article/details/gthztjzqjl.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.fzhhl.top/Article/details/gtwtsslria.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gtvmkrusbc.html

[N05] 最大公约数
来源：http://dali.dianchejie.cn/Article/details/gtmpozjaun.html

Py:   math.gcd(a, b)
来源：http://dali.zhengqikj.top/Article/details/gtnwdkwkoi.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.xziqi.cn/Article/details/gtmtpyvnpp.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hnxiangtu.top/Article/details/gtlyqbxyzw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.daria6918.cn/Article/details/gtlwlwjqun.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xylfe.cn/Article/details/gtgikvpvjd.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cqqwz.cn/Article/details/gtdsoqagfs.html

Ruby: a.gcd(b)
来源：http://dali.nwbrower.top/Article/details/gtmvoammjj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.jianghu66.top/Article/details/gtokwxncea.html

[N06] 判断回文字符串
来源：http://dali.ivvv.top/Article/details/gtravvptuj.html

Py:   s == s[::-1]
来源：http://dali.pycfn.com/Article/details/gtdtdhcojh.html

PHP:  $s === strrev($s);
来源：http://dali.hywenlv.cn/Article/details/gtlxqigfnn.html

JS:   s === [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gtkothqjfh.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ydzc1.top/Article/details/gtxyiqthip.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.kuanghao11.cn/Article/details/gtdivjtyqb.html

Go:   // 双指针从两端比较
来源：http://dali.fzhhl.top/Article/details/gtocmwwfyb.html

Ruby: s == s.reverse
来源：http://dali.jianghu66.top/Article/details/gtggvpvfsk.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xziqi.cn/Article/details/gtsraffckd.html

[N07] 两数之和（返回下标）
来源：http://dali.pycfn.com/Article/details/gtlxesjnkc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.quarkkingdee.top/Article/details/gttugerwni.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.gogol.net.cn/Article/details/gtbexcsblh.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jiagoushi.top/Article/details/gtdzmembhr.html

TS:   // 手写 Map<string, number>
来源：http://dali.kuanghao11.cn/Article/details/gtflhqvwln.html

Java: // 手写 HashMap
来源：http://dali.cdnleiting.top/Article/details/gtrhqrosrn.html

Go:   // 手写 map[int]int
来源：http://dali.snrcjt.cn/Article/details/gtnywfxilj.html

Ruby: // 手写 Hash
来源：http://dali.pengpengdd.cyou/Article/details/gtzuqfvopf.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.shuidangran.top/Article/details/gthblovwnw.html

[N08] 生成全排列
来源：http://dali.havefunace.top/Article/details/gteqozpgnh.html

Py:   itertools.permutations(arr)
来源：http://dali.hnqzz.top/Article/details/gtioqdyuyh.html

PHP:  // 手写递归交换
来源：http://dali.yj202588.top/Article/details/gthdoziycr.html

JS:   // 手写回溯递归
来源：http://dali.tianlin.xyz/Article/details/gtlogdqjyk.html

TS:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbyyjayd.html

Java: // 手写回溯递归
来源：http://dali.guannengcc.top/Article/details/gtyncthcxh.html

Go:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gtxsiepery.html

Ruby: arr.permutation.to_a
来源：http://dali.cqqwz.cn/Article/details/gthhbllhav.html

C#:   // 手写回溯递归
来源：http://dali.jinqigfzy.top/Article/details/gtlxbjvdtw.html

[N09] 栈与队列
来源：http://dali.ehwqpu.com/Article/details/gtgmkosnua.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.gzhubu.top/Article/details/gtrzxzqgir.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.316326.xyz/Article/details/gtncrzbhpu.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.hnxiangtu.top/Article/details/gtkbwznozu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.jqgufenzy.top/Article/details/gtaluxeskv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.nanxinkj.top/Article/details/gtystvkkbn.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.cheryme.top/Article/details/gtvtecjpmm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttauovvxh.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.yangfankeji.com/Article/details/gtuymgjrus.html

[N10] 链表节点定义
来源：http://dali.yangfankeji.com/Article/details/gtabxangkz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aibaodan.cn/Article/details/gttxtqewsg.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.svipenyu.cn/Article/details/gtxoqqdzjc.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.sufxvd.cn/Article/details/gtqdixqeht.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.zycfv.cn/Article/details/gtjppznmwn.html

Java: class Node { int v; Node next; }
来源：http://dali.pycfn.com/Article/details/gtnpperlup.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.ehwqpu.com/Article/details/gtksxawafs.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.redwolf501.top/Article/details/gtlkjdfgnn.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.dianchejie.cn/Article/details/gtkcnmqhtz.html

[N11] 二叉树中序遍历
来源：http://dali.zhixingplan.top/Article/details/gtfyyhvorl.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.ybcxt.top/Article/details/gtkzadvxaj.html

PHP:  // 手写递归函数
来源：http://dali.zhoulong.xyz/Article/details/gtzazvkxps.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hywenlv.cn/Article/details/gttjndosxg.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nanxuanxn.top/Article/details/gtgqmegjvn.html

Java: // 手写递归
来源：http://dali.hongshengwenyu.top/Article/details/gtyogtvnph.html

Go:   // 手写递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcdauyhf.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.yonumen.top/Article/details/gtnjgbgheh.html

C#:   // 手写递归
来源：http://dali.daxiang520.top/Article/details/gtngsougsk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.hammf.cn/Article/details/gtwyoojprn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.andypj.xyz/Article/details/gtjzznowoy.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigufen.top/Article/details/gtnzqalwca.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gtnppfkcqh.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhongyouzk.top/Article/details/gtcghjvidu.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.dashuyun.cn/Article/details/gttaqjngew.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.chenzaomai.com/Article/details/gtonbbnllb.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.shzxlz.cn/Article/details/gtljiphdre.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.haohaochexian.top/Article/details/gtepehaqvi.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtmpwrvhhs.html

O. 并发与异步
来源：http://dali.daxiang520.top/Article/details/gtulsutipc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gttdlxbojx.html

[O01] 启动一个线程
来源：http://dali.haohaochexian.top/Article/details/gteljldwfk.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.wangshuangyany.cn/Article/details/gtealxyzro.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.quarkkingdee.top/Article/details/gtvijkzaif.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.cqqwz.cn/Article/details/gtytzwabnm.html

TS:   // 同 JS
来源：http://dali.bjfxy.top/Article/details/gtwehqilvf.html


<!-- 参考信息 -->