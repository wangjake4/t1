代发 wailian999

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.kuanghao11.cn/Article/details/gtbftmbsai.html

[E03] 截取子串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyqnpnyx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.haohaochexian.top/Article/details/gtgrmvdukl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yangfankeji.com/Article/details/gtezvfvybp.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gtowqgcrlk.html

TS:   s.slice(1, 4)
来源：http://dali.bjfxy.top/Article/details/gtwrdlaidd.html

Java: s.substring(1, 4)
来源：http://dali.iojbl.cn/Article/details/gtjpycazlz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.birdmap.top/Article/details/gtmupclfvm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yanxiufei.cn/Article/details/gtgrcjnsuo.html

C#:   s.Substring(1, 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtjfebyhus.html

[E04] 查找子串位置
来源：http://dali.zhoulong.xyz/Article/details/gtwavpnzuw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cheryme.top/Article/details/gticacjjwe.html

PHP:  strpos($s, "x");
来源：http://dali.yj202588.top/Article/details/gtigmuhxpi.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ehwqpu.com/Article/details/gtmiolcwvt.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gtlbitcezz.html

Java: s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gtajsztniy.html

Go:   strings.Index(s, "x")
来源：http://dali.9152youxi.cn/Article/details/gtneddcoxp.html

Ruby: s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtwealmnlj.html

C#:   s.IndexOf("x")
来源：http://dali.zhiwuduotai.top/Article/details/gtwafugyrh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.bjfxy.top/Article/details/gtpjqhhxcc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yvedp.cn/Article/details/gtvotvlzvf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cashguo.top/Article/details/gtdkxkocje.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gteumnvffw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hnxiangtu.top/Article/details/gtsgsfzgpq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xuetiantiany.cn/Article/details/gtebtqgeob.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.chenzaomai.com/Article/details/gtqpmbtmpi.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsllqwgyy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtytusihkl.html

[E06] 替换子串
来源：http://dali.0kj1m.cn/Article/details/gtnswmhari.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.svipenyu.cn/Article/details/gtsrslrgwn.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yanxiufei.cn/Article/details/gtgrqosqti.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gtcnuhcgaz.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gttqfosayu.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gtuootuqqg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.ivvv.top/Article/details/gtvmlevjbm.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gtzkzskdah.html

C#:   s.Replace("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtjgtlcvmv.html

[E07] 按分隔符拆分
来源：http://dali.chenlongwang.top/Article/details/gtawnqdgtp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.daria6918.cn/Article/details/gtswvtgiuo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.ivvv.top/Article/details/gtucqyebqa.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.jianghu66.top/Article/details/gtbpyygfsf.html

TS:   s.split(",")
来源：http://dali.haohaochexian.top/Article/details/gtivlaszdl.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yj202588.top/Article/details/gtzqqeirun.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.aibaodan.cn/Article/details/gtxoyabbur.html

Ruby: s.split(",");  s.split
来源：http://dali.gogol.net.cn/Article/details/gteqcipgiz.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.yj202588.top/Article/details/gtkwdlpufb.html

[E08] 数组按分隔符合并
来源：http://dali.cashguo.top/Article/details/gtnhekdvoc.html

Py:   ",".join(items)
来源：http://dali.sxryk.cn/Article/details/gtezlnyuqa.html

PHP:  implode(",", $items);
来源：http://dali.shanyushiyangtech.top/Article/details/gthwlmrdyc.html

JS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gtqscvtqnp.html

TS:   items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtiqashcjm.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtmognfaln.html

Go:   strings.Join(items, ",")
来源：http://dali.wangshuangyany.cn/Article/details/gtnsrkinep.html

Ruby: items.join(",")
来源：http://dali.fengsongda.top/Article/details/gtjfqvvrjv.html

C#:   string.Join(",", items)
来源：http://dali.yuxming.cn/Article/details/gtaenoiyxf.html

[E09] 去除所有空白字符
来源：http://dali.jianghu66.top/Article/details/gtclbvmpeb.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.9152youxi.cn/Article/details/gtanjxomcz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jyoumei.cn/Article/details/gtbaxhyukq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gtelmpilmb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenzaomai.com/Article/details/gtvaptfcfk.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.chenjidiqi.icu/Article/details/gtuvwyhxgh.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.pycfn.com/Article/details/gtmkbooyvf.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258888.top/Article/details/gtohnkszrl.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jlsjyb.cn/Article/details/gtueomzxsb.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuetiantiany.cn/Article/details/gthxhdcjwk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtkpqgqxmt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxinkj.top/Article/details/gtqwqsrpnn.html

JS:   "7".padStart(3, "0")
来源：http://dali.cashguo.top/Article/details/gtncjvgqsn.html

TS:   "7".padStart(3, "0")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywcyzpkp.html

Java: String.format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gtzgdaimgq.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.cashguo.top/Article/details/gtxaodejdl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.316326.xyz/Article/details/gtfmuljoro.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jiagoushi.top/Article/details/gtteqmjpgy.html

[E11] 反转字符串
来源：http://dali.xylfe.cn/Article/details/gtznacvjnu.html

Py:   s[::-1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpyzfzaki.html

PHP:  strrev($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtvcsiufly.html

JS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gtktikilmm.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gtkvonyrbt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.cheryme.top/Article/details/gtcohulwak.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gtpbgaocqa.html

Ruby: s.reverse
来源：http://dali.fengsongda.top/Article/details/gttqpqjzur.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gtqatmokzm.html

[E12] 统计某字符出现次数
来源：http://dali.aibaodan.cn/Article/details/gtjmskvxuy.html

Py:   s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gtzdfkudlk.html

PHP:  substr_count($s, "a");
来源：http://dali.cqqwz.cn/Article/details/gtvxmhibqd.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gtlmfxcbkv.html

TS:   s.split("a").length - 1
来源：http://dali.birdmap.top/Article/details/gtkzgkmzsw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hongshengwenyu.top/Article/details/gtdzlcxrff.html

Go:   strings.Count(s, "a")
来源：http://dali.ivvv.top/Article/details/gtvsjeitpt.html

Ruby: s.count("a")
来源：http://dali.meibo888.top/Article/details/gthugpykui.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhongyouzk.top/Article/details/gtfpsuudom.html

[E13] 逐字符遍历
来源：http://dali.nanxinkj.top/Article/details/gtvgdyyago.html

Py:   for ch in s: print(ch)
来源：http://dali.daxiang520.top/Article/details/gtjethovsy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hfpthk.cn/Article/details/gtzmblfzno.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtczdgzroh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.redwolf501.top/Article/details/gtdwfmfofr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtzrcfwzrw.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.dianchejie.cn/Article/details/gtjoupalrt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yonumen.top/Article/details/gtttzanxvj.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtqatxvckq.html

[E14] URL 编码与 Base64
来源：http://dali.aizwys.cn/Article/details/gtcntdepco.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.chenjidiqi.icu/Article/details/gthbrgivvt.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pengpengdd.cyou/Article/details/gtegapmvba.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gtvefoxegp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.kuanghao11.cn/Article/details/gtqhxmepio.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.c1oappe.top/Article/details/gthsetopta.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gogol.net.cn/Article/details/gtyiksqwpr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yanxiufei.cn/Article/details/gtwovskyrj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hywenlv.cn/Article/details/gtxbywblgh.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gtqcbaoots.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.cqqwz.cn/Article/details/gtinazmzlt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.aizwys.cn/Article/details/gtndmwcxsi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gtwfjtzcvc.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cdnleiting.top/Article/details/gtxsmfgiyq.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.iojbl.cn/Article/details/gtlvhahskr.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtwtesrmcd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zdqjudy.top/Article/details/gtylmmjtcy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.ivvv.top/Article/details/gtqbcuzmeu.html

[E16] 数字千分位
来源：http://dali.pycfn.com/Article/details/gtlkdmhhud.html

Py:   f"{1234567:,}"
来源：http://dali.hfpthk.cn/Article/details/gtogwfvlfa.html

PHP:  number_format(1234567);
来源：http://dali.tian-w.cn/Article/details/gtggnhqhds.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gtchbrqxfx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.daxiang520.top/Article/details/gtulxaagdz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gtuqnyvneo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhengqikj.top/Article/details/gttgttonja.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjocjbjpb.html

C#:   1234567.ToString("N0")
来源：http://dali.c1oappe.top/Article/details/gtjlfgmjbz.html

[E17] 首字母大写
来源：http://dali.nanxinkj.top/Article/details/gtoxucrvxq.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtabqznevl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.smart0.xyz/Article/details/gtiqzyudlq.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtmjxbqufp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj202588.top/Article/details/gtpjjqletu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.tian-w.cn/Article/details/gtlxykxuhi.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.ybcxt.top/Article/details/gtqqnmcqez.html

Ruby: s.capitalize
来源：http://dali.fengsongda.top/Article/details/gthtcybtlt.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.cheryme.top/Article/details/gticfpzyqg.html

[E18] 模板占位符替换
来源：http://dali.nwbrower.top/Article/details/gtgnaohtmi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.yj202588.top/Article/details/gtnxkeryup.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yanxiufei.cn/Article/details/gtaesbcjwd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuetiantiany.cn/Article/details/gtfhpbbmgx.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.tian-w.cn/Article/details/gtilefuwls.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhengqikj.top/Article/details/gtsqmtojzv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtvnyglggu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zhixingplan.top/Article/details/gtynafdqix.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.hammf.cn/Article/details/gtjoudnmyq.html

[E19] 多行文本按行拆分
来源：http://dali.dashuyun.cn/Article/details/gtyeaonrcn.html

Py:   s.splitlines()
来源：http://dali.zdqjudy.top/Article/details/gtegwwsenj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtrgzwvldn.html

JS:   s.split(/\r?\n/)
来源：http://dali.mhx1999.top/Article/details/gtqqendoef.html

TS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gtgaygchsu.html

Java: s.lines().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtxgtylpos.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhengqikj.top/Article/details/gtklxbxwrs.html

Ruby: s.lines
来源：http://dali.aibaodan.cn/Article/details/gtvcphaigy.html

C#:   s.Split('\n')
来源：http://dali.yvedp.cn/Article/details/gtbutszhyi.html

[E20] 判断字符串是否为空
来源：http://dali.nanxinkj.top/Article/details/gtfiarsmvq.html

Py:   if not s:
来源：http://dali.shanyushiyangtech.top/Article/details/gtpuwsdrvb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlxngwcv.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuxming.cn/Article/details/gtyvclfuih.html

TS:   if (s === "") {}
来源：http://dali.jqgfzy.top/Article/details/gtpzhbkrxf.html

Java: if (s.isEmpty()) {}
来源：http://dali.jiagoushi.top/Article/details/gtciycyikk.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgsjrsuh.html

Ruby: if s.empty?
来源：http://dali.hnqzz.top/Article/details/gtjkybdyfc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cheryme.top/Article/details/gtfwpmgplw.html

[E21] 超长截断加省略号
来源：http://dali.haohaochexian.top/Article/details/gttgeigvcc.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.haohaochexian.top/Article/details/gtzttizpex.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gtvtqrjlfn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cucudq.cn/Article/details/gtncpplpgv.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aibaodan.cn/Article/details/gtstvpbsxp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.bjfxy.top/Article/details/gtncpobzpg.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.sufxvd.cn/Article/details/gtimkrcrug.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.jinghuilouyu.cn/Article/details/gtakgvveri.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.daxiang520.top/Article/details/gtktgjbnks.html

[E22] 字节长度与字符长度
来源：http://dali.zhixingplan.top/Article/details/gtllxcjewv.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtrhhvqnlr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtezikbqmz.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.sufxvd.cn/Article/details/gttctddsce.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.aizwys.cn/Article/details/gtkxicwovc.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigufen.top/Article/details/gtufarqtzb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.birdmap.top/Article/details/gtmkwlzlvu.html

Ruby: s.bytesize;  s.length
来源：http://dali.daria6918.cn/Article/details/gtnicmrygs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.gogol.net.cn/Article/details/gtxokhoxxr.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtwealambu.html

F. 文件与目录
来源：http://dali.jqgfzy.top/Article/details/gtuyhvloku.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtybmltkqq.html

[F01] 读取整个文件
来源：http://dali.cheryme.top/Article/details/gthagzwtgc.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwslijfcb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gtfgphojct.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yanxiufei.cn/Article/details/gtgmmxhwji.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenlongwang.top/Article/details/gtxyhahhck.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gtpnmyuhbz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zdqjudy.top/Article/details/gtdxbvabqm.html

Ruby: File.read("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtpcvhnjyy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.chenjidiqi.icu/Article/details/gtmmiptctj.html

[F02] 逐行读取文件
来源：http://dali.yanxiufei.cn/Article/details/gtfoluivrm.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukeczhxd.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtwhyupcly.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jianghu66.top/Article/details/gtdaqbejrv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gtgypygiqj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.redwolf501.top/Article/details/gtzpapqnst.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gtnvojuube.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xinyue.icu/Article/details/gtfvlfxvul.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.xylfe.cn/Article/details/gtwtqbxyfg.html

[F03] 写入文件（覆盖）
来源：http://dali.sufxvd.cn/Article/details/gtywjtknsz.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinaeysaj.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrgoulxg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gtjsbzpbnk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.iojbl.cn/Article/details/gtlhgvwvsl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.dianchejie.cn/Article/details/gtcgsbsfbl.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258.top/Article/details/gtuncdkorr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.xinyue.icu/Article/details/gtuksvdgjj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.guowangkeji.top/Article/details/gtbugyadej.html

[F04] 追加写入文件
来源：http://dali.fzhhl.top/Article/details/gttmhlmvyo.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cdnleiting.top/Article/details/gtzmfrbkhs.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.iojbl.cn/Article/details/gtgshqbrqc.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gtltaaxpae.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gthfxybzov.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sysykeji.top/Article/details/gtinyvenra.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtqxrraysv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwvkisjt.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gthsfbkgjp.html

[F05] 判断文件或目录是否存在
来源：http://dali.daxiang520.top/Article/details/gtiwrvblsb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shuidangran.top/Article/details/gtfzytvoad.html

PHP:  file_exists("a.txt");
来源：http://dali.yj202588.top/Article/details/gtvbjibkwl.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gttyhmpodj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtlfqtgcpd.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ehwqpu.com/Article/details/gtjvqjrhhw.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aizwys.cn/Article/details/gtnuoxsucy.html

Ruby: File.exist?("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtxglpheyq.html

C#:   File.Exists("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gtataouplg.html

[F06] 删除文件
来源：http://dali.vqdsnc.cn/Article/details/gthzrrnkac.html

Py:   os.remove("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gttryakcfn.html

PHP:  unlink("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtwwbaejpv.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtglybrsap.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.daria6918.cn/Article/details/gtftrhwkcb.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.yongpay.top/Article/details/gtmzoojgyq.html

Go:   os.Remove("a.txt")
来源：http://dali.sxryk.cn/Article/details/gtdljzretx.html

Ruby: File.delete("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gticykyawi.html

C#:   File.Delete("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gtnfeuutda.html

[F07] 创建目录（含多级）
来源：http://dali.aizwys.cn/Article/details/gtgyfvdwyr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.316326.xyz/Article/details/gtrikztmas.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gtkptytrzy.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sxryk.cn/Article/details/gttqxbwbcy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hfpthk.cn/Article/details/gtzccilzgm.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yj20258.top/Article/details/gtaqvfqubo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.aibaodan.cn/Article/details/gtyhadznvm.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gtbtebdvdy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gtsvjocxmy.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gtmmhitaug.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.quarkkingdee.top/Article/details/gtwwljnszg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.9152youxi.cn/Article/details/gtjophrqkb.html

JS:   fs.readdirSync("dir")
来源：http://dali.nanxinkj.top/Article/details/gtgaxtthqt.html

TS:   fs.readdirSync("dir")
来源：http://dali.iojbl.cn/Article/details/gtdxptxmuw.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.feifeiyinyue.top/Article/details/gtsumatzet.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ppjwa.cn/Article/details/gtvgfnsejn.html

Ruby: Dir.children("dir")
来源：http://dali.zdqjudy.top/Article/details/gtgkgojvsk.html

C#:   Directory.GetFiles("dir")
来源：http://dali.zdqjudy.top/Article/details/gtqcytuogm.html

[F09] 获取文件大小
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpltnithj.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtwtenhmov.html

PHP:  filesize("a.txt");
来源：http://dali.cheryme.top/Article/details/gttvrottxa.html

JS:   fs.statSync("a.txt").size
来源：http://dali.birdmap.top/Article/details/gthewevdun.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gttczsutwn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gtimchlxub.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.bjfxy.top/Article/details/gtfcdtixeb.html

Ruby: File.size("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gtlppubkmk.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jianghu66.top/Article/details/gtehrawhop.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258888.top/Article/details/gtwcyqptcr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jiagoushi.top/Article/details/gtwqhyajom.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gtgfcebgmj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gtymnzvsig.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfcesowl.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yanxiufei.cn/Article/details/gtodbuxiam.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipvrzexd.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.shuidangran.top/Article/details/gtskdesbqv.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtdcjeygjl.html

[F11] 复制与移动文件
来源：http://dali.gzhubu.top/Article/details/gtgaogpekc.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuanzx.com/Article/details/gtcshuuemg.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hysaishi.cn/Article/details/gtmmhxqysj.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.smart0.xyz/Article/details/gtfveetdig.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtdkrlkpmc.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cucudq.cn/Article/details/gtsnoucvtp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gttrheuimr.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtbpirhfbn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.iojbl.cn/Article/details/gtqozxxala.html

[F12] CSV 读写
来源：http://dali.nanxuanxn.top/Article/details/gtlsafkrxd.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jqgufenzy.top/Article/details/gtkcjasdrs.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ybcxt.top/Article/details/gteiqbcdeu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.dianchejie.cn/Article/details/gtygzazylv.html

TS:   // 同上
来源：http://dali.jqgfzy.top/Article/details/gthkaxihpi.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgufenzy.top/Article/details/gtcrwppxfb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.feifeiyinyue.top/Article/details/gtlnlmsmdh.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.dashuyun.cn/Article/details/gtatvkydqu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ivvv.top/Article/details/gtyhhrjrib.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtufaodoyc.html

G. 面向对象
来源：http://dali.gotoacloud.top/Article/details/gtzsqunwif.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtivdwfzve.html

[G01] 定义类
来源：http://dali.yj202588.top/Article/details/gtvqwmieki.html

Py:   class User: pass
来源：http://dali.kuanghao11.cn/Article/details/gtshmkdqfo.html

PHP:  class User {}
来源：http://dali.jinqigfzy.top/Article/details/gtejrfcsjk.html

JS:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtajuwujvq.html

TS:   class User { name: string = ""; }
来源：http://dali.zycfv.cn/Article/details/gtzhhtizfl.html


<!-- 参考信息 -->