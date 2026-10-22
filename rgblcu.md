代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gtjcraiebl.html

Java: String.format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtislryvji.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.svipenyu.cn/Article/details/gtgfdivkqq.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gtpvxgdofj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenlongwang.top/Article/details/gtjosbivgp.html

[E11] 反转字符串
来源：http://dali.zhijiandao.cn/Article/details/gtuxedarvr.html

Py:   s[::-1]
来源：http://dali.jinqigufen.top/Article/details/gtbeshcbrd.html

PHP:  strrev($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlipwltkz.html

JS:   [...s].reverse().join("")
来源：http://dali.jianghu66.top/Article/details/gtahrdqvbz.html

TS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtobnmaceq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gtquvolatk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gzhubu.top/Article/details/gtrgxwntdu.html

Ruby: s.reverse
来源：http://dali.yj202588.top/Article/details/gtolnwvknb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnqzz.top/Article/details/gtqiyvbipl.html

[E12] 统计某字符出现次数
来源：http://dali.gotoacloud.top/Article/details/gtkxegfkiy.html

Py:   s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtpfjxnxqx.html

PHP:  substr_count($s, "a");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvrlnwzw.html

JS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gthzgymhci.html

TS:   s.split("a").length - 1
来源：http://dali.chenlongwang.top/Article/details/gtjxatlwjd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.fengsongda.top/Article/details/gtomdfsvvf.html

Go:   strings.Count(s, "a")
来源：http://dali.zdqjudy.top/Article/details/gtdjksbosq.html

Ruby: s.count("a")
来源：http://dali.hammf.cn/Article/details/gtfmbcbtxk.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiaonbkih.html

[E13] 逐字符遍历
来源：http://dali.jiagoushi.top/Article/details/gtxvpobpzx.html

Py:   for ch in s: print(ch)
来源：http://dali.cucudq.cn/Article/details/gtskoczrfi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jqgufenzy.top/Article/details/gtvialvokf.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gtrilmmidg.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gthxnzwvcc.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtkpusywwk.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jqgfzy.top/Article/details/gtlbhypkft.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.snrcjt.cn/Article/details/gtvbbygcwb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yvedp.cn/Article/details/gtzbplnxyd.html

[E14] URL 编码与 Base64
来源：http://dali.shuidangran.top/Article/details/gtbangowfh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yangfankeji.com/Article/details/gtddndizrp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gotoacloud.top/Article/details/gtpqhxqrql.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hammf.cn/Article/details/gttmabfmwg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgufenzy.top/Article/details/gtxffobgle.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.havefunace.top/Article/details/gtlejknnhu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cqqwz.cn/Article/details/gtyopugroe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.aibaodan.cn/Article/details/gtuzwtsnfh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhijiandao.cn/Article/details/gtrjzuaihl.html

[E15] HTML 转义 / 反转义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmgeaumd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yuxming.cn/Article/details/gtqbxjxbwj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gtlcebkqdr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sxryk.cn/Article/details/gtegmgbufi.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.redwolf501.top/Article/details/gtpdfmrxya.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yongpay.top/Article/details/gtntwaundw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtxyajfixo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hammf.cn/Article/details/gtutbcifcb.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gtcmupvaom.html

[E16] 数字千分位
来源：http://dali.hfpthk.cn/Article/details/gtlbelyyaj.html

Py:   f"{1234567:,}"
来源：http://dali.sweek.top/Article/details/gtasitpjst.html

PHP:  number_format(1234567);
来源：http://dali.gaohongyu789.top/Article/details/gtmyvuwpew.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtoxacuxdb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.gaohongyu789.top/Article/details/gtzdbjusve.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gtjngpmdom.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjsmydje.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.sufxvd.cn/Article/details/gtgcltgcsd.html

C#:   1234567.ToString("N0")
来源：http://dali.nanxinkj.top/Article/details/gtopugyeoo.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gtdjuskzio.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhongyouzk.top/Article/details/gtskwgasoz.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zycfv.cn/Article/details/gtnbzgjowe.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtnztotlhf.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtvitaetys.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gtaubpihft.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhijiandao.cn/Article/details/gtyxqaljlz.html

Ruby: s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gtkzuxvvgb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.svipenyu.cn/Article/details/gtwjujmqie.html

[E18] 模板占位符替换
来源：http://dali.xinyue.icu/Article/details/gtqdtirigz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.xylfe.cn/Article/details/gtoocstywk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yuxming.cn/Article/details/gtsmolyzjh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gtmsbtckli.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtbplzbgak.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.hnxiangtu.top/Article/details/gtxlanjtpa.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gtqdqhlmwk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ydzc1.top/Article/details/gteegepjgg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jiagoushi.top/Article/details/gtliagbobb.html

[E19] 多行文本按行拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqbisdrs.html

Py:   s.splitlines()
来源：http://dali.gotoacloud.top/Article/details/gtxbfuacue.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gthcnbicvg.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhixingplan.top/Article/details/gthfsgkoyv.html

TS:   s.split(/\r?\n/)
来源：http://dali.hysaishi.cn/Article/details/gtklsmuieo.html

Java: s.lines().toList()
来源：http://dali.gzhubu.top/Article/details/gtzycsveqk.html

Go:   strings.Split(s, "\n")
来源：http://dali.guowangkeji.top/Article/details/gtpshvgmex.html

Ruby: s.lines
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpidyafcg.html

C#:   s.Split('\n')
来源：http://dali.yj20258.top/Article/details/gtoswhhjef.html

[E20] 判断字符串是否为空
来源：http://dali.jianghu66.top/Article/details/gtqflacwjs.html

Py:   if not s:
来源：http://dali.ivvv.top/Article/details/gttutvfauu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.wangshuangyany.cn/Article/details/gtzbhcriph.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtzrlbywsk.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gtcubnunwe.html

Java: if (s.isEmpty()) {}
来源：http://dali.ydzc1.top/Article/details/gthaztwnfe.html

Go:   if s == "" {}
来源：http://dali.cucudq.cn/Article/details/gtvgwzndxw.html

Ruby: if s.empty?
来源：http://dali.xziqi.cn/Article/details/gtmfuljbjh.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhengqikj.top/Article/details/gtqnxoffuk.html

[E21] 超长截断加省略号
来源：http://dali.dianchejie.cn/Article/details/gtjluyonnf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jyoumei.cn/Article/details/gtomlbpbqi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtuoupdadl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.wangdashe.top/Article/details/gtmlxejgnp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtgjqyqtpu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtblvgftxc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shzxlz.cn/Article/details/gtuljkwsck.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtxgodhuxg.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xuanzx.com/Article/details/gtpvqnfvxe.html

[E22] 字节长度与字符长度
来源：http://dali.jyoumei.cn/Article/details/gtmazbceyb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gogol.net.cn/Article/details/gtodrqiwzz.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gtkdzneshb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gtfnmwtinf.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhijiandao.cn/Article/details/gtsfgiexyy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwymezor.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gtotkajwgu.html

Ruby: s.bytesize;  s.length
来源：http://dali.aibaodan.cn/Article/details/gtvsphlqlx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtcinjvzbw.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtyofmeumm.html

F. 文件与目录
来源：http://dali.redwolf501.top/Article/details/gtlyrvelkc.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtfvfbrwlv.html

[F01] 读取整个文件
来源：http://dali.hysaishi.cn/Article/details/gtmaghgvxn.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cucudq.cn/Article/details/gtmbpgzmvz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.daria6918.cn/Article/details/gtesjkrhry.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jianghu66.top/Article/details/gtclipbzrr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtacpjgeal.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtcnevqmaj.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhoulong.xyz/Article/details/gtcbpimzys.html

Ruby: File.read("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtuqexwzii.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.sufxvd.cn/Article/details/gtileflheu.html

[F02] 逐行读取文件
来源：http://dali.xuetiantiany.cn/Article/details/gtnprqfyrg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.wangdashe.top/Article/details/gtnnkzihav.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jyoumei.cn/Article/details/gtrmgbwfql.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtkljvrhmj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwirdewy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daria6918.cn/Article/details/gtlyikrytx.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.xinyue.icu/Article/details/gtpilsiuyk.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsugkvgcf.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.bjfxy.top/Article/details/gtdlkwmghk.html

[F03] 写入文件（覆盖）
来源：http://dali.yuxming.cn/Article/details/gtncwinjvz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.9152youxi.cn/Article/details/gtxraksoxb.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gtjxgvqhid.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomlsuhvr.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtmceewwjl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.mhx1999.top/Article/details/gtoawymezo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhengqikj.top/Article/details/gtzztochoa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yj202588.top/Article/details/gtbjkowycp.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gtdhwdtsxl.html

[F04] 追加写入文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuhfcpsx.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gtnkepaknu.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhoulong.xyz/Article/details/gtqcczhmus.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gogol.net.cn/Article/details/gttmzkedyl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.316326.xyz/Article/details/gtqobdaevb.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cheryme.top/Article/details/gtooixrzes.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zdqjudy.top/Article/details/gtdjvbhqca.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.c1oappe.top/Article/details/gtltyzaghv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.vqdsnc.cn/Article/details/gtqenofrdi.html

[F05] 判断文件或目录是否存在
来源：http://dali.shzxlz.cn/Article/details/gtnenmlxqz.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.tanke756.top/Article/details/gtcedoouca.html

PHP:  file_exists("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtyzvfdxrq.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtqcvbmdxq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfffwvepj.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtgjcpwcbn.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hongshengwenyu.top/Article/details/gtqhycjqck.html

Ruby: File.exist?("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtqvsqpecd.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtipijfnvf.html

[F06] 删除文件
来源：http://dali.tianlin.xyz/Article/details/gtnzhfjpqv.html

Py:   os.remove("a.txt")
来源：http://dali.meibo888.top/Article/details/gtjkmixkts.html

PHP:  unlink("a.txt");
来源：http://dali.cashguo.top/Article/details/gtxgzrdngx.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtuxlbbdvj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjvyntpn.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtzigedtle.html

Go:   os.Remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtoiqmiizv.html

Ruby: File.delete("a.txt")
来源：http://dali.shuidangran.top/Article/details/gtpcujtoma.html

C#:   File.Delete("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gtbmjmkyrb.html

[F07] 创建目录（含多级）
来源：http://dali.xuetiantiany.cn/Article/details/gteahrgubo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhengqikj.top/Article/details/gtmzxmocyl.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hongshengwenyu.top/Article/details/gtytudcizb.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shzxlz.cn/Article/details/gtfkxxvpnh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gtgouydqjv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gtmhlshbev.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.pycfn.com/Article/details/gttqkqxyeg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.havefunace.top/Article/details/gtuanipoxx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guowangkeji.top/Article/details/gtghvovgaw.html

[F08] 遍历目录
来源：http://dali.jinqigfzy.top/Article/details/gtkqbeshgi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daxiang520.top/Article/details/gtswmlubhq.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.daria6918.cn/Article/details/gtspcddxzi.html

JS:   fs.readdirSync("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtqtjllzfb.html

TS:   fs.readdirSync("dir")
来源：http://dali.ydzc1.top/Article/details/gtgzlohdtg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtbcwsdigp.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gaohongyu789.top/Article/details/gtkyxgavxe.html

Ruby: Dir.children("dir")
来源：http://dali.zhongyouzk.top/Article/details/gtvudulggi.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinqigufen.top/Article/details/gtafijcmed.html

[F09] 获取文件大小
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyuwddnrf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtsqvnhxyn.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtxdxjivrb.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtqyazdplx.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shzxlz.cn/Article/details/gtucjqjkrk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sysykeji.top/Article/details/gtufdpdyul.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ydzc1.top/Article/details/gtypizaftw.html

Ruby: File.size("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtyaivpfoh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cucudq.cn/Article/details/gtkgxwgfqf.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xinyue.icu/Article/details/gtjgabegwx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtvxihjpla.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.nanxinkj.top/Article/details/gtzbvticjs.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gtvcavekzm.html

TS:   path.extname("a.txt")
来源：http://dali.ybcxt.top/Article/details/gthnrtxqxr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xuetiantiany.cn/Article/details/gtcrongofo.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtjpexxfvs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gtxsspxskf.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtazunvjxf.html

[F11] 复制与移动文件
来源：http://dali.hysaishi.cn/Article/details/gtenvcjbqg.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gtfbbzxscd.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yongpay.top/Article/details/gtkwpgnpxt.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.gotoacloud.top/Article/details/gtzgodbnpe.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtiuarpbnq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258.top/Article/details/gtbyyohxpc.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gttywxtmuk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtqqmomxvu.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.havefunace.top/Article/details/gtlbykfkhg.html

[F12] CSV 读写
来源：http://dali.yj20258.top/Article/details/gtlttidpbe.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gtyqnycwmi.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.meibo888.top/Article/details/gtdynrxugx.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.ydzc1.top/Article/details/gtbpchsqrm.html

TS:   // 同上
来源：http://dali.gaohongyu789.top/Article/details/gtlgjlymav.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.cqqwz.cn/Article/details/gtgqorktif.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.xuanzx.com/Article/details/gtftmosqhx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.shanyushiyangtech.top/Article/details/gtmlksdehq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnqzz.top/Article/details/gtllftnvjb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtbenloayy.html

G. 面向对象
来源：http://dali.nanxuanxn.top/Article/details/gtftqwjemg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtoqtiilij.html

[G01] 定义类
来源：http://dali.yvedp.cn/Article/details/gtehipyiyn.html

Py:   class User: pass
来源：http://dali.hywenlv.cn/Article/details/gtngoidchu.html

PHP:  class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtnmyuvujy.html

JS:   class User {}
来源：http://dali.gaohongyu789.top/Article/details/gtesiqauaw.html

TS:   class User { name: string = ""; }
来源：http://dali.ivvv.top/Article/details/gtfmtiucuy.html

Java: class User {}
来源：http://dali.gogol.net.cn/Article/details/gtnofrkpyo.html

Go:   type User struct { Name string }
来源：http://dali.jlsjyb.cn/Article/details/gtbfkfydyl.html

Ruby: class User; end
来源：http://dali.cashguo.top/Article/details/gtzcvpsjnw.html

C#:   class User {}
来源：http://dali.yueranfly.top/Article/details/gtfcakhdbh.html

[G02] 构造函数
来源：http://dali.zdqjudy.top/Article/details/gttdmzqiyv.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.chenlongwang.top/Article/details/gtqmkyudcx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfiugudee.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhengqikj.top/Article/details/gtxqebzhzp.html

TS:   constructor(public name: string) {}
来源：http://dali.nanxuanxn.top/Article/details/gtsseklyzh.html

Java: User(String name) { this.name = name; }
来源：http://dali.nanxinkj.top/Article/details/gtmeyklwpa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.redwolf501.top/Article/details/gtluwycrvh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdoiagszi.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtjztqfgsu.html

[G03] 实例属性
来源：http://dali.cheryme.top/Article/details/gtmivkrinl.html

Py:   self.name = "x"
来源：http://dali.hammf.cn/Article/details/gthuekoifa.html

PHP:  public string $name = "x";
来源：http://dali.bjfxy.top/Article/details/gtcihrdvrc.html

JS:   this.name = "x";
来源：http://dali.chenzaomai.com/Article/details/gtgcjdleld.html

TS:   name: string = "x";
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzznnvaz.html

Java: private String name;
来源：http://dali.fzhhl.top/Article/details/gtuxmwsfxv.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.andypj.xyz/Article/details/gtlaqaxbqr.html

Ruby: @name = "x"
来源：http://dali.tianlin.xyz/Article/details/gtazylwops.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.0kj1m.cn/Article/details/gttfueihvz.html

[G04] 定义方法
来源：http://dali.ybcxt.top/Article/details/gtvnwakfwq.html

Py:   def greet(self): return self.name
来源：http://dali.jqgfzy.top/Article/details/gtyuuiibcs.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.daria6918.cn/Article/details/gtnfhtcenj.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtalebjnxw.html

TS:   greet(): string { return this.name; }
来源：http://dali.iojbl.cn/Article/details/gtolyapycq.html

Java: String greet() { return name; }
来源：http://dali.tanke756.top/Article/details/gtyxvlrall.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.hnxiangtu.top/Article/details/gtblddmggy.html

Ruby: def greet; @name; end
来源：http://dali.pycfn.com/Article/details/gthlgagler.html

C#:   public string Greet() => Name;
来源：http://dali.guowangkeji.top/Article/details/gtdqcrlzzw.html

[G05] 继承
来源：http://dali.ybcxt.top/Article/details/gtmexsrpsj.html

Py:   class Admin(User): pass
来源：http://dali.snrcjt.cn/Article/details/gtflqeoumm.html

PHP:  class Admin extends User {}
来源：http://dali.tanke756.top/Article/details/gtjzeknxdw.html

JS:   class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gtndtxzwem.html

TS:   class Admin extends User {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsfisjew.html

Java: class Admin extends User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwyiqpfb.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpixfzqk.html

Ruby: class Admin < User; end
来源：http://dali.bjfxy.top/Article/details/gtaauoytpn.html

C#:   class Admin : User {}
来源：http://dali.aizwys.cn/Article/details/gtcmnacbdv.html

[G06] 重写方法
来源：http://dali.yvedp.cn/Article/details/gtxymwklwy.html

Py:   def greet(self): return "admin"
来源：http://dali.shzxlz.cn/Article/details/gtsfkcjaad.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvevciura.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtfvvosfxa.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hnxiangtu.top/Article/details/gtcwewpetp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pycfn.com/Article/details/gtzdqpyvlz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.nwbrower.top/Article/details/gtcczxaahr.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgufenzy.top/Article/details/gtpqrficow.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gtqcytxyir.html

[G07] 调用父类方法
来源：http://dali.cashguo.top/Article/details/gtneppivdb.html

Py:   super().greet()
来源：http://dali.zhoulong.xyz/Article/details/gtctfrrxmb.html

PHP:  parent::greet();
来源：http://dali.andypj.xyz/Article/details/gthgbladft.html

JS:   super.greet();
来源：http://dali.sxryk.cn/Article/details/gttqjaosjn.html

TS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gtjxidnshj.html

Java: super.greet();
来源：http://dali.jinghuilouyu.cn/Article/details/gtldexaxtg.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.cheryme.top/Article/details/gtwrxpkrtw.html

Ruby: super
来源：http://dali.xinyue.icu/Article/details/gtookzptzd.html

C#:   base.Greet();
来源：http://dali.ybcxt.top/Article/details/gtsmyanwse.html

[G08] 静态方法与属性
来源：http://dali.cdnleiting.top/Article/details/gttkjhmdsz.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.cashguo.top/Article/details/gtcpntgunr.html

PHP:  public static function f() {}
来源：http://dali.meibo888.top/Article/details/gtulsoyuvv.html

JS:   static f() {}
来源：http://dali.gaohongyu789.top/Article/details/gtibiujpgt.html

TS:   static f(): void {}
来源：http://dali.yj20258.top/Article/details/gtzlngfetw.html

Java: static void f() {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnzcbeipc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hnqzz.top/Article/details/gthkjebjup.html

Ruby: def self.f; end
来源：http://dali.xuetiantiany.cn/Article/details/gtefjgfqnc.html

C#:   public static void F() {}
来源：http://dali.fzhhl.top/Article/details/gtnngylmcb.html

[G09] 接口 / 抽象类
来源：http://dali.ehwqpu.com/Article/details/gtndmttden.html


<!-- 参考信息 -->