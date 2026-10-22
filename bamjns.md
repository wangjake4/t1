代发 wailian999

[E02] 重复字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2pljxfsog.html

Py:   "ab" * 3
来源：http://dali.hywenlv.cn/Article/details/gt2sqskukeb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cqqwz.cn/Article/details/gt2whvxoobz.html

JS:   "ab".repeat(3)
来源：http://dali.yonumen.top/Article/details/gt2bduqvkar.html

TS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gt2yiwnlhdt.html

Java: "ab".repeat(3)
来源：http://dali.dashuyun.cn/Article/details/gt2ycmhijkm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2nznwpava.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gt2lzqezlzv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hongshengwenyu.top/Article/details/gt2jgqfugad.html

[E03] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gt2ruplwgtu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cqqwz.cn/Article/details/gt2jhgdiycs.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gt2vdoeynzw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gt2rkmcqnbr.html

TS:   s.slice(1, 4)
来源：http://dali.mhx1999.top/Article/details/gt2hpfsbixe.html

Java: s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2lswpcifn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daxiang520.top/Article/details/gt2gmlkfsle.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shuidangran.top/Article/details/gt2etkcbfxe.html

C#:   s.Substring(1, 3)
来源：http://dali.fengsongda.top/Article/details/gt2qtxczsfp.html

[E04] 查找子串位置
来源：http://dali.ivvv.top/Article/details/gt2bxxwjtqw.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ydzc1.top/Article/details/gt2uzvxphgb.html

PHP:  strpos($s, "x");
来源：http://dali.cqqwz.cn/Article/details/gt2ofbpnhwm.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.shuidangran.top/Article/details/gt2weagezsj.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ybmrjvdb.html

Java: s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkknmnpc.html

Go:   strings.Index(s, "x")
来源：http://dali.jyoumei.cn/Article/details/gt2xjivvabx.html

Ruby: s.index("x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2vksehblo.html

C#:   s.IndexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2faocfhlz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xylfe.cn/Article/details/gt2gpetvwbj.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.bjfxy.top/Article/details/gt2gmjwukez.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.dianchejie.cn/Article/details/gt2kdmppmra.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gt2kyqytnmj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.tian-w.cn/Article/details/gt2qlspbxbs.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gt2btbroiny.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.dashuyun.cn/Article/details/gt2rvmwevil.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hysaishi.cn/Article/details/gt2dguosujj.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.cucudq.cn/Article/details/gt2kchathrh.html

[E06] 替换子串
来源：http://dali.kuanghao11.cn/Article/details/gt2iprrerhm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.shuidangran.top/Article/details/gt2cwqkfnrk.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hywenlv.cn/Article/details/gt2nbvkblsa.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2ghaxotnm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gt2ugdlqjeh.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gt2hbnsmzym.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.cqqwz.cn/Article/details/gt2cyvcpemw.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2tgvsquco.html

C#:   s.Replace("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kucqjxqo.html

[E07] 按分隔符拆分
来源：http://dali.shangyingyoupin.top/Article/details/gt2lsyfxasr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lbjwljct.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hysaishi.cn/Article/details/gt2wlyebifi.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.aibaodan.cn/Article/details/gt2aqzoetpc.html

TS:   s.split(",")
来源：http://dali.andypj.xyz/Article/details/gt2hqrbpcnd.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.yuxming.cn/Article/details/gt2famlesgu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.bjfxy.top/Article/details/gt2noiizpbb.html

Ruby: s.split(",");  s.split
来源：http://dali.pycfn.com/Article/details/gt2yzkxfhad.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.jqgfzy.top/Article/details/gt2rzewtkyy.html

[E08] 数组按分隔符合并
来源：http://dali.ivvv.top/Article/details/gt2bgdksptf.html

Py:   ",".join(items)
来源：http://dali.dashuyun.cn/Article/details/gt2yqskipkd.html

PHP:  implode(",", $items);
来源：http://dali.sysykeji.top/Article/details/gt2nbcrrykv.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcfbhlum.html

TS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gt2qeaembyj.html

Java: String.join(",", items)
来源：http://dali.redwolf501.top/Article/details/gt2qeubtscp.html

Go:   strings.Join(items, ",")
来源：http://dali.gzhubu.top/Article/details/gt2viiahvfz.html

Ruby: items.join(",")
来源：http://dali.tianlin.xyz/Article/details/gt2qlrpfkqi.html

C#:   string.Join(",", items)
来源：http://dali.sufxvd.cn/Article/details/gt2dionkxqj.html

[E09] 去除所有空白字符
来源：http://dali.0kj1m.cn/Article/details/gt2vhkqfmdy.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.daxiang520.top/Article/details/gt2dzwwsclv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.dashuyun.cn/Article/details/gt2kcsrkrxn.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258.top/Article/details/gt2bbiqtmyd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gt2jlaxaavb.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.fzhhl.top/Article/details/gt2nlsnjsnr.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pinvpood.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yonumen.top/Article/details/gt2zpmsymfc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jiagoushi.top/Article/details/gt2hgrpdnan.html

[E10] 左侧补零 / 定长填充
来源：http://dali.snrcjt.cn/Article/details/gt2wvbopiza.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.mhx1999.top/Article/details/gt2rhxuvlmr.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cucudq.cn/Article/details/gt2bgeztacb.html

JS:   "7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gt2xbyydpfw.html

TS:   "7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gt2frnusdos.html

Java: String.format("%03d", 7)
来源：http://dali.daria6918.cn/Article/details/gt2mhpmutrt.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.chenzaomai.com/Article/details/gt2ymbwbuwk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2tjgeplvc.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gt2swuqzaxj.html

[E11] 反转字符串
来源：http://dali.andypj.xyz/Article/details/gt2qsjlgsvm.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gt2ktsnzdth.html

PHP:  strrev($s);
来源：http://dali.zdqjudy.top/Article/details/gt2qmlzecyy.html

JS:   [...s].reverse().join("")
来源：http://dali.kuanghao11.cn/Article/details/gt2ooidiqqv.html

TS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2nmozocli.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.kuanghao11.cn/Article/details/gt2iqrozbzi.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhengqikj.top/Article/details/gt2iituwdal.html

Ruby: s.reverse
来源：http://dali.sxryk.cn/Article/details/gt2kwgahlfn.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj202588.top/Article/details/gt2zlugzqwb.html

[E12] 统计某字符出现次数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmrupmtr.html

Py:   s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gt2fsskqqch.html

PHP:  substr_count($s, "a");
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvgflzp.html

JS:   s.split("a").length - 1
来源：http://dali.cqqwz.cn/Article/details/gt2gazjqvao.html

TS:   s.split("a").length - 1
来源：http://dali.xylfe.cn/Article/details/gt2iasdyvbw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hzrefayf.html

Go:   strings.Count(s, "a")
来源：http://dali.vqdsnc.cn/Article/details/gt2inhhhxtf.html

Ruby: s.count("a")
来源：http://dali.chenzaomai.com/Article/details/gt2ypmjyuyy.html

C#:   s.Count(c => c == 'a')
来源：http://dali.hammf.cn/Article/details/gt2lmfddmzh.html

[E13] 逐字符遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2srqjnooq.html

Py:   for ch in s: print(ch)
来源：http://dali.tanke756.top/Article/details/gt2eihqnint.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zagsiuzm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yvedp.cn/Article/details/gt2lfzotxio.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.smart0.xyz/Article/details/gt2sysuofrp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jlsjyb.cn/Article/details/gt2izcfetkg.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.snrcjt.cn/Article/details/gt2cxrvrdpl.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.tanke756.top/Article/details/gt2kyfvsohu.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jianghu66.top/Article/details/gt2satoooso.html

[E14] URL 编码与 Base64
来源：http://dali.guannengcc.top/Article/details/gt2sncpjhfh.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yuanzhike.top/Article/details/gt2wbwdbftu.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ajkvywal.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.wangshuangyany.cn/Article/details/gt2uuxiecvo.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tanke756.top/Article/details/gt2zcmaikke.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.chenlongwang.top/Article/details/gt2wjdtpbqg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gt2xipclltl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nfatcueu.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fzhhl.top/Article/details/gt2hfjlfzbk.html

[E15] HTML 转义 / 反转义
来源：http://dali.pengpengdd.cyou/Article/details/gt2jqkiaiwp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zycfv.cn/Article/details/gt2bkrvmutb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.ivvv.top/Article/details/gt2gtuhsawd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.pycfn.com/Article/details/gt2drjwqikn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.dianchejie.cn/Article/details/gt2waalpzam.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gt2clloogfc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.9152youxi.cn/Article/details/gt2pajhsocn.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hywenlv.cn/Article/details/gt2atgeutjk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.316326.xyz/Article/details/gt2vepydykv.html

[E16] 数字千分位
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctrbqkqy.html

Py:   f"{1234567:,}"
来源：http://dali.yuanzhike.top/Article/details/gt2ybmfpyds.html

PHP:  number_format(1234567);
来源：http://dali.yueranfly.top/Article/details/gt2iuyvqlse.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258888.top/Article/details/gt2zpdgtcdq.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jianghu66.top/Article/details/gt2womejsix.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gt2zeixkhpm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gt2jbqecony.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shuidangran.top/Article/details/gt2tomqklmj.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gt2puesriof.html

[E17] 首字母大写
来源：http://dali.sysykeji.top/Article/details/gt2livzxfex.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gt2vsgwbqnx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.xziqi.cn/Article/details/gt2borfzuzg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.andypj.xyz/Article/details/gt2oqabgjvg.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gt2xrnrzmyp.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.ydzc1.top/Article/details/gt2zfvlvmva.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gt2xpwpkcbx.html

Ruby: s.capitalize
来源：http://dali.yonumen.top/Article/details/gt2bqkayikq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shuidangran.top/Article/details/gt2dvhvgthx.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gt2njgerfgy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shzxlz.cn/Article/details/gt2mzwopyvx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbadiuuk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.jlsjyb.cn/Article/details/gt2qtxupgvp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhixingplan.top/Article/details/gt2npygxtex.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.redwolf501.top/Article/details/gt2uowapqzf.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kpvmwksq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gogol.net.cn/Article/details/gt2qdlggsaa.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnsmryv.html

[E19] 多行文本按行拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2yttqelnl.html

Py:   s.splitlines()
来源：http://dali.pycfn.com/Article/details/gt2xyiuhzrg.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2eodhrgzo.html

JS:   s.split(/\r?\n/)
来源：http://dali.9152youxi.cn/Article/details/gt2pvxdwvro.html

TS:   s.split(/\r?\n/)
来源：http://dali.0kj1m.cn/Article/details/gt2qsfqmfvy.html

Java: s.lines().toList()
来源：http://dali.cashguo.top/Article/details/gt2gimbpiav.html

Go:   strings.Split(s, "\n")
来源：http://dali.cashguo.top/Article/details/gt2fgphapzj.html

Ruby: s.lines
来源：http://dali.wangshuangyany.cn/Article/details/gt2hlxdjqri.html

C#:   s.Split('\n')
来源：http://dali.xziqi.cn/Article/details/gt2wlnshgsh.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gt2vgxswdim.html

Py:   if not s:
来源：http://dali.ybcxt.top/Article/details/gt2ehvrcovp.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrjunne.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhengqikj.top/Article/details/gt2nyzqirxb.html

TS:   if (s === "") {}
来源：http://dali.aizwys.cn/Article/details/gt2fwlsgtql.html

Java: if (s.isEmpty()) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2iizcapgq.html

Go:   if s == "" {}
来源：http://dali.shzxlz.cn/Article/details/gt2mnrygqjn.html

Ruby: if s.empty?
来源：http://dali.zycfv.cn/Article/details/gt2fftcslxd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2okpznbxa.html

[E21] 超长截断加省略号
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ihunvtxi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.pengpengdd.cyou/Article/details/gt2hbnjlwef.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgwwwrsc.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhixingplan.top/Article/details/gt2sdmxakro.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2bgdtcevy.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gt2qxcrkwqf.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hammf.cn/Article/details/gt2pexvimfx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2pbxziqhp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.mhx1999.top/Article/details/gt2vrzbbsny.html

[E22] 字节长度与字符长度
来源：http://dali.zhixingplan.top/Article/details/gt2fqrdbfrl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.yuanzhike.top/Article/details/gt2takkidix.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gt2wrdkhjxi.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.c1oappe.top/Article/details/gt2qthfcaet.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gt2xbgumwbx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.meibo888.top/Article/details/gt2cavgidud.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.iojbl.cn/Article/details/gt2vsrubppc.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuxming.cn/Article/details/gt2xowcwhkd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dohowgre.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2bebvxsbx.html

F. 文件与目录
来源：http://dali.jyoumei.cn/Article/details/gt2nspmnncw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2rfkgcjwl.html

[F01] 读取整个文件
来源：http://dali.zhongyouzk.top/Article/details/gt2ftjapbzb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258888.top/Article/details/gt2zwfsbjux.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvxmuizr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.chenlongwang.top/Article/details/gt2rfyvnyuw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.chenjidiqi.icu/Article/details/gt2rtyzecbq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2updcbuyw.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.redwolf501.top/Article/details/gt2jmfeskhu.html

Ruby: File.read("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2azlltmpl.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lstlvuvw.html

[F02] 逐行读取文件
来源：http://dali.zhixingplan.top/Article/details/gt2lqoneyib.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.havefunace.top/Article/details/gt2yiwwskem.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fengsongda.top/Article/details/gt2lftoydum.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2efymtomm.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ehwqpu.com/Article/details/gt2gypieqff.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.daxiang520.top/Article/details/gt2ardsknmp.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgfzy.top/Article/details/gt2aiaquqpd.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.cucudq.cn/Article/details/gt2csuapetg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.sysykeji.top/Article/details/gt2dtgxisyr.html

[F03] 写入文件（覆盖）
来源：http://dali.zhixingplan.top/Article/details/gt2ivfrartb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xziqi.cn/Article/details/gt2dvjxnrxk.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.meibo888.top/Article/details/gt2lxyvdxpc.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xthjgbxe.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gt2bsfjbopl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hywenlv.cn/Article/details/gt2uqnsrxoe.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cqqwz.cn/Article/details/gt2jrfhlayv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.dashuyun.cn/Article/details/gt2ctrxqqow.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jqgufenzy.top/Article/details/gt2memhcnjx.html

[F04] 追加写入文件
来源：http://dali.jiagoushi.top/Article/details/gt2fzuflpey.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.cashguo.top/Article/details/gt2udiaxbjd.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuanzhike.top/Article/details/gt2bwootcqr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.mhx1999.top/Article/details/gt2vloeynmn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2ncrifadl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jinqigfzy.top/Article/details/gt2jqbilsxy.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yj202588.top/Article/details/gt2dcoobruy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.wangdashe.top/Article/details/gt2xuomybov.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.nwbrower.top/Article/details/gt2xecqwfty.html

[F05] 判断文件或目录是否存在
来源：http://dali.jqgfzy.top/Article/details/gt2vbapowon.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.aibaodan.cn/Article/details/gt2xrhdazto.html

PHP:  file_exists("a.txt");
来源：http://dali.zhongyouzk.top/Article/details/gt2ckhfujnk.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2sfijqxiv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2wdhxewyg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jinqigfzy.top/Article/details/gt2dytmbvzc.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.aibaodan.cn/Article/details/gt2nzjygjxe.html

Ruby: File.exist?("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gt2kspdfgzz.html

C#:   File.Exists("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2bphslijw.html

[F06] 删除文件
来源：http://dali.tanke756.top/Article/details/gt2loajyamz.html

Py:   os.remove("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2xluxmovk.html

PHP:  unlink("a.txt");
来源：http://dali.aizwys.cn/Article/details/gt2wbhwixwq.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2dpmhxmsj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2ompqpwoh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2xrkprpyd.html

Go:   os.Remove("a.txt")
来源：http://dali.sweek.top/Article/details/gt2ahbqhdkh.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2dvhzgxhy.html

C#:   File.Delete("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2zezahghd.html

[F07] 创建目录（含多级）
来源：http://dali.zhoulong.xyz/Article/details/gt2ylgvyyft.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dszdbvmo.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.hfpthk.cn/Article/details/gt2ekmawsfx.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.tianlin.xyz/Article/details/gt2lkvxzysg.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gt2utcvmscr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gt2sutvykjq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shuidangran.top/Article/details/gt2afacieru.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xuanzx.com/Article/details/gt2ziwbxkmb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhengqikj.top/Article/details/gt2enggjgnz.html

[F08] 遍历目录
来源：http://dali.c1oappe.top/Article/details/gt2duxttddr.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.0kj1m.cn/Article/details/gt2gzxcvyju.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqrosvbi.html

JS:   fs.readdirSync("dir")
来源：http://dali.jqgufenzy.top/Article/details/gt2xfdmdsmt.html

TS:   fs.readdirSync("dir")
来源：http://dali.gzhubu.top/Article/details/gt2cujyudmm.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.cashguo.top/Article/details/gt2enexngmb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aizwys.cn/Article/details/gt2xqcpkeit.html

Ruby: Dir.children("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2tahhfzne.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cucudq.cn/Article/details/gt2tssdbpks.html

[F09] 获取文件大小
来源：http://dali.wangshuangyany.cn/Article/details/gt2qohahbqq.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2suvpyuqk.html

PHP:  filesize("a.txt");
来源：http://dali.gzhubu.top/Article/details/gt2ecuagjmt.html

JS:   fs.statSync("a.txt").size
来源：http://dali.nanxuanxn.top/Article/details/gt2eompikye.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xylfe.cn/Article/details/gt2jdvouwlm.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gt2haagsxoq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gt2rsopvzzo.html

Ruby: File.size("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2xjdphkqg.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yongpay.top/Article/details/gt2ysokmotj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hammf.cn/Article/details/gt2rzixursg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2echnumel.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2thphojlo.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gt2jzwxdahn.html

TS:   path.extname("a.txt")
来源：http://dali.c1oappe.top/Article/details/gt2dbxegzyq.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.tianlin.xyz/Article/details/gt2xcqhnqmz.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2jcwzdghk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cidawahl.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yonumen.top/Article/details/gt2hqlcxlto.html

[F11] 复制与移动文件
来源：http://dali.chenlongwang.top/Article/details/gt2zqrrhvvt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2gqgrerqf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gt2pumclhqa.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kbioteyn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ydzc1.top/Article/details/gt2wbtelpot.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.svipenyu.cn/Article/details/gt2dxvuljjv.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aizwys.cn/Article/details/gt2ypplnwzq.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2wnuadkib.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.chenlongwang.top/Article/details/gt2smtomzhd.html

[F12] CSV 读写
来源：http://dali.yuanzhike.top/Article/details/gt2zsmahubu.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yyahtfcc.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sweek.top/Article/details/gt2nwfkmllf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gt2buasztcf.html

TS:   // 同上
来源：http://dali.hnxiangtu.top/Article/details/gt2itkdrjbx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gt2wmqromis.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.vqdsnc.cn/Article/details/gt2cmelirdp.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gt2bgequvbf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.yvedp.cn/Article/details/gt2ejtxkkbl.html


<!-- 参考信息 -->