代发 wailian999

C#:   list.Reverse();
来源：http://dali.smart0.xyz/Article/details/gtsvdieeng.html

[D12] 查找元素下标
来源：http://dali.ybcxt.top/Article/details/gtrsvpkqbk.html

Py:   arr.index(x);  x in arr
来源：http://dali.tianlin.xyz/Article/details/gtrlwstcta.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sysykeji.top/Article/details/gtsliddqdg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cdnleiting.top/Article/details/gthhcjmylh.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtjepabmhz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.redwolf501.top/Article/details/gtcjdrfluf.html

Go:   slices.Index(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtclnbgnjt.html

Ruby: arr.index(x)
来源：http://dali.zhixingplan.top/Article/details/gtyqiwefjh.html

C#:   list.IndexOf(x);
来源：http://dali.aibaodan.cn/Article/details/gtanhwoysa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.meibo888.top/Article/details/gtqdrjogiu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xziqi.cn/Article/details/gtgiziatse.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ppjwa.cn/Article/details/gtijadttrk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gtdepdnjqi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuigkqvyv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.birdmap.top/Article/details/gtcykptnes.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shzxlz.cn/Article/details/gtnjifejdp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.feifeiyinyue.top/Article/details/gtghnhymdy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fengsongda.top/Article/details/gtgwjuwfdt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zycfv.cn/Article/details/gtqbdjwcox.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gzhubu.top/Article/details/gtausrckte.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cheryme.top/Article/details/gtemvyzpgu.html

JS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtifegkwul.html

TS:   arr.map(x => x * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtfugimqql.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yuanzhike.top/Article/details/gteoarhgyg.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtdqnnkvhl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtfcliacrg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtglobuwyi.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gtmmdazzrr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gtwcedxsjv.html

PHP:  array_unique($arr);
来源：http://dali.chenzaomai.com/Article/details/gtkeffhavj.html

JS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtbdozcimp.html

TS:   [...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtjbgdkjab.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xylfe.cn/Article/details/gtruvinzgq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgxdgova.html

Ruby: arr.uniq
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstuvhlnx.html

C#:   list.Distinct().ToList()
来源：http://dali.ehwqpu.com/Article/details/gthuivrjfj.html

[D16] 求和与平均值
来源：http://dali.kuanghao11.cn/Article/details/gtovozyfxw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtdxhxfuen.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtkqtosubk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gtgdmtofje.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gtlotchmla.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuxming.cn/Article/details/gttdnbwjyj.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gtczgulpqo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gaohongyu789.top/Article/details/gtwglwbvmj.html

C#:   list.Sum();  list.Average()
来源：http://dali.shangyingyoupin.top/Article/details/gtsiibqtju.html

[D17] 最大值与最小值
来源：http://dali.guannengcc.top/Article/details/gtuyieaixj.html

Py:   max(arr);  min(arr)
来源：http://dali.tianlin.xyz/Article/details/gtbtxdtgwk.html

PHP:  max($arr);  min($arr);
来源：http://dali.gotoacloud.top/Article/details/gtewshapzn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gthixfggyt.html

TS:   Math.max(...arr);
来源：http://dali.pycfn.com/Article/details/gtscxodndh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guannengcc.top/Article/details/gtszqwpfsl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtukddiolm.html

Ruby: arr.max;  arr.min
来源：http://dali.hfpthk.cn/Article/details/gtxefsxpzj.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258.top/Article/details/gtwuzxjqng.html

[D18] 扁平化嵌套数组
来源：http://dali.zhengqikj.top/Article/details/gtwogfkjfg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sweek.top/Article/details/gtfnxoqrae.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gtdmprxhuy.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daxiang520.top/Article/details/gthgxcrxfa.html

TS:   nested.flat();
来源：http://dali.jiagoushi.top/Article/details/gtieelojwv.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gogol.net.cn/Article/details/gtlpzxcosj.html

Go:   // 手写双层循环
来源：http://dali.havefunace.top/Article/details/gtknspbhsk.html

Ruby: nested.flatten
来源：http://dali.pycfn.com/Article/details/gtcwrtfvkq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtepzddyzm.html

[D19] 按字段分组
来源：http://dali.zhixingplan.top/Article/details/gtgtoamctt.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yj20258888.top/Article/details/gtkrlwdqoi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gtowlzgubj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnxiangtu.top/Article/details/gtjixkycgo.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gtdleuzqhx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cheryme.top/Article/details/gtvsmweeba.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gtnqrrwkpv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hammf.cn/Article/details/gtpnxrnyzi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.0kj1m.cn/Article/details/gtddiuocyv.html

[D20] 统计每个元素出现次数
来源：http://dali.chenjidiqi.icu/Article/details/gthkmazefy.html

Py:   Counter(arr)
来源：http://dali.cucudq.cn/Article/details/gtzmxbdecj.html

PHP:  array_count_values($arr);
来源：http://dali.havefunace.top/Article/details/gtcbyyyvye.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnihkhvgt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cucudq.cn/Article/details/gtpjhviesq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.iojbl.cn/Article/details/gtefcgrayc.html

Go:   // 手写 map[T]int
来源：http://dali.fzhhl.top/Article/details/gtnmykdlje.html

Ruby: arr.tally
来源：http://dali.tianlin.xyz/Article/details/gtyvhvxabr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoooxzbko.html

[D21] 判断是否包含某元素
来源：http://dali.zdqjudy.top/Article/details/gtiozalyjj.html

Py:   x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzerljaym.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hysaishi.cn/Article/details/gtvyrzlmma.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtlqxwopax.html

TS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gtngzkiwyl.html

Java: list.contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtqayfllmt.html

Go:   slices.Contains(arr, x)
来源：http://dali.yonumen.top/Article/details/gtvvmilqzd.html

Ruby: arr.include?(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqqncaay.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gtatflfkdh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jiagoushi.top/Article/details/gtlebqlklv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtwfmgoifb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gttqseimrl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gogol.net.cn/Article/details/gtykkxdypr.html

TS:   [...arr];
来源：http://dali.guowangkeji.top/Article/details/gtmnxhgnqi.html

Java: new ArrayList<>(list);
来源：http://dali.gotoacloud.top/Article/details/gtrahtatzd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gaohongyu789.top/Article/details/gthyhzzodh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.birdmap.top/Article/details/gtrxpfyzzp.html

C#:   new List<int>(list);
来源：http://dali.snrcjt.cn/Article/details/gtnmsedmyb.html

[D23] reduce 累积计算
来源：http://dali.xziqi.cn/Article/details/gtilqhxcqw.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnqzz.top/Article/details/gthfsbesva.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.dashuyun.cn/Article/details/gtismtuxpp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuufuaqbz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtzyvnwfqx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nwbrower.top/Article/details/gtkyqytsyo.html

Go:   // 手写循环
来源：http://dali.jqgufenzy.top/Article/details/gtaqrptepv.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yvedp.cn/Article/details/gtnwflnrxg.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.tianlin.xyz/Article/details/gthtcfrmqm.html

[D24] 字典 / Map 基本操作
来源：http://dali.gogol.net.cn/Article/details/gtmahlpazh.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.iojbl.cn/Article/details/gtblcpskvr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.redwolf501.top/Article/details/gtlvaobbxy.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yueranfly.top/Article/details/gtqhdhsvpl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pycfn.com/Article/details/gthqwchsgl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sysykeji.top/Article/details/gtpxmulexb.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufnjrclh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhixingplan.top/Article/details/gtmhpgwvmn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.ppjwa.cn/Article/details/gtvkirvqal.html

[D25] Set 集合去重与交并差
来源：http://dali.zdqjudy.top/Article/details/gtezdqiweb.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ydzc1.top/Article/details/gttdjxmeze.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.feifeiyinyue.top/Article/details/gtdjjkwlvy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.quarkkingdee.top/Article/details/gtqzewtgjg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yonumen.top/Article/details/gtqwexzupn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.kuanghao11.cn/Article/details/gtrilndxew.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hammf.cn/Article/details/gttfgeysvm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.nwbrower.top/Article/details/gtfychpkex.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sysykeji.top/Article/details/gtpddebisl.html

[D26] 数组转字符串
来源：http://dali.yueranfly.top/Article/details/gtnpzfpqwj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.sufxvd.cn/Article/details/gtyyyjoiup.html

PHP:  implode(", ", $arr);
来源：http://dali.yj20258.top/Article/details/gtqgurhjgy.html

JS:   arr.join(", ")
来源：http://dali.yonumen.top/Article/details/gtzujbvsco.html

TS:   arr.join(", ")
来源：http://dali.hysaishi.cn/Article/details/gtgwuuqdff.html

Java: String.join(", ", list)
来源：http://dali.ivvv.top/Article/details/gtbbpfpeab.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hammf.cn/Article/details/gthvkwceqi.html

Ruby: arr.join(", ")
来源：http://dali.aizwys.cn/Article/details/gttkqngaje.html

C#:   string.Join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gtpyvwzrjy.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtsnebqish.html

E. 字符串处理
来源：http://dali.redwolf501.top/Article/details/gtqpeuymhf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtqydwvtte.html

[E01] 拼接字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrownmpct.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ivvv.top/Article/details/gtipqwlcls.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.gotoacloud.top/Article/details/gtyflxjtsy.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shuidangran.top/Article/details/gtszfmflkm.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gtsnrulpud.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.meibo888.top/Article/details/gtbxizufku.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhengqikj.top/Article/details/gtudczkabc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinghuilouyu.cn/Article/details/gtupyotcdv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywkgrbrj.html

[E02] 重复字符串
来源：http://dali.pengpengdd.cyou/Article/details/gthrtuhlid.html

Py:   "ab" * 3
来源：http://dali.yuanzhike.top/Article/details/gtvhvpxnfy.html

PHP:  str_repeat("ab", 3);
来源：http://dali.daxiang520.top/Article/details/gtvxapgxwd.html

JS:   "ab".repeat(3)
来源：http://dali.jqgfzy.top/Article/details/gtpofpnxdm.html

TS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gtxbztbzqo.html

Java: "ab".repeat(3)
来源：http://dali.hnqzz.top/Article/details/gttsydfjwq.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dianchejie.cn/Article/details/gtzriobayu.html

Ruby: "ab" * 3
来源：http://dali.jinqigfzy.top/Article/details/gtbcmssost.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gaohongyu789.top/Article/details/gttiuvlnje.html

[E03] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtrvjxnezt.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzbzndpi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuufmpkun.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtodqcdmcb.html

TS:   s.slice(1, 4)
来源：http://dali.daria6918.cn/Article/details/gtcmevrdkn.html

Java: s.substring(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtlibbtixj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.dianchejie.cn/Article/details/gtykuwvdlv.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.haohaochexian.top/Article/details/gtzdbqwweh.html

C#:   s.Substring(1, 3)
来源：http://dali.aibaodan.cn/Article/details/gtslnyluyb.html

[E04] 查找子串位置
来源：http://dali.wangdashe.top/Article/details/gtzpfddlch.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gtfbqtlvzk.html

PHP:  strpos($s, "x");
来源：http://dali.zycfv.cn/Article/details/gtnniuitpw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.pycfn.com/Article/details/gtzvahkswt.html

TS:   s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gtspfgejyl.html

Java: s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtqndhtsgo.html

Go:   strings.Index(s, "x")
来源：http://dali.fzhhl.top/Article/details/gtqvijcwfe.html

Ruby: s.index("x")
来源：http://dali.yuanzhike.top/Article/details/gtxelqzqyx.html

C#:   s.IndexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtspcdgudv.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.hongshengwenyu.top/Article/details/gtmpivanpd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.fengsongda.top/Article/details/gtwbechoyq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.ybcxt.top/Article/details/gtvaralacy.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sweek.top/Article/details/gtqchnohvc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cdnleiting.top/Article/details/gtnjpafysq.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.9152youxi.cn/Article/details/gttrtbpeef.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.316326.xyz/Article/details/gtvitlqxhx.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.hnqzz.top/Article/details/gtzintfgcy.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtmjrwiikl.html

[E06] 替换子串
来源：http://dali.xinyue.icu/Article/details/gtuyplddbm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.316326.xyz/Article/details/gtrmifnufs.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shuidangran.top/Article/details/gtwtraiofe.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtsagjqtaf.html

TS:   s.replaceAll("a", "b")
来源：http://dali.bjfxy.top/Article/details/gtdizzdbdx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtshejtppj.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.hysaishi.cn/Article/details/gtrsrllwkq.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.316326.xyz/Article/details/gtnqusodri.html

C#:   s.Replace("a", "b")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwahbvrvn.html

[E07] 按分隔符拆分
来源：http://dali.yvedp.cn/Article/details/gteatixidm.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.jianghu66.top/Article/details/gtcoznekos.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.hnqzz.top/Article/details/gtgnblotnt.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.sufxvd.cn/Article/details/gtedjdopkq.html

TS:   s.split(",")
来源：http://dali.yvedp.cn/Article/details/gtvelkdiww.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.jlsjyb.cn/Article/details/gtfngijiic.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.dashuyun.cn/Article/details/gtmfqvdonh.html

Ruby: s.split(",");  s.split
来源：http://dali.zhoulong.xyz/Article/details/gthlfauemy.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.mhx1999.top/Article/details/gtnjapzhoi.html

[E08] 数组按分隔符合并
来源：http://dali.jqgfzy.top/Article/details/gtcalkyakd.html

Py:   ",".join(items)
来源：http://dali.sufxvd.cn/Article/details/gtcleamezr.html

PHP:  implode(",", $items);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvkgvirma.html

JS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gthulijpdp.html

TS:   items.join(",")
来源：http://dali.c1oappe.top/Article/details/gtevdikkpq.html

Java: String.join(",", items)
来源：http://dali.sweek.top/Article/details/gtcnrpytkh.html

Go:   strings.Join(items, ",")
来源：http://dali.0kj1m.cn/Article/details/gtnxbbpfmz.html

Ruby: items.join(",")
来源：http://dali.redwolf501.top/Article/details/gthnhoxzqr.html

C#:   string.Join(",", items)
来源：http://dali.jiagoushi.top/Article/details/gtdzrnejvb.html

[E09] 去除所有空白字符
来源：http://dali.ppjwa.cn/Article/details/gtioxmhjbf.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.c1oappe.top/Article/details/gtywcgzcnc.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigufen.top/Article/details/gtxalfrazf.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.hongshengwenyu.top/Article/details/gttbyeoccn.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.vqdsnc.cn/Article/details/gtmqtebedx.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.gaohongyu789.top/Article/details/gtesrldypu.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.chenlongwang.top/Article/details/gtvflhmyhn.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttipvwmbk.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.ehwqpu.com/Article/details/gthkkwhxja.html

[E10] 左侧补零 / 定长填充
来源：http://dali.shanyushiyangtech.top/Article/details/gtsxqibfgm.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.xziqi.cn/Article/details/gttdhmjcpy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cheryme.top/Article/details/gtktgdffmw.html

JS:   "7".padStart(3, "0")
来源：http://dali.hysaishi.cn/Article/details/gtnutazvxp.html

TS:   "7".padStart(3, "0")
来源：http://dali.quarkkingdee.top/Article/details/gtxouqagnx.html

Java: String.format("%03d", 7)
来源：http://dali.jqgufenzy.top/Article/details/gtawzpmaiv.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtqdxkzonc.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.sweek.top/Article/details/gtpxbvilkb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yuanzhike.top/Article/details/gtxzmfcyun.html

[E11] 反转字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqlaopmm.html

Py:   s[::-1]
来源：http://dali.aizwys.cn/Article/details/gtpfgtdqby.html

PHP:  strrev($s);
来源：http://dali.zhixingplan.top/Article/details/gtcrrafaak.html

JS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtjtphciec.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtuxcuykti.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.zhongyouzk.top/Article/details/gtjwtmbgvz.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gthnbzngjf.html

Ruby: s.reverse
来源：http://dali.tanke756.top/Article/details/gtlgljfdcj.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.yonumen.top/Article/details/gtgiozbogc.html

[E12] 统计某字符出现次数
来源：http://dali.nanxuanxn.top/Article/details/gtqqqemnhk.html

Py:   s.count("a")
来源：http://dali.yj202588.top/Article/details/gtvurpmdvx.html

PHP:  substr_count($s, "a");
来源：http://dali.tianlin.xyz/Article/details/gtszxclrrm.html

JS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gtpfdpleso.html

TS:   s.split("a").length - 1
来源：http://dali.jqgfzy.top/Article/details/gtkvypizzi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.dianchejie.cn/Article/details/gtqaimsxsq.html

Go:   strings.Count(s, "a")
来源：http://dali.meibo888.top/Article/details/gtmeznudwe.html

Ruby: s.count("a")
来源：http://dali.quarkkingdee.top/Article/details/gtnxyoytho.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gotoacloud.top/Article/details/gttmgphunc.html

[E13] 逐字符遍历
来源：http://dali.gzhubu.top/Article/details/gtmhuwrkmf.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gtvrppzoru.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.shuidangran.top/Article/details/gtlpujnrcm.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yonumen.top/Article/details/gtebwdhizh.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gtarnrmtuh.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gogol.net.cn/Article/details/gtcyeuiqus.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jinqigfzy.top/Article/details/gtaabsydpd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenzaomai.com/Article/details/gtvplpxnwy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tianlin.xyz/Article/details/gtkivzendk.html

[E14] URL 编码与 Base64
来源：http://dali.jyoumei.cn/Article/details/gtjocivgie.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinqigfzy.top/Article/details/gtxmpzdlfm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.daxiang520.top/Article/details/gtouoqgyue.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.nanxuanxn.top/Article/details/gtxuetpjxs.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.tian-w.cn/Article/details/gtozmyxlqj.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yuanzhike.top/Article/details/gtpejihtls.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hnqzz.top/Article/details/gtqcyifgbk.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jyoumei.cn/Article/details/gthfgqryoo.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsyikoilz.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenjidiqi.icu/Article/details/gtpmkavzvn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gtnwemwkvf.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.jyoumei.cn/Article/details/gtzfjxocvo.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hnqzz.top/Article/details/gthpvcikfx.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.cheryme.top/Article/details/gtwdhiqvkr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.daria6918.cn/Article/details/gtutzhvxhx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tanke756.top/Article/details/gtoelxfzjd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.cqqwz.cn/Article/details/gtvnfdzxmn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.havefunace.top/Article/details/gteakvrwea.html

[E16] 数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtfwdgippd.html

Py:   f"{1234567:,}"
来源：http://dali.jlsjyb.cn/Article/details/gtucnhqeon.html

PHP:  number_format(1234567);
来源：http://dali.shuidangran.top/Article/details/gtitdyodcq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.cdnleiting.top/Article/details/gtnyrlffbh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtkukltbyv.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ydzc1.top/Article/details/gtbtimeraj.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xziqi.cn/Article/details/gtpgqbpjwq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.mhx1999.top/Article/details/gtvhjotrbt.html

C#:   1234567.ToString("N0")
来源：http://dali.gotoacloud.top/Article/details/gtnqdcflwk.html

[E17] 首字母大写
来源：http://dali.jinghuilouyu.cn/Article/details/gtladuxcyr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.dashuyun.cn/Article/details/gtfymisgvs.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdcicwuh.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtstkkabrk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.mhx1999.top/Article/details/gtowihfbmj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guannengcc.top/Article/details/gtqqciobhr.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.tanke756.top/Article/details/gtiygqkjra.html

Ruby: s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gtaqzokpcz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.sxryk.cn/Article/details/gtvfbfddcg.html

[E18] 模板占位符替换
来源：http://dali.sweek.top/Article/details/gtfpfjlorr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.bjfxy.top/Article/details/gtzdvraoih.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.fzhhl.top/Article/details/gtmbagnras.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gttmmeoxsa.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrasygrh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fzhhl.top/Article/details/gthwduytit.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yonumen.top/Article/details/gtvglexkql.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nanxuanxn.top/Article/details/gtbslqqveq.html


<!-- 参考信息 -->