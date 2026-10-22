代发 wailian999

PHP:  serialize($obj);  unserialize($s);
来源：http://dali.andypj.xyz/Article/details/gt2xumjhvio.html

JS:   v8.serialize(obj)        // Node
来源：http://dali.ppjwa.cn/Article/details/gt2rbrzpmsp.html

TS:   v8.serialize(obj)        // Node
来源：http://dali.yanxiufei.cn/Article/details/gt2ivybgvyi.html

Java: // 用 Kryo / Protobuf；Java 原生序列化已不推荐
来源：http://dali.chenjidiqi.icu/Article/details/gt2ogbgauxu.html

Go:   encoding/gob
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jatvxbzv.html

Ruby: Marshal.dump(obj)
来源：http://dali.cashguo.top/Article/details/gt2pbydfgso.html

C#:   // BinaryFormatter 已弃用，改用 MessagePack / System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gt2mksjczdf.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2vpijhtxa.html

L. 网络请求
来源：http://dali.wangdashe.top/Article/details/gt2eljfscqm.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2gtbifeqr.html

[L01] 发送 GET 请求
来源：http://dali.nwbrower.top/Article/details/gt2nzwwuesn.html

Py:   requests.get(url)                        # 第三方库 requests
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhsmetdk.html

PHP:  file_get_contents($url);                 // 简单场景；复杂用 curl
来源：http://dali.yonumen.top/Article/details/gt2lhielgcx.html

JS:   await fetch(url)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rzygeszz.html

TS:   await fetch(url)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2axylhyzs.html

Java: HttpClient.newHttpClient().send(HttpRequest.newBuilder(URI.create(url)).build(), BodyHandlers.ofString())
来源：http://dali.wangshuangyany.cn/Article/details/gt2agkqwbrf.html

Go:   resp, err := http.Get(url)
来源：http://dali.hysaishi.cn/Article/details/gt2jwubpxoi.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.birdmap.top/Article/details/gt2jrvjgnhp.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.zycfv.cn/Article/details/gt2eitaqoun.html

[L02] 发送 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjwrczal.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zhongyouzk.top/Article/details/gt2qfiyplbo.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.sysykeji.top/Article/details/gt2koxhwzny.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.shuidangran.top/Article/details/gt2heitneqv.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.xinyue.icu/Article/details/gt2kqpigstr.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bwcowpew.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.xylfe.cn/Article/details/gt2fhmvfoij.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.bjfxy.top/Article/details/gt2zqqaeoxh.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.quarkkingdee.top/Article/details/gt2dexmdvir.html

[L03] 设置自定义请求头
来源：http://dali.yuanzhike.top/Article/details/gt2lnvhtdrw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.fzhhl.top/Article/details/gt2mpianzne.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvdmkxif.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.cucudq.cn/Article/details/gt2unxleiik.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtramrk.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.fzhhl.top/Article/details/gt2gvjpomfn.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.nwbrower.top/Article/details/gt2ungcubzf.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hpngssby.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.cqqwz.cn/Article/details/gt2ygfznycs.html

[L04] 设置超时
来源：http://dali.yj202588.top/Article/details/gt2fyuaxbye.html

Py:   requests.get(url, timeout=5)
来源：http://dali.yj202588.top/Article/details/gt2mzhwwuoa.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.ivvv.top/Article/details/gt2qlvuzmwb.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.ybcxt.top/Article/details/gt2ffzxsyhb.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.pycfn.com/Article/details/gt2mscizxzg.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.hnqzz.top/Article/details/gt2wklzjgcp.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.hnxiangtu.top/Article/details/gt2uhqpwlug.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.cucudq.cn/Article/details/gt2qcekqwka.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.fzhhl.top/Article/details/gt2mgumegwk.html

[L05] 上传文件（multipart）
来源：http://dali.havefunace.top/Article/details/gt2qchhljbm.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.0kj1m.cn/Article/details/gt2bygoblja.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.nanxuanxn.top/Article/details/gt2ghadebqy.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.tanke756.top/Article/details/gt2otyoudsd.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.ydzc1.top/Article/details/gt2sswkvojc.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.xziqi.cn/Article/details/gt2zihibhwz.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.zhoulong.xyz/Article/details/gt2kfyskygu.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.nanxuanxn.top/Article/details/gt2yojeghge.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lynlylkd.html

[L06] 解析响应为 JSON
来源：http://dali.iojbl.cn/Article/details/gt2tjjcwtuc.html

Py:   resp.json()
来源：http://dali.yongpay.top/Article/details/gt2atsoqiav.html

PHP:  json_decode($body, true);
来源：http://dali.yj202588.top/Article/details/gt2emvrxyuh.html

JS:   await resp.json()
来源：http://dali.zhengqikj.top/Article/details/gt2qvupablq.html

TS:   await resp.json()
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdqdfdqk.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.yj20258.top/Article/details/gt2wnunpsze.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ztkoiavp.html

Ruby: JSON.parse(resp.body)
来源：http://dali.zhengqikj.top/Article/details/gt2bpbeqyqz.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.andypj.xyz/Article/details/gt2towhwxel.html

[L07] 处理 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gt2kzsinfxb.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.tianlin.xyz/Article/details/gt2bozomhnd.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.iojbl.cn/Article/details/gt2altycuwn.html

JS:   resp.ok;  resp.status
来源：http://dali.jianghu66.top/Article/details/gt2ebtmyhjb.html

TS:   resp.ok;  resp.status
来源：http://dali.jlsjyb.cn/Article/details/gt2bfeffxxh.html

Java: resp.statusCode()
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkfygebc.html

Go:   resp.StatusCode
来源：http://dali.yj202588.top/Article/details/gt2xrkvmkkj.html

Ruby: resp.code.to_i
来源：http://dali.andypj.xyz/Article/details/gt2ssrqfgxe.html

C#:   (int)resp.StatusCode
来源：http://dali.fengsongda.top/Article/details/gt2eszbwdey.html

[L08] 并发请求多个地址
来源：http://dali.xziqi.cn/Article/details/gt2mmtslmsg.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.birdmap.top/Article/details/gt2railllwm.html

PHP:  curl_multi_init() 系列
来源：http://dali.snrcjt.cn/Article/details/gt2kdcnygax.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2xtdnsxnn.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangdashe.top/Article/details/gt2dkcmhrri.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.9152youxi.cn/Article/details/gt2jimsmvpj.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.ybcxt.top/Article/details/gt2bdijuojl.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.svipenyu.cn/Article/details/gt2dkvylvbu.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.yvedp.cn/Article/details/gt2muihqkch.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2hunmkfsg.html

M. 命令行 / 进程 / 环境
来源：http://dali.tian-w.cn/Article/details/gt2llsomvsu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2mpsiaonf.html

[M01] 读取命令行参数
来源：http://dali.tanke756.top/Article/details/gt2msrdxurh.html

Py:   sys.argv[1:]
来源：http://dali.svipenyu.cn/Article/details/gt2raytxnsn.html

PHP:  $argv;  $argc;
来源：http://dali.xziqi.cn/Article/details/gt2hdpongje.html

JS:   process.argv.slice(2)
来源：http://dali.xuanzx.com/Article/details/gt2xbypetqe.html

TS:   process.argv.slice(2)
来源：http://dali.ppjwa.cn/Article/details/gt2upcsotwx.html

Java: args 数组（main 方法参数）
来源：http://dali.sweek.top/Article/details/gt2paobwayd.html

Go:   os.Args[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fabniita.html

Ruby: ARGV
来源：http://dali.wangshuangyany.cn/Article/details/gt2bpeylvku.html

C#:   args 数组（Main 方法参数）
来源：http://dali.yanxiufei.cn/Article/details/gt2cirorjop.html

[M02] 读取环境变量
来源：http://dali.gaohongyu789.top/Article/details/gt2fagsmdyg.html

Py:   os.environ.get("HOME")
来源：http://dali.xuetiantiany.cn/Article/details/gt2frevycga.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.mhx1999.top/Article/details/gt2nyvbmwkm.html

JS:   process.env.HOME
来源：http://dali.xuetiantiany.cn/Article/details/gt2jjokrfpk.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xtzjdmwc.html

Java: System.getenv("HOME")
来源：http://dali.hywenlv.cn/Article/details/gt2mqrnhvhb.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.xziqi.cn/Article/details/gt2zqiigjlr.html

Ruby: ENV["HOME"]
来源：http://dali.jlsjyb.cn/Article/details/gt2bpshtsgm.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.aibaodan.cn/Article/details/gt2yezzlfnr.html

[M03] 执行外部命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ajvcuxpr.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.cashguo.top/Article/details/gt2ihsqjplc.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awlvvioe.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.ydzc1.top/Article/details/gt2trcuiknw.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2nvbyoqxv.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.nanxinkj.top/Article/details/gt2ebfuggpz.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.pengpengdd.cyou/Article/details/gt2qjewgalu.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.c1oappe.top/Article/details/gt2euuhcjnz.html

C#:   Process.Start("ls", "-l");
来源：http://dali.tanke756.top/Article/details/gt2jzoabqzk.html

[M04] 获取当前工作目录
来源：http://dali.tian-w.cn/Article/details/gt2fwpydylz.html

Py:   os.getcwd()
来源：http://dali.cqqwz.cn/Article/details/gt2gyyksehi.html

PHP:  getcwd();
来源：http://dali.gzhubu.top/Article/details/gt2wppnlooo.html

JS:   process.cwd()
来源：http://dali.yj202588.top/Article/details/gt2sdiavzkv.html

TS:   process.cwd()
来源：http://dali.yonumen.top/Article/details/gt2ihkhwzcg.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.xuanzx.com/Article/details/gt2dqejewbm.html

Go:   os.Getwd()
来源：http://dali.gaohongyu789.top/Article/details/gt2sljajxgv.html

Ruby: Dir.pwd
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qvcsoqgw.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.haohaochexian.top/Article/details/gt2pwzqbcan.html

[M05] 设置退出码
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnrkzlsy.html

Py:   sys.exit(1)
来源：http://dali.hysaishi.cn/Article/details/gt2uzpqbmsb.html

PHP:  exit(1);
来源：http://dali.jinqigfzy.top/Article/details/gt2jlbxejtf.html

JS:   process.exit(1)
来源：http://dali.daxiang520.top/Article/details/gt2ptrixfmj.html

TS:   process.exit(1)
来源：http://dali.jinqigufen.top/Article/details/gt2dhsfdkhz.html

Java: System.exit(1)
来源：http://dali.yueranfly.top/Article/details/gt2saeyfsyc.html

Go:   os.Exit(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2kqxnuowd.html

Ruby: exit 1
来源：http://dali.guowangkeji.top/Article/details/gt2fokljmzg.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.316326.xyz/Article/details/gt2jehopjsk.html

[M06] 向标准错误输出
来源：http://dali.ehwqpu.com/Article/details/gt2snpkjmjc.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gt2tbmqjxhz.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.cdnleiting.top/Article/details/gt2bfpcswzk.html

JS:   console.error("err")
来源：http://dali.ivvv.top/Article/details/gt2gbodofjh.html

TS:   console.error("err")
来源：http://dali.yj20258.top/Article/details/gt2tsbieuxm.html

Java: System.err.println("err")
来源：http://dali.zhoulong.xyz/Article/details/gt2kzzyiqpm.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.jiagoushi.top/Article/details/gt2kmokriom.html

Ruby: warn "err"
来源：http://dali.yuanzhike.top/Article/details/gt2ntfdehij.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.guannengcc.top/Article/details/gt2amkulxmq.html

[M07] 判断是否为主入口
来源：http://dali.cqqwz.cn/Article/details/gt2babhjrhm.html

Py:   if __name__ == "__main__":
来源：http://dali.gogol.net.cn/Article/details/gt2qpevppmw.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.gogol.net.cn/Article/details/gt2igzqlhvq.html

JS:   require.main === module
来源：http://dali.sufxvd.cn/Article/details/gt2ygzyymwg.html

TS:   require.main === module
来源：http://dali.tianlin.xyz/Article/details/gt2tbogfgzh.html

Java: public static void main(String[] args)
来源：http://dali.jqgfzy.top/Article/details/gt2ntbwiwqr.html

Go:   func main()
来源：http://dali.yvedp.cn/Article/details/gt2lmzzigum.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jinqigufen.top/Article/details/gt2epaxtxbg.html

C#:   static void Main(string[] args)
来源：http://dali.haohaochexian.top/Article/details/gt2ngvymndv.html

[M08] 获取系统与运行时信息
来源：http://dali.daxiang520.top/Article/details/gt2nfktktjn.html

Py:   platform.system();  platform.python_version()
来源：http://dali.gotoacloud.top/Article/details/gt2mqbweprb.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zhoulong.xyz/Article/details/gt2qxtjqzui.html

JS:   process.platform;  process.version
来源：http://dali.tanke756.top/Article/details/gt2xsneigou.html

TS:   process.platform;  process.version
来源：http://dali.chenzaomai.com/Article/details/gt2cugsxgkd.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.zhixingplan.top/Article/details/gt2obhkxbdh.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.tanke756.top/Article/details/gt2wqjrontl.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.bjfxy.top/Article/details/gt2ucmnydmr.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.haohaochexian.top/Article/details/gt2iefocmka.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2ncutmykr.html

N. 数据结构与算法
来源：http://dali.vqdsnc.cn/Article/details/gt2oqzqgkmp.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2zrmfixnm.html

[N01] 二分查找（有序数组）
来源：http://dali.yj202588.top/Article/details/gt2zlftiejy.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2zmmhybbs.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.zhijiandao.cn/Article/details/gt2cymgubbr.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.redwolf501.top/Article/details/gt2xizipohm.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.vqdsnc.cn/Article/details/gt2ywrtfnon.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.hfpthk.cn/Article/details/gt2prghwfbh.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qqwhoixz.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.nwbrower.top/Article/details/gt2ualsvgna.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.jinqigufen.top/Article/details/gt2ddjlesgn.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.cqqwz.cn/Article/details/gt2xoxhvbrb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gt2cfzwpkhc.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.chenlongwang.top/Article/details/gt2uyiscoef.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gt2divrwzwe.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.jqgfzy.top/Article/details/gt2xbarltod.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.haohaochexian.top/Article/details/gt2mbjduigh.html

Go:   slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gt2qiamrhrb.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gt2wqlmwymv.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.xuetiantiany.cn/Article/details/gt2unwovlve.html

[N03] 快速排序（分治示例）
来源：http://dali.kuanghao11.cn/Article/details/gt2btzgnjxg.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.fzhhl.top/Article/details/gt2kwfllkje.html

PHP:  // 递归实现，或用 usort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sqtryssg.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.cdnleiting.top/Article/details/gt2bycixamc.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.xuanzx.com/Article/details/gt2aroolpbg.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gt2usqbdadr.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.zhijiandao.cn/Article/details/gt2bxisdaje.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.yuanzhike.top/Article/details/gt2oftkupqn.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.yj20258888.top/Article/details/gt2vgsijtxf.html

[N04] 斐波那契数列
来源：http://dali.chenzaomai.com/Article/details/gt2qbkggcwz.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daxiang520.top/Article/details/gt2emcikuoo.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.zhongyouzk.top/Article/details/gt2eezltpkl.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jqyzeclz.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2kokbvtxf.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daria6918.cn/Article/details/gt2rwlywdxy.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2eyfqgfhe.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.snrcjt.cn/Article/details/gt2urjoudyk.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.ppjwa.cn/Article/details/gt2ukruzahn.html

[N05] 最大公约数
来源：http://dali.vqdsnc.cn/Article/details/gt2rzqjxlkp.html

Py:   math.gcd(a, b)
来源：http://dali.yongpay.top/Article/details/gt2leyduxxk.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.mhx1999.top/Article/details/gt2bovdfmvc.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2idojswyd.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.guowangkeji.top/Article/details/gt2tbjprlis.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.daxiang520.top/Article/details/gt2veplpnml.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pqedkegc.html

Ruby: a.gcd(b)
来源：http://dali.sxryk.cn/Article/details/gt2voqofnss.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.yvedp.cn/Article/details/gt2snokrvds.html

[N06] 判断回文字符串
来源：http://dali.yanxiufei.cn/Article/details/gt2vsykauhc.html

Py:   s == s[::-1]
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfwaesqi.html

PHP:  $s === strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gt2ovroepbe.html

JS:   s === [...s].reverse().join("")
来源：http://dali.zhixingplan.top/Article/details/gt2pbsspnql.html

TS:   s === [...s].reverse().join("")
来源：http://dali.wangshuangyany.cn/Article/details/gt2ulyxwtdu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.yj202588.top/Article/details/gt2sbxifsiy.html

Go:   // 双指针从两端比较
来源：http://dali.aibaodan.cn/Article/details/gt2pasowzis.html

Ruby: s == s.reverse
来源：http://dali.yuanzhike.top/Article/details/gt2nevmeffj.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.fengsongda.top/Article/details/gt2uxkuhmut.html

[N07] 两数之和（返回下标）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cidwuncl.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.andypj.xyz/Article/details/gt2rxepqlnd.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.aibaodan.cn/Article/details/gt2fjlzyokr.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.kuanghao11.cn/Article/details/gt2oszdjvau.html

TS:   // 手写 Map<string, number>
来源：http://dali.wangshuangyany.cn/Article/details/gt2kevxiopg.html

Java: // 手写 HashMap
来源：http://dali.hnqzz.top/Article/details/gt2siykvcoa.html

Go:   // 手写 map[int]int
来源：http://dali.smart0.xyz/Article/details/gt2xieyoxoa.html

Ruby: // 手写 Hash
来源：http://dali.quarkkingdee.top/Article/details/gt2lkdrzbyu.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.dashuyun.cn/Article/details/gt2pxhvztid.html

[N08] 生成全排列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tmszlcgk.html

Py:   itertools.permutations(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2pqgwkydd.html

PHP:  // 手写递归交换
来源：http://dali.birdmap.top/Article/details/gt2ezeanlvi.html

JS:   // 手写回溯递归
来源：http://dali.aibaodan.cn/Article/details/gt2eaflcnsa.html

TS:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2fyydckom.html

Java: // 手写回溯递归
来源：http://dali.sysykeji.top/Article/details/gt2xfaatqib.html

Go:   // 手写回溯递归
来源：http://dali.jiagoushi.top/Article/details/gt2ikpdrkko.html

Ruby: arr.permutation.to_a
来源：http://dali.yuanzhike.top/Article/details/gt2scuaooyg.html

C#:   // 手写回溯递归
来源：http://dali.tanke756.top/Article/details/gt2vxoaqvav.html

[N09] 栈与队列
来源：http://dali.shuidangran.top/Article/details/gt2gcdykcgx.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yonumen.top/Article/details/gt2vzohvezm.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.ybcxt.top/Article/details/gt2yruojdqw.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.cucudq.cn/Article/details/gt2pkcfmcjk.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.snrcjt.cn/Article/details/gt2leclswqf.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.jyoumei.cn/Article/details/gt2vcxxkwcb.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.ydzc1.top/Article/details/gt2gfnkgmpq.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.svipenyu.cn/Article/details/gt2xxlkodfm.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fmbprhqz.html

[N10] 链表节点定义
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywcgcscg.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.aizwys.cn/Article/details/gt2rnsffrwv.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.zhengqikj.top/Article/details/gt2kdpuqmrf.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2rfrtyols.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.9152youxi.cn/Article/details/gt2udylenmj.html

Java: class Node { int v; Node next; }
来源：http://dali.hnqzz.top/Article/details/gt2lpgvkfnh.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.kuanghao11.cn/Article/details/gt2ddwhwjcp.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.chenzaomai.com/Article/details/gt2bgcecbwr.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.birdmap.top/Article/details/gt2njohkreq.html

[N11] 二叉树中序遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2mmgrmpit.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.hammf.cn/Article/details/gt2rxsxptbr.html

PHP:  // 手写递归函数
来源：http://dali.yj20258888.top/Article/details/gt2qnopomoa.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.hammf.cn/Article/details/gt2tnucqazp.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.shzxlz.cn/Article/details/gt2zfuwgjci.html

Java: // 手写递归
来源：http://dali.yvedp.cn/Article/details/gt2qtobdarr.html

Go:   // 手写递归
来源：http://dali.tanke756.top/Article/details/gt2qiahpeyc.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.cqqwz.cn/Article/details/gt2jhlrzvzb.html

C#:   // 手写递归
来源：http://dali.yj202588.top/Article/details/gt2oyfzhjxa.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlesdsjc.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.sysykeji.top/Article/details/gt2iavnxvae.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.gzhubu.top/Article/details/gt2mvehsfhb.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.sxryk.cn/Article/details/gt2zflhqhbn.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlarhmn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.yvedp.cn/Article/details/gt2qepzpivc.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.dianchejie.cn/Article/details/gt2yxmrmzlz.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.vqdsnc.cn/Article/details/gt2whdoazns.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tdbjrkkb.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ovhaoluz.html

O. 并发与异步
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ualhnccz.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2oopjnnie.html

[O01] 启动一个线程
来源：http://dali.gotoacloud.top/Article/details/gt2tghobpcx.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.havefunace.top/Article/details/gt2hfawzsie.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.svipenyu.cn/Article/details/gt2fmnkiiia.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.dianchejie.cn/Article/details/gt2ozmmvrfd.html

TS:   // 同 JS
来源：http://dali.vqdsnc.cn/Article/details/gt2xisqwaqd.html

Java: new Thread(() -> f()).start()
来源：http://dali.dashuyun.cn/Article/details/gt2szpxrorn.html

Go:   go f()
来源：http://dali.yangfankeji.com/Article/details/gt2zjjqbeck.html

Ruby: Thread.new { f }
来源：http://dali.andypj.xyz/Article/details/gt2masluesr.html

C#:   Task.Run(() => F());
来源：http://dali.jinqigfzy.top/Article/details/gt2nijfexnj.html

[O02] 使用线程池
来源：http://dali.quarkkingdee.top/Article/details/gt2nylpmkso.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.hywenlv.cn/Article/details/gt2blzbqdnm.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.316326.xyz/Article/details/gt2ibifequb.html

JS:   // worker_threads 线程池
来源：http://dali.yueranfly.top/Article/details/gt2kdyvrdyl.html

TS:   // worker_threads 线程池
来源：http://dali.sufxvd.cn/Article/details/gt2kzsdrzek.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dpvcsbuh.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.andypj.xyz/Article/details/gt2pskdoykb.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.iojbl.cn/Article/details/gt2jwxujcpk.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.jqgufenzy.top/Article/details/gt2plnedlrl.html

[O03] 加锁保护共享数据
来源：http://dali.mhx1999.top/Article/details/gt2inuxezjl.html

Py:   with lock: shared += 1
来源：http://dali.zhongyouzk.top/Article/details/gt2jgnrukoi.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.quarkkingdee.top/Article/details/gt2oggtjiwx.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.nwbrower.top/Article/details/gt2taxvztdl.html

TS:   // 同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gt2sgfeeklq.html

Java: synchronized (this) { shared++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2drdkypbg.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.gaohongyu789.top/Article/details/gt2ettkvbcf.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxbcxpga.html

C#:   lock (gate) { shared++; }
来源：http://dali.ehwqpu.com/Article/details/gt2zymuytyz.html

[O04] 定义异步函数并等待
来源：http://dali.tian-w.cn/Article/details/gt2jzgthbba.html

Py:   async def f():⏎    await g()
来源：http://dali.snrcjt.cn/Article/details/gt2epykqigy.html


<!-- 参考信息 -->