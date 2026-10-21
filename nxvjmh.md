代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbevjhzhs.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.jinqigfzy.top/Article/details/gtvhkqcsvj.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.xylfe.cn/Article/details/gtwuwgehip.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gtftotrdcw.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.dashuyun.cn/Article/details/gtzxljcnqc.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.cashguo.top/Article/details/gtwmvovbgt.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.bjfxy.top/Article/details/gtwqrrxfid.html

[K05] 深拷贝对象
来源：http://dali.bjfxy.top/Article/details/gttdxyhmir.html

Py:   copy.deepcopy(obj)
来源：http://dali.shzxlz.cn/Article/details/gtvnzhrqgj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.sysykeji.top/Article/details/gtcqdjzkdp.html

JS:   structuredClone(obj)
来源：http://dali.jiagoushi.top/Article/details/gtravmjqky.html

TS:   structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtiqejoeeq.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.vqdsnc.cn/Article/details/gtbqucjcdy.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.guannengcc.top/Article/details/gtbwwdmfwz.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.c1oappe.top/Article/details/gtxsvyngjy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.jianghu66.top/Article/details/gtghqsynsf.html

[K06] 解析 URL 查询串
来源：http://dali.ehwqpu.com/Article/details/gttpichaie.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.vqdsnc.cn/Article/details/gtrmrznxqi.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.bjfxy.top/Article/details/gtmzsjpuoq.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.zhongyouzk.top/Article/details/gtyjimqapy.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.hnxiangtu.top/Article/details/gtvywwflne.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.yvedp.cn/Article/details/gtisqkrjjw.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hfpthk.cn/Article/details/gticjlvypb.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.xylfe.cn/Article/details/gthaotgzar.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.hysaishi.cn/Article/details/gtwmtvargc.html

[K07] 进制转换
来源：http://dali.wangshuangyany.cn/Article/details/gtbkzywzmp.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.xuanzx.com/Article/details/gtfrmcqaxy.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.tanke756.top/Article/details/gtdfuwbulw.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.gzhubu.top/Article/details/gtlsgvpjwf.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gtekqihyxp.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqfbllece.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmsciosgd.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gtwqsyzfln.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.bjfxy.top/Article/details/gtbrybepxn.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.chenjidiqi.icu/Article/details/gtsoxelggv.html

Py:   pickle.dumps(obj)
来源：http://dali.jiagoushi.top/Article/details/gttfoaqmly.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xylfe.cn/Article/details/gtljltejdo.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.yuanzhike.top/Article/details/gtjkmbposy.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.jinqigfzy.top/Article/details/gtgqldryiy.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.xylfe.cn/Article/details/gtjatwknmr.html

Go:   encoding/gob
来源：http://dali.cheryme.top/Article/details/gtccdmebei.html

Ruby: Marshal.dump(obj)
来源：http://dali.xuetiantiany.cn/Article/details/gtpiunfmde.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gtowcikrjp.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxhvnuos.html

L. 网络请求
来源：http://dali.yj202588.top/Article/details/gtfkldnfdc.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtnogldifc.html

[L01] 发送 GET 请求
来源：http://dali.tianlin.xyz/Article/details/gtwzzkfyrq.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.sufxvd.cn/Article/details/gtxwxenrun.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yuxming.cn/Article/details/gtjoueehpd.html

JS:   await fetch(url)
来源：http://dali.pycfn.com/Article/details/gtrpeyfnmu.html

TS:   await fetch(url)
来源：http://dali.mhx1999.top/Article/details/gtnipljjpd.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.zhongyouzk.top/Article/details/gtuvjlmonm.html

Go:   resp, err := http.Get(url)
来源：http://dali.chenjidiqi.icu/Article/details/gtbuoevarp.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xylfe.cn/Article/details/gthjnhgofe.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.cheryme.top/Article/details/gtdzkkxoed.html

[L02] 发送 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gttuhdoqrk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.yanxiufei.cn/Article/details/gtjblffhfs.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.mhx1999.top/Article/details/gtptrhehxw.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpesvmmwo.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.gogol.net.cn/Article/details/gtvngncbut.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.iojbl.cn/Article/details/gttoyxrote.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.birdmap.top/Article/details/gthpnnhxmm.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.0kj1m.cn/Article/details/gtkcquvkuj.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.daria6918.cn/Article/details/gtkilnttak.html

[L03] 设置自定义请求头
来源：http://dali.yj20258.top/Article/details/gtlukfrqln.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.ydzc1.top/Article/details/gtawuhdikw.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.zycfv.cn/Article/details/gttjtgojyp.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.jqgufenzy.top/Article/details/gtplblnesk.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.yonumen.top/Article/details/gtvocnkxww.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.sxryk.cn/Article/details/gttgakttii.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.smart0.xyz/Article/details/gtzvfesgsl.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.yuanzhike.top/Article/details/gtckcpkbzn.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.shzxlz.cn/Article/details/gtrtywcuyo.html

[L04] 设置超时
来源：http://dali.yuanzhike.top/Article/details/gtfacsenxm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.hfpthk.cn/Article/details/gtghwaqjrw.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.shuidangran.top/Article/details/gtwwuenvhi.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ivvv.top/Article/details/gtvznaitui.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhijiandao.cn/Article/details/gtmswvkgeq.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.iojbl.cn/Article/details/gtyscykcgw.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.ehwqpu.com/Article/details/gtfllkjyub.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daria6918.cn/Article/details/gtjltzvtcl.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jqgufenzy.top/Article/details/gtpeemybtz.html

[L05] 上传文件（multipart）
来源：http://dali.zhoulong.xyz/Article/details/gtuejazieq.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.chenjidiqi.icu/Article/details/gtnbtmiwsb.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcjlavdg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.xinyue.icu/Article/details/gtqqtnxjeo.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nwbrower.top/Article/details/gtskcveleg.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hywenlv.cn/Article/details/gthvnoyehf.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.0kj1m.cn/Article/details/gtddqhhpng.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.shuidangran.top/Article/details/gtulzulpfm.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtyarppqvr.html

[L06] 解析响应为 JSON
来源：http://dali.jlsjyb.cn/Article/details/gttmmkoaxh.html

Py:   resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gtlemjmqow.html

PHP:  json_decode($body, true);
来源：http://dali.9152youxi.cn/Article/details/gtztvjsbhw.html

JS:   await resp.json()
来源：http://dali.jyoumei.cn/Article/details/gtmuhqovsc.html

TS:   await resp.json()
来源：http://dali.shuidangran.top/Article/details/gtllfuzbad.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.redwolf501.top/Article/details/gtfvnjmqbq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.aibaodan.cn/Article/details/gtzyqrfiie.html

Ruby: JSON.parse(resp.body)
来源：http://dali.aibaodan.cn/Article/details/gtpithiafh.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.sufxvd.cn/Article/details/gtxnyvxmhm.html

[L07] 处理 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gthspxhytq.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.xylfe.cn/Article/details/gtorngwzfo.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.meibo888.top/Article/details/gtjjwwrmkv.html

JS:   resp.ok;  resp.status
来源：http://dali.gzhubu.top/Article/details/gthopjztpl.html

TS:   resp.ok;  resp.status
来源：http://dali.daria6918.cn/Article/details/gtcwdfrpai.html

Java: resp.statusCode()
来源：http://dali.yj20258888.top/Article/details/gtvvewxgif.html

Go:   resp.StatusCode
来源：http://dali.zhijiandao.cn/Article/details/gtrjmoanex.html

Ruby: resp.code.to_i
来源：http://dali.hywenlv.cn/Article/details/gteqqvdcqb.html

C#:   (int)resp.StatusCode
来源：http://dali.guowangkeji.top/Article/details/gtubwnfpta.html

[L08] 并发请求多个地址
来源：http://dali.cdnleiting.top/Article/details/gtyneyuwom.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.yuxming.cn/Article/details/gtbizcwmif.html

PHP:  curl_multi_init() 系列
来源：http://dali.redwolf501.top/Article/details/gtmszfjrsp.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtjaymfuin.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.9152youxi.cn/Article/details/gtefnamzlm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.zhijiandao.cn/Article/details/gtxkcrercv.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.yj20258.top/Article/details/gtblciaexh.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.gzhubu.top/Article/details/gtwfdianqc.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.ppjwa.cn/Article/details/gtohxzwtrz.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtmmdbawij.html

M. 命令行 / 进程 / 环境
来源：http://dali.guowangkeji.top/Article/details/gtrztplkve.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtkrmmknkw.html

[M01] 读取命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtqwrblhvw.html

Py:   sys.argv[1:]
来源：http://dali.316326.xyz/Article/details/gtwtkqmwbu.html

PHP:  $argv;  $argc;
来源：http://dali.aizwys.cn/Article/details/gtepgehyng.html

JS:   process.argv.slice(2)
来源：http://dali.daria6918.cn/Article/details/gtvzurixws.html

TS:   process.argv.slice(2)
来源：http://dali.cheryme.top/Article/details/gtgvrudkci.html

Java: args 数组（main 方法参数）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnoilwzpe.html

Go:   os.Args[1:]
来源：http://dali.ehwqpu.com/Article/details/gtjbfzmmtx.html

Ruby: ARGV
来源：http://dali.zycfv.cn/Article/details/gtcvvukxbe.html

C#:   args 数组（Main 方法参数）
来源：http://dali.haohaochexian.top/Article/details/gtfyeqtswa.html

[M02] 读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuvbjwas.html

Py:   os.environ.get("HOME")
来源：http://dali.yj20258888.top/Article/details/gtvfeoztfc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.andypj.xyz/Article/details/gtqvvwhbvs.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gtmtralcej.html

TS:   process.env.HOME
来源：http://dali.c1oappe.top/Article/details/gtlwsmvzng.html

Java: System.getenv("HOME")
来源：http://dali.jinqigfzy.top/Article/details/gtdtzhpopk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.smart0.xyz/Article/details/gtclpdubuo.html

Ruby: ENV["HOME"]
来源：http://dali.jiagoushi.top/Article/details/gtuqqpxxli.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.andypj.xyz/Article/details/gthyhdkjsg.html

[M03] 执行外部命令
来源：http://dali.sysykeji.top/Article/details/gtpgsmfjgx.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.chenlongwang.top/Article/details/gtbtusyuul.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenlongwang.top/Article/details/gtelmjdrbq.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlhpbyqni.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gtmeqdjkbd.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxuanxn.top/Article/details/gtolrvudok.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.shangyingyoupin.top/Article/details/gtoybvbdgv.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.zhijiandao.cn/Article/details/gtrzqbkamk.html

C#:   Process.Start("ls", "-l");
来源：http://dali.zycfv.cn/Article/details/gtjlaqgseb.html

[M04] 获取当前工作目录
来源：http://dali.yuanzhike.top/Article/details/gtdavkhjun.html

Py:   os.getcwd()
来源：http://dali.yj20258888.top/Article/details/gtxehawmiz.html

PHP:  getcwd();
来源：http://dali.cashguo.top/Article/details/gtxslokkoh.html

JS:   process.cwd()
来源：http://dali.zhengqikj.top/Article/details/gtrkevaosu.html

TS:   process.cwd()
来源：http://dali.gzhubu.top/Article/details/gtcoeskrge.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrztxgzgb.html

Go:   os.Getwd()
来源：http://dali.yueranfly.top/Article/details/gtrxaiezbd.html

Ruby: Dir.pwd
来源：http://dali.cucudq.cn/Article/details/gtaobqejnr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nwbrower.top/Article/details/gtufyerlky.html

[M05] 设置退出码
来源：http://dali.guannengcc.top/Article/details/gtkshknscl.html

Py:   sys.exit(1)
来源：http://dali.yj202588.top/Article/details/gteigzkxal.html

PHP:  exit(1);
来源：http://dali.cdnleiting.top/Article/details/gtvzxuvgjh.html

JS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gtdmivmqhr.html

TS:   process.exit(1)
来源：http://dali.guowangkeji.top/Article/details/gtyaxupdth.html

Java: System.exit(1)
来源：http://dali.yj20258.top/Article/details/gtuoseqbwq.html

Go:   os.Exit(1)
来源：http://dali.nanxuanxn.top/Article/details/gtwbzqxddu.html

Ruby: exit 1
来源：http://dali.dashuyun.cn/Article/details/gtroaoyzqu.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.kuanghao11.cn/Article/details/gtndulsywk.html

[M06] 向标准错误输出
来源：http://dali.hfpthk.cn/Article/details/gtxbaslzbn.html

Py:   print("err", file=sys.stderr)
来源：http://dali.dashuyun.cn/Article/details/gtbnjhyruj.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.xuetiantiany.cn/Article/details/gtfmdvztsw.html

JS:   console.error("err")
来源：http://dali.316326.xyz/Article/details/gtajpcvekk.html

TS:   console.error("err")
来源：http://dali.cashguo.top/Article/details/gtsvjxifyy.html

Java: System.err.println("err")
来源：http://dali.hongshengwenyu.top/Article/details/gtohovwkab.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.birdmap.top/Article/details/gtzkmgrvkc.html

Ruby: warn "err"
来源：http://dali.havefunace.top/Article/details/gtxijnbuua.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.9152youxi.cn/Article/details/gtohqcjdkg.html

[M07] 判断是否为主入口
来源：http://dali.meibo888.top/Article/details/gtjootlqjw.html

Py:   if __name__ == "__main__":
来源：http://dali.sweek.top/Article/details/gtmirmdslt.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.cqqwz.cn/Article/details/gtmhghqqhh.html

JS:   require.main === module
来源：http://dali.yangfankeji.com/Article/details/gtsvkdfrcf.html

TS:   require.main === module
来源：http://dali.svipenyu.cn/Article/details/gtotqydjii.html

Java: public static void main(String[] args)
来源：http://dali.daria6918.cn/Article/details/gtqrotqqmx.html

Go:   func main()
来源：http://dali.yuanzhike.top/Article/details/gtzgodzaoy.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.ivvv.top/Article/details/gtddkpjpxy.html

C#:   static void Main(string[] args)
来源：http://dali.svipenyu.cn/Article/details/gteznbrqul.html

[M08] 获取系统与运行时信息
来源：http://dali.birdmap.top/Article/details/gthplqykfl.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gogol.net.cn/Article/details/gtxmtvooep.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.daria6918.cn/Article/details/gthvefxtkn.html

JS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gtneqtejnr.html

TS:   process.platform;  process.version
来源：http://dali.ppjwa.cn/Article/details/gtfequtjwk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.jiagoushi.top/Article/details/gterlxerta.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.jqgfzy.top/Article/details/gtduzouers.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.0kj1m.cn/Article/details/gtgmepwhpe.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.hongshengwenyu.top/Article/details/gtbfcmzhcx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtuhxplvgi.html

N. 数据结构与算法
来源：http://dali.dianchejie.cn/Article/details/gtoyiapesa.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtyfqiygxy.html

[N01] 二分查找（有序数组）
来源：http://dali.jqgfzy.top/Article/details/gtgghzjhas.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gtgbaeffeu.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.xuanzx.com/Article/details/gtnyiiozzt.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgdhjvbx.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.hnxiangtu.top/Article/details/gtqogutfsi.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtpqebmsqf.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtjwxlmqzq.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxmjikkp.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmwpyhfu.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.hfpthk.cn/Article/details/gtzmsbgopm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtvozgfoxd.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.yuanzhike.top/Article/details/gtflmoknkj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtwlyuoxik.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtrfdorqyc.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zhixingplan.top/Article/details/gtrbigamrl.html

Go:   slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gtkiaqjtvf.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gthaviqtek.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.yueranfly.top/Article/details/gtiiskmmkz.html

[N03] 快速排序（分治示例）
来源：http://dali.sweek.top/Article/details/gtuzkhltnq.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.yuanzhike.top/Article/details/gtbigbspiu.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xuanzx.com/Article/details/gtwpqeonui.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.yj202588.top/Article/details/gtiridajxr.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jqgfzy.top/Article/details/gtlijekrec.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtfozzqmxl.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.nanxuanxn.top/Article/details/gtopcafysa.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daria6918.cn/Article/details/gtcrcngjzh.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.pycfn.com/Article/details/gtfphsrmlw.html

[N04] 斐波那契数列
来源：http://dali.bjfxy.top/Article/details/gtxfnwhhta.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.yonumen.top/Article/details/gtbivtaoqm.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpzvozkc.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cheryme.top/Article/details/gteebsyfwt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cashguo.top/Article/details/gtaicmwprc.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.sxryk.cn/Article/details/gttnirpayv.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.yj20258888.top/Article/details/gtkevahvzc.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.birdmap.top/Article/details/gtjakbqjte.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.yvedp.cn/Article/details/gtbmhisexd.html

[N05] 最大公约数
来源：http://dali.tian-w.cn/Article/details/gtwluahmve.html

Py:   math.gcd(a, b)
来源：http://dali.nanxinkj.top/Article/details/gtjrsmhffy.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.c1oappe.top/Article/details/gtcxxhaxwr.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.jinqigfzy.top/Article/details/gtiocnwipw.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.aizwys.cn/Article/details/gtbwhfffvs.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daxiang520.top/Article/details/gtscdbhdjk.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.cqqwz.cn/Article/details/gtccqfwjsr.html

Ruby: a.gcd(b)
来源：http://dali.hnxiangtu.top/Article/details/gtwnhkpskw.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.svipenyu.cn/Article/details/gtmvfndgbm.html

[N06] 判断回文字符串
来源：http://dali.sysykeji.top/Article/details/gtnaaohvwi.html

Py:   s == s[::-1]
来源：http://dali.hnxiangtu.top/Article/details/gtxvgacgid.html

PHP:  $s === strrev($s);
来源：http://dali.aizwys.cn/Article/details/gtwsppgeuk.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtjrpcibqa.html

TS:   s === [...s].reverse().join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcquxpwno.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.feifeiyinyue.top/Article/details/gtxevviqxt.html

Go:   // 双指针从两端比较
来源：http://dali.sxryk.cn/Article/details/gtqqqmbohz.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdmehkvw.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.aibaodan.cn/Article/details/gtwbzpobtg.html

[N07] 两数之和（返回下标）
来源：http://dali.jqgufenzy.top/Article/details/gtidxzocyi.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.ehwqpu.com/Article/details/gtwbnjmbcj.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yj20258.top/Article/details/gtrzfsasiz.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyiivdlyk.html

TS:   // 手写 Map<string, number>
来源：http://dali.daria6918.cn/Article/details/gthypjbqka.html

Java: // 手写 HashMap
来源：http://dali.havefunace.top/Article/details/gtrzqdgrlz.html

Go:   // 手写 map[int]int
来源：http://dali.gaohongyu789.top/Article/details/gtxajpfxyp.html

Ruby: // 手写 Hash
来源：http://dali.svipenyu.cn/Article/details/gteoxxgosr.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinqigfzy.top/Article/details/gtkoifvnzj.html

[N08] 生成全排列
来源：http://dali.wangdashe.top/Article/details/gtoljbsbgz.html

Py:   itertools.permutations(arr)
来源：http://dali.cashguo.top/Article/details/gtijttyzxd.html

PHP:  // 手写递归交换
来源：http://dali.vqdsnc.cn/Article/details/gtqhwqammm.html

JS:   // 手写回溯递归
来源：http://dali.hysaishi.cn/Article/details/gtbecpkgwp.html

TS:   // 手写回溯递归
来源：http://dali.pengpengdd.cyou/Article/details/gtuphbpsfr.html

Java: // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gtsojjoczf.html

Go:   // 手写回溯递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvixklch.html

Ruby: arr.permutation.to_a
来源：http://dali.quarkkingdee.top/Article/details/gttufwzbdz.html

C#:   // 手写回溯递归
来源：http://dali.xuetiantiany.cn/Article/details/gtfnnkcaak.html

[N09] 栈与队列
来源：http://dali.aizwys.cn/Article/details/gtbkseokhe.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.zhoulong.xyz/Article/details/gtpsnsmnna.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.fzhhl.top/Article/details/gtbgbcamhs.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtqhjbbpcp.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.pengpengdd.cyou/Article/details/gtdfpqrdhv.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.chenjidiqi.icu/Article/details/gtijuscwzq.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.zhongyouzk.top/Article/details/gtwydtwpxu.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.9152youxi.cn/Article/details/gtfpmifvun.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.daxiang520.top/Article/details/gtvaealixl.html

[N10] 链表节点定义
来源：http://dali.jyoumei.cn/Article/details/gtnkehfnss.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.xuetiantiany.cn/Article/details/gtfjkuwvhm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.jlsjyb.cn/Article/details/gtgryfwlzl.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.pengpengdd.cyou/Article/details/gthsbfgxeq.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.tianlin.xyz/Article/details/gtqxhevaoc.html

Java: class Node { int v; Node next; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthujmtecz.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.jiagoushi.top/Article/details/gtlzgkymop.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.9152youxi.cn/Article/details/gtpgnoeygl.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.aizwys.cn/Article/details/gtypbrxwpm.html

[N11] 二叉树中序遍历
来源：http://dali.bjfxy.top/Article/details/gtzkmpavvk.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.zhongyouzk.top/Article/details/gtsigafdwk.html

PHP:  // 手写递归函数
来源：http://dali.jyoumei.cn/Article/details/gtykrrusox.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.gzhubu.top/Article/details/gtewvvfepn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaovlpurt.html

Java: // 手写递归
来源：http://dali.0kj1m.cn/Article/details/gtuvdndqey.html

Go:   // 手写递归
来源：http://dali.hammf.cn/Article/details/gtdhsnkasx.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.iojbl.cn/Article/details/gttywdvcjp.html

C#:   // 手写递归
来源：http://dali.fengsongda.top/Article/details/gtqklfbsrk.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.gzhubu.top/Article/details/gtemsmhwfn.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcebiqrrc.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.0kj1m.cn/Article/details/gtdeklpvze.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ehwqpu.com/Article/details/gthvpwrqjm.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.ydzc1.top/Article/details/gtkzdjurhy.html


<!-- 参考信息 -->