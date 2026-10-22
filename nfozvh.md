代发 wailian999

[D11] 反转数组
来源：http://dali.zhixingplan.top/Article/details/gtctkubpjl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldgyoins.html

PHP:  array_reverse($arr);
来源：http://dali.jyoumei.cn/Article/details/gtrlysycez.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinqigufen.top/Article/details/gtdtmbhbdj.html

TS:   [...arr].reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gtcieimzrn.html

Java: Collections.reverse(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtamfaezpc.html

Go:   slices.Reverse(arr)
来源：http://dali.sysykeji.top/Article/details/gtyeroqicm.html

Ruby: arr.reverse
来源：http://dali.sufxvd.cn/Article/details/gtpducrssc.html

C#:   list.Reverse();
来源：http://dali.meibo888.top/Article/details/gtuotumuyq.html

[D12] 查找元素下标
来源：http://dali.quarkkingdee.top/Article/details/gtdnaefdrb.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdowzfadl.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtpxxmgugs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtoowdqsbt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gtmmxoemfz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fengsongda.top/Article/details/gtfjakkemc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gttdkcivuu.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gtnrabrxwn.html

C#:   list.IndexOf(x);
来源：http://dali.cashguo.top/Article/details/gtelxaqvqn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gtmwzbdikj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguvvzzyp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.quarkkingdee.top/Article/details/gtruuuewta.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cucudq.cn/Article/details/gtlexyhdoi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtrbtxsmks.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gtifaehwue.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.9152youxi.cn/Article/details/gtqkwgllaj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shzxlz.cn/Article/details/gtvowxfkuj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gtaaendaqz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yongpay.top/Article/details/gtsolfngfw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daria6918.cn/Article/details/gtuscbmufv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangdashe.top/Article/details/gtjveughxa.html

JS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtptvwxjbg.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gtxkfrhxlk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbmuqrnc.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtjygmunoj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtxpcbnozs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zdqjudy.top/Article/details/gtdxetaols.html

[D15] 去重
来源：http://dali.fzhhl.top/Article/details/gtocigqnex.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowsisbie.html

PHP:  array_unique($arr);
来源：http://dali.haohaochexian.top/Article/details/gtlcyklvbn.html

JS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtzouqnwtf.html

TS:   [...new Set(arr)]
来源：http://dali.gogol.net.cn/Article/details/gtcjbfrrog.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.pengpengdd.cyou/Article/details/gtbwbwimlb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zdqjudy.top/Article/details/gtznkjtwgx.html

Ruby: arr.uniq
来源：http://dali.zhoulong.xyz/Article/details/gtbmnhqesh.html

C#:   list.Distinct().ToList()
来源：http://dali.svipenyu.cn/Article/details/gtvepbimrk.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gtgtzcgneh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtoyhxcrgt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtsjcgwchj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dianchejie.cn/Article/details/gtvclzwgqw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gtydwrjuqu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hongshengwenyu.top/Article/details/gtlprshyjv.html

Go:   // 手写循环累加
来源：http://dali.yj20258888.top/Article/details/gtssunczpr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ybcxt.top/Article/details/gtfujzyubu.html

C#:   list.Sum();  list.Average()
来源：http://dali.daria6918.cn/Article/details/gtdmpsizes.html

[D17] 最大值与最小值
来源：http://dali.yueranfly.top/Article/details/gtrqyhqgst.html

Py:   max(arr);  min(arr)
来源：http://dali.jyoumei.cn/Article/details/gtbmxtwiso.html

PHP:  max($arr);  min($arr);
来源：http://dali.yj20258888.top/Article/details/gtsfvprlhu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhengqikj.top/Article/details/gtncqkocje.html

TS:   Math.max(...arr);
来源：http://dali.dashuyun.cn/Article/details/gtjuorjltu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gtbhphaqqp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtkjrexxzl.html

Ruby: arr.max;  arr.min
来源：http://dali.ehwqpu.com/Article/details/gtgkavnrbx.html

C#:   list.Max();  list.Min()
来源：http://dali.cqqwz.cn/Article/details/gtuluinnth.html

[D18] 扁平化嵌套数组
来源：http://dali.svipenyu.cn/Article/details/gtoxletvln.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.316326.xyz/Article/details/gtwoktshrq.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgufenzy.top/Article/details/gtkcczmxpa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gtqtczattz.html

TS:   nested.flat();
来源：http://dali.yongpay.top/Article/details/gtgazygoqd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvsiicvf.html

Go:   // 手写双层循环
来源：http://dali.cheryme.top/Article/details/gteauenvsi.html

Ruby: nested.flatten
来源：http://dali.shangyingyoupin.top/Article/details/gtxjzoszrh.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtymbgazsh.html

[D19] 按字段分组
来源：http://dali.bjfxy.top/Article/details/gtntvycyar.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gtijzpyeta.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yuxming.cn/Article/details/gtuloeszyl.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.9152youxi.cn/Article/details/gtkiefgcti.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gtxbgqcsev.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gtjmczhyvq.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gtfisygiua.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxugjkxqw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.316326.xyz/Article/details/gtwgklwbdj.html

[D20] 统计每个元素出现次数
来源：http://dali.shanyushiyangtech.top/Article/details/gtillggsub.html

Py:   Counter(arr)
来源：http://dali.yj20258.top/Article/details/gtfrggeiup.html

PHP:  array_count_values($arr);
来源：http://dali.sweek.top/Article/details/gtjglhumxu.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gtpecaxbgb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtojscoazi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jlsjyb.cn/Article/details/gticcleldt.html

Go:   // 手写 map[T]int
来源：http://dali.ivvv.top/Article/details/gtwvxgngix.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gtuzxdguzr.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jianghu66.top/Article/details/gtzuisswjo.html

[D21] 判断是否包含某元素
来源：http://dali.jlsjyb.cn/Article/details/gthxrldljp.html

Py:   x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gtlotosnat.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcfxobwj.html

JS:   arr.includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtwhcwsimk.html

TS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtrstlayxw.html

Java: list.contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslgjlind.html

Go:   slices.Contains(arr, x)
来源：http://dali.jqgfzy.top/Article/details/gthswcrhca.html

Ruby: arr.include?(x)
来源：http://dali.c1oappe.top/Article/details/gthmyigene.html

C#:   list.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gtzavxpqof.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yj202588.top/Article/details/gtclbpzckb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwotguqa.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangshuangyany.cn/Article/details/gtjgpzoglu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gttnhxuzoy.html

TS:   [...arr];
来源：http://dali.sysykeji.top/Article/details/gtchlrbtdh.html

Java: new ArrayList<>(list);
来源：http://dali.jiagoushi.top/Article/details/gtpslzynpd.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhoulong.xyz/Article/details/gtlygcmwwh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.chenjidiqi.icu/Article/details/gtbounwfnt.html

C#:   new List<int>(list);
来源：http://dali.jlsjyb.cn/Article/details/gtlvohufkk.html

[D23] reduce 累积计算
来源：http://dali.nanxinkj.top/Article/details/gtxtnebcvx.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.tianlin.xyz/Article/details/gtwyefirat.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tian-w.cn/Article/details/gtzqdjeuub.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.tianlin.xyz/Article/details/gtccpcydxx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtfqmiiped.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigufen.top/Article/details/gtfymcnbok.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gtmroadjts.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jianghu66.top/Article/details/gtygogxkfs.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yj202588.top/Article/details/gtseqlxgpo.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhoulong.xyz/Article/details/gtolmilpmi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tian-w.cn/Article/details/gtszogusbl.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yangfankeji.com/Article/details/gtgshcjrnr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gtseauwjuu.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtppjxleti.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jianghu66.top/Article/details/gtrtzuqvlx.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.tanke756.top/Article/details/gtajcppmda.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ydzc1.top/Article/details/gtgkfhrmnz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.aibaodan.cn/Article/details/gtojaqlrdi.html

[D25] Set 集合去重与交并差
来源：http://dali.zhengqikj.top/Article/details/gtusinxnuo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.iojbl.cn/Article/details/gtswytvych.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.sufxvd.cn/Article/details/gtkwmnoqkp.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnxiangtu.top/Article/details/gtsuyzumph.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.sweek.top/Article/details/gtthfsknps.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqfmjhdg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cucudq.cn/Article/details/gtmmczekxc.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.svipenyu.cn/Article/details/gttrtchavq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.redwolf501.top/Article/details/gtghnhpzmf.html

[D26] 数组转字符串
来源：http://dali.zhoulong.xyz/Article/details/gtvkokegmb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jianghu66.top/Article/details/gtgmtroziy.html

PHP:  implode(", ", $arr);
来源：http://dali.cashguo.top/Article/details/gtwectvwro.html

JS:   arr.join(", ")
来源：http://dali.kuanghao11.cn/Article/details/gtsigibdjw.html

TS:   arr.join(", ")
来源：http://dali.haohaochexian.top/Article/details/gtldrxihmp.html

Java: String.join(", ", list)
来源：http://dali.gaohongyu789.top/Article/details/gteijairgq.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yongpay.top/Article/details/gtczucbmof.html

Ruby: arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gtssnxfvpe.html

C#:   string.Join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcfwgvkr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdiulcxc.html

E. 字符串处理
来源：http://dali.gogol.net.cn/Article/details/gthoqeixcm.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtnirckaav.html

[E01] 拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtkwipebwd.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.chenlongwang.top/Article/details/gtdhytlcwb.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jyoumei.cn/Article/details/gtcbgcsglz.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gtrjgmgphd.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cucudq.cn/Article/details/gtmtpzwnqy.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jlsjyb.cn/Article/details/gtmckqqnkb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnatvypqh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gaohongyu789.top/Article/details/gtqeaznrhm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwzvaojrn.html

[E02] 重复字符串
来源：http://dali.shzxlz.cn/Article/details/gtuevdlchr.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gtfjpanswq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj202588.top/Article/details/gtecgrrdvh.html

JS:   "ab".repeat(3)
来源：http://dali.redwolf501.top/Article/details/gtkiltzldp.html

TS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gthegvdbbz.html

Java: "ab".repeat(3)
来源：http://dali.hnxiangtu.top/Article/details/gtgzweeoli.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ppjwa.cn/Article/details/gtrkaioqov.html

Ruby: "ab" * 3
来源：http://dali.fzhhl.top/Article/details/gtkkicgpnx.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yongpay.top/Article/details/gtvqnhkafd.html

[E03] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gtqopmjhav.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.tanke756.top/Article/details/gtouwyzpxe.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtbnyjmzux.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cheryme.top/Article/details/gtpvhfmutv.html

TS:   s.slice(1, 4)
来源：http://dali.c1oappe.top/Article/details/gtujfxdqsq.html

Java: s.substring(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtwftjvkec.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbufsgys.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhongyouzk.top/Article/details/gtgfqweeld.html

C#:   s.Substring(1, 3)
来源：http://dali.chenzaomai.com/Article/details/gtrqhkhkjg.html

[E04] 查找子串位置
来源：http://dali.aibaodan.cn/Article/details/gtdoxoqnnv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jyoumei.cn/Article/details/gtmlmqmjlm.html

PHP:  strpos($s, "x");
来源：http://dali.daxiang520.top/Article/details/gtogjlqtrx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxeunrwav.html

TS:   s.indexOf("x")
来源：http://dali.jqgfzy.top/Article/details/gtaqyntquq.html

Java: s.indexOf("x")
来源：http://dali.yanxiufei.cn/Article/details/gtshbgcmje.html

Go:   strings.Index(s, "x")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvgpmonoc.html

Ruby: s.index("x")
来源：http://dali.redwolf501.top/Article/details/gtmatnjbib.html

C#:   s.IndexOf("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrsdtfdk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.vqdsnc.cn/Article/details/gtcrnlqimo.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.birdmap.top/Article/details/gtrhjgfwsp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.xuanzx.com/Article/details/gtpitpkerw.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shangyingyoupin.top/Article/details/gtacslbssl.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.guannengcc.top/Article/details/gtfmelfumw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.sufxvd.cn/Article/details/gtcbklinlf.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hywenlv.cn/Article/details/gtvqejacdf.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zdqjudy.top/Article/details/gtjraurzlf.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.yangfankeji.com/Article/details/gtcndjnioo.html

[E06] 替换子串
来源：http://dali.9152youxi.cn/Article/details/gttgnszggo.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.sufxvd.cn/Article/details/gtlrgrbubf.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.daria6918.cn/Article/details/gtnfihmbxi.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtxzmnkibk.html

TS:   s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtoakqljut.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.jiagoushi.top/Article/details/gtopnkfvrg.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.guannengcc.top/Article/details/gtshsmnfrx.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtwyharlcs.html

C#:   s.Replace("a", "b")
来源：http://dali.316326.xyz/Article/details/gtgxjnliiw.html

[E07] 按分隔符拆分
来源：http://dali.guowangkeji.top/Article/details/gtvkhaqvkg.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.gotoacloud.top/Article/details/gtqlxdaded.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.9152youxi.cn/Article/details/gtdtupusjv.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.havefunace.top/Article/details/gtzvcictru.html

TS:   s.split(",")
来源：http://dali.tanke756.top/Article/details/gtohsknjlr.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.svipenyu.cn/Article/details/gtavnnxqtd.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.yanxiufei.cn/Article/details/gtamtygfss.html

Ruby: s.split(",");  s.split
来源：http://dali.sufxvd.cn/Article/details/gtodzeumhv.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.snrcjt.cn/Article/details/gtrxeshzcy.html

[E08] 数组按分隔符合并
来源：http://dali.nwbrower.top/Article/details/gtlphebhil.html

Py:   ",".join(items)
来源：http://dali.zdqjudy.top/Article/details/gtkeuildjm.html

PHP:  implode(",", $items);
来源：http://dali.chenlongwang.top/Article/details/gtexheigch.html

JS:   items.join(",")
来源：http://dali.hfpthk.cn/Article/details/gtccxuyqcn.html

TS:   items.join(",")
来源：http://dali.chenjidiqi.icu/Article/details/gtfiohkamj.html

Java: String.join(",", items)
来源：http://dali.nanxinkj.top/Article/details/gtstmzscvw.html

Go:   strings.Join(items, ",")
来源：http://dali.sysykeji.top/Article/details/gtmancjpby.html

Ruby: items.join(",")
来源：http://dali.nanxuanxn.top/Article/details/gtasslibnu.html

C#:   string.Join(",", items)
来源：http://dali.c1oappe.top/Article/details/gtzyrsvgfz.html

[E09] 去除所有空白字符
来源：http://dali.yvedp.cn/Article/details/gtijibsmzl.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtbwvqvcaz.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fengsongda.top/Article/details/gtqmvixsis.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.zhengqikj.top/Article/details/gtdqwyuqkd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.jianghu66.top/Article/details/gtueoogrhw.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuapnymz.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxuanxn.top/Article/details/gtvfasihcd.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.vqdsnc.cn/Article/details/gttqkkxsha.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hfpthk.cn/Article/details/gtwqjltmav.html

[E10] 左侧补零 / 定长填充
来源：http://dali.ydzc1.top/Article/details/gtqamxlfbg.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtzzwrydjg.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.smart0.xyz/Article/details/gtgzhuchta.html

JS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtymkqdnic.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtcwjdahyc.html

Java: String.format("%03d", 7)
来源：http://dali.hongshengwenyu.top/Article/details/gtlwznzyla.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.xziqi.cn/Article/details/gtbgysfmhk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xuanzx.com/Article/details/gtrdfhynaq.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.dianchejie.cn/Article/details/gtywukvasz.html

[E11] 反转字符串
来源：http://dali.jiagoushi.top/Article/details/gtvpdcdgqy.html

Py:   s[::-1]
来源：http://dali.jianghu66.top/Article/details/gtdxvmaslg.html

PHP:  strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtxugylqsp.html

JS:   [...s].reverse().join("")
来源：http://dali.c1oappe.top/Article/details/gtglehzixk.html

TS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gtxdbqvfwr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.nanxinkj.top/Article/details/gteaacodzf.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.shangyingyoupin.top/Article/details/gtgpwngcrr.html

Ruby: s.reverse
来源：http://dali.iojbl.cn/Article/details/gtcpaqlbeo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.quarkkingdee.top/Article/details/gtelpolccd.html

[E12] 统计某字符出现次数
来源：http://dali.snrcjt.cn/Article/details/gtlrlktckk.html

Py:   s.count("a")
来源：http://dali.dashuyun.cn/Article/details/gtwnfmlyjc.html

PHP:  substr_count($s, "a");
来源：http://dali.gotoacloud.top/Article/details/gtrevyqegq.html

JS:   s.split("a").length - 1
来源：http://dali.chenzaomai.com/Article/details/gtdknxlgnq.html

TS:   s.split("a").length - 1
来源：http://dali.yonumen.top/Article/details/gtspideqtu.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.birdmap.top/Article/details/gtxnwpryhh.html

Go:   strings.Count(s, "a")
来源：http://dali.zhongyouzk.top/Article/details/gtripefqki.html

Ruby: s.count("a")
来源：http://dali.vqdsnc.cn/Article/details/gtjerkfndl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.sweek.top/Article/details/gtdfkmlcsk.html

[E13] 逐字符遍历
来源：http://dali.shzxlz.cn/Article/details/gtsamtxqmz.html

Py:   for ch in s: print(ch)
来源：http://dali.yueranfly.top/Article/details/gttrhzfuef.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.kuanghao11.cn/Article/details/gthroiewqi.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtlubgkdft.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xinyue.icu/Article/details/gtwoulxwag.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xylfe.cn/Article/details/gtnisvaplu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yuanzhike.top/Article/details/gtagxhoxcc.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.smart0.xyz/Article/details/gtrebcpuqr.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.cdnleiting.top/Article/details/gtbujixxcx.html

[E14] URL 编码与 Base64
来源：http://dali.ivvv.top/Article/details/gtnnstgwok.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuanzx.com/Article/details/gtwltesqcq.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.yj20258.top/Article/details/gtsyitbkxw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hywenlv.cn/Article/details/gtogskrfkv.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yj202588.top/Article/details/gtmltvnedg.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gtxoktwaxb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnnwseex.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cqqwz.cn/Article/details/gtizjxjsqx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yongpay.top/Article/details/gtjgjxupgi.html

[E15] HTML 转义 / 反转义
来源：http://dali.feifeiyinyue.top/Article/details/gtpefzfmff.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zdqjudy.top/Article/details/gtqhskoxfg.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shangyingyoupin.top/Article/details/gtutswpows.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xuanzx.com/Article/details/gtcfivsfqp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.svipenyu.cn/Article/details/gtsfdfqbvj.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ivvv.top/Article/details/gtzpezzncz.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.andypj.xyz/Article/details/gtjxuekqxl.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hfpthk.cn/Article/details/gtsvktufvf.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xuanzx.com/Article/details/gtdhqkccfa.html

[E16] 数字千分位
来源：http://dali.yj20258.top/Article/details/gthgmgwltw.html

Py:   f"{1234567:,}"
来源：http://dali.chenjidiqi.icu/Article/details/gtqoewhadf.html

PHP:  number_format(1234567);
来源：http://dali.snrcjt.cn/Article/details/gtrgdicrqt.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hnqzz.top/Article/details/gtxjokpeyh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hammf.cn/Article/details/gtkxjdiezp.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pycfn.com/Article/details/gtwizenxuu.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tianlin.xyz/Article/details/gtblfppbvx.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhengqikj.top/Article/details/gtmspdqgne.html

C#:   1234567.ToString("N0")
来源：http://dali.aibaodan.cn/Article/details/gtyyumoxvo.html

[E17] 首字母大写
来源：http://dali.tian-w.cn/Article/details/gtoxqkyzio.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yueranfly.top/Article/details/gtycxtsbzl.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztmunnsd.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cqqwz.cn/Article/details/gtyvodevoc.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yj20258888.top/Article/details/gttsckiwcc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkckyzvev.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zycfv.cn/Article/details/gtagzaokxa.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gtjsilyhcm.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jqgufenzy.top/Article/details/gtuhgkzxpa.html


<!-- 参考信息 -->