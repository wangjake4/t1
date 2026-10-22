代发 wailian999

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yangfankeji.com/Article/details/gt2pnguokii.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2nqygfkaa.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jnjtlmmc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gt2jiqckjpu.html

[E02] 重复字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pycqcnkn.html

Py:   "ab" * 3
来源：http://dali.sxryk.cn/Article/details/gt2tdzzjabo.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yangfankeji.com/Article/details/gt2fxgbdrdg.html

JS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gt2ddwyctrt.html

TS:   "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gt2hzmhdhyq.html

Java: "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gt2ygvvogns.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2zjgebtqp.html

Ruby: "ab" * 3
来源：http://dali.wangshuangyany.cn/Article/details/gt2zopvkefu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fengsongda.top/Article/details/gt2uqineifv.html

[E03] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gt2mokejpuy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sysykeji.top/Article/details/gt2rasdibbo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.haohaochexian.top/Article/details/gt2yosmkuvb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gzhubu.top/Article/details/gt2bocgxrpb.html

TS:   s.slice(1, 4)
来源：http://dali.aizwys.cn/Article/details/gt2hvygeqbh.html

Java: s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kbwlzdph.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dianchejie.cn/Article/details/gt2xluwjrdo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.yj20258.top/Article/details/gt2ggzviijk.html

C#:   s.Substring(1, 3)
来源：http://dali.daria6918.cn/Article/details/gt2jeygqtlb.html

[E04] 查找子串位置
来源：http://dali.chenzaomai.com/Article/details/gt2axiyvenf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2xzevuznm.html

PHP:  strpos($s, "x");
来源：http://dali.smart0.xyz/Article/details/gt2ievlwpej.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.bjfxy.top/Article/details/gt2tgpkdgev.html

TS:   s.indexOf("x")
来源：http://dali.wangdashe.top/Article/details/gt2fzyabdma.html

Java: s.indexOf("x")
来源：http://dali.bjfxy.top/Article/details/gt2xmfcsdpk.html

Go:   strings.Index(s, "x")
来源：http://dali.yanxiufei.cn/Article/details/gt2nzggxogr.html

Ruby: s.index("x")
来源：http://dali.cucudq.cn/Article/details/gt2rxvupgyx.html

C#:   s.IndexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gt2kcltxcfv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.daria6918.cn/Article/details/gt2bfqfphyu.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.redwolf501.top/Article/details/gt2awsavkng.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.mhx1999.top/Article/details/gt2ukqchruf.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gt2fyeynohs.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.haohaochexian.top/Article/details/gt2vyhjfquj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.tian-w.cn/Article/details/gt2makwdrzr.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zhijiandao.cn/Article/details/gt2mjoxovvt.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.daxiang520.top/Article/details/gt2scgsioux.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fforqxos.html

[E06] 替换子串
来源：http://dali.zhiwuduotai.top/Article/details/gt2dljftqmx.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gt2tqsnbmid.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.andypj.xyz/Article/details/gt2fqggnjbp.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gt2nostkafx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aizwys.cn/Article/details/gt2ybufkigl.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gt2xpxoxekm.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.tian-w.cn/Article/details/gt2atwqvrhc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fojupjtn.html

C#:   s.Replace("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2cvnxfugb.html

[E07] 按分隔符拆分
来源：http://dali.jlsjyb.cn/Article/details/gt2hfqdekuo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.xuanzx.com/Article/details/gt2wuyfaokf.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.andypj.xyz/Article/details/gt2bbmcvvov.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yuxming.cn/Article/details/gt2lewpeoks.html

TS:   s.split(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wuudtjhm.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ehwqpu.com/Article/details/gt2lmigcxgc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.xuanzx.com/Article/details/gt2dbdbnpzk.html

Ruby: s.split(",");  s.split
来源：http://dali.xylfe.cn/Article/details/gt2rtjmjejf.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gt2aptfjzxq.html

[E08] 数组按分隔符合并
来源：http://dali.zhixingplan.top/Article/details/gt2fbahmcpb.html

Py:   ",".join(items)
来源：http://dali.pycfn.com/Article/details/gt2aafmtrcp.html

PHP:  implode(",", $items);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ifadipxj.html

JS:   items.join(",")
来源：http://dali.xinyue.icu/Article/details/gt2fnzvupng.html

TS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gt2qbhluoyj.html

Java: String.join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gt2kkglvzqm.html

Go:   strings.Join(items, ",")
来源：http://dali.shuidangran.top/Article/details/gt2wgihepko.html

Ruby: items.join(",")
来源：http://dali.ydzc1.top/Article/details/gt2aainkdif.html

C#:   string.Join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gt2fugkwyzg.html

[E09] 去除所有空白字符
来源：http://dali.yueranfly.top/Article/details/gt2kumyafry.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzgocmsn.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.gzhubu.top/Article/details/gt2myuahzjl.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gt2ajmwkynw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ydzc1.top/Article/details/gt2lpeqbzfs.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cucudq.cn/Article/details/gt2wajzsgvm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.xuanzx.com/Article/details/gt2twuzvtse.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.sxryk.cn/Article/details/gt2zdqnrimi.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.chenzaomai.com/Article/details/gt2zlhiglcq.html

[E10] 左侧补零 / 定长填充
来源：http://dali.cheryme.top/Article/details/gt2tvlsykdd.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gt2zsxuunea.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hammf.cn/Article/details/gt2kjdjdunw.html

JS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gt2sukdpcud.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gt2ipwfxlqi.html

Java: String.format("%03d", 7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yatdksdd.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gt2uzlblhia.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yuanzhike.top/Article/details/gt2sqgahnqs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jyoumei.cn/Article/details/gt2abijztkd.html

[E11] 反转字符串
来源：http://dali.jianghu66.top/Article/details/gt2eghqakgy.html

Py:   s[::-1]
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjihtsiw.html

PHP:  strrev($s);
来源：http://dali.dashuyun.cn/Article/details/gt2wqvwsxyf.html

JS:   [...s].reverse().join("")
来源：http://dali.xziqi.cn/Article/details/gt2prwafhcp.html

TS:   [...s].reverse().join("")
来源：http://dali.pengpengdd.cyou/Article/details/gt2intcsjlz.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tanke756.top/Article/details/gt2aiyjazng.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hammf.cn/Article/details/gt2xeheedvm.html

Ruby: s.reverse
来源：http://dali.svipenyu.cn/Article/details/gt2jpqfkrhd.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yj20258888.top/Article/details/gt2whwvctrz.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gt2hevbymbd.html

Py:   s.count("a")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujimdxyt.html

PHP:  substr_count($s, "a");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhjlhjab.html

JS:   s.split("a").length - 1
来源：http://dali.yuanzhike.top/Article/details/gt2cokwuffn.html

TS:   s.split("a").length - 1
来源：http://dali.wangdashe.top/Article/details/gt2eofmqlvx.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gt2qctuzjik.html

Go:   strings.Count(s, "a")
来源：http://dali.fzhhl.top/Article/details/gt2gzzobfye.html

Ruby: s.count("a")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vhduwrfw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.nwbrower.top/Article/details/gt2pxkfxovb.html

[E13] 逐字符遍历
来源：http://dali.tian-w.cn/Article/details/gt2mdjjpmfd.html

Py:   for ch in s: print(ch)
来源：http://dali.guowangkeji.top/Article/details/gt2gjxotawj.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shzxlz.cn/Article/details/gt2yerdjuwk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.shzxlz.cn/Article/details/gt2ewhsvbrh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hysaishi.cn/Article/details/gt2zgggdwhs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cqqwz.cn/Article/details/gt2fmdidihl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gt2ixtsffua.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yj20258888.top/Article/details/gt2lobjorpc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.redwolf501.top/Article/details/gt2pjpnmjtz.html

[E14] URL 编码与 Base64
来源：http://dali.quarkkingdee.top/Article/details/gt2slzciqhc.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jqgufenzy.top/Article/details/gt2egcjufcm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.dianchejie.cn/Article/details/gt2emdkvyic.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yueranfly.top/Article/details/gt2rixzoysd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.bjfxy.top/Article/details/gt2qzdkxawj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yonumen.top/Article/details/gt2bkkcizbg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gt2ariovmpm.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yuxming.cn/Article/details/gt2urihfnau.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ttfqtbhs.html

[E15] HTML 转义 / 反转义
来源：http://dali.ppjwa.cn/Article/details/gt2kmttdodj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ppjwa.cn/Article/details/gt2pczuxvil.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gt2pqddembu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.zdqjudy.top/Article/details/gt2dumnmlrv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xylfe.cn/Article/details/gt2lssbkxpi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.snrcjt.cn/Article/details/gt2dnsjbfdc.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.mhx1999.top/Article/details/gt2bihjbdwu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gt2vhqlnlin.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.c1oappe.top/Article/details/gt2zjjzfydz.html

[E16] 数字千分位
来源：http://dali.ydzc1.top/Article/details/gt2qqyuwumg.html

Py:   f"{1234567:,}"
来源：http://dali.zhongyouzk.top/Article/details/gt2mhddfsvm.html

PHP:  number_format(1234567);
来源：http://dali.zdqjudy.top/Article/details/gt2znpwnvwn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hxfoahxu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.tianlin.xyz/Article/details/gt2jenihbzd.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tcgntasm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xylfe.cn/Article/details/gt2ihxokodr.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xuanzx.com/Article/details/gt2febkfxyn.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gt2abmxhszy.html

[E17] 首字母大写
来源：http://dali.tian-w.cn/Article/details/gt2wphejgde.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gaohongyu789.top/Article/details/gt2gxyebjfw.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcotplca.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gzhubu.top/Article/details/gt2egenooin.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ppjwa.cn/Article/details/gt2maulgmer.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.dashuyun.cn/Article/details/gt2oecmnvoa.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gt2jhinbhes.html

Ruby: s.capitalize
来源：http://dali.nanxinkj.top/Article/details/gt2osaxpgxi.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daxiang520.top/Article/details/gt2atvxmnhl.html

[E18] 模板占位符替换
来源：http://dali.pycfn.com/Article/details/gt2ziimvasd.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sweek.top/Article/details/gt2hjfdbtly.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gotoacloud.top/Article/details/gt2rzqsczzk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.iojbl.cn/Article/details/gt2auzrxtgt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cucudq.cn/Article/details/gt2mbfwtxch.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2ciornpmt.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2qobhunpp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xuanzx.com/Article/details/gt2otwlwzvy.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.yangfankeji.com/Article/details/gt2rknuntxj.html

[E19] 多行文本按行拆分
来源：http://dali.yj20258888.top/Article/details/gt2zmcnxjoc.html

Py:   s.splitlines()
来源：http://dali.ybcxt.top/Article/details/gt2vksuqjfq.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2szlzaqjk.html

JS:   s.split(/\r?\n/)
来源：http://dali.yueranfly.top/Article/details/gt2efncawnq.html

TS:   s.split(/\r?\n/)
来源：http://dali.zhijiandao.cn/Article/details/gt2chsuwnug.html

Java: s.lines().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wjevopui.html

Go:   strings.Split(s, "\n")
来源：http://dali.dianchejie.cn/Article/details/gt2wzokoywc.html

Ruby: s.lines
来源：http://dali.zhongyouzk.top/Article/details/gt2upsnumvp.html

C#:   s.Split('\n')
来源：http://dali.xinyue.icu/Article/details/gt2ajymkjik.html

[E20] 判断字符串是否为空
来源：http://dali.gaohongyu789.top/Article/details/gt2xelgizsj.html

Py:   if not s:
来源：http://dali.yanxiufei.cn/Article/details/gt2mplamebg.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.dashuyun.cn/Article/details/gt2yjrypmha.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.tianlin.xyz/Article/details/gt2cthycmwu.html

TS:   if (s === "") {}
来源：http://dali.zhongyouzk.top/Article/details/gt2jvxczoiy.html

Java: if (s.isEmpty()) {}
来源：http://dali.tianlin.xyz/Article/details/gt2trbptmsx.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ffccclrk.html

Ruby: if s.empty?
来源：http://dali.tanke756.top/Article/details/gt2cdqqpdsy.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.daria6918.cn/Article/details/gt2zrxtojcl.html

[E21] 超长截断加省略号
来源：http://dali.wangshuangyany.cn/Article/details/gt2vsihnxhh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sufxvd.cn/Article/details/gt2lywtuutk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdtgxkvs.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fengsongda.top/Article/details/gt2yciuistk.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.sufxvd.cn/Article/details/gt2xwkovuby.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2okgsuzph.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.shzxlz.cn/Article/details/gt2gnmrzuud.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gt2qminzttq.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gt2vmvsodrl.html

[E22] 字节长度与字符长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2owsuoejz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.tanke756.top/Article/details/gt2gykpixfp.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jianghu66.top/Article/details/gt2aozfvrhr.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.daxiang520.top/Article/details/gt2euvthexe.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gt2iwibishh.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.ivvv.top/Article/details/gt2hwpzljyn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.mhx1999.top/Article/details/gt2xnvqaknh.html

Ruby: s.bytesize;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2robowqbd.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sxryk.cn/Article/details/gt2peocfzrf.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ywpfnvgi.html

F. 文件与目录
来源：http://dali.yueranfly.top/Article/details/gt2dqckzokl.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2ncwtcwfs.html

[F01] 读取整个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eighqlpd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.ydzc1.top/Article/details/gt2pbtnpjxk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2fyvsxdwc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tian-w.cn/Article/details/gt2giplblya.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2ysxlhypk.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gt2xoigdrfy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.yonumen.top/Article/details/gt2dakhgnnc.html

Ruby: File.read("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gt2ibttigqy.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.mhx1999.top/Article/details/gt2zmdsesrn.html

[F02] 逐行读取文件
来源：http://dali.xuanzx.com/Article/details/gt2dwtomzij.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.pycfn.com/Article/details/gt2hdmknbaq.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.yuanzhike.top/Article/details/gt2udvfhyqk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.9152youxi.cn/Article/details/gt2wpwmbmva.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xziqi.cn/Article/details/gt2xfmvqqfj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.bjfxy.top/Article/details/gt2qcftaxqf.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2meuhskse.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ehwqpu.com/Article/details/gt2mdvucuyh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.gzhubu.top/Article/details/gt2ggfsuwdg.html

[F03] 写入文件（覆盖）
来源：http://dali.zhengqikj.top/Article/details/gt2katxeapd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cashguo.top/Article/details/gt2lsezzasf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gt2jqtkxcls.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yanxiufei.cn/Article/details/gt2imucxfmj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.yuxming.cn/Article/details/gt2pkqxfffb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.xylfe.cn/Article/details/gt2ymrtemkv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.dianchejie.cn/Article/details/gt2hdrgdbvx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sweek.top/Article/details/gt2szrqvjcr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.kuanghao11.cn/Article/details/gt2eiemjiuw.html

[F04] 追加写入文件
来源：http://dali.0kj1m.cn/Article/details/gt2gxtemtxi.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.fengsongda.top/Article/details/gt2miiaraxz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.fzhhl.top/Article/details/gt2sokbbvgd.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.fengsongda.top/Article/details/gt2xwydiiiz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.aizwys.cn/Article/details/gt2vbexhyid.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.ehwqpu.com/Article/details/gt2amhiroil.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.guannengcc.top/Article/details/gt2wieywucs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.zhijiandao.cn/Article/details/gt2riircgge.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.shzxlz.cn/Article/details/gt2wsopihvx.html

[F05] 判断文件或目录是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2nybmigpj.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.guowangkeji.top/Article/details/gt2pcekztqs.html

PHP:  file_exists("a.txt");
来源：http://dali.fzhhl.top/Article/details/gt2izkuhrvw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gt2yvvbksdc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2exjqckfy.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gogol.net.cn/Article/details/gt2itxztxfl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nwbrower.top/Article/details/gt2xvsubvgu.html

Ruby: File.exist?("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wezvwdvk.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2aaebxeqe.html

[F06] 删除文件
来源：http://dali.c1oappe.top/Article/details/gt2fmofrmcj.html

Py:   os.remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2svelfnry.html

PHP:  unlink("a.txt");
来源：http://dali.nwbrower.top/Article/details/gt2vuprnqtr.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2eqrrotiw.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gt2zcjyotan.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jianghu66.top/Article/details/gt2vdfcjvpo.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2ygasheyk.html

Ruby: File.delete("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2isrudwoh.html

C#:   File.Delete("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2ijmccmmj.html

[F07] 创建目录（含多级）
来源：http://dali.ybcxt.top/Article/details/gt2lfwifyaq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gt2pzzczztq.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2owsuhpfq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yvedp.cn/Article/details/gt2wtwybleb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.xziqi.cn/Article/details/gt2cqnthehr.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.andypj.xyz/Article/details/gt2hhzyjieq.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wefbjfgx.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xylfe.cn/Article/details/gt2txkurjqr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258.top/Article/details/gt2gcscixuu.html

[F08] 遍历目录
来源：http://dali.jqgufenzy.top/Article/details/gt2abliaezi.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cucudq.cn/Article/details/gt2anhvycuw.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.aibaodan.cn/Article/details/gt2xdpgrqxy.html

JS:   fs.readdirSync("dir")
来源：http://dali.ppjwa.cn/Article/details/gt2qjyibskx.html

TS:   fs.readdirSync("dir")
来源：http://dali.yuanzhike.top/Article/details/gt2bbbygmha.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yj20258.top/Article/details/gt2fkxcjaok.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xziqi.cn/Article/details/gt2nclxxfom.html

Ruby: Dir.children("dir")
来源：http://dali.kuanghao11.cn/Article/details/gt2likvlcwt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shuidangran.top/Article/details/gt2gywujxqy.html

[F09] 获取文件大小
来源：http://dali.sweek.top/Article/details/gt2wpanbong.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2awkjhgyh.html

PHP:  filesize("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2mevbqkuj.html

JS:   fs.statSync("a.txt").size
来源：http://dali.havefunace.top/Article/details/gt2najauual.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ppjwa.cn/Article/details/gt2smdmnlih.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.chenjidiqi.icu/Article/details/gt2azwphhdd.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.316326.xyz/Article/details/gt2vngjmgpx.html

Ruby: File.size("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2gmrmhzyx.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.chenzaomai.com/Article/details/gt2clbknces.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yvedp.cn/Article/details/gt2bonikhnm.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ztnbolcq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2hjgvhmkw.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.cqqwz.cn/Article/details/gt2rjugfvcb.html

TS:   path.extname("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2ytyydfap.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.daxiang520.top/Article/details/gt2wlnjpnmq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2sobeyeqk.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2pnavnqfd.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2okzgggog.html

[F11] 复制与移动文件
来源：http://dali.redwolf501.top/Article/details/gt2mnarvfbh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2trgjfqjf.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.sweek.top/Article/details/gt2apzeitmu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2cxsnduxi.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2jlczoihm.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.daxiang520.top/Article/details/gt2mgwevhpy.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.guannengcc.top/Article/details/gt2bwznegdp.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhixingplan.top/Article/details/gt2jgasgxrg.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yj20258.top/Article/details/gt2enpqxnys.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gt2yyaxlqfo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.shzxlz.cn/Article/details/gt2xdgojuui.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.sufxvd.cn/Article/details/gt2hbulwvoe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.sweek.top/Article/details/gt2fnovywil.html

TS:   // 同上
来源：http://dali.zhoulong.xyz/Article/details/gt2meekudmv.html


<!-- 参考信息 -->