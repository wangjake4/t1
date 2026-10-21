代发 wailian999

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.aibaodan.cn/Article/details/gtnayiriqr.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgufenzy.top/Article/details/gtnxxyofur.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtixkcbwec.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhoulong.xyz/Article/details/gtjnwcmaby.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.vqdsnc.cn/Article/details/gtrptktuno.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gtwuvqyxdt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhiwuduotai.top/Article/details/gtlbvcvjbc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.nanxuanxn.top/Article/details/gtqrqlosab.html

[E02] 重复字符串
来源：http://dali.zdqjudy.top/Article/details/gtchbbqiaj.html

Py:   "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gtzokkfpaw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xziqi.cn/Article/details/gtrcnutuat.html

JS:   "ab".repeat(3)
来源：http://dali.vqdsnc.cn/Article/details/gtytqvavbw.html

TS:   "ab".repeat(3)
来源：http://dali.aibaodan.cn/Article/details/gtxjzydubw.html

Java: "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtuunhhsde.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtlazuvjgx.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtadojbhuk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jyoumei.cn/Article/details/gtfqzdpfbj.html

[E03] 截取子串
来源：http://dali.shangyingyoupin.top/Article/details/gtvlvuofjd.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxdtxqtl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gtmzvkwvdm.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtcdcbabtv.html

TS:   s.slice(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtyxajvvlp.html

Java: s.substring(1, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhsblmib.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hfpthk.cn/Article/details/gtcqlwerfw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.snrcjt.cn/Article/details/gtpfawmiap.html

C#:   s.Substring(1, 3)
来源：http://dali.zycfv.cn/Article/details/gtsnxabheb.html

[E04] 查找子串位置
来源：http://dali.c1oappe.top/Article/details/gtyjzbikox.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sweek.top/Article/details/gtfodtgqfr.html

PHP:  strpos($s, "x");
来源：http://dali.nwbrower.top/Article/details/gtahcdnetb.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvknuznt.html

TS:   s.indexOf("x")
来源：http://dali.pycfn.com/Article/details/gtpvkrpexa.html

Java: s.indexOf("x")
来源：http://dali.andypj.xyz/Article/details/gtaenvlwtu.html

Go:   strings.Index(s, "x")
来源：http://dali.andypj.xyz/Article/details/gtjjnwjglf.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gtccqhdmdh.html

C#:   s.IndexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtvdsyueai.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjijclunq.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzssvayon.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ivvv.top/Article/details/gtibdonvbt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.pycfn.com/Article/details/gtkiaejxkq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xziqi.cn/Article/details/gtqalflezf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.smart0.xyz/Article/details/gtwclkpfvn.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hywenlv.cn/Article/details/gtvmbqdecl.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gogol.net.cn/Article/details/gtbrecfrhb.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jlsjyb.cn/Article/details/gtzdrcueas.html

[E06] 替换子串
来源：http://dali.xylfe.cn/Article/details/gtatxquvvy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.zhengqikj.top/Article/details/gtvdrvkbvs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aibaodan.cn/Article/details/gtgtjvzruy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtlwvuprsr.html

TS:   s.replaceAll("a", "b")
来源：http://dali.fengsongda.top/Article/details/gtdnxyvuhd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.haohaochexian.top/Article/details/gtjwhnaspk.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pycfn.com/Article/details/gtfmdrvunz.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtjsxzyjkb.html

C#:   s.Replace("a", "b")
来源：http://dali.meibo888.top/Article/details/gtaqloaqxk.html

[E07] 按分隔符拆分
来源：http://dali.dashuyun.cn/Article/details/gtojkcvnzn.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.tanke756.top/Article/details/gtnzglrolm.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtaecikotp.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cucudq.cn/Article/details/gtgypyyakw.html

TS:   s.split(",")
来源：http://dali.havefunace.top/Article/details/gtriztbbgc.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yueranfly.top/Article/details/gtqgqeeggn.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtmxyzruhw.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigfzy.top/Article/details/gtfdvdwizb.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yuxming.cn/Article/details/gthpqkphti.html

[E08] 数组按分隔符合并
来源：http://dali.sweek.top/Article/details/gtyoshwjmv.html

Py:   ",".join(items)
来源：http://dali.jinqigufen.top/Article/details/gtmjrlmdux.html

PHP:  implode(",", $items);
来源：http://dali.smart0.xyz/Article/details/gtqyllovka.html

JS:   items.join(",")
来源：http://dali.wangshuangyany.cn/Article/details/gtklohywup.html

TS:   items.join(",")
来源：http://dali.hammf.cn/Article/details/gtdcseyzts.html

Java: String.join(",", items)
来源：http://dali.zhengqikj.top/Article/details/gtotwegyka.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gtyqqsxqqm.html

Ruby: items.join(",")
来源：http://dali.zhiwuduotai.top/Article/details/gtkgajczkc.html

C#:   string.Join(",", items)
来源：http://dali.daxiang520.top/Article/details/gtpvwhwyro.html

[E09] 去除所有空白字符
来源：http://dali.guannengcc.top/Article/details/gthehbvluz.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zycfv.cn/Article/details/gthclkslxi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daxiang520.top/Article/details/gtcrwrwiel.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gtrijqigpd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.xuanzx.com/Article/details/gtruzycjzm.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.snrcjt.cn/Article/details/gttabkthww.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtykoqlfal.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sufxvd.cn/Article/details/gtejnxdyui.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xziqi.cn/Article/details/gtjupcsglj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.zdqjudy.top/Article/details/gtlqskhucv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.birdmap.top/Article/details/gtsmfolhjl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cashguo.top/Article/details/gtvdhkkfim.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgufenzy.top/Article/details/gtkbqwluaz.html

TS:   "7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtujnesfou.html

Java: String.format("%03d", 7)
来源：http://dali.xuetiantiany.cn/Article/details/gtgtmihxrr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tian-w.cn/Article/details/gtpvdpjnjx.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gtqegswezh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.cucudq.cn/Article/details/gtjlyuiasd.html

[E11] 反转字符串
来源：http://dali.jyoumei.cn/Article/details/gtlauygszg.html

Py:   s[::-1]
来源：http://dali.meibo888.top/Article/details/gtwfqxenyg.html

PHP:  strrev($s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtyyfaoasi.html

JS:   [...s].reverse().join("")
来源：http://dali.iojbl.cn/Article/details/gtmcrglkjx.html

TS:   [...s].reverse().join("")
来源：http://dali.hfpthk.cn/Article/details/gttomrhgiw.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.xziqi.cn/Article/details/gtgrkqagnz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtldpems.html

Ruby: s.reverse
来源：http://dali.yongpay.top/Article/details/gtjbmgybrs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.wangshuangyany.cn/Article/details/gtwvrqnvvs.html

[E12] 统计某字符出现次数
来源：http://dali.chenzaomai.com/Article/details/gtfdrrazun.html

Py:   s.count("a")
来源：http://dali.redwolf501.top/Article/details/gtlhcchpct.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gtvxjpnxud.html

JS:   s.split("a").length - 1
来源：http://dali.9152youxi.cn/Article/details/gtkyvslblv.html

TS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gtyjqralfr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvadtfltl.html

Go:   strings.Count(s, "a")
来源：http://dali.hnqzz.top/Article/details/gtmwbbmqtd.html

Ruby: s.count("a")
来源：http://dali.daria6918.cn/Article/details/gtxvgxowuf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sxryk.cn/Article/details/gtiuqrynaj.html

[E13] 逐字符遍历
来源：http://dali.gaohongyu789.top/Article/details/gtwuowbays.html

Py:   for ch in s: print(ch)
来源：http://dali.cdnleiting.top/Article/details/gtimrobanu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhongyouzk.top/Article/details/gtrymoxgbk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gtaucmmhxk.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gtuupxwgqm.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aibaodan.cn/Article/details/gtsxdtdrqg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ivvv.top/Article/details/gthtxjkipx.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenlongwang.top/Article/details/gtvdhtgjix.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daxiang520.top/Article/details/gtrbzmppwr.html

[E14] URL 编码与 Base64
来源：http://dali.gotoacloud.top/Article/details/gtrcfvkpfy.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yonumen.top/Article/details/gttdtzaurc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.tanke756.top/Article/details/gttnthpbrc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.havefunace.top/Article/details/gtnsszjgky.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cdnleiting.top/Article/details/gthnifnwrs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenjidiqi.icu/Article/details/gtunfgrszd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ydzc1.top/Article/details/gtuvdnrntp.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.dashuyun.cn/Article/details/gtthwrfnqy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yuxming.cn/Article/details/gtmonjrwhs.html

[E15] HTML 转义 / 反转义
来源：http://dali.cheryme.top/Article/details/gtfliyfaya.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shzxlz.cn/Article/details/gtcylhgiof.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.smart0.xyz/Article/details/gtxhvkqgfo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pycfn.com/Article/details/gtkbbsdlgz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jqgufenzy.top/Article/details/gtgtdzxawd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jqgfzy.top/Article/details/gtmrswtoxd.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.9152youxi.cn/Article/details/gticpsnlsq.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.andypj.xyz/Article/details/gttievgtyc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.zhongyouzk.top/Article/details/gthlxgcqgw.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtmbbrpmnn.html

Py:   f"{1234567:,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgpfipfb.html

PHP:  number_format(1234567);
来源：http://dali.havefunace.top/Article/details/gtoskzsgin.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.meibo888.top/Article/details/gtfornzfer.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtkttvxqzv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sysykeji.top/Article/details/gtfloecfgl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.nwbrower.top/Article/details/gtbvlordeb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.guannengcc.top/Article/details/gtqpwcrgsx.html

C#:   1234567.ToString("N0")
来源：http://dali.redwolf501.top/Article/details/gtddfzjrhp.html

[E17] 首字母大写
来源：http://dali.zhoulong.xyz/Article/details/gtxifiwmyw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.0kj1m.cn/Article/details/gtbrdwguad.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hammf.cn/Article/details/gtipjefxkq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxlezgvrm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gtwcryqnfk.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnqzz.top/Article/details/gtbbmgvzka.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.aizwys.cn/Article/details/gtztibpyio.html

Ruby: s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gtloflksnt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shangyingyoupin.top/Article/details/gtnruqwqlj.html

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gttuqymhut.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.chenlongwang.top/Article/details/gtrzyrlklu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.redwolf501.top/Article/details/gtckgczutu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtdhswqxyu.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhijiandao.cn/Article/details/gtbvjiwomh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gtcqvqbuno.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gtkwalewye.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.hnqzz.top/Article/details/gtbdhjbbkv.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cashguo.top/Article/details/gtacbocqhu.html

[E19] 多行文本按行拆分
来源：http://dali.sweek.top/Article/details/gtqygidssh.html

Py:   s.splitlines()
来源：http://dali.sufxvd.cn/Article/details/gtlsokxvlu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zdqjudy.top/Article/details/gtfotbzrrm.html

JS:   s.split(/\r?\n/)
来源：http://dali.yonumen.top/Article/details/gtewcfmugi.html

TS:   s.split(/\r?\n/)
来源：http://dali.vqdsnc.cn/Article/details/gttzbmfpka.html

Java: s.lines().toList()
来源：http://dali.xziqi.cn/Article/details/gtoncjlikg.html

Go:   strings.Split(s, "\n")
来源：http://dali.snrcjt.cn/Article/details/gtxiyiiljp.html

Ruby: s.lines
来源：http://dali.jinqigfzy.top/Article/details/gtfxdqymur.html

C#:   s.Split('\n')
来源：http://dali.cheryme.top/Article/details/gtjlehgqar.html

[E20] 判断字符串是否为空
来源：http://dali.sysykeji.top/Article/details/gtsyacomye.html

Py:   if not s:
来源：http://dali.zhoulong.xyz/Article/details/gtmyfkjzhg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.aibaodan.cn/Article/details/gtmtycwryf.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jinqigfzy.top/Article/details/gtukiospdr.html

TS:   if (s === "") {}
来源：http://dali.ydzc1.top/Article/details/gtsbshuhzt.html

Java: if (s.isEmpty()) {}
来源：http://dali.cqqwz.cn/Article/details/gtuuxaufaf.html

Go:   if s == "" {}
来源：http://dali.redwolf501.top/Article/details/gtycyqgfne.html

Ruby: if s.empty?
来源：http://dali.andypj.xyz/Article/details/gtvosiujqr.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yangfankeji.com/Article/details/gtioysqnga.html

[E21] 超长截断加省略号
来源：http://dali.316326.xyz/Article/details/gtrdokqizy.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuetiantiany.cn/Article/details/gtmhivursf.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.mhx1999.top/Article/details/gtuhdqzewt.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gtaraarwer.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtlpgmdblg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.chenjidiqi.icu/Article/details/gtelrlhcfc.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tianlin.xyz/Article/details/gtdogrmsbe.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqxebmsr.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtyvbcupeq.html

[E22] 字节长度与字符长度
来源：http://dali.yj20258.top/Article/details/gtjgbmtgpj.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.haohaochexian.top/Article/details/gtgajbwvwx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgfzy.top/Article/details/gtwknijobd.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xinyue.icu/Article/details/gtrljyjmqr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xuanzx.com/Article/details/gtmuzxjbrz.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.c1oappe.top/Article/details/gtknkitusc.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.dashuyun.cn/Article/details/gtpgiifwlx.html

Ruby: s.bytesize;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtnxmyyeth.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gtgydnpfds.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtpjuoxlxk.html

F. 文件与目录
来源：http://dali.cqqwz.cn/Article/details/gttkjvhrhw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtgmcxnwaw.html

[F01] 读取整个文件
来源：http://dali.birdmap.top/Article/details/gttebgceow.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.pycfn.com/Article/details/gtrvumzezs.html

PHP:  file_get_contents("a.txt");
来源：http://dali.meibo888.top/Article/details/gtrwvizvwv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.cdnleiting.top/Article/details/gtfbzjgjwk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gtqpuiebtv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gtwdvmphqy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.bjfxy.top/Article/details/gteyzfrbjw.html

Ruby: File.read("a.txt")
来源：http://dali.hnqzz.top/Article/details/gtcpdeqzmn.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtzbwhlywz.html

[F02] 逐行读取文件
来源：http://dali.hammf.cn/Article/details/gtqzgyvgvb.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.chenzaomai.com/Article/details/gthpwlbaoa.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.mhx1999.top/Article/details/gtywqksdxs.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.andypj.xyz/Article/details/gtmomcdxwu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.daria6918.cn/Article/details/gtklykxptc.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cdnleiting.top/Article/details/gtqbhuecbl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.andypj.xyz/Article/details/gtduckiyfz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenlongwang.top/Article/details/gtlsinczcl.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtveyfyqce.html

[F03] 写入文件（覆盖）
来源：http://dali.sxryk.cn/Article/details/gtmxoiswaf.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.sxryk.cn/Article/details/gtbaefbzwf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.gzhubu.top/Article/details/gtjiujfrzn.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.redwolf501.top/Article/details/gtcjirsdca.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sweek.top/Article/details/gtmwgeyjul.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jqgufenzy.top/Article/details/gthbwvyysf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.nanxinkj.top/Article/details/gtdowmxpzt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dashuyun.cn/Article/details/gtejukrzln.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guannengcc.top/Article/details/gttzaxgvcs.html

[F04] 追加写入文件
来源：http://dali.chenjidiqi.icu/Article/details/gtsrwlklum.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ehwqpu.com/Article/details/gthnygyont.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.gzhubu.top/Article/details/gtbbusjaws.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yonumen.top/Article/details/gthlxnlxvn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gttrzfnywh.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuanzhike.top/Article/details/gtvdiovcbu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmzehslvj.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hfpthk.cn/Article/details/gtypcgipmw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gtfxahfnyd.html

[F05] 判断文件或目录是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtmihwqgti.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrlzvqpr.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtkqpkamys.html

JS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gttjywmgho.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtejwlscjo.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gtizpiqnpi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuanzx.com/Article/details/gtkbbmkrdq.html

Ruby: File.exist?("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gtvhfxshsn.html

C#:   File.Exists("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtpvyquxgf.html

[F06] 删除文件
来源：http://dali.meibo888.top/Article/details/gtzhlmggot.html

Py:   os.remove("a.txt")
来源：http://dali.xinyue.icu/Article/details/gtfncmjmfn.html

PHP:  unlink("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtkeslzjec.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtwymbcxrn.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtgqnotqns.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yvedp.cn/Article/details/gtlsklzgkz.html

Go:   os.Remove("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtnjduztud.html

Ruby: File.delete("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtjvlqqnng.html

C#:   File.Delete("a.txt");
来源：http://dali.yongpay.top/Article/details/gtezeecscw.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gtbpblhhuu.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtfdawzkwh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xziqi.cn/Article/details/gtvepaknzz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jqgfzy.top/Article/details/gtpqrtrbgh.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldiycwdm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhengqikj.top/Article/details/gtnqnpbhtm.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.gotoacloud.top/Article/details/gtpbjukszj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gtxyvqvekd.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hfpthk.cn/Article/details/gtjqktkwto.html

[F08] 遍历目录
来源：http://dali.jqgfzy.top/Article/details/gtojlyepkf.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cheryme.top/Article/details/gtiwposzim.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvedniqd.html

JS:   fs.readdirSync("dir")
来源：http://dali.haohaochexian.top/Article/details/gthtpndzwb.html

TS:   fs.readdirSync("dir")
来源：http://dali.hongshengwenyu.top/Article/details/gtvuuxafwe.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.dashuyun.cn/Article/details/gtyoyzrfrw.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtndclqihu.html

Ruby: Dir.children("dir")
来源：http://dali.hywenlv.cn/Article/details/gtpxmqpvdz.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jqgufenzy.top/Article/details/gtorfmpdsh.html

[F09] 获取文件大小
来源：http://dali.wangdashe.top/Article/details/gtyqncjijr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yj20258.top/Article/details/gtowdzochg.html

PHP:  filesize("a.txt");
来源：http://dali.tianlin.xyz/Article/details/gtqxyqwkad.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtgukkunrh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xuanzx.com/Article/details/gtgnrdqfxp.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shangyingyoupin.top/Article/details/gtpcmhukwh.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sysykeji.top/Article/details/gtcozqwwpl.html

Ruby: File.size("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtbisevkii.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gtdladvccc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.nwbrower.top/Article/details/gtbsxrpyna.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtrjitskmr.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtltovzsdc.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.haohaochexian.top/Article/details/gthxfzyyxv.html

TS:   path.extname("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtdewqvrun.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gtnijhrsgz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gthfeqymfx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gteeccgbrq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtnrxencpw.html

[F11] 复制与移动文件
来源：http://dali.ehwqpu.com/Article/details/gtctcjnqry.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.bjfxy.top/Article/details/gtebzpwxff.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.nanxinkj.top/Article/details/gtaykkjbcj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtwfugswut.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hfpthk.cn/Article/details/gtphqukcsw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cheryme.top/Article/details/gtzmnnulls.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.hammf.cn/Article/details/gtvopzyhlg.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gtwtltnijk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gogol.net.cn/Article/details/gttsceliqx.html

[F12] CSV 读写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtycuzanxw.html


<!-- 参考信息 -->