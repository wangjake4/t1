代发 wailian999

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.xuetiantiany.cn/Article/details/gt2qtwmdldy.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfhuooer.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.hnxiangtu.top/Article/details/gt2ctzgwdjo.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.dianchejie.cn/Article/details/gt2vfudavmb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.dashuyun.cn/Article/details/gt2uwkfxzsn.html

[K07] 进制转换
来源：http://dali.fzhhl.top/Article/details/gt2ztyztdvb.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.snrcjt.cn/Article/details/gt2tqtrakzk.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.chenjidiqi.icu/Article/details/gt2yfficgjr.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.nanxuanxn.top/Article/details/gt2qydmqzga.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.nanxinkj.top/Article/details/gt2imlxfpso.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.xziqi.cn/Article/details/gt2lqgpdrqb.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2inlsyiky.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrfvxppj.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.yuanzhike.top/Article/details/gt2pkpjdmye.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.yueranfly.top/Article/details/gt2pnjiootm.html

Py:   pickle.dumps(obj)
来源：http://dali.sxryk.cn/Article/details/gt2jspgpkjo.html

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dboakrhz.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.fengsongda.top/Article/details/gt2pfersvjw.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.hysaishi.cn/Article/details/gt2hzhshlck.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.yj20258.top/Article/details/gt2tesdfufd.html

Go:   encoding/gob
来源：http://dali.ybcxt.top/Article/details/gt2quskajec.html

Ruby: Marshal.dump(obj)
来源：http://dali.feifeiyinyue.top/Article/details/gt2methbpdw.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.cucudq.cn/Article/details/gt2vienyzkd.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2vqblurae.html

L. 网络请求
来源：http://dali.nanxuanxn.top/Article/details/gt2cbusiveu.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2hrqkamer.html

[L01] 发送 GET 请求
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2evukezkf.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.yvedp.cn/Article/details/gt2whtvgsju.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.jqgufenzy.top/Article/details/gt2mfppvzij.html

JS:   await fetch(url)
来源：http://dali.gotoacloud.top/Article/details/gt2aazbaqdz.html

TS:   await fetch(url)
来源：http://dali.haohaochexian.top/Article/details/gt2zlirlooq.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.cdnleiting.top/Article/details/gt2zvxrxurl.html

Go:   resp, err := http.Get(url)
来源：http://dali.guowangkeji.top/Article/details/gt2flbwdkwk.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.xziqi.cn/Article/details/gt2fiulakun.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iyxksrmb.html

[L02] 发送 POST JSON
来源：http://dali.gogol.net.cn/Article/details/gt2qeajfihk.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tzqtgbff.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.zhoulong.xyz/Article/details/gt2saplzcmc.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhongyouzk.top/Article/details/gt2vsvvmaoc.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.quarkkingdee.top/Article/details/gt2obshbaet.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.jianghu66.top/Article/details/gt2ndlfmhmb.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xuanzx.com/Article/details/gt2oxaydthd.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.jqgufenzy.top/Article/details/gt2ymmpsrpa.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.9152youxi.cn/Article/details/gt2ytewlffx.html

[L03] 设置自定义请求头
来源：http://dali.iojbl.cn/Article/details/gt2eenlcclm.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gsdxhsng.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hammf.cn/Article/details/gt2yxyazade.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.ydzc1.top/Article/details/gt2fnuilyfp.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.chenlongwang.top/Article/details/gt2cuxiqzgp.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.yj20258888.top/Article/details/gt2nuqngrrx.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gpdtzlmx.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.jinqigufen.top/Article/details/gt2bzwbjrdu.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.chenlongwang.top/Article/details/gt2pcrsljlv.html

[L04] 设置超时
来源：http://dali.ehwqpu.com/Article/details/gt2nspyablh.html

Py:   requests.get(url, timeout=5)
来源：http://dali.sweek.top/Article/details/gt2xevpmriv.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yuanzhike.top/Article/details/gt2tnjyswuk.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.gogol.net.cn/Article/details/gt2cjoahfbt.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.shangyingyoupin.top/Article/details/gt2ammlxvec.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.wangdashe.top/Article/details/gt2ccnpqpfx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.guannengcc.top/Article/details/gt2hoksjmid.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.svipenyu.cn/Article/details/gt2lazfbczq.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guannengcc.top/Article/details/gt2mcajpsuw.html

[L05] 上传文件（multipart）
来源：http://dali.pengpengdd.cyou/Article/details/gt2hobfylvi.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.zdqjudy.top/Article/details/gt2mjefgcsy.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.gotoacloud.top/Article/details/gt2civrwwsg.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.bjfxy.top/Article/details/gt2rinbuuzs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.daxiang520.top/Article/details/gt2uynjwcnt.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2igiveips.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wxdutkkq.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pycfn.com/Article/details/gt2mwvhmagv.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2fvsscprw.html

[L06] 解析响应为 JSON
来源：http://dali.yangfankeji.com/Article/details/gt2flliwmve.html

Py:   resp.json()
来源：http://dali.havefunace.top/Article/details/gt2yxgfnqjc.html

PHP:  json_decode($body, true);
来源：http://dali.jlsjyb.cn/Article/details/gt2pyppjrvb.html

JS:   await resp.json()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nswnjmop.html

TS:   await resp.json()
来源：http://dali.jianghu66.top/Article/details/gt2dqpufqqo.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.tianlin.xyz/Article/details/gt2veplgctq.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.cheryme.top/Article/details/gt2kyfqzlgl.html

Ruby: JSON.parse(resp.body)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgrxutuf.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.aizwys.cn/Article/details/gt2xjvdxfhu.html

[L07] 处理 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gt2yvtwanpa.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.cashguo.top/Article/details/gt2lhydosse.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.yj20258.top/Article/details/gt2ekmcyzcq.html

JS:   resp.ok;  resp.status
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jychobxn.html

TS:   resp.ok;  resp.status
来源：http://dali.shzxlz.cn/Article/details/gt2nxvmdvkf.html

Java: resp.statusCode()
来源：http://dali.kuanghao11.cn/Article/details/gt2tesaetzw.html

Go:   resp.StatusCode
来源：http://dali.jyoumei.cn/Article/details/gt2cwodvnyt.html

Ruby: resp.code.to_i
来源：http://dali.hywenlv.cn/Article/details/gt2mcchtkxq.html

C#:   (int)resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gt2psbkmgsc.html

[L08] 并发请求多个地址
来源：http://dali.316326.xyz/Article/details/gt2fvvjawok.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.xziqi.cn/Article/details/gt2cxrjmoza.html

PHP:  curl_multi_init() 系列
来源：http://dali.wangdashe.top/Article/details/gt2vybzybyj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gt2vqvivbsp.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258888.top/Article/details/gt2bhsczirr.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.sxryk.cn/Article/details/gt2lnnipvnh.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.jqgfzy.top/Article/details/gt2ccrsyogk.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.hammf.cn/Article/details/gt2djbrdmek.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.cheryme.top/Article/details/gt2yfxrklkn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2vzpimnkm.html

M. 命令行 / 进程 / 环境
来源：http://dali.nanxinkj.top/Article/details/gt2ccwsheov.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2fivdgghu.html

[M01] 读取命令行参数
来源：http://dali.guowangkeji.top/Article/details/gt2hvsnljga.html

Py:   sys.argv[1:]
来源：http://dali.feifeiyinyue.top/Article/details/gt2pofqmoni.html

PHP:  $argv;  $argc;
来源：http://dali.bjfxy.top/Article/details/gt2jqhgqssj.html

JS:   process.argv.slice(2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqyhkmgo.html

TS:   process.argv.slice(2)
来源：http://dali.ehwqpu.com/Article/details/gt2ckqezltt.html

Java: args 数组（main 方法参数）
来源：http://dali.aizwys.cn/Article/details/gt2ehtfbejy.html

Go:   os.Args[1:]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kywxqbcy.html

Ruby: ARGV
来源：http://dali.fengsongda.top/Article/details/gt2kqtsymfi.html

C#:   args 数组（Main 方法参数）
来源：http://dali.daria6918.cn/Article/details/gt2vopbgmmw.html

[M02] 读取环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2mjtxdboo.html

Py:   os.environ.get("HOME")
来源：http://dali.zhongyouzk.top/Article/details/gt2qhjzwcjc.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.yuanzhike.top/Article/details/gt2gpwbxrmq.html

JS:   process.env.HOME
来源：http://dali.fengsongda.top/Article/details/gt2qujdascf.html

TS:   process.env.HOME
来源：http://dali.xuanzx.com/Article/details/gt2ulrackgp.html

Java: System.getenv("HOME")
来源：http://dali.shuidangran.top/Article/details/gt2ltddfbvk.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.hammf.cn/Article/details/gt2gpnslwto.html

Ruby: ENV["HOME"]
来源：http://dali.xuanzx.com/Article/details/gt2nhqmbdjn.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.hfpthk.cn/Article/details/gt2ozazzlzl.html

[M03] 执行外部命令
来源：http://dali.yonumen.top/Article/details/gt2zmdasqxp.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.redwolf501.top/Article/details/gt2zuzqbrpt.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.daxiang520.top/Article/details/gt2yizcfghr.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.jlsjyb.cn/Article/details/gt2sodyyeup.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2cxirakca.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.gzhubu.top/Article/details/gt2mkeufsle.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zhoulong.xyz/Article/details/gt2xzizgojg.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.ydzc1.top/Article/details/gt2jjhnrtwf.html

C#:   Process.Start("ls", "-l");
来源：http://dali.hysaishi.cn/Article/details/gt2fmzpgdmm.html

[M04] 获取当前工作目录
来源：http://dali.jyoumei.cn/Article/details/gt2pwybqflk.html

Py:   os.getcwd()
来源：http://dali.hfpthk.cn/Article/details/gt2qidtocge.html

PHP:  getcwd();
来源：http://dali.dashuyun.cn/Article/details/gt2nmrxweaa.html

JS:   process.cwd()
来源：http://dali.xinyue.icu/Article/details/gt2nzequxwc.html

TS:   process.cwd()
来源：http://dali.birdmap.top/Article/details/gt2sieoqayo.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jlsjyb.cn/Article/details/gt2somszwui.html

Go:   os.Getwd()
来源：http://dali.zdqjudy.top/Article/details/gt2poduvxbk.html

Ruby: Dir.pwd
来源：http://dali.fengsongda.top/Article/details/gt2enfzqcnu.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.andypj.xyz/Article/details/gt2sctzybip.html

[M05] 设置退出码
来源：http://dali.yj20258.top/Article/details/gt2kfwkwdlt.html

Py:   sys.exit(1)
来源：http://dali.yangfankeji.com/Article/details/gt2jarfhats.html

PHP:  exit(1);
来源：http://dali.zycfv.cn/Article/details/gt2yetlnxrg.html

JS:   process.exit(1)
来源：http://dali.ehwqpu.com/Article/details/gt2nllegura.html

TS:   process.exit(1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2csblnkrx.html

Java: System.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2pfyvahwu.html

Go:   os.Exit(1)
来源：http://dali.svipenyu.cn/Article/details/gt2vnzuhlug.html

Ruby: exit 1
来源：http://dali.xylfe.cn/Article/details/gt2ccagicyw.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.ppjwa.cn/Article/details/gt2xauticxk.html

[M06] 向标准错误输出
来源：http://dali.gzhubu.top/Article/details/gt2ynkncbuv.html

Py:   print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gt2gvlccfhy.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.hongshengwenyu.top/Article/details/gt2qgcgeodx.html

JS:   console.error("err")
来源：http://dali.jiagoushi.top/Article/details/gt2fzwuaymi.html

TS:   console.error("err")
来源：http://dali.wangshuangyany.cn/Article/details/gt2zirkeamk.html

Java: System.err.println("err")
来源：http://dali.gogol.net.cn/Article/details/gt2pmmsxbly.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gqwvkxln.html

Ruby: warn "err"
来源：http://dali.guannengcc.top/Article/details/gt2jiyfjbca.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2yjytloqx.html

[M07] 判断是否为主入口
来源：http://dali.aibaodan.cn/Article/details/gt2nwymbjom.html

Py:   if __name__ == "__main__":
来源：http://dali.yangfankeji.com/Article/details/gt2nvghcitg.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.dianchejie.cn/Article/details/gt2dtgltqix.html

JS:   require.main === module
来源：http://dali.nanxinkj.top/Article/details/gt2hvabjrex.html

TS:   require.main === module
来源：http://dali.hammf.cn/Article/details/gt2lxexbkxu.html

Java: public static void main(String[] args)
来源：http://dali.tanke756.top/Article/details/gt2tnuyvpfk.html

Go:   func main()
来源：http://dali.tian-w.cn/Article/details/gt2avsmfreq.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.fengsongda.top/Article/details/gt2bmnwphmo.html

C#:   static void Main(string[] args)
来源：http://dali.yuxming.cn/Article/details/gt2hgepfhki.html

[M08] 获取系统与运行时信息
来源：http://dali.quarkkingdee.top/Article/details/gt2swakkqbb.html

Py:   platform.system();  platform.python_version()
来源：http://dali.havefunace.top/Article/details/gt2vkkfbdnr.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.yvedp.cn/Article/details/gt2qdkspkjd.html

JS:   process.platform;  process.version
来源：http://dali.yuxming.cn/Article/details/gt2aehrgyof.html

TS:   process.platform;  process.version
来源：http://dali.cqqwz.cn/Article/details/gt2vzbjqynb.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.vqdsnc.cn/Article/details/gt2mfuwykho.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yj20258.top/Article/details/gt2lestlacs.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.wangdashe.top/Article/details/gt2xjvvcjyr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.yueranfly.top/Article/details/gt2yxxwvhhp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2fjuidflu.html

N. 数据结构与算法
来源：http://dali.hnqzz.top/Article/details/gt2bmeetsnh.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2opfviezk.html

[N01] 二分查找（有序数组）
来源：http://dali.hnqzz.top/Article/details/gt2mwsjirxd.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.ybcxt.top/Article/details/gt2bizjgnis.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.guowangkeji.top/Article/details/gt2nnrezwvy.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.zdqjudy.top/Article/details/gt2hnvmycfv.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2jncloizv.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gt2lkuwarls.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2kzrpzodw.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.daxiang520.top/Article/details/gt2nblxpcpa.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.mhx1999.top/Article/details/gt2dizhwwff.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.ehwqpu.com/Article/details/gt2ejpqkbec.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenlongwang.top/Article/details/gt2cnqytfff.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.svipenyu.cn/Article/details/gt2kkilsmku.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.zycfv.cn/Article/details/gt2rbgvxejq.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.xuanzx.com/Article/details/gt2azasnatf.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.zdqjudy.top/Article/details/gt2ntkxenuq.html

Go:   slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gt2xlhoquxb.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gt2vnxvapaw.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.zycfv.cn/Article/details/gt2jjybwevz.html

[N03] 快速排序（分治示例）
来源：http://dali.hongshengwenyu.top/Article/details/gt2gytbmxvt.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.jqgfzy.top/Article/details/gt2eegbophs.html

PHP:  // 递归实现，或用 usort
来源：http://dali.sxryk.cn/Article/details/gt2gqtpipyj.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.chenlongwang.top/Article/details/gt2nxlxqqms.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.jinqigfzy.top/Article/details/gt2othjmuee.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.yj202588.top/Article/details/gt2theaxlmd.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.sysykeji.top/Article/details/gt2ajasqshb.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.daxiang520.top/Article/details/gt2ecgysotv.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.ehwqpu.com/Article/details/gt2xwotcwix.html

[N04] 斐波那契数列
来源：http://dali.guannengcc.top/Article/details/gt2psjynerp.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.hnqzz.top/Article/details/gt2hrikbxst.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.hfpthk.cn/Article/details/gt2idwpkjnu.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.cqqwz.cn/Article/details/gt2fmznlmdt.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.9152youxi.cn/Article/details/gt2ttkuqtoh.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.hnxiangtu.top/Article/details/gt2rsdblonk.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.cheryme.top/Article/details/gt2phedkpxq.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.yangfankeji.com/Article/details/gt2prgrnzsw.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ydzc1.top/Article/details/gt2antnpckp.html

[N05] 最大公约数
来源：http://dali.havefunace.top/Article/details/gt2muejefnn.html

Py:   math.gcd(a, b)
来源：http://dali.jinqigfzy.top/Article/details/gt2vuewhjpw.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.shzxlz.cn/Article/details/gt2vnrlyuij.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.gogol.net.cn/Article/details/gt2wstvvjpt.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ddogjhwj.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.xuetiantiany.cn/Article/details/gt2akmpgnrp.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.zhengqikj.top/Article/details/gt2uuqpsahj.html

Ruby: a.gcd(b)
来源：http://dali.hfpthk.cn/Article/details/gt2uqgjhsvj.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.shuidangran.top/Article/details/gt2nzcivzrz.html

[N06] 判断回文字符串
来源：http://dali.xuanzx.com/Article/details/gt2mmxvilyg.html

Py:   s == s[::-1]
来源：http://dali.feifeiyinyue.top/Article/details/gt2cvnvwhnd.html

PHP:  $s === strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gt2lmprhrdt.html

JS:   s === [...s].reverse().join("")
来源：http://dali.yuxming.cn/Article/details/gt2yhvffciu.html

TS:   s === [...s].reverse().join("")
来源：http://dali.snrcjt.cn/Article/details/gt2ojrendvy.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.jinqigfzy.top/Article/details/gt2rkzmvypu.html

Go:   // 双指针从两端比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2qxjezmja.html

Ruby: s == s.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhbqqtrn.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gt2opqwoenu.html

[N07] 两数之和（返回下标）
来源：http://dali.yvedp.cn/Article/details/gt2objlmbns.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.andypj.xyz/Article/details/gt2pmejgxpx.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.tanke756.top/Article/details/gt2weyjqkfs.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.yj20258.top/Article/details/gt2ljpomsyj.html

TS:   // 手写 Map<string, number>
来源：http://dali.gzhubu.top/Article/details/gt2pixgtkty.html

Java: // 手写 HashMap
来源：http://dali.chenzaomai.com/Article/details/gt2ckxhehse.html

Go:   // 手写 map[int]int
来源：http://dali.yueranfly.top/Article/details/gt2vovpffbg.html

Ruby: // 手写 Hash
来源：http://dali.yj20258888.top/Article/details/gt2gteeucnz.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.9152youxi.cn/Article/details/gt2fgjzibsp.html

[N08] 生成全排列
来源：http://dali.fzhhl.top/Article/details/gt2iqyjwaag.html

Py:   itertools.permutations(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2zppzepbm.html

PHP:  // 手写递归交换
来源：http://dali.andypj.xyz/Article/details/gt2edcazatb.html

JS:   // 手写回溯递归
来源：http://dali.redwolf501.top/Article/details/gt2sroiyyyc.html

TS:   // 手写回溯递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ylugpdmd.html

Java: // 手写回溯递归
来源：http://dali.andypj.xyz/Article/details/gt2leymatdv.html

Go:   // 手写回溯递归
来源：http://dali.tian-w.cn/Article/details/gt2gthxxqde.html

Ruby: arr.permutation.to_a
来源：http://dali.xinyue.icu/Article/details/gt2pbfldzwo.html

C#:   // 手写回溯递归
来源：http://dali.mhx1999.top/Article/details/gt2clvfpfuf.html

[N09] 栈与队列
来源：http://dali.yj20258.top/Article/details/gt2bmkmvnyu.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.c1oappe.top/Article/details/gt2rpceqjxp.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.zhiwuduotai.top/Article/details/gt2jacpaove.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.zhengqikj.top/Article/details/gt2cdwahsjg.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2crirdehs.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.gzhubu.top/Article/details/gt2blolmqij.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.sysykeji.top/Article/details/gt2nseithpd.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.dashuyun.cn/Article/details/gt2asjkxumv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.iojbl.cn/Article/details/gt2xiyrkoya.html

[N10] 链表节点定义
来源：http://dali.guowangkeji.top/Article/details/gt2firgxwcx.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.shuidangran.top/Article/details/gt2oxpzhbbv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.aizwys.cn/Article/details/gt2zufxshru.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xymwbwfg.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.daxiang520.top/Article/details/gt2asrjkotc.html

Java: class Node { int v; Node next; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdqqghra.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.chenzaomai.com/Article/details/gt2nrkonpkr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.sufxvd.cn/Article/details/gt2yuzopucg.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.gaohongyu789.top/Article/details/gt2zbkmveov.html

[N11] 二叉树中序遍历
来源：http://dali.0kj1m.cn/Article/details/gt2qlkxrbeb.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.smart0.xyz/Article/details/gt2crlazozk.html

PHP:  // 手写递归函数
来源：http://dali.sweek.top/Article/details/gt2wsfarlcd.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.jinqigfzy.top/Article/details/gt2bcfhewbn.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.nwbrower.top/Article/details/gt2rflfcryp.html

Java: // 手写递归
来源：http://dali.snrcjt.cn/Article/details/gt2uryfopfq.html

Go:   // 手写递归
来源：http://dali.wangshuangyany.cn/Article/details/gt2quhxesta.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.hysaishi.cn/Article/details/gt2hkbvyude.html

C#:   // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2dkkxjhdz.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfcsakyt.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zlztagrm.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.jinqigfzy.top/Article/details/gt2gdcexcoj.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.andypj.xyz/Article/details/gt2xqvvwwmb.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.daria6918.cn/Article/details/gt2lvlfpwny.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.chenjidiqi.icu/Article/details/gt2nsarghee.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dianchejie.cn/Article/details/gt2pxdgbjoy.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.jiagoushi.top/Article/details/gt2jeawqycf.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.fzhhl.top/Article/details/gt2jbzvuqzl.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxqppqaw.html

O. 并发与异步
来源：http://dali.shangyingyoupin.top/Article/details/gt2lojiurqw.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2hhbcnppo.html

[O01] 启动一个线程
来源：http://dali.jqgfzy.top/Article/details/gt2hzrpxucr.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.snrcjt.cn/Article/details/gt2mtqwgiur.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.yj20258.top/Article/details/gt2kpwhwcij.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.iojbl.cn/Article/details/gt2axxqbfvv.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gt2qbdjptzb.html

Java: new Thread(() -> f()).start()
来源：http://dali.xuetiantiany.cn/Article/details/gt2euowcsbf.html

Go:   go f()
来源：http://dali.snrcjt.cn/Article/details/gt2ohnqcqlb.html

Ruby: Thread.new { f }
来源：http://dali.zhoulong.xyz/Article/details/gt2rjlbgzqw.html

C#:   Task.Run(() => F());
来源：http://dali.quarkkingdee.top/Article/details/gt2frqodyxl.html

[O02] 使用线程池
来源：http://dali.hammf.cn/Article/details/gt2nthajwqs.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qsbygkpu.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.cashguo.top/Article/details/gt2wmdhgodx.html

JS:   // worker_threads 线程池
来源：http://dali.wangshuangyany.cn/Article/details/gt2onvswlxx.html


<!-- 参考信息 -->