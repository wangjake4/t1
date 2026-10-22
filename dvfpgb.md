代发 wailian999

Py:   for ch in s: print(ch)
来源：http://dali.vqdsnc.cn/Article/details/gthxokekap.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gtevpzwfxk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.316326.xyz/Article/details/gtxsvuyqrh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenzaomai.com/Article/details/gtksjvuokt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shuidangran.top/Article/details/gteipospat.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gtzsuyhqmb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.feifeiyinyue.top/Article/details/gtwdnznipa.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ppjwa.cn/Article/details/gtxorkbahi.html

[E14] URL 编码与 Base64
来源：http://dali.yj20258888.top/Article/details/gtbeszingn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.meibo888.top/Article/details/gtdniyqhxh.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gtjlzbjxqk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.daria6918.cn/Article/details/gtrebxpuho.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nwbrower.top/Article/details/gtakcwgvch.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.ybcxt.top/Article/details/gtpogvgfzg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gtbumhyedq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxinkj.top/Article/details/gtgfxwvmsr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xziqi.cn/Article/details/gtuxewpumh.html

[E15] HTML 转义 / 反转义
来源：http://dali.redwolf501.top/Article/details/gticzettkm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hysaishi.cn/Article/details/gtozkyiczm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ppjwa.cn/Article/details/gtymmszaim.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gtvhnbzgsx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xylfe.cn/Article/details/gtminvjlig.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gtygeabzfx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sufxvd.cn/Article/details/gtjyjsqzou.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.birdmap.top/Article/details/gthzpgcwqo.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gttzyyydiv.html

[E16] 数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtcvckgwyo.html

Py:   f"{1234567:,}"
来源：http://dali.yongpay.top/Article/details/gtdpnflake.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gtakbpwksi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gtqkbbskdh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangtech.top/Article/details/gteyxgargj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gtnssohjdn.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gtoieddcqv.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guowangkeji.top/Article/details/gthacaowvz.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxscckhpj.html

[E17] 首字母大写
来源：http://dali.cheryme.top/Article/details/gtedovzdkp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xziqi.cn/Article/details/gtlbymqsxe.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daxiang520.top/Article/details/gtbeeonqfc.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shuidangran.top/Article/details/gttagnlxhn.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitiixxqm.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hfpthk.cn/Article/details/gtfkyknygh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guowangkeji.top/Article/details/gtqpybboas.html

Ruby: s.capitalize
来源：http://dali.aibaodan.cn/Article/details/gtezopnfge.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hywenlv.cn/Article/details/gtxfjpvupx.html

[E18] 模板占位符替换
来源：http://dali.0kj1m.cn/Article/details/gtegghcjwt.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hammf.cn/Article/details/gtrmpsnuzc.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gtytrchmfe.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtnjnygrbj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtyhozgqsl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtuipxshjm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtndizllof.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.316326.xyz/Article/details/gtqzkroihh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gaohongyu789.top/Article/details/gtmtmtrwtc.html

[E19] 多行文本按行拆分
来源：http://dali.vqdsnc.cn/Article/details/gtbflpdqjo.html

Py:   s.splitlines()
来源：http://dali.yj202588.top/Article/details/gtevfgqkme.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jiagoushi.top/Article/details/gtdzdrllta.html

JS:   s.split(/\r?\n/)
来源：http://dali.dashuyun.cn/Article/details/gtulqrnmqr.html

TS:   s.split(/\r?\n/)
来源：http://dali.jianghu66.top/Article/details/gtnndgylqh.html

Java: s.lines().toList()
来源：http://dali.dashuyun.cn/Article/details/gtqezuebkj.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenzaomai.com/Article/details/gtkzercueg.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gtwzgsnnmn.html

C#:   s.Split('\n')
来源：http://dali.xylfe.cn/Article/details/gtvzlxjgxp.html

[E20] 判断字符串是否为空
来源：http://dali.jiagoushi.top/Article/details/gtdebwccqw.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gtloowzghx.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.redwolf501.top/Article/details/gtctfdjrab.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbcpyldu.html

TS:   if (s === "") {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdttiueql.html

Java: if (s.isEmpty()) {}
来源：http://dali.bjfxy.top/Article/details/gtwkyhhuwb.html

Go:   if s == "" {}
来源：http://dali.cdnleiting.top/Article/details/gttaibunbz.html

Ruby: if s.empty?
来源：http://dali.svipenyu.cn/Article/details/gtfwnkgqmn.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangdashe.top/Article/details/gtulezafdp.html

[E21] 超长截断加省略号
来源：http://dali.ivvv.top/Article/details/gtrdsmrxaz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuetiantiany.cn/Article/details/gtnmkhouue.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gtzlvndfwn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbnuoghqf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gthdqcfefj.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtnklwdmcq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yj202588.top/Article/details/gttzgamfjb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtmbtnlxrv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cashguo.top/Article/details/gtoklslmca.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gtzhfqqkvm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gthbowotzi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gtephnueai.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtuoyargco.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtmwwmpyva.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.bjfxy.top/Article/details/gtojqymajy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigfzy.top/Article/details/gtmujqusms.html

Ruby: s.bytesize;  s.length
来源：http://dali.pengpengdd.cyou/Article/details/gtnrvreyvb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtislpzjjn.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqpuwmktz.html

F. 文件与目录
来源：http://dali.yonumen.top/Article/details/gtcivljavf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttyzoztgu.html

[F01] 读取整个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtynghcqxx.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.aibaodan.cn/Article/details/gtjayziukl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtzewxhsho.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.feifeiyinyue.top/Article/details/gtiunxfaaz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtogatmiof.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gthdnhohsw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cashguo.top/Article/details/gtacysxszn.html

Ruby: File.read("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtaicynepn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtlpyadnfk.html

[F02] 逐行读取文件
来源：http://dali.pengpengdd.cyou/Article/details/gtyhrauuyv.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangdashe.top/Article/details/gtxbkrrmai.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.bjfxy.top/Article/details/gtobsoxxwd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtzepzeg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gttaxapvyq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gtbfasmxsa.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.sysykeji.top/Article/details/gtyqruzoqn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ivvv.top/Article/details/gtygjstyks.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigufen.top/Article/details/gtnlwxvher.html

[F03] 写入文件（覆盖）
来源：http://dali.shangyingyoupin.top/Article/details/gtjzanxlrf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tian-w.cn/Article/details/gtxzzjyoxd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtssyvljmx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtdcazdasa.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.feifeiyinyue.top/Article/details/gtissymxbr.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.chenjidiqi.icu/Article/details/gtdzumrhxz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgfzy.top/Article/details/gtzijsrnvp.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yueranfly.top/Article/details/gtxgvnqwvt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtisjbwthi.html

[F04] 追加写入文件
来源：http://dali.aizwys.cn/Article/details/gtdjcllrps.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhiwuduotai.top/Article/details/gtnxrguttc.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj202588.top/Article/details/gtfpbyryxf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gtjfkrdnre.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gtwpjoqpyu.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.aizwys.cn/Article/details/gtppgpxlcz.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.pycfn.com/Article/details/gtyxkvvcey.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yuxming.cn/Article/details/gthcydgobn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.redwolf501.top/Article/details/gtjssyxapg.html

[F05] 判断文件或目录是否存在
来源：http://dali.fzhhl.top/Article/details/gtfjajnnjo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gzhubu.top/Article/details/gtnmlxpxzz.html

PHP:  file_exists("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtpbkwrdmp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtvjjlycgb.html

TS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtzmvppxrq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.sweek.top/Article/details/gtjkkaequc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhiwuduotai.top/Article/details/gtbbqpfnde.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtdmtvfweo.html

C#:   File.Exists("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtwohjszxl.html

[F06] 删除文件
来源：http://dali.feifeiyinyue.top/Article/details/gtrvtmaulz.html

Py:   os.remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtsopnfhiy.html

PHP:  unlink("a.txt");
来源：http://dali.svipenyu.cn/Article/details/gtyucxwtsg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtiqwklqnp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtrcylnygp.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtwnslcqwg.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtkcqmfisu.html

Ruby: File.delete("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtqvnrcwzd.html

C#:   File.Delete("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtwedifxqc.html

[F07] 创建目录（含多级）
来源：http://dali.xuanzx.com/Article/details/gtdwszmgyr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtvrelemcv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jqgfzy.top/Article/details/gtrvdjjphq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gtddhpoegq.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtnnkggtux.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.aibaodan.cn/Article/details/gtzdykydef.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aizwys.cn/Article/details/gtlpwomfur.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.chenzaomai.com/Article/details/gtiwhbqlkq.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.daxiang520.top/Article/details/gtzbvdoefy.html

[F08] 遍历目录
来源：http://dali.yonumen.top/Article/details/gtiysyvrxu.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.andypj.xyz/Article/details/gtkifbfers.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.nanxuanxn.top/Article/details/gtdqrafucv.html

JS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gthnfsjdvz.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gteopaptql.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gthttycfxn.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigfzy.top/Article/details/gthzsgaeki.html

Ruby: Dir.children("dir")
来源：http://dali.ydzc1.top/Article/details/gtajqmeuhu.html

C#:   Directory.GetFiles("dir")
来源：http://dali.sysykeji.top/Article/details/gtaiwwttpg.html

[F09] 获取文件大小
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxtsthpt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtrqaalmxm.html

PHP:  filesize("a.txt");
来源：http://dali.ydzc1.top/Article/details/gthcikkcaa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hnxiangtu.top/Article/details/gtlxtumkvx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqrfbjei.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.9152youxi.cn/Article/details/gtzncijngv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nwbrower.top/Article/details/gtwinwodkx.html

Ruby: File.size("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gttudkqjrz.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pycfn.com/Article/details/gtqftzttdx.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gtegxpooua.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gtmyprriyd.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fengsongda.top/Article/details/gtfgqwolwi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtrzbfvbsb.html

TS:   path.extname("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtcrmabiwt.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sweek.top/Article/details/gtaouihzrz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtkwvxmkyn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gtwxttaxjk.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtfeswsnrq.html

[F11] 复制与移动文件
来源：http://dali.cucudq.cn/Article/details/gtnhtfiijr.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gttageeegr.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtpgsldzmm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtwhfngrlj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.dashuyun.cn/Article/details/gtpqengeln.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtylxfkyoe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hysaishi.cn/Article/details/gtchrphzge.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gtkiiwlhbw.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhengqikj.top/Article/details/gtqdxslujj.html

[F12] CSV 读写
来源：http://dali.sufxvd.cn/Article/details/gtlssdsqwa.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ehwqpu.com/Article/details/gtbgvvhhqd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hysaishi.cn/Article/details/gtnjiuefoz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukajiejj.html

TS:   // 同上
来源：http://dali.yonumen.top/Article/details/gtfhscpbec.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinqigufen.top/Article/details/gtpbfjxawk.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqhmjxjw.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gthwqxwgwm.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pycfn.com/Article/details/gtclshxsfz.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtarvzmnev.html

G. 面向对象
来源：http://dali.yanxiufei.cn/Article/details/gtnvvvaobj.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtglspjacm.html

[G01] 定义类
来源：http://dali.snrcjt.cn/Article/details/gtlfildjch.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gtovwlgtdy.html

PHP:  class User {}
来源：http://dali.hfpthk.cn/Article/details/gtndhkzjoh.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gthkhpmdgc.html

TS:   class User { name: string = ""; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbveilno.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gtxerzopgs.html

Go:   type User struct { Name string }
来源：http://dali.quarkkingdee.top/Article/details/gtlevhznwr.html

Ruby: class User; end
来源：http://dali.hammf.cn/Article/details/gtyubstijs.html

C#:   class User {}
来源：http://dali.xinyue.icu/Article/details/gtonlkucan.html

[G02] 构造函数
来源：http://dali.tian-w.cn/Article/details/gtckwpqysf.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.havefunace.top/Article/details/gtavbriktk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.nwbrower.top/Article/details/gtlgjpjsnv.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cucudq.cn/Article/details/gtcixpxnsw.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gtzvzwhxyq.html

Java: User(String name) { this.name = name; }
来源：http://dali.fzhhl.top/Article/details/gtwmgwtmyu.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yanxiufei.cn/Article/details/gtwurwsyfs.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jinqigufen.top/Article/details/gtraervvqa.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnqzz.top/Article/details/gtyybrregz.html

[G03] 实例属性
来源：http://dali.xziqi.cn/Article/details/gtodqatnzb.html

Py:   self.name = "x"
来源：http://dali.jyoumei.cn/Article/details/gtrrkihkto.html

PHP:  public string $name = "x";
来源：http://dali.hnqzz.top/Article/details/gtmgakcdsu.html

JS:   this.name = "x";
来源：http://dali.cheryme.top/Article/details/gtomdivxwx.html

TS:   name: string = "x";
来源：http://dali.chenjidiqi.icu/Article/details/gtqvobmnxa.html

Java: private String name;
来源：http://dali.kuanghao11.cn/Article/details/gtryoqzpae.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.jinqigufen.top/Article/details/gtkrzpcyki.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gtjhusxcvs.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cqqwz.cn/Article/details/gtgntnwxdt.html

[G04] 定义方法
来源：http://dali.ehwqpu.com/Article/details/gtyyxwiiqp.html

Py:   def greet(self): return self.name
来源：http://dali.fzhhl.top/Article/details/gturiwomja.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.shuidangran.top/Article/details/gtibluxjlw.html

JS:   greet() { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtmaqssuer.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gtuihzzqnc.html

Java: String greet() { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtxxkwrvxy.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.bjfxy.top/Article/details/gtrctigymj.html

Ruby: def greet; @name; end
来源：http://dali.xuetiantiany.cn/Article/details/gtocoeqchk.html

C#:   public string Greet() => Name;
来源：http://dali.jinqigfzy.top/Article/details/gtpyqbixvf.html

[G05] 继承
来源：http://dali.yuanzhike.top/Article/details/gtlvuvdgto.html

Py:   class Admin(User): pass
来源：http://dali.gogol.net.cn/Article/details/gtskhxzuzr.html

PHP:  class Admin extends User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvdrjfqog.html

JS:   class Admin extends User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtjkudpqtj.html

TS:   class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtgjvxcgzb.html

Java: class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gtiqnmkduo.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gtdatlpfkr.html

Ruby: class Admin < User; end
来源：http://dali.cdnleiting.top/Article/details/gtbjctdrtf.html

C#:   class Admin : User {}
来源：http://dali.jianghu66.top/Article/details/gtzajbnjse.html

[G06] 重写方法
来源：http://dali.sufxvd.cn/Article/details/gtqccmuntq.html

Py:   def greet(self): return "admin"
来源：http://dali.nwbrower.top/Article/details/gtadepvpkj.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.c1oappe.top/Article/details/gtvepgrojq.html

JS:   greet() { return "admin"; }
来源：http://dali.yj202588.top/Article/details/gtfrnncoku.html

TS:   greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtvlvkajjs.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsujvvqz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gogol.net.cn/Article/details/gtjshocfbk.html

Ruby: def greet; "admin"; end
来源：http://dali.nwbrower.top/Article/details/gttpnbgbha.html

C#:   public override string Greet() => "admin";
来源：http://dali.gzhubu.top/Article/details/gtjipplrpt.html

[G07] 调用父类方法
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvdiernt.html

Py:   super().greet()
来源：http://dali.zhongyouzk.top/Article/details/gtvzefamdo.html

PHP:  parent::greet();
来源：http://dali.yj202588.top/Article/details/gtbctfzfox.html

JS:   super.greet();
来源：http://dali.chenlongwang.top/Article/details/gtyygrzppl.html

TS:   super.greet();
来源：http://dali.xuanzx.com/Article/details/gtantqdjvs.html

Java: super.greet();
来源：http://dali.shuidangran.top/Article/details/gtappedfmj.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.bjfxy.top/Article/details/gtfazbgqpr.html

Ruby: super
来源：http://dali.jqgfzy.top/Article/details/gtdbzfhovk.html

C#:   base.Greet();
来源：http://dali.zycfv.cn/Article/details/gtxnqjlcbs.html

[G08] 静态方法与属性
来源：http://dali.chenzaomai.com/Article/details/gtfmkdtglg.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jlsjyb.cn/Article/details/gtkukbfbxp.html

PHP:  public static function f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gtlwsphopy.html

JS:   static f() {}
来源：http://dali.ybcxt.top/Article/details/gtqetrwnma.html

TS:   static f(): void {}
来源：http://dali.jqgufenzy.top/Article/details/gtibgiexyq.html

Java: static void f() {}
来源：http://dali.sysykeji.top/Article/details/gtyuvyhfyt.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yueranfly.top/Article/details/gtnnbrynnu.html

Ruby: def self.f; end
来源：http://dali.jyoumei.cn/Article/details/gtnprqkwnh.html

C#:   public static void F() {}
来源：http://dali.yuanzhike.top/Article/details/gtwthwhiey.html

[G09] 接口 / 抽象类
来源：http://dali.kuanghao11.cn/Article/details/gtdlzwalwe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.shzxlz.cn/Article/details/gttdtgzhws.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hysaishi.cn/Article/details/gtrpyypuhr.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pycfn.com/Article/details/gtczxgkqvr.html

TS:   interface Shape { area(): number; }
来源：http://dali.0kj1m.cn/Article/details/gtinxcyzpe.html

Java: interface Shape { double area(); }
来源：http://dali.quarkkingdee.top/Article/details/gtulnmogsz.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.mhx1999.top/Article/details/gtxigczuzz.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.aibaodan.cn/Article/details/gtcmximknw.html

C#:   interface IShape { double Area(); }
来源：http://dali.yuanzhike.top/Article/details/gtadykfaur.html

[G10] 访问控制
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkytwrxvf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.wangshuangyany.cn/Article/details/gtgtpwmtqr.html

PHP:  public / protected / private
来源：http://dali.nanxuanxn.top/Article/details/gtzwvbgusj.html

JS:   #private 字段；其余公开
来源：http://dali.gotoacloud.top/Article/details/gtxjolpbvv.html

TS:   public / protected / private
来源：http://dali.yonumen.top/Article/details/gtjqkmttpw.html

Java: public / protected / private / 默认包级
来源：http://dali.wangdashe.top/Article/details/gthtgvmgko.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.zdqjudy.top/Article/details/gtbmrloyho.html

Ruby: public / protected / private
来源：http://dali.ybcxt.top/Article/details/gtmknwxzcm.html

C#:   public / protected / private / internal
来源：http://dali.yj20258.top/Article/details/gtaxdlapvm.html

[G11] getter / setter
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpjoivoh.html

Py:   @property 与 @x.setter
来源：http://dali.fzhhl.top/Article/details/gtarqpxrgh.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.tianlin.xyz/Article/details/gtueinorio.html

JS:   get name() { return this._name; }
来源：http://dali.cashguo.top/Article/details/gtnwcdiixf.html

TS:   get name(): string { return this._name; }
来源：http://dali.yvedp.cn/Article/details/gtwiauvrlk.html

Java: public String getName() { return name; }
来源：http://dali.xinyue.icu/Article/details/gttthwckhu.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.svipenyu.cn/Article/details/gtikajlmfz.html


<!-- 参考信息 -->