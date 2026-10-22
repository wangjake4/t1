代发 wailian999

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yuxming.cn/Article/details/gt2blkdxqtt.html

TS:   s.slice(1, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2xczaeway.html

Java: s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gt2azevsjjt.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jianghu66.top/Article/details/gt2oexaoazl.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dashuyun.cn/Article/details/gt2ynuwdied.html

C#:   s.Substring(1, 3)
来源：http://dali.jianghu66.top/Article/details/gt2vzuxwoyq.html

[E04] 查找子串位置
来源：http://dali.zhoulong.xyz/Article/details/gt2ukwvknws.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xinyue.icu/Article/details/gt2xezxunks.html

PHP:  strpos($s, "x");
来源：http://dali.xylfe.cn/Article/details/gt2syxzkota.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gt2ikzfspxn.html

TS:   s.indexOf("x")
来源：http://dali.jlsjyb.cn/Article/details/gt2amooaumv.html

Java: s.indexOf("x")
来源：http://dali.316326.xyz/Article/details/gt2ghymnrsi.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uyljerhj.html

Ruby: s.index("x")
来源：http://dali.hammf.cn/Article/details/gt2higpvvnh.html

C#:   s.IndexOf("x")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmshcqxs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hongshengwenyu.top/Article/details/gt2soiasjqa.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shzxlz.cn/Article/details/gt2kwngzxwg.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258.top/Article/details/gt2eqxjmxab.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cdnleiting.top/Article/details/gt2ejeotdhk.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.xuanzx.com/Article/details/gt2gnwsgurw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yueranfly.top/Article/details/gt2kmjrikkm.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daria6918.cn/Article/details/gt2gdbupqjp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.yuanzhike.top/Article/details/gt2uowhcpeq.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hywenlv.cn/Article/details/gt2rkdsmgqc.html

[E06] 替换子串
来源：http://dali.tianlin.xyz/Article/details/gt2yjebobss.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gt2mdfsdxji.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jlsjyb.cn/Article/details/gt2fimfpceb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.tanke756.top/Article/details/gt2vrcqvuvt.html

TS:   s.replaceAll("a", "b")
来源：http://dali.xylfe.cn/Article/details/gt2uiurqwpn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gt2cfczsrkq.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yvedp.cn/Article/details/gt2kpwavvsl.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gt2qajrybma.html

C#:   s.Replace("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gt2wlnjgbma.html

[E07] 按分隔符拆分
来源：http://dali.ivvv.top/Article/details/gt2uupzclxp.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.yuanzhike.top/Article/details/gt2howpqxsx.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2rklovnxj.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cdnleiting.top/Article/details/gt2vfgrtugu.html

TS:   s.split(",")
来源：http://dali.chenjidiqi.icu/Article/details/gt2waqbqvhu.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ucyoyhee.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nwbrower.top/Article/details/gt2qwzjjlvr.html

Ruby: s.split(",");  s.split
来源：http://dali.jinqigfzy.top/Article/details/gt2mgihokcv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2orprzerc.html

[E08] 数组按分隔符合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2frukcoen.html

Py:   ",".join(items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvorhhoh.html

PHP:  implode(",", $items);
来源：http://dali.hywenlv.cn/Article/details/gt2cqvmjgch.html

JS:   items.join(",")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jwtxxzms.html

TS:   items.join(",")
来源：http://dali.xuanzx.com/Article/details/gt2iedandvk.html

Java: String.join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gt2rtjahjkf.html

Go:   strings.Join(items, ",")
来源：http://dali.ivvv.top/Article/details/gt2jpwlaale.html

Ruby: items.join(",")
来源：http://dali.tanke756.top/Article/details/gt2lnkoeken.html

C#:   string.Join(",", items)
来源：http://dali.jyoumei.cn/Article/details/gt2jzmigkaz.html

[E09] 去除所有空白字符
来源：http://dali.yj20258888.top/Article/details/gt2uzxbfnax.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.havefunace.top/Article/details/gt2jygczhcz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrxjwrax.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.snrcjt.cn/Article/details/gt2ybumdrph.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.svipenyu.cn/Article/details/gt2ifrxmkfz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.dianchejie.cn/Article/details/gt2emzvefpw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2osgwfmfi.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.chenlongwang.top/Article/details/gt2duuucbfh.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xuanzx.com/Article/details/gt2nfhbgxem.html

[E10] 左侧补零 / 定长填充
来源：http://dali.nwbrower.top/Article/details/gt2dwrjmhwz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xpqvttli.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.jyoumei.cn/Article/details/gt2qdenjdlr.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvrmxrdv.html

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gt2lieqyfms.html

Java: String.format("%03d", 7)
来源：http://dali.zycfv.cn/Article/details/gt2sltaunwc.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gt2zvqtgjny.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.gzhubu.top/Article/details/gt2sdgvuwwf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yphybybi.html

[E11] 反转字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2poqonzul.html

Py:   s[::-1]
来源：http://dali.mhx1999.top/Article/details/gt2dmtnjkxe.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gt2kjtpwwdm.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2ekhihwpk.html

TS:   [...s].reverse().join("")
来源：http://dali.ybcxt.top/Article/details/gt2rfsehwpm.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.wangshuangyany.cn/Article/details/gt2uaqtoozb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gt2zetwaewu.html

Ruby: s.reverse
来源：http://dali.yonumen.top/Article/details/gt2jjqasfcj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.sysykeji.top/Article/details/gt2aviooybx.html

[E12] 统计某字符出现次数
来源：http://dali.daxiang520.top/Article/details/gt2hwlrrbbr.html

Py:   s.count("a")
来源：http://dali.xuanzx.com/Article/details/gt2tnmpzbut.html

PHP:  substr_count($s, "a");
来源：http://dali.hywenlv.cn/Article/details/gt2ndpittyw.html

JS:   s.split("a").length - 1
来源：http://dali.andypj.xyz/Article/details/gt2ccgmzdss.html

TS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pieoguld.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.havefunace.top/Article/details/gt2wahkinis.html

Go:   strings.Count(s, "a")
来源：http://dali.shzxlz.cn/Article/details/gt2pktanvdc.html

Ruby: s.count("a")
来源：http://dali.cdnleiting.top/Article/details/gt2vuinazcq.html

C#:   s.Count(c => c == 'a')
来源：http://dali.birdmap.top/Article/details/gt2cguothhi.html

[E13] 逐字符遍历
来源：http://dali.cheryme.top/Article/details/gt2pptdouxj.html

Py:   for ch in s: print(ch)
来源：http://dali.daxiang520.top/Article/details/gt2svabdlvw.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xylfe.cn/Article/details/gt2tyqczpzx.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.birdmap.top/Article/details/gt2bsqqdobj.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gt2ufubqazs.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.mhx1999.top/Article/details/gt2pfjfryso.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yj20258888.top/Article/details/gt2esutgbbf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hfpthk.cn/Article/details/gt2pggykihm.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gt2mzbkvfvx.html

[E14] URL 编码与 Base64
来源：http://dali.ppjwa.cn/Article/details/gt2pnevthds.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nefiszdp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhixingplan.top/Article/details/gt2cpwwzehn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ualukroq.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.nanxinkj.top/Article/details/gt2zvwddnqs.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aibaodan.cn/Article/details/gt2pekiwuca.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.ybcxt.top/Article/details/gt2hghxgppc.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlbhglwi.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yueranfly.top/Article/details/gt2ajipeqrf.html

[E15] HTML 转义 / 反转义
来源：http://dali.guowangkeji.top/Article/details/gt2uclnweqn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.nanxinkj.top/Article/details/gt2twudckyv.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.guannengcc.top/Article/details/gt2jwhvoctu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.cheryme.top/Article/details/gt2bsxwluei.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuanzx.com/Article/details/gt2iyamrihk.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tian-w.cn/Article/details/gt2dvkwvhgf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.redwolf501.top/Article/details/gt2pvkalssb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2uodnklsj.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gt2ajpteudp.html

[E16] 数字千分位
来源：http://dali.daria6918.cn/Article/details/gt2nzknfont.html

Py:   f"{1234567:,}"
来源：http://dali.hammf.cn/Article/details/gt2xmhzagjf.html

PHP:  number_format(1234567);
来源：http://dali.andypj.xyz/Article/details/gt2owxzwbil.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gt2pyucfgde.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.shangyingyoupin.top/Article/details/gt2pytwdcct.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gt2zyjuzikx.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hnqzz.top/Article/details/gt2ckqhuumy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2lzbdjwfm.html

C#:   1234567.ToString("N0")
来源：http://dali.yanxiufei.cn/Article/details/gt2zjmdakjy.html

[E17] 首字母大写
来源：http://dali.tianlin.xyz/Article/details/gt2wuvibary.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.hnxiangtu.top/Article/details/gt2yenlspov.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.nanxuanxn.top/Article/details/gt2cdskdszw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gt2ljdnbbel.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gt2awebmrjx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.shuidangran.top/Article/details/gt2kkdzoabh.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gt2zjrunlez.html

Ruby: s.capitalize
来源：http://dali.chenzaomai.com/Article/details/gt2dqxulsgh.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dianchejie.cn/Article/details/gt2kgbyebzh.html

[E18] 模板占位符替换
来源：http://dali.jinqigufen.top/Article/details/gt2qmrfnogv.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.iojbl.cn/Article/details/gt2fcglsltx.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.iojbl.cn/Article/details/gt2reeqrrnv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gt2bfzqiucn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2hgzluhtj.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gt2jmvabnhk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gt2hztsknuz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.xylfe.cn/Article/details/gt2dfxphcxq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.birdmap.top/Article/details/gt2hbdxdutw.html

[E19] 多行文本按行拆分
来源：http://dali.zycfv.cn/Article/details/gt2kvnwnvkf.html

Py:   s.splitlines()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qmtfdqiw.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2lyvytgzb.html

JS:   s.split(/\r?\n/)
来源：http://dali.gaohongyu789.top/Article/details/gt2tbrfrkzm.html

TS:   s.split(/\r?\n/)
来源：http://dali.xinyue.icu/Article/details/gt2kznnzfvm.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2tmjkrwfa.html

Go:   strings.Split(s, "\n")
来源：http://dali.chenlongwang.top/Article/details/gt2ygjijpgc.html

Ruby: s.lines
来源：http://dali.daxiang520.top/Article/details/gt2sltpyzeh.html

C#:   s.Split('\n')
来源：http://dali.nanxinkj.top/Article/details/gt2viqoskqr.html

[E20] 判断字符串是否为空
来源：http://dali.zhoulong.xyz/Article/details/gt2dxorjajw.html

Py:   if not s:
来源：http://dali.zhiwuduotai.top/Article/details/gt2qnmsjams.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tian-w.cn/Article/details/gt2hqrgylgp.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.smart0.xyz/Article/details/gt2fewewmyy.html

TS:   if (s === "") {}
来源：http://dali.guannengcc.top/Article/details/gt2wjbltqen.html

Java: if (s.isEmpty()) {}
来源：http://dali.shuidangran.top/Article/details/gt2umyezmtj.html

Go:   if s == "" {}
来源：http://dali.yvedp.cn/Article/details/gt2difmrlpl.html

Ruby: if s.empty?
来源：http://dali.xziqi.cn/Article/details/gt2rsktiuts.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.meibo888.top/Article/details/gt2jyfsodio.html

[E21] 超长截断加省略号
来源：http://dali.quarkkingdee.top/Article/details/gt2zlqcbeao.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xuetiantiany.cn/Article/details/gt2rvvhjljj.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ybcxt.top/Article/details/gt2amyajsrq.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ydzc1.top/Article/details/gt2acvfpcwf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2coiyxngu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2xlwhtzvn.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.guannengcc.top/Article/details/gt2vrsixckc.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2vkurgsiu.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.c1oappe.top/Article/details/gt2ghjtfljg.html

[E22] 字节长度与字符长度
来源：http://dali.dianchejie.cn/Article/details/gt2icdmsedf.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cashguo.top/Article/details/gt2pfhlquxw.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gt2mtescgwo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2kbmheawy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2uyzdflbn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gt2ysegjmnb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hammf.cn/Article/details/gt2rcqrtsym.html

Ruby: s.bytesize;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2sublwrsf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.zhoulong.xyz/Article/details/gt2cmvbengk.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2izxakjbs.html

F. 文件与目录
来源：http://dali.fzhhl.top/Article/details/gt2yfqznrew.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2trkyehhr.html

[F01] 读取整个文件
来源：http://dali.jqgufenzy.top/Article/details/gt2orpnrkvi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gt2mcweaxsl.html

PHP:  file_get_contents("a.txt");
来源：http://dali.fengsongda.top/Article/details/gt2jnaepsyv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnqzz.top/Article/details/gt2zonfyfyr.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.wangdashe.top/Article/details/gt2xajktdln.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2rhicjdry.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.fzhhl.top/Article/details/gt2vngyygyk.html

Ruby: File.read("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nenmkevr.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hnqzz.top/Article/details/gt2pebajqln.html

[F02] 逐行读取文件
来源：http://dali.xylfe.cn/Article/details/gt2wefnjjki.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fxnpalgj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigufen.top/Article/details/gt2vllwxyvt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gt2cwdamdfn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qsskztta.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hnqzz.top/Article/details/gt2pywpwacq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.tianlin.xyz/Article/details/gt2xspzaxbf.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jinqigfzy.top/Article/details/gt2vxoucspg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jlsjyb.cn/Article/details/gt2wshyreah.html

[F03] 写入文件（覆盖）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vsqtkiim.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tian-w.cn/Article/details/gt2shjwcepe.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.c1oappe.top/Article/details/gt2gjkwcbpl.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2yosgquwp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gt2ivkorbfs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.0kj1m.cn/Article/details/gt2zsnksgvr.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yanxiufei.cn/Article/details/gt2xejteulv.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.ydzc1.top/Article/details/gt2janffvdt.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.tanke756.top/Article/details/gt2qhbikwyn.html

[F04] 追加写入文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2rlkfzvfe.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.ydzc1.top/Article/details/gt2ghhnzhjk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.pengpengdd.cyou/Article/details/gt2iudreqqa.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ivvv.top/Article/details/gt2ihssakfl.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gt2cdympkcj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2opjjerwo.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.nanxinkj.top/Article/details/gt2izwwfuxd.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.hywenlv.cn/Article/details/gt2xzsulzxe.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.birdmap.top/Article/details/gt2wpiunskt.html

[F05] 判断文件或目录是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2spvjaazu.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.gotoacloud.top/Article/details/gt2ghvmctev.html

PHP:  file_exists("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2tbxpxeop.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gt2ptyzarmi.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2tgtuvkni.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2rkluluzq.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.tianlin.xyz/Article/details/gt2wlykyqol.html

Ruby: File.exist?("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2uluugozd.html

C#:   File.Exists("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2fzotoxhj.html

[F06] 删除文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2dehngiqg.html

Py:   os.remove("a.txt")
来源：http://dali.sweek.top/Article/details/gt2avceprqr.html

PHP:  unlink("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2kkgbrbbd.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gt2xumtldna.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.sweek.top/Article/details/gt2qjtkjqji.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2vquyumgu.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gt2ooarxlmi.html

Ruby: File.delete("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2qpqxsgek.html

C#:   File.Delete("a.txt");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bplryjry.html

[F07] 创建目录（含多级）
来源：http://dali.fzhhl.top/Article/details/gt2hqjctueq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sweek.top/Article/details/gt2grwqtlgg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.nanxinkj.top/Article/details/gt2zssdukfg.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gt2wwpebnmu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pycfn.com/Article/details/gt2zffcbnku.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.shzxlz.cn/Article/details/gt2guwradzn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.meibo888.top/Article/details/gt2ighutvdj.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.aibaodan.cn/Article/details/gt2tvepkxzk.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.316326.xyz/Article/details/gt2zkscpxur.html

[F08] 遍历目录
来源：http://dali.hongshengwenyu.top/Article/details/gt2eceubcog.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2siehrjod.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2gxbavzxq.html

JS:   fs.readdirSync("dir")
来源：http://dali.guannengcc.top/Article/details/gt2wuaackmy.html

TS:   fs.readdirSync("dir")
来源：http://dali.cucudq.cn/Article/details/gt2qgzwnvhq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kufmpkgz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.jiagoushi.top/Article/details/gt2illskinh.html

Ruby: Dir.children("dir")
来源：http://dali.haohaochexian.top/Article/details/gt2txspallh.html

C#:   Directory.GetFiles("dir")
来源：http://dali.birdmap.top/Article/details/gt2xxmspwka.html

[F09] 获取文件大小
来源：http://dali.fengsongda.top/Article/details/gt2wflenpho.html

Py:   os.path.getsize("a.txt")
来源：http://dali.redwolf501.top/Article/details/gt2zmqssrpa.html

PHP:  filesize("a.txt");
来源：http://dali.hywenlv.cn/Article/details/gt2sgouixvg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gt2hcfmvtxs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gt2qslhoxes.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2mlhfbabo.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.sufxvd.cn/Article/details/gt2zqznnpbg.html

Ruby: File.size("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nijaqyzp.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.pengpengdd.cyou/Article/details/gt2cuqkkbre.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.haohaochexian.top/Article/details/gt2xazieshp.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2yljwrqvq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2iqchsjio.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2jqvggjfk.html

TS:   path.extname("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2uapmpskj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gaohongyu789.top/Article/details/gt2fthmultt.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2uqcjjxwx.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2wjbxfffa.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2fyauldam.html

[F11] 复制与移动文件
来源：http://dali.hammf.cn/Article/details/gt2qatgslfx.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.c1oappe.top/Article/details/gt2oosgkxcj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2udfjabyc.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2fbolezqh.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2qtywjhya.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.dashuyun.cn/Article/details/gt2ypcibrsl.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xziqi.cn/Article/details/gt2uhehueim.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.sufxvd.cn/Article/details/gt2vqfxtatn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.shuidangran.top/Article/details/gt2kytsmjtq.html

[F12] CSV 读写
来源：http://dali.gotoacloud.top/Article/details/gt2lszzhbpt.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.svipenyu.cn/Article/details/gt2pawdbzcd.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.aizwys.cn/Article/details/gt2nopwzfpf.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.9152youxi.cn/Article/details/gt2eumwogaw.html

TS:   // 同上
来源：http://dali.cheryme.top/Article/details/gt2aduroybc.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hywenlv.cn/Article/details/gt2qpzvefdo.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jyoumei.cn/Article/details/gt2mhbyxcod.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eztyhwah.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpfsazai.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2dcxehmbq.html

G. 面向对象
来源：http://dali.c1oappe.top/Article/details/gt2pkwikeqy.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2qfyjqzfa.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gt2dtxazaxu.html

Py:   class User: pass
来源：http://dali.hywenlv.cn/Article/details/gt2sbrmvhrz.html

PHP:  class User {}
来源：http://dali.quarkkingdee.top/Article/details/gt2vshmajhg.html

JS:   class User {}
来源：http://dali.wangdashe.top/Article/details/gt2dugeijty.html

TS:   class User { name: string = ""; }
来源：http://dali.vqdsnc.cn/Article/details/gt2omxxafhe.html

Java: class User {}
来源：http://dali.yongpay.top/Article/details/gt2ckeeyzkb.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gt2utbifdms.html

Ruby: class User; end
来源：http://dali.0kj1m.cn/Article/details/gt2rzmhrsrp.html

C#:   class User {}
来源：http://dali.nwbrower.top/Article/details/gt2djuywrmu.html


<!-- 参考信息 -->