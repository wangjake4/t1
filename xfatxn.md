代发 wailian999

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aibaodan.cn/Article/details/gtzlamenyj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cashguo.top/Article/details/gtrkkjosoz.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.havefunace.top/Article/details/gtmkzoserm.html

Go:   // 手写 map[T]int
来源：http://dali.hysaishi.cn/Article/details/gthvfecjix.html

Ruby: arr.tally
来源：http://dali.andypj.xyz/Article/details/gtdtuadytn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxinkj.top/Article/details/gtbglkcsex.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gtxtlssqiw.html

Py:   x in arr
来源：http://dali.zhongyouzk.top/Article/details/gtrxwlwbpy.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gotoacloud.top/Article/details/gtpcucdogc.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtzxcuphtf.html

TS:   arr.includes(x)
来源：http://dali.xziqi.cn/Article/details/gtzidfuoim.html

Java: list.contains(x)
来源：http://dali.pycfn.com/Article/details/gtocyuffsh.html

Go:   slices.Contains(arr, x)
来源：http://dali.cheryme.top/Article/details/gtpiditpwr.html

Ruby: arr.include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecdipsed.html

C#:   list.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtmrgaakey.html

[D22] 复制数组（避免共享引用）
来源：http://dali.9152youxi.cn/Article/details/gturyjxmbd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ybcxt.top/Article/details/gthtyutrsf.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.0kj1m.cn/Article/details/gtfiwprqkl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gthdzgendj.html

TS:   [...arr];
来源：http://dali.andypj.xyz/Article/details/gtsqdjjcpl.html

Java: new ArrayList<>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqotllqst.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shuidangran.top/Article/details/gtmdnlvhgg.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fzhhl.top/Article/details/gtyxbohkpi.html

C#:   new List<int>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtnyhdrpea.html

[D23] reduce 累积计算
来源：http://dali.hongshengwenyu.top/Article/details/gtbwxacpsx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gtckwirhmk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sufxvd.cn/Article/details/gtdvxtzqpo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.chenlongwang.top/Article/details/gtvksrsepw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yvedp.cn/Article/details/gtpvxfwsgp.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.svipenyu.cn/Article/details/gtxjgcvhpe.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gticxmhzbq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yuanzhike.top/Article/details/gtxypvwohp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.svipenyu.cn/Article/details/gtbflfestf.html

[D24] 字典 / Map 基本操作
来源：http://dali.cqqwz.cn/Article/details/gtxjmaspsw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jinqigfzy.top/Article/details/gttxwqjkxg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.sxryk.cn/Article/details/gtyfnmynyc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenlongwang.top/Article/details/gttrnvwtdm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtprucyrdz.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yvedp.cn/Article/details/gtshytbjmg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.aizwys.cn/Article/details/gtatkexyqf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.guannengcc.top/Article/details/gtuwbqbnom.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cheryme.top/Article/details/gtlfylbsuy.html

[D25] Set 集合去重与交并差
来源：http://dali.ivvv.top/Article/details/gtddbndqkl.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.wangshuangyany.cn/Article/details/gtjeehgwji.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jlsjyb.cn/Article/details/gtnshreenj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cqqwz.cn/Article/details/gtzemibjuz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.pycfn.com/Article/details/gtczzoqofa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnqzz.top/Article/details/gtxschhvjo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlsgcvpvv.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.ydzc1.top/Article/details/gtwyrwpxbd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhixingplan.top/Article/details/gthgnbsocm.html

[D26] 数组转字符串
来源：http://dali.kuanghao11.cn/Article/details/gtlsegetgk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cucudq.cn/Article/details/gtvzxgrdhu.html

PHP:  implode(", ", $arr);
来源：http://dali.yueranfly.top/Article/details/gtcodxmxhc.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtvlxwqzwm.html

TS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gtheirsdve.html

Java: String.join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gtsvzomcja.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yanxiufei.cn/Article/details/gtzjdinogw.html

Ruby: arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtrjnxhdhb.html

C#:   string.Join(", ", list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaofwqunz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtcfmslgdf.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gtstfvruwh.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtcimgjvjq.html

[E01] 拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtkjgnktrb.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ivvv.top/Article/details/gtbaylecxj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ybcxt.top/Article/details/gtnvbzuvyo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gtqyvhztix.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shzxlz.cn/Article/details/gtdsxfyund.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.sysykeji.top/Article/details/gtwarfteee.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gtcxlcpdws.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hammf.cn/Article/details/gtsfmfrtbf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.cashguo.top/Article/details/gtslqdrcdo.html

[E02] 重复字符串
来源：http://dali.sufxvd.cn/Article/details/gtmxbwghzd.html

Py:   "ab" * 3
来源：http://dali.shangyingyoupin.top/Article/details/gtcbppcusy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj202588.top/Article/details/gtqwnrxgvg.html

JS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtidfklinz.html

TS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtbxtkssfm.html

Java: "ab".repeat(3)
来源：http://dali.gotoacloud.top/Article/details/gtjctdcgia.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.fengsongda.top/Article/details/gtvipqdcaz.html

Ruby: "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gtmwykwrtd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenzaomai.com/Article/details/gtwodaaksn.html

[E03] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtqcrpypaz.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.meibo888.top/Article/details/gtbqygkzcn.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.aibaodan.cn/Article/details/gtispmhhrr.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yangfankeji.com/Article/details/gtbvffckck.html

TS:   s.slice(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtkoodwniu.html

Java: s.substring(1, 4)
来源：http://dali.yj20258.top/Article/details/gtgolccdsx.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yonumen.top/Article/details/gtnocybezp.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hysaishi.cn/Article/details/gtsqgonoyq.html

C#:   s.Substring(1, 3)
来源：http://dali.snrcjt.cn/Article/details/gtwhzhevyr.html

[E04] 查找子串位置
来源：http://dali.sxryk.cn/Article/details/gtokaukdib.html

Py:   s.find("x");  s.index("x")
来源：http://dali.sufxvd.cn/Article/details/gtnrukkxfr.html

PHP:  strpos($s, "x");
来源：http://dali.tian-w.cn/Article/details/gtfhtjbgso.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sufxvd.cn/Article/details/gtvierwkdp.html

TS:   s.indexOf("x")
来源：http://dali.svipenyu.cn/Article/details/gtunagsink.html

Java: s.indexOf("x")
来源：http://dali.jinqigfzy.top/Article/details/gtisnqridj.html

Go:   strings.Index(s, "x")
来源：http://dali.bjfxy.top/Article/details/gtbvxesiqx.html

Ruby: s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gtlutoaehi.html

C#:   s.IndexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gtphazixln.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodgkzztk.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuzpwfrao.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhengqikj.top/Article/details/gtmakvpnpz.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtvjbaczqx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sweek.top/Article/details/gtfkjblrqn.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.zhoulong.xyz/Article/details/gteguckwtx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.0kj1m.cn/Article/details/gtfdevygtc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.iojbl.cn/Article/details/gtuqzbgrme.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.zhengqikj.top/Article/details/gtjuniuteo.html

[E06] 替换子串
来源：http://dali.tian-w.cn/Article/details/gtgyxhkbmz.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sysykeji.top/Article/details/gtuyvspkwa.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.smart0.xyz/Article/details/gtuwmcuxsy.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtrcfsiyme.html

TS:   s.replaceAll("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjjcvwhz.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtapxiwzwz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.jinqigufen.top/Article/details/gtqzjoxkfu.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cdnleiting.top/Article/details/gtquvykagh.html

C#:   s.Replace("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuiylvqmp.html

[E07] 按分隔符拆分
来源：http://dali.daria6918.cn/Article/details/gtiuqzdszq.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gogol.net.cn/Article/details/gtpegxyhic.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.nanxinkj.top/Article/details/gtqjxjwmrb.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.andypj.xyz/Article/details/gtrdymsxez.html

TS:   s.split(",")
来源：http://dali.tanke756.top/Article/details/gtrbmgsomz.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.aibaodan.cn/Article/details/gtsgtcnexy.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.sufxvd.cn/Article/details/gtzfgzoplf.html

Ruby: s.split(",");  s.split
来源：http://dali.ehwqpu.com/Article/details/gtbbukrnwy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.xuanzx.com/Article/details/gtcmifftso.html

[E08] 数组按分隔符合并
来源：http://dali.ehwqpu.com/Article/details/gtqwjxqwbu.html

Py:   ",".join(items)
来源：http://dali.smart0.xyz/Article/details/gtkyvqnank.html

PHP:  implode(",", $items);
来源：http://dali.zhongyouzk.top/Article/details/gtxhttxskz.html

JS:   items.join(",")
来源：http://dali.feifeiyinyue.top/Article/details/gtydasgapd.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtbnddndwt.html

Java: String.join(",", items)
来源：http://dali.jlsjyb.cn/Article/details/gtfzuqpqla.html

Go:   strings.Join(items, ",")
来源：http://dali.gaohongyu789.top/Article/details/gtkwybvoai.html

Ruby: items.join(",")
来源：http://dali.smart0.xyz/Article/details/gttzjdzzdg.html

C#:   string.Join(",", items)
来源：http://dali.316326.xyz/Article/details/gtotpflfgc.html

[E09] 去除所有空白字符
来源：http://dali.yanxiufei.cn/Article/details/gthjlmkqha.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jqgufenzy.top/Article/details/gtsyozssfi.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.daria6918.cn/Article/details/gtancslgeu.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.9152youxi.cn/Article/details/gtjgcrzhhn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.cdnleiting.top/Article/details/gticweivay.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.smart0.xyz/Article/details/gthcmfbbfc.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.redwolf501.top/Article/details/gtpzedunsb.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.pengpengdd.cyou/Article/details/gtvppgyadd.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fzhhl.top/Article/details/gtsgeggeqj.html

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gtebrjrywk.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.yj202588.top/Article/details/gtzgedwszc.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhbvffej.html

JS:   "7".padStart(3, "0")
来源：http://dali.hnxiangtu.top/Article/details/gtcefidlpv.html

TS:   "7".padStart(3, "0")
来源：http://dali.ydzc1.top/Article/details/gtgtcicbgu.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtdzhlcros.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yuxming.cn/Article/details/gtedyrjkfc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtewatmyxi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.guowangkeji.top/Article/details/gtebngyesk.html

[E11] 反转字符串
来源：http://dali.snrcjt.cn/Article/details/gtwdpajaew.html

Py:   s[::-1]
来源：http://dali.zhoulong.xyz/Article/details/gtfbzfgdct.html

PHP:  strrev($s);
来源：http://dali.xinyue.icu/Article/details/gtgydecynj.html

JS:   [...s].reverse().join("")
来源：http://dali.ppjwa.cn/Article/details/gtfpmbahfa.html

TS:   [...s].reverse().join("")
来源：http://dali.zhijiandao.cn/Article/details/gtkczwfkmh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.feifeiyinyue.top/Article/details/gttlmydaya.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gzhubu.top/Article/details/gtuiafmhpb.html

Ruby: s.reverse
来源：http://dali.tianlin.xyz/Article/details/gtppnulups.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.andypj.xyz/Article/details/gtctzprywh.html

[E12] 统计某字符出现次数
来源：http://dali.tianlin.xyz/Article/details/gtbhkkqpao.html

Py:   s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtbokwinke.html

PHP:  substr_count($s, "a");
来源：http://dali.tian-w.cn/Article/details/gtvjvdzegn.html

JS:   s.split("a").length - 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtfrkphecy.html

TS:   s.split("a").length - 1
来源：http://dali.vqdsnc.cn/Article/details/gtqjuyswvc.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gtrbxbiymc.html

Go:   strings.Count(s, "a")
来源：http://dali.pycfn.com/Article/details/gtwxwldpnr.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtwnaawelb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shangyingyoupin.top/Article/details/gtrvibgnqq.html

[E13] 逐字符遍历
来源：http://dali.xylfe.cn/Article/details/gtwbtzjtxw.html

Py:   for ch in s: print(ch)
来源：http://dali.cheryme.top/Article/details/gtrvbrsxvp.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhongyouzk.top/Article/details/gtpzdhglml.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.vqdsnc.cn/Article/details/gtjsclxwjn.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtmpcludwt.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.dashuyun.cn/Article/details/gtlbbpzsol.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gtagyzbkma.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gtmnvdbalk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gtmgsawapz.html

[E14] URL 编码与 Base64
来源：http://dali.jyoumei.cn/Article/details/gtjqawaapw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yonumen.top/Article/details/gtthigxorc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.feifeiyinyue.top/Article/details/gtokmsbbds.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yangfankeji.com/Article/details/gtpagvscik.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj20258888.top/Article/details/gtheqxfvxo.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.bjfxy.top/Article/details/gtgitwylyp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yj20258888.top/Article/details/gtejflogpd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yonumen.top/Article/details/gtbaghctwe.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.feifeiyinyue.top/Article/details/gtemlyyadb.html

[E15] HTML 转义 / 反转义
来源：http://dali.zhengqikj.top/Article/details/gttzejjkzj.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.quarkkingdee.top/Article/details/gtwsneblrd.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cqqwz.cn/Article/details/gtuekznadk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gthxogdelk.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenlongwang.top/Article/details/gtrrgauumx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xylfe.cn/Article/details/gtbwrxprwq.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nwbrower.top/Article/details/gtvnwsnvib.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbgyypnc.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.tian-w.cn/Article/details/gtrwiggwru.html

[E16] 数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gtlkgiqwsg.html

Py:   f"{1234567:,}"
来源：http://dali.wangshuangyany.cn/Article/details/gtneuvdbqv.html

PHP:  number_format(1234567);
来源：http://dali.gogol.net.cn/Article/details/gtnuatwvdv.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmyhruak.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hongshengwenyu.top/Article/details/gtmcxvyunk.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yj20258888.top/Article/details/gtzlmcqsph.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.wangshuangyany.cn/Article/details/gthjjtizaa.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtpjdmqxcs.html

C#:   1234567.ToString("N0")
来源：http://dali.shzxlz.cn/Article/details/gtfmccxizm.html

[E17] 首字母大写
来源：http://dali.yongpay.top/Article/details/gtmqsrmcoj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tianlin.xyz/Article/details/gtoyhrvbdk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.dashuyun.cn/Article/details/gtgvnlpyao.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigfzy.top/Article/details/gtlcoxkgxx.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.aizwys.cn/Article/details/gttxofpwog.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxydfhvw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.daxiang520.top/Article/details/gthpwwbjcp.html

Ruby: s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gtmjxcipnq.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.chenlongwang.top/Article/details/gtbtsdszpe.html

[E18] 模板占位符替换
来源：http://dali.hnqzz.top/Article/details/gtomhpmfav.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.shangyingyoupin.top/Article/details/gtubymskeu.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.yj20258.top/Article/details/gtdotjgggx.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.sweek.top/Article/details/gtauzazloo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinghuilouyu.cn/Article/details/gtixrwhuho.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daria6918.cn/Article/details/gtntumkgjn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hywenlv.cn/Article/details/gtokichmkc.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.9152youxi.cn/Article/details/gtjkmrtubd.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.quarkkingdee.top/Article/details/gtslpvuadt.html

[E19] 多行文本按行拆分
来源：http://dali.hnqzz.top/Article/details/gtkxckrcjb.html

Py:   s.splitlines()
来源：http://dali.jqgfzy.top/Article/details/gtygurtuqv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.c1oappe.top/Article/details/gtsbffopia.html

JS:   s.split(/\r?\n/)
来源：http://dali.quarkkingdee.top/Article/details/gtrwrghijo.html

TS:   s.split(/\r?\n/)
来源：http://dali.xuetiantiany.cn/Article/details/gtxstooprn.html

Java: s.lines().toList()
来源：http://dali.tianlin.xyz/Article/details/gtgnymdipo.html

Go:   strings.Split(s, "\n")
来源：http://dali.sysykeji.top/Article/details/gtsbofpgah.html

Ruby: s.lines
来源：http://dali.cheryme.top/Article/details/gtdhvmbebp.html

C#:   s.Split('\n')
来源：http://dali.zhijiandao.cn/Article/details/gttoqrbmqx.html

[E20] 判断字符串是否为空
来源：http://dali.zycfv.cn/Article/details/gtyvxkcire.html

Py:   if not s:
来源：http://dali.hysaishi.cn/Article/details/gtbuiwwiml.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shuidangran.top/Article/details/gtvjjdwbqz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.sufxvd.cn/Article/details/gtoxjwqoay.html

TS:   if (s === "") {}
来源：http://dali.yvedp.cn/Article/details/gtnaaonkwt.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gtgwotzjyd.html

Go:   if s == "" {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfdfhkzz.html

Ruby: if s.empty?
来源：http://dali.jqgufenzy.top/Article/details/gtlfshfjoo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.tanke756.top/Article/details/gtjdwwxcrb.html

[E21] 超长截断加省略号
来源：http://dali.xylfe.cn/Article/details/gtxkfzfkdp.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yuxming.cn/Article/details/gttinkaigq.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtrvnjsiou.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhijiandao.cn/Article/details/gthlzbxsma.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ehwqpu.com/Article/details/gtsuyhfrzp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gzhubu.top/Article/details/gtzgqxlghb.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.tian-w.cn/Article/details/gtsbrfvjhk.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtygtfodgs.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gtuimuuudr.html

[E22] 字节长度与字符长度
来源：http://dali.yj202588.top/Article/details/gtajllmdlb.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.jqgfzy.top/Article/details/gttokgigmm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfjtpbxt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyykckjb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hnqzz.top/Article/details/gtswywzonq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yueranfly.top/Article/details/gtdwpsrphl.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shanyushiyangtech.top/Article/details/gtoebewdra.html

Ruby: s.bytesize;  s.length
来源：http://dali.yuanzhike.top/Article/details/gtoojvrbma.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.yonumen.top/Article/details/gtpnuehoxn.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtuwaekqtq.html

F. 文件与目录
来源：http://dali.vqdsnc.cn/Article/details/gtggtmdyhn.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtbsjkxqcb.html

[F01] 读取整个文件
来源：http://dali.kuanghao11.cn/Article/details/gtnzbjexpu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xziqi.cn/Article/details/gthwbyjhkm.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtwpqqdsho.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guannengcc.top/Article/details/gtyihtruej.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shuidangran.top/Article/details/gtopwbqbml.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.yonumen.top/Article/details/gtvbokmwsh.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.shzxlz.cn/Article/details/gtoepgrpjq.html

Ruby: File.read("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtzahmysba.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtotogqcug.html

[F02] 逐行读取文件
来源：http://dali.cucudq.cn/Article/details/gttjcydnte.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.vqdsnc.cn/Article/details/gtfwughnlp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gtypvetumg.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gttjhbsvzx.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtuolplefq.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sxryk.cn/Article/details/gtlvhnxyam.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.dianchejie.cn/Article/details/gtsggrcxkh.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.yangfankeji.com/Article/details/gtuifpuiwd.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.dianchejie.cn/Article/details/gtqqjvhehm.html

[F03] 写入文件（覆盖）
来源：http://dali.xylfe.cn/Article/details/gtpglchltb.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.andypj.xyz/Article/details/gtyyyqayxq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtkflpbfsq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gthcuczeoc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtltheeglu.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jianghu66.top/Article/details/gtxckvtlyo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xinyue.icu/Article/details/gtinlpdyqr.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxuanxn.top/Article/details/gtzbgsocgw.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtzdgayzgy.html

[F04] 追加写入文件
来源：http://dali.c1oappe.top/Article/details/gtfelwvizk.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.smart0.xyz/Article/details/gtuvtlwuad.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yueranfly.top/Article/details/gtgplxyvcb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xziqi.cn/Article/details/gtfrhbwpiy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfjfxcqr.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yvedp.cn/Article/details/gtiffhweqw.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.dashuyun.cn/Article/details/gtymlwtebu.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.chenjidiqi.icu/Article/details/gttkvithdw.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.zhixingplan.top/Article/details/gtfqvocyfm.html


<!-- 参考信息 -->