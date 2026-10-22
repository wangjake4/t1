代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2njiynrna.html

TS:   [...s].reverse().join("")
来源：http://dali.fzhhl.top/Article/details/gt2qafwsyuc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.chenlongwang.top/Article/details/gt2jtstkxpw.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gxmtmrgm.html

Ruby: s.reverse
来源：http://dali.pycfn.com/Article/details/gt2boalevwk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gt2fqvtgbnx.html

[E12] 统计某字符出现次数
来源：http://dali.shzxlz.cn/Article/details/gt2qkeetobu.html

Py:   s.count("a")
来源：http://dali.fengsongda.top/Article/details/gt2hauohhcy.html

PHP:  substr_count($s, "a");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ojgcwgtj.html

JS:   s.split("a").length - 1
来源：http://dali.cashguo.top/Article/details/gt2wjxksjho.html

TS:   s.split("a").length - 1
来源：http://dali.ehwqpu.com/Article/details/gt2xkybddil.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cucudq.cn/Article/details/gt2hojhuonj.html

Go:   strings.Count(s, "a")
来源：http://dali.birdmap.top/Article/details/gt2vaqojgko.html

Ruby: s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gt2mdnfhlnh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.jqgufenzy.top/Article/details/gt2pbsdajub.html

[E13] 逐字符遍历
来源：http://dali.sysykeji.top/Article/details/gt2ozxaovxr.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gt2rlkxkxey.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hywenlv.cn/Article/details/gt2clgpjtdz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gt2nrprdeet.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yanxiufei.cn/Article/details/gt2zmuujgcy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2ybaujawg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ehwqpu.com/Article/details/gt2cotxzwze.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gt2tkgpshsr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dwslkxmk.html

[E14] URL 编码与 Base64
来源：http://dali.hnxiangtu.top/Article/details/gt2gufqykuz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gogol.net.cn/Article/details/gt2omfpsrov.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gt2xrjkucjx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gt2akuwmqcn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tianlin.xyz/Article/details/gt2auqcarpk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jyoumei.cn/Article/details/gt2stnlnxyr.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ryxtvqqo.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnqzz.top/Article/details/gt2bmjghinb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cdnleiting.top/Article/details/gt2sggdythr.html

[E15] HTML 转义 / 反转义
来源：http://dali.pengpengdd.cyou/Article/details/gt2xuruoggf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fzhhl.top/Article/details/gt2vpnjqhbf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yonumen.top/Article/details/gt2gurzmlwi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sysykeji.top/Article/details/gt2xdxflvpq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.guannengcc.top/Article/details/gt2jvwqndlg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sysykeji.top/Article/details/gt2bzuwyijx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.daxiang520.top/Article/details/gt2qxjjcorl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ehwqpu.com/Article/details/gt2tvzgxxlp.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sxryk.cn/Article/details/gt2clrpqzxo.html

[E16] 数字千分位
来源：http://dali.birdmap.top/Article/details/gt2bwiqmlja.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gt2vrcrpasu.html

PHP:  number_format(1234567);
来源：http://dali.daria6918.cn/Article/details/gt2vuckvepk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhongyouzk.top/Article/details/gt2uvgazwhs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgfzy.top/Article/details/gt2mscqmrbc.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ivvv.top/Article/details/gt2kqygtjwz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hywenlv.cn/Article/details/gt2zcoaojuu.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sysykeji.top/Article/details/gt2kndqazli.html

C#:   1234567.ToString("N0")
来源：http://dali.aibaodan.cn/Article/details/gt2tziwfivc.html

[E17] 首字母大写
来源：http://dali.chenlongwang.top/Article/details/gt2rwyehtpv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yj20258.top/Article/details/gt2fjykxkrf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xinyue.icu/Article/details/gt2tbyjckzs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gt2apxvbdcq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gt2xiogosrv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gt2mervgroc.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oamayrwt.html

Ruby: s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gt2gkhupwoh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.0kj1m.cn/Article/details/gt2wbbidbes.html

[E18] 模板占位符替换
来源：http://dali.jyoumei.cn/Article/details/gt2knhscqul.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.gotoacloud.top/Article/details/gt2azagvolk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.chenzaomai.com/Article/details/gt2rnxsrcft.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yangfankeji.com/Article/details/gt2sipeipsu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gogol.net.cn/Article/details/gt2zrvkipud.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gt2trxthdug.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2sogbmvxg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gt2elddthya.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guowangkeji.top/Article/details/gt2eqiomcyx.html

[E19] 多行文本按行拆分
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrpveqnm.html

Py:   s.splitlines()
来源：http://dali.guannengcc.top/Article/details/gt2zokoxefv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gt2gpqzypor.html

JS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gt2skfraqhq.html

TS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gt2fwkgortz.html

Java: s.lines().toList()
来源：http://dali.yj202588.top/Article/details/gt2jstniqlu.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gt2dszxubyt.html

Ruby: s.lines
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2frgtqfqv.html

C#:   s.Split('\n')
来源：http://dali.jinqigufen.top/Article/details/gt2cjqyarid.html

[E20] 判断字符串是否为空
来源：http://dali.feifeiyinyue.top/Article/details/gt2iiygjrfi.html

Py:   if not s:
来源：http://dali.feifeiyinyue.top/Article/details/gt2mjcnfjxr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrnbzmpw.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2owcsnwdy.html

TS:   if (s === "") {}
来源：http://dali.svipenyu.cn/Article/details/gt2ifrmwofa.html

Java: if (s.isEmpty()) {}
来源：http://dali.xziqi.cn/Article/details/gt2tedkdtew.html

Go:   if s == "" {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2luztsbro.html

Ruby: if s.empty?
来源：http://dali.zhengqikj.top/Article/details/gt2lywlbqen.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2trkevvye.html

[E21] 超长截断加省略号
来源：http://dali.feifeiyinyue.top/Article/details/gt2sojaicid.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuetiantiany.cn/Article/details/gt2xtpedueh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gt2ubvnbiun.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gt2hcmtacbj.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2ouhyynnb.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2eubkgsxf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gotoacloud.top/Article/details/gt2nqrxqucv.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2ttcxiuqn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daria6918.cn/Article/details/gt2vxfqlffn.html

[E22] 字节长度与字符长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxbjjclm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.wangdashe.top/Article/details/gt2tfknxwym.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.havefunace.top/Article/details/gt2haavppbi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.pycfn.com/Article/details/gt2gxsilsyz.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.redwolf501.top/Article/details/gt2danmbhno.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hysaishi.cn/Article/details/gt2fnhyxyhh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yonumen.top/Article/details/gt2chunyyio.html

Ruby: s.bytesize;  s.length
来源：http://dali.zdqjudy.top/Article/details/gt2yxkyiqva.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenzaomai.com/Article/details/gt2tsmtkobo.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2sijlxwip.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gt2khyaajtr.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2bqypngxp.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gt2txvccdzo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tanke756.top/Article/details/gt2vyqwtywy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2szipqapu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.0kj1m.cn/Article/details/gt2gyizdzbh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.vqdsnc.cn/Article/details/gt2xcegvusr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gt2mhlazxyk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.jiagoushi.top/Article/details/gt2sospfedp.html

Ruby: File.read("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2takkvush.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sweek.top/Article/details/gt2zidcjhbx.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gt2cmzgmzrb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.vqdsnc.cn/Article/details/gt2wgnhylgl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.9152youxi.cn/Article/details/gt2ulvxornm.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ppjwa.cn/Article/details/gt2zdadbmkh.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gt2zlhzqqiv.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gt2znxwwneh.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sweek.top/Article/details/gt2xqrqthzf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aizwys.cn/Article/details/gt2utonxdov.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nanxinkj.top/Article/details/gt2ceacjslw.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gt2fsmrijlh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xziqi.cn/Article/details/gt2ploeoprq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sxryk.cn/Article/details/gt2fvohzlpp.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gt2gpujkooi.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj202588.top/Article/details/gt2rzwgjced.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ivvv.top/Article/details/gt2tqspmpuk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gt2kvgicfjk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ehwqpu.com/Article/details/gt2vrghonkm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2oomuttfi.html

[F04] 追加写入文件
来源：http://dali.fengsongda.top/Article/details/gt2obbjrdbn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenlongwang.top/Article/details/gt2euexxjdi.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmtowkhz.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gt2ysyqwpkn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gt2olrnzbxb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.andypj.xyz/Article/details/gt2fadjqpzr.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cheryme.top/Article/details/gt2mrspxwqi.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yj20258.top/Article/details/gt2agrlxrnl.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.316326.xyz/Article/details/gt2dbfbdbgw.html

[F05] 判断文件或目录是否存在
来源：http://dali.sxryk.cn/Article/details/gt2jxhcplvv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gt2ctfynxax.html

PHP:  file_exists("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2phxgmlrq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2moedtdcw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2bfkhddrc.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xopojpnm.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jiagoushi.top/Article/details/gt2fnfiykxz.html

Ruby: File.exist?("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2fxhlmjwy.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2znrnxmex.html

[F06] 删除文件
来源：http://dali.sufxvd.cn/Article/details/gt2ihijoikh.html

Py:   os.remove("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2jyfgaxxm.html

PHP:  unlink("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2tgcottzv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ejsntrfw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2stgtaazy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.wangdashe.top/Article/details/gt2pklfsoup.html

Go:   os.Remove("a.txt")
来源：http://dali.ivvv.top/Article/details/gt2ybdjeqrb.html

Ruby: File.delete("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2ntufihix.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gt2rtagfvmq.html

[F07] 创建目录（含多级）
来源：http://dali.yueranfly.top/Article/details/gt2qykifocl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bdbpeyvl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2whoxfydp.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.9152youxi.cn/Article/details/gt2unsllpzs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258888.top/Article/details/gt2lefedipr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhixingplan.top/Article/details/gt2vwtynwby.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuxming.cn/Article/details/gt2txvbdrfu.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.iojbl.cn/Article/details/gt2duzofoye.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.0kj1m.cn/Article/details/gt2nwucolhh.html

[F08] 遍历目录
来源：http://dali.jianghu66.top/Article/details/gt2hvpapjoo.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gt2rpwaeafm.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.vqdsnc.cn/Article/details/gt2arxheiys.html

JS:   fs.readdirSync("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gt2rphzvioj.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmdmxtw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ympyotdw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.yj20258888.top/Article/details/gt2rniujiiy.html

Ruby: Dir.children("dir")
来源：http://dali.wangdashe.top/Article/details/gt2ezzrrsds.html

C#:   Directory.GetFiles("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2rkumnars.html

[F09] 获取文件大小
来源：http://dali.dashuyun.cn/Article/details/gt2egvunctv.html

Py:   os.path.getsize("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2blhupoet.html

PHP:  filesize("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2bltcsfvs.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yonumen.top/Article/details/gt2izxhpeoo.html

TS:   fs.statSync("a.txt").size
来源：http://dali.svipenyu.cn/Article/details/gt2hreotfuc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gt2jhohywre.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.wangdashe.top/Article/details/gt2fyoecvsk.html

Ruby: File.size("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2tynhwtnh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nvavsttj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.snrcjt.cn/Article/details/gt2deelxvhv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2vanqxsxx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.aibaodan.cn/Article/details/gt2cicwvmki.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dashuyun.cn/Article/details/gt2lxorfbcv.html

TS:   path.extname("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jwiykaho.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yanxiufei.cn/Article/details/gt2kenqcwip.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gt2vgllkclm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eithaklk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2absnuzns.html

[F11] 复制与移动文件
来源：http://dali.hnxiangtu.top/Article/details/gt2tlkqvuvq.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xvmiklug.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fzhhl.top/Article/details/gt2gplxdstj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2exarrzaz.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ivvv.top/Article/details/gt2rgyfazav.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kyyvskwz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xylfe.cn/Article/details/gt2ntjbqtca.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2imrfqzqv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shzxlz.cn/Article/details/gt2judqnoop.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gt2uciyvdoo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cdnleiting.top/Article/details/gt2kbolnygp.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fengsongda.top/Article/details/gt2xjotxtkr.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.fzhhl.top/Article/details/gt2deygbmvu.html

TS:   // 同上
来源：http://dali.aizwys.cn/Article/details/gt2pvnufdpq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gt2foajycyp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ehwqpu.com/Article/details/gt2bqtfborh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.sxryk.cn/Article/details/gt2vvxpqtfg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jyoumei.cn/Article/details/gt2qtwfyjwv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2hyqlgcov.html

G. 面向对象
来源：http://dali.tianlin.xyz/Article/details/gt2zgtqazuv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ztgwzlta.html

[G01] 定义类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tbvikhhh.html

Py:   class User: pass
来源：http://dali.dashuyun.cn/Article/details/gt2zmvrftwv.html

PHP:  class User {}
来源：http://dali.sxryk.cn/Article/details/gt2vdrvcofb.html

JS:   class User {}
来源：http://dali.sysykeji.top/Article/details/gt2kmbegwul.html

TS:   class User { name: string = ""; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2imlzuikw.html

Java: class User {}
来源：http://dali.bjfxy.top/Article/details/gt2xxofyuen.html

Go:   type User struct { Name string }
来源：http://dali.sysykeji.top/Article/details/gt2alqxvejt.html

Ruby: class User; end
来源：http://dali.yvedp.cn/Article/details/gt2beljxkmb.html

C#:   class User {}
来源：http://dali.daxiang520.top/Article/details/gt2lhkjkzvj.html

[G02] 构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2fbxuxncz.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ydzc1.top/Article/details/gt2upcgxtyd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yj20258.top/Article/details/gt2zvvwveft.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.sxryk.cn/Article/details/gt2nergwtsp.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gt2nphzdqhy.html

Java: User(String name) { this.name = name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2kdmkofaa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gt2wcsyqxzs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.sysykeji.top/Article/details/gt2hidhsnwe.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hywenlv.cn/Article/details/gt2azvnofmm.html

[G03] 实例属性
来源：http://dali.redwolf501.top/Article/details/gt2dqdfmzkm.html

Py:   self.name = "x"
来源：http://dali.hfpthk.cn/Article/details/gt2znzekjpb.html

PHP:  public string $name = "x";
来源：http://dali.redwolf501.top/Article/details/gt2gdmvblci.html

JS:   this.name = "x";
来源：http://dali.nanxuanxn.top/Article/details/gt2bynkceiv.html

TS:   name: string = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yxkaikpe.html

Java: private String name;
来源：http://dali.tian-w.cn/Article/details/gt2yjmtgmsh.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.nanxuanxn.top/Article/details/gt2nlqcthvv.html

Ruby: @name = "x"
来源：http://dali.hongshengwenyu.top/Article/details/gt2jpipywnp.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2nvbidmnp.html

[G04] 定义方法
来源：http://dali.vqdsnc.cn/Article/details/gt2haaqqncz.html

Py:   def greet(self): return self.name
来源：http://dali.yongpay.top/Article/details/gt2ddgaixeq.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oepfxjud.html

JS:   greet() { return this.name; }
来源：http://dali.yj20258.top/Article/details/gt2snrenhqv.html

TS:   greet(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gt2oucymffy.html

Java: String greet() { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2otfmvnrt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj20258888.top/Article/details/gt2yrqoxqmv.html

Ruby: def greet; @name; end
来源：http://dali.ehwqpu.com/Article/details/gt2bifudnar.html

C#:   public string Greet() => Name;
来源：http://dali.yj202588.top/Article/details/gt2yhyirdeh.html

[G05] 继承
来源：http://dali.iojbl.cn/Article/details/gt2xsvxecng.html

Py:   class Admin(User): pass
来源：http://dali.gaohongyu789.top/Article/details/gt2utjklbyr.html

PHP:  class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gt2esupqljy.html

JS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2hxynnhxn.html

TS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gt2zzcwocax.html

Java: class Admin extends User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ggodjwtt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.haohaochexian.top/Article/details/gt2puahakvq.html

Ruby: class Admin < User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2znllnpsn.html

C#:   class Admin : User {}
来源：http://dali.sysykeji.top/Article/details/gt2atadifeo.html

[G06] 重写方法
来源：http://dali.zdqjudy.top/Article/details/gt2iiledkku.html

Py:   def greet(self): return "admin"
来源：http://dali.hnxiangtu.top/Article/details/gt2kjnhnylw.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2donpetkl.html

JS:   greet() { return "admin"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vovumbzy.html

TS:   greet(): string { return "admin"; }
来源：http://dali.sweek.top/Article/details/gt2jhobrrle.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.svipenyu.cn/Article/details/gt2rystrrtt.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.jqgufenzy.top/Article/details/gt2sytrysyq.html

Ruby: def greet; "admin"; end
来源：http://dali.jiagoushi.top/Article/details/gt2rjpmuefo.html

C#:   public override string Greet() => "admin";
来源：http://dali.mhx1999.top/Article/details/gt2auavvbgl.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gt2zsrmlosv.html

Py:   super().greet()
来源：http://dali.guannengcc.top/Article/details/gt2hrfwbqqq.html

PHP:  parent::greet();
来源：http://dali.pycfn.com/Article/details/gt2vvfjdpgp.html

JS:   super.greet();
来源：http://dali.guowangkeji.top/Article/details/gt2vabapoug.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gt2xkaoygjq.html

Java: super.greet();
来源：http://dali.xuanzx.com/Article/details/gt2utksgeui.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pengpengdd.cyou/Article/details/gt2xbvmhubp.html

Ruby: super
来源：http://dali.ydzc1.top/Article/details/gt2eyysozbd.html

C#:   base.Greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pqkrefrl.html

[G08] 静态方法与属性
来源：http://dali.yangfankeji.com/Article/details/gt2sptoncgk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jiagoushi.top/Article/details/gt2uowfzwsr.html

PHP:  public static function f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2bcowjtxi.html

JS:   static f() {}
来源：http://dali.ppjwa.cn/Article/details/gt2alyshrcr.html

TS:   static f(): void {}
来源：http://dali.havefunace.top/Article/details/gt2ilukhgzx.html

Java: static void f() {}
来源：http://dali.yuanzhike.top/Article/details/gt2eusoymez.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xziqi.cn/Article/details/gt2ljvauyqz.html

Ruby: def self.f; end
来源：http://dali.jlsjyb.cn/Article/details/gt2qobmvezk.html

C#:   public static void F() {}
来源：http://dali.hammf.cn/Article/details/gt2ubktswyn.html

[G09] 接口 / 抽象类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jyfnbvxp.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.redwolf501.top/Article/details/gt2vphifrtn.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yonumen.top/Article/details/gt2kzkmmqni.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jqgfzy.top/Article/details/gt2ecdglval.html

TS:   interface Shape { area(): number; }
来源：http://dali.yangfankeji.com/Article/details/gt2jwldpycv.html

Java: interface Shape { double area(); }
来源：http://dali.haohaochexian.top/Article/details/gt2ffwfldtp.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.sufxvd.cn/Article/details/gt2imxmxizl.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aizwys.cn/Article/details/gt2fqoegnzr.html

C#:   interface IShape { double Area(); }
来源：http://dali.chenzaomai.com/Article/details/gt2yxorqxng.html


<!-- 参考信息 -->