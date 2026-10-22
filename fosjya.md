代发 wailian999

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.daria6918.cn/Article/details/gt2zdzxxomn.html

[D24] 字典 / Map 基本操作
来源：http://dali.jinqigufen.top/Article/details/gt2psctukej.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tianlin.xyz/Article/details/gt2ogsoxcsy.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sufxvd.cn/Article/details/gt2wnzxhimy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.svipenyu.cn/Article/details/gt2usukxzvh.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gt2inqtioel.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xziqi.cn/Article/details/gt2ryzxvnyj.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gt2lrlbahbh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sxryk.cn/Article/details/gt2psurtyfh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.0kj1m.cn/Article/details/gt2eljdwvpr.html

[D25] Set 集合去重与交并差
来源：http://dali.redwolf501.top/Article/details/gt2ldhefcri.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.chenjidiqi.icu/Article/details/gt2buttsehb.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yanxiufei.cn/Article/details/gt2kgirhyjc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.redwolf501.top/Article/details/gt2ojpsursy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2syrvdier.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nwbrower.top/Article/details/gt2fmdxgvrt.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gt2ytlrnrre.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yueranfly.top/Article/details/gt2wplyloer.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yangfankeji.com/Article/details/gt2fpgkobms.html

[D26] 数组转字符串
来源：http://dali.9152youxi.cn/Article/details/gt2ddxzjhfv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.havefunace.top/Article/details/gt2jzkrtvck.html

PHP:  implode(", ", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2zhkotasy.html

JS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gt2qbeqnyux.html

TS:   arr.join(", ")
来源：http://dali.zycfv.cn/Article/details/gt2fhyuilfv.html

Java: String.join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gt2pqvynxzk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fengsongda.top/Article/details/gt2oxruvqvf.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gt2ftfnouzp.html

C#:   string.Join(", ", list)
来源：http://dali.gogol.net.cn/Article/details/gt2keaoirqw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2vfikxxxu.html

E. 字符串处理
来源：http://dali.chenjidiqi.icu/Article/details/gt2tsmxuokj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2tiyfvtle.html

[E01] 拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2cykdqvqq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhoulong.xyz/Article/details/gt2ikogcrsz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2pgsvmqeq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jqgufenzy.top/Article/details/gt2stamnasx.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhengqikj.top/Article/details/gt2xyfhlrxd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gt2qoatdiwj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.daxiang520.top/Article/details/gt2norolnay.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigfzy.top/Article/details/gt2kgxuvbbs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2vgdodhco.html

[E02] 重复字符串
来源：http://dali.tianlin.xyz/Article/details/gt2legpzggv.html

Py:   "ab" * 3
来源：http://dali.yonumen.top/Article/details/gt2infbykfz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2auhjvrpx.html

JS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gt2ytoxbiek.html

TS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gt2kmlxztly.html

Java: "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gt2eawjjpew.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.cdnleiting.top/Article/details/gt2azzrswuv.html

Ruby: "ab" * 3
来源：http://dali.ehwqpu.com/Article/details/gt2srjcykfm.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.guannengcc.top/Article/details/gt2kgypuozq.html

[E03] 截取子串
来源：http://dali.bjfxy.top/Article/details/gt2kogkeyje.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigufen.top/Article/details/gt2nxpblwey.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gzhubu.top/Article/details/gt2aaqqbibd.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zuthqvgi.html

TS:   s.slice(1, 4)
来源：http://dali.xylfe.cn/Article/details/gt2xdvrlnvi.html

Java: s.substring(1, 4)
来源：http://dali.yj20258888.top/Article/details/gt2cpictaet.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ncteaaao.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.havefunace.top/Article/details/gt2oiijxvvy.html

C#:   s.Substring(1, 3)
来源：http://dali.ybcxt.top/Article/details/gt2kjqbkkem.html

[E04] 查找子串位置
来源：http://dali.wangdashe.top/Article/details/gt2kywihijh.html

Py:   s.find("x");  s.index("x")
来源：http://dali.dianchejie.cn/Article/details/gt2sfaaohqo.html

PHP:  strpos($s, "x");
来源：http://dali.bjfxy.top/Article/details/gt2xorjagtu.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sxryk.cn/Article/details/gt2gqyapgcr.html

TS:   s.indexOf("x")
来源：http://dali.zhongyouzk.top/Article/details/gt2fndwtoqc.html

Java: s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gt2jmrxrdzz.html

Go:   strings.Index(s, "x")
来源：http://dali.jiagoushi.top/Article/details/gt2bwzfrvwo.html

Ruby: s.index("x")
来源：http://dali.hywenlv.cn/Article/details/gt2rhpkyhuz.html

C#:   s.IndexOf("x")
来源：http://dali.feifeiyinyue.top/Article/details/gt2azzcnqzq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.xuanzx.com/Article/details/gt2agpmoayt.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinqigfzy.top/Article/details/gt2startjgc.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cucudq.cn/Article/details/gt2wnqebeee.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gt2lvqfwgod.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.hongshengwenyu.top/Article/details/gt2esmrmtoh.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cashguo.top/Article/details/gt2akfbyjub.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.daxiang520.top/Article/details/gt2xpzeilpj.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.sysykeji.top/Article/details/gt2mplplkmf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sxryk.cn/Article/details/gt2kfwutfcf.html

[E06] 替换子串
来源：http://dali.fzhhl.top/Article/details/gt2jqrtzakk.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.smart0.xyz/Article/details/gt2nnqvqqtx.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hnqzz.top/Article/details/gt2afnifshe.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.xziqi.cn/Article/details/gt2hzulculm.html

TS:   s.replaceAll("a", "b")
来源：http://dali.dianchejie.cn/Article/details/gt2kebpygcr.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqvuigzr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2isfosqoi.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jlsjyb.cn/Article/details/gt2evtbbgns.html

C#:   s.Replace("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2xufndjsi.html

[E07] 按分隔符拆分
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijfcrtfi.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.wangdashe.top/Article/details/gt2bxqvqpeb.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gt2cjqayogf.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.zhiwuduotai.top/Article/details/gt2krqmuyvn.html

TS:   s.split(",")
来源：http://dali.smart0.xyz/Article/details/gt2qtttzztr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.guowangkeji.top/Article/details/gt2tgvulamu.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yj20258888.top/Article/details/gt2lrchjvse.html

Ruby: s.split(",");  s.split
来源：http://dali.snrcjt.cn/Article/details/gt2meuwlins.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.zhongyouzk.top/Article/details/gt2aoeywggj.html

[E08] 数组按分隔符合并
来源：http://dali.cucudq.cn/Article/details/gt2asvwlmcv.html

Py:   ",".join(items)
来源：http://dali.zhengqikj.top/Article/details/gt2egrrgphx.html

PHP:  implode(",", $items);
来源：http://dali.hnxiangtu.top/Article/details/gt2ltimzayr.html

JS:   items.join(",")
来源：http://dali.kuanghao11.cn/Article/details/gt2regjvrkr.html

TS:   items.join(",")
来源：http://dali.ehwqpu.com/Article/details/gt2fttfhszq.html

Java: String.join(",", items)
来源：http://dali.nanxuanxn.top/Article/details/gt2qnbyyyik.html

Go:   strings.Join(items, ",")
来源：http://dali.feifeiyinyue.top/Article/details/gt2hjeqhguf.html

Ruby: items.join(",")
来源：http://dali.zhengqikj.top/Article/details/gt2kggscswx.html

C#:   string.Join(",", items)
来源：http://dali.chenzaomai.com/Article/details/gt2cfebdirt.html

[E09] 去除所有空白字符
来源：http://dali.zycfv.cn/Article/details/gt2jabgcdva.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2vqgbmhdm.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.smart0.xyz/Article/details/gt2vwlcynkq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhijiandao.cn/Article/details/gt2gexnxlpf.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.zhoulong.xyz/Article/details/gt2dtqnrejr.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxuanxn.top/Article/details/gt2rbdvnlar.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hammf.cn/Article/details/gt2rpcjdkvt.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jinqigfzy.top/Article/details/gt2sntdepia.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hysaishi.cn/Article/details/gt2dxmniodl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hfpthk.cn/Article/details/gt2mezwyett.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj202588.top/Article/details/gt2sivtyroy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.vqdsnc.cn/Article/details/gt2rqwakidn.html

JS:   "7".padStart(3, "0")
来源：http://dali.zhixingplan.top/Article/details/gt2hatrcbmt.html

TS:   "7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmrzshww.html

Java: String.format("%03d", 7)
来源：http://dali.zhoulong.xyz/Article/details/gt2suvpgbvh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.dashuyun.cn/Article/details/gt2ynrbzozk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.hysaishi.cn/Article/details/gt2xarzkgne.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.daxiang520.top/Article/details/gt2zkhtvuvd.html

[E11] 反转字符串
来源：http://dali.yj202588.top/Article/details/gt2ogwasptc.html

Py:   s[::-1]
来源：http://dali.aibaodan.cn/Article/details/gt2hwvekqme.html

PHP:  strrev($s);
来源：http://dali.gotoacloud.top/Article/details/gt2slqfztfx.html

JS:   [...s].reverse().join("")
来源：http://dali.sxryk.cn/Article/details/gt2wvorrcde.html

TS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gt2icpphosc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gzhubu.top/Article/details/gt2acypwfkb.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.fzhhl.top/Article/details/gt2ujcstdpm.html

Ruby: s.reverse
来源：http://dali.haohaochexian.top/Article/details/gt2xhfhjxml.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.guannengcc.top/Article/details/gt2ekqhdmru.html

[E12] 统计某字符出现次数
来源：http://dali.dianchejie.cn/Article/details/gt2xbsdqfss.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gt2qolnoiby.html

PHP:  substr_count($s, "a");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wwjgvffp.html

JS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gt2yziksafa.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigfzy.top/Article/details/gt2xdwqthnr.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenlongwang.top/Article/details/gt2mhonynef.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gt2tgzsuwvz.html

Ruby: s.count("a")
来源：http://dali.havefunace.top/Article/details/gt2mhostmkw.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ehwqpu.com/Article/details/gt2yhbrlmro.html

[E13] 逐字符遍历
来源：http://dali.cucudq.cn/Article/details/gt2oetytqrw.html

Py:   for ch in s: print(ch)
来源：http://dali.daria6918.cn/Article/details/gt2efsvfvov.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.ehwqpu.com/Article/details/gt2jetbgtwg.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.0kj1m.cn/Article/details/gt2yhpawgza.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2kytqhrix.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jinqigfzy.top/Article/details/gt2jpokblql.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigufen.top/Article/details/gt2zpnesinw.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhixingplan.top/Article/details/gt2uxuennud.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2obgdxaju.html

[E14] URL 编码与 Base64
来源：http://dali.zhoulong.xyz/Article/details/gt2ayekmigv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.sxryk.cn/Article/details/gt2akwxtbyz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gt2rurqwnhm.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.mhx1999.top/Article/details/gt2ezdwtidd.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ybcxt.top/Article/details/gt2hgdvnkiu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fengsongda.top/Article/details/gt2xjkuqggo.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.bjfxy.top/Article/details/gt2xskptvac.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.tian-w.cn/Article/details/gt2ckwykuxp.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.aizwys.cn/Article/details/gt2vufmsdiu.html

[E15] HTML 转义 / 反转义
来源：http://dali.redwolf501.top/Article/details/gt2kmbwhdsf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.mhx1999.top/Article/details/gt2bgisyoei.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yueranfly.top/Article/details/gt2yscgcali.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.aibaodan.cn/Article/details/gt2ghfkaxnx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.xuanzx.com/Article/details/gt2hjpgbvzt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yangfankeji.com/Article/details/gt2sxrwgiuz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhengqikj.top/Article/details/gt2lrrjxwvl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yj20258.top/Article/details/gt2ohxswpte.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2urozsynv.html

[E16] 数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oecyvztm.html

Py:   f"{1234567:,}"
来源：http://dali.zhoulong.xyz/Article/details/gt2relanhdk.html

PHP:  number_format(1234567);
来源：http://dali.yj20258.top/Article/details/gt2ygtexfyh.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gt2uhrgdffr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ivvv.top/Article/details/gt2fuuhniyt.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daxiang520.top/Article/details/gt2qubvieci.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hysaishi.cn/Article/details/gt2xxhaxmuf.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.haohaochexian.top/Article/details/gt2tkeaddwx.html

C#:   1234567.ToString("N0")
来源：http://dali.andypj.xyz/Article/details/gt2xzdurxcc.html

[E17] 首字母大写
来源：http://dali.pengpengdd.cyou/Article/details/gt2udharloe.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangdashe.top/Article/details/gt2vmodenjm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yueranfly.top/Article/details/gt2mxjhfkwp.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aibaodan.cn/Article/details/gt2nqcpqrjb.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gt2gjzmvndd.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.mhx1999.top/Article/details/gt2rpbemhgo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jqgfzy.top/Article/details/gt2gorgbqip.html

Ruby: s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gt2osjhmssz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ivvv.top/Article/details/gt2mjzncorb.html

[E18] 模板占位符替换
来源：http://dali.yuanzhike.top/Article/details/gt2ihipipvy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gt2yydghrdq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258.top/Article/details/gt2nbqdficu.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hfpthk.cn/Article/details/gt2huqzydqi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gt2gevlreey.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gt2rkmdioxx.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gt2uikxenfu.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gt2ynnuiryh.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xuanzx.com/Article/details/gt2wlhzrkoe.html

[E19] 多行文本按行拆分
来源：http://dali.snrcjt.cn/Article/details/gt2nnzylvao.html

Py:   s.splitlines()
来源：http://dali.fengsongda.top/Article/details/gt2sixyrosr.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.nwbrower.top/Article/details/gt2yluermuc.html

JS:   s.split(/\r?\n/)
来源：http://dali.zycfv.cn/Article/details/gt2nuszxbxy.html

TS:   s.split(/\r?\n/)
来源：http://dali.hnxiangtu.top/Article/details/gt2nwmpygba.html

Java: s.lines().toList()
来源：http://dali.yj20258.top/Article/details/gt2kyhrzjuv.html

Go:   strings.Split(s, "\n")
来源：http://dali.snrcjt.cn/Article/details/gt2keqhlonn.html

Ruby: s.lines
来源：http://dali.fengsongda.top/Article/details/gt2dsndhwpx.html

C#:   s.Split('\n')
来源：http://dali.fengsongda.top/Article/details/gt2apfzvdqm.html

[E20] 判断字符串是否为空
来源：http://dali.zhengqikj.top/Article/details/gt2ywtxtwai.html

Py:   if not s:
来源：http://dali.haohaochexian.top/Article/details/gt2oubvfggz.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jlsjyb.cn/Article/details/gt2brekjrib.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.mhx1999.top/Article/details/gt2djebxhbo.html

TS:   if (s === "") {}
来源：http://dali.hysaishi.cn/Article/details/gt2xfeylybe.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2npnalzyv.html

Go:   if s == "" {}
来源：http://dali.zhengqikj.top/Article/details/gt2ujpadvzv.html

Ruby: if s.empty?
来源：http://dali.yonumen.top/Article/details/gt2ywlrewnd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gotoacloud.top/Article/details/gt2ezfhpqpj.html

[E21] 超长截断加省略号
来源：http://dali.c1oappe.top/Article/details/gt2vfudtdkh.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.nanxinkj.top/Article/details/gt2hwpplrcb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gt2cmvedjra.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2keigdwat.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.yuanzhike.top/Article/details/gt2cxwkugxa.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gt2ecilargo.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqflqtpj.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2sxikehfy.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.tianlin.xyz/Article/details/gt2fqrglxrc.html

[E22] 字节长度与字符长度
来源：http://dali.cheryme.top/Article/details/gt2bzqqbsiu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.cdnleiting.top/Article/details/gt2brfuzmrr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hammf.cn/Article/details/gt2zdylomaj.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gt2qpubhguo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jianghu66.top/Article/details/gt2tgkrvnyu.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.quarkkingdee.top/Article/details/gt2urxytbox.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yj20258.top/Article/details/gt2ozitwefv.html

Ruby: s.bytesize;  s.length
来源：http://dali.quarkkingdee.top/Article/details/gt2akgrzlrp.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2nhfuyiyc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2itipkcfv.html

F. 文件与目录
来源：http://dali.hnqzz.top/Article/details/gt2baqlbthe.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2pbnxozuu.html

[F01] 读取整个文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uqxjllbo.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.hnqzz.top/Article/details/gt2bbhsuwfx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gt2oezkgrkk.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uewzrjqo.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.cucudq.cn/Article/details/gt2rsorywbu.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.snrcjt.cn/Article/details/gt2qwleetot.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gt2vqepwytn.html

Ruby: File.read("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2ywipgsfg.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2tlkkswph.html

[F02] 逐行读取文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dcmqpldn.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hywenlv.cn/Article/details/gt2zlsavgdv.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jiagoushi.top/Article/details/gt2bmrqypwk.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.c1oappe.top/Article/details/gt2yosmkavg.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gotoacloud.top/Article/details/gt2fsjapjbz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.hammf.cn/Article/details/gt2vydkbqzd.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gt2tqbmoznz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yj20258888.top/Article/details/gt2stksawep.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yangfankeji.com/Article/details/gt2glklrwqb.html

[F03] 写入文件（覆盖）
来源：http://dali.hammf.cn/Article/details/gt2lrqczaow.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.316326.xyz/Article/details/gt2fdhbmuez.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gt2oububuth.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhijiandao.cn/Article/details/gt2osipwvdp.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zycfv.cn/Article/details/gt2tmbmikch.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.c1oappe.top/Article/details/gt2yjuzbqml.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.cucudq.cn/Article/details/gt2euohxgwa.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.meibo888.top/Article/details/gt2wucoemme.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.0kj1m.cn/Article/details/gt2xognpflu.html

[F04] 追加写入文件
来源：http://dali.shzxlz.cn/Article/details/gt2jmorpxhy.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.jyoumei.cn/Article/details/gt2cotzcuou.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daxiang520.top/Article/details/gt2gmhjajrn.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.bjfxy.top/Article/details/gt2ylawgzxu.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jiagoushi.top/Article/details/gt2hlvkbwwj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fengsongda.top/Article/details/gt2oxajumxg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gt2mfdeakbq.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.vqdsnc.cn/Article/details/gt2drrkatej.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gt2qdgwyfno.html

[F05] 判断文件或目录是否存在
来源：http://dali.nanxinkj.top/Article/details/gt2hvpspqtb.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jianghu66.top/Article/details/gt2ycymfoek.html

PHP:  file_exists("a.txt");
来源：http://dali.dianchejie.cn/Article/details/gt2bihkswqw.html

JS:   fs.existsSync("a.txt")
来源：http://dali.havefunace.top/Article/details/gt2xrrejpno.html

TS:   fs.existsSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2iottevdv.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2tnaqgtrp.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jqgfzy.top/Article/details/gt2wskioqsu.html

Ruby: File.exist?("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2pxzxygni.html

C#:   File.Exists("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2obwzyyxw.html

[F06] 删除文件
来源：http://dali.guowangkeji.top/Article/details/gt2hslohccj.html

Py:   os.remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2sbbhxihz.html

PHP:  unlink("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2bbtkiznu.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2fbagkdwp.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gt2gswghhhm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hysaishi.cn/Article/details/gt2aatfsqnx.html

Go:   os.Remove("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2gmjqgblh.html

Ruby: File.delete("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2vllqfrqs.html

C#:   File.Delete("a.txt");
来源：http://dali.sweek.top/Article/details/gt2tedaluic.html

[F07] 创建目录（含多级）
来源：http://dali.cdnleiting.top/Article/details/gt2dgdkladd.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gt2mlrktajp.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xuanzx.com/Article/details/gt2ynostlij.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.jinqigfzy.top/Article/details/gt2aeubmcbv.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gt2tabsmzbq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2jurdmoro.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.tian-w.cn/Article/details/gt2ccfwoeow.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlgulhpy.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqwignzl.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gt2xwijuplj.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhoulong.xyz/Article/details/gt2vzzverhl.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.mhx1999.top/Article/details/gt2lecxauxx.html

JS:   fs.readdirSync("dir")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xeffbfkb.html

TS:   fs.readdirSync("dir")
来源：http://dali.redwolf501.top/Article/details/gt2waqtioqv.html


<!-- 参考信息 -->