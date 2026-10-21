代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gtyekulibt.html

[E03] 截取子串
来源：http://dali.yj202588.top/Article/details/gtwlvirnxy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.nanxinkj.top/Article/details/gtxxrfziey.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtwxlwbqdw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gogol.net.cn/Article/details/gtqvrixbra.html

TS:   s.slice(1, 4)
来源：http://dali.pycfn.com/Article/details/gtzdkcmzdb.html

Java: s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtucjdfoki.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gtwahxowfu.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cashguo.top/Article/details/gtsmpeghgm.html

C#:   s.Substring(1, 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdojblyzz.html

[E04] 查找子串位置
来源：http://dali.ydzc1.top/Article/details/gtmkctnrja.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj202588.top/Article/details/gtxttsekcd.html

PHP:  strpos($s, "x");
来源：http://dali.zhiwuduotai.top/Article/details/gtwuaxwsym.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuxming.cn/Article/details/gtzcuvmomd.html

TS:   s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gtpzsjzkbx.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtwjtujigi.html

Go:   strings.Index(s, "x")
来源：http://dali.cheryme.top/Article/details/gtihpgpghm.html

Ruby: s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gturiowddi.html

C#:   s.IndexOf("x")
来源：http://dali.ybcxt.top/Article/details/gtdamyecoz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hywenlv.cn/Article/details/gtaumrrutf.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zdqjudy.top/Article/details/gtxlyinrlq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhixingplan.top/Article/details/gtrindeqda.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtwavqqeaq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhongyouzk.top/Article/details/gtflibtiub.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gtchscjuex.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuxlgygk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.xziqi.cn/Article/details/gtqcmkabvv.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.vqdsnc.cn/Article/details/gtrnahsasf.html

[E06] 替换子串
来源：http://dali.sweek.top/Article/details/gtcslxiyci.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.haohaochexian.top/Article/details/gtiivdjxfe.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.pengpengdd.cyou/Article/details/gtxrawwyre.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtuemqyjrz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtzntqyhrq.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gttfolyeom.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ydzc1.top/Article/details/gtmjkznotk.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yuanzhike.top/Article/details/gtvyhxeoac.html

C#:   s.Replace("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtyqytuqiu.html

[E07] 按分隔符拆分
来源：http://dali.zhengqikj.top/Article/details/gttvhdkhbd.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yongpay.top/Article/details/gtrqdgffep.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.jinqigufen.top/Article/details/gttkcjbirs.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.shuidangran.top/Article/details/gtbzwuvtzf.html

TS:   s.split(",")
来源：http://dali.zhengqikj.top/Article/details/gtxgdiigce.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ppjwa.cn/Article/details/gtcaucoocm.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.zdqjudy.top/Article/details/gtsswkhine.html

Ruby: s.split(",");  s.split
来源：http://dali.cashguo.top/Article/details/gteppfrqmd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yongpay.top/Article/details/gtbnfzjxdw.html

[E08] 数组按分隔符合并
来源：http://dali.c1oappe.top/Article/details/gthrsuvvcx.html

Py:   ",".join(items)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypnkmimw.html

PHP:  implode(",", $items);
来源：http://dali.daria6918.cn/Article/details/gtglckvgll.html

JS:   items.join(",")
来源：http://dali.meibo888.top/Article/details/gtucvplacq.html

TS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gtfqxhryag.html

Java: String.join(",", items)
来源：http://dali.wangdashe.top/Article/details/gtzgzehuvq.html

Go:   strings.Join(items, ",")
来源：http://dali.xylfe.cn/Article/details/gtekfcvdxj.html

Ruby: items.join(",")
来源：http://dali.sysykeji.top/Article/details/gtdhncgltj.html

C#:   string.Join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gtorlkrsfj.html

[E09] 去除所有空白字符
来源：http://dali.zdqjudy.top/Article/details/gtzbcxsgab.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.fzhhl.top/Article/details/gtpiojbgqw.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yongpay.top/Article/details/gtgpxkjthm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtixnmlxho.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xziqi.cn/Article/details/gtswljnroe.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtoasebxfq.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.quarkkingdee.top/Article/details/gtqoavddjq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yanxiufei.cn/Article/details/gtpsvgkjjh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.pengpengdd.cyou/Article/details/gtnbycohaa.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yanxiufei.cn/Article/details/gtqogigwty.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.fzhhl.top/Article/details/gtwwphrisk.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.mhx1999.top/Article/details/gtxjdrjbta.html

JS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gtsvmexucs.html

TS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtwkdjxhmq.html

Java: String.format("%03d", 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucmnvfaf.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.fengsongda.top/Article/details/gtxdhtszhm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gogol.net.cn/Article/details/gtfigddnjc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.quarkkingdee.top/Article/details/gtoqxhidww.html

[E11] 反转字符串
来源：http://dali.tian-w.cn/Article/details/gtsezqaiot.html

Py:   s[::-1]
来源：http://dali.shuidangran.top/Article/details/gtsytmgszc.html

PHP:  strrev($s);
来源：http://dali.smart0.xyz/Article/details/gtuaclusru.html

JS:   [...s].reverse().join("")
来源：http://dali.bjfxy.top/Article/details/gtbfaatnpa.html

TS:   [...s].reverse().join("")
来源：http://dali.pycfn.com/Article/details/gtpnzjvdmc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkbimbll.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.meibo888.top/Article/details/gthulztywk.html

Ruby: s.reverse
来源：http://dali.hfpthk.cn/Article/details/gtpbqreecu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhongyouzk.top/Article/details/gtbapsjqbb.html

[E12] 统计某字符出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gtxunzwpjc.html

Py:   s.count("a")
来源：http://dali.jianghu66.top/Article/details/gtbpqtzjbr.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gthvwnwmgd.html

JS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtqhsbjveq.html

TS:   s.split("a").length - 1
来源：http://dali.iojbl.cn/Article/details/gtanmxztng.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hnxiangtu.top/Article/details/gtstuyusth.html

Go:   strings.Count(s, "a")
来源：http://dali.316326.xyz/Article/details/gtplnpvazs.html

Ruby: s.count("a")
来源：http://dali.c1oappe.top/Article/details/gtwqtdwavo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cashguo.top/Article/details/gtsfdqxehi.html

[E13] 逐字符遍历
来源：http://dali.jiagoushi.top/Article/details/gtadctelme.html

Py:   for ch in s: print(ch)
来源：http://dali.jqgfzy.top/Article/details/gttfddblzt.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.haohaochexian.top/Article/details/gtwyphkbji.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtrzrauedu.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtslhcjxij.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jqgufenzy.top/Article/details/gtmjhftiye.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.sxryk.cn/Article/details/gtjgjarnkw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuysovou.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtbxjtmced.html

[E14] URL 编码与 Base64
来源：http://dali.xuanzx.com/Article/details/gtaniadoaw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenlongwang.top/Article/details/gtmxldykos.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.ybcxt.top/Article/details/gtelhipbho.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gtatrjxojd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.sweek.top/Article/details/gtnklrytja.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zdqjudy.top/Article/details/gtwckmqnqx.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.cheryme.top/Article/details/gtisjkpcxl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.andypj.xyz/Article/details/gtfknrdhop.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcoujvpiz.html

[E15] HTML 转义 / 反转义
来源：http://dali.0kj1m.cn/Article/details/gtccywizuj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.xuanzx.com/Article/details/gtmbugwuty.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ybcxt.top/Article/details/gtgyrymlth.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yanxiufei.cn/Article/details/gtmnhwaliq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtdxshdtfb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.gaohongyu789.top/Article/details/gtrvkbhsom.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.gzhubu.top/Article/details/gtdxlmqfcg.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gtqvqffxxn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.shuidangran.top/Article/details/gtetgqhlzi.html

[E16] 数字千分位
来源：http://dali.mhx1999.top/Article/details/gtmolwfrdq.html

Py:   f"{1234567:,}"
来源：http://dali.kuanghao11.cn/Article/details/gtmbcgdayk.html

PHP:  number_format(1234567);
来源：http://dali.hysaishi.cn/Article/details/gtjrjeblpo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gtjhdhuutu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jqgufenzy.top/Article/details/gtorwumpue.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258.top/Article/details/gtccekhngk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenlongwang.top/Article/details/gtoofanbnf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gtvjbaofol.html

C#:   1234567.ToString("N0")
来源：http://dali.meibo888.top/Article/details/gtehonbtmb.html

[E17] 首字母大写
来源：http://dali.gotoacloud.top/Article/details/gtdjpupcjt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhoulong.xyz/Article/details/gtcrwrnjor.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cqqwz.cn/Article/details/gthhmvxtse.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gtenjctzue.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzimlfxak.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.havefunace.top/Article/details/gtcvglwkjs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tianlin.xyz/Article/details/gtyhvyghbr.html

Ruby: s.capitalize
来源：http://dali.tanke756.top/Article/details/gtdzjaijka.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.smart0.xyz/Article/details/gtvmgkwbfh.html

[E18] 模板占位符替换
来源：http://dali.tian-w.cn/Article/details/gtelakjfbl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.guannengcc.top/Article/details/gtcaramgyb.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxensswh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gtueyyeqht.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtnipqvnmz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gtsrejvzcw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jqgfzy.top/Article/details/gttmgeaxrk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gtxzqnerug.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jinqigfzy.top/Article/details/gtngdlsfgc.html

[E19] 多行文本按行拆分
来源：http://dali.smart0.xyz/Article/details/gtxryzhdmq.html

Py:   s.splitlines()
来源：http://dali.cqqwz.cn/Article/details/gttntfvclf.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhiwuduotai.top/Article/details/gtgdsqodda.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtslbknllr.html

TS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtujumozyy.html

Java: s.lines().toList()
来源：http://dali.dianchejie.cn/Article/details/gtnjwxpqjh.html

Go:   strings.Split(s, "\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztwrfjtv.html

Ruby: s.lines
来源：http://dali.shzxlz.cn/Article/details/gtauyitkdw.html

C#:   s.Split('\n')
来源：http://dali.zhoulong.xyz/Article/details/gtwzfqffpj.html

[E20] 判断字符串是否为空
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttrwqcso.html

Py:   if not s:
来源：http://dali.quarkkingdee.top/Article/details/gtsebazbrp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yj20258888.top/Article/details/gtuokfjeyo.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yanxiufei.cn/Article/details/gtrihcgtfl.html

TS:   if (s === "") {}
来源：http://dali.gotoacloud.top/Article/details/gtegizklvk.html

Java: if (s.isEmpty()) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtveqhdsxn.html

Go:   if s == "" {}
来源：http://dali.zhengqikj.top/Article/details/gtljivweup.html

Ruby: if s.empty?
来源：http://dali.xylfe.cn/Article/details/gtxezsyrcv.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnqzz.top/Article/details/gtfhrjmbhi.html

[E21] 超长截断加省略号
来源：http://dali.zhiwuduotai.top/Article/details/gtprfwngns.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.ehwqpu.com/Article/details/gthqhcuvkn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtctivgdil.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.daria6918.cn/Article/details/gtowrcjoxu.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gthrcezvvg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtyliwtszm.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.kuanghao11.cn/Article/details/gtqfptqbjx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtmuqxfkkn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gtvwbcolxt.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gtsqwzhufj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtucbuwtzu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwijvvvt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtdmvgwhgx.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gteioctwzm.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jianghu66.top/Article/details/gtjuckpydb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj202588.top/Article/details/gtxxcowvdm.html

Ruby: s.bytesize;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gtuihliipe.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yj20258888.top/Article/details/gthzlobjoq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gttxugixns.html

F. 文件与目录
来源：http://dali.redwolf501.top/Article/details/gtmzibxmpd.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtalrdjdgi.html

[F01] 读取整个文件
来源：http://dali.fzhhl.top/Article/details/gtbdidcdni.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenlongwang.top/Article/details/gteudmbyes.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fzhhl.top/Article/details/gtkgsvjshu.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.quarkkingdee.top/Article/details/gtwgmlkgok.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gtqqcncyem.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtrmvpsaky.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shzxlz.cn/Article/details/gtzolkgiyr.html

Ruby: File.read("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtqpwaiute.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtrjdzpqko.html

[F02] 逐行读取文件
来源：http://dali.hysaishi.cn/Article/details/gtzjadvhbx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yonumen.top/Article/details/gtnejinsfm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtxcnxpkbq.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtqethewsd.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zdqjudy.top/Article/details/gtgsmfurnw.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yuxming.cn/Article/details/gtocykbvzg.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yvedp.cn/Article/details/gtecrqluus.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.snrcjt.cn/Article/details/gtnsoafyvq.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.guowangkeji.top/Article/details/gtqlkqyruz.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gtduvhtykp.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gtvoilglla.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.sweek.top/Article/details/gtlbdlkmml.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtaeffjndo.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtuayqpouo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sufxvd.cn/Article/details/gtmhghshut.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.zhongyouzk.top/Article/details/gtpschxipc.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sysykeji.top/Article/details/gtloisgopt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtvzlhudxt.html

[F04] 追加写入文件
来源：http://dali.cqqwz.cn/Article/details/gtsqmgqwct.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj202588.top/Article/details/gtfxqlehlr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhengqikj.top/Article/details/gtvrsgeyap.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fzhhl.top/Article/details/gtmfwsxzig.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtibemyvud.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gtfgcthjfh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.hywenlv.cn/Article/details/gtglqlerhm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfpswdqnv.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.c1oappe.top/Article/details/gtybwifyvj.html

[F05] 判断文件或目录是否存在
来源：http://dali.yonumen.top/Article/details/gtidqxhxkc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.wangdashe.top/Article/details/gtzawdalqr.html

PHP:  file_exists("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtaqlygudi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gttsvbmezl.html

TS:   fs.existsSync("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtowscpdcg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gthmsuyvhe.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.zhengqikj.top/Article/details/gtkverlums.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtwdffsoft.html

C#:   File.Exists("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtkpwdtewy.html

[F06] 删除文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclmzfelb.html

Py:   os.remove("a.txt")
来源：http://dali.cucudq.cn/Article/details/gtszzqsjgp.html

PHP:  unlink("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gtlsssrurw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.bjfxy.top/Article/details/gtrzytqbxz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtzfmtrnuc.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gtufuzbnso.html

Go:   os.Remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtkkmokicq.html

Ruby: File.delete("a.txt")
来源：http://dali.daxiang520.top/Article/details/gtzkgdxaup.html

C#:   File.Delete("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtldshrgyz.html

[F07] 创建目录（含多级）
来源：http://dali.daria6918.cn/Article/details/gtrfqxyrdi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gtxznljiqh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yanxiufei.cn/Article/details/gtkkdnherk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenjidiqi.icu/Article/details/gteernyscf.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqgvxwll.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yuxming.cn/Article/details/gtcwsrcnad.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gtoxarhoah.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.birdmap.top/Article/details/gtcujnymff.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.tianlin.xyz/Article/details/gtjkzxnato.html

[F08] 遍历目录
来源：http://dali.xziqi.cn/Article/details/gtwpylpqqf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.c1oappe.top/Article/details/gtpvvgltzr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnxiangtu.top/Article/details/gtfkoszdrs.html

JS:   fs.readdirSync("dir")
来源：http://dali.gotoacloud.top/Article/details/gtzqszgdku.html

TS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gtpwhhasfo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gtivslrjmr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.guannengcc.top/Article/details/gtxrrghqip.html

Ruby: Dir.children("dir")
来源：http://dali.0kj1m.cn/Article/details/gturxmmnax.html

C#:   Directory.GetFiles("dir")
来源：http://dali.guannengcc.top/Article/details/gtstseldqs.html

[F09] 获取文件大小
来源：http://dali.tian-w.cn/Article/details/gtqykdbcnx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtmigvrhts.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gtcqivrcbn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtbcpwwfpd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zycfv.cn/Article/details/gtydwleety.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtmzlyxtxz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.ehwqpu.com/Article/details/gtvdvynapy.html

Ruby: File.size("a.txt")
来源：http://dali.mhx1999.top/Article/details/gtglcxvuic.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqltjnovg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcahzavyg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtrgbaatwv.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cqqwz.cn/Article/details/gtmxvfnefi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gthpsyenkk.html

TS:   path.extname("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtptvjgxuo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.ehwqpu.com/Article/details/gtykwiyeta.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gtauuwpmpf.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yueranfly.top/Article/details/gtnmrcazhh.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtlznozamt.html

[F11] 复制与移动文件
来源：http://dali.jianghu66.top/Article/details/gtbnfotcnv.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gtpaprgwib.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.mhx1999.top/Article/details/gtuyglvdlg.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gtxzvtynia.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtvjnyitql.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.redwolf501.top/Article/details/gtinxzosqo.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xziqi.cn/Article/details/gtgudtmqcm.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtczzykgkp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhongyouzk.top/Article/details/gtxtcvxseu.html

[F12] CSV 读写
来源：http://dali.ydzc1.top/Article/details/gtzvyrummq.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinqigfzy.top/Article/details/gtgarzqavr.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gtrepmaecy.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.shzxlz.cn/Article/details/gtoowdqzzy.html

TS:   // 同上
来源：http://dali.cqqwz.cn/Article/details/gtcnwkwuxy.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.xziqi.cn/Article/details/gtsgdhpnfr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gtppumuegq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.9152youxi.cn/Article/details/gtdhewclyk.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.sufxvd.cn/Article/details/gtcbiyzwfn.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtwodzuqap.html

G. 面向对象
来源：http://dali.zhiwuduotai.top/Article/details/gtvphzshwv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtixxmuzyt.html

[G01] 定义类
来源：http://dali.cdnleiting.top/Article/details/gtlzuqsbeo.html

Py:   class User: pass
来源：http://dali.zycfv.cn/Article/details/gtaltmwurz.html

PHP:  class User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrlsyhzr.html

JS:   class User {}
来源：http://dali.0kj1m.cn/Article/details/gtaasfqdyc.html

TS:   class User { name: string = ""; }
来源：http://dali.nwbrower.top/Article/details/gtifiefirt.html


<!-- 参考信息 -->