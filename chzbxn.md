代发 wailian999

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.redwolf501.top/Article/details/gtqpwwnbmt.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.tian-w.cn/Article/details/gtyfrbshzy.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.birdmap.top/Article/details/gthazaxvng.html

[K05] 深拷贝对象
来源：http://dali.guowangkeji.top/Article/details/gtsgkevtaq.html

Py:   copy.deepcopy(obj)
来源：http://dali.316326.xyz/Article/details/gtcgelztni.html

PHP:  unserialize(serialize($obj));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglbkbbnh.html

JS:   structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtloojmxmq.html

TS:   structuredClone(obj)
来源：http://dali.yangfankeji.com/Article/details/gtjgnjagvr.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.mhx1999.top/Article/details/gteslmjwiu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.hnqzz.top/Article/details/gtbaepdreg.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.dianchejie.cn/Article/details/gtumbhlqha.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.daria6918.cn/Article/details/gtlqwvnabz.html

[K06] 解析 URL 查询串
来源：http://dali.dashuyun.cn/Article/details/gtyubyddwl.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.havefunace.top/Article/details/gtcbicbugo.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.chenzaomai.com/Article/details/gtbeueoyqf.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.jinqigfzy.top/Article/details/gtaqduifwf.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdpelgsqh.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.316326.xyz/Article/details/gttbxhllfk.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.redwolf501.top/Article/details/gtuwcjsvxs.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.hywenlv.cn/Article/details/gtqtomwbaa.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.jqgufenzy.top/Article/details/gtvjdecthu.html

[K07] 进制转换
来源：http://dali.cheryme.top/Article/details/gtcewcyjvn.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.jlsjyb.cn/Article/details/gtdgdlkwji.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.ivvv.top/Article/details/gtcmjptrxp.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.shanyushiyangtech.top/Article/details/gtldcnfaeg.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.sweek.top/Article/details/gtfnubdspl.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtpicgvvng.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.yonumen.top/Article/details/gtadfxfmol.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpfrxpbvs.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.wangdashe.top/Article/details/gtlezccrfx.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.wangshuangyany.cn/Article/details/gtnsazclga.html

Py:   pickle.dumps(obj)
来源：http://dali.pengpengdd.cyou/Article/details/gtcfwcadsv.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.jiagoushi.top/Article/details/gtvdgpeyzb.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yueranfly.top/Article/details/gtcyqbpsml.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.xuanzx.com/Article/details/gtuipqbtfm.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.gogol.net.cn/Article/details/gtchrotmec.html

Go:   encoding/gob
来源：http://dali.quarkkingdee.top/Article/details/gtnykpwyil.html

Ruby: Marshal.dump(obj)
来源：http://dali.daxiang520.top/Article/details/gtehmgdrkl.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.tanke756.top/Article/details/gtxmbtequv.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtggmqtgyl.html

L. 网络请求
来源：http://dali.ppjwa.cn/Article/details/gtmsuwvfbo.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtsymbkiyq.html

[L01] 发送 GET 请求
来源：http://dali.fzhhl.top/Article/details/gtwxjfvkaf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjgfutle.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.zhongyouzk.top/Article/details/gtvayvbmqj.html

JS:   await fetch(url)
来源：http://dali.andypj.xyz/Article/details/gtwhxgjxvw.html

TS:   await fetch(url)
来源：http://dali.iojbl.cn/Article/details/gteeyrwqqk.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jqgufenzy.top/Article/details/gtkaydxuuk.html

Go:   resp, err := http.Get(url)
来源：http://dali.ydzc1.top/Article/details/gtepyasdui.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.hywenlv.cn/Article/details/gtuflsquiy.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hnqzz.top/Article/details/gtqowhkteg.html

[L02] 发送 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtndrekbdm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.316326.xyz/Article/details/gtgrgphvon.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jqgufenzy.top/Article/details/gtpypmktyy.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xylfe.cn/Article/details/gtqzuwivek.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xuanzx.com/Article/details/gtffhilrkt.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.cucudq.cn/Article/details/gtaszfqupa.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.gotoacloud.top/Article/details/gtzmburjml.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthsvmdvlf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.jiagoushi.top/Article/details/gteftujjfo.html

[L03] 设置自定义请求头
来源：http://dali.yueranfly.top/Article/details/gtpdcyoory.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.quarkkingdee.top/Article/details/gtgnanoegg.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.sweek.top/Article/details/gtrruntdvb.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zycfv.cn/Article/details/gttvwcmapv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yongpay.top/Article/details/gtyjoowmdr.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.c1oappe.top/Article/details/gtophpydke.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqmpbhjj.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.xziqi.cn/Article/details/gtgafkeaxo.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.hnqzz.top/Article/details/gtzgjevivn.html

[L04] 设置超时
来源：http://dali.hammf.cn/Article/details/gtservbxve.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hongshengwenyu.top/Article/details/gttkkiphav.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.vqdsnc.cn/Article/details/gtfguqwoye.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.xziqi.cn/Article/details/gtcsnccijj.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.cucudq.cn/Article/details/gtkrlwmclt.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jinghuilouyu.cn/Article/details/gtduwegboa.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.jiagoushi.top/Article/details/gtpfcxajvx.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvrlaeng.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.andypj.xyz/Article/details/gtuhonwpfa.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gtxjqrzogf.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.jyoumei.cn/Article/details/gtjbxcwlrw.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.c1oappe.top/Article/details/gtwwutpwjt.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.chenlongwang.top/Article/details/gtlzjyzyys.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhoulong.xyz/Article/details/gtnbmdgpko.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.gaohongyu789.top/Article/details/gtvuljaosd.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.aibaodan.cn/Article/details/gtmwihdedv.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cheryme.top/Article/details/gtowjugmnv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtuuqsgfur.html

[L06] 解析响应为 JSON
来源：http://dali.hnxiangtu.top/Article/details/gtjzzvkaoy.html

Py:   resp.json()
来源：http://dali.daria6918.cn/Article/details/gttlexrzwd.html

PHP:  json_decode($body, true);
来源：http://dali.kuanghao11.cn/Article/details/gtukufcznt.html

JS:   await resp.json()
来源：http://dali.nanxuanxn.top/Article/details/gtnuuugllo.html

TS:   await resp.json()
来源：http://dali.hnqzz.top/Article/details/gtrclteqlv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtbxzfsmys.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.yvedp.cn/Article/details/gtuzicjbsv.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aizwys.cn/Article/details/gtsgvvptkg.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gtiyiqnxbv.html

[L07] 处理 HTTP 状态码
来源：http://dali.hnxiangtu.top/Article/details/gtxmthllpz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhoulong.xyz/Article/details/gtpyybqclm.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.zhongyouzk.top/Article/details/gtcopakwye.html

JS:   resp.ok;  resp.status
来源：http://dali.guowangkeji.top/Article/details/gtwukswxrn.html

TS:   resp.ok;  resp.status
来源：http://dali.ydzc1.top/Article/details/gtblgftuqw.html

Java: resp.statusCode()
来源：http://dali.zycfv.cn/Article/details/gtdsvumnnp.html

Go:   resp.StatusCode
来源：http://dali.cashguo.top/Article/details/gtxjfyojtc.html

Ruby: resp.code.to_i
来源：http://dali.bjfxy.top/Article/details/gtptvktjpw.html

C#:   (int)resp.StatusCode
来源：http://dali.sweek.top/Article/details/gtvvyaljoc.html

[L08] 并发请求多个地址
来源：http://dali.wangdashe.top/Article/details/gtqtvlkhss.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yj202588.top/Article/details/gtguwdiykf.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gtqvsmveug.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinqigfzy.top/Article/details/gtvjakjofe.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.pycfn.com/Article/details/gtchjkbrjx.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.yuanzhike.top/Article/details/gtqtlbsbno.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jyoumei.cn/Article/details/gtidpyujry.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.shzxlz.cn/Article/details/gtzdvixcty.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.jianghu66.top/Article/details/gtwiggobti.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtkjfkvdoh.html

M. 命令行 / 进程 / 环境
来源：http://dali.yj20258.top/Article/details/gtxnpojuts.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtqssujdvd.html

[M01] 读取命令行参数
来源：http://dali.zycfv.cn/Article/details/gtxgdojwuf.html

Py:   sys.argv[1:]
来源：http://dali.shuidangran.top/Article/details/gtlkmdibwd.html

PHP:  $argv;  $argc;
来源：http://dali.fzhhl.top/Article/details/gtvfmbmdoo.html

JS:   process.argv.slice(2)
来源：http://dali.daxiang520.top/Article/details/gtbxosgtvo.html

TS:   process.argv.slice(2)
来源：http://dali.jinqigufen.top/Article/details/gtfhvbscyb.html

Java: args 数组（main 方法参数）
来源：http://dali.jinqigfzy.top/Article/details/gtsycfcrao.html

Go:   os.Args[1:]
来源：http://dali.jqgfzy.top/Article/details/gttavyxjfg.html

Ruby: ARGV
来源：http://dali.daxiang520.top/Article/details/gtbmntwxke.html

C#:   args 数组（Main 方法参数）
来源：http://dali.zhongyouzk.top/Article/details/gtnsmbcjaq.html

[M02] 读取环境变量
来源：http://dali.ydzc1.top/Article/details/gtfixxodil.html

Py:   os.environ.get("HOME")
来源：http://dali.cqqwz.cn/Article/details/gtlbcqqunv.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.ppjwa.cn/Article/details/gtwvriofla.html

JS:   process.env.HOME
来源：http://dali.aizwys.cn/Article/details/gtoupjspyf.html

TS:   process.env.HOME
来源：http://dali.iojbl.cn/Article/details/gtyvifpowe.html

Java: System.getenv("HOME")
来源：http://dali.vqdsnc.cn/Article/details/gtpjsicqum.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.c1oappe.top/Article/details/gttmvfbtsa.html

Ruby: ENV["HOME"]
来源：http://dali.xziqi.cn/Article/details/gttiowkfrd.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.cucudq.cn/Article/details/gtbzqsrrgj.html

[M03] 执行外部命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjvsxfop.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gtnyagofpd.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.gzhubu.top/Article/details/gtnuunnczc.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yj20258.top/Article/details/gtsvvodvfl.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.jqgufenzy.top/Article/details/gtllxtubqa.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.yuanzhike.top/Article/details/gtfkbjbiea.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.nanxuanxn.top/Article/details/gtmdmdlcuz.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.pycfn.com/Article/details/gtsgakaaod.html

C#:   Process.Start("ls", "-l");
来源：http://dali.havefunace.top/Article/details/gtzfxrbmye.html

[M04] 获取当前工作目录
来源：http://dali.iojbl.cn/Article/details/gtucvfvemc.html

Py:   os.getcwd()
来源：http://dali.zycfv.cn/Article/details/gthhzdorpi.html

PHP:  getcwd();
来源：http://dali.yvedp.cn/Article/details/gtkfbuzkir.html

JS:   process.cwd()
来源：http://dali.hnqzz.top/Article/details/gtiubtfwky.html

TS:   process.cwd()
来源：http://dali.gotoacloud.top/Article/details/gtxodcowzi.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.shanyushiyangtech.top/Article/details/gtbccycast.html

Go:   os.Getwd()
来源：http://dali.zhijiandao.cn/Article/details/gtuhotifcp.html

Ruby: Dir.pwd
来源：http://dali.c1oappe.top/Article/details/gtkylhlejd.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.xziqi.cn/Article/details/gtiiatpffj.html

[M05] 设置退出码
来源：http://dali.wangshuangyany.cn/Article/details/gthcxojexe.html

Py:   sys.exit(1)
来源：http://dali.mhx1999.top/Article/details/gtrqdbnjku.html

PHP:  exit(1);
来源：http://dali.hywenlv.cn/Article/details/gtwmqriirc.html

JS:   process.exit(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpoagufh.html

TS:   process.exit(1)
来源：http://dali.zhoulong.xyz/Article/details/gtmjjlvqdy.html

Java: System.exit(1)
来源：http://dali.cashguo.top/Article/details/gtyxvfgcph.html

Go:   os.Exit(1)
来源：http://dali.sufxvd.cn/Article/details/gthiwwepfe.html

Ruby: exit 1
来源：http://dali.nanxinkj.top/Article/details/gtkgprkfai.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.hongshengwenyu.top/Article/details/gthqhcalyy.html

[M06] 向标准错误输出
来源：http://dali.yvedp.cn/Article/details/gtnzdyixcu.html

Py:   print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gtfvswpivu.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.zhengqikj.top/Article/details/gtdrhbitxv.html

JS:   console.error("err")
来源：http://dali.yuanzhike.top/Article/details/gtcckvtdzv.html

TS:   console.error("err")
来源：http://dali.wangdashe.top/Article/details/gtpsukfaib.html

Java: System.err.println("err")
来源：http://dali.hysaishi.cn/Article/details/gtnzyekfca.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.cucudq.cn/Article/details/gtipjyaows.html

Ruby: warn "err"
来源：http://dali.hammf.cn/Article/details/gtcofejnkl.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.hnxiangtu.top/Article/details/gtyaobhyfm.html

[M07] 判断是否为主入口
来源：http://dali.svipenyu.cn/Article/details/gtnupfxaod.html

Py:   if __name__ == "__main__":
来源：http://dali.daria6918.cn/Article/details/gtiguhdnqj.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.sysykeji.top/Article/details/gtmbvzvqwo.html

JS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gtxjzawydw.html

TS:   require.main === module
来源：http://dali.andypj.xyz/Article/details/gtjzzalplc.html

Java: public static void main(String[] args)
来源：http://dali.cqqwz.cn/Article/details/gttszgzndw.html

Go:   func main()
来源：http://dali.dianchejie.cn/Article/details/gtisuucbgp.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.sweek.top/Article/details/gtkxybntjx.html

C#:   static void Main(string[] args)
来源：http://dali.shanyushiyangtech.top/Article/details/gtetmzaoux.html

[M08] 获取系统与运行时信息
来源：http://dali.andypj.xyz/Article/details/gtsaegxyne.html

Py:   platform.system();  platform.python_version()
来源：http://dali.iojbl.cn/Article/details/gtbrujnldk.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.hfpthk.cn/Article/details/gtrerblspq.html

JS:   process.platform;  process.version
来源：http://dali.nanxuanxn.top/Article/details/gtcrgopduw.html

TS:   process.platform;  process.version
来源：http://dali.guannengcc.top/Article/details/gtjwdwguuj.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.cucudq.cn/Article/details/gtidzjpkdt.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.bjfxy.top/Article/details/gtroyadyeq.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.pycfn.com/Article/details/gtrvlgqdwz.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.meibo888.top/Article/details/gtniqyrutt.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtilihpmny.html

N. 数据结构与算法
来源：http://dali.cdnleiting.top/Article/details/gtsbohrgwx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtfxarxqqm.html

[N01] 二分查找（有序数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtjtejmjej.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtscbhdgff.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.yj20258888.top/Article/details/gtkeqqnizc.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.fzhhl.top/Article/details/gtfaintltr.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.9152youxi.cn/Article/details/gtjmtghozi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gttjienmeg.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtawsifgap.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.chenzaomai.com/Article/details/gtqqribppi.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtmmpgntpq.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.sweek.top/Article/details/gtmqipsgzj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtkygspepc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtmbqityug.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.hammf.cn/Article/details/gtnruyvmii.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqfbeyay.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.cqqwz.cn/Article/details/gtapfjtlvr.html

Go:   slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmczblscm.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtqaftlosv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yongpay.top/Article/details/gtedxbjygm.html

[N03] 快速排序（分治示例）
来源：http://dali.shanyushiyangtech.top/Article/details/gtdefwjqtm.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.hongshengwenyu.top/Article/details/gtuliefsrk.html

PHP:  // 递归实现，或用 usort
来源：http://dali.gzhubu.top/Article/details/gtczdnfled.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.dashuyun.cn/Article/details/gteqgzxzug.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.gzhubu.top/Article/details/gthbjywmjd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hammf.cn/Article/details/gtvhtyzybf.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yj202588.top/Article/details/gtwvjitapm.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.0kj1m.cn/Article/details/gtmbuylzsj.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.wangshuangyany.cn/Article/details/gtmankpydz.html

[N04] 斐波那契数列
来源：http://dali.jyoumei.cn/Article/details/gtokjycldb.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.zhixingplan.top/Article/details/gtouexphgv.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.mhx1999.top/Article/details/gtuebprhim.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtbulavfhf.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.fengsongda.top/Article/details/gtkjsphfru.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgppnhln.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hfpthk.cn/Article/details/gtfdkiiebr.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgsgisra.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ehwqpu.com/Article/details/gtdwpfhxme.html

[N05] 最大公约数
来源：http://dali.gotoacloud.top/Article/details/gtclsmraia.html

Py:   math.gcd(a, b)
来源：http://dali.dianchejie.cn/Article/details/gtgzqkvzcu.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.cashguo.top/Article/details/gtzpuxnhun.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtwkqxdywj.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gtgpamrtfw.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.hammf.cn/Article/details/gtaknstzhi.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.mhx1999.top/Article/details/gtttlidrmu.html

Ruby: a.gcd(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtjkdmzjrc.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.gogol.net.cn/Article/details/gtlflzoate.html

[N06] 判断回文字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrxmsaiz.html

Py:   s == s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvwrelqn.html

PHP:  $s === strrev($s);
来源：http://dali.gzhubu.top/Article/details/gtpaouxvdo.html

JS:   s === [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtjrzgdddi.html

TS:   s === [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtdnpaqxwn.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.gotoacloud.top/Article/details/gtfobrklbz.html

Go:   // 双指针从两端比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocipwfly.html

Ruby: s == s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtxmyutrnp.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.xuetiantiany.cn/Article/details/gtewrqgjlp.html

[N07] 两数之和（返回下标）
来源：http://dali.9152youxi.cn/Article/details/gtjjzzbjcj.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.sxryk.cn/Article/details/gtkywganbo.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.xuetiantiany.cn/Article/details/gtdrgsgktr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.wangdashe.top/Article/details/gtvkkfslyn.html

TS:   // 手写 Map<string, number>
来源：http://dali.aizwys.cn/Article/details/gtpkimnpcp.html

Java: // 手写 HashMap
来源：http://dali.sweek.top/Article/details/gtisfwqjsp.html

Go:   // 手写 map[int]int
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnoynzqt.html

Ruby: // 手写 Hash
来源：http://dali.chenlongwang.top/Article/details/gtcdtscjes.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.aizwys.cn/Article/details/gtcspwhqhh.html

[N08] 生成全排列
来源：http://dali.0kj1m.cn/Article/details/gtpethdzut.html

Py:   itertools.permutations(arr)
来源：http://dali.jianghu66.top/Article/details/gtqkcbmrdl.html

PHP:  // 手写递归交换
来源：http://dali.kuanghao11.cn/Article/details/gtpsolxrjx.html

JS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtzrcbekwo.html

TS:   // 手写回溯递归
来源：http://dali.cqqwz.cn/Article/details/gtocmvrzxq.html

Java: // 手写回溯递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgbjhzuf.html

Go:   // 手写回溯递归
来源：http://dali.snrcjt.cn/Article/details/gtaxgblapt.html

Ruby: arr.permutation.to_a
来源：http://dali.zhoulong.xyz/Article/details/gtogfdltzw.html

C#:   // 手写回溯递归
来源：http://dali.smart0.xyz/Article/details/gthguhygzs.html

[N09] 栈与队列
来源：http://dali.shangyingyoupin.top/Article/details/gtopaiqfmc.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenjidiqi.icu/Article/details/gtncmskofv.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.chenlongwang.top/Article/details/gtbgjflijq.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gtmgmyzchs.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.zdqjudy.top/Article/details/gtawputqxg.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gogol.net.cn/Article/details/gtyqntdfbc.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jiagoushi.top/Article/details/gtiibeuzwf.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtaicaortp.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.jinqigufen.top/Article/details/gtotwkosyp.html

[N10] 链表节点定义
来源：http://dali.fzhhl.top/Article/details/gtstparmmz.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sxryk.cn/Article/details/gtmoewyfsh.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.nwbrower.top/Article/details/gtozqrtinl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtlrdskfys.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.cashguo.top/Article/details/gtovnfzeim.html

Java: class Node { int v; Node next; }
来源：http://dali.zdqjudy.top/Article/details/gtxgflirqt.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.zhengqikj.top/Article/details/gtlzkfokvm.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.hywenlv.cn/Article/details/gtjcayvzar.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnqzz.top/Article/details/gtetamwedm.html

[N11] 二叉树中序遍历
来源：http://dali.cheryme.top/Article/details/gtptrfrniw.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhongyouzk.top/Article/details/gttpcuqtiy.html

PHP:  // 手写递归函数
来源：http://dali.guowangkeji.top/Article/details/gtyparnzor.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.pycfn.com/Article/details/gtgckyrmpf.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ydzc1.top/Article/details/gtahdkbpbz.html

Java: // 手写递归
来源：http://dali.ppjwa.cn/Article/details/gtirhjsgpd.html

Go:   // 手写递归
来源：http://dali.hywenlv.cn/Article/details/gtvyraoush.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.zhaomingkeji.xyz/Article/details/gtluspdamh.html

C#:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gtnymytcla.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.havefunace.top/Article/details/gttiaixbrq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.svipenyu.cn/Article/details/gtwmitzjci.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.sufxvd.cn/Article/details/gtbaqrytis.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.gaohongyu789.top/Article/details/gtxngrpvyq.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jlsjyb.cn/Article/details/gtmzptjujx.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gtcyngdfhd.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.quarkkingdee.top/Article/details/gtirwonqby.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.gzhubu.top/Article/details/gthuyxpuik.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.hysaishi.cn/Article/details/gtplwpgsnn.html


<!-- 参考信息 -->