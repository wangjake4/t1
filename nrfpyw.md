代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ybcxt.top/Article/details/gtkcmzqipo.html

[E03] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtqzpnverz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.svipenyu.cn/Article/details/gtstpuvhhe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jiagoushi.top/Article/details/gthsdnznnp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtkjjrttcw.html

TS:   s.slice(1, 4)
来源：http://dali.smart0.xyz/Article/details/gtpsbizzyq.html

Java: s.substring(1, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtukctqwko.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhijiandao.cn/Article/details/gtenhyoklw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.quarkkingdee.top/Article/details/gtszxnwymf.html

C#:   s.Substring(1, 3)
来源：http://dali.ehwqpu.com/Article/details/gtfijmadhc.html

[E04] 查找子串位置
来源：http://dali.kuanghao11.cn/Article/details/gtdqyrlgqk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuopnskvj.html

PHP:  strpos($s, "x");
来源：http://dali.zhengqikj.top/Article/details/gtrxxhajnt.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxsqicab.html

TS:   s.indexOf("x")
来源：http://dali.tanke756.top/Article/details/gtuupwrlkk.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtcoiitrmd.html

Go:   strings.Index(s, "x")
来源：http://dali.yongpay.top/Article/details/gtdckhmfjn.html

Ruby: s.index("x")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbdefelim.html

C#:   s.IndexOf("x")
来源：http://dali.cucudq.cn/Article/details/gtwpdihpel.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.fengsongda.top/Article/details/gtjodgzpay.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hnxiangtu.top/Article/details/gtuzvocpvz.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ppjwa.cn/Article/details/gtzppxamdu.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zdqjudy.top/Article/details/gtfvpexqcg.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.ivvv.top/Article/details/gtcznkhmom.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtetilzpdc.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ivvv.top/Article/details/gtnhnrujdd.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtxtwkigrg.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.wangshuangyany.cn/Article/details/gtlhwduorg.html

[E06] 替换子串
来源：http://dali.andypj.xyz/Article/details/gtskoxpuvo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.gotoacloud.top/Article/details/gtucgqhnym.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daria6918.cn/Article/details/gtmputkrtx.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtaselihqn.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dashuyun.cn/Article/details/gtcqbgshwc.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.andypj.xyz/Article/details/gtidvjpxpf.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.aibaodan.cn/Article/details/gtbxixsxqe.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtboyodbyh.html

C#:   s.Replace("a", "b")
来源：http://dali.hammf.cn/Article/details/gthvastepa.html

[E07] 按分隔符拆分
来源：http://dali.zhixingplan.top/Article/details/gtfenvqizt.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yueranfly.top/Article/details/gtepkosfwh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gaohongyu789.top/Article/details/gtqlmstxbn.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.kuanghao11.cn/Article/details/gtprgqmqbj.html

TS:   s.split(",")
来源：http://dali.mhx1999.top/Article/details/gtjhhfjxkf.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.gaohongyu789.top/Article/details/gtqvhzciqk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.gogol.net.cn/Article/details/gtvdlyzusx.html

Ruby: s.split(",");  s.split
来源：http://dali.chenjidiqi.icu/Article/details/gtwumenvap.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ppjwa.cn/Article/details/gtrpiihako.html

[E08] 数组按分隔符合并
来源：http://dali.jqgufenzy.top/Article/details/gtansmnqoo.html

Py:   ",".join(items)
来源：http://dali.jlsjyb.cn/Article/details/gtrfhybmsp.html

PHP:  implode(",", $items);
来源：http://dali.yonumen.top/Article/details/gtpjcckxsu.html

JS:   items.join(",")
来源：http://dali.sxryk.cn/Article/details/gtwpeqceba.html

TS:   items.join(",")
来源：http://dali.shzxlz.cn/Article/details/gtwznmzxhy.html

Java: String.join(",", items)
来源：http://dali.zhongyouzk.top/Article/details/gtakcqzoub.html

Go:   strings.Join(items, ",")
来源：http://dali.cucudq.cn/Article/details/gtalhxfghn.html

Ruby: items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtcecfoqkh.html

C#:   string.Join(",", items)
来源：http://dali.guowangkeji.top/Article/details/gtnfybwqwy.html

[E09] 去除所有空白字符
来源：http://dali.birdmap.top/Article/details/gtfowcetee.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.andypj.xyz/Article/details/gthijomaym.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtatlvxewb.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.ivvv.top/Article/details/gtfhzpilyc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.316326.xyz/Article/details/gtshwtgctg.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.xuetiantiany.cn/Article/details/gtxexmoamu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fengsongda.top/Article/details/gtnlabxfqq.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258888.top/Article/details/gtzmaochff.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gtijeomvtz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yanxiufei.cn/Article/details/gtdgvjhoxl.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtklrcakvl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cqqwz.cn/Article/details/gteeuzxmhj.html

JS:   "7".padStart(3, "0")
来源：http://dali.tanke756.top/Article/details/gtajdzetit.html

TS:   "7".padStart(3, "0")
来源：http://dali.yueranfly.top/Article/details/gttthrlexn.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258.top/Article/details/gtrkxavhsp.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dianchejie.cn/Article/details/gtoyzjjyjm.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.ehwqpu.com/Article/details/gtemanlhgx.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.xziqi.cn/Article/details/gtphgsutfl.html

[E11] 反转字符串
来源：http://dali.chenlongwang.top/Article/details/gtnbjjslzt.html

Py:   s[::-1]
来源：http://dali.nanxuanxn.top/Article/details/gtauyrwafy.html

PHP:  strrev($s);
来源：http://dali.nanxuanxn.top/Article/details/gtlymogzvt.html

JS:   [...s].reverse().join("")
来源：http://dali.cdnleiting.top/Article/details/gtmlstssbj.html

TS:   [...s].reverse().join("")
来源：http://dali.yj20258.top/Article/details/gtxtpfyjok.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jqgufenzy.top/Article/details/gtfchahxas.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yuxming.cn/Article/details/gtnqsqlksr.html

Ruby: s.reverse
来源：http://dali.cucudq.cn/Article/details/gtqxlwcqjt.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.9152youxi.cn/Article/details/gtqxpexxes.html

[E12] 统计某字符出现次数
来源：http://dali.jyoumei.cn/Article/details/gtiwunqyfi.html

Py:   s.count("a")
来源：http://dali.birdmap.top/Article/details/gtlyutregc.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigufen.top/Article/details/gthmiknbye.html

JS:   s.split("a").length - 1
来源：http://dali.zhengqikj.top/Article/details/gtzexbzlqh.html

TS:   s.split("a").length - 1
来源：http://dali.jianghu66.top/Article/details/gtjypaabxn.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jyoumei.cn/Article/details/gtfofcqhwh.html

Go:   strings.Count(s, "a")
来源：http://dali.gaohongyu789.top/Article/details/gtikljavmd.html

Ruby: s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gtkajjsjxl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.birdmap.top/Article/details/gtvajrnont.html

[E13] 逐字符遍历
来源：http://dali.gotoacloud.top/Article/details/gtvzbagzyq.html

Py:   for ch in s: print(ch)
来源：http://dali.yueranfly.top/Article/details/gtzsuhkpqx.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yueranfly.top/Article/details/gtcjxexbck.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.mhx1999.top/Article/details/gttqfecirl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuxming.cn/Article/details/gthynazftj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.daria6918.cn/Article/details/gtmxjptypp.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.daria6918.cn/Article/details/gteozhhoxy.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.wangdashe.top/Article/details/gtqpbxyjzr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtghhehnas.html

[E14] URL 编码与 Base64
来源：http://dali.hongshengwenyu.top/Article/details/gteibtgrxr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.cqqwz.cn/Article/details/gtyteyzvuq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cqqwz.cn/Article/details/gtvggsrqbe.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.snrcjt.cn/Article/details/gtfdzjwcgx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gtwahgeglh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtrjpbbosk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.guannengcc.top/Article/details/gtfcdrlnmc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xylfe.cn/Article/details/gtyjsykhjm.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcwxcbvs.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhixingplan.top/Article/details/gtzntmzpda.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhijiandao.cn/Article/details/gtgwiuxcoz.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.svipenyu.cn/Article/details/gtmbhtcohi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.vqdsnc.cn/Article/details/gtufrptigu.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.jinqigufen.top/Article/details/gtzahfsetg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gtqgyfxtvv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ehwqpu.com/Article/details/gtlwkxpxte.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttrwxnkvy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hongshengwenyu.top/Article/details/gthoxfchkn.html

[E16] 数字千分位
来源：http://dali.0kj1m.cn/Article/details/gtlwqwgxzc.html

Py:   f"{1234567:,}"
来源：http://dali.tianlin.xyz/Article/details/gtykatfpjk.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gtredtlage.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.mhx1999.top/Article/details/gtopyblfyo.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gtlrjzqjbj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.jinqigufen.top/Article/details/gtdkdrsjlq.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.kuanghao11.cn/Article/details/gtufmuitju.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tanke756.top/Article/details/gtqwfbqqlm.html

C#:   1234567.ToString("N0")
来源：http://dali.aizwys.cn/Article/details/gtekrfbyjd.html

[E17] 首字母大写
来源：http://dali.ivvv.top/Article/details/gtfbctweoz.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gtzzwkdtrh.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xuanzx.com/Article/details/gtxbicqxpt.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.hnxiangtu.top/Article/details/gtsxwvbynk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvazdbesr.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gtqcxxkvev.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.pycfn.com/Article/details/gtuuzyaddc.html

Ruby: s.capitalize
来源：http://dali.snrcjt.cn/Article/details/gtjjtovpse.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gtupfpomlt.html

[E18] 模板占位符替换
来源：http://dali.yonumen.top/Article/details/gtchyhgywu.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutjqstud.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.guannengcc.top/Article/details/gtdeydgjdl.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtoaufsfgr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtvdfkwcki.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gtwopdqrce.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.xinyue.icu/Article/details/gteaerdlmp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.smart0.xyz/Article/details/gtldcubssz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.bjfxy.top/Article/details/gtlpjibvxm.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gtcjqecupw.html

Py:   s.splitlines()
来源：http://dali.yonumen.top/Article/details/gtvcjfdyet.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xziqi.cn/Article/details/gtxoglkjtb.html

JS:   s.split(/\r?\n/)
来源：http://dali.gogol.net.cn/Article/details/gttmwlrltl.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenjidiqi.icu/Article/details/gtbwihxekv.html

Java: s.lines().toList()
来源：http://dali.ydzc1.top/Article/details/gtwbpxhrkw.html

Go:   strings.Split(s, "\n")
来源：http://dali.sxryk.cn/Article/details/gttquichgl.html

Ruby: s.lines
来源：http://dali.shangyingyoupin.top/Article/details/gtkbsctpjt.html

C#:   s.Split('\n')
来源：http://dali.nwbrower.top/Article/details/gtifygmcmz.html

[E20] 判断字符串是否为空
来源：http://dali.pycfn.com/Article/details/gtigmkbxlu.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gtycpgfamr.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwfozsmk.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hammf.cn/Article/details/gttruusefr.html

TS:   if (s === "") {}
来源：http://dali.iojbl.cn/Article/details/gttokxpoyb.html

Java: if (s.isEmpty()) {}
来源：http://dali.haohaochexian.top/Article/details/gtxlpqclsn.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtsyqdhrhp.html

Ruby: if s.empty?
来源：http://dali.aibaodan.cn/Article/details/gtiffkaddb.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuxming.cn/Article/details/gtggfwwldz.html

[E21] 超长截断加省略号
来源：http://dali.cashguo.top/Article/details/gtjlbutput.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.hnxiangtu.top/Article/details/gtcgzraqts.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.birdmap.top/Article/details/gtzoxzccuj.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzqtkhrr.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtrkpxgsls.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jqgfzy.top/Article/details/gtyphtqeyo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnqzz.top/Article/details/gtxhmgjqnh.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnnmxeid.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.andypj.xyz/Article/details/gtseytdkkx.html

[E22] 字节长度与字符长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmjmsxzzc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtegdjouju.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.chenlongwang.top/Article/details/gttyaregkv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yanxiufei.cn/Article/details/gtnbyxywkk.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hysaishi.cn/Article/details/gtspdgnatb.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ivvv.top/Article/details/gtiboxmzew.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhixingplan.top/Article/details/gtnrandqlh.html

Ruby: s.bytesize;  s.length
来源：http://dali.redwolf501.top/Article/details/gtdkavgpsi.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtoqdtkkij.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtitcmsjnu.html

F. 文件与目录
来源：http://dali.daria6918.cn/Article/details/gtzpuwfkuo.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtoglpfxix.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gtzzrzebyt.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gtxcozsvqr.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cashguo.top/Article/details/gtdawfbgze.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yvedp.cn/Article/details/gtomyzhssu.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.birdmap.top/Article/details/gtimnbramg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.havefunace.top/Article/details/gtbajpfkfw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hnqzz.top/Article/details/gtdbuvxvwb.html

Ruby: File.read("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtdlkpzcst.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yj20258.top/Article/details/gtqvyrgqzb.html

[F02] 逐行读取文件
来源：http://dali.ivvv.top/Article/details/gtcsgkfock.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.dashuyun.cn/Article/details/gtkqdxovsl.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zhiwuduotai.top/Article/details/gtnrbnsyku.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.svipenyu.cn/Article/details/gtobtvlxio.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenlongwang.top/Article/details/gtcnrivylb.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zycfv.cn/Article/details/gtwguvfndw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.chenzaomai.com/Article/details/gtxjzfqhwf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.nwbrower.top/Article/details/gtigjbhjnp.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gotoacloud.top/Article/details/gtxwkyrwdd.html

[F03] 写入文件（覆盖）
来源：http://dali.hnxiangtu.top/Article/details/gttjurbdkd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.c1oappe.top/Article/details/gtlqbnrlsd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtbkjtautl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.andypj.xyz/Article/details/gtvynjchsf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gteordyocn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpwnegdz.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.gzhubu.top/Article/details/gtxbcvroos.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.shangyingyoupin.top/Article/details/gtmfgilupa.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.nanxinkj.top/Article/details/gtdvzkldfw.html

[F04] 追加写入文件
来源：http://dali.iojbl.cn/Article/details/gtbgkrjvdh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtfqotlwuo.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinqigfzy.top/Article/details/gthelodsjf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkosnyhj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yvedp.cn/Article/details/gtmdynxqrz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhongyouzk.top/Article/details/gtcdhyjhzn.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.zhixingplan.top/Article/details/gtpetnsnwx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.nwbrower.top/Article/details/gtrflpviql.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.birdmap.top/Article/details/gtpohuymqg.html

[F05] 判断文件或目录是否存在
来源：http://dali.bjfxy.top/Article/details/gtrmjddryb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.nanxuanxn.top/Article/details/gtctwvtpia.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtzopadhem.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gttrjqsjxf.html

TS:   fs.existsSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbaryppfy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gttoupntzu.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jiagoushi.top/Article/details/gtmybmwxvp.html

Ruby: File.exist?("a.txt")
来源：http://dali.sysykeji.top/Article/details/gtptxojmtl.html

C#:   File.Exists("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtufyuhnpq.html

[F06] 删除文件
来源：http://dali.svipenyu.cn/Article/details/gtsuvjiyzb.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtjzbjegas.html

PHP:  unlink("a.txt");
来源：http://dali.wangdashe.top/Article/details/gtxotjccaw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xziqi.cn/Article/details/gtdiistwip.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gteobzewdj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jyoumei.cn/Article/details/gtrfoikqlz.html

Go:   os.Remove("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtlgnvuoxt.html

Ruby: File.delete("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtmxirnibb.html

C#:   File.Delete("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtsmynaifc.html

[F07] 创建目录（含多级）
来源：http://dali.feifeiyinyue.top/Article/details/gtslunnkra.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtxnlnwxpg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.mhx1999.top/Article/details/gtldbyucct.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.fengsongda.top/Article/details/gtehlrzdjm.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gtsitqkcaa.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jqgfzy.top/Article/details/gtjyqkeqlv.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nwbrower.top/Article/details/gthdwvsojg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xylfe.cn/Article/details/gtbknsykgj.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinqigfzy.top/Article/details/gtxwjxoxco.html

[F08] 遍历目录
来源：http://dali.sxryk.cn/Article/details/gteoicaeqv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.chenjidiqi.icu/Article/details/gtokmvzgvp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hnqzz.top/Article/details/gtakroyrli.html

JS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gteoixjwst.html

TS:   fs.readdirSync("dir")
来源：http://dali.daria6918.cn/Article/details/gtcbbctrjr.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.ydzc1.top/Article/details/gtunzyxmly.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.andypj.xyz/Article/details/gtuixoaibg.html

Ruby: Dir.children("dir")
来源：http://dali.gzhubu.top/Article/details/gtltgyjdhw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.smart0.xyz/Article/details/gtxlxfpqxk.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gtsurirggb.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtkjawrrno.html

PHP:  filesize("a.txt");
来源：http://dali.yj20258.top/Article/details/gtsktftiys.html

JS:   fs.statSync("a.txt").size
来源：http://dali.pycfn.com/Article/details/gtquazfchd.html

TS:   fs.statSync("a.txt").size
来源：http://dali.nanxinkj.top/Article/details/gtzoqdvzej.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gtketxnfsa.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jinghuilouyu.cn/Article/details/gtashbbfnk.html

Ruby: File.size("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtylxnrrmc.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.gotoacloud.top/Article/details/gtrrrfvepd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cdnleiting.top/Article/details/gtnntzanfk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtkifuwfqb.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtrczjxihk.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.nanxinkj.top/Article/details/gtpmgdlogk.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtthyrtsir.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gtoyxasufn.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gtidrslvwv.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cashguo.top/Article/details/gtwuprgqeq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hammf.cn/Article/details/gthifvjnoq.html

[F11] 复制与移动文件
来源：http://dali.wangshuangyany.cn/Article/details/gtpvazkene.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xinyue.icu/Article/details/gtnkzdijln.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dianchejie.cn/Article/details/gtyqricnbk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtayuiwbba.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gtxpmcxrvr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yangfankeji.com/Article/details/gtquvjihqy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.ppjwa.cn/Article/details/gtruudrnyv.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtteqruljj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hysaishi.cn/Article/details/gtcwfakvco.html

[F12] CSV 读写
来源：http://dali.cdnleiting.top/Article/details/gtmbjfaudi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xuetiantiany.cn/Article/details/gtjzorwvmh.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.wangdashe.top/Article/details/gtqwdsgkil.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.316326.xyz/Article/details/gtedmgivxc.html

TS:   // 同上
来源：http://dali.jiagoushi.top/Article/details/gtmpywnkmo.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zhiwuduotai.top/Article/details/gtrnbojyje.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.0kj1m.cn/Article/details/gttsxxvfhq.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gtojkrumam.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.feifeiyinyue.top/Article/details/gtzgkamldn.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtkdqllaec.html

G. 面向对象
来源：http://dali.shuidangran.top/Article/details/gtazkqhvqd.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtvznubbtm.html

[G01] 定义类
来源：http://dali.ppjwa.cn/Article/details/gthorfjdqw.html

Py:   class User: pass
来源：http://dali.haohaochexian.top/Article/details/gtelefsloh.html

PHP:  class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gttdbhvqpn.html

JS:   class User {}
来源：http://dali.zhengqikj.top/Article/details/gtennlygcz.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258888.top/Article/details/gtpvxgzdcg.html


<!-- 参考信息 -->