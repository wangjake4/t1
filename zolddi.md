代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gtitggqbao.html

[E03] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtisvobhkd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pengpengdd.cyou/Article/details/gtswzaiubd.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ydzc1.top/Article/details/gtbanguumn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtiwmmfqqb.html

TS:   s.slice(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtahqqjrzn.html

Java: s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtoghdiwrd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.iojbl.cn/Article/details/gtsagsgveq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jyoumei.cn/Article/details/gtgxkmqjgv.html

C#:   s.Substring(1, 3)
来源：http://dali.jianghu66.top/Article/details/gtlypsmunx.html

[E04] 查找子串位置
来源：http://dali.meibo888.top/Article/details/gtjmvmdvgp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guannengcc.top/Article/details/gtyqryvgey.html

PHP:  strpos($s, "x");
来源：http://dali.ybcxt.top/Article/details/gtlteqlmes.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nwbrower.top/Article/details/gtzwpbhqjh.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbpuhgvp.html

Java: s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtmqppoefd.html

Go:   strings.Index(s, "x")
来源：http://dali.hysaishi.cn/Article/details/gtilyuzisq.html

Ruby: s.index("x")
来源：http://dali.gzhubu.top/Article/details/gtkqdqpfsz.html

C#:   s.IndexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtjprvtqzp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhijiandao.cn/Article/details/gtljollgum.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.guowangkeji.top/Article/details/gtckecmuzq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.gogol.net.cn/Article/details/gtrunapsjx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhijiandao.cn/Article/details/gtiziilang.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcynqoffb.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtfenzojck.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.fzhhl.top/Article/details/gtiuzzagma.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hongshengwenyu.top/Article/details/gtjxvecxdj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.tian-w.cn/Article/details/gtxqvobirk.html

[E06] 替换子串
来源：http://dali.c1oappe.top/Article/details/gtfdzalrwb.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtstdwuiyn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.fzhhl.top/Article/details/gtutnuzdlb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtqfouiorw.html

TS:   s.replaceAll("a", "b")
来源：http://dali.svipenyu.cn/Article/details/gtwftmucwo.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtsiqwnenv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnkjewhq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtdbivbnnr.html

C#:   s.Replace("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtszqtgnjk.html

[E07] 按分隔符拆分
来源：http://dali.yangfankeji.com/Article/details/gtdcmbojvj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.ehwqpu.com/Article/details/gtwwhkpyhb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hywenlv.cn/Article/details/gtbqkisamg.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gttesdrrta.html

TS:   s.split(",")
来源：http://dali.ppjwa.cn/Article/details/gtlcghexxh.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jqgufenzy.top/Article/details/gticfxpjru.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nanxinkj.top/Article/details/gtpzvyeyga.html

Ruby: s.split(",");  s.split
来源：http://dali.vqdsnc.cn/Article/details/gtmyflxnrg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jiagoushi.top/Article/details/gtxyczrewt.html

[E08] 数组按分隔符合并
来源：http://dali.ivvv.top/Article/details/gtbqcrpitq.html

Py:   ",".join(items)
来源：http://dali.cqqwz.cn/Article/details/gtzpxcdmmf.html

PHP:  implode(",", $items);
来源：http://dali.yonumen.top/Article/details/gtyrqbkgan.html

JS:   items.join(",")
来源：http://dali.jinqigfzy.top/Article/details/gtijzfgifb.html

TS:   items.join(",")
来源：http://dali.jinqigufen.top/Article/details/gtbsbpwhkr.html

Java: String.join(",", items)
来源：http://dali.sweek.top/Article/details/gttravacvj.html

Go:   strings.Join(items, ",")
来源：http://dali.tanke756.top/Article/details/gtmzmzilfq.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gtfgimgsrq.html

C#:   string.Join(",", items)
来源：http://dali.jinqigfzy.top/Article/details/gtblhqghxq.html

[E09] 去除所有空白字符
来源：http://dali.xuetiantiany.cn/Article/details/gtfezkwcbi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sweek.top/Article/details/gtgfzgfuvw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtouxaipij.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj202588.top/Article/details/gtorcrwoyl.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.fengsongda.top/Article/details/gtaobbbvzl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yonumen.top/Article/details/gtrptpklmi.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gaohongyu789.top/Article/details/gtijdrenif.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.daria6918.cn/Article/details/gtitxcjrut.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.guannengcc.top/Article/details/gthbqeyrxv.html

[E10] 左侧补零 / 定长填充
来源：http://dali.meibo888.top/Article/details/gtxwtmuirs.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtnsrdhznu.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.ybcxt.top/Article/details/gtdddyqnaw.html

JS:   "7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtkjtxdxur.html

TS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtamhwgzpo.html

Java: String.format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtxmngjqxr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cdnleiting.top/Article/details/gtlnagwoiz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtwjepkgdq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.chenzaomai.com/Article/details/gtftwpgekn.html

[E11] 反转字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtulodufmi.html

Py:   s[::-1]
来源：http://dali.9152youxi.cn/Article/details/gtsgvmpumh.html

PHP:  strrev($s);
来源：http://dali.316326.xyz/Article/details/gtfolpeoxm.html

JS:   [...s].reverse().join("")
来源：http://dali.xuanzx.com/Article/details/gtctjaohwn.html

TS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtozjsceki.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.daxiang520.top/Article/details/gtvlopjtus.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtyxqfiacr.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gthkgmllgz.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.snrcjt.cn/Article/details/gtbkqgdkeh.html

[E12] 统计某字符出现次数
来源：http://dali.yangfankeji.com/Article/details/gtfavvcgee.html

Py:   s.count("a")
来源：http://dali.tian-w.cn/Article/details/gtnjwpvtnm.html

PHP:  substr_count($s, "a");
来源：http://dali.yuxming.cn/Article/details/gttyjobxnp.html

JS:   s.split("a").length - 1
来源：http://dali.jiagoushi.top/Article/details/gtgnehfnsn.html

TS:   s.split("a").length - 1
来源：http://dali.jlsjyb.cn/Article/details/gtnrcahseo.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gtankjkprg.html

Go:   strings.Count(s, "a")
来源：http://dali.birdmap.top/Article/details/gtetpfjzjs.html

Ruby: s.count("a")
来源：http://dali.hnqzz.top/Article/details/gtdfnfzold.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yonumen.top/Article/details/gtzfgywuuz.html

[E13] 逐字符遍历
来源：http://dali.nanxuanxn.top/Article/details/gtazvcziid.html

Py:   for ch in s: print(ch)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiiluqypq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.316326.xyz/Article/details/gtlylrhfdm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtvfdyysgk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gtugzhoevy.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.pengpengdd.cyou/Article/details/gteruzonoq.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.cheryme.top/Article/details/gtdeovhazw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.quarkkingdee.top/Article/details/gtuhedsvjp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtlpclqdro.html

[E14] URL 编码与 Base64
来源：http://dali.zhiwuduotai.top/Article/details/gtqoembrdw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.aibaodan.cn/Article/details/gtzbspwvey.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.jqgufenzy.top/Article/details/gteildurnb.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gttbyzcubz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.chenlongwang.top/Article/details/gtxpfranpg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fzhhl.top/Article/details/gtxhkyivke.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cashguo.top/Article/details/gtblvaqpzz.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hysaishi.cn/Article/details/gthjgthslm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yanxiufei.cn/Article/details/gthistmixh.html

[E15] HTML 转义 / 反转义
来源：http://dali.fzhhl.top/Article/details/gtknqzichw.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yangfankeji.com/Article/details/gtyhblixrx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xuanzx.com/Article/details/gtbfbunnef.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.shzxlz.cn/Article/details/gtotebpegj.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgxjrdbag.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cheryme.top/Article/details/gtuokqmois.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtvfzejkuu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sxryk.cn/Article/details/gtikywaywi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yj202588.top/Article/details/gtehmdjpli.html

[E16] 数字千分位
来源：http://dali.yuxming.cn/Article/details/gtedoakssr.html

Py:   f"{1234567:,}"
来源：http://dali.redwolf501.top/Article/details/gtezgidhmy.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gtmxiycozb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.gzhubu.top/Article/details/gtyawuhtlb.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.dashuyun.cn/Article/details/gtowhjwzso.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.9152youxi.cn/Article/details/gtacoqixoc.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbfxdsgp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.snrcjt.cn/Article/details/gtwxcxapoh.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gtwauubkaq.html

[E17] 首字母大写
来源：http://dali.0kj1m.cn/Article/details/gtxszihfom.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtjhfdoxvj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.aibaodan.cn/Article/details/gtdshtuzjs.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258.top/Article/details/gtbiehlwss.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dashuyun.cn/Article/details/gtldwogphw.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jiagoushi.top/Article/details/gtrbdosqzg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jlsjyb.cn/Article/details/gtwrezamyu.html

Ruby: s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gtrfzgopnh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yvedp.cn/Article/details/gtljwxuttg.html

[E18] 模板占位符替换
来源：http://dali.xylfe.cn/Article/details/gtfmlxcuft.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnxiangtu.top/Article/details/gtewnmulvr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj202588.top/Article/details/gtlhlmforv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.chenjidiqi.icu/Article/details/gtvlpcdtmj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gthoqdepbs.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.smart0.xyz/Article/details/gtkznaysqe.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj20258888.top/Article/details/gtrarrvolx.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.yanxiufei.cn/Article/details/gtwmqzitoh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yueranfly.top/Article/details/gtsruxrrmn.html

[E19] 多行文本按行拆分
来源：http://dali.hysaishi.cn/Article/details/gtplzddiyi.html

Py:   s.splitlines()
来源：http://dali.xinyue.icu/Article/details/gtugfchulv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtzmrsnssi.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtysgmtuos.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gtemggjsfl.html

Java: s.lines().toList()
来源：http://dali.gzhubu.top/Article/details/gtsobqsmlg.html

Go:   strings.Split(s, "\n")
来源：http://dali.nanxinkj.top/Article/details/gtvrfcfggu.html

Ruby: s.lines
来源：http://dali.yvedp.cn/Article/details/gttrlucrak.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gtiflfzwyw.html

[E20] 判断字符串是否为空
来源：http://dali.yangfankeji.com/Article/details/gtoblhxtlb.html

Py:   if not s:
来源：http://dali.cheryme.top/Article/details/gtomincxme.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hnxiangtu.top/Article/details/gtktrwwfuq.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hfpthk.cn/Article/details/gtoxddmwnw.html

TS:   if (s === "") {}
来源：http://dali.haohaochexian.top/Article/details/gtqhalakjr.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gtxuraizkb.html

Go:   if s == "" {}
来源：http://dali.hysaishi.cn/Article/details/gtyahywnbk.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gtrhlmjwfe.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.0kj1m.cn/Article/details/gtemtzfsxl.html

[E21] 超长截断加省略号
来源：http://dali.yj202588.top/Article/details/gttynkqkax.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.0kj1m.cn/Article/details/gtwytcitep.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gthiiqnmch.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtynremmjv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtjbgibwec.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtyelcunzo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhongyouzk.top/Article/details/gtjjcdttro.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtfbcuofqw.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gtxabwfnif.html

[E22] 字节长度与字符长度
来源：http://dali.zhijiandao.cn/Article/details/gtfoopvcuu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhengqikj.top/Article/details/gtcmuocawt.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiroivgod.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gtfslfbmig.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.kuanghao11.cn/Article/details/gthlyvrksz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwlzssfa.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pycfn.com/Article/details/gtgovzimxl.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtbhwtgznq.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.aizwys.cn/Article/details/gtbdphfots.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtzhlvcvwv.html

F. 文件与目录
来源：http://dali.xinyue.icu/Article/details/gtmpelpxsp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtkkevndez.html

[F01] 读取整个文件
来源：http://dali.cashguo.top/Article/details/gtrtrrfhwt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gtechstqvy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtuqbxfqdn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xylfe.cn/Article/details/gtakyxhnnc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhongyouzk.top/Article/details/gtgazytwpx.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtxkxconcz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.xuanzx.com/Article/details/gtstguvisl.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtaxcviipl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gtzcjwjodl.html

[F02] 逐行读取文件
来源：http://dali.smart0.xyz/Article/details/gtczmyhnzh.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gtomsgouna.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.sysykeji.top/Article/details/gtbdarmnmq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guannengcc.top/Article/details/gtzmjurkeo.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.316326.xyz/Article/details/gtdjltwjqx.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtylhckmxq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.haohaochexian.top/Article/details/gtbgfdgczr.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gtrqeqburj.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.quarkkingdee.top/Article/details/gtzyjbhprn.html

[F03] 写入文件（覆盖）
来源：http://dali.chenjidiqi.icu/Article/details/gtfsptcxct.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sweek.top/Article/details/gtlqycqciu.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtxulrhfhv.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tian-w.cn/Article/details/gtcdkwdzwz.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtxlhtcnor.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuxming.cn/Article/details/gtpmkrprgy.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.daxiang520.top/Article/details/gtvlqwmodk.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwssliiu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gtjpvusoey.html

[F04] 追加写入文件
来源：http://dali.chenjidiqi.icu/Article/details/gtaiqetohp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yvedp.cn/Article/details/gtpbdouvwh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yj202588.top/Article/details/gtlpkntwje.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenlongwang.top/Article/details/gtfjfiurwe.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntuvfwxc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gogol.net.cn/Article/details/gtjuaoeeuh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.tianlin.xyz/Article/details/gtduzfgonb.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.smart0.xyz/Article/details/gtszwtrbkw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jlsjyb.cn/Article/details/gtxgdchlmk.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gtcurnqaaq.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cdnleiting.top/Article/details/gtxhbsxtex.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtemjlabco.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtusprwlvj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.c1oappe.top/Article/details/gthpzhfhbh.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.feifeiyinyue.top/Article/details/gtzwtyovim.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shangyingyoupin.top/Article/details/gtktkzjwuz.html

Ruby: File.exist?("a.txt")
来源：http://dali.andypj.xyz/Article/details/gttwodvxse.html

C#:   File.Exists("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtdlswfdvd.html

[F06] 删除文件
来源：http://dali.yonumen.top/Article/details/gtuqjtovqu.html

Py:   os.remove("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtsodewjvi.html

PHP:  unlink("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtocehjqlp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtowwsshts.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gtwewwhdsb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtxobvbmme.html

Go:   os.Remove("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gttryglcvh.html

Ruby: File.delete("a.txt")
来源：http://dali.hammf.cn/Article/details/gttqvfhlaf.html

C#:   File.Delete("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtteyibnos.html

[F07] 创建目录（含多级）
来源：http://dali.chenjidiqi.icu/Article/details/gtovcvzhub.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aibaodan.cn/Article/details/gtylknseyh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.sufxvd.cn/Article/details/gtntnivucq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.haohaochexian.top/Article/details/gtdrrjrfpy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtwolyxjcs.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gtjyujsaqd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.hywenlv.cn/Article/details/gtndwhdddl.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gttorxdlfa.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jianghu66.top/Article/details/gtzmzueavy.html

[F08] 遍历目录
来源：http://dali.gogol.net.cn/Article/details/gtuwdcyyri.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yongpay.top/Article/details/gtodtwejwf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jianghu66.top/Article/details/gtbkrtrkxx.html

JS:   fs.readdirSync("dir")
来源：http://dali.andypj.xyz/Article/details/gthqzydyhg.html

TS:   fs.readdirSync("dir")
来源：http://dali.tian-w.cn/Article/details/gthehvwsgm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gtakimumdc.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.dianchejie.cn/Article/details/gtzwqmphdi.html

Ruby: Dir.children("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrwhqzzc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gtzrckbdvp.html

[F09] 获取文件大小
来源：http://dali.feifeiyinyue.top/Article/details/gtrpzcyppz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtxvlmqsxr.html

PHP:  filesize("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtgrkpycjv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhoulong.xyz/Article/details/gtrczajpdp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gtdhjjildy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.gotoacloud.top/Article/details/gtsuvdatuk.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.nanxinkj.top/Article/details/gtybrdmjun.html

Ruby: File.size("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtdahhykqp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yuanzhike.top/Article/details/gtfgboqrao.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.wangdashe.top/Article/details/gtvsxhqeqi.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yuxming.cn/Article/details/gthgqucvgv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtvsdjgxum.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtnfdpylsw.html

TS:   path.extname("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gticcrjcln.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgfzy.top/Article/details/gtmbsarbbj.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtoqjukvjh.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtfugdunrx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.sweek.top/Article/details/gtqzjhftdv.html

[F11] 复制与移动文件
来源：http://dali.hnqzz.top/Article/details/gtyrftdmro.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtcdnwtocv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gtxksyeeed.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gtnxsqkeds.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtfvxvxlez.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gtlybbvxld.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhixingplan.top/Article/details/gtioqxoach.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.xziqi.cn/Article/details/gtuwgrgwid.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hongshengwenyu.top/Article/details/gtmbzoizsj.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gtbhdiilmy.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.gogol.net.cn/Article/details/gtyaomgire.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jianghu66.top/Article/details/gthdgvjtnw.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.kuanghao11.cn/Article/details/gtapijoqwm.html

TS:   // 同上
来源：http://dali.zdqjudy.top/Article/details/gtabckpflb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ybcxt.top/Article/details/gtgmxeztev.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.daxiang520.top/Article/details/gtqgoeygww.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhiwuduotai.top/Article/details/gtwrvocflq.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jlsjyb.cn/Article/details/gtciqxrbgv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtidahybpy.html

G. 面向对象
来源：http://dali.yuxming.cn/Article/details/gtkbfckvnd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtfnjlwmvq.html

[G01] 定义类
来源：http://dali.sxryk.cn/Article/details/gtvndirqdx.html

Py:   class User: pass
来源：http://dali.jlsjyb.cn/Article/details/gtbobeeprc.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gttlrntsrj.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gthggauazz.html

TS:   class User { name: string = ""; }
来源：http://dali.dianchejie.cn/Article/details/gtcjxpiani.html


<!-- 参考信息 -->