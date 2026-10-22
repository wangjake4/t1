代发 wailian999

TS:   [...arr].reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gturqavtdw.html

Java: Collections.reverse(list);
来源：http://dali.shangyingyoupin.top/Article/details/gtvzzmdaqx.html

Go:   slices.Reverse(arr)
来源：http://dali.yongpay.top/Article/details/gtrzeffywu.html

Ruby: arr.reverse
来源：http://dali.tian-w.cn/Article/details/gtgnnhxlor.html

C#:   list.Reverse();
来源：http://dali.nanxuanxn.top/Article/details/gtuqvighdx.html

[D12] 查找元素下标
来源：http://dali.daxiang520.top/Article/details/gtjpjjtiux.html

Py:   arr.index(x);  x in arr
来源：http://dali.birdmap.top/Article/details/gtriiegamm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cashguo.top/Article/details/gtrkizbqiw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtqozzfgda.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtyahiwtgd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.quarkkingdee.top/Article/details/gtxfllyuyc.html

Go:   slices.Index(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtzddbhkzl.html

Ruby: arr.index(x)
来源：http://dali.fengsongda.top/Article/details/gthlbkwmse.html

C#:   list.IndexOf(x);
来源：http://dali.cucudq.cn/Article/details/gtjwqktjuv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guowangkeji.top/Article/details/gtwdskxrxc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtcmqkqrkc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.andypj.xyz/Article/details/gtawvuhkmg.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtlxyghpis.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gtuhqwoyth.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ivvv.top/Article/details/gthayfomsl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hongshengwenyu.top/Article/details/gtuvrhciyt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.snrcjt.cn/Article/details/gtjbxshnvi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ybcxt.top/Article/details/gtwfrcnyuc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhixingplan.top/Article/details/gtwbjtmjgs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj202588.top/Article/details/gtjzvktrub.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.quarkkingdee.top/Article/details/gteooizxoo.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrwenpar.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnctmobjn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrhfdvch.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtmycvguui.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtqipiwtqu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.svipenyu.cn/Article/details/gteyhktmyb.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gtqdkxayhh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gtnpsomsrg.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtceygmuth.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtktnngeom.html

TS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtxzrszbji.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yvedp.cn/Article/details/gtmkdxsbud.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.haohaochexian.top/Article/details/gtavkzydox.html

Ruby: arr.uniq
来源：http://dali.shangyingyoupin.top/Article/details/gttesshzwz.html

C#:   list.Distinct().ToList()
来源：http://dali.hywenlv.cn/Article/details/gtytfdtopu.html

[D16] 求和与平均值
来源：http://dali.jianghu66.top/Article/details/gtxubzxjyq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.9152youxi.cn/Article/details/gtuzuypjfp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtxknjjuim.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtzaekcarp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gtdqckouuz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.tanke756.top/Article/details/gtinijybsb.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwilegqnb.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhlzcxho.html

C#:   list.Sum();  list.Average()
来源：http://dali.nanxinkj.top/Article/details/gtesfauxpv.html

[D17] 最大值与最小值
来源：http://dali.cashguo.top/Article/details/gtkuffghrv.html

Py:   max(arr);  min(arr)
来源：http://dali.cucudq.cn/Article/details/gtnedvpgrw.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gtpoljiyse.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cucudq.cn/Article/details/gtvekhzmyj.html

TS:   Math.max(...arr);
来源：http://dali.xuanzx.com/Article/details/gtakravkrg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuanzhike.top/Article/details/gtnfvwrgxq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xziqi.cn/Article/details/gtevkgegwj.html

Ruby: arr.max;  arr.min
来源：http://dali.yanxiufei.cn/Article/details/gtiyuptwgi.html

C#:   list.Max();  list.Min()
来源：http://dali.hywenlv.cn/Article/details/gthqluwtnt.html

[D18] 扁平化嵌套数组
来源：http://dali.shzxlz.cn/Article/details/gtlmimhjeh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.c1oappe.top/Article/details/gtxhhdzlxh.html

PHP:  array_merge(...$nested);
来源：http://dali.gotoacloud.top/Article/details/gtklhitcxp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.mhx1999.top/Article/details/gtaimxrfot.html

TS:   nested.flat();
来源：http://dali.mhx1999.top/Article/details/gtvxsicqhg.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtihktyjvv.html

Go:   // 手写双层循环
来源：http://dali.yuxming.cn/Article/details/gtqprnegfp.html

Ruby: nested.flatten
来源：http://dali.zhijiandao.cn/Article/details/gtqvnlnypa.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gtxyrdjoey.html

[D19] 按字段分组
来源：http://dali.zycfv.cn/Article/details/gtobpqxhkf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtgbfxshlj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pengpengdd.cyou/Article/details/gtuigpqcue.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daria6918.cn/Article/details/gtfgwpseks.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsynfmjv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hammf.cn/Article/details/gtbflwhpje.html

Go:   // 手写 map[string][]T
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgczypicq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xuanzx.com/Article/details/gtwulqvswy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jqgfzy.top/Article/details/gtteuroapc.html

[D20] 统计每个元素出现次数
来源：http://dali.andypj.xyz/Article/details/gtolmyupbh.html

Py:   Counter(arr)
来源：http://dali.guannengcc.top/Article/details/gtrjnquitg.html

PHP:  array_count_values($arr);
来源：http://dali.ivvv.top/Article/details/gtjybibyfi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gttytsgyrv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gtbgnzlcwq.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.0kj1m.cn/Article/details/gtqpmcnsum.html

Go:   // 手写 map[T]int
来源：http://dali.xylfe.cn/Article/details/gthijkdvug.html

Ruby: arr.tally
来源：http://dali.0kj1m.cn/Article/details/gtwbjnvzir.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.chenjidiqi.icu/Article/details/gtwaiexyar.html

[D21] 判断是否包含某元素
来源：http://dali.shanyushiyangtech.top/Article/details/gttxxgvezg.html

Py:   x in arr
来源：http://dali.yuanzhike.top/Article/details/gtmimaaiap.html

PHP:  in_array($x, $arr, true);
来源：http://dali.xuetiantiany.cn/Article/details/gtsaccqtle.html

JS:   arr.includes(x)
来源：http://dali.bjfxy.top/Article/details/gtbpubdynl.html

TS:   arr.includes(x)
来源：http://dali.fzhhl.top/Article/details/gtblfbelzs.html

Java: list.contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtndanigqf.html

Go:   slices.Contains(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclskepds.html

Ruby: arr.include?(x)
来源：http://dali.daxiang520.top/Article/details/gtihuygisk.html

C#:   list.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtnnyjsdwm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aizwys.cn/Article/details/gtggwgzqjg.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtgmlsniiy.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.wangdashe.top/Article/details/gteqzjcfaz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zycfv.cn/Article/details/gtmvkgadlr.html

TS:   [...arr];
来源：http://dali.meibo888.top/Article/details/gtmzaakzxh.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gtwcjnbtfc.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shzxlz.cn/Article/details/gtkjuptfdk.html

Ruby: arr.dup;  arr.clone
来源：http://dali.feifeiyinyue.top/Article/details/gtpjodqmib.html

C#:   new List<int>(list);
来源：http://dali.jqgfzy.top/Article/details/gtktzobcjb.html

[D23] reduce 累积计算
来源：http://dali.aibaodan.cn/Article/details/gtslxaxswc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yuxming.cn/Article/details/gtrwjicnnz.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ybcxt.top/Article/details/gtyhpvmfnx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hywenlv.cn/Article/details/gtjoqvrbwk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yj20258.top/Article/details/gtbexkawlb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.hongshengwenyu.top/Article/details/gtlnumlyme.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gteqkfegov.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hywenlv.cn/Article/details/gthbjvxzcd.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.chenjidiqi.icu/Article/details/gtcllvytit.html

[D24] 字典 / Map 基本操作
来源：http://dali.meibo888.top/Article/details/gtzvgxmqrv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.gogol.net.cn/Article/details/gtxeiconbd.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.chenzaomai.com/Article/details/gtxfjetnse.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtkkjkgm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtcduvyksc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtoqajhonn.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xinyue.icu/Article/details/gtdkfxiwhn.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtkebzbhfz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xuetiantiany.cn/Article/details/gtghiyclkf.html

[D25] Set 集合去重与交并差
来源：http://dali.xziqi.cn/Article/details/gtkzdktdvk.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gtilguhpwz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafwhxyix.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dianchejie.cn/Article/details/gtdtlzvjjj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxfgrnow.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.snrcjt.cn/Article/details/gthdlephnz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xziqi.cn/Article/details/gtlydygqdz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpxkwuqk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepeyvowz.html

[D26] 数组转字符串
来源：http://dali.bjfxy.top/Article/details/gtsevtsilg.html

Py:   ", ".join(map(str, arr))
来源：http://dali.havefunace.top/Article/details/gtbszebqgr.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtdqhufrob.html

JS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gtntbhquun.html

TS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gtsjxdrlgh.html

Java: String.join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gtreiufhjh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.zhongyouzk.top/Article/details/gtpbodbubl.html

Ruby: arr.join(", ")
来源：http://dali.zhijiandao.cn/Article/details/gtgucabbzr.html

C#:   string.Join(", ", list)
来源：http://dali.yj20258.top/Article/details/gtaxdsjujb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtjqxfxpot.html

E. 字符串处理
来源：http://dali.cdnleiting.top/Article/details/gtxwrhttxn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtpzxekyos.html

[E01] 拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtwxhwvhox.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.nanxuanxn.top/Article/details/gtpgaonpwt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.redwolf501.top/Article/details/gtloeviljn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtlmzccqiy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cashguo.top/Article/details/gthkaeduvd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xylfe.cn/Article/details/gtzdcxisky.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhijiandao.cn/Article/details/gtmsowysck.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvlejkuq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.0kj1m.cn/Article/details/gtlnvwfqmp.html

[E02] 重复字符串
来源：http://dali.sxryk.cn/Article/details/gtlhhamtjb.html

Py:   "ab" * 3
来源：http://dali.jinqigufen.top/Article/details/gtjgvimfft.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhongyouzk.top/Article/details/gtaandzwah.html

JS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtaizfcore.html

TS:   "ab".repeat(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtpypbjvfc.html

Java: "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gtokkhglfy.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aizwys.cn/Article/details/gtwgmycaeq.html

Ruby: "ab" * 3
来源：http://dali.chenjidiqi.icu/Article/details/gtcciygmws.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gtyizqheoa.html

[E03] 截取子串
来源：http://dali.nanxinkj.top/Article/details/gtryunpbfn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ywan-chungtsiang.top/Article/details/gttedqrkmb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.nwbrower.top/Article/details/gtoullkzcl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gtcsczkbuq.html

TS:   s.slice(1, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtdpowawgw.html

Java: s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtmztoijma.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ivvv.top/Article/details/gtqcbdqpht.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hywenlv.cn/Article/details/gtykorrcdp.html

C#:   s.Substring(1, 3)
来源：http://dali.yonumen.top/Article/details/gtwssczflu.html

[E04] 查找子串位置
来源：http://dali.yj20258888.top/Article/details/gtboiioflr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtliavkwey.html

PHP:  strpos($s, "x");
来源：http://dali.fengsongda.top/Article/details/gtqtxrbgnn.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxuanxn.top/Article/details/gtqfmrjpwh.html

TS:   s.indexOf("x")
来源：http://dali.dianchejie.cn/Article/details/gtfuaunjch.html

Java: s.indexOf("x")
来源：http://dali.yj20258.top/Article/details/gtindhnzhc.html

Go:   strings.Index(s, "x")
来源：http://dali.yj20258.top/Article/details/gtcdspemth.html

Ruby: s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gtqrppbuzv.html

C#:   s.IndexOf("x")
来源：http://dali.yj202588.top/Article/details/gteuasfufj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgfzy.top/Article/details/gtaczxcjog.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.shzxlz.cn/Article/details/gtzksokuzd.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.cqqwz.cn/Article/details/gtvicfjnog.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jyoumei.cn/Article/details/gttxvbehlx.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gotoacloud.top/Article/details/gtbmafbjvw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtwnpelwoa.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.quarkkingdee.top/Article/details/gtnpzjaqao.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.jyoumei.cn/Article/details/gtmcrhqpbo.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.gzhubu.top/Article/details/gtivkwgzvc.html

[E06] 替换子串
来源：http://dali.fzhhl.top/Article/details/gtggjdgkgh.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.yangfankeji.com/Article/details/gthxgwafqb.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwdjgxbt.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gogol.net.cn/Article/details/gtgbjlklwi.html

TS:   s.replaceAll("a", "b")
来源：http://dali.ivvv.top/Article/details/gtgmsdisae.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.gzhubu.top/Article/details/gtftmgcxeo.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.c1oappe.top/Article/details/gtzepywkbj.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.cqqwz.cn/Article/details/gtzezquyjg.html

C#:   s.Replace("a", "b")
来源：http://dali.meibo888.top/Article/details/gtkjjlxsgr.html

[E07] 按分隔符拆分
来源：http://dali.fzhhl.top/Article/details/gtpuqergqr.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.birdmap.top/Article/details/gtzdmgwosh.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xinyue.icu/Article/details/gtgxyibkwr.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.cucudq.cn/Article/details/gtofwnebee.html

TS:   s.split(",")
来源：http://dali.svipenyu.cn/Article/details/gtbqibtphq.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.vqdsnc.cn/Article/details/gtklasksfo.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.bjfxy.top/Article/details/gtqolgovku.html

Ruby: s.split(",");  s.split
来源：http://dali.pengpengdd.cyou/Article/details/gtyymvjprs.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.daxiang520.top/Article/details/gtnvlvunkw.html

[E08] 数组按分隔符合并
来源：http://dali.smart0.xyz/Article/details/gtelkkjmbk.html

Py:   ",".join(items)
来源：http://dali.xuetiantiany.cn/Article/details/gtbjgntuqk.html

PHP:  implode(",", $items);
来源：http://dali.yvedp.cn/Article/details/gtfxtqyyly.html

JS:   items.join(",")
来源：http://dali.gaohongyu789.top/Article/details/gtvxwyypny.html

TS:   items.join(",")
来源：http://dali.sweek.top/Article/details/gthurutcxd.html

Java: String.join(",", items)
来源：http://dali.shangyingyoupin.top/Article/details/gtdtfmkevt.html

Go:   strings.Join(items, ",")
来源：http://dali.316326.xyz/Article/details/gtkmquglvk.html

Ruby: items.join(",")
来源：http://dali.yangfankeji.com/Article/details/gtvzjxxgod.html

C#:   string.Join(",", items)
来源：http://dali.xuetiantiany.cn/Article/details/gtxwhksyck.html

[E09] 去除所有空白字符
来源：http://dali.cucudq.cn/Article/details/gtxjomicgs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxgtqhok.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.sxryk.cn/Article/details/gtxczpdxec.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jinqigfzy.top/Article/details/gtmrsjirbp.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258.top/Article/details/gtiixhdgnp.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yj202588.top/Article/details/gtoflumdjm.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdhzksma.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.jqgfzy.top/Article/details/gtcetwpfxe.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.xylfe.cn/Article/details/gtoxddttnf.html

[E10] 左侧补零 / 定长填充
来源：http://dali.tanke756.top/Article/details/gtyytapcfh.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.sweek.top/Article/details/gtrcfswckb.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.shzxlz.cn/Article/details/gthbythvij.html

JS:   "7".padStart(3, "0")
来源：http://dali.yj202588.top/Article/details/gtrftoarcn.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtdalyjjsn.html

Java: String.format("%03d", 7)
来源：http://dali.yj20258888.top/Article/details/gtpzvlhcnh.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmjkyxcl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.jinqigufen.top/Article/details/gtvirzcrdj.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yj202588.top/Article/details/gthnhecddb.html

[E11] 反转字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtkrojmktp.html

Py:   s[::-1]
来源：http://dali.hammf.cn/Article/details/gtvhkiqtco.html

PHP:  strrev($s);
来源：http://dali.aibaodan.cn/Article/details/gtqetllgwr.html

JS:   [...s].reverse().join("")
来源：http://dali.nanxinkj.top/Article/details/gtnjambapx.html

TS:   [...s].reverse().join("")
来源：http://dali.316326.xyz/Article/details/gtskzbqaed.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.haohaochexian.top/Article/details/gtmucybucy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.wangdashe.top/Article/details/gthzpxbjkx.html

Ruby: s.reverse
来源：http://dali.snrcjt.cn/Article/details/gtkldtznuk.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucdxtvsc.html

[E12] 统计某字符出现次数
来源：http://dali.sufxvd.cn/Article/details/gtaejqlnpj.html

Py:   s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gtfircedbz.html

PHP:  substr_count($s, "a");
来源：http://dali.haohaochexian.top/Article/details/gtgnmkyvcp.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gtwbterklr.html

TS:   s.split("a").length - 1
来源：http://dali.fengsongda.top/Article/details/gtyhahdhdw.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gtljtvsahd.html

Go:   strings.Count(s, "a")
来源：http://dali.fzhhl.top/Article/details/gtqoxwleid.html

Ruby: s.count("a")
来源：http://dali.mhx1999.top/Article/details/gtprnriskr.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenzaomai.com/Article/details/gtecexaztn.html

[E13] 逐字符遍历
来源：http://dali.zhongyouzk.top/Article/details/gtohwfkzcf.html

Py:   for ch in s: print(ch)
来源：http://dali.shuidangran.top/Article/details/gtiilgsoat.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gotoacloud.top/Article/details/gtxjrhgpek.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sufxvd.cn/Article/details/gtcneovkiw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sysykeji.top/Article/details/gthpwliudf.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.aizwys.cn/Article/details/gtxihoiynj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xylfe.cn/Article/details/gtnouwwjqo.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xziqi.cn/Article/details/gtscpbukgi.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.dashuyun.cn/Article/details/gttalimtis.html

[E14] URL 编码与 Base64
来源：http://dali.zhengqikj.top/Article/details/gtwrebfrpx.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.yonumen.top/Article/details/gtvpfuwrex.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.cdnleiting.top/Article/details/gtoaliwzvc.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.tianlin.xyz/Article/details/gtfpxlsjod.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.jqgufenzy.top/Article/details/gticyrbwnr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yvedp.cn/Article/details/gtbofrxqzs.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.redwolf501.top/Article/details/gtrkvfkahb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.gotoacloud.top/Article/details/gtjljljvgx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.ybcxt.top/Article/details/gtulaogrpg.html

[E15] HTML 转义 / 反转义
来源：http://dali.smart0.xyz/Article/details/gtgohdrgse.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtvqinhgle.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.cashguo.top/Article/details/gtmqqexnxu.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gtyrwgaqmf.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yanxiufei.cn/Article/details/gtdizdildn.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cucudq.cn/Article/details/gtwwgfxkul.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gttscrucuo.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gtvlftzawa.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.smart0.xyz/Article/details/gtojiwnhtq.html

[E16] 数字千分位
来源：http://dali.zhengqikj.top/Article/details/gtsdiphwhn.html

Py:   f"{1234567:,}"
来源：http://dali.cdnleiting.top/Article/details/gtauebsxjv.html

PHP:  number_format(1234567);
来源：http://dali.xziqi.cn/Article/details/gttkmrabia.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhixingplan.top/Article/details/gtiykesrbn.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.jlsjyb.cn/Article/details/gtwmvvpktl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hammf.cn/Article/details/gtgcxwnkok.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.snrcjt.cn/Article/details/gtybwhpajq.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgufenzy.top/Article/details/gtxvjwgbbj.html

C#:   1234567.ToString("N0")
来源：http://dali.hammf.cn/Article/details/gtmmpudurp.html

[E17] 首字母大写
来源：http://dali.wangshuangyany.cn/Article/details/gtjzdvvmku.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.bjfxy.top/Article/details/gtpcswikxb.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yonumen.top/Article/details/gtzcwtljtg.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nanxuanxn.top/Article/details/gtxniicrjp.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.gogol.net.cn/Article/details/gtxkdbnqeq.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.guannengcc.top/Article/details/gtnxfannrw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xuanzx.com/Article/details/gtsdmkipct.html

Ruby: s.capitalize
来源：http://dali.yueranfly.top/Article/details/gtbbilayor.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.gzhubu.top/Article/details/gtwvpthnih.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdnbxhjr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hongshengwenyu.top/Article/details/gtwhgxtfor.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.gaohongyu789.top/Article/details/gtohsowcxc.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.pengpengdd.cyou/Article/details/gtherybbom.html


<!-- 参考信息 -->