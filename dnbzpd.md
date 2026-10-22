代发 wailian999

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtkpgdjmqu.html

TS:   s.slice(1, 4)
来源：http://dali.dashuyun.cn/Article/details/gtivmbuuup.html

Java: s.substring(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmenfutyk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tian-w.cn/Article/details/gtzlynkrtu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.nanxinkj.top/Article/details/gtnhaxrfhn.html

C#:   s.Substring(1, 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtqeydzhib.html

[E04] 查找子串位置
来源：http://dali.birdmap.top/Article/details/gtugyhjlko.html

Py:   s.find("x");  s.index("x")
来源：http://dali.redwolf501.top/Article/details/gtfbzyecid.html

PHP:  strpos($s, "x");
来源：http://dali.sysykeji.top/Article/details/gtlhwjovmb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258.top/Article/details/gthgxpjjxp.html

TS:   s.indexOf("x")
来源：http://dali.daxiang520.top/Article/details/gthpjbakwi.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtmqmmsbxn.html

Go:   strings.Index(s, "x")
来源：http://dali.ehwqpu.com/Article/details/gtglfqbtax.html

Ruby: s.index("x")
来源：http://dali.bjfxy.top/Article/details/gtfkqxvvrz.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gtgeygbpwa.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.cheryme.top/Article/details/gteljgzdet.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtbisdnvwf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.jqgfzy.top/Article/details/gtjgbrqrvf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.gogol.net.cn/Article/details/gthdblbsoc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cashguo.top/Article/details/gtokuukqtk.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtjpcbvupv.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gtozvkzelu.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.tanke756.top/Article/details/gttjrseway.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtujmzwcnq.html

[E06] 替换子串
来源：http://dali.zhiwuduotai.top/Article/details/gtxwimzsah.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gtyhwvrtoy.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gzhubu.top/Article/details/gtoqpftkfl.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtmddsymgg.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gtsdekhkgq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtmlnlqhhz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.iojbl.cn/Article/details/gtbwvsmptk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtpbodsncq.html

C#:   s.Replace("a", "b")
来源：http://dali.hongshengwenyu.top/Article/details/gtxgtsgfox.html

[E07] 按分隔符拆分
来源：http://dali.gogol.net.cn/Article/details/gtfwjknmtk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.hammf.cn/Article/details/gtrflflvza.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.bjfxy.top/Article/details/gtofeucmwa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagbalvbk.html

TS:   s.split(",")
来源：http://dali.guannengcc.top/Article/details/gtnecxiqyt.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.vqdsnc.cn/Article/details/gtouwfxeet.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.ehwqpu.com/Article/details/gtbqgokwlj.html

Ruby: s.split(",");  s.split
来源：http://dali.quarkkingdee.top/Article/details/gtcawdijjn.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhixingplan.top/Article/details/gtsmauawwn.html

[E08] 数组按分隔符合并
来源：http://dali.tian-w.cn/Article/details/gtfwchqfyq.html

Py:   ",".join(items)
来源：http://dali.bjfxy.top/Article/details/gtcyhieopz.html

PHP:  implode(",", $items);
来源：http://dali.bjfxy.top/Article/details/gtijluyism.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtwxgnwzbk.html

TS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtluwrwidk.html

Java: String.join(",", items)
来源：http://dali.birdmap.top/Article/details/gtnxyvlmkn.html

Go:   strings.Join(items, ",")
来源：http://dali.zhixingplan.top/Article/details/gtyyeqfzlp.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtkagcrwyu.html

C#:   string.Join(",", items)
来源：http://dali.zhoulong.xyz/Article/details/gtxsnmtpuv.html

[E09] 去除所有空白字符
来源：http://dali.feifeiyinyue.top/Article/details/gtbjxprhev.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhixingplan.top/Article/details/gtkjcouhpq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.cdnleiting.top/Article/details/gtllmfpvhi.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.dashuyun.cn/Article/details/gtowjtmlwq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yueranfly.top/Article/details/gtprulazap.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tianlin.xyz/Article/details/gtfabubxbs.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.dashuyun.cn/Article/details/gthdczksmq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.ydzc1.top/Article/details/gtxocnioig.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ppjwa.cn/Article/details/gtakahkgmm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jianghu66.top/Article/details/gtqbjejeam.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gthqhkygbq.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jqgufenzy.top/Article/details/gtprbecrba.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtejzeelhj.html

TS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtyzdoneof.html

Java: String.format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtswlbhxyk.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtfbmzdkyv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.cqqwz.cn/Article/details/gtkcjwmdae.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.smart0.xyz/Article/details/gttxzzxlps.html

[E11] 反转字符串
来源：http://dali.jlsjyb.cn/Article/details/gtvxzrgcpw.html

Py:   s[::-1]
来源：http://dali.jinghuilouyu.cn/Article/details/gtordcgffd.html

PHP:  strrev($s);
来源：http://dali.jianghu66.top/Article/details/gtwntxubfl.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gthzobdhjf.html

TS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtboalabzx.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.bjfxy.top/Article/details/gtnjjibyuf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxinkj.top/Article/details/gtreavftrl.html

Ruby: s.reverse
来源：http://dali.redwolf501.top/Article/details/gttlosesvk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.redwolf501.top/Article/details/gthlxrwjws.html

[E12] 统计某字符出现次数
来源：http://dali.tian-w.cn/Article/details/gtcwkfulvd.html

Py:   s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtyiftghjy.html

PHP:  substr_count($s, "a");
来源：http://dali.shangyingyoupin.top/Article/details/gtoburkivd.html

JS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrexouut.html

TS:   s.split("a").length - 1
来源：http://dali.gotoacloud.top/Article/details/gtewouizfd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tian-w.cn/Article/details/gtabqlgtwu.html

Go:   strings.Count(s, "a")
来源：http://dali.gotoacloud.top/Article/details/gtichfofmb.html

Ruby: s.count("a")
来源：http://dali.dianchejie.cn/Article/details/gtscylfhph.html

C#:   s.Count(c => c == 'a')
来源：http://dali.daria6918.cn/Article/details/gtheggaoej.html

[E13] 逐字符遍历
来源：http://dali.svipenyu.cn/Article/details/gtnhwphcej.html

Py:   for ch in s: print(ch)
来源：http://dali.jyoumei.cn/Article/details/gthjcnkkjp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aizwys.cn/Article/details/gtjfzfeczh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.tian-w.cn/Article/details/gtunxzhrub.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtsveavmdl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.zhoulong.xyz/Article/details/gtvoypmksj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenzaomai.com/Article/details/gtuxghjhtq.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhongyouzk.top/Article/details/gteaotiwth.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zdqjudy.top/Article/details/gttrvmdeou.html

[E14] URL 编码与 Base64
来源：http://dali.chenzaomai.com/Article/details/gtdztwtjns.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gttpcbmkej.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.c1oappe.top/Article/details/gtnomckbnt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtisptyizr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.316326.xyz/Article/details/gtgzmykrnn.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258.top/Article/details/gtwfvatjzh.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shangyingyoupin.top/Article/details/gtymevofwe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cdnleiting.top/Article/details/gtffutrldn.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xylfe.cn/Article/details/gtonomgpso.html

[E15] HTML 转义 / 反转义
来源：http://dali.yonumen.top/Article/details/gtrxssduqa.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiovzclkh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuetiantiany.cn/Article/details/gtawdnxbik.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.birdmap.top/Article/details/gtqhmzfppd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtukilbvsj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hongshengwenyu.top/Article/details/gtwxeyixux.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.sxryk.cn/Article/details/gtyfwjdyrd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtocjagpxr.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhongyouzk.top/Article/details/gtszyudkbr.html

[E16] 数字千分位
来源：http://dali.wangdashe.top/Article/details/gtypcatrur.html

Py:   f"{1234567:,}"
来源：http://dali.xinyue.icu/Article/details/gtbrynuswa.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gtqdnowulk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.ppjwa.cn/Article/details/gtmaeaxtlo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shuidangran.top/Article/details/gtfjebmzte.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yonumen.top/Article/details/gtdhosezzp.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayladpll.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgufenzy.top/Article/details/gtypnefeqd.html

C#:   1234567.ToString("N0")
来源：http://dali.316326.xyz/Article/details/gtodwfkkbb.html

[E17] 首字母大写
来源：http://dali.vqdsnc.cn/Article/details/gtbopbxojn.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jiagoushi.top/Article/details/gtsktigpez.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtibczglme.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtygiztrha.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.fzhhl.top/Article/details/gtgosnbrrd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.bjfxy.top/Article/details/gtsetmyetn.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.vqdsnc.cn/Article/details/gtmqliiphs.html

Ruby: s.capitalize
来源：http://dali.haohaochexian.top/Article/details/gtmcrqkvya.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gtwckcjvhs.html

[E18] 模板占位符替换
来源：http://dali.yuanzhike.top/Article/details/gtggguebyx.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.bjfxy.top/Article/details/gtvezaxyqt.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hysaishi.cn/Article/details/gtykguulmw.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtmnjrjazw.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtmthqlfxl.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.haohaochexian.top/Article/details/gtjjwpbtgz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtyufzivav.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.haohaochexian.top/Article/details/gtvomryisg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.nanxinkj.top/Article/details/gtpvaxvmge.html

[E19] 多行文本按行拆分
来源：http://dali.guowangkeji.top/Article/details/gtmpyxpbdd.html

Py:   s.splitlines()
来源：http://dali.zhongyouzk.top/Article/details/gtyhzbqilz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtddngqggi.html

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gtiajgpbcr.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuanzx.com/Article/details/gtizqfvhzc.html

Java: s.lines().toList()
来源：http://dali.yangfankeji.com/Article/details/gtsjkyepmj.html

Go:   strings.Split(s, "\n")
来源：http://dali.vqdsnc.cn/Article/details/gtbcupzqas.html

Ruby: s.lines
来源：http://dali.gogol.net.cn/Article/details/gtnkmczuxh.html

C#:   s.Split('\n')
来源：http://dali.gzhubu.top/Article/details/gtpiiksybv.html

[E20] 判断字符串是否为空
来源：http://dali.pengpengdd.cyou/Article/details/gtdfdweozg.html

Py:   if not s:
来源：http://dali.daria6918.cn/Article/details/gtqrhzcree.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.nanxuanxn.top/Article/details/gtjdekcjco.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gtxzpctris.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqddlhaik.html

Java: if (s.isEmpty()) {}
来源：http://dali.svipenyu.cn/Article/details/gtgujkzttz.html

Go:   if s == "" {}
来源：http://dali.fzhhl.top/Article/details/gtwulpdgem.html

Ruby: if s.empty?
来源：http://dali.andypj.xyz/Article/details/gtzbpvtjsm.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jiagoushi.top/Article/details/gtlzzjkzyy.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gtvapqokni.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xinyue.icu/Article/details/gtwuddbtux.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtaviufdjz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gtynsniius.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtmyeuskyk.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtvxewefyj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shangyingyoupin.top/Article/details/gtptyvfnba.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtukhpjzyv.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnqzz.top/Article/details/gtnlnehaud.html

[E22] 字节长度与字符长度
来源：http://dali.zhengqikj.top/Article/details/gtkcaccymk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xuanzx.com/Article/details/gtncdqzkxi.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gtutwpajkb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gtpxmoiivw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dashuyun.cn/Article/details/gtjsdydjlb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.gogol.net.cn/Article/details/gtslxknome.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.vqdsnc.cn/Article/details/gteicrbthl.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gtqvjwhfaf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.quarkkingdee.top/Article/details/gtibomvjko.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtlpuvhrew.html

F. 文件与目录
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumosnyhg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtajbnvyqy.html

[F01] 读取整个文件
来源：http://dali.aizwys.cn/Article/details/gtozkzzvdf.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.sufxvd.cn/Article/details/gtadpsyttp.html

PHP:  file_get_contents("a.txt");
来源：http://dali.havefunace.top/Article/details/gtmdjokshk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwmxlausn.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gtifsonkul.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.shuidangran.top/Article/details/gtpvjycfgg.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.guowangkeji.top/Article/details/gtbiakjftk.html

Ruby: File.read("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtyzkpvkaf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtvwnojqxl.html

[F02] 逐行读取文件
来源：http://dali.zycfv.cn/Article/details/gtutcunwal.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yj202588.top/Article/details/gtcqweprtz.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtztzalhoh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gtbkvwomlj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sufxvd.cn/Article/details/gtjkfumtcf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtmojlxswi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.fzhhl.top/Article/details/gtwxrlipfm.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.vqdsnc.cn/Article/details/gtalvcpxcx.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jqgfzy.top/Article/details/gtihbkedkq.html

[F03] 写入文件（覆盖）
来源：http://dali.jianghu66.top/Article/details/gtcjmfqbfe.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.daria6918.cn/Article/details/gtaymkumwj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhixingplan.top/Article/details/gtxzfjsisz.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gtbqhnjhet.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.c1oappe.top/Article/details/gtpnwnuiod.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.nwbrower.top/Article/details/gtpoaceggx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gtbexgqtzg.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gtpoyovvrg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.ybcxt.top/Article/details/gtibvaveqc.html

[F04] 追加写入文件
来源：http://dali.hfpthk.cn/Article/details/gtwvxyswyg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuiargrrv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hysaishi.cn/Article/details/gtizhggnmb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtjnednusn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guannengcc.top/Article/details/gtoaqzalan.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.xylfe.cn/Article/details/gtubmehhwf.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gtcvhhblee.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jlsjyb.cn/Article/details/gtddkzfznd.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.iojbl.cn/Article/details/gtdcqjppds.html

[F05] 判断文件或目录是否存在
来源：http://dali.316326.xyz/Article/details/gtzxiflgyj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj202588.top/Article/details/gtrafnvxjl.html

PHP:  file_exists("a.txt");
来源：http://dali.cheryme.top/Article/details/gtakusftjr.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gtwgdovorq.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtbehbyzjk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yj20258888.top/Article/details/gtcfvegubp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.birdmap.top/Article/details/gtioxqnupc.html

Ruby: File.exist?("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtjuxsztbs.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtmwrqkein.html

[F06] 删除文件
来源：http://dali.ivvv.top/Article/details/gtlzihwrvs.html

Py:   os.remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gtjexhbtka.html

PHP:  unlink("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gtikpxzoez.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gtajaqmeen.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtjxtsejrt.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gtucaduhci.html

Go:   os.Remove("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtsnubgfza.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gttdmwocaw.html

C#:   File.Delete("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtfxxsnajf.html

[F07] 创建目录（含多级）
来源：http://dali.dashuyun.cn/Article/details/gtvjsfhoys.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcloeirhj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.redwolf501.top/Article/details/gtadbwqrdo.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aibaodan.cn/Article/details/gticwxkvun.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtowbevaqf.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gtshenhuaj.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.316326.xyz/Article/details/gtlantyzau.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.mhx1999.top/Article/details/gtcrgfuebb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ybcxt.top/Article/details/gtqrnkcscv.html

[F08] 遍历目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsyhirsk.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj202588.top/Article/details/gthtmambch.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jinqigfzy.top/Article/details/gthbzbwqjj.html

JS:   fs.readdirSync("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtzvlqpolp.html

TS:   fs.readdirSync("dir")
来源：http://dali.nwbrower.top/Article/details/gtkimpunuw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzjlistr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtooalnesq.html

Ruby: Dir.children("dir")
来源：http://dali.svipenyu.cn/Article/details/gtokguedde.html

C#:   Directory.GetFiles("dir")
来源：http://dali.nwbrower.top/Article/details/gtkhskwnhf.html

[F09] 获取文件大小
来源：http://dali.tianlin.xyz/Article/details/gthbudnwkn.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtjvsivqfq.html

PHP:  filesize("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtyowlnpux.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqastgiu.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cucudq.cn/Article/details/gtdtabqwhs.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtvwcdrpza.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoayozdeo.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtgddzoskf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yj202588.top/Article/details/gtklnkipti.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.xuetiantiany.cn/Article/details/gtncyfiqpj.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtqxocneqt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gtrryrcrte.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtcmvzcrav.html

TS:   path.extname("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtyahcktoy.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.pengpengdd.cyou/Article/details/gtkfdwfgcw.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtoqilhsww.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.ybcxt.top/Article/details/gtpbaupgow.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gtjejzebnl.html

[F11] 复制与移动文件
来源：http://dali.zhijiandao.cn/Article/details/gtglmlxlwc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtfskonctw.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.xinyue.icu/Article/details/gtgvsmxsqq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtsxfrxsfy.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenzaomai.com/Article/details/gtsiusbowe.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.iojbl.cn/Article/details/gtdsvddlfv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.meibo888.top/Article/details/gtkksxvygh.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtwhhdndne.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cqqwz.cn/Article/details/gtibdaohlj.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gtspmbvxyd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtauxwmebd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.daria6918.cn/Article/details/gtvujhyxdp.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.haohaochexian.top/Article/details/gtqymmhndu.html

TS:   // 同上
来源：http://dali.mhx1999.top/Article/details/gtsvrkvbkh.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrypitxiy.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnxiangtu.top/Article/details/gtthmcwldz.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yuxming.cn/Article/details/gtjbqgddxl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnymyypg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtpipnjzgv.html

G. 面向对象
来源：http://dali.bjfxy.top/Article/details/gtelklsipn.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gttsqhxoxi.html

[G01] 定义类
来源：http://dali.gotoacloud.top/Article/details/gtllhhprsw.html

Py:   class User: pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gtowmratba.html

PHP:  class User {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjresdgsz.html

JS:   class User {}
来源：http://dali.shzxlz.cn/Article/details/gtedftpyqc.html

TS:   class User { name: string = ""; }
来源：http://dali.tanke756.top/Article/details/gtwcwlegpu.html

Java: class User {}
来源：http://dali.jinqigufen.top/Article/details/gtfqfxmjji.html

Go:   type User struct { Name string }
来源：http://dali.zdqjudy.top/Article/details/gtppqixpbd.html

Ruby: class User; end
来源：http://dali.jyoumei.cn/Article/details/gtjeourpda.html

C#:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtlnmjqqby.html


<!-- 参考信息 -->