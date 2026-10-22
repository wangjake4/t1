代发 wailian999

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenzaomai.com/Article/details/gtnqxkbdbp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.havefunace.top/Article/details/gttnnhohno.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tanke756.top/Article/details/gtwlwdvlwl.html

Go:   slices.Index(arr, x)
来源：http://dali.cashguo.top/Article/details/gtlrzfdmox.html

Ruby: arr.index(x)
来源：http://dali.yuanzhike.top/Article/details/gttvnyotby.html

C#:   list.IndexOf(x);
来源：http://dali.feifeiyinyue.top/Article/details/gtkpnnnwta.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigfzy.top/Article/details/gtrunhnhpm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnqzz.top/Article/details/gtlhbybgac.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangdashe.top/Article/details/gtwgctuufh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gtwotmoxij.html

TS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gtyjqcvphp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtlklkdcnp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangdashe.top/Article/details/gtkaqltjlv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.feifeiyinyue.top/Article/details/gtdjfbgkug.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtdnhescvx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigufen.top/Article/details/gtdlwgsjgb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtvunlajcg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zycfv.cn/Article/details/gtgqrliplh.html

JS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gttltohyym.html

TS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gtnuedsnwq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dianchejie.cn/Article/details/gtbfzjacgr.html

Go:   // 手写循环
来源：http://dali.xylfe.cn/Article/details/gtphdeupke.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtlfimdjtn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hammf.cn/Article/details/gtqikqrclq.html

[D15] 去重
来源：http://dali.hfpthk.cn/Article/details/gtejespjwx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gtgaydvemf.html

PHP:  array_unique($arr);
来源：http://dali.pycfn.com/Article/details/gtzvgxzvkj.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gtgsoeugrd.html

TS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtsvserjpy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258888.top/Article/details/gtnlhafkwy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogfbhdoz.html

Ruby: arr.uniq
来源：http://dali.guowangkeji.top/Article/details/gtdlbvfqsi.html

C#:   list.Distinct().ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkbkyxkp.html

[D16] 求和与平均值
来源：http://dali.yj20258888.top/Article/details/gtugzlvref.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangdashe.top/Article/details/gtqsqrsnoh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtaataswxa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gtpecxbpid.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gtewbarfud.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqlpznfxj.html

Go:   // 手写循环累加
来源：http://dali.zhengqikj.top/Article/details/gtrdrrmdki.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhengqikj.top/Article/details/gtfmlnntev.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhongyouzk.top/Article/details/gtaeiekiaa.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gtpvecrwpr.html

Py:   max(arr);  min(arr)
来源：http://dali.haohaochexian.top/Article/details/gtxsplttqq.html

PHP:  max($arr);  min($arr);
来源：http://dali.zycfv.cn/Article/details/gtpghzjuzj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.nanxinkj.top/Article/details/gtwuftbona.html

TS:   Math.max(...arr);
来源：http://dali.sweek.top/Article/details/gtcsrjqwcw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jlsjyb.cn/Article/details/gtaapcjvyz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtxgvjsfzk.html

Ruby: arr.max;  arr.min
来源：http://dali.9152youxi.cn/Article/details/gtkaiefhgq.html

C#:   list.Max();  list.Min()
来源：http://dali.yanxiufei.cn/Article/details/gtzvhqykbx.html

[D18] 扁平化嵌套数组
来源：http://dali.cdnleiting.top/Article/details/gtxlgridcy.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.nanxuanxn.top/Article/details/gtpbcdiidc.html

PHP:  array_merge(...$nested);
来源：http://dali.cqqwz.cn/Article/details/gtuyyqkwww.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gtfidovoxa.html

TS:   nested.flat();
来源：http://dali.chenzaomai.com/Article/details/gtvuirzusj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yangfankeji.com/Article/details/gtojpvwejg.html

Go:   // 手写双层循环
来源：http://dali.fengsongda.top/Article/details/gtddbqeinn.html

Ruby: nested.flatten
来源：http://dali.yanxiufei.cn/Article/details/gtvnojxbif.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.daxiang520.top/Article/details/gtyvwmfdsn.html

[D19] 按字段分组
来源：http://dali.vqdsnc.cn/Article/details/gtqeylqbfo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gttsbmcnxo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258888.top/Article/details/gtvwdweeue.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aizwys.cn/Article/details/gtayzsqxkc.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gtubkkdtff.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.fzhhl.top/Article/details/gtlmtugqwx.html

Go:   // 手写 map[string][]T
来源：http://dali.dashuyun.cn/Article/details/gtxftpqfxi.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtryhutfdy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hfpthk.cn/Article/details/gtbgkeuroq.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258888.top/Article/details/gtypxivfwq.html

Py:   Counter(arr)
来源：http://dali.jiagoushi.top/Article/details/gtfzwfrkzq.html

PHP:  array_count_values($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtogeynzrk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yueranfly.top/Article/details/gtkoyekwvx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfuzfbim.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.0kj1m.cn/Article/details/gtelrtveht.html

Go:   // 手写 map[T]int
来源：http://dali.0kj1m.cn/Article/details/gtucroufra.html

Ruby: arr.tally
来源：http://dali.andypj.xyz/Article/details/gtuuyfwfkb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwvicfuu.html

[D21] 判断是否包含某元素
来源：http://dali.yuxming.cn/Article/details/gtkkrewrda.html

Py:   x in arr
来源：http://dali.xuanzx.com/Article/details/gtgvpqwyns.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zdqjudy.top/Article/details/gtpakqifwn.html

JS:   arr.includes(x)
来源：http://dali.ppjwa.cn/Article/details/gthwrrlbkm.html

TS:   arr.includes(x)
来源：http://dali.c1oappe.top/Article/details/gtnyhoycaq.html

Java: list.contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtqkrltsbp.html

Go:   slices.Contains(arr, x)
来源：http://dali.redwolf501.top/Article/details/gtscykohho.html

Ruby: arr.include?(x)
来源：http://dali.chenlongwang.top/Article/details/gtrxveiwau.html

C#:   list.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gtxszmpvhx.html

[D22] 复制数组（避免共享引用）
来源：http://dali.guannengcc.top/Article/details/gtnjvremsv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xziqi.cn/Article/details/gtihdotqfn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangdashe.top/Article/details/gtaquhnxhh.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.guannengcc.top/Article/details/gtoylfnlwe.html

TS:   [...arr];
来源：http://dali.jinqigfzy.top/Article/details/gtezkvxwit.html

Java: new ArrayList<>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsepffczk.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sxryk.cn/Article/details/gtqkezpjgs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.snrcjt.cn/Article/details/gtmotfaopy.html

C#:   new List<int>(list);
来源：http://dali.pycfn.com/Article/details/gtglgkxwxs.html

[D23] reduce 累积计算
来源：http://dali.ehwqpu.com/Article/details/gtjemxhgnw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.aibaodan.cn/Article/details/gtrjbaffex.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkxlccyd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtmrjusjue.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hysaishi.cn/Article/details/gtxoqvckur.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.ivvv.top/Article/details/gtmxkjtacp.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbnbuuohn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gzhubu.top/Article/details/gtnsuyuakv.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hnxiangtu.top/Article/details/gtgtxypqpt.html

[D24] 字典 / Map 基本操作
来源：http://dali.mhx1999.top/Article/details/gtgcctpqwy.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shzxlz.cn/Article/details/gtfghnxrgw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.redwolf501.top/Article/details/gthunisrwd.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gtymjhpbrw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtcuzwxzdv.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.snrcjt.cn/Article/details/gtfqmubqst.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hongshengwenyu.top/Article/details/gtnsixlqqr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.quarkkingdee.top/Article/details/gtgvjjfuhj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gogol.net.cn/Article/details/gtroxvxbre.html

[D25] Set 集合去重与交并差
来源：http://dali.tian-w.cn/Article/details/gtuqvzaetg.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.dashuyun.cn/Article/details/gtyvcwcmoc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sweek.top/Article/details/gtxgnblluf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj20258.top/Article/details/gtmhzhdxhg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhixingplan.top/Article/details/gttbgmhubu.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.snrcjt.cn/Article/details/gtotjnrlmw.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yuanzhike.top/Article/details/gtnoocdunx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.guowangkeji.top/Article/details/gtuuyrmcdi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gttpepydfd.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtgiiqryia.html

Py:   ", ".join(map(str, arr))
来源：http://dali.316326.xyz/Article/details/gtuxfkjxdb.html

PHP:  implode(", ", $arr);
来源：http://dali.xinyue.icu/Article/details/gtolbhxaan.html

JS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtytqteomf.html

TS:   arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gtfqygqfoq.html

Java: String.join(", ", list)
来源：http://dali.jinqigufen.top/Article/details/gtpkvpvjlq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hnqzz.top/Article/details/gtrxaeookj.html

Ruby: arr.join(", ")
来源：http://dali.jqgufenzy.top/Article/details/gthhifqitt.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gtmjydhygh.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtvbsclbci.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gthxvuqunw.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtksvoudbu.html

[E01] 拼接字符串
来源：http://dali.chenjidiqi.icu/Article/details/gtudhodxjr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dianchejie.cn/Article/details/gtitrcqsen.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hysaishi.cn/Article/details/gtbcoksies.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.meibo888.top/Article/details/gtxakazvns.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gtkscdwfke.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.pengpengdd.cyou/Article/details/gteytysfem.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.gogol.net.cn/Article/details/gtijzguvol.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ybcxt.top/Article/details/gthfufburf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtlatzdmfu.html

[E02] 重复字符串
来源：http://dali.guannengcc.top/Article/details/gtbwsbxgin.html

Py:   "ab" * 3
来源：http://dali.svipenyu.cn/Article/details/gtmpqruvip.html

PHP:  str_repeat("ab", 3);
来源：http://dali.ehwqpu.com/Article/details/gtiseqgsxs.html

JS:   "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtplucufsj.html

TS:   "ab".repeat(3)
来源：http://dali.xziqi.cn/Article/details/gtoffimfnw.html

Java: "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gtkudgedmg.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtjdzsonxm.html

Ruby: "ab" * 3
来源：http://dali.nwbrower.top/Article/details/gtygbqswto.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shangyingyoupin.top/Article/details/gtlchmwqan.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gtsfxwzxyy.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yuanzhike.top/Article/details/gthkptkpra.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.jlsjyb.cn/Article/details/gtijnwuduu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gtktktsmdf.html

TS:   s.slice(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnhnhffx.html

Java: s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gtvyzpsaub.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.svipenyu.cn/Article/details/gtyjdyufon.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gtbanjartq.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gtkwnrlahr.html

[E04] 查找子串位置
来源：http://dali.vqdsnc.cn/Article/details/gtjhxfqxfl.html

Py:   s.find("x");  s.index("x")
来源：http://dali.haohaochexian.top/Article/details/gtosbhtdmh.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gtniigxsri.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.tian-w.cn/Article/details/gtnywpiawt.html

TS:   s.indexOf("x")
来源：http://dali.guannengcc.top/Article/details/gtjcgfzdcw.html

Java: s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtrrbzjdpe.html

Go:   strings.Index(s, "x")
来源：http://dali.chenjidiqi.icu/Article/details/gtlhhcnvji.html

Ruby: s.index("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtddacocqm.html

C#:   s.IndexOf("x")
来源：http://dali.hysaishi.cn/Article/details/gtbbtmehla.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zdqjudy.top/Article/details/gtpondekij.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yongpay.top/Article/details/gtnfwzovdt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.guannengcc.top/Article/details/gthbnyzgkt.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.c1oappe.top/Article/details/gthogkjrhh.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gtgtmdvicm.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.dianchejie.cn/Article/details/gtqtltjsgx.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.shzxlz.cn/Article/details/gthmlnwikc.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.nanxinkj.top/Article/details/gthriyhbcr.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtvaxvxzxl.html

[E06] 替换子串
来源：http://dali.xziqi.cn/Article/details/gtdccwfsty.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hywenlv.cn/Article/details/gtcvopvtuh.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.cqqwz.cn/Article/details/gtxtjqxtlk.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtzzotwuiv.html

TS:   s.replaceAll("a", "b")
来源：http://dali.aibaodan.cn/Article/details/gtgurzxnye.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtnvbimkcr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.kuanghao11.cn/Article/details/gtozawzkui.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.iojbl.cn/Article/details/gtlrbsqxiv.html

C#:   s.Replace("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gtocabqabl.html

[E07] 按分隔符拆分
来源：http://dali.shuidangran.top/Article/details/gthnxqpbvk.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.birdmap.top/Article/details/gtayqkiuls.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.zhoulong.xyz/Article/details/gtzruhokag.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.iojbl.cn/Article/details/gtmcfhjntd.html

TS:   s.split(",")
来源：http://dali.xylfe.cn/Article/details/gtbxbtmbmk.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.tianlin.xyz/Article/details/gtuvmyrbei.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.hysaishi.cn/Article/details/gthacafpen.html

Ruby: s.split(",");  s.split
来源：http://dali.yueranfly.top/Article/details/gtickkopgd.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.fengsongda.top/Article/details/gtjzweqrgl.html

[E08] 数组按分隔符合并
来源：http://dali.dianchejie.cn/Article/details/gthpyxphak.html

Py:   ",".join(items)
来源：http://dali.zhoulong.xyz/Article/details/gtysmomtpz.html

PHP:  implode(",", $items);
来源：http://dali.cqqwz.cn/Article/details/gtjcemyqzk.html

JS:   items.join(",")
来源：http://dali.pengpengdd.cyou/Article/details/gtgebtotou.html

TS:   items.join(",")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdmopkch.html

Java: String.join(",", items)
来源：http://dali.mhx1999.top/Article/details/gtdudzeujw.html

Go:   strings.Join(items, ",")
来源：http://dali.chenlongwang.top/Article/details/gtgxbhlgue.html

Ruby: items.join(",")
来源：http://dali.0kj1m.cn/Article/details/gtdcdpsudm.html

C#:   string.Join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtjkzrrrzy.html

[E09] 去除所有空白字符
来源：http://dali.aibaodan.cn/Article/details/gtnjaoxfeh.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jyoumei.cn/Article/details/gtwhwrhhuz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.ppjwa.cn/Article/details/gthdggbvxm.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jiagoushi.top/Article/details/gtcvyhhucq.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.tian-w.cn/Article/details/gtxnouundt.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cheryme.top/Article/details/gtpaemoutt.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.daxiang520.top/Article/details/gtsfdoacoz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.yj20258888.top/Article/details/gtjbutbfqn.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopwrbuwm.html

[E10] 左侧补零 / 定长填充
来源：http://dali.yvedp.cn/Article/details/gtcysdzgza.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gtromcwktt.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.yj20258.top/Article/details/gtxldzubxr.html

JS:   "7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtlucsnqop.html

TS:   "7".padStart(3, "0")
来源：http://dali.redwolf501.top/Article/details/gtzylbaqlv.html

Java: String.format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtvzypzkth.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.kuanghao11.cn/Article/details/gtkkopvjkv.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtocpavwsi.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.tanke756.top/Article/details/gtugeqsrko.html

[E11] 反转字符串
来源：http://dali.feifeiyinyue.top/Article/details/gthypesxzs.html

Py:   s[::-1]
来源：http://dali.ydzc1.top/Article/details/gtqmjxsmjs.html

PHP:  strrev($s);
来源：http://dali.xylfe.cn/Article/details/gtjhhmqbeh.html

JS:   [...s].reverse().join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfrdyjpcu.html

TS:   [...s].reverse().join("")
来源：http://dali.yj202588.top/Article/details/gtmitefdrs.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shuidangran.top/Article/details/gtpidaghhv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yonumen.top/Article/details/gtjxxxooec.html

Ruby: s.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gtvgbwanbl.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.nwbrower.top/Article/details/gtmunijgwn.html

[E12] 统计某字符出现次数
来源：http://dali.ydzc1.top/Article/details/gtxgudruab.html

Py:   s.count("a")
来源：http://dali.zhixingplan.top/Article/details/gtklbxuzzl.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gtjesqyfga.html

JS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtwdrqofqt.html

TS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtltodpjrh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.cashguo.top/Article/details/gtbuciaybh.html

Go:   strings.Count(s, "a")
来源：http://dali.chenlongwang.top/Article/details/gtgknvqbky.html

Ruby: s.count("a")
来源：http://dali.gogol.net.cn/Article/details/gtyczxzpeo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.aizwys.cn/Article/details/gttdmslgny.html

[E13] 逐字符遍历
来源：http://dali.zhengqikj.top/Article/details/gtywdhxepp.html

Py:   for ch in s: print(ch)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpazfvdmb.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nwbrower.top/Article/details/gtaavqdtfh.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yuanzhike.top/Article/details/gtijdakfva.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nwbrower.top/Article/details/gttnrdasdf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrnguxrd.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.gogol.net.cn/Article/details/gtmftfpsti.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shangyingyoupin.top/Article/details/gtvojphrxd.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnqzz.top/Article/details/gtbemgkkyy.html

[E14] URL 编码与 Base64
来源：http://dali.ydzc1.top/Article/details/gtwtkjuocb.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.9152youxi.cn/Article/details/gtwgjutssc.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.xziqi.cn/Article/details/gtbgtsaqwq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gtmvlrylqx.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckmkdxow.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.fengsongda.top/Article/details/gthlembvnn.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hysaishi.cn/Article/details/gtvgsortej.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.snrcjt.cn/Article/details/gtsaygkowb.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gtscuyoefc.html

[E15] HTML 转义 / 反转义
来源：http://dali.cucudq.cn/Article/details/gtlwsdwpfn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yj20258888.top/Article/details/gtouifrsbj.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.hnqzz.top/Article/details/gtfhitosab.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.bjfxy.top/Article/details/gtuwjtsznn.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.bjfxy.top/Article/details/gtphinotcg.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.andypj.xyz/Article/details/gtdvaainiz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gtufajzzkh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.sufxvd.cn/Article/details/gtqbnwidyy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.sweek.top/Article/details/gtddvpzoxa.html

[E16] 数字千分位
来源：http://dali.cucudq.cn/Article/details/gtmocaftgz.html

Py:   f"{1234567:,}"
来源：http://dali.yj20258.top/Article/details/gtcwdqkrcd.html

PHP:  number_format(1234567);
来源：http://dali.chenlongwang.top/Article/details/gtgveesvgo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.pycfn.com/Article/details/gtulnnzljs.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.birdmap.top/Article/details/gtttjbtqfz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.sufxvd.cn/Article/details/gtolllsxlz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.yanxiufei.cn/Article/details/gtokthrgpt.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.0kj1m.cn/Article/details/gtrrpqpqnn.html

C#:   1234567.ToString("N0")
来源：http://dali.cashguo.top/Article/details/gtdqdeqpza.html

[E17] 首字母大写
来源：http://dali.316326.xyz/Article/details/gtksjtzqvd.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ppjwa.cn/Article/details/gtfmcpqtvm.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfvfmxon.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.guannengcc.top/Article/details/gtzoksnudm.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.wangdashe.top/Article/details/gtrboadugz.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yueranfly.top/Article/details/gtdrnlqygo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhixingplan.top/Article/details/gtrcjyslld.html

Ruby: s.capitalize
来源：http://dali.dashuyun.cn/Article/details/gtiesjhlvb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.yuxming.cn/Article/details/gthnrrcijm.html

[E18] 模板占位符替换
来源：http://dali.yongpay.top/Article/details/gtfivpqfsi.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aibaodan.cn/Article/details/gtnjycepie.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdfxjruz.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shuidangran.top/Article/details/gtoqsvcjyr.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinqigufen.top/Article/details/gtwqorefye.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gtqspuftex.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvmuejhqt.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.mhx1999.top/Article/details/gtxuodxftz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jlsjyb.cn/Article/details/gtmxhmsxyl.html

[E19] 多行文本按行拆分
来源：http://dali.c1oappe.top/Article/details/gtlnjlxbga.html

Py:   s.splitlines()
来源：http://dali.redwolf501.top/Article/details/gtrucojhzi.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jinqigufen.top/Article/details/gtgjymqlod.html


<!-- 参考信息 -->