代发 wailian999

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnxiangtu.top/Article/details/gtnzjcguss.html

TS:   s.split(",")
来源：http://dali.yvedp.cn/Article/details/gtyjieibiw.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.zhiwuduotai.top/Article/details/gtjwdpipeg.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jiagoushi.top/Article/details/gtozcfuwet.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigufen.top/Article/details/gtvjvpsnyp.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fengsongda.top/Article/details/gtjowkcrak.html

[E08] 数组按分隔符合并
来源：http://dali.smart0.xyz/Article/details/gtjttisbmm.html

Py:   ",".join(items)
来源：http://dali.ydzc1.top/Article/details/gtjrrmtjql.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gtsuzgtkaz.html

JS:   items.join(",")
来源：http://dali.zhongyouzk.top/Article/details/gtdibvmrhx.html

TS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtsxdlucna.html

Java: String.join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gttxqgazzy.html

Go:   strings.Join(items, ",")
来源：http://dali.aizwys.cn/Article/details/gtqdlszflk.html

Ruby: items.join(",")
来源：http://dali.gotoacloud.top/Article/details/gtranqrwok.html

C#:   string.Join(",", items)
来源：http://dali.hfpthk.cn/Article/details/gtxzsfclaf.html

[E09] 去除所有空白字符
来源：http://dali.mhx1999.top/Article/details/gtwqxlkrxr.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jlsjyb.cn/Article/details/gtwsfzzayb.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.smart0.xyz/Article/details/gtuwhonlct.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gtdtvbntmb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tanke756.top/Article/details/gtlpknzleg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cashguo.top/Article/details/gtlgamnbzk.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gotoacloud.top/Article/details/gtpmcfpiqq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.snrcjt.cn/Article/details/gtguvadtaq.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gtdruivqhj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.vqdsnc.cn/Article/details/gtcjstadwf.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhijiandao.cn/Article/details/gthwudwuwm.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jinqigfzy.top/Article/details/gtotkiakqg.html

JS:   "7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtfnarmezs.html

TS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtqpjcjzzs.html

Java: String.format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtosxukoop.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtqxnlbuay.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjshigvqn.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbkzpjqn.html

[E11] 反转字符串
来源：http://dali.xinyue.icu/Article/details/gtbhbarydm.html

Py:   s[::-1]
来源：http://dali.cqqwz.cn/Article/details/gtdtmaeazd.html

PHP:  strrev($s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttjuqxigp.html

JS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gtlyhjynua.html

TS:   [...s].reverse().join("")
来源：http://dali.jiagoushi.top/Article/details/gtdhphighb.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gtwacrxdtg.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gthdzkggbh.html

Ruby: s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvnvghvo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsmuxzwo.html

[E12] 统计某字符出现次数
来源：http://dali.xuanzx.com/Article/details/gtzkcdojcw.html

Py:   s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfuglpbv.html

PHP:  substr_count($s, "a");
来源：http://dali.shangyingyoupin.top/Article/details/gtbbcbzufh.html

JS:   s.split("a").length - 1
来源：http://dali.yj20258888.top/Article/details/gthlaszlsd.html

TS:   s.split("a").length - 1
来源：http://dali.shzxlz.cn/Article/details/gturizsgml.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnxiangtu.top/Article/details/gtgntbdhlj.html

Go:   strings.Count(s, "a")
来源：http://dali.ppjwa.cn/Article/details/gtfjsyweqh.html

Ruby: s.count("a")
来源：http://dali.jinqigufen.top/Article/details/gtaixznogp.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xinyue.icu/Article/details/gtpgvoxpit.html

[E13] 逐字符遍历
来源：http://dali.andypj.xyz/Article/details/gtbwsyjtjr.html

Py:   for ch in s: print(ch)
来源：http://dali.yj20258.top/Article/details/gtvxfvvdgb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aibaodan.cn/Article/details/gttwhpylkd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtuydlxler.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.svipenyu.cn/Article/details/gtnjlzwwcm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtdgirqcdl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuanzx.com/Article/details/gtyjcehfat.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenjidiqi.icu/Article/details/gtyzfvdvpq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtvryoreln.html

[E14] URL 编码与 Base64
来源：http://dali.nwbrower.top/Article/details/gtcqpzucrn.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtnxmsrvqn.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gtbbrgpsvk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hysaishi.cn/Article/details/gtozuugedx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cucudq.cn/Article/details/gtxyxthvol.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj202588.top/Article/details/gtgsmigkyn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.quarkkingdee.top/Article/details/gtwpnfnewq.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cheryme.top/Article/details/gtapavuelk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.c1oappe.top/Article/details/gtxchqqmev.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gtdhamhwwl.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.hfpthk.cn/Article/details/gtnvekbecg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shuidangran.top/Article/details/gtiexwbruy.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtgtglhuyc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hfpthk.cn/Article/details/gtazzfnzti.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gtvxnxbujq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yvedp.cn/Article/details/gtxjxxwvbi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gticnwhvoe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.aizwys.cn/Article/details/gtqaikowyy.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gtbyfxphmu.html

Py:   f"{1234567:,}"
来源：http://dali.shuidangran.top/Article/details/gtsmhwmjsx.html

PHP:  number_format(1234567);
来源：http://dali.quarkkingdee.top/Article/details/gtbtdqvdug.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gtizzlatbn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.wangshuangyany.cn/Article/details/gtjzrdqyum.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gotoacloud.top/Article/details/gtozwpiwlt.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.fzhhl.top/Article/details/gtpwcwdsap.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbahkndc.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gtwzghlzoe.html

[E17] 首字母大写
来源：http://dali.yj20258.top/Article/details/gtkzrebjwr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cashguo.top/Article/details/gtfmjqxrwx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtqvsketsj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gtualqawhp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtllqhpnmd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ehwqpu.com/Article/details/gtuiixzqsi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.cheryme.top/Article/details/gtimolkaui.html

Ruby: s.capitalize
来源：http://dali.guannengcc.top/Article/details/gtmmmknvhe.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yonumen.top/Article/details/gtxfhwjgcy.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttausnurj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ivvv.top/Article/details/gtdiryiqrt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhoulong.xyz/Article/details/gtqcxlhtpz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.birdmap.top/Article/details/gttvpxgijh.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gtapzxlidk.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtbqguvmqv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtwjdejdce.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.fengsongda.top/Article/details/gtxrunrjlh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gtjsxbshha.html

[E19] 多行文本按行拆分
来源：http://dali.zhoulong.xyz/Article/details/gtwalsllkn.html

Py:   s.splitlines()
来源：http://dali.snrcjt.cn/Article/details/gthsvdmxff.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gtabpsgtuh.html

JS:   s.split(/\r?\n/)
来源：http://dali.daria6918.cn/Article/details/gtuvhhxdya.html

TS:   s.split(/\r?\n/)
来源：http://dali.jiagoushi.top/Article/details/gtkzgxhmqc.html

Java: s.lines().toList()
来源：http://dali.aibaodan.cn/Article/details/gtofampron.html

Go:   strings.Split(s, "\n")
来源：http://dali.yonumen.top/Article/details/gtscxgrtho.html

Ruby: s.lines
来源：http://dali.daria6918.cn/Article/details/gtbxkryagl.html

C#:   s.Split('\n')
来源：http://dali.wangdashe.top/Article/details/gtbntelvoz.html

[E20] 判断字符串是否为空
来源：http://dali.aizwys.cn/Article/details/gtmueinnyj.html

Py:   if not s:
来源：http://dali.yvedp.cn/Article/details/gtdyovbqam.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tianlin.xyz/Article/details/gtslahegte.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jqgufenzy.top/Article/details/gtfzhaeyam.html

TS:   if (s === "") {}
来源：http://dali.pycfn.com/Article/details/gtwefmmsdk.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhengqikj.top/Article/details/gtxoudgrzo.html

Go:   if s == "" {}
来源：http://dali.aizwys.cn/Article/details/gtwmflwsay.html

Ruby: if s.empty?
来源：http://dali.jinqigufen.top/Article/details/gtqkeuxpko.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ehwqpu.com/Article/details/gtumfjmoty.html

[E21] 超长截断加省略号
来源：http://dali.chenlongwang.top/Article/details/gtrymfetnz.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhengqikj.top/Article/details/gtvbuszsvo.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hammf.cn/Article/details/gtuyhhitgf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gttncqhzvh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtsgvvegay.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtgndyfqek.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shanyushiyangtech.top/Article/details/gtbapotwcm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.birdmap.top/Article/details/gtghhadbfi.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtbrefjgcb.html

[E22] 字节长度与字符长度
来源：http://dali.vqdsnc.cn/Article/details/gtftykyngg.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.birdmap.top/Article/details/gtwnakztcr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexjzpdbg.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.birdmap.top/Article/details/gtshepjpve.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cqqwz.cn/Article/details/gtfctapypz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jlsjyb.cn/Article/details/gtasznmmgj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jqgfzy.top/Article/details/gtdmngnoch.html

Ruby: s.bytesize;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gtsjyejrzm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.birdmap.top/Article/details/gtjdgolxxx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlefaexvl.html

F. 文件与目录
来源：http://dali.chenzaomai.com/Article/details/gtbpyapfce.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtjkcddrzl.html

[F01] 读取整个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtjxwxkqtk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.smart0.xyz/Article/details/gttzdhnllk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yj20258888.top/Article/details/gtyuspfhgj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guowangkeji.top/Article/details/gtavenduhr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yueranfly.top/Article/details/gtfrcxvmbd.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhengqikj.top/Article/details/gtisrrazhg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.mhx1999.top/Article/details/gtkqcgctfv.html

Ruby: File.read("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslvmwpnp.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yuxming.cn/Article/details/gttcrbwbpj.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gtgqxccfyb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jlsjyb.cn/Article/details/gtgbvavpdv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.nanxinkj.top/Article/details/gtxuqybggg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ydzc1.top/Article/details/gtukihkbio.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gtxizccaih.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.dianchejie.cn/Article/details/gtdelmdrua.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.kuanghao11.cn/Article/details/gtdpqjxane.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhiwuduotai.top/Article/details/gtsegwjyde.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xinyue.icu/Article/details/gtzzrwpstj.html

[F03] 写入文件（覆盖）
来源：http://dali.vqdsnc.cn/Article/details/gtyzrvypxt.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.pycfn.com/Article/details/gtmjykacxv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtrhlmucrd.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yj20258.top/Article/details/gtkcppkbvv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtdlyabbea.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tanke756.top/Article/details/gtxqkzunqo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gtfdckuudz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.kuanghao11.cn/Article/details/gtuunieyoe.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtjldpatxx.html

[F04] 追加写入文件
来源：http://dali.zhongyouzk.top/Article/details/gtlnuhkxmp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cashguo.top/Article/details/gtomhwtllf.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.nanxuanxn.top/Article/details/gtdohqvnqh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gotoacloud.top/Article/details/gttzeobsgu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.birdmap.top/Article/details/gtvxlauqub.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gotoacloud.top/Article/details/gtwwebuakm.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigufen.top/Article/details/gtrybdlenx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.tianlin.xyz/Article/details/gtgvppbuhr.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cashguo.top/Article/details/gtlhkklnye.html

[F05] 判断文件或目录是否存在
来源：http://dali.sufxvd.cn/Article/details/gtoecwjcne.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.redwolf501.top/Article/details/gttysjcdit.html

PHP:  file_exists("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtuigktiii.html

JS:   fs.existsSync("a.txt")
来源：http://dali.meibo888.top/Article/details/gtwekiuscq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtqnnmvjly.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtrijtqwxc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zdqjudy.top/Article/details/gtnojnbxdt.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtkbbldywu.html

C#:   File.Exists("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtauhaonsk.html

[F06] 删除文件
来源：http://dali.daxiang520.top/Article/details/gtnarcwgbd.html

Py:   os.remove("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtqzjbeivz.html

PHP:  unlink("a.txt");
来源：http://dali.dashuyun.cn/Article/details/gtpasixjij.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtfkngaxfj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gthnoumxpj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtbtutqghu.html

Go:   os.Remove("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtyskuxnzy.html

Ruby: File.delete("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtkvmvlabe.html

C#:   File.Delete("a.txt");
来源：http://dali.hammf.cn/Article/details/gtgcmwwlqy.html

[F07] 创建目录（含多级）
来源：http://dali.hnqzz.top/Article/details/gtunyjrfoo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.birdmap.top/Article/details/gtnnxqbwhw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nwbrower.top/Article/details/gtlsyqhpns.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shanyushiyangtech.top/Article/details/gtfoyilmdb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zycfv.cn/Article/details/gtmbqqwozs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sysykeji.top/Article/details/gtqxbajjkg.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.xuetiantiany.cn/Article/details/gtwurkzbev.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.havefunace.top/Article/details/gtcyzyijwf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.c1oappe.top/Article/details/gtdzeicshx.html

[F08] 遍历目录
来源：http://dali.yuanzhike.top/Article/details/gtbtlqsuoj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.hongshengwenyu.top/Article/details/gtrcabybbc.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyehonron.html

JS:   fs.readdirSync("dir")
来源：http://dali.yvedp.cn/Article/details/gtagdxdula.html

TS:   fs.readdirSync("dir")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqjfpmts.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gtoytkxqly.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabgokwbr.html

Ruby: Dir.children("dir")
来源：http://dali.xylfe.cn/Article/details/gtodgkbjmy.html

C#:   Directory.GetFiles("dir")
来源：http://dali.haohaochexian.top/Article/details/gtuwyssbvt.html

[F09] 获取文件大小
来源：http://dali.yangfankeji.com/Article/details/gtyrgkppnb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtyrfiklln.html

PHP:  filesize("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlhtdffn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gtryngilvk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.c1oappe.top/Article/details/gtknnvsxqu.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtjwapygcm.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.quarkkingdee.top/Article/details/gtubshmpfh.html

Ruby: File.size("a.txt")
来源：http://dali.ivvv.top/Article/details/gtiwbskgfj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gtqeeizjtg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gtwelbnwsx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtygvxeapt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtikzpuqwi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtytikaubn.html

TS:   path.extname("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtgszgvpom.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdjvnfvh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtvdivgqdd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtfamnnwci.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtdypueptj.html

[F11] 复制与移动文件
来源：http://dali.aizwys.cn/Article/details/gtzkzlidxw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.havefunace.top/Article/details/gtkqoelheb.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gtpzmdxwpa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtiqxcetin.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtvpyjgkbj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.aibaodan.cn/Article/details/gtrbumockp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdwugzvs.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gtgdlsjjxl.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258888.top/Article/details/gtlskkmvhp.html

[F12] CSV 读写
来源：http://dali.gogol.net.cn/Article/details/gttnlkyqyi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.meibo888.top/Article/details/gtvbgdowvr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gtvxegiqac.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.svipenyu.cn/Article/details/gtrdewbalk.html

TS:   // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtvtsuniii.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.yangfankeji.com/Article/details/gtprunpbov.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yj20258.top/Article/details/gtgeefouyl.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.gaohongyu789.top/Article/details/gtvfmjvwls.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sysykeji.top/Article/details/gtagspalzc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtevwvasyx.html

G. 面向对象
来源：http://dali.pengpengdd.cyou/Article/details/gtdsqwgres.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtwbfrdauf.html

[G01] 定义类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjitplxx.html

Py:   class User: pass
来源：http://dali.c1oappe.top/Article/details/gtqtpogbpo.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gtygajjdvw.html

JS:   class User {}
来源：http://dali.dashuyun.cn/Article/details/gtybnlixfo.html

TS:   class User { name: string = ""; }
来源：http://dali.0kj1m.cn/Article/details/gtvanajwtd.html

Java: class User {}
来源：http://dali.nwbrower.top/Article/details/gtvrrijjeo.html

Go:   type User struct { Name string }
来源：http://dali.fengsongda.top/Article/details/gtdndtqzfr.html

Ruby: class User; end
来源：http://dali.cdnleiting.top/Article/details/gtaaxrvcnp.html

C#:   class User {}
来源：http://dali.sufxvd.cn/Article/details/gtjrztfpdj.html

[G02] 构造函数
来源：http://dali.jqgfzy.top/Article/details/gtavlkhmka.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.mhx1999.top/Article/details/gtwlgwzgfd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gtzvyzekas.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gtixincjru.html

TS:   constructor(public name: string) {}
来源：http://dali.fengsongda.top/Article/details/gtibfhxmti.html

Java: User(String name) { this.name = name; }
来源：http://dali.jqgfzy.top/Article/details/gtieddkmhy.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hongshengwenyu.top/Article/details/gtamglgznd.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xylfe.cn/Article/details/gtmwedywgq.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gtupwbqlct.html

[G03] 实例属性
来源：http://dali.sufxvd.cn/Article/details/gtknvheyib.html

Py:   self.name = "x"
来源：http://dali.hywenlv.cn/Article/details/gtjnsymwvt.html

PHP:  public string $name = "x";
来源：http://dali.hnqzz.top/Article/details/gtxicghpqa.html

JS:   this.name = "x";
来源：http://dali.zhiwuduotai.top/Article/details/gtfkuqzkol.html

TS:   name: string = "x";
来源：http://dali.quarkkingdee.top/Article/details/gtudlmayet.html

Java: private String name;
来源：http://dali.sysykeji.top/Article/details/gtxlprifuk.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.andypj.xyz/Article/details/gtlafdhviz.html

Ruby: @name = "x"
来源：http://dali.hammf.cn/Article/details/gtnlpsjxwj.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtqejcnf.html

[G04] 定义方法
来源：http://dali.yongpay.top/Article/details/gtnxgmjcba.html

Py:   def greet(self): return self.name
来源：http://dali.hywenlv.cn/Article/details/gtsfqyqpnl.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.pycfn.com/Article/details/gtwxddqdvx.html

JS:   greet() { return this.name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsblxxefl.html

TS:   greet(): string { return this.name; }
来源：http://dali.redwolf501.top/Article/details/gtnvcouxdt.html

Java: String greet() { return name; }
来源：http://dali.ivvv.top/Article/details/gtsrvuizmo.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ehwqpu.com/Article/details/gtcrppsvnp.html

Ruby: def greet; @name; end
来源：http://dali.xziqi.cn/Article/details/gtrgkgwtdz.html

C#:   public string Greet() => Name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoazcnpel.html

[G05] 继承
来源：http://dali.zhengqikj.top/Article/details/gtuulizcgk.html

Py:   class Admin(User): pass
来源：http://dali.hysaishi.cn/Article/details/gtsoyrgnzv.html

PHP:  class Admin extends User {}
来源：http://dali.mhx1999.top/Article/details/gtlheywzpm.html

JS:   class Admin extends User {}
来源：http://dali.yanxiufei.cn/Article/details/gtfkznkwdn.html

TS:   class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gthevsidku.html

Java: class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gteznpamxw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptwdkrqp.html

Ruby: class Admin < User; end
来源：http://dali.hongshengwenyu.top/Article/details/gtzjlkrjta.html

C#:   class Admin : User {}
来源：http://dali.ybcxt.top/Article/details/gthcuobjcz.html


<!-- 参考信息 -->