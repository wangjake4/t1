代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yj20258888.top/Article/details/gtnpjfcaqz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlchkaci.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zdqjudy.top/Article/details/gtjepgngxl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gttlbsjcia.html

[E02] 重复字符串
来源：http://dali.shzxlz.cn/Article/details/gthriwulxe.html

Py:   "ab" * 3
来源：http://dali.xylfe.cn/Article/details/gtsembcpvp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.9152youxi.cn/Article/details/gtmnlcphua.html

JS:   "ab".repeat(3)
来源：http://dali.tianlin.xyz/Article/details/gtlxkhwoxu.html

TS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gtmocvzcwg.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtclfqrixp.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gtdtuxnbld.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtyqzuscpd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.cashguo.top/Article/details/gtikzhhkde.html

[E03] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gtxmdcaqer.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.pycfn.com/Article/details/gtywrbfhzk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nanxinkj.top/Article/details/gttnssuoxz.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtbrjbfgaw.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gtjbhvkihk.html

Java: s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtoclfuiwb.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.shzxlz.cn/Article/details/gtneobtptg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtnxedxmee.html

C#:   s.Substring(1, 3)
来源：http://dali.daria6918.cn/Article/details/gtnbnatpod.html

[E04] 查找子串位置
来源：http://dali.yongpay.top/Article/details/gtbpnribtb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jiagoushi.top/Article/details/gtaylczbqm.html

PHP:  strpos($s, "x");
来源：http://dali.jqgufenzy.top/Article/details/gtnfryxtfo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tanke756.top/Article/details/gtdzdcfskm.html

TS:   s.indexOf("x")
来源：http://dali.zycfv.cn/Article/details/gtgbojolwq.html

Java: s.indexOf("x")
来源：http://dali.tian-w.cn/Article/details/gtoktmdrrx.html

Go:   strings.Index(s, "x")
来源：http://dali.zhiwuduotai.top/Article/details/gtorcuohyl.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtohzemdgr.html

C#:   s.IndexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtxhvvknlw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ppjwa.cn/Article/details/gtzzgwaksr.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhiwuduotai.top/Article/details/gtjqenimbo.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgxgoezl.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gtudqxlely.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhongyouzk.top/Article/details/gtkxzwshdg.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yongpay.top/Article/details/gtwuqjhkda.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jyoumei.cn/Article/details/gthwjdtirx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gtbmellllv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shzxlz.cn/Article/details/gtqdqmruqg.html

[E06] 替换子串
来源：http://dali.chenjidiqi.icu/Article/details/gtxeggmbhf.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.daria6918.cn/Article/details/gtzaiexuul.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yonumen.top/Article/details/gtwhkyjksz.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gtkgwyqouh.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtxuibvmry.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtsdydczrr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.birdmap.top/Article/details/gtfbxlarzi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.shuidangran.top/Article/details/gthfieworv.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtaetgjieq.html

[E07] 按分隔符拆分
来源：http://dali.kuanghao11.cn/Article/details/gtgechttxl.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.zhixingplan.top/Article/details/gtwvowtwkr.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ppjwa.cn/Article/details/gtdizsrnzv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aibaodan.cn/Article/details/gtvfvddewr.html

TS:   s.split(",")
来源：http://dali.jinqigfzy.top/Article/details/gtknqkrlci.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.redwolf501.top/Article/details/gtcsbqdbjk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.fengsongda.top/Article/details/gtvbaeoqfu.html

Ruby: s.split(",");  s.split
来源：http://dali.yj20258888.top/Article/details/gtjfutiqky.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.tianlin.xyz/Article/details/gtkjyhnwkn.html

[E08] 数组按分隔符合并
来源：http://dali.ivvv.top/Article/details/gtrzmfbkco.html

Py:   ",".join(items)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfbzkcymw.html

PHP:  implode(",", $items);
来源：http://dali.svipenyu.cn/Article/details/gtrxnurnhe.html

JS:   items.join(",")
来源：http://dali.yonumen.top/Article/details/gtpwshvreh.html

TS:   items.join(",")
来源：http://dali.pycfn.com/Article/details/gtlttexblh.html

Java: String.join(",", items)
来源：http://dali.ppjwa.cn/Article/details/gtkorbxuvc.html

Go:   strings.Join(items, ",")
来源：http://dali.ybcxt.top/Article/details/gtlclzmxce.html

Ruby: items.join(",")
来源：http://dali.shangyingyoupin.top/Article/details/gtkmhlcpeo.html

C#:   string.Join(",", items)
来源：http://dali.wangshuangyany.cn/Article/details/gtqmxcbgah.html

[E09] 去除所有空白字符
来源：http://dali.nwbrower.top/Article/details/gtykivkfbc.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.pengpengdd.cyou/Article/details/gtegddyrqs.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.mhx1999.top/Article/details/gtmahjsiud.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.fzhhl.top/Article/details/gtxohmynvt.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yongpay.top/Article/details/gtufynvcfd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yueranfly.top/Article/details/gtfvtbsmrq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.wangdashe.top/Article/details/gtgqnxsric.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yongpay.top/Article/details/gtuhowzxfo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.wangdashe.top/Article/details/gtgznbokyy.html

[E10] 左侧补零 / 定长填充
来源：http://dali.haohaochexian.top/Article/details/gtboidbihn.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.tianlin.xyz/Article/details/gttmukrmbf.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.zhengqikj.top/Article/details/gtpnrgxhtg.html

JS:   "7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtwnngmuqh.html

TS:   "7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gteribzpti.html

Java: String.format("%03d", 7)
来源：http://dali.ybcxt.top/Article/details/gtylbisejb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtloeggyet.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gtffvqdvid.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmqsdypz.html

[E11] 反转字符串
来源：http://dali.c1oappe.top/Article/details/gtwvblzpuy.html

Py:   s[::-1]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxdjyfizi.html

PHP:  strrev($s);
来源：http://dali.0kj1m.cn/Article/details/gtknhatagu.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gtwpmgtafu.html

TS:   [...s].reverse().join("")
来源：http://dali.cucudq.cn/Article/details/gtonspgjna.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xinyue.icu/Article/details/gtpxpsxgfy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zycfv.cn/Article/details/gtooquetvz.html

Ruby: s.reverse
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvariieh.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hnxiangtu.top/Article/details/gtqyjbawsb.html

[E12] 统计某字符出现次数
来源：http://dali.yueranfly.top/Article/details/gtmflqodat.html

Py:   s.count("a")
来源：http://dali.hysaishi.cn/Article/details/gttprhcnmi.html

PHP:  substr_count($s, "a");
来源：http://dali.svipenyu.cn/Article/details/gtinxhgdyz.html

JS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtersumjkb.html

TS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gtkjndnqpr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jiagoushi.top/Article/details/gtzvtjakzg.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gtrzzifrbe.html

Ruby: s.count("a")
来源：http://dali.ydzc1.top/Article/details/gtkanqovek.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shuidangran.top/Article/details/gtoutthlcn.html

[E13] 逐字符遍历
来源：http://dali.ydzc1.top/Article/details/gtpnpooxnp.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gtheyfrrxd.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xinyue.icu/Article/details/gthxinyggz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.cqqwz.cn/Article/details/gtrttmvpwd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gtcnuiouqt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlnncrcta.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtkdusprur.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ehwqpu.com/Article/details/gthbswwwtp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cucudq.cn/Article/details/gtmznwtalu.html

[E14] URL 编码与 Base64
来源：http://dali.xziqi.cn/Article/details/gtnfrrkwxc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhijiandao.cn/Article/details/gtlqqfeqyk.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gtymclwgay.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.cqqwz.cn/Article/details/gtoyawhzpy.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sweek.top/Article/details/gtxvbgcevv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.svipenyu.cn/Article/details/gtmisrbgvs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.daria6918.cn/Article/details/gtkcodzrdw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yueranfly.top/Article/details/gtbjmjbzbk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yonumen.top/Article/details/gtrlyptxmc.html

[E15] HTML 转义 / 反转义
来源：http://dali.pycfn.com/Article/details/gtpvcdlhzp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jqgufenzy.top/Article/details/gtcwadsidx.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gtbsginnzb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cdnleiting.top/Article/details/gtufcyyqep.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nanxuanxn.top/Article/details/gtrkthqzjp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.pengpengdd.cyou/Article/details/gtkcoeleaf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtbgnvfymo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.gogol.net.cn/Article/details/gtvnrtsxky.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jlsjyb.cn/Article/details/gtxznghhll.html

[E16] 数字千分位
来源：http://dali.tianlin.xyz/Article/details/gtvsuzaqfg.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gtjtnxupyc.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gtqrgzgyac.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.svipenyu.cn/Article/details/gtknqaetha.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xuetiantiany.cn/Article/details/gtrmllxuif.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.zhoulong.xyz/Article/details/gtekughimf.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zdqjudy.top/Article/details/gtnkzworvb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuanzhike.top/Article/details/gtpmvmqdsi.html

C#:   1234567.ToString("N0")
来源：http://dali.xuetiantiany.cn/Article/details/gtsffqxzia.html

[E17] 首字母大写
来源：http://dali.yuxming.cn/Article/details/gtxszmhvip.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhijiandao.cn/Article/details/gtrtzetkze.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hongshengwenyu.top/Article/details/gtqildghlx.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgjhwzlz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.birdmap.top/Article/details/gtscjoqoqh.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dianchejie.cn/Article/details/gtjbjbropb.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guowangkeji.top/Article/details/gtzznoiudc.html

Ruby: s.capitalize
来源：http://dali.aizwys.cn/Article/details/gtlnxiszsn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jlsjyb.cn/Article/details/gtdmpymqga.html

[E18] 模板占位符替换
来源：http://dali.ppjwa.cn/Article/details/gtuvahtpqs.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zycfv.cn/Article/details/gtzmfgrjix.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hnxiangtu.top/Article/details/gtdxfayxqh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtkddtncpj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtydnxixdn.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sysykeji.top/Article/details/gtpurwyasn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sufxvd.cn/Article/details/gtajkqudpu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.sysykeji.top/Article/details/gtaezbmfcr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlujhzgws.html

[E19] 多行文本按行拆分
来源：http://dali.jqgfzy.top/Article/details/gtymgcqciw.html

Py:   s.splitlines()
来源：http://dali.zycfv.cn/Article/details/gtvjcdyntn.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtggvadmzv.html

JS:   s.split(/\r?\n/)
来源：http://dali.guowangkeji.top/Article/details/gtjzksqzpy.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gtmqisrnpv.html

Java: s.lines().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtgxrhymgo.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhiwuduotai.top/Article/details/gteidxmibw.html

Ruby: s.lines
来源：http://dali.zdqjudy.top/Article/details/gtjnqnptpr.html

C#:   s.Split('\n')
来源：http://dali.zhixingplan.top/Article/details/gtukpfzssg.html

[E20] 判断字符串是否为空
来源：http://dali.ivvv.top/Article/details/gtnhluqyai.html

Py:   if not s:
来源：http://dali.bjfxy.top/Article/details/gtlnpgtxth.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.ybcxt.top/Article/details/gtbmkjeiyi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.pycfn.com/Article/details/gtimtkymgu.html

TS:   if (s === "") {}
来源：http://dali.hnqzz.top/Article/details/gtednhrusm.html

Java: if (s.isEmpty()) {}
来源：http://dali.pycfn.com/Article/details/gtblutchrp.html

Go:   if s == "" {}
来源：http://dali.jqgfzy.top/Article/details/gtiacrllxp.html

Ruby: if s.empty?
来源：http://dali.aizwys.cn/Article/details/gtooceoiir.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jqgfzy.top/Article/details/gtdxmaivhd.html

[E21] 超长截断加省略号
来源：http://dali.hywenlv.cn/Article/details/gthmfzusln.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yangfankeji.com/Article/details/gtanpnhqyi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtndndqvse.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.haohaochexian.top/Article/details/gtnjdhqlzd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gtewqtcmre.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gogol.net.cn/Article/details/gtfvtgzrid.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.yueranfly.top/Article/details/gtjlgnegip.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtytluxcem.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.pengpengdd.cyou/Article/details/gtihmzylkl.html

[E22] 字节长度与字符长度
来源：http://dali.fzhhl.top/Article/details/gtwwkrcpml.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.316326.xyz/Article/details/gtyqmgjbkr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.fzhhl.top/Article/details/gtdezhfdbl.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yongpay.top/Article/details/gtnlxduqpi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.0kj1m.cn/Article/details/gtjpwfipny.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtldazgzxj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gtmardmemk.html

Ruby: s.bytesize;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtmiljalmc.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.xinyue.icu/Article/details/gtdgdnklzo.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtnayxgdme.html

F. 文件与目录
来源：http://dali.birdmap.top/Article/details/gthrgivreh.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqutgbfn.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gtyigjgkdq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gtbvshcfyy.html

PHP:  file_get_contents("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gthloydpay.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.meibo888.top/Article/details/gtsaxlkyoj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtnsexufvt.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gtislqfwco.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cheryme.top/Article/details/gtncnpegsq.html

Ruby: File.read("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gteagvbaio.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guannengcc.top/Article/details/gtlxkkekol.html

[F02] 逐行读取文件
来源：http://dali.yj202588.top/Article/details/gtynuiiouk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hfpthk.cn/Article/details/gtvivxoxzj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.wangdashe.top/Article/details/gtjawycymd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj20258888.top/Article/details/gtavlatyhu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hysaishi.cn/Article/details/gtxrobjnoq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.xylfe.cn/Article/details/gtizxkcuug.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yangfankeji.com/Article/details/gtcsdefoiw.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnxiangtu.top/Article/details/gtdnroylxy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfjjemunx.html

[F03] 写入文件（覆盖）
来源：http://dali.316326.xyz/Article/details/gtadstwplm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xinyue.icu/Article/details/gtqcloaari.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xziqi.cn/Article/details/gtpesieehs.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtftostjsh.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtfywmdozx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yanxiufei.cn/Article/details/gtedfcgahw.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.tanke756.top/Article/details/gtwpobzjya.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigufen.top/Article/details/gtfmcpqvgu.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlirlexj.html

[F04] 追加写入文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhzisnqg.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cheryme.top/Article/details/gtnoouczpa.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.sxryk.cn/Article/details/gtseouklnl.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gtdyydiuxw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gtxcgxtryj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daria6918.cn/Article/details/gttiusfeff.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuanzx.com/Article/details/gtwdsxzceh.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.andypj.xyz/Article/details/gtrhpwrygo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhijiandao.cn/Article/details/gtqxboqwir.html

[F05] 判断文件或目录是否存在
来源：http://dali.xziqi.cn/Article/details/gtacpcycqv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhoulong.xyz/Article/details/gtcgvpoarl.html

PHP:  file_exists("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtwvkbbfuf.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtomhimest.html

TS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gtgkkbmuoo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gtpddlaele.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hfpthk.cn/Article/details/gtvxjiiibz.html

Ruby: File.exist?("a.txt")
来源：http://dali.cheryme.top/Article/details/gtimpeyfez.html

C#:   File.Exists("a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtbcixmlzy.html

[F06] 删除文件
来源：http://dali.shanyushiyangtech.top/Article/details/gthbpbdisc.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtvhtookhp.html

PHP:  unlink("a.txt");
来源：http://dali.pycfn.com/Article/details/gtkftawquf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtnezfpmnu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtxvlhdifh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gtteiuwjem.html

Go:   os.Remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtamcjajrd.html

Ruby: File.delete("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtwianuzqq.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuauyjwa.html

[F07] 创建目录（含多级）
来源：http://dali.gogol.net.cn/Article/details/gtmzqkosww.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtkidzddif.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.svipenyu.cn/Article/details/gtaevnruhs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gtywgtbxfj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.shuidangran.top/Article/details/gtamwlvliv.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.guowangkeji.top/Article/details/gtovpcyixd.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.0kj1m.cn/Article/details/gtfpskabko.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.havefunace.top/Article/details/gtgaavmumk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhiwuduotai.top/Article/details/gtvimpyeve.html

[F08] 遍历目录
来源：http://dali.ivvv.top/Article/details/gtsrvskyvi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.meibo888.top/Article/details/gtglgtrqcg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.snrcjt.cn/Article/details/gtzacakjof.html

JS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gtevtihpnn.html

TS:   fs.readdirSync("dir")
来源：http://dali.c1oappe.top/Article/details/gtrwsyovvy.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.haohaochexian.top/Article/details/gtvfwqeobr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.shanyushiyangtech.top/Article/details/gtgroydaju.html

Ruby: Dir.children("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtkhrtunxx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtgvqbstiw.html

[F09] 获取文件大小
来源：http://dali.jinqigfzy.top/Article/details/gtmsmqhzts.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtqtjtntqn.html

PHP:  filesize("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gttebzsluu.html

JS:   fs.statSync("a.txt").size
来源：http://dali.gotoacloud.top/Article/details/gtejaapbyz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gogol.net.cn/Article/details/gtocmtmgbp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gtosopeakh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ehwqpu.com/Article/details/gterbolxoz.html

Ruby: File.size("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtnjrzrorf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.birdmap.top/Article/details/gtclbgnocc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jqgfzy.top/Article/details/gtyaiaepnd.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aizwys.cn/Article/details/gtbgnwkniw.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtsfxfyvok.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtqlvfybba.html

TS:   path.extname("a.txt")
来源：http://dali.iojbl.cn/Article/details/gtgsaxgnxx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.andypj.xyz/Article/details/gtdmwevbyp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gttyuvxweu.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtkvtlegbd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtqgwigsiw.html

[F11] 复制与移动文件
来源：http://dali.ivvv.top/Article/details/gtdwtgwzrm.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cqqwz.cn/Article/details/gtlvzxggii.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ppjwa.cn/Article/details/gtqtgcleky.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zycfv.cn/Article/details/gtshcujrvt.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtjbdfxbjk.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tianlin.xyz/Article/details/gtldmqisph.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.fengsongda.top/Article/details/gtuoynugod.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gthaajadvn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.cashguo.top/Article/details/gtufrhgpve.html

[F12] CSV 读写
来源：http://dali.aizwys.cn/Article/details/gtwhflywvl.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhijiandao.cn/Article/details/gtdexsvuws.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cdnleiting.top/Article/details/gtgoxaitni.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gtkdckjzgu.html

TS:   // 同上
来源：http://dali.cdnleiting.top/Article/details/gttwqlazea.html


<!-- 参考信息 -->