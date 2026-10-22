代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aibaodan.cn/Article/details/gtvvrmieyz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.dianchejie.cn/Article/details/gtijfdyffc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gtevcmzpez.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yanxiufei.cn/Article/details/gtlvtcjbxh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jyoumei.cn/Article/details/gtvkskitwl.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.bjfxy.top/Article/details/gtlwlhigzn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jianghu66.top/Article/details/gtuqgtxzit.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtrvchhakf.html

[E02] 重复字符串
来源：http://dali.xylfe.cn/Article/details/gtctunxjvw.html

Py:   "ab" * 3
来源：http://dali.dashuyun.cn/Article/details/gtqriahdjz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guannengcc.top/Article/details/gtpxhhqcif.html

JS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtuielvfio.html

TS:   "ab".repeat(3)
来源：http://dali.jinqigfzy.top/Article/details/gtukcioeot.html

Java: "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttcfawyyx.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sweek.top/Article/details/gtlpkdvnod.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtlrzulyhv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxsqiyvf.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gtevpobrtm.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cashguo.top/Article/details/gtersbtzgy.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.smart0.xyz/Article/details/gtyloggywl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yanxiufei.cn/Article/details/gthocmajhq.html

TS:   s.slice(1, 4)
来源：http://dali.yj20258.top/Article/details/gtpjbkilto.html

Java: s.substring(1, 4)
来源：http://dali.sysykeji.top/Article/details/gtukkfecya.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.tanke756.top/Article/details/gtkgrxdqya.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.fengsongda.top/Article/details/gtzgwupdcm.html

C#:   s.Substring(1, 3)
来源：http://dali.316326.xyz/Article/details/gtwzssvhte.html

[E04] 查找子串位置
来源：http://dali.jinqigufen.top/Article/details/gtukdvvclq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtrgsjlufa.html

PHP:  strpos($s, "x");
来源：http://dali.yuanzhike.top/Article/details/gtwygiqzzg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sysykeji.top/Article/details/gtvinkkwaz.html

TS:   s.indexOf("x")
来源：http://dali.jqgufenzy.top/Article/details/gtwhbwmcqi.html

Java: s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtjzkghxic.html

Go:   strings.Index(s, "x")
来源：http://dali.pycfn.com/Article/details/gthpgreqzq.html

Ruby: s.index("x")
来源：http://dali.sysykeji.top/Article/details/gtzcmsenqw.html

C#:   s.IndexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gtadfkjcte.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.meibo888.top/Article/details/gtayasvhvm.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.cheryme.top/Article/details/gtsnknfrxp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ehwqpu.com/Article/details/gtrrkvtuuv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pengpengdd.cyou/Article/details/gttjsbnxnc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yueranfly.top/Article/details/gtyqxxqyll.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtekcvrypn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dianchejie.cn/Article/details/gtbcteplru.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aibaodan.cn/Article/details/gtohxmtapg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtmzdchnhb.html

[E06] 替换子串
来源：http://dali.meibo888.top/Article/details/gtjirpyjjg.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gtwoxmubqd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hammf.cn/Article/details/gtsdvvjavi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tian-w.cn/Article/details/gtqsiwmsrj.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yueranfly.top/Article/details/gthewzxxzm.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtyrgicakm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gtfhaeidsi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtcimgslcs.html

C#:   s.Replace("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gttljhlfzr.html

[E07] 按分隔符拆分
来源：http://dali.ybcxt.top/Article/details/gtdoycgavj.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.fzhhl.top/Article/details/gtdgtgxmkb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.tanke756.top/Article/details/gtlggsepwz.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.dianchejie.cn/Article/details/gtfjjnqbto.html

TS:   s.split(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtngxhblno.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.fengsongda.top/Article/details/gtzkfxusfm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hammf.cn/Article/details/gtqarqdzgs.html

Ruby: s.split(",");  s.split
来源：http://dali.vqdsnc.cn/Article/details/gtlyepbeqs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.gaohongyu789.top/Article/details/gtahcyitas.html

[E08] 数组按分隔符合并
来源：http://dali.pycfn.com/Article/details/gthdilfcol.html

Py:   ",".join(items)
来源：http://dali.gotoacloud.top/Article/details/gtixulupkb.html

PHP:  implode(",", $items);
来源：http://dali.kuanghao11.cn/Article/details/gtrrdpvgif.html

JS:   items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gthqvcrfdo.html

TS:   items.join(",")
来源：http://dali.cashguo.top/Article/details/gtmgismnoq.html

Java: String.join(",", items)
来源：http://dali.jqgfzy.top/Article/details/gthlehoywd.html

Go:   strings.Join(items, ",")
来源：http://dali.tian-w.cn/Article/details/gtwagkiqih.html

Ruby: items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtzylcddeh.html

C#:   string.Join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtgblgvoog.html

[E09] 去除所有空白字符
来源：http://dali.jqgufenzy.top/Article/details/gtqnbwirer.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pycfn.com/Article/details/gtegnywxcl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.svipenyu.cn/Article/details/gtpvpvkldh.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.wangdashe.top/Article/details/gtmkxlidpw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnacjvvvl.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gtbnovvyxq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.guowangkeji.top/Article/details/gtoqvmpbhd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgufenzy.top/Article/details/gtudoseyfp.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.zhengqikj.top/Article/details/gtnfxjvzer.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cashguo.top/Article/details/gtalikobms.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.smart0.xyz/Article/details/gtkyuswrjv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.havefunace.top/Article/details/gtqcxtdfiu.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtvdhruumh.html

TS:   "7".padStart(3, "0")
来源：http://dali.mhx1999.top/Article/details/gtvbwuuybe.html

Java: String.format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtenhwrhdn.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gtqaqifkbt.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.vqdsnc.cn/Article/details/gtazimtpmb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yonumen.top/Article/details/gtvmceivxv.html

[E11] 反转字符串
来源：http://dali.hysaishi.cn/Article/details/gtmijtwfbm.html

Py:   s[::-1]
来源：http://dali.ybcxt.top/Article/details/gttdkdcjrt.html

PHP:  strrev($s);
来源：http://dali.shzxlz.cn/Article/details/gtkzwfniqs.html

JS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gtckdqqppj.html

TS:   [...s].reverse().join("")
来源：http://dali.shangyingyoupin.top/Article/details/gtndtqriix.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guowangkeji.top/Article/details/gtsnxkzzzv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.tanke756.top/Article/details/gtxthwueum.html

Ruby: s.reverse
来源：http://dali.ppjwa.cn/Article/details/gtovagrhlb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.gogol.net.cn/Article/details/gtltslabps.html

[E12] 统计某字符出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlysjrmes.html

Py:   s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gtxrfxudwv.html

PHP:  substr_count($s, "a");
来源：http://dali.jqgufenzy.top/Article/details/gtjhgnhzsh.html

JS:   s.split("a").length - 1
来源：http://dali.havefunace.top/Article/details/gtycwdject.html

TS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gtebdvqpng.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.birdmap.top/Article/details/gtbnadraid.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gtzozjlqbs.html

Ruby: s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtgvzoowkm.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nanxinkj.top/Article/details/gtsnzsxbvv.html

[E13] 逐字符遍历
来源：http://dali.jqgfzy.top/Article/details/gtimqstgic.html

Py:   for ch in s: print(ch)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotzvqgqi.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shangyingyoupin.top/Article/details/gtvuqehnnd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtdxzjqlwh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.andypj.xyz/Article/details/gtcuqcmfdl.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxinkj.top/Article/details/gtonmqkfwh.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtqbxmocls.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangdashe.top/Article/details/gtprrihtmg.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.fengsongda.top/Article/details/gtonzslygx.html

[E14] URL 编码与 Base64
来源：http://dali.hywenlv.cn/Article/details/gtokjgwdcz.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.tian-w.cn/Article/details/gtezllyipy.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gtnmyhmfqk.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.redwolf501.top/Article/details/gtgqyddozg.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jyoumei.cn/Article/details/gtdjpwrdoo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hongshengwenyu.top/Article/details/gtkosvqvpi.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangdashe.top/Article/details/gtumbvovvw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guowangkeji.top/Article/details/gtvcxvkoom.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtkpjhrcru.html

[E15] HTML 转义 / 反转义
来源：http://dali.ehwqpu.com/Article/details/gtjzwwkcwd.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxuanxn.top/Article/details/gtfzkndgqc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xinyue.icu/Article/details/gtephmpjue.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtvdcquizr.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gtyjmlurpv.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenjidiqi.icu/Article/details/gtbpvduhip.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.jinqigufen.top/Article/details/gtguhwkboc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yanxiufei.cn/Article/details/gtvkxymrxm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenlongwang.top/Article/details/gtflqrirgn.html

[E16] 数字千分位
来源：http://dali.redwolf501.top/Article/details/gticoaqogp.html

Py:   f"{1234567:,}"
来源：http://dali.snrcjt.cn/Article/details/gttgvclnds.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdksrepp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cashguo.top/Article/details/gtwcwqjbmf.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gtgnyaqdvr.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj202588.top/Article/details/gtjgsibvas.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.0kj1m.cn/Article/details/gtnciqhuqa.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.hysaishi.cn/Article/details/gtmihiehgf.html

C#:   1234567.ToString("N0")
来源：http://dali.zycfv.cn/Article/details/gtokijskve.html

[E17] 首字母大写
来源：http://dali.gzhubu.top/Article/details/gtiudfugup.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gtsygssmfi.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.ppjwa.cn/Article/details/gthmtiszwj.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtyfxkhuvu.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gtnmsyhoug.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.wangdashe.top/Article/details/gtasndqowg.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvykwjkx.html

Ruby: s.capitalize
来源：http://dali.feifeiyinyue.top/Article/details/gtgxrxsknu.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sysykeji.top/Article/details/gtacsgykyb.html

[E18] 模板占位符替换
来源：http://dali.zhoulong.xyz/Article/details/gtzotnswvd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tianlin.xyz/Article/details/gtznbwmbrz.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gtzjygtuaf.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtohfhgpmd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtmzcumzox.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jinqigfzy.top/Article/details/gtctlrlfey.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gtfurtdvdg.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.tian-w.cn/Article/details/gttlvyvkou.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.sysykeji.top/Article/details/gtnmaihxhr.html

[E19] 多行文本按行拆分
来源：http://dali.sysykeji.top/Article/details/gtbpnigxya.html

Py:   s.splitlines()
来源：http://dali.quarkkingdee.top/Article/details/gtnwknvvhx.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nwbrower.top/Article/details/gtauuvqzhb.html

JS:   s.split(/\r?\n/)
来源：http://dali.yvedp.cn/Article/details/gticvzdetk.html

TS:   s.split(/\r?\n/)
来源：http://dali.daxiang520.top/Article/details/gtbfutehdd.html

Java: s.lines().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzudpjut.html

Go:   strings.Split(s, "\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtrpurjpsm.html

Ruby: s.lines
来源：http://dali.zhijiandao.cn/Article/details/gtyrpllggk.html

C#:   s.Split('\n')
来源：http://dali.shuidangran.top/Article/details/gtiowuafyf.html

[E20] 判断字符串是否为空
来源：http://dali.cheryme.top/Article/details/gtqzavgofn.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gtrmwaecbd.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuulwizy.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.316326.xyz/Article/details/gtyakfyfkr.html

TS:   if (s === "") {}
来源：http://dali.zycfv.cn/Article/details/gtitybxcru.html

Java: if (s.isEmpty()) {}
来源：http://dali.yongpay.top/Article/details/gtikvnodcq.html

Go:   if s == "" {}
来源：http://dali.fengsongda.top/Article/details/gtbopsjass.html

Ruby: if s.empty?
来源：http://dali.cashguo.top/Article/details/gtpsjpiahx.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gtesqlllop.html

[E21] 超长截断加省略号
来源：http://dali.fzhhl.top/Article/details/gtxaogjifb.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.feifeiyinyue.top/Article/details/gtyjelxdlt.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtqvxedktr.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sweek.top/Article/details/gtxoazhghc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gtompyposd.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gtbwfcavpp.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.gzhubu.top/Article/details/gtapqubdah.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtctinhshr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhiwuduotai.top/Article/details/gttmykgzij.html

[E22] 字节长度与字符长度
来源：http://dali.ppjwa.cn/Article/details/gtrwkprake.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.iojbl.cn/Article/details/gtdogegfcl.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtpszuezwo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gtmwshpzcn.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gtoboefwih.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jqgfzy.top/Article/details/gtdfvdkgyd.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gtzzlcvcle.html

Ruby: s.bytesize;  s.length
来源：http://dali.mhx1999.top/Article/details/gtaykrdrkr.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dianchejie.cn/Article/details/gtikjvjint.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtvohbffzu.html

F. 文件与目录
来源：http://dali.sysykeji.top/Article/details/gtoiozypcw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtoyfjnbmy.html

[F01] 读取整个文件
来源：http://dali.hysaishi.cn/Article/details/gtbxgudybz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hammf.cn/Article/details/gtpiqhmjsk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gthsljsbdn.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.smart0.xyz/Article/details/gtxtubdexc.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtqsrbatvf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtzxfvtvan.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gtyxiemgiw.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtbinityzx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.fengsongda.top/Article/details/gtqxhavhfr.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gtlopvyzxi.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.iojbl.cn/Article/details/gttsrzivee.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.smart0.xyz/Article/details/gtocqmhoet.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.guowangkeji.top/Article/details/gtgjcdhviu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.meibo888.top/Article/details/gtzffvhtpy.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.chenlongwang.top/Article/details/gtqqpiaszy.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenlongwang.top/Article/details/gtffufcjbf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.aibaodan.cn/Article/details/gtwpfsuxmm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gaohongyu789.top/Article/details/gtwomburkf.html

[F03] 写入文件（覆盖）
来源：http://dali.jiagoushi.top/Article/details/gtkgycybmh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.aibaodan.cn/Article/details/gtdkurceck.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtebhsvjzj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.havefunace.top/Article/details/gtdnhjknys.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gtgmsvmzrc.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cucudq.cn/Article/details/gtyemsjyyb.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.hammf.cn/Article/details/gtzzzsmcjq.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.quarkkingdee.top/Article/details/gtpqvjtfmv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.aizwys.cn/Article/details/gtyowyokpf.html

[F04] 追加写入文件
来源：http://dali.zhoulong.xyz/Article/details/gtwgzdudot.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxgbatjg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.316326.xyz/Article/details/gtpxbzbivn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtezftcfku.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shangyingyoupin.top/Article/details/gtrkwgfail.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jianghu66.top/Article/details/gtvzgiksbn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ybcxt.top/Article/details/gtmwhwmomr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.cucudq.cn/Article/details/gtmgeqoexu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.wangshuangyany.cn/Article/details/gtkubtnhza.html

[F05] 判断文件或目录是否存在
来源：http://dali.jiagoushi.top/Article/details/gtgcmcerum.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ehwqpu.com/Article/details/gtqzyiuquo.html

PHP:  file_exists("a.txt");
来源：http://dali.smart0.xyz/Article/details/gtikziepbl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtjrsvfodo.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqikmyyw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.zdqjudy.top/Article/details/gtmqdysgzx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gtsobdvycm.html

Ruby: File.exist?("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gtgjcfbkgv.html

C#:   File.Exists("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkafhwkfl.html

[F06] 删除文件
来源：http://dali.aibaodan.cn/Article/details/gtbfcgwjqu.html

Py:   os.remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gtmzpsokwf.html

PHP:  unlink("a.txt");
来源：http://dali.yj202588.top/Article/details/gtaywlxdar.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gthbyvrozn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gttwxcbsmm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.ydzc1.top/Article/details/gtatniyvlf.html

Go:   os.Remove("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtinplvggh.html

Ruby: File.delete("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtacnlkeoj.html

C#:   File.Delete("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtpmlfrpte.html

[F07] 创建目录（含多级）
来源：http://dali.yanxiufei.cn/Article/details/gttsxbtvks.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtccdzjhpr.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.9152youxi.cn/Article/details/gtgbvzjeal.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gtbjbbxsor.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.aizwys.cn/Article/details/gterieftqq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.gotoacloud.top/Article/details/gtbixxmpxf.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.daxiang520.top/Article/details/gtvqihrlxf.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yvedp.cn/Article/details/gtwmpmmapn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gttibtfrwf.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gtimyjqwel.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.daria6918.cn/Article/details/gtfqhuiqcp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ybcxt.top/Article/details/gtniewqald.html

JS:   fs.readdirSync("dir")
来源：http://dali.chenjidiqi.icu/Article/details/gtxkxamzyo.html

TS:   fs.readdirSync("dir")
来源：http://dali.cqqwz.cn/Article/details/gtkxrxxfvb.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtsccwqkgb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jianghu66.top/Article/details/gtyizzgflj.html

Ruby: Dir.children("dir")
来源：http://dali.9152youxi.cn/Article/details/gtkgyeksgf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gthzcbkshw.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gtxdzkejzg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtwxhyndlc.html

PHP:  filesize("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gtaffyxlhg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.hysaishi.cn/Article/details/gtxrpymjes.html

TS:   fs.statSync("a.txt").size
来源：http://dali.feifeiyinyue.top/Article/details/gtdhynluhg.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuxming.cn/Article/details/gtpvsnhoap.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gtiqyjobvr.html

Ruby: File.size("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtchhiyifd.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiajlbapi.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangtech.top/Article/details/gtyemkhfxn.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtbhtjmdhu.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtfeyhlamr.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.sxryk.cn/Article/details/gtefqugalc.html

TS:   path.extname("a.txt")
来源：http://dali.havefunace.top/Article/details/gtquopacmn.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.shanyushiyangtech.top/Article/details/gtzltetmco.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.mhx1999.top/Article/details/gtoxflxfco.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtagaagbva.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.havefunace.top/Article/details/gtvssiqhbl.html

[F11] 复制与移动文件
来源：http://dali.zdqjudy.top/Article/details/gtsoztvttd.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtgczxafoj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhengqikj.top/Article/details/gtjqctjeun.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hywenlv.cn/Article/details/gtidviyero.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.9152youxi.cn/Article/details/gtodxkvaqv.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gtnejbdfbf.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pengpengdd.cyou/Article/details/gtzuntcroe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258888.top/Article/details/gtnkdpypoh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dianchejie.cn/Article/details/gtydxjgnwd.html

[F12] CSV 读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnklclux.html


<!-- 参考信息 -->