代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xuetiantiany.cn/Article/details/gt2djipuvkb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tslfrbaw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xlafbbvl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.xuetiantiany.cn/Article/details/gt2rxccbiuj.html

[E02] 重复字符串
来源：http://dali.cheryme.top/Article/details/gt2clzugcju.html

Py:   "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fbuyqbuq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258888.top/Article/details/gt2oyakxjrn.html

JS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2bbjgwfmp.html

TS:   "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mvhsquvl.html

Java: "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2laqzgmmt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jlsjyb.cn/Article/details/gt2uiplmllw.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pmthfwsr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.tanke756.top/Article/details/gt2blkfmhkb.html

[E03] 截取子串
来源：http://dali.ppjwa.cn/Article/details/gt2solbcsyp.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sufxvd.cn/Article/details/gt2zngrrese.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gt2vrqwwstn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2kxywdotg.html

TS:   s.slice(1, 4)
来源：http://dali.cashguo.top/Article/details/gt2dxigbmwq.html

Java: s.substring(1, 4)
来源：http://dali.sxryk.cn/Article/details/gt2wueemsra.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2psigtqco.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gt2lsvyfnso.html

C#:   s.Substring(1, 3)
来源：http://dali.hnqzz.top/Article/details/gt2kldontyn.html

[E04] 查找子串位置
来源：http://dali.redwolf501.top/Article/details/gt2paossgvd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pqkuvmek.html

PHP:  strpos($s, "x");
来源：http://dali.hfpthk.cn/Article/details/gt2uudltaum.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yueranfly.top/Article/details/gt2wkcjdwjd.html

TS:   s.indexOf("x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tgaanjku.html

Java: s.indexOf("x")
来源：http://dali.0kj1m.cn/Article/details/gt2kvyuswbq.html

Go:   strings.Index(s, "x")
来源：http://dali.jqgufenzy.top/Article/details/gt2aeszgzjx.html

Ruby: s.index("x")
来源：http://dali.zdqjudy.top/Article/details/gt2dchfynzj.html

C#:   s.IndexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gt2kgyrlgud.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.sweek.top/Article/details/gt2hlllxpfu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ybcxt.top/Article/details/gt2ogwyguor.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sxryk.cn/Article/details/gt2czwwqhih.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gt2ymwrflpf.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxykvmfa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tanke756.top/Article/details/gt2nirrywcf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.xuanzx.com/Article/details/gt2ezkoajdk.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2iarhrykn.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.iojbl.cn/Article/details/gt2tehknwvf.html

[E06] 替换子串
来源：http://dali.9152youxi.cn/Article/details/gt2ejhjbhmh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.havefunace.top/Article/details/gt2xvanszjd.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yonumen.top/Article/details/gt2tripqhxh.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2bwzsviva.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2stumgexx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iizobnmy.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2iqerulir.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2ytrpgwqe.html

C#:   s.Replace("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2nctamfsf.html

[E07] 按分隔符拆分
来源：http://dali.wangshuangyany.cn/Article/details/gt2jhhmbwsr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.svipenyu.cn/Article/details/gt2ogqnmovv.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.cqqwz.cn/Article/details/gt2mhbguzod.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hnqzz.top/Article/details/gt2vtvvrasw.html

TS:   s.split(",")
来源：http://dali.jinqigufen.top/Article/details/gt2iqtajpxz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ppjwa.cn/Article/details/gt2qhyuxsgj.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258888.top/Article/details/gt2mpwtvumg.html

Ruby: s.split(",");  s.split
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kihfhckg.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bacilfnv.html

[E08] 数组按分隔符合并
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjxygaiu.html

Py:   ",".join(items)
来源：http://dali.jinqigufen.top/Article/details/gt2azpxehgn.html

PHP:  implode(",", $items);
来源：http://dali.xziqi.cn/Article/details/gt2htbthkpc.html

JS:   items.join(",")
来源：http://dali.zdqjudy.top/Article/details/gt2ydjesvat.html

TS:   items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gt2jhqlqfey.html

Java: String.join(",", items)
来源：http://dali.birdmap.top/Article/details/gt2ycqfivap.html

Go:   strings.Join(items, ",")
来源：http://dali.hfpthk.cn/Article/details/gt2yqztbbno.html

Ruby: items.join(",")
来源：http://dali.snrcjt.cn/Article/details/gt2haiaynir.html

C#:   string.Join(",", items)
来源：http://dali.yuxming.cn/Article/details/gt2iiorgehm.html

[E09] 去除所有空白字符
来源：http://dali.hysaishi.cn/Article/details/gt2trhkyxfu.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cqqwz.cn/Article/details/gt2rirgmgwt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oaelpapy.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.daria6918.cn/Article/details/gt2qkunlfpb.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenlongwang.top/Article/details/gt2lnvntwos.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.tian-w.cn/Article/details/gt2tpdrqftm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.zhoulong.xyz/Article/details/gt2ewbyvfuj.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.guannengcc.top/Article/details/gt2ugeokuyo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.cucudq.cn/Article/details/gt2jyduqrzf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hongshengwenyu.top/Article/details/gt2hsnsewee.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.gogol.net.cn/Article/details/gt2ddtuinmg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.nanxinkj.top/Article/details/gt2fyooljze.html

JS:   "7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2hiwrsvwb.html

TS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2qsqsrnob.html

Java: String.format("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gt2ttgpklmu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lusfprsy.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gt2mwnywnju.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.gogol.net.cn/Article/details/gt2oeawdgfs.html

[E11] 反转字符串
来源：http://dali.c1oappe.top/Article/details/gt2exijbvwt.html

Py:   s[::-1]
来源：http://dali.gogol.net.cn/Article/details/gt2ynqilkbh.html

PHP:  strrev($s);
来源：http://dali.aizwys.cn/Article/details/gt2hkurxxki.html

JS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gt2trsodhmy.html

TS:   [...s].reverse().join("")
来源：http://dali.hysaishi.cn/Article/details/gt2gexvjkya.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yangfankeji.com/Article/details/gt2flvedupu.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.nanxinkj.top/Article/details/gt2mtfzixsw.html

Ruby: s.reverse
来源：http://dali.vqdsnc.cn/Article/details/gt2edvutoop.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.jqgfzy.top/Article/details/gt2ctlcwjtu.html

[E12] 统计某字符出现次数
来源：http://dali.ivvv.top/Article/details/gt2tanelggk.html

Py:   s.count("a")
来源：http://dali.yonumen.top/Article/details/gt2osquvfsr.html

PHP:  substr_count($s, "a");
来源：http://dali.shuidangran.top/Article/details/gt2qvzbwrqi.html

JS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gt2mzmfgxns.html

TS:   s.split("a").length - 1
来源：http://dali.quarkkingdee.top/Article/details/gt2jitafdoh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.hysaishi.cn/Article/details/gt2ipjlsakv.html

Go:   strings.Count(s, "a")
来源：http://dali.ydzc1.top/Article/details/gt2iolgevse.html

Ruby: s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gt2muittogf.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gt2ohcnnicd.html

[E13] 逐字符遍历
来源：http://dali.yueranfly.top/Article/details/gt2tlmmbxtg.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gt2kmxzvxpb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yonumen.top/Article/details/gt2juibeesp.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daria6918.cn/Article/details/gt2bkzhtqmi.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhengqikj.top/Article/details/gt2sbuybhdp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jyoumei.cn/Article/details/gt2bfbosyff.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.fzhhl.top/Article/details/gt2iboiuplb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.guowangkeji.top/Article/details/gt2zfcsepfb.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yongpay.top/Article/details/gt2vnnnyvnr.html

[E14] URL 编码与 Base64
来源：http://dali.cashguo.top/Article/details/gt2szbockhr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jianghu66.top/Article/details/gt2yoqyugan.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.svipenyu.cn/Article/details/gt2nkwibedc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.meibo888.top/Article/details/gt2jvpqxbky.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxinkj.top/Article/details/gt2ybstfeqw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jqgufenzy.top/Article/details/gt2wugjhaxy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxteoobe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnqzz.top/Article/details/gt2qcjgjdbk.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.nanxuanxn.top/Article/details/gt2mmilqfbp.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhengqikj.top/Article/details/gt2lsdjwigt.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shzxlz.cn/Article/details/gt2mfwmqsrn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yangfankeji.com/Article/details/gt2ssnbnmtt.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gt2iqcmgeph.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ehwqpu.com/Article/details/gt2lmgpiten.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.dianchejie.cn/Article/details/gt2nexnkfgf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2eideegqa.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gt2dxtymetf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.svipenyu.cn/Article/details/gt2xqchhnuw.html

[E16] 数字千分位
来源：http://dali.andypj.xyz/Article/details/gt2yebvmyxr.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258888.top/Article/details/gt2iqghvwqv.html

PHP:  number_format(1234567);
来源：http://dali.xuetiantiany.cn/Article/details/gt2olczxvqz.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fodlgaff.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.havefunace.top/Article/details/gt2gflojtpg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daria6918.cn/Article/details/gt2wzascywz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.sweek.top/Article/details/gt2dqfltmmc.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.pycfn.com/Article/details/gt2owgbiqxo.html

C#:   1234567.ToString("N0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqssfvkm.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gt2acwngmgi.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqrmodmg.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.tian-w.cn/Article/details/gt2wwvnbjpl.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gt2eevndkft.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.dianchejie.cn/Article/details/gt2gywgazjc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pndymawz.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.fzhhl.top/Article/details/gt2woiglmsg.html

Ruby: s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gt2bbfjvqjw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.nanxuanxn.top/Article/details/gt2vzjtawrd.html

[E18] 模板占位符替换
来源：http://dali.meibo888.top/Article/details/gt2ymslknwh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhoulong.xyz/Article/details/gt2ukrgwveq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgfzy.top/Article/details/gt2kglaesxs.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.tanke756.top/Article/details/gt2myvwnvqd.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gt2sytyhksa.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.vqdsnc.cn/Article/details/gt2pkeakukm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.c1oappe.top/Article/details/gt2giwbefaq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.redwolf501.top/Article/details/gt2tudabuyp.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.gaohongyu789.top/Article/details/gt2rdgxsrwp.html

[E19] 多行文本按行拆分
来源：http://dali.vqdsnc.cn/Article/details/gt2hcgganvp.html

Py:   s.splitlines()
来源：http://dali.hfpthk.cn/Article/details/gt2dawscpmc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2xgxqbpdm.html

JS:   s.split(/\r?\n/)
来源：http://dali.yangfankeji.com/Article/details/gt2fncfkymw.html

TS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gt2lqokclya.html

Java: s.lines().toList()
来源：http://dali.ehwqpu.com/Article/details/gt2xiztijjy.html

Go:   strings.Split(s, "\n")
来源：http://dali.tanke756.top/Article/details/gt2lbcmijsi.html

Ruby: s.lines
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwyxkkfm.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gt2yeebosko.html

[E20] 判断字符串是否为空
来源：http://dali.fzhhl.top/Article/details/gt2hgfhafhe.html

Py:   if not s:
来源：http://dali.jyoumei.cn/Article/details/gt2xhdciwlg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.sysykeji.top/Article/details/gt2otevuddx.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gt2ybtnedpy.html

TS:   if (s === "") {}
来源：http://dali.cashguo.top/Article/details/gt2itvakzdx.html

Java: if (s.isEmpty()) {}
来源：http://dali.daria6918.cn/Article/details/gt2hfogsjjg.html

Go:   if s == "" {}
来源：http://dali.yanxiufei.cn/Article/details/gt2bmfbrhsw.html

Ruby: if s.empty?
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbybjvnp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.fengsongda.top/Article/details/gt2tegxwaok.html

[E21] 超长截断加省略号
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vxuvppvr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jlsjyb.cn/Article/details/gt2icnjtwkm.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.chenzaomai.com/Article/details/gt2gdrrjpdk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xuetiantiany.cn/Article/details/gt2xasivlrx.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.birdmap.top/Article/details/gt2ufwvmapl.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2dsehjvkx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.wangdashe.top/Article/details/gt2zawwuokl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2ssujueid.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nanxuanxn.top/Article/details/gt2cikwkczu.html

[E22] 字节长度与字符长度
来源：http://dali.chenzaomai.com/Article/details/gt2jovbmoke.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zdqjudy.top/Article/details/gt2qxvqausu.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2methjdwo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cucudq.cn/Article/details/gt2iigqmqzr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.guannengcc.top/Article/details/gt2btwxjymd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2givngvvn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.pengpengdd.cyou/Article/details/gt2egcpllvs.html

Ruby: s.bytesize;  s.length
来源：http://dali.havefunace.top/Article/details/gt2nmapyrja.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.vqdsnc.cn/Article/details/gt2clvckmoh.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2aicjwuzs.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gt2junygkmg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2pyejpbcp.html

[F01] 读取整个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ugniypdo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.chenzaomai.com/Article/details/gt2evpzetdb.html

PHP:  file_get_contents("a.txt");
来源：http://dali.bjfxy.top/Article/details/gt2sqpnxfsf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbjbaatq.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2jlsnsruz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2azrqjcvq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.daria6918.cn/Article/details/gt2fwmyqbmb.html

Ruby: File.read("a.txt")
来源：http://dali.daria6918.cn/Article/details/gt2azlvoznw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2iapdyumu.html

[F02] 逐行读取文件
来源：http://dali.cqqwz.cn/Article/details/gt2zfzbqwte.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gt2vimabwca.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gt2yvzjgnnz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbjdxhjf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yuxming.cn/Article/details/gt2sfsqjirf.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.snrcjt.cn/Article/details/gt2latweybw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gt2sjdzdoxv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.vqdsnc.cn/Article/details/gt2daqwqdzr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gt2rqvsbrxv.html

[F03] 写入文件（覆盖）
来源：http://dali.shzxlz.cn/Article/details/gt2pqnpqems.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcayzeay.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jiagoushi.top/Article/details/gt2phiahqye.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.tianlin.xyz/Article/details/gt2gnkbbcrg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuanzx.com/Article/details/gt2gcqhcqrj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmpbvjbv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yangfankeji.com/Article/details/gt2upbjndfs.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jinqigfzy.top/Article/details/gt2avvrfwqg.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hongshengwenyu.top/Article/details/gt2yylvgwev.html

[F04] 追加写入文件
来源：http://dali.hnqzz.top/Article/details/gt2jwgmakqh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zhoizmtq.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hfpthk.cn/Article/details/gt2aoagrhtt.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zycfv.cn/Article/details/gt2qvstkkup.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gt2avkhlloi.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.gotoacloud.top/Article/details/gt2hkgrniat.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2brgmuuob.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rgfbunru.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj202588.top/Article/details/gt2dvyeyyqh.html

[F05] 判断文件或目录是否存在
来源：http://dali.meibo888.top/Article/details/gt2pvaccctx.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cqqwz.cn/Article/details/gt2qnjdledv.html

PHP:  file_exists("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2honedqsd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2ldnfqgyd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2viphbiiq.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2cfblaezi.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hywenlv.cn/Article/details/gt2dwoyzijd.html

Ruby: File.exist?("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2isnjggsf.html

C#:   File.Exists("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2oerkksmq.html

[F06] 删除文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ofaabcyd.html

Py:   os.remove("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2jfjnplag.html

PHP:  unlink("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2mbidgzza.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2osfvsjhw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ntpynepx.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.svipenyu.cn/Article/details/gt2lxishpfa.html

Go:   os.Remove("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2fjaevbpa.html

Ruby: File.delete("a.txt")
来源：http://dali.cashguo.top/Article/details/gt2ntqihgyl.html

C#:   File.Delete("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2cjrizrbu.html

[F07] 创建目录（含多级）
来源：http://dali.yvedp.cn/Article/details/gt2xdqnpweo.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.fengsongda.top/Article/details/gt2hbjgwyaj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangdashe.top/Article/details/gt2pwbyozaw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gt2toerppdy.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.ybcxt.top/Article/details/gt2jxmxyixd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2odfpdeag.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.wangdashe.top/Article/details/gt2uqwerrdk.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.316326.xyz/Article/details/gt2dlvssphn.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.smart0.xyz/Article/details/gt2leuyhcgk.html

[F08] 遍历目录
来源：http://dali.xinyue.icu/Article/details/gt2awyjbhja.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.sufxvd.cn/Article/details/gt2qnkxcomh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.gzhubu.top/Article/details/gt2umofgfhs.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2toklfxwg.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258888.top/Article/details/gt2imijiweo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.9152youxi.cn/Article/details/gt2epxvjpxi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.gogol.net.cn/Article/details/gt2hbfagcyv.html

Ruby: Dir.children("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2zvvnkmtf.html

C#:   Directory.GetFiles("dir")
来源：http://dali.aibaodan.cn/Article/details/gt2cjksjpnp.html

[F09] 获取文件大小
来源：http://dali.nwbrower.top/Article/details/gt2gtdeqlyz.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2qmxkkccj.html

PHP:  filesize("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2mhixmabk.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gt2huqytcvk.html

TS:   fs.statSync("a.txt").size
来源：http://dali.tanke756.top/Article/details/gt2tqybijjy.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2ncezfbjl.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cheryme.top/Article/details/gt2cqnnfulm.html

Ruby: File.size("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2icxckrsh.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigfzy.top/Article/details/gt2ddkawjmj.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hywenlv.cn/Article/details/gt2zymimghz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ybumvikf.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.hysaishi.cn/Article/details/gt2yjjjkqgi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2orydvgml.html

TS:   path.extname("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2fvusdlks.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.xinyue.icu/Article/details/gt2mkkjqaij.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2vdmcoczm.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2qmgyrinp.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gt2fzfwqkof.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gt2yyskksec.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2gkbicajj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.dashuyun.cn/Article/details/gt2eunrpkox.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ixndfsvv.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2emzffyic.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.mhx1999.top/Article/details/gt2akidmctp.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.pycfn.com/Article/details/gt2feupwfqa.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2axttihpj.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.dashuyun.cn/Article/details/gt2grnunzdx.html

[F12] CSV 读写
来源：http://dali.jinqigfzy.top/Article/details/gt2wkanyswi.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yanxiufei.cn/Article/details/gt2thqjvtmv.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.nanxuanxn.top/Article/details/gt2fwvpsxbz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.gzhubu.top/Article/details/gt2yzizkbay.html

TS:   // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fludjmwc.html


<!-- 参考信息 -->