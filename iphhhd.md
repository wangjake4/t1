代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gt2ljnezbgk.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.svipenyu.cn/Article/details/gt2xhdbahqw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2auevkdua.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2aueztcir.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.guowangkeji.top/Article/details/gt2pybuyzux.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.shuidangran.top/Article/details/gt2ikrkvphm.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.0kj1m.cn/Article/details/gt2pfudeuel.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfjdjlbb.html

[E14] URL 编码与 Base64
来源：http://dali.gzhubu.top/Article/details/gt2zkdkqdcg.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhixingplan.top/Article/details/gt2tkhcibef.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yonumen.top/Article/details/gt2weotssgc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.gaohongyu789.top/Article/details/gt2vrgydysa.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhixingplan.top/Article/details/gt2lwkcchna.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ybcxt.top/Article/details/gt2sgrfkpnd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cashguo.top/Article/details/gt2xhuoquup.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aizwys.cn/Article/details/gt2ehiqxwol.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.pengpengdd.cyou/Article/details/gt2kvyffuuk.html

[E15] HTML 转义 / 反转义
来源：http://dali.ivvv.top/Article/details/gt2rjmkkrqi.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cheryme.top/Article/details/gt2vkppteup.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cucudq.cn/Article/details/gt2ymwzcthe.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.fzhhl.top/Article/details/gt2brspznqd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.redwolf501.top/Article/details/gt2nzkjfgtt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xinyue.icu/Article/details/gt2csdltmho.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gt2vtrthdqh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2ohbbwxaf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhengqikj.top/Article/details/gt2hpjlgavg.html

[E16] 数字千分位
来源：http://dali.cqqwz.cn/Article/details/gt2wgojjbai.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2rcqczuzu.html

PHP:  number_format(1234567);
来源：http://dali.guannengcc.top/Article/details/gt2kgykpadx.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gotoacloud.top/Article/details/gt2mitlmhho.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yuanzhike.top/Article/details/gt2booypejm.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yuxming.cn/Article/details/gt2vrrrfubj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yueranfly.top/Article/details/gt2bbzlhhoq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2rpxmzooa.html

C#:   1234567.ToString("N0")
来源：http://dali.hywenlv.cn/Article/details/gt2agvtkakk.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gt2mhcvqpcj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ydzc1.top/Article/details/gt2tzwpuntn.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gt2loipwwne.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gt2zhaxlykz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gt2ncvhxxrk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guannengcc.top/Article/details/gt2bixvhpwx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.yongpay.top/Article/details/gt2pxnzvlwy.html

Ruby: s.capitalize
来源：http://dali.wangdashe.top/Article/details/gt2qocmfngb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shuidangran.top/Article/details/gt2cnghfklk.html

[E18] 模板占位符替换
来源：http://dali.gaohongyu789.top/Article/details/gt2xrpkktyv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hysaishi.cn/Article/details/gt2tlgfnpoi.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.daria6918.cn/Article/details/gt2yloepnse.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2kkppbqtt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gt2axbgjwar.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.meibo888.top/Article/details/gt2pzvtfvzt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gt2wkdlgoac.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.havefunace.top/Article/details/gt2gqtgwowl.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.guowangkeji.top/Article/details/gt2wreeuhpk.html

[E19] 多行文本按行拆分
来源：http://dali.hnxiangtu.top/Article/details/gt2saludmra.html

Py:   s.splitlines()
来源：http://dali.gotoacloud.top/Article/details/gt2vcupugbq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2ospvkuua.html

JS:   s.split(/\r?\n/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eqtynmiy.html

TS:   s.split(/\r?\n/)
来源：http://dali.c1oappe.top/Article/details/gt2nsfvcopp.html

Java: s.lines().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxhimnre.html

Go:   strings.Split(s, "\n")
来源：http://dali.jiagoushi.top/Article/details/gt2uhwmdcjx.html

Ruby: s.lines
来源：http://dali.gzhubu.top/Article/details/gt2rdfefazy.html

C#:   s.Split('\n')
来源：http://dali.jyoumei.cn/Article/details/gt2qgyfzclb.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gt2qrzmygfu.html

Py:   if not s:
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnzdryug.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.9152youxi.cn/Article/details/gt2jhuiczbl.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gt2begkiatz.html

TS:   if (s === "") {}
来源：http://dali.xuanzx.com/Article/details/gt2ddqcjnep.html

Java: if (s.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gt2oovohlij.html

Go:   if s == "" {}
来源：http://dali.guannengcc.top/Article/details/gt2zcencvem.html

Ruby: if s.empty?
来源：http://dali.yuxming.cn/Article/details/gt2qeiwtthh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhengqikj.top/Article/details/gt2pkwxrupr.html

[E21] 超长截断加省略号
来源：http://dali.xziqi.cn/Article/details/gt2hcgoykrq.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xziqi.cn/Article/details/gt2izxeiezb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gt2ozuohpza.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2gmhwxcft.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gt2fntiffmr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2fcgawvpl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.svipenyu.cn/Article/details/gt2jltlpsgj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2silmpczy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.sysykeji.top/Article/details/gt2cjjqxtog.html

[E22] 字节长度与字符长度
来源：http://dali.hywenlv.cn/Article/details/gt2dqmmcovl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.guannengcc.top/Article/details/gt2yypfzkpd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yonumen.top/Article/details/gt2vlyscelx.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgvkdsbs.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gt2iomynawj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.svipenyu.cn/Article/details/gt2agofwlis.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.cheryme.top/Article/details/gt2ziaxtbhi.html

Ruby: s.bytesize;  s.length
来源：http://dali.xuanzx.com/Article/details/gt2lxliwzrq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.andypj.xyz/Article/details/gt2qmnfiape.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2qpcvrqsd.html

F. 文件与目录
来源：http://dali.316326.xyz/Article/details/gt2agexbioy.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2gquccfod.html

[F01] 读取整个文件
来源：http://dali.nanxinkj.top/Article/details/gt2eybfgvur.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xinyue.icu/Article/details/gt2hpdikpdi.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2gjwskcaz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gt2yjvyhlod.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxmyfdth.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbjfxto.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gt2kpgfppbx.html

Ruby: File.read("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2zyxkvbjx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhomvmmc.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gt2ojshdldb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhixingplan.top/Article/details/gt2cfdcalnl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jtagqhdn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gt2tzzvpmxe.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2mlaerpee.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hywenlv.cn/Article/details/gt2lixnjgxo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.cashguo.top/Article/details/gt2ksdazgny.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gt2cokquqrh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.zhongyouzk.top/Article/details/gt2wwtocvri.html

[F03] 写入文件（覆盖）
来源：http://dali.cqqwz.cn/Article/details/gt2ptbdyjml.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.wangdashe.top/Article/details/gt2iudejtin.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.birdmap.top/Article/details/gt2fzgjldcs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gt2kzkrctej.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhoulong.xyz/Article/details/gt2iklfmtme.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ehwqpu.com/Article/details/gt2nyizgsrz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbxlxmwl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.andypj.xyz/Article/details/gt2rnzfhxlq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2cjlvuhfq.html

[F04] 追加写入文件
来源：http://dali.xziqi.cn/Article/details/gt2egyiguxg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cdnleiting.top/Article/details/gt2eurfbgok.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yonumen.top/Article/details/gt2croavjiw.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2fkmzspgy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pnorxrca.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.redwolf501.top/Article/details/gt2ekkxesbz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuxming.cn/Article/details/gt2hghytmsz.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.mhx1999.top/Article/details/gt2gvhcmbcx.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.dashuyun.cn/Article/details/gt2klvqhzgu.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zstkjpjg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jyoumei.cn/Article/details/gt2vqjxxjii.html

PHP:  file_exists("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2twwbmdhz.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gt2amebhpze.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj20258.top/Article/details/gt2gdjkmnxt.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2pnphwhyg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zycfv.cn/Article/details/gt2uorrtpdf.html

Ruby: File.exist?("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2novgozzx.html

C#:   File.Exists("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2zdhhoghd.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gt2tkmagyzp.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2ohwdplkc.html

PHP:  unlink("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gt2lwbkjbmy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2ouuilboc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gt2easvdlrq.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2mypdvqit.html

Go:   os.Remove("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2lnjngdjm.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2vqmlcwye.html

C#:   File.Delete("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2texrldqm.html

[F07] 创建目录（含多级）
来源：http://dali.xziqi.cn/Article/details/gt2nwarvayi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gt2hdejioog.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.ivvv.top/Article/details/gt2glycegem.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gt2mocioigs.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xztwhpjw.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.tianlin.xyz/Article/details/gt2ugecsxot.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgfzy.top/Article/details/gt2mbmgchvi.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.hfpthk.cn/Article/details/gt2rkwdrhkn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhijiandao.cn/Article/details/gt2qtnfybrp.html

[F08] 遍历目录
来源：http://dali.hywenlv.cn/Article/details/gt2pyunbdls.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ncyvigtd.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.tianlin.xyz/Article/details/gt2qugnlxil.html

JS:   fs.readdirSync("dir")
来源：http://dali.meibo888.top/Article/details/gt2ibivcoei.html

TS:   fs.readdirSync("dir")
来源：http://dali.cheryme.top/Article/details/gt2mcpawzeq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gt2tnqorttd.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gotoacloud.top/Article/details/gt2tndhcfjb.html

Ruby: Dir.children("dir")
来源：http://dali.nwbrower.top/Article/details/gt2klzkdpnk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.havefunace.top/Article/details/gt2bzsxbrqm.html

[F09] 获取文件大小
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwzgsbvq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2hohmddrn.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gt2yyanixmp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gt2zlxcluyv.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yongpay.top/Article/details/gt2zxzlzjgs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gt2epkjille.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gzhubu.top/Article/details/gt2npifaoiq.html

Ruby: File.size("a.txt")
来源：http://dali.fengsongda.top/Article/details/gt2nkigrgjf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ydzc1.top/Article/details/gt2ygcjtzcd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yonumen.top/Article/details/gt2trecamyv.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2ivtxqdqa.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2mojacqaf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2gibbbfwe.html

TS:   path.extname("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2hgriuile.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ivvv.top/Article/details/gt2xrkunhhv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2rsdysiup.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2ikkptfdn.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2whbzjyyq.html

[F11] 复制与移动文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxwhuzvh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2roeeehjt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxinkj.top/Article/details/gt2ruqynmbq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fengsongda.top/Article/details/gt2kspbzgse.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2svezgmwv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqncelva.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.vqdsnc.cn/Article/details/gt2npqlzrsi.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gt2eiewryaz.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gt2ksjxsdkj.html

[F12] CSV 读写
来源：http://dali.9152youxi.cn/Article/details/gt2eskdzmwz.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.cdnleiting.top/Article/details/gt2jcrhjepf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daria6918.cn/Article/details/gt2jpiqogfa.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vneupoct.html

TS:   // 同上
来源：http://dali.316326.xyz/Article/details/gt2nlubgwzk.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.nanxuanxn.top/Article/details/gt2ocruakfa.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.gogol.net.cn/Article/details/gt2qilsxugs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gt2idbpcqsh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zdqjudy.top/Article/details/gt2jtewrzay.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2pmtdxgsv.html

G. 面向对象
来源：http://dali.hysaishi.cn/Article/details/gt2jdlafnoo.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2igyapiig.html

[G01] 定义类
来源：http://dali.yj20258.top/Article/details/gt2lmpifudd.html

Py:   class User: pass
来源：http://dali.meibo888.top/Article/details/gt2xpvwhfgb.html

PHP:  class User {}
来源：http://dali.guowangkeji.top/Article/details/gt2ilolwshv.html

JS:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gt2aevvlslz.html

TS:   class User { name: string = ""; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zarisgqw.html

Java: class User {}
来源：http://dali.meibo888.top/Article/details/gt2vxwezalr.html

Go:   type User struct { Name string }
来源：http://dali.yangfankeji.com/Article/details/gt2axfieggc.html

Ruby: class User; end
来源：http://dali.chenlongwang.top/Article/details/gt2epqedung.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gt2zaatkysx.html

[G02] 构造函数
来源：http://dali.yj202588.top/Article/details/gt2tzhpcsno.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.iojbl.cn/Article/details/gt2oubkvtro.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhengqikj.top/Article/details/gt2dqamjnoz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.iojbl.cn/Article/details/gt2sgrwbmyn.html

TS:   constructor(public name: string) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2objbbelm.html

Java: User(String name) { this.name = name; }
来源：http://dali.xinyue.icu/Article/details/gt2nsbgeofu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gt2tisjguxm.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhixingplan.top/Article/details/gt2heztqcgj.html

C#:   public User(string name) { Name = name; }
来源：http://dali.0kj1m.cn/Article/details/gt2psftshwm.html

[G03] 实例属性
来源：http://dali.snrcjt.cn/Article/details/gt2pnvzdomf.html

Py:   self.name = "x"
来源：http://dali.jiagoushi.top/Article/details/gt2vsqnfeca.html

PHP:  public string $name = "x";
来源：http://dali.zhijiandao.cn/Article/details/gt2hamuzrzl.html

JS:   this.name = "x";
来源：http://dali.jinqigufen.top/Article/details/gt2hdxfkvwc.html

TS:   name: string = "x";
来源：http://dali.tian-w.cn/Article/details/gt2fpuipync.html

Java: private String name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2fencusnb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gt2zvtjyggj.html

Ruby: @name = "x"
来源：http://dali.ppjwa.cn/Article/details/gt2rygcwaai.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bxezqkjh.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gt2fsgjkvwg.html

Py:   def greet(self): return self.name
来源：http://dali.0kj1m.cn/Article/details/gt2gcwmjerd.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bjkbsqtf.html

JS:   greet() { return this.name; }
来源：http://dali.zhixingplan.top/Article/details/gt2vadhtidw.html

TS:   greet(): string { return this.name; }
来源：http://dali.yj20258888.top/Article/details/gt2hjpybqgl.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2osbpewmt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenlongwang.top/Article/details/gt2naomlgqs.html

Ruby: def greet; @name; end
来源：http://dali.nanxuanxn.top/Article/details/gt2nzvirehp.html

C#:   public string Greet() => Name;
来源：http://dali.nanxinkj.top/Article/details/gt2nksmatcd.html

[G05] 继承
来源：http://dali.tanke756.top/Article/details/gt2ccyamuod.html

Py:   class Admin(User): pass
来源：http://dali.sxryk.cn/Article/details/gt2nbarpqxo.html

PHP:  class Admin extends User {}
来源：http://dali.iojbl.cn/Article/details/gt2zplpzlqk.html

JS:   class Admin extends User {}
来源：http://dali.ivvv.top/Article/details/gt2tcntsbfh.html

TS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gt2bajnxxra.html

Java: class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2dkzcpjad.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tian-w.cn/Article/details/gt2yolwuqsx.html

Ruby: class Admin < User; end
来源：http://dali.fengsongda.top/Article/details/gt2kuvifmlh.html

C#:   class Admin : User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2udarmrtt.html

[G06] 重写方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2tntvjihl.html

Py:   def greet(self): return "admin"
来源：http://dali.hfpthk.cn/Article/details/gt2soyalyhs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yj20258888.top/Article/details/gt2ravcuuxr.html

JS:   greet() { return "admin"; }
来源：http://dali.xylfe.cn/Article/details/gt2qmlevwmo.html

TS:   greet(): string { return "admin"; }
来源：http://dali.cheryme.top/Article/details/gt2vyicdrtz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gt2csilanrx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.tanke756.top/Article/details/gt2sknwymxp.html

Ruby: def greet; "admin"; end
来源：http://dali.vqdsnc.cn/Article/details/gt2vvdgsmek.html

C#:   public override string Greet() => "admin";
来源：http://dali.havefunace.top/Article/details/gt2bffpzskv.html

[G07] 调用父类方法
来源：http://dali.cheryme.top/Article/details/gt2vyjyxshw.html

Py:   super().greet()
来源：http://dali.xziqi.cn/Article/details/gt2ygxtzrft.html

PHP:  parent::greet();
来源：http://dali.yuanzhike.top/Article/details/gt2rqhuhqdx.html

JS:   super.greet();
来源：http://dali.yonumen.top/Article/details/gt2wevqbqwd.html

TS:   super.greet();
来源：http://dali.guannengcc.top/Article/details/gt2ayhbjlek.html

Java: super.greet();
来源：http://dali.c1oappe.top/Article/details/gt2revoxzhs.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.sufxvd.cn/Article/details/gt2ssabdasn.html

Ruby: super
来源：http://dali.sxryk.cn/Article/details/gt2hhmcczus.html

C#:   base.Greet();
来源：http://dali.hysaishi.cn/Article/details/gt2jcbwjsep.html

[G08] 静态方法与属性
来源：http://dali.0kj1m.cn/Article/details/gt2xnxundqi.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.yj202588.top/Article/details/gt2dbdetrhf.html

PHP:  public static function f() {}
来源：http://dali.xinyue.icu/Article/details/gt2fotwseyq.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gt2aqzslrss.html

TS:   static f(): void {}
来源：http://dali.jianghu66.top/Article/details/gt2dqpnhmku.html

Java: static void f() {}
来源：http://dali.meibo888.top/Article/details/gt2xfvxtelg.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jqgufenzy.top/Article/details/gt2qnwkingi.html

Ruby: def self.f; end
来源：http://dali.dashuyun.cn/Article/details/gt2nqsekaww.html

C#:   public static void F() {}
来源：http://dali.havefunace.top/Article/details/gt2cjvnugmi.html

[G09] 接口 / 抽象类
来源：http://dali.jinghuilouyu.cn/Article/details/gt2soxjnzcv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhengqikj.top/Article/details/gt2wqjsnoot.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.sxryk.cn/Article/details/gt2vifehuga.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.shzxlz.cn/Article/details/gt2pqqaghqp.html

TS:   interface Shape { area(): number; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxiunfnu.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gt2rcbzvvco.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zdqjudy.top/Article/details/gt2bowvgxjh.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.316326.xyz/Article/details/gt2pmwlplrr.html

C#:   interface IShape { double Area(); }
来源：http://dali.kuanghao11.cn/Article/details/gt2vwktgrfk.html

[G10] 访问控制
来源：http://dali.jqgufenzy.top/Article/details/gt2xwjbphst.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.xziqi.cn/Article/details/gt2ibofsbdp.html

PHP:  public / protected / private
来源：http://dali.bjfxy.top/Article/details/gt2fjvzxlvy.html

JS:   #private 字段；其余公开
来源：http://dali.zhongyouzk.top/Article/details/gt2oshjcvsy.html

TS:   public / protected / private
来源：http://dali.cashguo.top/Article/details/gt2qdaedkxx.html

Java: public / protected / private / 默认包级
来源：http://dali.ehwqpu.com/Article/details/gt2symjxwnj.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gt2zvlbcksw.html

Ruby: public / protected / private
来源：http://dali.xylfe.cn/Article/details/gt2alicheao.html

C#:   public / protected / private / internal
来源：http://dali.aibaodan.cn/Article/details/gt2rgcxjnax.html

[G11] getter / setter
来源：http://dali.ppjwa.cn/Article/details/gt2selfpqlk.html

Py:   @property 与 @x.setter
来源：http://dali.aibaodan.cn/Article/details/gt2kxrwwvta.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jinqigufen.top/Article/details/gt2ifryuhci.html

JS:   get name() { return this._name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjywqupk.html

TS:   get name(): string { return this._name; }
来源：http://dali.tianlin.xyz/Article/details/gt2exkngsxy.html

Java: public String getName() { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2yiibflsu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.yvedp.cn/Article/details/gt2qkocsqoi.html


<!-- 参考信息 -->