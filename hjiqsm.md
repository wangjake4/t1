代发 wailian999

Java: new ArrayList<>(list);
来源：http://dali.tianlin.xyz/Article/details/gt2weksdbnz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.svipenyu.cn/Article/details/gt2rjgtfbog.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gt2ogsrmysh.html

C#:   new List<int>(list);
来源：http://dali.aibaodan.cn/Article/details/gt2qsxwnypo.html

[D23] reduce 累积计算
来源：http://dali.quarkkingdee.top/Article/details/gt2vehnvtqs.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xylfe.cn/Article/details/gt2lvxogbmn.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2feierbsv.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2temsgpxs.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2lraohioe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.cashguo.top/Article/details/gt2wyshgqio.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gt2gnusfgdw.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jqgufenzy.top/Article/details/gt2wjvxvnab.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.smart0.xyz/Article/details/gt2laqgmpof.html

[D24] 字典 / Map 基本操作
来源：http://dali.ehwqpu.com/Article/details/gt2jekccoft.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yuanzhike.top/Article/details/gt2rnadanhl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.havefunace.top/Article/details/gt2oerwamqj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gt2dplirmmy.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gt2nvrjxext.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xinyue.icu/Article/details/gt2holhpddl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhengqikj.top/Article/details/gt2vpwetvzi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yangfankeji.com/Article/details/gt2xhyntjza.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gt2otnbepnt.html

[D25] Set 集合去重与交并差
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ykeapyvj.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.mhx1999.top/Article/details/gt2yifkrdqa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.guowangkeji.top/Article/details/gt2ddkpbrvd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hfpthk.cn/Article/details/gt2kufdlgdx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangdashe.top/Article/details/gt2kkmitmfr.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ajlhydrp.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenzaomai.com/Article/details/gt2mdditldj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guannengcc.top/Article/details/gt2sbpljqus.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sxryk.cn/Article/details/gt2eaptvoml.html

[D26] 数组转字符串
来源：http://dali.sxryk.cn/Article/details/gt2vcqfjkrw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.ehwqpu.com/Article/details/gt2plikcfhl.html

PHP:  implode(", ", $arr);
来源：http://dali.hywenlv.cn/Article/details/gt2xwezbigq.html

JS:   arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gt2ybpwffbo.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2nijsuqcm.html

Java: String.join(", ", list)
来源：http://dali.pycfn.com/Article/details/gt2sqmtxsdh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgfzy.top/Article/details/gt2qzgpofxc.html

Ruby: arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gt2hojdlhfo.html

C#:   string.Join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gt2rwxqlajx.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2btajzjhn.html

E. 字符串处理
来源：http://dali.zdqjudy.top/Article/details/gt2jigapnhp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2gtznrsaw.html

[E01] 拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2vjuypnmk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.bjfxy.top/Article/details/gt2mnrwfmvv.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.daria6918.cn/Article/details/gt2nepyefow.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gt2knjtslfp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhijiandao.cn/Article/details/gt2clcurjsu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dianchejie.cn/Article/details/gt2pepduvbz.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.aizwys.cn/Article/details/gt2ihktmuns.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybtprzeb.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gt2dfhjmief.html

[E02] 重复字符串
来源：http://dali.ppjwa.cn/Article/details/gt2uldhnyyj.html

Py:   "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gt2afvlxrgn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yonumen.top/Article/details/gt2qedapnob.html

JS:   "ab".repeat(3)
来源：http://dali.snrcjt.cn/Article/details/gt2fsaokseu.html

TS:   "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sxvoaqen.html

Java: "ab".repeat(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbtwkifm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jldjqcbc.html

Ruby: "ab" * 3
来源：http://dali.havefunace.top/Article/details/gt2xfhlzjmg.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenjidiqi.icu/Article/details/gt2xocxuluq.html

[E03] 截取子串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zggwjdeb.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.sxryk.cn/Article/details/gt2ihcpomdg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gt2oxwmeiuh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2zrwbcctx.html

TS:   s.slice(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ouibkwce.html

Java: s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gt2vbuamwpu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.fengsongda.top/Article/details/gt2uxdxujbd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqhfkhau.html

C#:   s.Substring(1, 3)
来源：http://dali.yueranfly.top/Article/details/gt2xssxuces.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gt2oahjphnu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zycfv.cn/Article/details/gt2ojpnjyhc.html

PHP:  strpos($s, "x");
来源：http://dali.zhijiandao.cn/Article/details/gt2zeauumvh.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.hnqzz.top/Article/details/gt2xdwiedgm.html

TS:   s.indexOf("x")
来源：http://dali.fzhhl.top/Article/details/gt2pwxxzakj.html

Java: s.indexOf("x")
来源：http://dali.xuanzx.com/Article/details/gt2fnslztsk.html

Go:   strings.Index(s, "x")
来源：http://dali.gogol.net.cn/Article/details/gt2igagojel.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gt2vbjstnxy.html

C#:   s.IndexOf("x")
来源：http://dali.tian-w.cn/Article/details/gt2zresiybw.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.iojbl.cn/Article/details/gt2slpuybla.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yonumen.top/Article/details/gt2juriswbu.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258.top/Article/details/gt2knyvgffq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cqqwz.cn/Article/details/gt2jhbgldws.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.aibaodan.cn/Article/details/gt2irlsuaul.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cheryme.top/Article/details/gt2kpsdyzpf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.andypj.xyz/Article/details/gt2ozqqkaxz.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zglkzpwe.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhongyouzk.top/Article/details/gt2icoylkfv.html

[E06] 替换子串
来源：http://dali.zycfv.cn/Article/details/gt2khqfhnsw.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.tanke756.top/Article/details/gt2xzeuoirr.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.yj202588.top/Article/details/gt2pdwaadey.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gt2ygeodmfx.html

TS:   s.replaceAll("a", "b")
来源：http://dali.hammf.cn/Article/details/gt2lpdjtexd.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zycfv.cn/Article/details/gt2vmlodyrr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.bjfxy.top/Article/details/gt2otpvcxqr.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gt2gcitwmaq.html

C#:   s.Replace("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2wlsvgews.html

[E07] 按分隔符拆分
来源：http://dali.nanxinkj.top/Article/details/gt2maxzireo.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gzhubu.top/Article/details/gt2wpqxtcmc.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.gotoacloud.top/Article/details/gt2eofhszjd.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.xylfe.cn/Article/details/gt2zsathyid.html

TS:   s.split(",")
来源：http://dali.fengsongda.top/Article/details/gt2grmegwwk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.xinyue.icu/Article/details/gt2ttzeeynh.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jiagoushi.top/Article/details/gt2njodnbpz.html

Ruby: s.split(",");  s.split
来源：http://dali.quarkkingdee.top/Article/details/gt2etzvqmwr.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gt2crtadica.html

[E08] 数组按分隔符合并
来源：http://dali.yangfankeji.com/Article/details/gt2woqutqbb.html

Py:   ",".join(items)
来源：http://dali.aizwys.cn/Article/details/gt2svbxeqmp.html

PHP:  implode(",", $items);
来源：http://dali.ybcxt.top/Article/details/gt2xzxhwqmk.html

JS:   items.join(",")
来源：http://dali.dianchejie.cn/Article/details/gt2wzepabjn.html

TS:   items.join(",")
来源：http://dali.sufxvd.cn/Article/details/gt2zgeupazm.html

Java: String.join(",", items)
来源：http://dali.vqdsnc.cn/Article/details/gt2nvmpzfjv.html

Go:   strings.Join(items, ",")
来源：http://dali.sysykeji.top/Article/details/gt2oceskmxn.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gt2ucnhlwbn.html

C#:   string.Join(",", items)
来源：http://dali.birdmap.top/Article/details/gt2xowliuck.html

[E09] 去除所有空白字符
来源：http://dali.cqqwz.cn/Article/details/gt2sazweaej.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jiagoushi.top/Article/details/gt2fdrabdgq.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ehwqpu.com/Article/details/gt2htdqjobs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gt2rankenlw.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.hnqzz.top/Article/details/gt2hembxynu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.sxryk.cn/Article/details/gt2dhchrbsu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.hfpthk.cn/Article/details/gt2czkaljzn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cqqwz.cn/Article/details/gt2odfjxtob.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.daria6918.cn/Article/details/gt2gffxxkjw.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xuetiantiany.cn/Article/details/gt2pplkfien.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.cashguo.top/Article/details/gt2mzezxgcv.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shzxlz.cn/Article/details/gt2eefhlzjb.html

JS:   "7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gt2yesdvanw.html

TS:   "7".padStart(3, "0")
来源：http://dali.jlsjyb.cn/Article/details/gt2izhrsgul.html

Java: String.format("%03d", 7)
来源：http://dali.ppjwa.cn/Article/details/gt2kbdbzvyu.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hnqzz.top/Article/details/gt2thqbkkdz.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gt2kyhsjykf.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shangyingyoupin.top/Article/details/gt2oexggers.html

[E11] 反转字符串
来源：http://dali.cashguo.top/Article/details/gt2ayygdbss.html

Py:   s[::-1]
来源：http://dali.shangyingyoupin.top/Article/details/gt2tsdynyww.html

PHP:  strrev($s);
来源：http://dali.sweek.top/Article/details/gt2shgfpqdi.html

JS:   [...s].reverse().join("")
来源：http://dali.sufxvd.cn/Article/details/gt2wdofhegc.html

TS:   [...s].reverse().join("")
来源：http://dali.aibaodan.cn/Article/details/gt2nuqfvbbr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2sejqfkmx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cashguo.top/Article/details/gt2ikisgmdp.html

Ruby: s.reverse
来源：http://dali.jqgufenzy.top/Article/details/gt2iiowtiua.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yongpay.top/Article/details/gt2iyczkehr.html

[E12] 统计某字符出现次数
来源：http://dali.316326.xyz/Article/details/gt2uvhglikz.html

Py:   s.count("a")
来源：http://dali.tanke756.top/Article/details/gt2hjnuytfz.html

PHP:  substr_count($s, "a");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2adcmqqqp.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cowvdeav.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gt2hetnghlw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.andypj.xyz/Article/details/gt2njljzscc.html

Go:   strings.Count(s, "a")
来源：http://dali.havefunace.top/Article/details/gt2vmvbbgab.html

Ruby: s.count("a")
来源：http://dali.cashguo.top/Article/details/gt2sjqwszzh.html

C#:   s.Count(c => c == 'a')
来源：http://dali.tian-w.cn/Article/details/gt2minsvlak.html

[E13] 逐字符遍历
来源：http://dali.jianghu66.top/Article/details/gt2rywneznv.html

Py:   for ch in s: print(ch)
来源：http://dali.ehwqpu.com/Article/details/gt2smdmxrqh.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zycfv.cn/Article/details/gt2mmqmcncd.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.aizwys.cn/Article/details/gt2odnvrlfx.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hwigtqau.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.cucudq.cn/Article/details/gt2viwpcmqo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xinyue.icu/Article/details/gt2ediuixfa.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhengqikj.top/Article/details/gt2ltirgcxp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.yuxming.cn/Article/details/gt2kbeodnel.html

[E14] URL 编码与 Base64
来源：http://dali.yangfankeji.com/Article/details/gt2jyeavdvd.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gt2yriznupd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.svipenyu.cn/Article/details/gt2bvleqcym.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gt2cwwidvnr.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cucudq.cn/Article/details/gt2shhjzntv.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.xylfe.cn/Article/details/gt2ojuijaqk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhongyouzk.top/Article/details/gt2nifpxlbl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.hnxiangtu.top/Article/details/gt2ygawxxem.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.tanke756.top/Article/details/gt2yargkleg.html

[E15] HTML 转义 / 反转义
来源：http://dali.tanke756.top/Article/details/gt2ipwplyda.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2cowgmmrl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.c1oappe.top/Article/details/gt2trjrsnox.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hywenlv.cn/Article/details/gt2jjarbgtb.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.aibaodan.cn/Article/details/gt2znkzbqzf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.snrcjt.cn/Article/details/gt2owuvvogw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xziqi.cn/Article/details/gt2nfvvlukx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cucudq.cn/Article/details/gt2ddhemddf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.9152youxi.cn/Article/details/gt2izyyxvel.html

[E16] 数字千分位
来源：http://dali.aibaodan.cn/Article/details/gt2olbyrokj.html

Py:   f"{1234567:,}"
来源：http://dali.tanke756.top/Article/details/gt2qzlqbpqe.html

PHP:  number_format(1234567);
来源：http://dali.yongpay.top/Article/details/gt2mmxxysrw.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gt2xsverfgv.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.aizwys.cn/Article/details/gt2muwkitni.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gt2rethwnnm.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.dianchejie.cn/Article/details/gt2iypkbuep.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2teselerx.html

C#:   1234567.ToString("N0")
来源：http://dali.fzhhl.top/Article/details/gt2gmqyzeft.html

[E17] 首字母大写
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxohpdkw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxzzgyio.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.quarkkingdee.top/Article/details/gt2rfwzderw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2txaqwzve.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gt2lhinsliv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.haohaochexian.top/Article/details/gt2bpzrcdzk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shangyingyoupin.top/Article/details/gt2tprmctey.html

Ruby: s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gt2qeucwwro.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.tanke756.top/Article/details/gt2hnzydlqz.html

[E18] 模板占位符替换
来源：http://dali.aizwys.cn/Article/details/gt2ccyqvwuz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.cashguo.top/Article/details/gt2hoeopbsy.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sweek.top/Article/details/gt2ehoopylb.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.havefunace.top/Article/details/gt2aumegicn.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.hnqzz.top/Article/details/gt2omarilop.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2lmotmgif.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.ybcxt.top/Article/details/gt2qucyvtdp.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gkmdpyag.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.redwolf501.top/Article/details/gt2mobuwhmm.html

[E19] 多行文本按行拆分
来源：http://dali.cqqwz.cn/Article/details/gt2knjbkcju.html

Py:   s.splitlines()
来源：http://dali.ivvv.top/Article/details/gt2uqnbbawz.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.xylfe.cn/Article/details/gt2simzcjww.html

JS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gt2gcokdoqy.html

TS:   s.split(/\r?\n/)
来源：http://dali.ehwqpu.com/Article/details/gt2auentoqp.html

Java: s.lines().toList()
来源：http://dali.sxryk.cn/Article/details/gt2iycxqbcr.html

Go:   strings.Split(s, "\n")
来源：http://dali.ppjwa.cn/Article/details/gt2wwajvhbb.html

Ruby: s.lines
来源：http://dali.yj20258888.top/Article/details/gt2kmcvrpnt.html

C#:   s.Split('\n')
来源：http://dali.meibo888.top/Article/details/gt2izryicno.html

[E20] 判断字符串是否为空
来源：http://dali.chenjidiqi.icu/Article/details/gt2dbcjrxcr.html

Py:   if not s:
来源：http://dali.yj20258888.top/Article/details/gt2oegwafug.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hywenlv.cn/Article/details/gt2bbjhokey.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2eumioeek.html

TS:   if (s === "") {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2ziwepolg.html

Java: if (s.isEmpty()) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kehikkge.html

Go:   if s == "" {}
来源：http://dali.bjfxy.top/Article/details/gt2wzonejcv.html

Ruby: if s.empty?
来源：http://dali.316326.xyz/Article/details/gt2jrjrmwvg.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuxming.cn/Article/details/gt2aifxjebz.html

[E21] 超长截断加省略号
来源：http://dali.zhengqikj.top/Article/details/gt2stjsdgie.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.daria6918.cn/Article/details/gt2weyslcdh.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.nanxuanxn.top/Article/details/gt2qjtrrgnx.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2vtpjnoar.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.hammf.cn/Article/details/gt2qxftsnyr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.cashguo.top/Article/details/gt2isymcjqj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.nanxuanxn.top/Article/details/gt2povozdab.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangdashe.top/Article/details/gt2nefsjjmc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gt2oytqvsgz.html

[E22] 字节长度与字符长度
来源：http://dali.ybcxt.top/Article/details/gt2yezsgbei.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2ksruxlrc.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.iojbl.cn/Article/details/gt2gatknlcc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj20258888.top/Article/details/gt2syusoqwy.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2kpqjxgcs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hysaishi.cn/Article/details/gt2sbsinvcy.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ehwqpu.com/Article/details/gt2ltjxjdcu.html

Ruby: s.bytesize;  s.length
来源：http://dali.gzhubu.top/Article/details/gt2ntjbklut.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2siqmvtlk.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2qwdlsoke.html

F. 文件与目录
来源：http://dali.cdnleiting.top/Article/details/gt2lxgnexao.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2knxklaop.html

[F01] 读取整个文件
来源：http://dali.snrcjt.cn/Article/details/gt2imyzjyyz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hnxmzesk.html

PHP:  file_get_contents("a.txt");
来源：http://dali.xuanzx.com/Article/details/gt2ponhjqfr.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.daxiang520.top/Article/details/gt2ophlsaov.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.xuetiantiany.cn/Article/details/gt2sjanvktg.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.nanxinkj.top/Article/details/gt2ypedypcq.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.haohaochexian.top/Article/details/gt2xqdasbdd.html

Ruby: File.read("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gt2bskzwlvh.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.gaohongyu789.top/Article/details/gt2jarjgwby.html

[F02] 逐行读取文件
来源：http://dali.dianchejie.cn/Article/details/gt2viorjfgw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.xylfe.cn/Article/details/gt2seasdgul.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.quarkkingdee.top/Article/details/gt2mwdquhpo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqjyrgvw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.ivvv.top/Article/details/gt2ycplzltp.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.smart0.xyz/Article/details/gt2czypgkzo.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.jqgufenzy.top/Article/details/gt2rajierwt.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.ivvv.top/Article/details/gt2loajqgjr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.316326.xyz/Article/details/gt2krxbzmwm.html

[F03] 写入文件（覆盖）
来源：http://dali.redwolf501.top/Article/details/gt2cqxmawxk.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shzxlz.cn/Article/details/gt2fxeymwzy.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2kmuhlumf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gt2mqrhohzx.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.jianghu66.top/Article/details/gt2miqlpimj.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.tianlin.xyz/Article/details/gt2asmonppn.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rnfahvrm.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nwbrower.top/Article/details/gt2rcpsfbcq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2whioqgpr.html

[F04] 追加写入文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2tfyydhzf.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sufxvd.cn/Article/details/gt2wydrqucb.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shzxlz.cn/Article/details/gt2zhlscyad.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xuanzx.com/Article/details/gt2hshvimuf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jqgufenzy.top/Article/details/gt2kuznivtw.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.chenlongwang.top/Article/details/gt2umiiyczb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yuxming.cn/Article/details/gt2kynshjub.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.havefunace.top/Article/details/gt2xwvttcmn.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.daxiang520.top/Article/details/gt2baslnmuj.html

[F05] 判断文件或目录是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2lmjxipwg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.haohaochexian.top/Article/details/gt2hxtckscv.html

PHP:  file_exists("a.txt");
来源：http://dali.guannengcc.top/Article/details/gt2wzqtksrt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gt2orvqlzab.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yj202588.top/Article/details/gt2nzxqhokm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2mgjdwiun.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xinyue.icu/Article/details/gt2skosdexv.html

Ruby: File.exist?("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2donrimeo.html

C#:   File.Exists("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ddiwhznd.html

[F06] 删除文件
来源：http://dali.jinqigfzy.top/Article/details/gt2lgkwured.html

Py:   os.remove("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gt2nalssauw.html

PHP:  unlink("a.txt");
来源：http://dali.zhengqikj.top/Article/details/gt2mtfojluf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2sdmraivk.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2ahduuohf.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.dianchejie.cn/Article/details/gt2tybdqjpv.html

Go:   os.Remove("a.txt")
来源：http://dali.yueranfly.top/Article/details/gt2pykjzkqc.html

Ruby: File.delete("a.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2fyiqfgbr.html

C#:   File.Delete("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gt2ejvzmcjr.html

[F07] 创建目录（含多级）
来源：http://dali.sxryk.cn/Article/details/gt2ldxjvtdq.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ybcxt.top/Article/details/gt2dcuqxizh.html


<!-- 参考信息 -->