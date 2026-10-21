代发 wailian999

Go:   strings.Index(s, "x")
来源：http://dali.dianchejie.cn/Article/details/gtykadpywt.html

Ruby: s.index("x")
来源：http://dali.vqdsnc.cn/Article/details/gtokjyshrx.html

C#:   s.IndexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtflltyshj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.yj202588.top/Article/details/gtmpgopipd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fzhhl.top/Article/details/gtjmytpgik.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.andypj.xyz/Article/details/gtprggpzls.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtgkqrxkko.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gtxuodbvvj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtwzydoipl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.wangdashe.top/Article/details/gtcncowhwt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xylfe.cn/Article/details/gtpkrhrwvs.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.guowangkeji.top/Article/details/gtjumznfge.html

[E06] 替换子串
来源：http://dali.guannengcc.top/Article/details/gthxzeixgl.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtemykxwlj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.tanke756.top/Article/details/gtdaaylelv.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtzleuuvqv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gtbibaqayd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtrgpwyfyx.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gtzqxmqbqu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hfpthk.cn/Article/details/gtlekmkviw.html

C#:   s.Replace("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtcsjaohqq.html

[E07] 按分隔符拆分
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafhmafmg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daria6918.cn/Article/details/gtvlfdxfdj.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.redwolf501.top/Article/details/gtoenfnnxz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.feifeiyinyue.top/Article/details/gtxwmymaqi.html

TS:   s.split(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtpagpvmpn.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shangyingyoupin.top/Article/details/gtgnaezvig.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.c1oappe.top/Article/details/gtyllrfyfm.html

Ruby: s.split(",");  s.split
来源：http://dali.pengpengdd.cyou/Article/details/gtrqxhdave.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgufenzy.top/Article/details/gteextmydg.html

[E08] 数组按分隔符合并
来源：http://dali.yueranfly.top/Article/details/gttkroefbx.html

Py:   ",".join(items)
来源：http://dali.hongshengwenyu.top/Article/details/gtasurigdp.html

PHP:  implode(",", $items);
来源：http://dali.zdqjudy.top/Article/details/gtwklqmftr.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gtzzdmxvew.html

TS:   items.join(",")
来源：http://dali.svipenyu.cn/Article/details/gtxhsjxbzf.html

Java: String.join(",", items)
来源：http://dali.redwolf501.top/Article/details/gtzyehysps.html

Go:   strings.Join(items, ",")
来源：http://dali.gogol.net.cn/Article/details/gtunhkbjys.html

Ruby: items.join(",")
来源：http://dali.guowangkeji.top/Article/details/gtgksrirxa.html

C#:   string.Join(",", items)
来源：http://dali.yj202588.top/Article/details/gtinbeaael.html

[E09] 去除所有空白字符
来源：http://dali.smart0.xyz/Article/details/gtxpudlrbl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.xziqi.cn/Article/details/gtzstxanck.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.pycfn.com/Article/details/gtqzblcolz.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtqolprjhs.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gtbgxdgwqg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.meibo888.top/Article/details/gtpcusicwx.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hammf.cn/Article/details/gtpzwegvfl.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gtnpxxygts.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gtoggjbmea.html

[E10] 左侧补零 / 定长填充
来源：http://dali.wangshuangyany.cn/Article/details/gtdxjythbn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtjcbwpjrx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.quarkkingdee.top/Article/details/gtllizshmx.html

JS:   "7".padStart(3, "0")
来源：http://dali.xylfe.cn/Article/details/gtscmkxfqz.html

TS:   "7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtrhuwkuxh.html

Java: String.format("%03d", 7)
来源：http://dali.cheryme.top/Article/details/gthlwfzbjj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtubzvlhqw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.havefunace.top/Article/details/gtdhjfhuyp.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenlongwang.top/Article/details/gttjzcptqe.html

[E11] 反转字符串
来源：http://dali.hysaishi.cn/Article/details/gttatmoami.html

Py:   s[::-1]
来源：http://dali.bjfxy.top/Article/details/gtrvklpxsi.html

PHP:  strrev($s);
来源：http://dali.fzhhl.top/Article/details/gtikmhvpsf.html

JS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtmjbzpxfy.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258888.top/Article/details/gtrgfmkfdl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jiagoushi.top/Article/details/gtmyqndisy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtjoiiccpk.html

Ruby: s.reverse
来源：http://dali.hnqzz.top/Article/details/gtcjncucuf.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zdqjudy.top/Article/details/gtoldsoxon.html

[E12] 统计某字符出现次数
来源：http://dali.sysykeji.top/Article/details/gtjwcivors.html

Py:   s.count("a")
来源：http://dali.bjfxy.top/Article/details/gtxftvrpbs.html

PHP:  substr_count($s, "a");
来源：http://dali.hfpthk.cn/Article/details/gtrubwnlhn.html

JS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gtdecfyqyq.html

TS:   s.split("a").length - 1
来源：http://dali.pycfn.com/Article/details/gteudxjuqw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.gogol.net.cn/Article/details/gtvkpeltkf.html

Go:   strings.Count(s, "a")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzalafza.html

Ruby: s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtcqrxhjqs.html

C#:   s.Count(c => c == 'a')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtooqbpdjp.html

[E13] 逐字符遍历
来源：http://dali.jianghu66.top/Article/details/gtzffuskno.html

Py:   for ch in s: print(ch)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuseoccaw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhixingplan.top/Article/details/gtkcemkohd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejcigost.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtiiskhxqo.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.c1oappe.top/Article/details/gtpfqxjszi.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenzaomai.com/Article/details/gtrngxrqyj.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zycfv.cn/Article/details/gtvbcxrudn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtoyvhuzox.html

[E14] URL 编码与 Base64
来源：http://dali.zhixingplan.top/Article/details/gtnwmppkze.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.birdmap.top/Article/details/gtjmvtgmic.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ydzc1.top/Article/details/gtpreymscs.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gtszplgzmx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hammf.cn/Article/details/gtkzqynpjl.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtzbahlvih.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.xylfe.cn/Article/details/gtxbcwrwbr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xinyue.icu/Article/details/gtnqmnovgx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.chenzaomai.com/Article/details/gthgpszbfl.html

[E15] HTML 转义 / 反转义
来源：http://dali.hysaishi.cn/Article/details/gtpkfkzkfy.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jianghu66.top/Article/details/gtzlqgcajw.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sweek.top/Article/details/gtwubmxiwk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yonumen.top/Article/details/gtsgcmvygm.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.0kj1m.cn/Article/details/gtvnsexmbs.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.iojbl.cn/Article/details/gtbemylvne.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gotoacloud.top/Article/details/gtkmxpjyob.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.quarkkingdee.top/Article/details/gtqoycsbtj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cqqwz.cn/Article/details/gtqoqrnaur.html

[E16] 数字千分位
来源：http://dali.kuanghao11.cn/Article/details/gtzfivpwqt.html

Py:   f"{1234567:,}"
来源：http://dali.jlsjyb.cn/Article/details/gtozgxjpcn.html

PHP:  number_format(1234567);
来源：http://dali.hammf.cn/Article/details/gtcbiuantv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gtitywctml.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jiagoushi.top/Article/details/gtmddtigow.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gtjvylxzbg.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.ppjwa.cn/Article/details/gtoihrgxnf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zdqjudy.top/Article/details/gtcnmowiej.html

C#:   1234567.ToString("N0")
来源：http://dali.yonumen.top/Article/details/gtwwrmzohl.html

[E17] 首字母大写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsepnuaoi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.cucudq.cn/Article/details/gtpnvkxddm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.vqdsnc.cn/Article/details/gtbjxpzuhn.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guowangkeji.top/Article/details/gtuhkzfkvz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shzxlz.cn/Article/details/gtphjsqcoc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yangfankeji.com/Article/details/gtixdkhmyl.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.wangdashe.top/Article/details/gtgmdhygbx.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxernuuo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuanzhike.top/Article/details/gtziedutoo.html

[E18] 模板占位符替换
来源：http://dali.yanxiufei.cn/Article/details/gtjdgxagbq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sysykeji.top/Article/details/gttzicjsgj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.aibaodan.cn/Article/details/gtlxlshgry.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtgrhiebcl.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yanxiufei.cn/Article/details/gtmndfhujw.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtymdywmbf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtwqhordsd.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtieazatua.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yvedp.cn/Article/details/gtyzlgzrgw.html

[E19] 多行文本按行拆分
来源：http://dali.pengpengdd.cyou/Article/details/gthedskbsg.html

Py:   s.splitlines()
来源：http://dali.dashuyun.cn/Article/details/gtvkoyaslm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ivvv.top/Article/details/gttcfkqssh.html

JS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gtqpxiubid.html

TS:   s.split(/\r?\n/)
来源：http://dali.hongshengwenyu.top/Article/details/gtkpvbbuze.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtymkrpbgf.html

Go:   strings.Split(s, "\n")
来源：http://dali.tian-w.cn/Article/details/gthhukaywn.html

Ruby: s.lines
来源：http://dali.zycfv.cn/Article/details/gtnozegyip.html

C#:   s.Split('\n')
来源：http://dali.pycfn.com/Article/details/gtzuvymwyq.html

[E20] 判断字符串是否为空
来源：http://dali.hywenlv.cn/Article/details/gtnjokhzkr.html

Py:   if not s:
来源：http://dali.tian-w.cn/Article/details/gtelwcvqig.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gtqesonmjk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtnqtnseup.html

TS:   if (s === "") {}
来源：http://dali.aibaodan.cn/Article/details/gtogqiecla.html

Java: if (s.isEmpty()) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtuxqyxggx.html

Go:   if s == "" {}
来源：http://dali.wangdashe.top/Article/details/gtaxcoxzal.html

Ruby: if s.empty?
来源：http://dali.vqdsnc.cn/Article/details/gtwswsanut.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.chenzaomai.com/Article/details/gtapvbmlax.html

[E21] 超长截断加省略号
来源：http://dali.ybcxt.top/Article/details/gtobbcgeir.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.chenjidiqi.icu/Article/details/gtucjxdawk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gtfaffclxl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gttxzatlfc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.chenlongwang.top/Article/details/gtvjdjlupv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaxbievj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgfzy.top/Article/details/gtvvmyypsg.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gtersumbgn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hywenlv.cn/Article/details/gtefbbumed.html

[E22] 字节长度与字符长度
来源：http://dali.haohaochexian.top/Article/details/gtmllubmuz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daria6918.cn/Article/details/gtnokumvfb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtuxwwoenp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenlongwang.top/Article/details/gtycldwlxt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jqgufenzy.top/Article/details/gthzhhionr.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ppjwa.cn/Article/details/gtqhgwfpfv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yanxiufei.cn/Article/details/gtjmlanzbh.html

Ruby: s.bytesize;  s.length
来源：http://dali.hnxiangtu.top/Article/details/gtrseceqrp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtxqaypnsu.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtfxfrjwil.html

F. 文件与目录
来源：http://dali.svipenyu.cn/Article/details/gtkndrryco.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtnpqlfdtx.html

[F01] 读取整个文件
来源：http://dali.nanxinkj.top/Article/details/gtvtcvcqdk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gteguywgxl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.iojbl.cn/Article/details/gtgowpkutt.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenzaomai.com/Article/details/gtkqoedlba.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gtljdifcfm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtehwkncnk.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aizwys.cn/Article/details/gtcpxiwfjs.html

Ruby: File.read("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtguztgucz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmuphtfq.html

[F02] 逐行读取文件
来源：http://dali.chenzaomai.com/Article/details/gtmxtrjcqy.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.shangyingyoupin.top/Article/details/gtnwpqngsi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cashguo.top/Article/details/gtabzhbetd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtpycmhhim.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhijiandao.cn/Article/details/gtjuesyziw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hongshengwenyu.top/Article/details/gtpqzeeret.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.9152youxi.cn/Article/details/gtsyznljwu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.andypj.xyz/Article/details/gtzpzdmmnm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.aizwys.cn/Article/details/gtaddlhjco.html

[F03] 写入文件（覆盖）
来源：http://dali.zhongyouzk.top/Article/details/gtibrqcuuv.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xuanzx.com/Article/details/gtcqybfizf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xuetiantiany.cn/Article/details/gtzkvbwhpv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yongpay.top/Article/details/gtwgdbsbya.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtqhaubbpf.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.redwolf501.top/Article/details/gtmfifsdnc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.haohaochexian.top/Article/details/gtbwbzqzot.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.yuxming.cn/Article/details/gtqwqndfdo.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zycfv.cn/Article/details/gtbhzfplom.html

[F04] 追加写入文件
来源：http://dali.ppjwa.cn/Article/details/gtsxtmsdpv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zhijiandao.cn/Article/details/gtgdwkrhqt.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenjidiqi.icu/Article/details/gtkfsghaof.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtoxzxvogh.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cheryme.top/Article/details/gtgzpzgnjz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sysykeji.top/Article/details/gtnurihlmg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtqyvrnbzk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gtcewtpfah.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jinqigfzy.top/Article/details/gttmfjmejk.html

[F05] 判断文件或目录是否存在
来源：http://dali.guannengcc.top/Article/details/gtumvoiicm.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sufxvd.cn/Article/details/gtcclltarx.html

PHP:  file_exists("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtpotyzfqo.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cheryme.top/Article/details/gtunllhmsf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtsovmmfhw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.guowangkeji.top/Article/details/gtqjbuydgc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhoulong.xyz/Article/details/gtvanagrbf.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gtwrlupnuq.html

C#:   File.Exists("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtiahfisdn.html

[F06] 删除文件
来源：http://dali.jianghu66.top/Article/details/gtbmjmrcyg.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtfdespakb.html

PHP:  unlink("a.txt");
来源：http://dali.zycfv.cn/Article/details/gtshunamdz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtapzcdlyy.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtgjsxqskv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtukvcgcuw.html

Go:   os.Remove("a.txt")
来源：http://dali.fengsongda.top/Article/details/gtyaszudyq.html

Ruby: File.delete("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtdparogfj.html

C#:   File.Delete("a.txt");
来源：http://dali.birdmap.top/Article/details/gtaphgbzad.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gtmbmpywxz.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtttgubnfx.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pycfn.com/Article/details/gthbsnerxi.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgufenzy.top/Article/details/gtspsrrksf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhixingplan.top/Article/details/gtrymrcwyh.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hnxiangtu.top/Article/details/gtwymesqfp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ppjwa.cn/Article/details/gtauwlxyow.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shangyingyoupin.top/Article/details/gtfgsiprcr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.feifeiyinyue.top/Article/details/gtqdxzmtrd.html

[F08] 遍历目录
来源：http://dali.cucudq.cn/Article/details/gtsmklqayb.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqgjmsgk.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aibaodan.cn/Article/details/gtwvdmsicf.html

JS:   fs.readdirSync("dir")
来源：http://dali.zycfv.cn/Article/details/gtbloqffqu.html

TS:   fs.readdirSync("dir")
来源：http://dali.smart0.xyz/Article/details/gthlarjqzr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangdashe.top/Article/details/gtabhogaka.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hywenlv.cn/Article/details/gtugzxzbau.html

Ruby: Dir.children("dir")
来源：http://dali.pengpengdd.cyou/Article/details/gtleyzspvw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtfaypgijl.html

[F09] 获取文件大小
来源：http://dali.svipenyu.cn/Article/details/gtevslktpd.html

Py:   os.path.getsize("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtuhdklidf.html

PHP:  filesize("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gtrgqckmjk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aibaodan.cn/Article/details/gtywazccqt.html

TS:   fs.statSync("a.txt").size
来源：http://dali.jqgfzy.top/Article/details/gtntiyenmq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gtohyueuqg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gthvchntnt.html

Ruby: File.size("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gthhluloqj.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.guowangkeji.top/Article/details/gtvrmjcgvk.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhijiandao.cn/Article/details/gtsfdywzaw.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtapsfbdvg.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtqojbxaue.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtmxsdyodb.html

TS:   path.extname("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gthuzpqaex.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.feifeiyinyue.top/Article/details/gtwfszzizc.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtfmojucwi.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtxkluolpy.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtdzhoendd.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gtpxuthpyy.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gthkzoktye.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yj202588.top/Article/details/gtdpgtdsef.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pycfn.com/Article/details/gtaocbjwja.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gtsalkfson.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.nwbrower.top/Article/details/gtofkemnoe.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hywenlv.cn/Article/details/gtmzzsrgva.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.kuanghao11.cn/Article/details/gttdcluxpv.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sweek.top/Article/details/gtbythuzvo.html

[F12] CSV 读写
来源：http://dali.jinqigufen.top/Article/details/gtdrabqzsd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gtvrdfizpc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258.top/Article/details/gtxsdbiktm.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.birdmap.top/Article/details/gtdizdiktf.html

TS:   // 同上
来源：http://dali.xinyue.icu/Article/details/gtccznfxtc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.quarkkingdee.top/Article/details/gtosiadesg.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gtraxoehhi.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.chenjidiqi.icu/Article/details/gtsnagmgrh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yj20258.top/Article/details/gtbpxruylh.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gthcfnosqb.html

G. 面向对象
来源：http://dali.nanxuanxn.top/Article/details/gtsbdojxmd.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtjpedtvhw.html

[G01] 定义类
来源：http://dali.pycfn.com/Article/details/gtipgygdxu.html

Py:   class User: pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaigajyra.html

PHP:  class User {}
来源：http://dali.birdmap.top/Article/details/gtwqllycii.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gtznohuyjj.html

TS:   class User { name: string = ""; }
来源：http://dali.tianlin.xyz/Article/details/gtrnsomilm.html

Java: class User {}
来源：http://dali.fengsongda.top/Article/details/gtfnqixpvm.html

Go:   type User struct { Name string }
来源：http://dali.havefunace.top/Article/details/gtflphcikz.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtovhsurvc.html

C#:   class User {}
来源：http://dali.jqgufenzy.top/Article/details/gtjfwdlkel.html

[G02] 构造函数
来源：http://dali.daxiang520.top/Article/details/gtifiqqduc.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.nanxuanxn.top/Article/details/gtxwlatlgu.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sysykeji.top/Article/details/gtwusblrgt.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hywenlv.cn/Article/details/gtntisblox.html

TS:   constructor(public name: string) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtvkrmwqfi.html

Java: User(String name) { this.name = name; }
来源：http://dali.yongpay.top/Article/details/gtzbhumgle.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.daria6918.cn/Article/details/gtqupktzdx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yj20258888.top/Article/details/gtlwotuamo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.tanke756.top/Article/details/gthwdydvxe.html

[G03] 实例属性
来源：http://dali.0kj1m.cn/Article/details/gtltvthtcy.html

Py:   self.name = "x"
来源：http://dali.andypj.xyz/Article/details/gtuurbunsb.html

PHP:  public string $name = "x";
来源：http://dali.zhoulong.xyz/Article/details/gtmatjzouz.html


<!-- 参考信息 -->