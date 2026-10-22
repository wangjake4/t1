代发 wailian999

Go:   resp, err := http.Get(url)
来源：http://dali.havefunace.top/Article/details/gt2qhhsfpvo.html

Ruby: Net::HTTP.get(URI(url))
来源：http://dali.iojbl.cn/Article/details/gt2wrczclmi.html

C#:   await new HttpClient().GetStringAsync(url)
来源：http://dali.dianchejie.cn/Article/details/gt2komrkfcj.html

[L02] 发送 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gt2crzpufpm.html

Py:   requests.post(url, json={"a": 1})
来源：http://dali.zycfv.cn/Article/details/gt2eihtrwek.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, json_encode(["a" => 1]));
来源：http://dali.jyoumei.cn/Article/details/gt2ffpcuhlt.html

JS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.zhixingplan.top/Article/details/gt2kbnjlqeg.html

TS:   fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify({ a: 1 }) })
来源：http://dali.yj202588.top/Article/details/gt2pbsxmwac.html

Java: HttpRequest.newBuilder(uri).header("Content-Type", "application/json").POST(BodyPublishers.ofString(body)).build()
来源：http://dali.andypj.xyz/Article/details/gt2iqpohyzo.html

Go:   http.Post(url, "application/json", strings.NewReader(`{"a":1}`))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ytwqgdgx.html

Ruby: Net::HTTP.post(URI(url), '{"a":1}', "Content-Type" => "application/json")
来源：http://dali.zhoulong.xyz/Article/details/gt2lftbpdbf.html

C#:   await client.PostAsync(url, new StringContent(json, Encoding.UTF8, "application/json"))
来源：http://dali.quarkkingdee.top/Article/details/gt2olsubedt.html

[L03] 设置自定义请求头
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yrroswuw.html

Py:   requests.get(url, headers={"X-Token": "abc"})
来源：http://dali.svipenyu.cn/Article/details/gt2agablixj.html

PHP:  curl_setopt($ch, CURLOPT_HTTPHEADER, ["X-Token: abc"]);
来源：http://dali.hysaishi.cn/Article/details/gt2rurtuowz.html

JS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqfydhc.html

TS:   fetch(url, { headers: { "X-Token": "abc" } })
来源：http://dali.quarkkingdee.top/Article/details/gt2lvytjgpi.html

Java: HttpRequest.newBuilder(uri).header("X-Token", "abc").build()
来源：http://dali.jqgfzy.top/Article/details/gt2vzsfrfxu.html

Go:   req, _ := http.NewRequest("GET", url, nil);  req.Header.Set("X-Token", "abc")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kiopwjpg.html

Ruby: req = Net::HTTP::Get.new(uri);  req["X-Token"] = "abc"
来源：http://dali.fzhhl.top/Article/details/gt2zrevgtfg.html

C#:   var req = new HttpRequestMessage(HttpMethod.Get, url);  req.Headers.Add("X-Token", "abc")
来源：http://dali.sysykeji.top/Article/details/gt2fthjrzho.html

[L04] 设置超时
来源：http://dali.yueranfly.top/Article/details/gt2pwfzaddf.html

Py:   requests.get(url, timeout=5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kamvllcr.html

PHP:  curl_setopt($ch, CURLOPT_TIMEOUT, 5);
来源：http://dali.yangfankeji.com/Article/details/gt2smulegza.html

JS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.zdqjudy.top/Article/details/gt2qehaosav.html

TS:   fetch(url, { signal: AbortSignal.timeout(5000) })
来源：http://dali.dashuyun.cn/Article/details/gt2fkebzlgm.html

Java: HttpClient.newBuilder().connectTimeout(Duration.ofSeconds(5)).build()
来源：http://dali.ehwqpu.com/Article/details/gt2ijuyyrjx.html

Go:   client := &http.Client{Timeout: 5 * time.Second}
来源：http://dali.redwolf501.top/Article/details/gt2nsauntje.html

Ruby: Net::HTTP.start(uri.host, uri.port, open_timeout: 5, read_timeout: 5)
来源：http://dali.havefunace.top/Article/details/gt2zambbxtw.html

C#:   client.Timeout = TimeSpan.FromSeconds(5);
来源：http://dali.guannengcc.top/Article/details/gt2gcerreqc.html

[L05] 上传文件（multipart）
来源：http://dali.wangshuangyany.cn/Article/details/gt2loqubzgy.html

Py:   requests.post(url, files={"f": open("a.txt", "rb")})
来源：http://dali.cashguo.top/Article/details/gt2msudzlyx.html

PHP:  curl_setopt($ch, CURLOPT_POSTFIELDS, ["f" => new CURLFile("a.txt")]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ukqaexci.html

JS:   const fd = new FormData();  fd.append("f", blob);  fetch(url, { method: "POST", body: fd })
来源：http://dali.yj20258.top/Article/details/gt2moglervs.html

TS:   const fd = new FormData();  fetch(url, { method: "POST", body: fd })
来源：http://dali.xylfe.cn/Article/details/gt2dckxbnif.html

Java: // 用 BodyPublishers.ofFile 或手写 multipart
来源：http://dali.yangfankeji.com/Article/details/gt2bxgtwboc.html

Go:   mime/multipart.NewWriter 写入字段与文件
来源：http://dali.sweek.top/Article/details/gt2wkxfpiny.html

Ruby: req.set_form([["f", File.open("a.txt")]])
来源：http://dali.pengpengdd.cyou/Article/details/gt2xnpydcin.html

C#:   var form = new MultipartFormDataContent();  form.Add(new StreamContent(stream), "f", "a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gt2eomtllzk.html

[L06] 解析响应为 JSON
来源：http://dali.wangshuangyany.cn/Article/details/gt2uqldogjh.html

Py:   resp.json()
来源：http://dali.gzhubu.top/Article/details/gt2jjzwmdcv.html

PHP:  json_decode($body, true);
来源：http://dali.guowangkeji.top/Article/details/gt2bmoitgog.html

JS:   await resp.json()
来源：http://dali.gaohongyu789.top/Article/details/gt2eljaszvd.html

TS:   await resp.json()
来源：http://dali.iojbl.cn/Article/details/gt2gbcwwgzy.html

Java: new ObjectMapper().readValue(resp.body(), Map.class)
来源：http://dali.jianghu66.top/Article/details/gt2fveawymh.html

Go:   json.NewDecoder(resp.Body).Decode(&v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2owhtrxzo.html

Ruby: JSON.parse(resp.body)
来源：http://dali.tanke756.top/Article/details/gt2suxvzvdc.html

C#:   await resp.Content.ReadFromJsonAsync<T>()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjnyube.html

[L07] 处理 HTTP 状态码
来源：http://dali.feifeiyinyue.top/Article/details/gt2ftdecsxz.html

Py:   resp.status_code;  resp.raise_for_status()
来源：http://dali.zhoulong.xyz/Article/details/gt2recgehnv.html

PHP:  curl_getinfo($ch, CURLINFO_HTTP_CODE);
来源：http://dali.xylfe.cn/Article/details/gt2zwjgmzne.html

JS:   resp.ok;  resp.status
来源：http://dali.jqgufenzy.top/Article/details/gt2khvhwemn.html

TS:   resp.ok;  resp.status
来源：http://dali.feifeiyinyue.top/Article/details/gt2gtmfihao.html

Java: resp.statusCode()
来源：http://dali.xuetiantiany.cn/Article/details/gt2pqbqkcft.html

Go:   resp.StatusCode
来源：http://dali.andypj.xyz/Article/details/gt2gwwgfzoc.html

Ruby: resp.code.to_i
来源：http://dali.smart0.xyz/Article/details/gt2netzuoty.html

C#:   (int)resp.StatusCode
来源：http://dali.yanxiufei.cn/Article/details/gt2phwzojlp.html

[L08] 并发请求多个地址
来源：http://dali.hnxiangtu.top/Article/details/gt2nhgodupo.html

Py:   asyncio.gather(*[fetch(u) for u in urls])      # 或 ThreadPoolExecutor
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gqcemkst.html

PHP:  curl_multi_init() 系列
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yatkrucj.html

JS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.tian-w.cn/Article/details/gt2nzuiycps.html

TS:   await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yonumen.top/Article/details/gt2olftrhjm.html

Java: CompletableFuture.allOf(...) 或 HttpClient.sendAsync
来源：http://dali.nwbrower.top/Article/details/gt2jfppario.html

Go:   errgroup 分组并发，或 sync.WaitGroup
来源：http://dali.xziqi.cn/Article/details/gt2piacfdxt.html

Ruby: threads = urls.map { |u| Thread.new { fetch(u) } };  threads.each(&:join)
来源：http://dali.zhoulong.xyz/Article/details/gt2cvvlqpsm.html

C#:   await Task.WhenAll(urls.Select(u => client.GetStringAsync(u)))
来源：http://dali.snrcjt.cn/Article/details/gt2eljokcuj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2wylqfxyn.html

M. 命令行 / 进程 / 环境
来源：http://dali.yvedp.cn/Article/details/gt2cjytsrie.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbynapdc.html

[M01] 读取命令行参数
来源：http://dali.jqgfzy.top/Article/details/gt2aypxwqsv.html

Py:   sys.argv[1:]
来源：http://dali.cqqwz.cn/Article/details/gt2ihstdmfb.html

PHP:  $argv;  $argc;
来源：http://dali.daxiang520.top/Article/details/gt2szeboeaq.html

JS:   process.argv.slice(2)
来源：http://dali.sweek.top/Article/details/gt2kcvkpupe.html

TS:   process.argv.slice(2)
来源：http://dali.hfpthk.cn/Article/details/gt2pocmlzvn.html

Java: args 数组（main 方法参数）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljiozplr.html

Go:   os.Args[1:]
来源：http://dali.yongpay.top/Article/details/gt2fcvjgtmc.html

Ruby: ARGV
来源：http://dali.hfpthk.cn/Article/details/gt2qbiibuap.html

C#:   args 数组（Main 方法参数）
来源：http://dali.kuanghao11.cn/Article/details/gt2rabzqium.html

[M02] 读取环境变量
来源：http://dali.bjfxy.top/Article/details/gt2hlvxmlgu.html

Py:   os.environ.get("HOME")
来源：http://dali.svipenyu.cn/Article/details/gt2xnlbggrb.html

PHP:  getenv("HOME");  $_ENV["HOME"] ?? null;
来源：http://dali.hnxiangtu.top/Article/details/gt2bakpafcg.html

JS:   process.env.HOME
来源：http://dali.kuanghao11.cn/Article/details/gt2wtwwhilf.html

TS:   process.env.HOME
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xcuvuzqg.html

Java: System.getenv("HOME")
来源：http://dali.haohaochexian.top/Article/details/gt2xwyvpihj.html

Go:   os.Getenv("HOME");  os.LookupEnv("HOME")
来源：http://dali.gogol.net.cn/Article/details/gt2kzxqwowu.html

Ruby: ENV["HOME"]
来源：http://dali.quarkkingdee.top/Article/details/gt2toxgltcw.html

C#:   Environment.GetEnvironmentVariable("HOME")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfgnzgqq.html

[M03] 执行外部命令
来源：http://dali.tianlin.xyz/Article/details/gt2foowmtjw.html

Py:   subprocess.run(["ls", "-l"], capture_output=True, text=True)
来源：http://dali.wangdashe.top/Article/details/gt2lcfsjors.html

PHP:  exec("ls -l", $out);  shell_exec("ls -l");
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijzyqmia.html

JS:   child_process.execSync("ls -l").toString()
来源：http://dali.yvedp.cn/Article/details/gt2ygoaqrer.html

TS:   child_process.execSync("ls -l").toString()
来源：http://dali.ybcxt.top/Article/details/gt2nyxxdcmu.html

Java: new ProcessBuilder("ls", "-l").start()
来源：http://dali.shuidangran.top/Article/details/gt2wxxadgpf.html

Go:   exec.Command("ls", "-l").Output()
来源：http://dali.zycfv.cn/Article/details/gt2bpriiwhe.html

Ruby: system("ls -l");  `ls -l`
来源：http://dali.fzhhl.top/Article/details/gt2ovmadwgx.html

C#:   Process.Start("ls", "-l");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckvgwuab.html

[M04] 获取当前工作目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eotgvgom.html

Py:   os.getcwd()
来源：http://dali.zhijiandao.cn/Article/details/gt2qxefjsie.html

PHP:  getcwd();
来源：http://dali.jinqigfzy.top/Article/details/gt2jmrntcvh.html

JS:   process.cwd()
来源：http://dali.hysaishi.cn/Article/details/gt2evhprtba.html

TS:   process.cwd()
来源：http://dali.daria6918.cn/Article/details/gt2kxiczfbx.html

Java: Path.of("").toAbsolutePath()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fhlnnlct.html

Go:   os.Getwd()
来源：http://dali.ppjwa.cn/Article/details/gt2rvxxssgz.html

Ruby: Dir.pwd
来源：http://dali.kuanghao11.cn/Article/details/gt2fqaakija.html

C#:   Directory.GetCurrentDirectory()
来源：http://dali.nanxinkj.top/Article/details/gt2boufshvk.html

[M05] 设置退出码
来源：http://dali.nanxuanxn.top/Article/details/gt2tllcxzve.html

Py:   sys.exit(1)
来源：http://dali.andypj.xyz/Article/details/gt2lzafcvkj.html

PHP:  exit(1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ewvvsmrj.html

JS:   process.exit(1)
来源：http://dali.yuxming.cn/Article/details/gt2zmxjbmgf.html

TS:   process.exit(1)
来源：http://dali.quarkkingdee.top/Article/details/gt2muwjptoa.html

Java: System.exit(1)
来源：http://dali.fengsongda.top/Article/details/gt2bsbzuvyp.html

Go:   os.Exit(1)
来源：http://dali.daria6918.cn/Article/details/gt2lawjsuve.html

Ruby: exit 1
来源：http://dali.andypj.xyz/Article/details/gt2plnpiqjy.html

C#:   Environment.Exit(1);  // 或 Main 返回 int
来源：http://dali.dashuyun.cn/Article/details/gt2uxqyyijs.html

[M06] 向标准错误输出
来源：http://dali.ppjwa.cn/Article/details/gt2vgjwkear.html

Py:   print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gt2cynhntpx.html

PHP:  fwrite(STDERR, "err\n");
来源：http://dali.ehwqpu.com/Article/details/gt2vfspfiwm.html

JS:   console.error("err")
来源：http://dali.hnxiangtu.top/Article/details/gt2qbmequcu.html

TS:   console.error("err")
来源：http://dali.hywenlv.cn/Article/details/gt2xzytkajn.html

Java: System.err.println("err")
来源：http://dali.yueranfly.top/Article/details/gt2bjfhnjft.html

Go:   fmt.Fprintln(os.Stderr, "err")
来源：http://dali.yongpay.top/Article/details/gt2tctbhlob.html

Ruby: warn "err"
来源：http://dali.hammf.cn/Article/details/gt2iqyvhxtx.html

C#:   Console.Error.WriteLine("err")
来源：http://dali.jqgufenzy.top/Article/details/gt2vialnftm.html

[M07] 判断是否为主入口
来源：http://dali.hnqzz.top/Article/details/gt2hbmxlfwb.html

Py:   if __name__ == "__main__":
来源：http://dali.jinqigfzy.top/Article/details/gt2vausodgu.html

PHP:  // 无直接写法：用 debug_backtrace 或定义常量判断
来源：http://dali.chenzaomai.com/Article/details/gt2pvgizfsm.html

JS:   require.main === module
来源：http://dali.iojbl.cn/Article/details/gt2hlysgmfn.html

TS:   require.main === module
来源：http://dali.guowangkeji.top/Article/details/gt2qyuczqsn.html

Java: public static void main(String[] args)
来源：http://dali.smart0.xyz/Article/details/gt2ihtmurys.html

Go:   func main()
来源：http://dali.aizwys.cn/Article/details/gt2ohxrtfum.html

Ruby: if __FILE__ == $PROGRAM_NAME
来源：http://dali.jqgfzy.top/Article/details/gt2fwrxylls.html

C#:   static void Main(string[] args)
来源：http://dali.0kj1m.cn/Article/details/gt2hlhbdsrl.html

[M08] 获取系统与运行时信息
来源：http://dali.meibo888.top/Article/details/gt2wuehsdgw.html

Py:   platform.system();  platform.python_version()
来源：http://dali.jinqigufen.top/Article/details/gt2jhqeztsl.html

PHP:  PHP_OS;  phpversion();
来源：http://dali.zycfv.cn/Article/details/gt2qzculhsd.html

JS:   process.platform;  process.version
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xcsqbfhd.html

TS:   process.platform;  process.version
来源：http://dali.guowangkeji.top/Article/details/gt2ntpmhhfk.html

Java: System.getProperty("os.name");  System.getProperty("java.version")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wmlocrcg.html

Go:   runtime.GOOS;  runtime.Version()
来源：http://dali.yuanzhike.top/Article/details/gt2fgfijpxe.html

Ruby: RUBY_PLATFORM;  RUBY_VERSION
来源：http://dali.daria6918.cn/Article/details/gt2jyyhifub.html

C#:   Environment.OSVersion;  Environment.Version
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lkzbfnev.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2egbzuoao.html

N. 数据结构与算法
来源：http://dali.chenjidiqi.icu/Article/details/gt2gciuaiub.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2hhxtyzxj.html

[N01] 二分查找（有序数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqscjeiq.html

Py:   bisect.bisect_left(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gt2ddgjqfhr.html

PHP:  // 手写：$lo=0; $hi=count($a)-1; while ($lo <= $hi) { $mid = ($lo+$hi)>>1; ... }
来源：http://dali.ybcxt.top/Article/details/gt2oujsoend.html

JS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.aizwys.cn/Article/details/gt2jbiutguk.html

TS:   // 手写：while (lo <= hi) { const mid = (lo + hi) >> 1; ... }
来源：http://dali.snrcjt.cn/Article/details/gt2xrkhljgd.html

Java: Arrays.binarySearch(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2emuyraqv.html

Go:   sort.SearchInts(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gt2bfwgxxqy.html

Ruby: arr.bsearch { |e| e >= x }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwzzncpq.html

C#:   Array.BinarySearch(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2nkyfoqao.html

[N02] 排序（工程实践用内置实现）
来源：http://dali.gaohongyu789.top/Article/details/gt2tocrvvbm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.dianchejie.cn/Article/details/gt2orgwewcy.html

PHP:  sort($arr);  usort($arr, $cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mmohsbzj.html

JS:   [...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rgigbser.html

TS:   [...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gt2ryxmjqvn.html

Java: Arrays.sort(arr);  Collections.sort(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdrrhwmi.html

Go:   slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2juwdgmnh.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gt2ormpklwe.html

C#:   Array.Sort(arr);  list.Sort()
来源：http://dali.hywenlv.cn/Article/details/gt2xqdiunng.html

[N03] 快速排序（分治示例）
来源：http://dali.yuxming.cn/Article/details/gt2xjbziqse.html

Py:   def qs(a): return a if len(a) <= 1 else qs([x for x in a[1:] if x < a[0]]) + [a[0]] + qs([x for x in a[1:] if x >= a[0]])
来源：http://dali.mhx1999.top/Article/details/gt2toqyryss.html

PHP:  // 递归实现，或用 usort
来源：http://dali.fzhhl.top/Article/details/gt2hwsyvtlx.html

JS:   const qs = a => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.tanke756.top/Article/details/gt2vxpvmfpd.html

TS:   const qs = (a: number[]): number[] => a.length <= 1 ? a : [...qs(a.slice(1).filter(x => x < a[0])), a[0], ...qs(a.slice(1).filter(x => x >= a[0]))];
来源：http://dali.0kj1m.cn/Article/details/gt2wazodikk.html

Java: // 手写递归，或直接用 Arrays.sort
来源：http://dali.daxiang520.top/Article/details/gt2xfhxrqok.html

Go:   slices.Sort(arr)      // 手写快排需递归实现
来源：http://dali.yueranfly.top/Article/details/gt2uwhwcfgu.html

Ruby: def qs(a) = a.size <= 1 ? a : qs(a[1..].select { |x| x < a[0] }) + [a[0]] + qs(a[1..].select { |x| x >= a[0] })
来源：http://dali.zhijiandao.cn/Article/details/gt2haeyuxsm.html

C#:   // 手写递归，或 Array.Sort
来源：http://dali.bjfxy.top/Article/details/gt2wktuzptk.html

[N04] 斐波那契数列
来源：http://dali.zhixingplan.top/Article/details/gt2iqjmcepk.html

Py:   def fib(n): return n if n < 2 else fib(n - 1) + fib(n - 2)
来源：http://dali.daria6918.cn/Article/details/gt2vlbhtkwk.html

PHP:  function fib($n) { return $n < 2 ? $n : fib($n - 1) + fib($n - 2); }
来源：http://dali.nanxinkj.top/Article/details/gt2coxaygmw.html

JS:   const fib = n => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.andypj.xyz/Article/details/gt2ogdygmaw.html

TS:   const fib = (n: number): number => n < 2 ? n : fib(n - 1) + fib(n - 2);
来源：http://dali.wangdashe.top/Article/details/gt2sjreonvv.html

Java: static int fib(int n) { return n < 2 ? n : fib(n - 1) + fib(n - 2); }
来源：http://dali.daxiang520.top/Article/details/gt2ydaecclx.html

Go:   func fib(n int) int { if n < 2 { return n }; return fib(n-1) + fib(n-2) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldiwofss.html

Ruby: def fib(n) = n < 2 ? n : fib(n - 1) + fib(n - 2)
来源：http://dali.haohaochexian.top/Article/details/gt2vihcydod.html

C#:   static int Fib(int n) => n < 2 ? n : Fib(n - 1) + Fib(n - 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rbnyencp.html

[N05] 最大公约数
来源：http://dali.hnxiangtu.top/Article/details/gt2amjknuxb.html

Py:   math.gcd(a, b)
来源：http://dali.yongpay.top/Article/details/gt2lpkxjmzt.html

PHP:  // 手写：while ($b) { [$a, $b] = [$b, $a % $b]; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mbrfjczw.html

JS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.nwbrower.top/Article/details/gt2lijfumgf.html

TS:   // 手写：while (b) { [a, b] = [b, a % b]; }
来源：http://dali.sweek.top/Article/details/gt2bokirfqq.html

Java: BigInteger.valueOf(a).gcd(BigInteger.valueOf(b))
来源：http://dali.jyoumei.cn/Article/details/gt2llkxpxsr.html

Go:   // 手写：for b != 0 { a, b = b, a%b }
来源：http://dali.aizwys.cn/Article/details/gt2tjpmllxy.html

Ruby: a.gcd(b)
来源：http://dali.fzhhl.top/Article/details/gt2hanidffs.html

C#:   // 手写：while (b != 0) { (a, b) = (b, a % b); }
来源：http://dali.cashguo.top/Article/details/gt2duadbdvj.html

[N06] 判断回文字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2dteqihqx.html

Py:   s == s[::-1]
来源：http://dali.hysaishi.cn/Article/details/gt2zepbalkg.html

PHP:  $s === strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zyqwyxyj.html

JS:   s === [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2fmbqibez.html

TS:   s === [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2sdacfutu.html

Java: s.equals(new StringBuilder(s).reverse().toString())
来源：http://dali.hywenlv.cn/Article/details/gt2lpbkwyqf.html

Go:   // 双指针从两端比较
来源：http://dali.chenzaomai.com/Article/details/gt2vdqawghm.html

Ruby: s == s.reverse
来源：http://dali.smart0.xyz/Article/details/gt2fvtvazle.html

C#:   s == new string(s.Reverse().ToArray())
来源：http://dali.daxiang520.top/Article/details/gt2wgbnfbxp.html

[N07] 两数之和（返回下标）
来源：http://dali.wangshuangyany.cn/Article/details/gt2uexaxyal.html

Py:   idx = {v: i for i, v in enumerate(nums)}      # 再逐个查 target - v 是否在表内
来源：http://dali.snrcjt.cn/Article/details/gt2cbtzcreg.html

PHP:  // 手写哈希表：$map[$v] = $i
来源：http://dali.yongpay.top/Article/details/gt2pclbwaol.html

JS:   // 手写 Map：map.set(v, i)
来源：http://dali.guannengcc.top/Article/details/gt2eqirzjmf.html

TS:   // 手写 Map<string, number>
来源：http://dali.c1oappe.top/Article/details/gt2tjjpoani.html

Java: // 手写 HashMap
来源：http://dali.yuxming.cn/Article/details/gt2nhzpuoub.html

Go:   // 手写 map[int]int
来源：http://dali.tanke756.top/Article/details/gt2gsshnuld.html

Ruby: // 手写 Hash
来源：http://dali.jianghu66.top/Article/details/gt2dynybfrd.html

C#:   // 手写 Dictionary<int, int>
来源：http://dali.yangfankeji.com/Article/details/gt2fuxkywxj.html

[N08] 生成全排列
来源：http://dali.yj20258888.top/Article/details/gt2egktcvuk.html

Py:   itertools.permutations(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2prtzoeqo.html

PHP:  // 手写递归交换
来源：http://dali.yj20258.top/Article/details/gt2ufittdlx.html

JS:   // 手写回溯递归
来源：http://dali.c1oappe.top/Article/details/gt2zkvtbsrw.html

TS:   // 手写回溯递归
来源：http://dali.bjfxy.top/Article/details/gt2nsxexiiw.html

Java: // 手写回溯递归
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdeovyta.html

Go:   // 手写回溯递归
来源：http://dali.yuanzhike.top/Article/details/gt2syiorrig.html

Ruby: arr.permutation.to_a
来源：http://dali.gogol.net.cn/Article/details/gt2fiyhzkmr.html

C#:   // 手写回溯递归
来源：http://dali.cheryme.top/Article/details/gt2rbqzbizu.html

[N09] 栈与队列
来源：http://dali.havefunace.top/Article/details/gt2dajgdkbn.html

Py:   stack.append(x) / stack.pop()；deque.popleft() 作队列
来源：http://dali.yj20258888.top/Article/details/gt2kpssrrdn.html

PHP:  array_push/array_pop 作栈；array_shift 作队列
来源：http://dali.0kj1m.cn/Article/details/gt2pmsrweot.html

JS:   arr.push(x) / arr.pop() 作栈；arr.push / arr.shift 作队列
来源：http://dali.ydzc1.top/Article/details/gt2vvbtufax.html

TS:   arr.push(x) / arr.pop() 作栈
来源：http://dali.shuidangran.top/Article/details/gt2qnwjffmk.html

Java: new ArrayDeque<>() 同时支持栈与队列
来源：http://dali.wangshuangyany.cn/Article/details/gt2lsynkyji.html

Go:   append(s, x) 与 s[len(s)-1] 出栈
来源：http://dali.jiagoushi.top/Article/details/gt2vehnvahs.html

Ruby: arr.push / arr.pop 作栈；arr.shift 作队列
来源：http://dali.xziqi.cn/Article/details/gt2nthydpyv.html

C#:   new Stack<T>() 与 new Queue<T>()
来源：http://dali.gogol.net.cn/Article/details/gt2ulixesxd.html

[N10] 链表节点定义
来源：http://dali.nwbrower.top/Article/details/gt2vshnjzjo.html

Py:   class Node:⏎    def __init__(self, v, nxt=None): self.v, self.next = v, nxt
来源：http://dali.svipenyu.cn/Article/details/gt2imfbrptk.html

PHP:  class Node { public $v; public $next = null; }
来源：http://dali.gzhubu.top/Article/details/gt2czetfktk.html

JS:   class Node { constructor(v) { this.v = v; this.next = null; } }
来源：http://dali.hnqzz.top/Article/details/gt2kskoygxv.html

TS:   class Node { constructor(public v: number, public next: Node | null = null) {} }
来源：http://dali.jlsjyb.cn/Article/details/gt2bhemzfhb.html

Java: class Node { int v; Node next; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qnkoarui.html

Go:   type Node struct { V int; Next *Node }
来源：http://dali.mhx1999.top/Article/details/gt2erdirudr.html

Ruby: Node = Struct.new(:v, :next)
来源：http://dali.xylfe.cn/Article/details/gt2ggljriaz.html

C#:   class Node { public int V; public Node? Next; }
来源：http://dali.zhengqikj.top/Article/details/gt2iwislcxu.html

[N11] 二叉树中序遍历
来源：http://dali.hysaishi.cn/Article/details/gt2jjxnvuor.html

Py:   def inorder(n): return inorder(n.left) + [n.val] + inorder(n.right) if n else []
来源：http://dali.cucudq.cn/Article/details/gt2fwirsrun.html

PHP:  // 手写递归函数
来源：http://dali.daria6918.cn/Article/details/gt2rehzepos.html

JS:   const inorder = n => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.tianlin.xyz/Article/details/gt2pyimdwfw.html

TS:   const inorder = (n: T | null): number[] => n ? [...inorder(n.left), n.val, ...inorder(n.right)] : [];
来源：http://dali.wangshuangyany.cn/Article/details/gt2qwzgchwn.html

Java: // 手写递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gifwmfsq.html

Go:   // 手写递归
来源：http://dali.guowangkeji.top/Article/details/gt2qbhyesns.html

Ruby: def inorder(n) = n ? inorder(n.left) + [n.val] + inorder(n.right) : []
来源：http://dali.daxiang520.top/Article/details/gt2fabhufhb.html

C#:   // 手写递归
来源：http://dali.havefunace.top/Article/details/gt2iwciayck.html

[N12] 动态规划：爬楼梯（每次 1 或 2 级）
来源：http://dali.birdmap.top/Article/details/gt2lseoubzz.html

Py:   from functools import reduce;  climb = lambda n: reduce(lambda p, _: (p[1], p[0] + p[1]), range(n), (1, 1))[0]
来源：http://dali.yuxming.cn/Article/details/gt2qdlkhtau.html

PHP:  // 递推：$a=1;$b=1;for(...){[$a,$b]=[$b,$a+$b];}
来源：http://dali.zdqjudy.top/Article/details/gt2xiqajgkq.html

JS:   // 递推：let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.xuanzx.com/Article/details/gt2xvsvhfyl.html

TS:   let [a, b] = [1, 1]; for (let i = 0; i < n; i++) [a, b] = [b, a + b];
来源：http://dali.nwbrower.top/Article/details/gt2fsamkczn.html

Java: // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.jianghu66.top/Article/details/gt2xpguycbw.html

Go:   // 递推：a, b := 1, 1; for i := 0; i < n; i++ { a, b = b, a+b }
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxciudpf.html

Ruby: a, b = 1, 1;  n.times { a, b = b, a + b }
来源：http://dali.yj20258888.top/Article/details/gt2wncyghdj.html

C#:   // 递推：int a = 1, b = 1; 循环更新
来源：http://dali.zhongyouzk.top/Article/details/gt2pozzqqwy.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2ofvogtcv.html

O. 并发与异步
来源：http://dali.chenzaomai.com/Article/details/gt2jcdwypen.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2jqtljgyp.html

[O01] 启动一个线程
来源：http://dali.xziqi.cn/Article/details/gt2bznsideo.html

Py:   threading.Thread(target=f, args=(1,)).start()
来源：http://dali.jyoumei.cn/Article/details/gt2bjuepcoq.html

PHP:  // 无原生线程：用 pcntl_fork 或消息队列
来源：http://dali.fengsongda.top/Article/details/gt2gkoeipdn.html

JS:   // 单线程事件循环：CPU 密集用 worker_threads
来源：http://dali.tian-w.cn/Article/details/gt2hewsbdia.html

TS:   // 同 JS
来源：http://dali.cheryme.top/Article/details/gt2aficimjl.html

Java: new Thread(() -> f()).start()
来源：http://dali.shzxlz.cn/Article/details/gt2egqjnfvj.html

Go:   go f()
来源：http://dali.chenjidiqi.icu/Article/details/gt2npnvjrra.html

Ruby: Thread.new { f }
来源：http://dali.jinqigfzy.top/Article/details/gt2dnyitnau.html

C#:   Task.Run(() => F());
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhguznge.html

[O02] 使用线程池
来源：http://dali.zhongyouzk.top/Article/details/gt2ctwzzpsp.html

Py:   concurrent.futures.ThreadPoolExecutor(max_workers=4)
来源：http://dali.jiagoushi.top/Article/details/gt2hlgdcdnq.html

PHP:  // 用 Swoole / ReactPHP 等扩展实现
来源：http://dali.yonumen.top/Article/details/gt2slfnxpjx.html

JS:   // worker_threads 线程池
来源：http://dali.guowangkeji.top/Article/details/gt2cpmwfepi.html

TS:   // worker_threads 线程池
来源：http://dali.ivvv.top/Article/details/gt2aaqomvnb.html

Java: Executors.newFixedThreadPool(4)
来源：http://dali.ppjwa.cn/Article/details/gt2ooujkqaz.html

Go:   // 协程轻量，无需池；限并发用带缓冲 channel 当信号量
来源：http://dali.zhongyouzk.top/Article/details/gt2txbwmjlw.html

Ruby: // 用 concurrent-ruby 的 ThreadPool
来源：http://dali.shangyingyoupin.top/Article/details/gt2eokxgtrv.html

C#:   Task.WhenAll(...)  或 Parallel.ForEach
来源：http://dali.guowangkeji.top/Article/details/gt2ovfkbdxr.html

[O03] 加锁保护共享数据
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pbvgjfgu.html

Py:   with lock: shared += 1
来源：http://dali.fengsongda.top/Article/details/gt2xoqefxuv.html

PHP:  // 用 flock() 做文件锁
来源：http://dali.hysaishi.cn/Article/details/gt2ojzojsfw.html

JS:   // 单线程无需锁；跨线程共享内存用 Atomics
来源：http://dali.mhx1999.top/Article/details/gt2kwunzwjn.html

TS:   // 同 JS
来源：http://dali.daxiang520.top/Article/details/gt2yjambxif.html

Java: synchronized (this) { shared++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2jtqpsqdb.html

Go:   mu.Lock();  defer mu.Unlock()
来源：http://dali.havefunace.top/Article/details/gt2htpxeurr.html

Ruby: mutex.synchronize { shared += 1 }
来源：http://dali.iojbl.cn/Article/details/gt2fzwzlhhm.html

C#:   lock (gate) { shared++; }
来源：http://dali.andypj.xyz/Article/details/gt2cisvgggf.html

[O04] 定义异步函数并等待
来源：http://dali.tanke756.top/Article/details/gt2yoeofyax.html

Py:   async def f():⏎    await g()
来源：http://dali.yj20258.top/Article/details/gt2rxttcljd.html

PHP:  // 无原生 async：用 Fiber 或 Swoole
来源：http://dali.nanxuanxn.top/Article/details/gt2cjbauukh.html

JS:   async function f() { await g(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2brvmjbyi.html

TS:   async function f(): Promise<void> { await g(); }
来源：http://dali.yuxming.cn/Article/details/gt2pzpmjgjq.html

Java: // 用 CompletableFuture 或虚拟线程
来源：http://dali.hywenlv.cn/Article/details/gt2ibzrpkfa.html

Go:   // 无 async 关键字：直接 go 调用，用 channel 收结果
来源：http://dali.cqqwz.cn/Article/details/gt2mtvbdgva.html

Ruby: # 用 Fiber 或 async gem
来源：http://dali.jiagoushi.top/Article/details/gt2fghesade.html

C#:   async Task F() { await G(); }
来源：http://dali.nanxuanxn.top/Article/details/gt2visapcwn.html

[O05] 并发执行并等待全部完成
来源：http://dali.andypj.xyz/Article/details/gt2kihfpfyo.html

Py:   asyncio.gather(*tasks)
来源：http://dali.fzhhl.top/Article/details/gt2yxtuscar.html

PHP:  // curl_multi 或 Amp 的 Promise\all
来源：http://dali.jinghuilouyu.cn/Article/details/gt2htpqhhir.html

JS:   await Promise.all(tasks)
来源：http://dali.aizwys.cn/Article/details/gt2lhzuqdsv.html

TS:   await Promise.all(tasks)
来源：http://dali.ehwqpu.com/Article/details/gt2jajjwwvq.html

Java: CompletableFuture.allOf(f1, f2).join()
来源：http://dali.hywenlv.cn/Article/details/gt2cbcvywfw.html

Go:   sync.WaitGroup 或 errgroup.Wait()
来源：http://dali.fzhhl.top/Article/details/gt2wlehmdkt.html

Ruby: threads.map(&:join)
来源：http://dali.guannengcc.top/Article/details/gt2zcqqareg.html

C#:   await Task.WhenAll(t1, t2)
来源：http://dali.yangfankeji.com/Article/details/gt2kewyzgrk.html


<!-- 参考信息 -->