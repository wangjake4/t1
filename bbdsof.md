代发 wailian999

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtobmtpjjb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ydzc1.top/Article/details/gtlqmpzfhp.html

[D05] 访问与修改元素
来源：http://dali.bjfxy.top/Article/details/gtpsxecvre.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtucdkrtsw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtveopvzhv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtfsuyodrf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gtblagkeco.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ppjwa.cn/Article/details/gtiejthcwr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtgmpdwrrw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtizfgtcnz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sweek.top/Article/details/gtbrgcvqfk.html

[D06] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtcslpwlgr.html

Py:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gtsxfpxfjc.html

PHP:  count($arr);
来源：http://dali.zycfv.cn/Article/details/gtywxhvgte.html

JS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gthrsjzthi.html

TS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtydjqkats.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gtqwiyxysc.html

Go:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtvizuzamz.html

Ruby: arr.length; arr.size
来源：http://dali.jlsjyb.cn/Article/details/gthoyuipjt.html

C#:   list.Count;
来源：http://dali.nanxuanxn.top/Article/details/gttlksqxfi.html

[D07] 切片 / 取子数组
来源：http://dali.zhoulong.xyz/Article/details/gtfohwoohd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnqzz.top/Article/details/gtbftpjbsc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gzhubu.top/Article/details/gtcoxjbsjf.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtqkztmoew.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgcivqrw.html

Java: list.subList(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtzokgggcc.html

Go:   arr[1:4]
来源：http://dali.hysaishi.cn/Article/details/gtyfkjdxsh.html

Ruby: arr[1, 3]
来源：http://dali.redwolf501.top/Article/details/gtoxeiqftu.html

C#:   list.GetRange(1, 3);
来源：http://dali.ydzc1.top/Article/details/gtqmrytsuj.html

[D08] 合并两个数组
来源：http://dali.gotoacloud.top/Article/details/gtklsqpnir.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gtkfcjqjue.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtpptwpmba.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxuanxn.top/Article/details/gtanorynsv.html

TS:   [...a, ...b];
来源：http://dali.gotoacloud.top/Article/details/gtkrqdqgsv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cashguo.top/Article/details/gtpshayexq.html

Go:   append(a, b...)
来源：http://dali.cqqwz.cn/Article/details/gtvwxbqoxy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.316326.xyz/Article/details/gtphrwfsxd.html

C#:   a.Concat(b).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtuuvbtzxh.html

[D09] 排序（升序）
来源：http://dali.jinqigufen.top/Article/details/gtjeuwcnux.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jiagoushi.top/Article/details/gtpmxotofl.html

PHP:  sort($arr);
来源：http://dali.jqgfzy.top/Article/details/gtjxqmgcdq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258.top/Article/details/gtkkmwlmqf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yangfankeji.com/Article/details/gtrdoopzds.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuanzhike.top/Article/details/gtyujhdtxw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtcrqpzkxg.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gtzdxrjrxh.html

C#:   list.Sort();
来源：http://dali.yuanzhike.top/Article/details/gthiuroyfp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guowangkeji.top/Article/details/gtydxzdksq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gtkwsccfnk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtizxprdfz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gtfeqcvfci.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gtwmffmhuh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fengsongda.top/Article/details/gtzbnzpwfw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gtqudaynkn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnxiangtu.top/Article/details/gtkcdduvjp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhiwuduotai.top/Article/details/gtjisoooto.html

[D11] 反转数组
来源：http://dali.iojbl.cn/Article/details/gtbxspwlxg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhengqikj.top/Article/details/gtvjohnrnz.html

PHP:  array_reverse($arr);
来源：http://dali.wangdashe.top/Article/details/gtljmnuoot.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hfpthk.cn/Article/details/gtxhkejved.html

TS:   [...arr].reverse();
来源：http://dali.c1oappe.top/Article/details/gtkxxmchwv.html

Java: Collections.reverse(list);
来源：http://dali.nwbrower.top/Article/details/gtorhhikzd.html

Go:   slices.Reverse(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtgevrhpkw.html

Ruby: arr.reverse
来源：http://dali.hammf.cn/Article/details/gtojafdgea.html

C#:   list.Reverse();
来源：http://dali.shuidangran.top/Article/details/gtsictyamj.html

[D12] 查找元素下标
来源：http://dali.jqgfzy.top/Article/details/gtfquywasa.html

Py:   arr.index(x);  x in arr
来源：http://dali.cashguo.top/Article/details/gtjlmjgmwv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlobzwkic.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gthczzniwx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtljtpahol.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sweek.top/Article/details/gtxtgwxomf.html

Go:   slices.Index(arr, x)
来源：http://dali.9152youxi.cn/Article/details/gtuzsilfrs.html

Ruby: arr.index(x)
来源：http://dali.hysaishi.cn/Article/details/gtzjfshyzr.html

C#:   list.IndexOf(x);
来源：http://dali.gzhubu.top/Article/details/gtkibbayom.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gaohongyu789.top/Article/details/gtxxuqqjat.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtekjqxovb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuetiantiany.cn/Article/details/gteznbvefl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gtxedxswss.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtgakddomx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtdjgdygea.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sweek.top/Article/details/gtfskdiikm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gtrvzcknfm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtvfjkzook.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yangfankeji.com/Article/details/gtrnmakizo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgufenzy.top/Article/details/gtpswgnhor.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtbacoltjb.html

JS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gtzgnckqwx.html

TS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtpertxuhc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtvwhidpca.html

Go:   // 手写循环
来源：http://dali.jlsjyb.cn/Article/details/gtytcqxxkh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtlflhsudb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtybpkfmjo.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gtwviewnpk.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gtiqonxfgk.html

PHP:  array_unique($arr);
来源：http://dali.jianghu66.top/Article/details/gtyhjukyje.html

JS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtenbtdhhf.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtcysinbko.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yj20258.top/Article/details/gtdycyabql.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.iojbl.cn/Article/details/gtfzbjnyay.html

Ruby: arr.uniq
来源：http://dali.0kj1m.cn/Article/details/gtrybrcruz.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehcnyirh.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gtwnkovawd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtbgparrjf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jianghu66.top/Article/details/gtbfwiwclv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtljdhzuhl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtddbcehyl.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zdqjudy.top/Article/details/gtjlfnzzuy.html

Go:   // 手写循环累加
来源：http://dali.zhixingplan.top/Article/details/gtepafrdve.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gtsrlakvke.html

C#:   list.Sum();  list.Average()
来源：http://dali.sysykeji.top/Article/details/gtaonvkccj.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gtelehgjmf.html

Py:   max(arr);  min(arr)
来源：http://dali.yueranfly.top/Article/details/gtywylvvwy.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gtogphgutn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hammf.cn/Article/details/gtetgilmpr.html

TS:   Math.max(...arr);
来源：http://dali.yueranfly.top/Article/details/gtnxcoonna.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuanzhike.top/Article/details/gtxghqqsan.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258.top/Article/details/gtpmwjgsdz.html

Ruby: arr.max;  arr.min
来源：http://dali.ybcxt.top/Article/details/gtfcnidgch.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258.top/Article/details/gtlncpgzef.html

[D18] 扁平化嵌套数组
来源：http://dali.ehwqpu.com/Article/details/gtrqvloxzo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.birdmap.top/Article/details/gttgcmenas.html

PHP:  array_merge(...$nested);
来源：http://dali.c1oappe.top/Article/details/gtfvhkvkhr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ppjwa.cn/Article/details/gtoemrnico.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gtewyxpnni.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthzwwfimb.html

Go:   // 手写双层循环
来源：http://dali.vqdsnc.cn/Article/details/gtdarlxxbz.html

Ruby: nested.flatten
来源：http://dali.gaohongyu789.top/Article/details/gtykgpjyyf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.316326.xyz/Article/details/gtskzrsosu.html

[D19] 按字段分组
来源：http://dali.daxiang520.top/Article/details/gtuxnfwpkz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dianchejie.cn/Article/details/gtdhjtzghi.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gtsojdario.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhixingplan.top/Article/details/gtxhulvyqi.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtlazagkkj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daxiang520.top/Article/details/gtoknqbpbh.html

Go:   // 手写 map[string][]T
来源：http://dali.hysaishi.cn/Article/details/gtrcyvnowx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cucudq.cn/Article/details/gttaunhxxh.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.havefunace.top/Article/details/gthfexchry.html

[D20] 统计每个元素出现次数
来源：http://dali.hfpthk.cn/Article/details/gtvipagbxj.html

Py:   Counter(arr)
来源：http://dali.zycfv.cn/Article/details/gttqxttzrh.html

PHP:  array_count_values($arr);
来源：http://dali.mhx1999.top/Article/details/gtegyjzfcz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zdqjudy.top/Article/details/gtmtriaihq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.birdmap.top/Article/details/gtzgdcaaph.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgfzy.top/Article/details/gthnzusbhl.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbnaizfy.html

Ruby: arr.tally
来源：http://dali.wangdashe.top/Article/details/gtwfamcpkv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.andypj.xyz/Article/details/gtmivfwpys.html

[D21] 判断是否包含某元素
来源：http://dali.hywenlv.cn/Article/details/gtualezpaw.html

Py:   x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnztdgwq.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenlongwang.top/Article/details/gtomsdjusx.html

JS:   arr.includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtclrobfgk.html

TS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtcolpqvwz.html

Java: list.contains(x)
来源：http://dali.havefunace.top/Article/details/gtjjrvvjzp.html

Go:   slices.Contains(arr, x)
来源：http://dali.jianghu66.top/Article/details/gtahvkgirh.html

Ruby: arr.include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtpmgoikrd.html

C#:   list.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtqejupahw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgufenzy.top/Article/details/gtidvjxsxb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.mhx1999.top/Article/details/gtmjocyvdb.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.chenlongwang.top/Article/details/gtyqbzwylt.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.havefunace.top/Article/details/gtmtftgtlc.html

TS:   [...arr];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwiigwlgh.html

Java: new ArrayList<>(list);
来源：http://dali.jyoumei.cn/Article/details/gtmuvpfnos.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.chenzaomai.com/Article/details/gtbvwtsbmx.html

Ruby: arr.dup;  arr.clone
来源：http://dali.redwolf501.top/Article/details/gtiipxaocz.html

C#:   new List<int>(list);
来源：http://dali.chenzaomai.com/Article/details/gtlbuqjmip.html

[D23] reduce 累积计算
来源：http://dali.sweek.top/Article/details/gtkqwotytj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.bjfxy.top/Article/details/gtlpjzugpf.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtjraceqpq.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gtvftcwmol.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gtvdxhunbq.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jyoumei.cn/Article/details/gtqnkueimt.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gtcdaawdtq.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shuidangran.top/Article/details/gtpotaejsi.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nwbrower.top/Article/details/gtcrzvuqos.html

[D24] 字典 / Map 基本操作
来源：http://dali.redwolf501.top/Article/details/gtkgyiyjxi.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.shanyushiyangtech.top/Article/details/gtprppcuoe.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gzhubu.top/Article/details/gtgqsraktn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ybcxt.top/Article/details/gtjylhidgm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtzjxtmkoc.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hywenlv.cn/Article/details/gtputdgmsy.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhongyouzk.top/Article/details/gttdmdnbeq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.aibaodan.cn/Article/details/gtotlhkboi.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yonumen.top/Article/details/gtfbcwcpls.html

[D25] Set 集合去重与交并差
来源：http://dali.gaohongyu789.top/Article/details/gtjrcyjidx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.vqdsnc.cn/Article/details/gtdpwpayoc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.yuxming.cn/Article/details/gtixkkhcwl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cashguo.top/Article/details/gtlavbdbyr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenzaomai.com/Article/details/gtbxcllcpa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtudllmbrn.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.yvedp.cn/Article/details/gtycquhsgx.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjonxwexl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.wangshuangyany.cn/Article/details/gtjelsobin.html

[D26] 数组转字符串
来源：http://dali.meibo888.top/Article/details/gtreavpepj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtssynderc.html

PHP:  implode(", ", $arr);
来源：http://dali.gogol.net.cn/Article/details/gtelptixyo.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtipazdkmv.html

TS:   arr.join(", ")
来源：http://dali.jinqigfzy.top/Article/details/gtgxdwguul.html

Java: String.join(", ", list)
来源：http://dali.vqdsnc.cn/Article/details/gtmjejtdhv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.daria6918.cn/Article/details/gtmvauidyj.html

Ruby: arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtcwkfkagq.html

C#:   string.Join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gtcukmkysh.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtjyhwrrtu.html

E. 字符串处理
来源：http://dali.316326.xyz/Article/details/gtqhtfxczh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtsejfcsln.html

[E01] 拼接字符串
来源：http://dali.havefunace.top/Article/details/gtyjxlulba.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhixingplan.top/Article/details/gtbfuubqch.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fzhhl.top/Article/details/gtrpodtpop.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbaflitvn.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtzzeitprx.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.meibo888.top/Article/details/gtillebokm.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jyoumei.cn/Article/details/gtdwivldau.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.chenjidiqi.icu/Article/details/gtwtqpbjfv.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtgnwrmrip.html

[E02] 重复字符串
来源：http://dali.sxryk.cn/Article/details/gtggsomgny.html

Py:   "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gtwxbcedpf.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hysaishi.cn/Article/details/gtycxeklxv.html

JS:   "ab".repeat(3)
来源：http://dali.zdqjudy.top/Article/details/gtdrrzpeux.html

TS:   "ab".repeat(3)
来源：http://dali.zhongyouzk.top/Article/details/gtbhrdianj.html

Java: "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtktltaeul.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhixingplan.top/Article/details/gtvqklxxqn.html

Ruby: "ab" * 3
来源：http://dali.zycfv.cn/Article/details/gtrpctojbr.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.birdmap.top/Article/details/gtudnwdcca.html

[E03] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvkhjxjia.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ydzc1.top/Article/details/gtechjicln.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dashuyun.cn/Article/details/gtcfmqpjru.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.cdnleiting.top/Article/details/gtiandrids.html

TS:   s.slice(1, 4)
来源：http://dali.smart0.xyz/Article/details/gttnjdzjiy.html

Java: s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtcahimsmu.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtakimurge.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnnzrgde.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthopimccl.html

[E04] 查找子串位置
来源：http://dali.shuidangran.top/Article/details/gtpceoxzlk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tian-w.cn/Article/details/gtdawafxor.html

PHP:  strpos($s, "x");
来源：http://dali.smart0.xyz/Article/details/gtadzmynek.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgeuzcmnd.html

TS:   s.indexOf("x")
来源：http://dali.jyoumei.cn/Article/details/gthrnbxbiv.html

Java: s.indexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxyrtvre.html

Go:   strings.Index(s, "x")
来源：http://dali.meibo888.top/Article/details/gtiprujdam.html

Ruby: s.index("x")
来源：http://dali.yj20258888.top/Article/details/gtznoubgbc.html

C#:   s.IndexOf("x")
来源：http://dali.gogol.net.cn/Article/details/gtmmctrktq.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.tianlin.xyz/Article/details/gtombkaysd.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jianghu66.top/Article/details/gtablirogj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shanyushiyangtech.top/Article/details/gttjgcfemk.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtbhopdtkq.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.sufxvd.cn/Article/details/gtjxklaixj.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xziqi.cn/Article/details/gtejpicfcp.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.hnxiangtu.top/Article/details/gtktkyjqqs.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkirpubuw.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.kuanghao11.cn/Article/details/gtxycvorjz.html

[E06] 替换子串
来源：http://dali.gzhubu.top/Article/details/gtetiffnta.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.nwbrower.top/Article/details/gtskrcflwj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvoqjbhvw.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.9152youxi.cn/Article/details/gtajsnsylo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.gotoacloud.top/Article/details/gtbxwmnuwn.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gthfiohywe.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.0kj1m.cn/Article/details/gtacezxqrc.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gttbhphvha.html

C#:   s.Replace("a", "b")
来源：http://dali.tianlin.xyz/Article/details/gtudyuneyv.html

[E07] 按分隔符拆分
来源：http://dali.jyoumei.cn/Article/details/gtzlqnlhop.html

Py:   s.split(",");  s.split()      # 无参按任意空白拆
来源：http://dali.bjfxy.top/Article/details/gtuqzpuims.html

PHP:  explode(",", $s);  preg_split('/\s+/', $s);
来源：http://dali.xuanzx.com/Article/details/gtfypyyjgo.html

JS:   s.split(",");  s.split(/\s+/)
来源：http://dali.hammf.cn/Article/details/gtmiomwggr.html

TS:   s.split(",")
来源：http://dali.quarkkingdee.top/Article/details/gtkkfxmjvi.html

Java: s.split(",");  s.split("\\s+")
来源：http://dali.cucudq.cn/Article/details/gtjprpdwgb.html

Go:   strings.Split(s, ",");  strings.Fields(s)
来源：http://dali.nwbrower.top/Article/details/gtbuxgnwyr.html

Ruby: s.split(",");  s.split
来源：http://dali.hammf.cn/Article/details/gtiqlunaby.html

C#:   s.Split(',');  s.Split(new[] { ' ' }, StringSplitOptions.RemoveEmptyEntries)
来源：http://dali.meibo888.top/Article/details/gtmzebkias.html

[E08] 数组按分隔符合并
来源：http://dali.tian-w.cn/Article/details/gtiwwmvzzl.html

Py:   ",".join(items)
来源：http://dali.hfpthk.cn/Article/details/gtcaqfbxsp.html

PHP:  implode(",", $items);
来源：http://dali.chenzaomai.com/Article/details/gtdrdpqjdk.html

JS:   items.join(",")
来源：http://dali.mhx1999.top/Article/details/gtodzoxjvv.html

TS:   items.join(",")
来源：http://dali.birdmap.top/Article/details/gtvhqgoiwp.html

Java: String.join(",", items)
来源：http://dali.jianghu66.top/Article/details/gthsbrwfpm.html

Go:   strings.Join(items, ",")
来源：http://dali.jinqigfzy.top/Article/details/gtpppclvui.html

Ruby: items.join(",")
来源：http://dali.hnxiangtu.top/Article/details/gtkhjvpugn.html

C#:   string.Join(",", items)
来源：http://dali.gotoacloud.top/Article/details/gtxdzzfgcd.html

[E09] 去除所有空白字符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrekrpqs.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.tian-w.cn/Article/details/gtnthbegjt.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.jinqigufen.top/Article/details/gthnyficxa.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.cqqwz.cn/Article/details/gtchgfmsui.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.chenjidiqi.icu/Article/details/gthksyqdoz.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.feifeiyinyue.top/Article/details/gtlumuwmqw.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.ehwqpu.com/Article/details/gteceahyva.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.9152youxi.cn/Article/details/gtkhtvojpt.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jqgfzy.top/Article/details/gtcviqipcl.html

[E10] 左侧补零 / 定长填充
来源：http://dali.fzhhl.top/Article/details/gtwkfexxrz.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ppjwa.cn/Article/details/gtybybgqwy.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cdnleiting.top/Article/details/gthtnpasvl.html

JS:   "7".padStart(3, "0")
来源：http://dali.jinqigfzy.top/Article/details/gthuldiqdu.html

TS:   "7".padStart(3, "0")
来源：http://dali.gzhubu.top/Article/details/gtpcyinqnr.html

Java: String.format("%03d", 7)
来源：http://dali.zhengqikj.top/Article/details/gtwgeztpmj.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.9152youxi.cn/Article/details/gtezthsnzr.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.shzxlz.cn/Article/details/gthemeyhow.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.mhx1999.top/Article/details/gtwysvyetd.html

[E11] 反转字符串
来源：http://dali.shuidangran.top/Article/details/gtvmwgjaye.html

Py:   s[::-1]
来源：http://dali.yonumen.top/Article/details/gtjqtqxodf.html

PHP:  strrev($s);
来源：http://dali.wangdashe.top/Article/details/gtgbdezkdm.html

JS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtmivpufdj.html

TS:   [...s].reverse().join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdgredwp.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.kuanghao11.cn/Article/details/gtqocylbjv.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhiwuduotai.top/Article/details/gtjvnoyjnw.html


<!-- 参考信息 -->