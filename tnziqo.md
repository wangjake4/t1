代发 wailian999

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.316326.xyz/Article/details/gtoazkrvrr.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.ehwqpu.com/Article/details/gtrrdredou.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.c1oappe.top/Article/details/gtbnexqxbr.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.chenlongwang.top/Article/details/gthqicoqsq.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gtxidfmdon.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.dashuyun.cn/Article/details/gtimnastsk.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.xuetiantiany.cn/Article/details/gtyaernhhy.html

[K05] 深拷贝对象
来源：http://dali.yuanzhike.top/Article/details/gthctsmsok.html

Py:   copy.deepcopy(obj)
来源：http://dali.birdmap.top/Article/details/gtpdstcdqj.html

PHP:  unserialize(serialize($obj));
来源：http://dali.iojbl.cn/Article/details/gtpbseqxdz.html

JS:   structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtmpznlsvu.html

TS:   structuredClone(obj)
来源：http://dali.vqdsnc.cn/Article/details/gtojjicjur.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.sweek.top/Article/details/gtcchumavu.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.316326.xyz/Article/details/gtjkkaizmk.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.yj20258.top/Article/details/gthupeevmp.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.tianlin.xyz/Article/details/gtwjcrvetj.html

[K06] 解析 URL 查询串
来源：http://dali.shangyingyoupin.top/Article/details/gtqcadswym.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.zhiwuduotai.top/Article/details/gtcfiguxgp.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.dashuyun.cn/Article/details/gtdaftsdvn.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.feifeiyinyue.top/Article/details/gtuxrtnweq.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.sysykeji.top/Article/details/gtwlattcgp.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.chenjidiqi.icu/Article/details/gtlpyhedib.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.zhijiandao.cn/Article/details/gtiliwsosk.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.jyoumei.cn/Article/details/gtindzyfzv.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gtplwpgevj.html

[K07] 进制转换
来源：http://dali.zhiwuduotai.top/Article/details/gtnvyjhwnu.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.quarkkingdee.top/Article/details/gtjrzjotlv.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.haohaochexian.top/Article/details/gtrqdbjmtr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.sufxvd.cn/Article/details/gtrlxpngmc.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gtnbijvcvs.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.ybcxt.top/Article/details/gtoxlgmxva.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.xziqi.cn/Article/details/gtmdxnrkkt.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.quarkkingdee.top/Article/details/gtnowoyvae.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ydzc1.top/Article/details/gtcurahgoi.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.zhixingplan.top/Article/details/gtnpcaczfo.html

Py:   pickle.dumps(obj)
来源：http://dali.birdmap.top/Article/details/gtubobvdpi.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.xziqi.cn/Article/details/gtmlizttxx.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqazygmzw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.zycfv.cn/Article/details/gtpsvpckmt.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.ivvv.top/Article/details/gtxaxgmdzp.html

Go:   encoding/gob
来源：http://dali.aizwys.cn/Article/details/gtqzzivler.html

Ruby: Marshal.dump(obj)
来源：http://dali.zhoulong.xyz/Article/details/gtspnjulav.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.shzxlz.cn/Article/details/gtpxrthkmw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtoksfohzv.html

L. 网络请求
来源：http://dali.hammf.cn/Article/details/gtmovayctr.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtyftnozqu.html

[L01] 发送 GET 请求
来源：http://dali.hammf.cn/Article/details/gtrthawzzw.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.ehwqpu.com/Article/details/gtkmvittnp.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.daxiang520.top/Article/details/gtochirqdp.html

JS:   await fetch(url)
来源：http://dali.yuxming.cn/Article/details/gtuuuunyuv.html

TS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gtquazmgtl.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.jlsjyb.cn/Article/details/gtpbodhldc.html

Go:   resp, err := http.Get(url)
来源：http://dali.sxryk.cn/Article/details/gtvhoqrqob.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.zhiwuduotai.top/Article/details/gtyywbbwko.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.hfpthk.cn/Article/details/gtcnmhoqie.html

[L02] 发送 POST JSON
来源：http://dali.cashguo.top/Article/details/gtkvakwizi.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexarmgqx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jiagoushi.top/Article/details/gtumjfmbzm.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.daxiang520.top/Article/details/gtkodxsyty.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gtsbyvnwhk.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.sweek.top/Article/details/gtvahtuxiu.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepqlssdl.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.shangyingyoupin.top/Article/details/gtulhptonv.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.xziqi.cn/Article/details/gtwyyvpwaa.html

[L03] 设置自定义请求头
来源：http://dali.sysykeji.top/Article/details/gttrjldzam.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuejcysjv.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.jinqigufen.top/Article/details/gtaryzbbpu.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.bjfxy.top/Article/details/gtuevmavrv.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhauzchd.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwanqhjnb.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.shangyingyoupin.top/Article/details/gtsnyeslno.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.quarkkingdee.top/Article/details/gtyzcscaln.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.yongpay.top/Article/details/gtymrcgndf.html

[L04] 设置超时
来源：http://dali.hammf.cn/Article/details/gtvtflcmrm.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yonumen.top/Article/details/gtlbxbtjuv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.iojbl.cn/Article/details/gtjglcwlhf.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.c1oappe.top/Article/details/gtivkxgcno.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zhongyouzk.top/Article/details/gtwperctry.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.jyoumei.cn/Article/details/gtdsxwxdau.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.mhx1999.top/Article/details/gtkvhuinew.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.daxiang520.top/Article/details/gtjmstepje.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.jlsjyb.cn/Article/details/gtpcndgfow.html

[L05] 上传文件（multipart）
来源：http://dali.hongshengwenyu.top/Article/details/gtgjrooxne.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zhijiandao.cn/Article/details/gtygbhazig.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.jqgfzy.top/Article/details/gtmigarefa.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxezwcuc.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.nanxuanxn.top/Article/details/gtkjydcljx.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.hnqzz.top/Article/details/gtmskzzamh.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.ppjwa.cn/Article/details/gtwxeorxdp.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.cdnleiting.top/Article/details/gtuloubdyt.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtqcdszkro.html

[L06] 解析响应为 JSON
来源：http://dali.zdqjudy.top/Article/details/gtyhdiurzb.html

Py:   resp.json()
来源：http://dali.sxryk.cn/Article/details/gtmbtbdwvp.html

PHP:  json_decode($body, true);
来源：http://dali.c1oappe.top/Article/details/gtfndeahps.html

JS:   await resp.json()
来源：http://dali.jinqigfzy.top/Article/details/gtbbpexymk.html

TS:   await resp.json()
来源：http://dali.ehwqpu.com/Article/details/gtnofwcniv.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.dashuyun.cn/Article/details/gtbmwtbnil.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttdxtjzta.html

Ruby: JSON.parse(resp.body)
来源：http://dali.fzhhl.top/Article/details/gtiwbmromj.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.ivvv.top/Article/details/gtyrdvbzsl.html

[L07] 处理 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtjthocvfi.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhijiandao.cn/Article/details/gtijzpivya.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.vqdsnc.cn/Article/details/gtwaxkqczb.html

JS:   resp.ok;  resp.status
来源：http://dali.hongshengwenyu.top/Article/details/gtovoubmnr.html

TS:   resp.ok;  resp.status
来源：http://dali.cashguo.top/Article/details/gtmzctkihf.html

Java: resp.statusCode()
来源：http://dali.zhixingplan.top/Article/details/gtgrlrpdsu.html

Go:   resp.StatusCode
来源：http://dali.jinghuilouyu.cn/Article/details/gtjahoukej.html

Ruby: resp.code.to_i
来源：http://dali.yuxming.cn/Article/details/gtiojpbtwn.html

C#:   (int)resp.StatusCode
来源：http://dali.ydzc1.top/Article/details/gtrzfclogx.html

[L08] 并发请求多个地址
来源：http://dali.yueranfly.top/Article/details/gtzvojocyx.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.havefunace.top/Article/details/gtmslbxnqm.html

PHP:  curl_multi_init() 系列
来源：http://dali.xylfe.cn/Article/details/gtylxdbysz.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yueranfly.top/Article/details/gtcezjfdjb.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gthoxabiiv.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.gaohongyu789.top/Article/details/gtcwfjrrul.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.nwbrower.top/Article/details/gtiqemvcoi.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.andypj.xyz/Article/details/gthrkteyrw.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.shzxlz.cn/Article/details/gtjmdxrmpt.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtdbjidaxq.html

M. 命令行 / 进程 / 环境
来源：http://dali.chenjidiqi.icu/Article/details/gtijkzjehn.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtoubptsdo.html

[M01] 读取命令行参数
来源：http://dali.birdmap.top/Article/details/gtstlwhtgl.html

Py:   sys.argv[1:]
来源：http://dali.tianlin.xyz/Article/details/gtnzggliae.html

PHP:  $argv;  $argc;
来源：http://dali.ybcxt.top/Article/details/gtjwzaidep.html

JS:   process.argv.slice(2)
来源：http://dali.jqgufenzy.top/Article/details/gtzhzbjivg.html

TS:   process.argv.slice(2)
来源：http://dali.redwolf501.top/Article/details/gteswegael.html

Java: args 数组（main 方法参数）
来源：http://dali.hnxiangtu.top/Article/details/gtnmtxxrlm.html

Go:   os.Args[1:]
来源：http://dali.xziqi.cn/Article/details/gtmzmwqfts.html

Ruby: ARGV
来源：http://dali.iojbl.cn/Article/details/gtfkilmwfg.html

C#:   args 数组（Main 方法参数）
来源：http://dali.jqgfzy.top/Article/details/gtzyqawtir.html

[M02] 读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gtlilslukp.html

Py:   os.environ.get("HOME")
来源：http://dali.sysykeji.top/Article/details/gtwlehxmlw.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtuakqjb.html

JS:   process.env.HOME
来源：http://dali.shuidangran.top/Article/details/gtwgfeoflm.html

TS:   process.env.HOME
来源：http://dali.zhiwuduotai.top/Article/details/gtvhbyhrrh.html

Java: System.getenv("HOME")
来源：http://dali.hnqzz.top/Article/details/gthyhuvejc.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzllxrqo.html

Ruby: ENV["HOME"]
来源：http://dali.0kj1m.cn/Article/details/gtfitwbmuq.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.nwbrower.top/Article/details/gtjjgexmpw.html

[M03] 执行外部命令
来源：http://dali.birdmap.top/Article/details/gtjexmnspp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.kuanghao11.cn/Article/details/gtqumhmzgg.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.chenzaomai.com/Article/details/gtmgdslmad.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.hysaishi.cn/Article/details/gtsmhgjzen.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.zhiwuduotai.top/Article/details/gtvfjigrqp.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.zhengqikj.top/Article/details/gtdufdhwmb.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.snrcjt.cn/Article/details/gtqizrawnh.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.snrcjt.cn/Article/details/gtoypeqcuc.html

C#:   Process.Start("ls", "-l");
来源：http://dali.haohaochexian.top/Article/details/gtdsemomtf.html

[M04] 获取当前工作目录
来源：http://dali.andypj.xyz/Article/details/gtjuwgggup.html

Py:   os.getcwd()
来源：http://dali.gotoacloud.top/Article/details/gtuwjynxea.html

PHP:  getcwd();
来源：http://dali.bjfxy.top/Article/details/gtfsanplgm.html

JS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gtxzgcyvwn.html

TS:   process.cwd()
来源：http://dali.mhx1999.top/Article/details/gtkrdlrnbh.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.fengsongda.top/Article/details/gtoqbrikoc.html

Go:   os.Getwd()
来源：http://dali.daria6918.cn/Article/details/gtyhlfkjhs.html

Ruby: Dir.pwd
来源：http://dali.cucudq.cn/Article/details/gtrycxwxrr.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.zycfv.cn/Article/details/gtceuqnmmm.html

[M05] 设置退出码
来源：http://dali.zycfv.cn/Article/details/gtzraqnwmq.html

Py:   sys.exit(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxsaqats.html

PHP:  exit(1);
来源：http://dali.316326.xyz/Article/details/gtrjqfdzuf.html

JS:   process.exit(1)
来源：http://dali.ydzc1.top/Article/details/gtikmhzzvx.html

TS:   process.exit(1)
来源：http://dali.shzxlz.cn/Article/details/gtxobwpwvm.html

Java: System.exit(1)
来源：http://dali.gaohongyu789.top/Article/details/gtducmapum.html

Go:   os.Exit(1)
来源：http://dali.sysykeji.top/Article/details/gtypvbddte.html

Ruby: exit 1
来源：http://dali.0kj1m.cn/Article/details/gtgmgxvrve.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.chenzaomai.com/Article/details/gtzxldozrp.html

[M06] 向标准错误输出
来源：http://dali.dianchejie.cn/Article/details/gtqzicayat.html

Py:   print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtymjyvgoz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.shuidangran.top/Article/details/gthuybgvvl.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gtfconvyjs.html

TS:   console.error("err")
来源：http://dali.hnqzz.top/Article/details/gtcdfugyzp.html

Java: System.err.println("err")
来源：http://dali.ivvv.top/Article/details/gtatowieif.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.ivvv.top/Article/details/gtqhpqaofv.html

Ruby: warn "err"
来源：http://dali.gaohongyu789.top/Article/details/gtxzuqzfkq.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.bjfxy.top/Article/details/gtvhvuksbg.html

[M07] 判断是否为主入口
来源：http://dali.cashguo.top/Article/details/gtwjctjkrn.html

Py:   if __name__ == "__main__":
来源：http://dali.meibo888.top/Article/details/gtduhjaett.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.0kj1m.cn/Article/details/gtwcvssotj.html

JS:   require.main === module
来源：http://dali.wangshuangyany.cn/Article/details/gtqrtnflvy.html

TS:   require.main === module
来源：http://dali.zycfv.cn/Article/details/gtejqsuvcz.html

Java: public static void main(String[] args)
来源：http://dali.zdqjudy.top/Article/details/gtdfyylaga.html

Go:   func main()
来源：http://dali.fzhhl.top/Article/details/gtbssvruno.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.gotoacloud.top/Article/details/gthzvtakzr.html

C#:   static void Main(string[] args)
来源：http://dali.haohaochexian.top/Article/details/gtixndfxmk.html

[M08] 获取系统与运行时信息
来源：http://dali.zhijiandao.cn/Article/details/gtbluyzwxw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.cheryme.top/Article/details/gtyimhjphj.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.fzhhl.top/Article/details/gtegcvzndj.html

JS:   process.platform;  process.version
来源：http://dali.ehwqpu.com/Article/details/gttqehvimi.html

TS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gtomuxheiz.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.hongshengwenyu.top/Article/details/gtlavzqtxu.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.ehwqpu.com/Article/details/gtpqfnpcir.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.jinyuanbaomall.cn/Article/details/gtukncgvhi.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.gaohongyu789.top/Article/details/gtgpboepoy.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtjsupcpco.html

N. 数据结构与算法
来源：http://dali.tianlin.xyz/Article/details/gtgflwstir.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtfthvuaxi.html

[N01] 二分查找（有序数组）
来源：http://dali.nanxinkj.top/Article/details/gtaefxamzs.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.chenjidiqi.icu/Article/details/gtpgsvfxzg.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.hysaishi.cn/Article/details/gtcfcjhhul.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.gzhubu.top/Article/details/gtytalfkki.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.cucudq.cn/Article/details/gtznxrcxri.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gttujjenob.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtseovells.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nanxuanxn.top/Article/details/gthanwnqul.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.wangdashe.top/Article/details/gtmokxavzd.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.nwbrower.top/Article/details/gtkdrlyiph.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtrbdprsji.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zdqjudy.top/Article/details/gtkjqihwsf.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtflyivscz.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.pycfn.com/Article/details/gtygitkdza.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzuzipgtm.html

Go:   slices.Sort(arr)
来源：http://dali.shzxlz.cn/Article/details/gtygrppthx.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gtbwddtggk.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hongshengwenyu.top/Article/details/gtddjhpuar.html

[N03] 快速排序（分治示例）
来源：http://dali.yangfankeji.com/Article/details/gtowcarlhd.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.redwolf501.top/Article/details/gtqbenfhcy.html

PHP:  // 递归实现，或用 usort
来源：http://dali.ydzc1.top/Article/details/gtfeafnqzj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gtxcozqstg.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinghuilouyu.cn/Article/details/gtyclcqcgd.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.hnxiangtu.top/Article/details/gthhblhsal.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zdqjudy.top/Article/details/gtmrynfarp.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.dianchejie.cn/Article/details/gtszdwnwvo.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.andypj.xyz/Article/details/gtqafxebqx.html

[N04] 斐波那契数列
来源：http://dali.hywenlv.cn/Article/details/gtcywlvhun.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.chenzaomai.com/Article/details/gtnsninbcx.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxuanxn.top/Article/details/gtyberjsgs.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jiagoushi.top/Article/details/gtwfglzlyt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.jlsjyb.cn/Article/details/gtxvcbfyei.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.jinqigufen.top/Article/details/gtsigrwmdr.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.jianghu66.top/Article/details/gtzmdgvhqt.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.xylfe.cn/Article/details/gtfvkluibk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.nanxuanxn.top/Article/details/gtpjzgstic.html

[N05] 最大公约数
来源：http://dali.zhoulong.xyz/Article/details/gtjowarznw.html

Py:   math.gcd(a, b)
来源：http://dali.iojbl.cn/Article/details/gtwnbduqct.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.yueranfly.top/Article/details/gtuxlmjhwv.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.cheryme.top/Article/details/gtreviuqvy.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.hywenlv.cn/Article/details/gtzdxshsbd.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.ybcxt.top/Article/details/gtfadoptky.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.guowangkeji.top/Article/details/gtmxetrigx.html

Ruby: a.gcd(b)
来源：http://dali.xinyue.icu/Article/details/gtqkpacmru.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.chenjidiqi.icu/Article/details/gtrhsfivgr.html

[N06] 判断回文字符串
来源：http://dali.havefunace.top/Article/details/gtxdwveuhe.html

Py:   s == s[::-1]
来源：http://dali.zhixingplan.top/Article/details/gtkpagicka.html

PHP:  $s === strrev($s);
来源：http://dali.haohaochexian.top/Article/details/gttsufkwsb.html

JS:   s === [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtqdmbcjzr.html

TS:   s === [...s].reverse().join("")
来源：http://dali.hywenlv.cn/Article/details/gtuwxeylao.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.havefunace.top/Article/details/gteopmziyx.html

Go:   // 双指针从两端比较
来源：http://dali.guannengcc.top/Article/details/gthsqwflbl.html

Ruby: s == s.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtppretzsx.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhqmckcq.html

[N07] 两数之和（返回下标）
来源：http://dali.hysaishi.cn/Article/details/gtxqiwyeqc.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.iojbl.cn/Article/details/gttbeqjkyg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.havefunace.top/Article/details/gtqszqynzm.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.c1oappe.top/Article/details/gtxsagzuwd.html

TS:   // 手写 Map<string, number>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjijifnvi.html

Java: // 手写 HashMap
来源：http://dali.yonumen.top/Article/details/gtpoucgwow.html

Go:   // 手写 map[int]int
来源：http://dali.pengpengdd.cyou/Article/details/gtwwvcpwmy.html

Ruby: // 手写 Hash
来源：http://dali.ppjwa.cn/Article/details/gtcqoaqytp.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.jinyuanbaomall.cn/Article/details/gteqaunysm.html

[N08] 生成全排列
来源：http://dali.yj202588.top/Article/details/gtocmhlcts.html

Py:   itertools.permutations(arr)
来源：http://dali.ybcxt.top/Article/details/gtanysxyva.html

PHP:  // 手写递归交换
来源：http://dali.hfpthk.cn/Article/details/gtpxysnxvn.html

JS:   // 手写回溯递归
来源：http://dali.hnqzz.top/Article/details/gtdpropkac.html

TS:   // 手写回溯递归
来源：http://dali.havefunace.top/Article/details/gtniaxbkbc.html

Java: // 手写回溯递归
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkhbjvdi.html

Go:   // 手写回溯递归
来源：http://dali.sxryk.cn/Article/details/gtjespokpj.html

Ruby: arr.permutation.to_a
来源：http://dali.aibaodan.cn/Article/details/gtrfurrlyf.html

C#:   // 手写回溯递归
来源：http://dali.hnxiangtu.top/Article/details/gtciylbvhg.html

[N09] 栈与队列
来源：http://dali.yj20258888.top/Article/details/gtnztprslh.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.chenzaomai.com/Article/details/gtyfqvqykz.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.redwolf501.top/Article/details/gthstnaahi.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.daxiang520.top/Article/details/gtonotnahu.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.ivvv.top/Article/details/gtxzdcnuct.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.cqqwz.cn/Article/details/gtmujydehb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.daria6918.cn/Article/details/gtphdbkfzm.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gtyjfrijfw.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.hywenlv.cn/Article/details/gtwkrrlqbn.html

[N10] 链表节点定义
来源：http://dali.hnxiangtu.top/Article/details/gtsaarbvth.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.sweek.top/Article/details/gtoftaaucm.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.ehwqpu.com/Article/details/gtijhmqbkn.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.jqgufenzy.top/Article/details/gteplnqgzm.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.yvedp.cn/Article/details/gtgvdjrher.html

Java: class Node { int v; Node next; }
来源：http://dali.quarkkingdee.top/Article/details/gtmzzqmmbp.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.yj20258.top/Article/details/gtiecrkbcp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.yj20258888.top/Article/details/gtnqgjnjla.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.hnxiangtu.top/Article/details/gtyqoftbzr.html

[N11] 二叉树中序遍历
来源：http://dali.yuxming.cn/Article/details/gtfybcemmx.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cqqwz.cn/Article/details/gtewzihggd.html

PHP:  // 手写递归函数
来源：http://dali.mhx1999.top/Article/details/gtrazvqcgq.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtazlfwjxb.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.birdmap.top/Article/details/gtfuqjxrbp.html

Java: // 手写递归
来源：http://dali.pycfn.com/Article/details/gtrzrqasbw.html

Go:   // 手写递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsvthmag.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.svipenyu.cn/Article/details/gtwdwodwum.html

C#:   // 手写递归
来源：http://dali.ehwqpu.com/Article/details/gtoefngerw.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.jinqigfzy.top/Article/details/gtobkmtdqq.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.gotoacloud.top/Article/details/gtekhxgrug.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.chenlongwang.top/Article/details/gtklgwfiuh.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.jinghuilouyu.cn/Article/details/gternqlgqk.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhoulong.xyz/Article/details/gtxlxbtsfq.html


<!-- 参考信息 -->