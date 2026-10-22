代发 wailian999

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2nysvoihs.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hnqzz.top/Article/details/gt2zsexmfae.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gt2eqadbrlw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gt2jkzukdoh.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuanzhike.top/Article/details/gt2omcoburd.html

[D24] 字典 / Map 基本操作
来源：http://dali.xinyue.icu/Article/details/gt2eifymqpz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zxmfzdly.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.meibo888.top/Article/details/gt2dqlwzyax.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fengsongda.top/Article/details/gt2vrvyyzgt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2cvobkptn.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuxming.cn/Article/details/gt2mabtdzwg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinqigufen.top/Article/details/gt2brevgvvn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.cdnleiting.top/Article/details/gt2evsjggtu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ehwqpu.com/Article/details/gt2zoxjuxmj.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gt2nboiyzzq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hongshengwenyu.top/Article/details/gt2kskhwgsa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.andypj.xyz/Article/details/gt2fqdchtvg.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnqzz.top/Article/details/gt2iwggcohm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gt2mmvntadk.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.sxryk.cn/Article/details/gt2edrvvdfs.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wojcabbm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daria6918.cn/Article/details/gt2jutwtwrk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2rechechw.html

[D26] 数组转字符串
来源：http://dali.c1oappe.top/Article/details/gt2cfrkdiqm.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gzhubu.top/Article/details/gt2ozptzfri.html

PHP:  implode(", ", $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2yajmaakd.html

JS:   arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gt2tltvwgds.html

TS:   arr.join(", ")
来源：http://dali.9152youxi.cn/Article/details/gt2fkxaglfm.html

Java: String.join(", ", list)
来源：http://dali.hywenlv.cn/Article/details/gt2afxcspon.html

Go:   strings.Join(strs, ", ")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ubrlblys.html

Ruby: arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ajarwctn.html

C#:   string.Join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vuwfqkxi.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2nipcodoj.html

E. 字符串处理
来源：http://dali.ybcxt.top/Article/details/gt2iqsurwul.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2jywbzljk.html

[E01] 拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gt2avaubxct.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nwbrower.top/Article/details/gt2pvrrohgx.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.cucudq.cn/Article/details/gt2jxyvqqbt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxswgyn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gt2wzxipywn.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2qffwiqll.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.sweek.top/Article/details/gt2twkyyhob.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.fengsongda.top/Article/details/gt2njygubdn.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj20258888.top/Article/details/gt2mvpfaknw.html

[E02] 重复字符串
来源：http://dali.zhongyouzk.top/Article/details/gt2txiwxoaa.html

Py:   "ab" * 3
来源：http://dali.nanxinkj.top/Article/details/gt2cdmfrxcw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ftvqxtuo.html

JS:   "ab".repeat(3)
来源：http://dali.ehwqpu.com/Article/details/gt2qoxxbzxk.html

TS:   "ab".repeat(3)
来源：http://dali.ppjwa.cn/Article/details/gt2vicmducz.html

Java: "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2mjswbcft.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hywenlv.cn/Article/details/gt2gjzzwadk.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gt2tkyoeleq.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258888.top/Article/details/gt2uimeqtki.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gt2ehenmyll.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuxming.cn/Article/details/gt2oashcatl.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cdnleiting.top/Article/details/gt2pwhmtkyk.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.andypj.xyz/Article/details/gt2zecfaofn.html

TS:   s.slice(1, 4)
来源：http://dali.yuanzhike.top/Article/details/gt2slxwbtof.html

Java: s.substring(1, 4)
来源：http://dali.tian-w.cn/Article/details/gt2vswzglig.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jlsjyb.cn/Article/details/gt2mugjrjpr.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.tanke756.top/Article/details/gt2fxveezct.html

C#:   s.Substring(1, 3)
来源：http://dali.ivvv.top/Article/details/gt2foyhvitn.html

[E04] 查找子串位置
来源：http://dali.cucudq.cn/Article/details/gt2hemugkgq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2tglrdhuz.html

PHP:  strpos($s, "x");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hnihuwhq.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bexzprus.html

TS:   s.indexOf("x")
来源：http://dali.ehwqpu.com/Article/details/gt2exngwzos.html

Java: s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jlpzmqzh.html

Go:   strings.Index(s, "x")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kcywaofh.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gt2knagijco.html

C#:   s.IndexOf("x")
来源：http://dali.nanxinkj.top/Article/details/gt2tfbnqzqx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gzhubu.top/Article/details/gt2vafwxzxc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.meibo888.top/Article/details/gt2zdjnogra.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xziqi.cn/Article/details/gt2hildqxlo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuanzhike.top/Article/details/gt2vjqyfbxm.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.dashuyun.cn/Article/details/gt2eyzkkpjf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.ehwqpu.com/Article/details/gt2vmnjptrl.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.zycfv.cn/Article/details/gt2oppzqooa.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.cdnleiting.top/Article/details/gt2fnmwfzmx.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yj202588.top/Article/details/gt2gtjzikas.html

[E06] 替换子串
来源：http://dali.wangdashe.top/Article/details/gt2sdbliksq.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.ppjwa.cn/Article/details/gt2xkujztkq.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yuxming.cn/Article/details/gt2dejapsqo.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.sweek.top/Article/details/gt2tytqeuyi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.pengpengdd.cyou/Article/details/gt2zoyqggec.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2hftknjtv.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2phenybiq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.feifeiyinyue.top/Article/details/gt2ybbpxkri.html

C#:   s.Replace("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gt2twboktpg.html

[E07] 按分隔符拆分
来源：http://dali.cashguo.top/Article/details/gt2gflwaaka.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epiachll.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.yuxming.cn/Article/details/gt2noohwgwo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.haohaochexian.top/Article/details/gt2xbcxawjo.html

TS:   s.split(",")
来源：http://dali.tianlin.xyz/Article/details/gt2ganneasj.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jlsjyb.cn/Article/details/gt2rzezclph.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.wangdashe.top/Article/details/gt2pddpqxkz.html

Ruby: s.split(",");  s.split
来源：http://dali.aibaodan.cn/Article/details/gt2wnybxyps.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pimsqkfl.html

[E08] 数组按分隔符合并
来源：http://dali.dianchejie.cn/Article/details/gt2drehixut.html

Py:   ",".join(items)
来源：http://dali.havefunace.top/Article/details/gt2jyjyavos.html

PHP:  implode(",", $items);
来源：http://dali.jinqigfzy.top/Article/details/gt2jinubkya.html

JS:   items.join(",")
来源：http://dali.hnqzz.top/Article/details/gt2zudjcmjp.html

TS:   items.join(",")
来源：http://dali.aibaodan.cn/Article/details/gt2wwsgfrkv.html

Java: String.join(",", items)
来源：http://dali.quarkkingdee.top/Article/details/gt2ddbkbogl.html

Go:   strings.Join(items, ",")
来源：http://dali.ehwqpu.com/Article/details/gt2kmyykedy.html

Ruby: items.join(",")
来源：http://dali.fzhhl.top/Article/details/gt2mvohelti.html

C#:   string.Join(",", items)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sxhcmjge.html

[E09] 去除所有空白字符
来源：http://dali.dianchejie.cn/Article/details/gt2pzaoskus.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.c1oappe.top/Article/details/gt2gkczzewl.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.yanxiufei.cn/Article/details/gt2pryyimjt.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dyzngqko.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nwkczicn.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.aibaodan.cn/Article/details/gt2ixralrns.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.gaohongyu789.top/Article/details/gt2iiliufai.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yuanzhike.top/Article/details/gt2voaslfxw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.gotoacloud.top/Article/details/gt2cbpkhjqk.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuetiantiany.cn/Article/details/gt2ssakmqao.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.pengpengdd.cyou/Article/details/gt2colrzjqc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.9152youxi.cn/Article/details/gt2ozwaordy.html

JS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2vxchqlus.html

TS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2istcmulm.html

Java: String.format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gt2pkciiydm.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zdqjudy.top/Article/details/gt2afwehewb.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxinkj.top/Article/details/gt2wtbaakve.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.aizwys.cn/Article/details/gt2owjvbmuc.html

[E11] 反转字符串
来源：http://dali.cucudq.cn/Article/details/gt2wypwwqti.html

Py:   s[::-1]
来源：http://dali.jiagoushi.top/Article/details/gt2crxqdexk.html

PHP:  strrev($s);
来源：http://dali.jlsjyb.cn/Article/details/gt2iaqgidtm.html

JS:   [...s].reverse().join("")
来源：http://dali.cheryme.top/Article/details/gt2fojiajig.html

TS:   [...s].reverse().join("")
来源：http://dali.yueranfly.top/Article/details/gt2ascteogf.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.andypj.xyz/Article/details/gt2jdtjlqgm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.guannengcc.top/Article/details/gt2cpweqhfb.html

Ruby: s.reverse
来源：http://dali.c1oappe.top/Article/details/gt2nolxdcxs.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nanxuanxn.top/Article/details/gt2aitsfrmr.html

[E12] 统计某字符出现次数
来源：http://dali.xinyue.icu/Article/details/gt2haofvakf.html

Py:   s.count("a")
来源：http://dali.snrcjt.cn/Article/details/gt2csfyqqdk.html

PHP:  substr_count($s, "a");
来源：http://dali.zycfv.cn/Article/details/gt2bpkapnuv.html

JS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nujloemy.html

TS:   s.split("a").length - 1
来源：http://dali.yanxiufei.cn/Article/details/gt2lpgttynm.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gt2ksgrbhpj.html

Go:   strings.Count(s, "a")
来源：http://dali.gzhubu.top/Article/details/gt2fqoznwkj.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gt2yllfnfyv.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zycfv.cn/Article/details/gt2lggyebee.html

[E13] 逐字符遍历
来源：http://dali.chenzaomai.com/Article/details/gt2xbgahygt.html

Py:   for ch in s: print(ch)
来源：http://dali.zhongyouzk.top/Article/details/gt2ykuxsaen.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.yj202588.top/Article/details/gt2mfycqswn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.kuanghao11.cn/Article/details/gt2cwqxbplt.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2ybocpsms.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.meibo888.top/Article/details/gt2inuamdmd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenzaomai.com/Article/details/gt2xsisbebv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cgoybjwf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zycfv.cn/Article/details/gt2kcctkcrv.html

[E14] URL 编码与 Base64
来源：http://dali.c1oappe.top/Article/details/gt2wheyzlnj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.nanxinkj.top/Article/details/gt2orzpcwci.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.gotoacloud.top/Article/details/gt2lgiqluwo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.vqdsnc.cn/Article/details/gt2cnljiaaz.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zarubpwz.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.wangdashe.top/Article/details/gt2exzyeisd.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.sufxvd.cn/Article/details/gt2pbubzupr.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fzhhl.top/Article/details/gt2gkuyigyr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.gotoacloud.top/Article/details/gt2qgihpuli.html

[E15] HTML 转义 / 反转义
来源：http://dali.shangyingyoupin.top/Article/details/gt2npbhzosz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dbuicboy.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.chenlongwang.top/Article/details/gt2bbbtuezm.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gt2dorexbzz.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.gotoacloud.top/Article/details/gt2qmfxthwr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.sxryk.cn/Article/details/gt2vbcvanne.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tian-w.cn/Article/details/gt2wcktpzmb.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.aizwys.cn/Article/details/gt2psnbbjed.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.jiagoushi.top/Article/details/gt2lpzkypbf.html

[E16] 数字千分位
来源：http://dali.yonumen.top/Article/details/gt2zjansgom.html

Py:   f"{1234567:,}"
来源：http://dali.wangshuangyany.cn/Article/details/gt2rypygwgh.html

PHP:  number_format(1234567);
来源：http://dali.xylfe.cn/Article/details/gt2rbjomyqi.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zycfv.cn/Article/details/gt2onjaprfx.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yonumen.top/Article/details/gt2qgfqksfj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.316326.xyz/Article/details/gt2muerkcag.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sjhaiuck.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.nanxinkj.top/Article/details/gt2xyrublhj.html

C#:   1234567.ToString("N0")
来源：http://dali.pycfn.com/Article/details/gt2mvlkstfj.html

[E17] 首字母大写
来源：http://dali.guannengcc.top/Article/details/gt2ewrfmhxp.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tian-w.cn/Article/details/gt2pjyiokol.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.mhx1999.top/Article/details/gt2rxqabjuu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gt2wxnmdpmv.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.chenlongwang.top/Article/details/gt2ksnpkwpt.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zqfsssqs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhongyouzk.top/Article/details/gt2wejsrqqy.html

Ruby: s.capitalize
来源：http://dali.yj202588.top/Article/details/gt2uekxqtqf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yvedp.cn/Article/details/gt2iagsjcos.html

[E18] 模板占位符替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhiqnwhj.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cheryme.top/Article/details/gt2tnxdlgek.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fengsongda.top/Article/details/gt2mjllcwjb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gt2egefrorv.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gt2kqiayspu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.316326.xyz/Article/details/gt2rpfdyvve.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.meibo888.top/Article/details/gt2afexvfjj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.bjfxy.top/Article/details/gt2gisbwujr.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vsiqyron.html

[E19] 多行文本按行拆分
来源：http://dali.bjfxy.top/Article/details/gt2lfusrcsl.html

Py:   s.splitlines()
来源：http://dali.andypj.xyz/Article/details/gt2njpbtdgh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhixingplan.top/Article/details/gt2oqcwvqgr.html

JS:   s.split(/\r?\n/)
来源：http://dali.yuanzhike.top/Article/details/gt2smvmgwsz.html

TS:   s.split(/\r?\n/)
来源：http://dali.jlsjyb.cn/Article/details/gt2hjsbgndd.html

Java: s.lines().toList()
来源：http://dali.guannengcc.top/Article/details/gt2nnwgwevt.html

Go:   strings.Split(s, "\n")
来源：http://dali.svipenyu.cn/Article/details/gt2afsmbodz.html

Ruby: s.lines
来源：http://dali.wangdashe.top/Article/details/gt2yqcrdwfv.html

C#:   s.Split('\n')
来源：http://dali.hongshengwenyu.top/Article/details/gt2sytfotyb.html

[E20] 判断字符串是否为空
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yxtnsmaw.html

Py:   if not s:
来源：http://dali.havefunace.top/Article/details/gt2ghsbwcll.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cuftvqro.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yj20258.top/Article/details/gt2owroufrm.html

TS:   if (s === "") {}
来源：http://dali.yonumen.top/Article/details/gt2wbygozyx.html

Java: if (s.isEmpty()) {}
来源：http://dali.hywenlv.cn/Article/details/gt2zjegfwut.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2twtpbvag.html

Ruby: if s.empty?
来源：http://dali.haohaochexian.top/Article/details/gt2vgpzwkjc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.shuidangran.top/Article/details/gt2mosajwjn.html

[E21] 超长截断加省略号
来源：http://dali.shuidangran.top/Article/details/gt2knwynyms.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.vqdsnc.cn/Article/details/gt2zlvzcooy.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gt2feztqnxp.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.kuanghao11.cn/Article/details/gt2gzczbfuy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvmejgth.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gt2bmszjkip.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.andypj.xyz/Article/details/gt2ujblijed.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.ppjwa.cn/Article/details/gt2gyisicbn.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jianghu66.top/Article/details/gt2jukpurgb.html

[E22] 字节长度与字符长度
来源：http://dali.aibaodan.cn/Article/details/gt2cdjmjfgl.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fswnlxlx.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gt2idprfbgc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ybcxt.top/Article/details/gt2prtaqliw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2qhmrwegy.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.daxiang520.top/Article/details/gt2ohosresn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhengqikj.top/Article/details/gt2uvvmqqqf.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhengqikj.top/Article/details/gt2audqyjqt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.birdmap.top/Article/details/gt2nbaxrgpu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xolsfqer.html

F. 文件与目录
来源：http://dali.sxryk.cn/Article/details/gt2cnklqytz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2isgetcsa.html

[F01] 读取整个文件
来源：http://dali.jlsjyb.cn/Article/details/gt2sjkwogwu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gt2nmxquonz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gt2kbymovzq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.gaohongyu789.top/Article/details/gt2lhhdylvm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gt2dfkthocq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.c1oappe.top/Article/details/gt2lpwfmpis.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gaohongyu789.top/Article/details/gt2gymgmdtj.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2kgreuwbs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ybcxt.top/Article/details/gt2wizirnbh.html

[F02] 逐行读取文件
来源：http://dali.havefunace.top/Article/details/gt2uytqhmax.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xuanzx.com/Article/details/gt2uicepxqx.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.fengsongda.top/Article/details/gt2yvuwggwt.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2snemrqsg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2zrlfvjbr.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.pycfn.com/Article/details/gt2wmyluupt.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jiagoushi.top/Article/details/gt2ilykatli.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uznabaxg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cdnleiting.top/Article/details/gt2jjxrctjy.html

[F03] 写入文件（覆盖）
来源：http://dali.bjfxy.top/Article/details/gt2judvined.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.tianlin.xyz/Article/details/gt2fclrvghn.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.vqdsnc.cn/Article/details/gt2jmaghzjx.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.svipenyu.cn/Article/details/gt2xmmiyinu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.9152youxi.cn/Article/details/gt2alqjltoo.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.hnxiangtu.top/Article/details/gt2ucdxcgkp.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.redwolf501.top/Article/details/gt2oirynhkb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sxryk.cn/Article/details/gt2cbhbvgjd.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gt2jgqpdtdr.html

[F04] 追加写入文件
来源：http://dali.svipenyu.cn/Article/details/gt2emdhdarc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jinqigufen.top/Article/details/gt2nnxrmyox.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.zhongyouzk.top/Article/details/gt2bqotglbh.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ybcxt.top/Article/details/gt2kxzzzmyc.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.0kj1m.cn/Article/details/gt2eajkfqfv.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.0kj1m.cn/Article/details/gt2ouyfzitp.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cheryme.top/Article/details/gt2idhxscpm.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.yueranfly.top/Article/details/gt2msertiew.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ybcxt.top/Article/details/gt2uuvvzsfg.html

[F05] 判断文件或目录是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2qhfxslbo.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jqgfzy.top/Article/details/gt2uipvdued.html

PHP:  file_exists("a.txt");
来源：http://dali.gogol.net.cn/Article/details/gt2xfiqbvks.html

JS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2nimafxoj.html

TS:   fs.existsSync("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2nnjxzcff.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.smart0.xyz/Article/details/gt2rvfvkimf.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.haohaochexian.top/Article/details/gt2daifdlue.html

Ruby: File.exist?("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2jvjaeosc.html

C#:   File.Exists("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2wubccaoj.html

[F06] 删除文件
来源：http://dali.chenlongwang.top/Article/details/gt2eqvpeyhc.html

Py:   os.remove("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phgxryjm.html

PHP:  unlink("a.txt");
来源：http://dali.sxryk.cn/Article/details/gt2lirbsnzg.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2lbqmcbsr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdoebtxl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gt2mrbwhqtf.html

Go:   os.Remove("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2ngsrnrwu.html

Ruby: File.delete("a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2wovyswsv.html

C#:   File.Delete("a.txt");
来源：http://dali.jlsjyb.cn/Article/details/gt2hfrqaunt.html

[F07] 创建目录（含多级）
来源：http://dali.0kj1m.cn/Article/details/gt2tifvcmkb.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2johcepke.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jyoumei.cn/Article/details/gt2zurdkulf.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.wangshuangyany.cn/Article/details/gt2dwcmkryi.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhoulong.xyz/Article/details/gt2vhtjymvd.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.jiagoushi.top/Article/details/gt2cgblxele.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jqgufenzy.top/Article/details/gt2rviuxxav.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xylfe.cn/Article/details/gt2erziacad.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcnuicjg.html

[F08] 遍历目录
来源：http://dali.yuanzhike.top/Article/details/gt2hfrvtudt.html


<!-- 参考信息 -->