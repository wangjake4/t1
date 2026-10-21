代发 wailian999

C#:   list.Reverse();
来源：http://dali.c1oappe.top/Article/details/gtzicdopbe.html

[D12] 查找元素下标
来源：http://dali.zhiwuduotai.top/Article/details/gtkbnrpbxn.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258.top/Article/details/gtzhihkatc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.smart0.xyz/Article/details/gtuneqxjka.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtienrmbhu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtbpdmzrjs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guowangkeji.top/Article/details/gtskjxngwh.html

Go:   slices.Index(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtbjphuhot.html

Ruby: arr.index(x)
来源：http://dali.sysykeji.top/Article/details/gtjaydbnlz.html

C#:   list.IndexOf(x);
来源：http://dali.jiagoushi.top/Article/details/gtvtfepnku.html

[D13] 过滤（保留满足条件的）
来源：http://dali.aizwys.cn/Article/details/gtcnjayaid.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gtzqiiaqnk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aizwys.cn/Article/details/gtxurmhool.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gthzsoinkl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gtwgdsqpfh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gthcdsrnra.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ehwqpu.com/Article/details/gtssfhflii.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gtshenocss.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gttupflkyj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gtwtgaezjg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gtpynjvexj.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cheryme.top/Article/details/gthdsxlteh.html

JS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtedueeeln.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtsleiiyrm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.svipenyu.cn/Article/details/gtqusetxkm.html

Go:   // 手写循环
来源：http://dali.jinqigfzy.top/Article/details/gtdoamhngw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cashguo.top/Article/details/gtjgaeivip.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xziqi.cn/Article/details/gtluczvfgl.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gtbyniibmj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gthwythgpy.html

PHP:  array_unique($arr);
来源：http://dali.xinyue.icu/Article/details/gtesunmvmy.html

JS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxuwxiptm.html

TS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtepsqpdni.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yueranfly.top/Article/details/gtgltwakof.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gotoacloud.top/Article/details/gtirtjlkhi.html

Ruby: arr.uniq
来源：http://dali.wangdashe.top/Article/details/gththxmafm.html

C#:   list.Distinct().ToList()
来源：http://dali.shuidangran.top/Article/details/gtxevxnsyj.html

[D16] 求和与平均值
来源：http://dali.gotoacloud.top/Article/details/gtocwsgnkr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkoruenbg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ivvv.top/Article/details/gtscftkgrt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gtmtoyncza.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtnslrtgjm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.smart0.xyz/Article/details/gtyqnwbnkr.html

Go:   // 手写循环累加
来源：http://dali.hongshengwenyu.top/Article/details/gtqyyxtfuj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenlongwang.top/Article/details/gtclltkzsq.html

C#:   list.Sum();  list.Average()
来源：http://dali.sysykeji.top/Article/details/gtalnjyapt.html

[D17] 最大值与最小值
来源：http://dali.0kj1m.cn/Article/details/gtntlioatn.html

Py:   max(arr);  min(arr)
来源：http://dali.daxiang520.top/Article/details/gtgfagtkvg.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gtxgwiwzum.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtlvzwqigd.html

TS:   Math.max(...arr);
来源：http://dali.xuanzx.com/Article/details/gtljbpevpe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.tanke756.top/Article/details/gtkxazwrkm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj202588.top/Article/details/gtphughrfv.html

Ruby: arr.max;  arr.min
来源：http://dali.quarkkingdee.top/Article/details/gthoskljmt.html

C#:   list.Max();  list.Min()
来源：http://dali.quarkkingdee.top/Article/details/gthuwzocci.html

[D18] 扁平化嵌套数组
来源：http://dali.yuanzhike.top/Article/details/gttdlsbxga.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hammf.cn/Article/details/gtywtgfanj.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gthghndspq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.fengsongda.top/Article/details/gtjbqzuzih.html

TS:   nested.flat();
来源：http://dali.zhixingplan.top/Article/details/gtcaavjnek.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gttqxgmuka.html

Go:   // 手写双层循环
来源：http://dali.shzxlz.cn/Article/details/gtpvojvlpw.html

Ruby: nested.flatten
来源：http://dali.cheryme.top/Article/details/gtpyqzranp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtddrytien.html

[D19] 按字段分组
来源：http://dali.c1oappe.top/Article/details/gtkngkljuf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dashuyun.cn/Article/details/gtdmqobxyw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.vqdsnc.cn/Article/details/gtyeerijrw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gaohongyu789.top/Article/details/gtjfsyrxuk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gtswoumgsm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.guannengcc.top/Article/details/gtdojpdyrr.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gtlrfhvtht.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gzhubu.top/Article/details/gtsajarckv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gaohongyu789.top/Article/details/gtvgnouryq.html

[D20] 统计每个元素出现次数
来源：http://dali.shuidangran.top/Article/details/gtkpmruovi.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtlvgnfjpg.html

PHP:  array_count_values($arr);
来源：http://dali.shzxlz.cn/Article/details/gtpbyjehsy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gteqjnfnwe.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gtwdjjqiwc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ybcxt.top/Article/details/gttolytgzu.html

Go:   // 手写 map[T]int
来源：http://dali.gzhubu.top/Article/details/gtxifkfhbc.html

Ruby: arr.tally
来源：http://dali.mhx1999.top/Article/details/gtlfraohhm.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnsqxawm.html

[D21] 判断是否包含某元素
来源：http://dali.meibo888.top/Article/details/gtimfajjug.html

Py:   x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gthtolcagr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinqigfzy.top/Article/details/gthploxmvu.html

JS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gtovvazbmx.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteopswsji.html

Java: list.contains(x)
来源：http://dali.316326.xyz/Article/details/gtlkpliyub.html

Go:   slices.Contains(arr, x)
来源：http://dali.tianlin.xyz/Article/details/gtvzpcxymy.html

Ruby: arr.include?(x)
来源：http://dali.redwolf501.top/Article/details/gteclzidrz.html

C#:   list.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtrehrwhuf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xinyue.icu/Article/details/gtukfdypqp.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtxvkuhror.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tian-w.cn/Article/details/gtfziefsxs.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.mhx1999.top/Article/details/gtyqppunmj.html

TS:   [...arr];
来源：http://dali.quarkkingdee.top/Article/details/gtobmttrla.html

Java: new ArrayList<>(list);
来源：http://dali.fengsongda.top/Article/details/gtkmimwkef.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gtgfsqlvio.html

Ruby: arr.dup;  arr.clone
来源：http://dali.zdqjudy.top/Article/details/gtbvfwqlkc.html

C#:   new List<int>(list);
来源：http://dali.meibo888.top/Article/details/gtcwxzsnkk.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gtdiabelod.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.xuanzx.com/Article/details/gtekcusbpr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.mhx1999.top/Article/details/gtqldkdkdk.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkdurtdc.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtvggddcov.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yanxiufei.cn/Article/details/gtnnbjggjh.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gtxpguwykr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.guowangkeji.top/Article/details/gtegsovznd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aibaodan.cn/Article/details/gtaounxatj.html

[D24] 字典 / Map 基本操作
来源：http://dali.tian-w.cn/Article/details/gtjhfqvqjz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yonumen.top/Article/details/gtwhvpkgvn.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yongpay.top/Article/details/gtsnpajqhc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.smart0.xyz/Article/details/gtadhlazzm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ivvv.top/Article/details/gtmxmhpesq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.xinyue.icu/Article/details/gtxfwrocii.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.guannengcc.top/Article/details/gtwcdmulpe.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbkwxwwt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yonumen.top/Article/details/gtwjxuslik.html

[D25] Set 集合去重与交并差
来源：http://dali.ydzc1.top/Article/details/gtpkemeihu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jiagoushi.top/Article/details/gtdjyrsbsl.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.zhoulong.xyz/Article/details/gtkazipsis.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.havefunace.top/Article/details/gttdlxyifu.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sweek.top/Article/details/gtadmpnqii.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhiwuduotai.top/Article/details/gtmfhgatac.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.havefunace.top/Article/details/gtyaiycphx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhoulong.xyz/Article/details/gtzbykcrts.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.daria6918.cn/Article/details/gtfepetqql.html

[D26] 数组转字符串
来源：http://dali.nanxuanxn.top/Article/details/gtnlsodcid.html

Py:   ", ".join(map(str, arr))
来源：http://dali.aizwys.cn/Article/details/gtifmrujfp.html

PHP:  implode(", ", $arr);
来源：http://dali.ybcxt.top/Article/details/gtqgbuufpl.html

JS:   arr.join(", ")
来源：http://dali.yanxiufei.cn/Article/details/gtqmbrjinl.html

TS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtyxfhuhdx.html

Java: String.join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtjwoyofpp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhongyouzk.top/Article/details/gtpknbfpxt.html

Ruby: arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtovqtyfln.html

C#:   string.Join(", ", list)
来源：http://dali.snrcjt.cn/Article/details/gtqwkcrcbr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtyvatxgyg.html

E. 字符串处理
来源：http://dali.ydzc1.top/Article/details/gtwxbkjzem.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gttwmgwrfg.html

[E01] 拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtjmiqlftd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.iojbl.cn/Article/details/gtrbsyfkyq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.tian-w.cn/Article/details/gtzxnjjslo.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gtbdiptixs.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtojdzltyu.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hnqzz.top/Article/details/gtojidxkgv.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zdqjudy.top/Article/details/gtiplrsgtl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.tian-w.cn/Article/details/gtcnwxzhzp.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtrbrbyjdt.html

[E02] 重复字符串
来源：http://dali.hfpthk.cn/Article/details/gtdwglqipy.html

Py:   "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gtqmvbeldt.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinqigfzy.top/Article/details/gtohhkcqvs.html

JS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtxeftgrfh.html

TS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gthyvotkhu.html

Java: "ab".repeat(3)
来源：http://dali.ydzc1.top/Article/details/gtivpmjsbd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasnhessz.html

Ruby: "ab" * 3
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdkyhenk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yvedp.cn/Article/details/gtuegpgskm.html

[E03] 截取子串
来源：http://dali.yj202588.top/Article/details/gtfxjinkmg.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gtfgrqmmvb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yvedp.cn/Article/details/gtwfcceffj.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxvsovis.html

TS:   s.slice(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtyzbssxsj.html

Java: s.substring(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtcczobyjg.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jqgfzy.top/Article/details/gtsnkclmtn.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.aibaodan.cn/Article/details/gtrdyhcovm.html

C#:   s.Substring(1, 3)
来源：http://dali.yuxming.cn/Article/details/gtysajznvc.html

[E04] 查找子串位置
来源：http://dali.yonumen.top/Article/details/gtshrjhazq.html

Py:   s.find("x");  s.index("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtvohzxrnr.html

PHP:  strpos($s, "x");
来源：http://dali.jyoumei.cn/Article/details/gtzwxkucnw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dianchejie.cn/Article/details/gtkwwqivpq.html

TS:   s.indexOf("x")
来源：http://dali.yj20258888.top/Article/details/gtdegltvkl.html

Java: s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gtkymnzdji.html

Go:   strings.Index(s, "x")
来源：http://dali.zhoulong.xyz/Article/details/gtzxqqhvfk.html

Ruby: s.index("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtphikwdqh.html

C#:   s.IndexOf("x")
来源：http://dali.cashguo.top/Article/details/gtvpyjychy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jlsjyb.cn/Article/details/gtefqttxnx.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yanxiufei.cn/Article/details/gtqwyhzecf.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.havefunace.top/Article/details/gthmcbibxq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258.top/Article/details/gtpeccujfj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenjidiqi.icu/Article/details/gtauacklly.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.havefunace.top/Article/details/gtsoksrpuw.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.cucudq.cn/Article/details/gtbyzxmgod.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.mhx1999.top/Article/details/gtixdealhs.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.hfpthk.cn/Article/details/gtewkjvzok.html

[E06] 替换子串
来源：http://dali.cashguo.top/Article/details/gtpndcefxy.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtnsuwmgly.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.aibaodan.cn/Article/details/gtlhabagbt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtdwrtevga.html

TS:   s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gttidaiisw.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtumkwdsyi.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hnxiangtu.top/Article/details/gtnuruyirq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtjtvplyyx.html

C#:   s.Replace("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtuuupgaxj.html

[E07] 按分隔符拆分
来源：http://dali.dashuyun.cn/Article/details/gthavhqaoa.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.andypj.xyz/Article/details/gtzjnsfshy.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhengqikj.top/Article/details/gtluibvqof.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.yueranfly.top/Article/details/gtucpwtprr.html

TS:   s.split(",")
来源：http://dali.gotoacloud.top/Article/details/gtkmwwnqth.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.ppjwa.cn/Article/details/gtpwdwzgzk.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.svipenyu.cn/Article/details/gtobbltagx.html

Ruby: s.split(",");  s.split
来源：http://dali.zhixingplan.top/Article/details/gtosnoammx.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.snrcjt.cn/Article/details/gtynylgcvx.html

[E08] 数组按分隔符合并
来源：http://dali.cdnleiting.top/Article/details/gtvlsgjfxf.html

Py:   ",".join(items)
来源：http://dali.zhengqikj.top/Article/details/gtklpjhlhy.html

PHP:  implode(",", $items);
来源：http://dali.guannengcc.top/Article/details/gtdcjgeifx.html

JS:   items.join(",")
来源：http://dali.yj202588.top/Article/details/gtrkwzaglz.html

TS:   items.join(",")
来源：http://dali.cdnleiting.top/Article/details/gtkdzlflki.html

Java: String.join(",", items)
来源：http://dali.havefunace.top/Article/details/gtmipyxhvj.html

Go:   strings.Join(items, ",")
来源：http://dali.ppjwa.cn/Article/details/gtfsivnszd.html

Ruby: items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gthnuallqj.html

C#:   string.Join(",", items)
来源：http://dali.dashuyun.cn/Article/details/gtraffjubb.html

[E09] 去除所有空白字符
来源：http://dali.daria6918.cn/Article/details/gtjmrpfppo.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.redwolf501.top/Article/details/gtcvwkekch.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jiagoushi.top/Article/details/gtfjmuipju.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.gogol.net.cn/Article/details/gtwnhkcjlo.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.birdmap.top/Article/details/gtwxihlgwu.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.jyoumei.cn/Article/details/gtshkopimw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenzaomai.com/Article/details/gtjnuigdwg.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cheryme.top/Article/details/gtdkczkdbn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.fzhhl.top/Article/details/gtgwhxtnez.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hammf.cn/Article/details/gtshvawjpe.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.andypj.xyz/Article/details/gtjvxghnfh.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.gotoacloud.top/Article/details/gtknvazdqn.html

JS:   "7".padStart(3, "0")
来源：http://dali.fengsongda.top/Article/details/gtsisravct.html

TS:   "7".padStart(3, "0")
来源：http://dali.dianchejie.cn/Article/details/gtdytjvcxz.html

Java: String.format("%03d", 7)
来源：http://dali.smart0.xyz/Article/details/gtbpqtsngw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtfoaqrach.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sxryk.cn/Article/details/gtptwabzqs.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.shzxlz.cn/Article/details/gtxvwhtmlp.html

[E11] 反转字符串
来源：http://dali.gogol.net.cn/Article/details/gtrhweaadw.html

Py:   s[::-1]
来源：http://dali.shzxlz.cn/Article/details/gtwoegsvtl.html

PHP:  strrev($s);
来源：http://dali.hfpthk.cn/Article/details/gtwysllgiw.html

JS:   [...s].reverse().join("")
来源：http://dali.jqgfzy.top/Article/details/gtaxzhqhdg.html

TS:   [...s].reverse().join("")
来源：http://dali.wangdashe.top/Article/details/gtcltbkupt.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.hfpthk.cn/Article/details/gtwgcrbgqx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.iojbl.cn/Article/details/gtxcjudepw.html

Ruby: s.reverse
来源：http://dali.guannengcc.top/Article/details/gtyqwyijhp.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhengqikj.top/Article/details/gtgooqmhuk.html

[E12] 统计某字符出现次数
来源：http://dali.zycfv.cn/Article/details/gtjtcgkjuw.html

Py:   s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtjltoshyi.html

PHP:  substr_count($s, "a");
来源：http://dali.yj202588.top/Article/details/gtqmgxfwkl.html

JS:   s.split("a").length - 1
来源：http://dali.sxryk.cn/Article/details/gtvvpzyhye.html

TS:   s.split("a").length - 1
来源：http://dali.jqgufenzy.top/Article/details/gtvowaovcd.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.chenlongwang.top/Article/details/gtcahqwdzo.html

Go:   strings.Count(s, "a")
来源：http://dali.316326.xyz/Article/details/gtkqkqhnqr.html

Ruby: s.count("a")
来源：http://dali.daxiang520.top/Article/details/gtkmnhivxt.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gotoacloud.top/Article/details/gtbxychbzj.html

[E13] 逐字符遍历
来源：http://dali.havefunace.top/Article/details/gtofqzujem.html

Py:   for ch in s: print(ch)
来源：http://dali.cheryme.top/Article/details/gtipdmbruo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.aizwys.cn/Article/details/gtpjihzpco.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.guannengcc.top/Article/details/gtjgiitrvl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xziqi.cn/Article/details/gtzeodirlr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.birdmap.top/Article/details/gtdasgspcm.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yonumen.top/Article/details/gtoglwkafh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.316326.xyz/Article/details/gtlcyvxqrf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.bjfxy.top/Article/details/gtrtqzihas.html

[E14] URL 编码与 Base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgurokncq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.guowangkeji.top/Article/details/gtgwzrgeuz.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.meibo888.top/Article/details/gtzogoqivv.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.chenjidiqi.icu/Article/details/gtqrajqklv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.0kj1m.cn/Article/details/gtezfdbwli.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.cqqwz.cn/Article/details/gtgzhjurgm.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.yueranfly.top/Article/details/gtuvpciydd.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jiagoushi.top/Article/details/gtecickhtr.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jiagoushi.top/Article/details/gtbeptburg.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnpdxfrtg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxyaixwu.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cqqwz.cn/Article/details/gtuaugojzo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.daria6918.cn/Article/details/gtuwrgozpx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.sxryk.cn/Article/details/gtrlyknwjd.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gtlbwihprj.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.birdmap.top/Article/details/gtussxcbyl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.xylfe.cn/Article/details/gtigpngiyh.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.guannengcc.top/Article/details/gtpggvfnol.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtymjqjvqu.html

Py:   f"{1234567:,}"
来源：http://dali.sweek.top/Article/details/gtuqcersiw.html

PHP:  number_format(1234567);
来源：http://dali.fzhhl.top/Article/details/gteqsaxxtt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.andypj.xyz/Article/details/gtnyoolbml.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhengqikj.top/Article/details/gtxkseqald.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.chenjidiqi.icu/Article/details/gtjlkbiuca.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jiagoushi.top/Article/details/gtwihkoifz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gtxojqvxdf.html

C#:   1234567.ToString("N0")
来源：http://dali.jyoumei.cn/Article/details/gtsfnibjrj.html

[E17] 首字母大写
来源：http://dali.ehwqpu.com/Article/details/gtmhegyttx.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jianghu66.top/Article/details/gtxhfctkuk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.hywenlv.cn/Article/details/gtbynozgta.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhongyouzk.top/Article/details/gtkhffbhkz.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtqfiyvzdu.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zycfv.cn/Article/details/gtwpfcitgk.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaoygsvks.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcwzpfhn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.snrcjt.cn/Article/details/gtmkuggxqi.html

[E18] 模板占位符替换
来源：http://dali.redwolf501.top/Article/details/gtxqsttroy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangdashe.top/Article/details/gtfteiahzw.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhijiandao.cn/Article/details/gtqtaddwgg.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxebksbf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.zhongyouzk.top/Article/details/gtadurgfxu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gttbyiscgn.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yuanzhike.top/Article/details/gtjfutlrhz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shuidangran.top/Article/details/gtyubicuqt.html


<!-- 参考信息 -->