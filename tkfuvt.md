代发 wailian999

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gtoczrofxq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gogol.net.cn/Article/details/gtxehkdwle.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gtnjxggolc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ehwqpu.com/Article/details/gtdsqshrkf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigufen.top/Article/details/gtgjnrjtxt.html

[D20] 统计每个元素出现次数
来源：http://dali.jianghu66.top/Article/details/gtqlfewcdc.html

Py:   Counter(arr)
来源：http://dali.daria6918.cn/Article/details/gtlcnxpobf.html

PHP:  array_count_values($arr);
来源：http://dali.hysaishi.cn/Article/details/gtkvybzklm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtgvkwfopl.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtymlwkbmn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gtevulkore.html

Go:   // 手写 map[T]int
来源：http://dali.hnxiangtu.top/Article/details/gtcvwhdpmy.html

Ruby: arr.tally
来源：http://dali.sweek.top/Article/details/gtdfseozya.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ydzc1.top/Article/details/gtxqyxwqwx.html

[D21] 判断是否包含某元素
来源：http://dali.yangfankeji.com/Article/details/gtizvhnjlh.html

Py:   x in arr
来源：http://dali.xinyue.icu/Article/details/gtithdopyp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shzxlz.cn/Article/details/gtflqbngiu.html

JS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gtqpfzxixz.html

TS:   arr.includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwlkbbuz.html

Java: list.contains(x)
来源：http://dali.yuxming.cn/Article/details/gtnhkhshwa.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gttcmmviqs.html

Ruby: arr.include?(x)
来源：http://dali.chenlongwang.top/Article/details/gtqvhwifmq.html

C#:   list.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gteacmvxtj.html

[D22] 复制数组（避免共享引用）
来源：http://dali.havefunace.top/Article/details/gtkooqeidx.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgyenbclc.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hongshengwenyu.top/Article/details/gtrbdvhxcp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hfpthk.cn/Article/details/gtvdcrcrda.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gtcvwhppix.html

Java: new ArrayList<>(list);
来源：http://dali.zhengqikj.top/Article/details/gtdemsiabe.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yuxming.cn/Article/details/gtaycmcuqt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gtkyzpddrt.html

C#:   new List<int>(list);
来源：http://dali.havefunace.top/Article/details/gtcfjrhzrg.html

[D23] reduce 累积计算
来源：http://dali.hnxiangtu.top/Article/details/gtzbqempdp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtiqkuwvut.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jinqigufen.top/Article/details/gtyxotlutt.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gthsbuvhmb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgghtozxe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuanzhike.top/Article/details/gtynfltbsb.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gttfgbmtqn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.redwolf501.top/Article/details/gtljlpnptn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gtesvywftc.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258.top/Article/details/gtdrtvbwha.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.hywenlv.cn/Article/details/gtcxyuhalf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xinyue.icu/Article/details/gtohbalkld.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.cheryme.top/Article/details/gtacofnykk.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtpfbhdhrh.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhixingplan.top/Article/details/gtzahqlrot.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangdashe.top/Article/details/gtumlrhhku.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yuxming.cn/Article/details/gtwwaehjnr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jyoumei.cn/Article/details/gtsfuyegcg.html

[D25] Set 集合去重与交并差
来源：http://dali.jinghuilouyu.cn/Article/details/gtyabdkxdt.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guannengcc.top/Article/details/gtkbengqkg.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.cucudq.cn/Article/details/gtphdtdjxv.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.daxiang520.top/Article/details/gtekvvzrcb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jqgufenzy.top/Article/details/gtqlkqjoto.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gtczetkvoz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aibaodan.cn/Article/details/gtjaqnlcyy.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nanxuanxn.top/Article/details/gtlvdqtwfs.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.xuanzx.com/Article/details/gtkufxqizh.html

[D26] 数组转字符串
来源：http://dali.c1oappe.top/Article/details/gtitwlfjeb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gttnmnytun.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtrlkbfpej.html

JS:   arr.join(", ")
来源：http://dali.yuxming.cn/Article/details/gtcioudasa.html

TS:   arr.join(", ")
来源：http://dali.gogol.net.cn/Article/details/gtvovjlmmx.html

Java: String.join(", ", list)
来源：http://dali.chenzaomai.com/Article/details/gtyykhkhoa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtuydyebpg.html

Ruby: arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gtuombnnpy.html

C#:   string.Join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gtvlpuxmlm.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtunboomyb.html

E. 字符串处理
来源：http://dali.kuanghao11.cn/Article/details/gtbwmyetsh.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphgyherh.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtuoglyaev.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.iojbl.cn/Article/details/gtdlkuvusa.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.chenzaomai.com/Article/details/gtfqsguvkc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xylfe.cn/Article/details/gtbyezvdjw.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guannengcc.top/Article/details/gtlfqqgeri.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwwmfhbfw.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hnxiangtu.top/Article/details/gtsqswfvcm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.sufxvd.cn/Article/details/gtdczbjeyi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtmgrqvnma.html

[E02] 重复字符串
来源：http://dali.9152youxi.cn/Article/details/gtilvhynaj.html

Py:   "ab" * 3
来源：http://dali.cdnleiting.top/Article/details/gtalhagtpz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.sweek.top/Article/details/gtepdfwbqv.html

JS:   "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gtpddfzkel.html

TS:   "ab".repeat(3)
来源：http://dali.yanxiufei.cn/Article/details/gtjobedpyk.html

Java: "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtlxhclkgt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigfzy.top/Article/details/gtyosyyjyo.html

Ruby: "ab" * 3
来源：http://dali.daxiang520.top/Article/details/gtvzehyrab.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdjhcifs.html

[E03] 截取子串
来源：http://dali.zhiwuduotai.top/Article/details/gtrygqwebh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aizwys.cn/Article/details/gtcardqfxm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.9152youxi.cn/Article/details/gtigdsiupb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtnuynpwas.html

TS:   s.slice(1, 4)
来源：http://dali.gotoacloud.top/Article/details/gtmcpgvlzo.html

Java: s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpmvufkzv.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ybcxt.top/Article/details/gtkyiczfur.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhijiandao.cn/Article/details/gtjtdjpglk.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gtiaobphnq.html

[E04] 查找子串位置
来源：http://dali.sxryk.cn/Article/details/gtvwbbbrkb.html

Py:   s.find("x");  s.index("x")
来源：http://dali.iojbl.cn/Article/details/gtvnshbbrj.html

PHP:  strpos($s, "x");
来源：http://dali.birdmap.top/Article/details/gtidlejjyg.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258888.top/Article/details/gtainlqbnp.html

TS:   s.indexOf("x")
来源：http://dali.hammf.cn/Article/details/gttcntpjrf.html

Java: s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gtaanuznjj.html

Go:   strings.Index(s, "x")
来源：http://dali.xylfe.cn/Article/details/gtognxdnpt.html

Ruby: s.index("x")
来源：http://dali.gzhubu.top/Article/details/gtuwintdrg.html

C#:   s.IndexOf("x")
来源：http://dali.daxiang520.top/Article/details/gtolohwjej.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.meibo888.top/Article/details/gtxjqetocc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.nanxinkj.top/Article/details/gtjkwttkci.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ybcxt.top/Article/details/gtsqmghzxb.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sxryk.cn/Article/details/gtpmlmjupc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gaohongyu789.top/Article/details/gtlovxazpo.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.chenjidiqi.icu/Article/details/gtjzvqnjcj.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.jyoumei.cn/Article/details/gtozblgrnp.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.aizwys.cn/Article/details/gtswtkofet.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwncigwz.html

[E06] 替换子串
来源：http://dali.zycfv.cn/Article/details/gtbzcxxmka.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.snrcjt.cn/Article/details/gtufssxjiz.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.hfpthk.cn/Article/details/gtcmjlslcb.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.fzhhl.top/Article/details/gtqnczhfwf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrmmvyyre.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.hywenlv.cn/Article/details/gtitdksjgl.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.mhx1999.top/Article/details/gtrjtobixc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtclvzkbwa.html

C#:   s.Replace("a", "b")
来源：http://dali.hnqzz.top/Article/details/gtzeljpqel.html

[E07] 按分隔符拆分
来源：http://dali.nanxuanxn.top/Article/details/gtuatmgvya.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.nanxinkj.top/Article/details/gtoegjbvzo.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtioaregda.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cheryme.top/Article/details/gtgjzyyram.html

TS:   s.split(",")
来源：http://dali.yueranfly.top/Article/details/gtbvlwazdq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.hnqzz.top/Article/details/gtnxqjhqfc.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtavgammar.html

Ruby: s.split(",");  s.split
来源：http://dali.yvedp.cn/Article/details/gtpftajyzv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.ehwqpu.com/Article/details/gtfihyfips.html

[E08] 数组按分隔符合并
来源：http://dali.birdmap.top/Article/details/gttxahyikm.html

Py:   ",".join(items)
来源：http://dali.chenlongwang.top/Article/details/gtrijkpnir.html

PHP:  implode(",", $items);
来源：http://dali.chenjidiqi.icu/Article/details/gtxvuvadir.html

JS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtqzdbuxmk.html

TS:   items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtoyqoybda.html

Java: String.join(",", items)
来源：http://dali.hammf.cn/Article/details/gthxjqswst.html

Go:   strings.Join(items, ",")
来源：http://dali.yj20258888.top/Article/details/gtapgjfxbg.html

Ruby: items.join(",")
来源：http://dali.aizwys.cn/Article/details/gtmhesdfwx.html

C#:   string.Join(",", items)
来源：http://dali.cheryme.top/Article/details/gtsspegrnm.html

[E09] 去除所有空白字符
来源：http://dali.jqgfzy.top/Article/details/gtqtthaqrj.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.gaohongyu789.top/Article/details/gtaxhloqlo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.bjfxy.top/Article/details/gtumnegczs.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.nanxinkj.top/Article/details/gtxugvrddv.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.havefunace.top/Article/details/gtujiujaxy.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.nanxinkj.top/Article/details/gtujeyriln.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.bjfxy.top/Article/details/gthulhcwgc.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgfzy.top/Article/details/gtjlgngcpc.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hongshengwenyu.top/Article/details/gturrtfrnz.html

[E10] 左侧补零 / 定长填充
来源：http://dali.feifeiyinyue.top/Article/details/gtwtrbqemu.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aibaodan.cn/Article/details/gtiuwzznsl.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.hysaishi.cn/Article/details/gtspzznsgg.html

JS:   "7".padStart(3, "0")
来源：http://dali.jqgfzy.top/Article/details/gtefairfap.html

TS:   "7".padStart(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtaqmsvvpa.html

Java: String.format("%03d", 7)
来源：http://dali.ivvv.top/Article/details/gtrcijtfwx.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yongpay.top/Article/details/gtwakgsxdp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.yvedp.cn/Article/details/gtwrtqzhae.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hongshengwenyu.top/Article/details/gtkrdmjgqh.html

[E11] 反转字符串
来源：http://dali.yongpay.top/Article/details/gtsspkcmak.html

Py:   s[::-1]
来源：http://dali.cashguo.top/Article/details/gtsqygvfgb.html

PHP:  strrev($s);
来源：http://dali.tanke756.top/Article/details/gthlkdjskj.html

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtbpmhpwbn.html

TS:   [...s].reverse().join("")
来源：http://dali.zhongyouzk.top/Article/details/gtudwtzsxq.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tian-w.cn/Article/details/gtvdemmyzm.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gttnhubsts.html

Ruby: s.reverse
来源：http://dali.guowangkeji.top/Article/details/gtkxvbmnpo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yuanzhike.top/Article/details/gtmeecayws.html

[E12] 统计某字符出现次数
来源：http://dali.cqqwz.cn/Article/details/gtmvdxeznj.html

Py:   s.count("a")
来源：http://dali.cqqwz.cn/Article/details/gtoyptftlr.html

PHP:  substr_count($s, "a");
来源：http://dali.dianchejie.cn/Article/details/gtxfxenabn.html

JS:   s.split("a").length - 1
来源：http://dali.snrcjt.cn/Article/details/gtuxdnkezd.html

TS:   s.split("a").length - 1
来源：http://dali.hysaishi.cn/Article/details/gtwduudxct.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.aibaodan.cn/Article/details/gtrmowyuxu.html

Go:   strings.Count(s, "a")
来源：http://dali.hongshengwenyu.top/Article/details/gtxkipcfnw.html

Ruby: s.count("a")
来源：http://dali.tanke756.top/Article/details/gtchvkilry.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yvedp.cn/Article/details/gtmrcjarcz.html

[E13] 逐字符遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtvizglopp.html

Py:   for ch in s: print(ch)
来源：http://dali.xuanzx.com/Article/details/gtokjjivce.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nwbrower.top/Article/details/gtgloslsfk.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuanzx.com/Article/details/gtzcrvvbih.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.daxiang520.top/Article/details/gtkqbefsab.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gtlxfnohtm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.bjfxy.top/Article/details/gtmssbzqfn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.gotoacloud.top/Article/details/gtqbcffjfo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gtaruqnoba.html

[E14] URL 编码与 Base64
来源：http://dali.nanxuanxn.top/Article/details/gtayrvxxhl.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guowangkeji.top/Article/details/gtsnftcnso.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nwbrower.top/Article/details/gtyqmxmhfc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yvedp.cn/Article/details/gtdgsrynhx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dashuyun.cn/Article/details/gtlvahpase.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sysykeji.top/Article/details/gtydfjhoya.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.nanxuanxn.top/Article/details/gtcnddjlqe.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gotoacloud.top/Article/details/gtdtzffrfr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.hysaishi.cn/Article/details/gtxjlfsqqk.html

[E15] HTML 转义 / 反转义
来源：http://dali.tianlin.xyz/Article/details/gtwknuoque.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.chenlongwang.top/Article/details/gtqamlzwqm.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.0kj1m.cn/Article/details/gtpumethmx.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtyjzvyboq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gttnbyrxqx.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.tanke756.top/Article/details/gtulnxcyag.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yj20258.top/Article/details/gthcfsdfdt.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gteatmhbfv.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.smart0.xyz/Article/details/gtfydgwqzm.html

[E16] 数字千分位
来源：http://dali.guowangkeji.top/Article/details/gtdaixphza.html

Py:   f"{1234567:,}"
来源：http://dali.mhx1999.top/Article/details/gtjmgdhqpa.html

PHP:  number_format(1234567);
来源：http://dali.zhixingplan.top/Article/details/gtwzzfdbfb.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gtzueaedjg.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.pengpengdd.cyou/Article/details/gteqdnyxlh.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gttpphitxr.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.cucudq.cn/Article/details/gtypbikwkn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.meibo888.top/Article/details/gtmghzbitg.html

C#:   1234567.ToString("N0")
来源：http://dali.fengsongda.top/Article/details/gtjnmvfovx.html

[E17] 首字母大写
来源：http://dali.sufxvd.cn/Article/details/gtosjvyahu.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.xuetiantiany.cn/Article/details/gtygplegya.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtvgpjhaur.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gtuwpwpkrl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtncaigpwf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gogol.net.cn/Article/details/gtxxlucgws.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shzxlz.cn/Article/details/gteegoonxx.html

Ruby: s.capitalize
来源：http://dali.wangdashe.top/Article/details/gtzpibegrf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.daria6918.cn/Article/details/gtsiazprgk.html

[E18] 模板占位符替换
来源：http://dali.daxiang520.top/Article/details/gtswxuunlz.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jianghu66.top/Article/details/gtprcmoklk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.tianlin.xyz/Article/details/gtwphoovvz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.feifeiyinyue.top/Article/details/gtvmtpapvk.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.xuanzx.com/Article/details/gtxfewmpzy.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.chenlongwang.top/Article/details/gtkaymbubh.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yj202588.top/Article/details/gtylnsdimq.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.svipenyu.cn/Article/details/gtdxstqjhu.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticdonfkc.html

[E19] 多行文本按行拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtysuyqjxv.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gtlwzcxjyu.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yanxiufei.cn/Article/details/gttmzbbejb.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhiwuduotai.top/Article/details/gtepntfvui.html

TS:   s.split(/\r?\n/)
来源：http://dali.yongpay.top/Article/details/gtnihdyejn.html

Java: s.lines().toList()
来源：http://dali.9152youxi.cn/Article/details/gtazhibaku.html

Go:   strings.Split(s, "\n")
来源：http://dali.jinqigfzy.top/Article/details/gtokhyrooh.html

Ruby: s.lines
来源：http://dali.yueranfly.top/Article/details/gtdxwinmzl.html

C#:   s.Split('\n')
来源：http://dali.jqgfzy.top/Article/details/gttxxjukbi.html

[E20] 判断字符串是否为空
来源：http://dali.chenzaomai.com/Article/details/gtyulznweg.html

Py:   if not s:
来源：http://dali.wangshuangyany.cn/Article/details/gtgffazpme.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.yanxiufei.cn/Article/details/gtahvbqdty.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.nwbrower.top/Article/details/gtbdserbhi.html

TS:   if (s === "") {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujipovuh.html

Java: if (s.isEmpty()) {}
来源：http://dali.daxiang520.top/Article/details/gtunmiuwps.html

Go:   if s == "" {}
来源：http://dali.zhijiandao.cn/Article/details/gtjdcwxwft.html

Ruby: if s.empty?
来源：http://dali.cheryme.top/Article/details/gtpqtvoqqf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuiqfvli.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gtngvkmmve.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gaohongyu789.top/Article/details/gtpsighsac.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gtjgorwwig.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.fzhhl.top/Article/details/gtabwsbprc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gtdgacvkaz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jinqigfzy.top/Article/details/gtonfxqrlt.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.jqgufenzy.top/Article/details/gtsmuvqkcx.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtssqgzpne.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xylfe.cn/Article/details/gtiovqshre.html

[E22] 字节长度与字符长度
来源：http://dali.sysykeji.top/Article/details/gtyaouvhrx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.fengsongda.top/Article/details/gtjskyazkd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.shzxlz.cn/Article/details/gtyrhihhjm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.iojbl.cn/Article/details/gtvdkbntrb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gthjrajkxs.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.hysaishi.cn/Article/details/gtjjjutwcj.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.jinqigufen.top/Article/details/gtprsnutcv.html

Ruby: s.bytesize;  s.length
来源：http://dali.tian-w.cn/Article/details/gtjvoqzska.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jiagoushi.top/Article/details/gthmzchiwm.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtkwoyvpnf.html

F. 文件与目录
来源：http://dali.ppjwa.cn/Article/details/gtmaxcidvr.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gthoecnvhm.html

[F01] 读取整个文件
来源：http://dali.feifeiyinyue.top/Article/details/gtqulxdpnd.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.nanxinkj.top/Article/details/gtbrsjjwmx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtzhtkdvqc.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yuanzhike.top/Article/details/gtwkzfkyum.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdizohzm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.cheryme.top/Article/details/gtchqrifyb.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gtkfovehgv.html

Ruby: File.read("a.txt")
来源：http://dali.aizwys.cn/Article/details/gtbtwmndlx.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.ydzc1.top/Article/details/gtxfylygzw.html

[F02] 逐行读取文件
来源：http://dali.c1oappe.top/Article/details/gtwanxgbut.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jianghu66.top/Article/details/gtnjuasnbi.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.kuanghao11.cn/Article/details/gtrxcqkntn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nanxinkj.top/Article/details/gttixbisqp.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenjidiqi.icu/Article/details/gthbljixls.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yueranfly.top/Article/details/gtdpmtufrl.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.haohaochexian.top/Article/details/gtteuyuslu.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.xinyue.icu/Article/details/gtwzfukowm.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.yj20258888.top/Article/details/gthocsrgck.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gtxwemgchm.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hysaishi.cn/Article/details/gtacrmgiht.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigufen.top/Article/details/gtongdosgb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gogol.net.cn/Article/details/gtzymcmptu.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gtqlwvmphz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yuxming.cn/Article/details/gtujrucmoo.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jiagoushi.top/Article/details/gteaoljets.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.cqqwz.cn/Article/details/gtjtvnjkey.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtqtdhfuup.html

[F04] 追加写入文件
来源：http://dali.zycfv.cn/Article/details/gtjhvnogkz.html


<!-- 参考信息 -->