代发 wailian999

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtginvmktx.html

C#:   s.Substring(1, 3)
来源：http://dali.tian-w.cn/Article/details/gtpslryztg.html

[E04] 查找子串位置
来源：http://dali.tanke756.top/Article/details/gttlwifxkl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gtcwvxkvsr.html

PHP:  strpos($s, "x");
来源：http://dali.hfpthk.cn/Article/details/gteeocioxd.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.fengsongda.top/Article/details/gtapjhgcbx.html

TS:   s.indexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gtrrtekdrj.html

Java: s.indexOf("x")
来源：http://dali.zdqjudy.top/Article/details/gtrroszclc.html

Go:   strings.Index(s, "x")
来源：http://dali.chenlongwang.top/Article/details/gtcdrgjzps.html

Ruby: s.index("x")
来源：http://dali.cheryme.top/Article/details/gtxffwzxxn.html

C#:   s.IndexOf("x")
来源：http://dali.birdmap.top/Article/details/gtgwyayfvf.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.kuanghao11.cn/Article/details/gtgdktgtrr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtidxdxthn.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.tianlin.xyz/Article/details/gtfxrjqspr.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenzaomai.com/Article/details/gtxqmrgekk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.mhx1999.top/Article/details/gttbqumbta.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.snrcjt.cn/Article/details/gthnlhqzop.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daria6918.cn/Article/details/gtdvcqurhd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xuanzx.com/Article/details/gtdjmpvgor.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jianghu66.top/Article/details/gttbfstvfo.html

[E06] 替换子串
来源：http://dali.cqqwz.cn/Article/details/gtijamcvzj.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.meibo888.top/Article/details/gtocxwbqfs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.nanxuanxn.top/Article/details/gtwwtnopgt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtxsfugwcb.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnyumbps.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gttztgbgia.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.zhixingplan.top/Article/details/gtugbpbxwp.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sxryk.cn/Article/details/gtntnrygax.html

C#:   s.Replace("a", "b")
来源：http://dali.birdmap.top/Article/details/gtmdtsotoh.html

[E07] 按分隔符拆分
来源：http://dali.zhengqikj.top/Article/details/gtikjglivl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.mhx1999.top/Article/details/gtyncvajdt.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.c1oappe.top/Article/details/gtqnnzpdit.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.wangshuangyany.cn/Article/details/gtqprxjwbw.html

TS:   s.split(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtbdhiowjo.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hysaishi.cn/Article/details/gtcmdhptty.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.birdmap.top/Article/details/gtoiljmhra.html

Ruby: s.split(",");  s.split
来源：http://dali.hysaishi.cn/Article/details/gthgvtkmmk.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jinqigfzy.top/Article/details/gtuufzrhsq.html

[E08] 数组按分隔符合并
来源：http://dali.iojbl.cn/Article/details/gtswjqpmhc.html

Py:   ",".join(items)
来源：http://dali.9152youxi.cn/Article/details/gtjhvrgwer.html

PHP:  implode(",", $items);
来源：http://dali.cucudq.cn/Article/details/gtjmbyfxwn.html

JS:   items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtpwkqngew.html

TS:   items.join(",")
来源：http://dali.bjfxy.top/Article/details/gtulqkuakp.html

Java: String.join(",", items)
来源：http://dali.shzxlz.cn/Article/details/gtvbprfote.html

Go:   strings.Join(items, ",")
来源：http://dali.havefunace.top/Article/details/gtlbzrhvpd.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gtodotencc.html

C#:   string.Join(",", items)
来源：http://dali.ybcxt.top/Article/details/gtlowwwlyo.html

[E09] 去除所有空白字符
来源：http://dali.jqgfzy.top/Article/details/gtuulhqbek.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.chenzaomai.com/Article/details/gtpjovijjj.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtchnufsln.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gtwpumssaz.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.quarkkingdee.top/Article/details/gtjoukpxib.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.mhx1999.top/Article/details/gtphboafen.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.mhx1999.top/Article/details/gtbcyerlnt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtvlububtn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtpwsgohxf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.andypj.xyz/Article/details/gtbglvscxb.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tanke756.top/Article/details/gtpjqwthhx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.xinyue.icu/Article/details/gthjlnrhob.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gtdxocqojx.html

TS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtlgpvcyvp.html

Java: String.format("%03d", 7)
来源：http://dali.redwolf501.top/Article/details/gtdhijqnna.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtoxnjekkc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gtwdixeryb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xylfe.cn/Article/details/gtzmqgedxe.html

[E11] 反转字符串
来源：http://dali.yongpay.top/Article/details/gtvuiywkfw.html

Py:   s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtdsohosdz.html

PHP:  strrev($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtvwusdudd.html

JS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtnftegfsd.html

TS:   [...s].reverse().join("")
来源：http://dali.yvedp.cn/Article/details/gtqeukpawt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cucudq.cn/Article/details/gtxpbfkuep.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yvedp.cn/Article/details/gtebkvziwk.html

Ruby: s.reverse
来源：http://dali.zhixingplan.top/Article/details/gtneghgflo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrnyhliq.html

[E12] 统计某字符出现次数
来源：http://dali.hammf.cn/Article/details/gtuygsfigz.html

Py:   s.count("a")
来源：http://dali.ivvv.top/Article/details/gtroenqmwq.html

PHP:  substr_count($s, "a");
来源：http://dali.yuxming.cn/Article/details/gtwqzxasit.html

JS:   s.split("a").length - 1
来源：http://dali.feifeiyinyue.top/Article/details/gtzjupdery.html

TS:   s.split("a").length - 1
来源：http://dali.shuidangran.top/Article/details/gtwhmcuqxn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.birdmap.top/Article/details/gtqltorhwg.html

Go:   strings.Count(s, "a")
来源：http://dali.zdqjudy.top/Article/details/gtuhohmmof.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtbsynywbc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sxryk.cn/Article/details/gtgjuwverp.html

[E13] 逐字符遍历
来源：http://dali.hfpthk.cn/Article/details/gthkycciwg.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gtimiifjij.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.redwolf501.top/Article/details/gtbtluqsgi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gtjwqjqzym.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtoycamkhe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.redwolf501.top/Article/details/gtshqiabqu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.c1oappe.top/Article/details/gtgfoikokf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.vqdsnc.cn/Article/details/gtasqcpyen.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtclgfgaqv.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gtxjhttbkr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sweek.top/Article/details/gtqpqqhtlz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.snrcjt.cn/Article/details/gtfjaqfacq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ppjwa.cn/Article/details/gtqtobufvz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nwbrower.top/Article/details/gtlkwpltwc.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gtkllpfyet.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnxiangtu.top/Article/details/gtycgmdoor.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.chenjidiqi.icu/Article/details/gtamtpmavm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtnzeojkdk.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gtyrwozibu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangshuangyany.cn/Article/details/gthtvkryul.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gotoacloud.top/Article/details/gtirqhuwzv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.0kj1m.cn/Article/details/gtxkrzbler.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.snrcjt.cn/Article/details/gtyfowdgfn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yuxming.cn/Article/details/gtufkzahyb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gtaygbpnfa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258888.top/Article/details/gtwoovidau.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gtxcvsqttc.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gtcoydhjfo.html

Py:   f"{1234567:,}"
来源：http://dali.yj202588.top/Article/details/gtvnvxtmkz.html

PHP:  number_format(1234567);
来源：http://dali.xuanzx.com/Article/details/gtjnbbctze.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinqigufen.top/Article/details/gtykdtzdkm.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cqqwz.cn/Article/details/gtecdhvtdi.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpyqbtfx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.316326.xyz/Article/details/gtlkilrzxc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yvedp.cn/Article/details/gtkbkpdyjt.html

C#:   1234567.ToString("N0")
来源：http://dali.daria6918.cn/Article/details/gtfpldliad.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gtwrijugag.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gtnnhvcayu.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gtsohnhfnb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xuanzx.com/Article/details/gttlbwprds.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zdqjudy.top/Article/details/gtxnplvpyx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cqqwz.cn/Article/details/gtctnkisjj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gtdrspjppv.html

Ruby: s.capitalize
来源：http://dali.9152youxi.cn/Article/details/gtwzbajlgt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nwbrower.top/Article/details/gtfzumdwuz.html

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gtooeqakuq.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jyoumei.cn/Article/details/gtkzugruwr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhongyouzk.top/Article/details/gthwziazgf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gtuxnlldjf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtveayxfky.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gtbpmwdptg.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtedgrzvrw.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tanke756.top/Article/details/gtwzleduew.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ehwqpu.com/Article/details/gtkufjtnkq.html

[E19] 多行文本按行拆分
来源：http://dali.aizwys.cn/Article/details/gtihhzlnww.html

Py:   s.splitlines()
来源：http://dali.yangfankeji.com/Article/details/gtcqxhnjpr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gtphkzjzsz.html

JS:   s.split(/\r?\n/)
来源：http://dali.jqgufenzy.top/Article/details/gtpocpwmpw.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gtefofetxo.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gthpdbjobd.html

Go:   strings.Split(s, "\n")
来源：http://dali.yonumen.top/Article/details/gtcypvnqoy.html

Ruby: s.lines
来源：http://dali.dianchejie.cn/Article/details/gtowzogtrm.html

C#:   s.Split('\n')
来源：http://dali.aizwys.cn/Article/details/gtplwyeice.html

[E20] 判断字符串是否为空
来源：http://dali.chenlongwang.top/Article/details/gtadpsddyv.html

Py:   if not s:
来源：http://dali.tian-w.cn/Article/details/gtgvmhvmjp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenlongwang.top/Article/details/gtpdyktgil.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.mhx1999.top/Article/details/gtdgwcoyaf.html

TS:   if (s === "") {}
来源：http://dali.yongpay.top/Article/details/gtmeilmtjj.html

Java: if (s.isEmpty()) {}
来源：http://dali.0kj1m.cn/Article/details/gtbwvpytar.html

Go:   if s == "" {}
来源：http://dali.9152youxi.cn/Article/details/gtzavhcpoa.html

Ruby: if s.empty?
来源：http://dali.nwbrower.top/Article/details/gthscisyxz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvquwuzl.html

[E21] 超长截断加省略号
来源：http://dali.svipenyu.cn/Article/details/gtuianbgle.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.snrcjt.cn/Article/details/gthejrjusy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj202588.top/Article/details/gteuvglqzl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtimuerdyq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gtpbcvtxpw.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.smart0.xyz/Article/details/gtvjfniewq.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tanke756.top/Article/details/gtcsrgydtu.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtqibandvn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gtefqntghv.html

[E22] 字节长度与字符长度
来源：http://dali.kuanghao11.cn/Article/details/gthhxuajnf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhakcnza.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvmnboirh.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxuanxn.top/Article/details/gtdrigyive.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.haohaochexian.top/Article/details/gtfgbeftao.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.iojbl.cn/Article/details/gtjttgtkhb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnxiangtu.top/Article/details/gtlidofxyh.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gtutirrxyu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shuidangran.top/Article/details/gtfvecxzxr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gttatsnmqh.html

F. 文件与目录
来源：http://dali.jqgfzy.top/Article/details/gtrxcrtgod.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtootpztdf.html

[F01] 读取整个文件
来源：http://dali.sufxvd.cn/Article/details/gtehmyyqzj.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gtovsquudc.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fzhhl.top/Article/details/gthcqvmrnd.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yongpay.top/Article/details/gtivkxjspy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.yj202588.top/Article/details/gtvvylqiir.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gtahvashqe.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sysykeji.top/Article/details/gtcxklqzrv.html

Ruby: File.read("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtzdbwnwko.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daxiang520.top/Article/details/gtcvozrqid.html

[F02] 逐行读取文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylqfbmfb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.sweek.top/Article/details/gtcolpzxil.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.chenzaomai.com/Article/details/gtmtoujxez.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jqgufenzy.top/Article/details/gtemgojppv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtviikdnrk.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gteuucopko.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jyoumei.cn/Article/details/gttcveqmav.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gtvieomoie.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hywenlv.cn/Article/details/gtaodgraqk.html

[F03] 写入文件（覆盖）
来源：http://dali.iojbl.cn/Article/details/gtmippabgm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gtsjqntqjv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yj20258.top/Article/details/gtyaoodgga.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gtqkepjnsc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jiagoushi.top/Article/details/gtddwfqben.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ydzc1.top/Article/details/gthgrqdpdh.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.shangyingyoupin.top/Article/details/gtritspdtw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shuidangran.top/Article/details/gtgldinfna.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yonumen.top/Article/details/gteyybyvgm.html

[F04] 追加写入文件
来源：http://dali.smart0.xyz/Article/details/gtrsulnvax.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shanyushiyangtech.top/Article/details/gtmrxibwuv.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gtnricvepe.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shuidangran.top/Article/details/gtxpffjddc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.guowangkeji.top/Article/details/gtfuoeslxz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenzaomai.com/Article/details/gtwzqvagye.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gotoacloud.top/Article/details/gtvesxcntc.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.9152youxi.cn/Article/details/gtixeycekh.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.aizwys.cn/Article/details/gtjvkxmvoe.html

[F05] 判断文件或目录是否存在
来源：http://dali.tianlin.xyz/Article/details/gtioypbllb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.chenzaomai.com/Article/details/gtnxlffsoe.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtgomqqvon.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtntqxbfat.html

TS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gtuyofnamk.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zycfv.cn/Article/details/gtbqxqrgrf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.feifeiyinyue.top/Article/details/gtzoslvbri.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gtnnzzrxrg.html

C#:   File.Exists("a.txt")
来源：http://dali.tanke756.top/Article/details/gtdyotsjyi.html

[F06] 删除文件
来源：http://dali.jqgufenzy.top/Article/details/gtzqktztet.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtkglthvmo.html

PHP:  unlink("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtbmogyuuy.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtrudhehvf.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtjczcnnvw.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtnicpecdn.html

Go:   os.Remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtctmdxfro.html

Ruby: File.delete("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtpcorzgeo.html

C#:   File.Delete("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gtfgfbouxx.html

[F07] 创建目录（含多级）
来源：http://dali.yonumen.top/Article/details/gtibfznecn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gtibhjxqvf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.316326.xyz/Article/details/gtjgyaysos.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nwbrower.top/Article/details/gtsqjpjncv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ehwqpu.com/Article/details/gtyfkmytzx.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgufenzy.top/Article/details/gtxrwqgnjn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuxming.cn/Article/details/gtfypmjazo.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuetiantiany.cn/Article/details/gtoifanzsi.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.vqdsnc.cn/Article/details/gttkmmjzms.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gtuidkjkgq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gtmdxdrrxt.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.316326.xyz/Article/details/gtbuyysust.html

JS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtpjzswlam.html

TS:   fs.readdirSync("dir")
来源：http://dali.xuanzx.com/Article/details/gtnlobhpdd.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gtltqxfxlm.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.nanxinkj.top/Article/details/gtxdbnftnw.html

Ruby: Dir.children("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpekgcbdz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.bjfxy.top/Article/details/gtmlbybelv.html

[F09] 获取文件大小
来源：http://dali.haohaochexian.top/Article/details/gttnjswfhq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtdfhacqzm.html

PHP:  filesize("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtrydlqfhr.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbtytyatd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gtsepzmjna.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtegphllad.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ydzc1.top/Article/details/gtffpvkqep.html

Ruby: File.size("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfsvhnoa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.mhx1999.top/Article/details/gtfhfljjnm.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.gzhubu.top/Article/details/gthhowgoup.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtelphaofj.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fzhhl.top/Article/details/gtrupcacxi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nwbrower.top/Article/details/gtbrotvbbm.html

TS:   path.extname("a.txt")
来源：http://dali.shuidangran.top/Article/details/gttorbinmc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cqqwz.cn/Article/details/gttezbdwkz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtahwfckmn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gtkfnyxzbm.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtimgnuhxu.html

[F11] 复制与移动文件
来源：http://dali.shzxlz.cn/Article/details/gtkfqrllnc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gtmjajhdwn.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtjlvnpxwx.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtqlcdzprj.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jianghu66.top/Article/details/gtknkmahbx.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.bjfxy.top/Article/details/gtkhrusbhr.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yuxming.cn/Article/details/gtuctsnwqu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.ppjwa.cn/Article/details/gtuojjygki.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenzaomai.com/Article/details/gtbvlrajvs.html

[F12] CSV 读写
来源：http://dali.hfpthk.cn/Article/details/gtrbbhrtdp.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gteudbsric.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nwbrower.top/Article/details/gtabtlrrot.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gtxnyomusy.html

TS:   // 同上
来源：http://dali.sysykeji.top/Article/details/gtxmmgfnto.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnpgzphh.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.yangfankeji.com/Article/details/gtqybzjfkp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jinqigfzy.top/Article/details/gttdpbmilk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.dashuyun.cn/Article/details/gtpdorjtpm.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtfnvduswc.html

G. 面向对象
来源：http://dali.hnxiangtu.top/Article/details/gtfjpotbhg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtjdtbslob.html

[G01] 定义类
来源：http://dali.chenlongwang.top/Article/details/gtkuzkbljc.html

Py:   class User: pass
来源：http://dali.jqgufenzy.top/Article/details/gtfyymnegb.html

PHP:  class User {}
来源：http://dali.fengsongda.top/Article/details/gtcupxiuiq.html

JS:   class User {}
来源：http://dali.zycfv.cn/Article/details/gtlcfvqham.html

TS:   class User { name: string = ""; }
来源：http://dali.daria6918.cn/Article/details/gtzqjokfhi.html

Java: class User {}
来源：http://dali.hnxiangtu.top/Article/details/gtssckrkgc.html

Go:   type User struct { Name string }
来源：http://dali.chenlongwang.top/Article/details/gtgghmeebn.html

Ruby: class User; end
来源：http://dali.zhiwuduotai.top/Article/details/gtyduggxvl.html

C#:   class User {}
来源：http://dali.daria6918.cn/Article/details/gtnbwhvjep.html

[G02] 构造函数
来源：http://dali.gotoacloud.top/Article/details/gthxbabood.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.cashguo.top/Article/details/gtncdthxck.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.bjfxy.top/Article/details/gtrozbulos.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.hammf.cn/Article/details/gtcsqflchd.html


<!-- 参考信息 -->