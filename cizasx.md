代发 wailian999

PHP:  // 无重载
来源：http://dali.hammf.cn/Article/details/gtiimzqbjh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zycfv.cn/Article/details/gtuawfmlpo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dashuyun.cn/Article/details/gtclsfukpt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtguvsdlxw.html

Go:   // 无重载：用不同函数名
来源：http://dali.birdmap.top/Article/details/gtgizwiequ.html

Ruby: # 无重载：靠动态参数
来源：http://dali.meibo888.top/Article/details/gtcoehuxqa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqmgunmru.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtlxtgwqdi.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gtzhhwlujj.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtszqarhco.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gtjzsdezfb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jlsjyb.cn/Article/details/gthlrdoxza.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.mhx1999.top/Article/details/gtkthgbqrf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtdrpetinr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnqzz.top/Article/details/gtvlzthgyt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xinyue.icu/Article/details/gtiaelqvof.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fengsongda.top/Article/details/gtwxbnepyd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gtjnbgrbpq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gzhubu.top/Article/details/gtwublitys.html

[D02] 追加元素到末尾
来源：http://dali.zhengqikj.top/Article/details/gtglytenrm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daria6918.cn/Article/details/gtzxxkxdpw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daria6918.cn/Article/details/gtrduqkfzg.html

JS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsetdexas.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzzsiwxg.html

Java: list.add(4);
来源：http://dali.316326.xyz/Article/details/gthdbpnofh.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gtzoygcber.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cucudq.cn/Article/details/gtjllpdodb.html

C#:   list.Add(4);
来源：http://dali.gogol.net.cn/Article/details/gtjmnpwwhb.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258.top/Article/details/gthvsrdlun.html

Py:   arr.insert(0, 0)
来源：http://dali.cqqwz.cn/Article/details/gtrjbnpkti.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.snrcjt.cn/Article/details/gtzhordhrb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhiwuduotai.top/Article/details/gtwueekvao.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtusmafpew.html

Java: list.add(0, 0);
来源：http://dali.birdmap.top/Article/details/gtmftnhjkc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hywenlv.cn/Article/details/gtghupydmj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fzhhl.top/Article/details/gtsghlolot.html

C#:   list.Insert(0, 0);
来源：http://dali.hammf.cn/Article/details/gtlvwpdiaj.html

[D04] 删除元素
来源：http://dali.jiagoushi.top/Article/details/gtkqramivl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.9152youxi.cn/Article/details/gtdydqnupr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xziqi.cn/Article/details/gtdfzpborn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhengqikj.top/Article/details/gtmesuuuln.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtjmdsgxqv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yanxiufei.cn/Article/details/gtvvdhnaju.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.snrcjt.cn/Article/details/gtwivyolwj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yongpay.top/Article/details/gtmywydzbf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sufxvd.cn/Article/details/gtdppmfiga.html

[D05] 访问与修改元素
来源：http://dali.gogol.net.cn/Article/details/gtessovbnn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtlenyubpc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuvdujqp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtonwcgtxc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gtmvcocyws.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.haohaochexian.top/Article/details/gtxpummodu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtkwzcusyf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtgrpmzofu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtvxpablmy.html

[D06] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtejscqadz.html

Py:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtodkebaal.html

PHP:  count($arr);
来源：http://dali.sxryk.cn/Article/details/gtbdzpuldy.html

JS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gtxkpwboox.html

TS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtqjgyzryt.html

Java: list.size();
来源：http://dali.nanxuanxn.top/Article/details/gtoklmawyi.html

Go:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtqstjqqfs.html

Ruby: arr.length; arr.size
来源：http://dali.zhixingplan.top/Article/details/gtgkadkdcq.html

C#:   list.Count;
来源：http://dali.dashuyun.cn/Article/details/gtfhcxkqcx.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gtlihtwrys.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnxiangtu.top/Article/details/gtckrodjmi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtvgtbjgar.html

JS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtbacclbca.html

TS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppcfrfgo.html

Java: list.subList(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtcmolqlrj.html

Go:   arr[1:4]
来源：http://dali.ybcxt.top/Article/details/gtrvgyzela.html

Ruby: arr[1, 3]
来源：http://dali.mhx1999.top/Article/details/gtvtrcejmn.html

C#:   list.GetRange(1, 3);
来源：http://dali.cqqwz.cn/Article/details/gtjbgtlswv.html

[D08] 合并两个数组
来源：http://dali.dashuyun.cn/Article/details/gtcfquxszn.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxuanxn.top/Article/details/gtmdscrmhn.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjrkkaebf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258888.top/Article/details/gtnrspcrlf.html

TS:   [...a, ...b];
来源：http://dali.zhoulong.xyz/Article/details/gtrodyticn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.smart0.xyz/Article/details/gtpfsvfppn.html

Go:   append(a, b...)
来源：http://dali.sweek.top/Article/details/gtfvzmwzxe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daxiang520.top/Article/details/gtxcgaeigr.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtvqsqbrst.html

[D09] 排序（升序）
来源：http://dali.cheryme.top/Article/details/gtjphbqswz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daria6918.cn/Article/details/gtqrowhsps.html

PHP:  sort($arr);
来源：http://dali.gogol.net.cn/Article/details/gthumuvude.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuxming.cn/Article/details/gtohabikhy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jqgfzy.top/Article/details/gthbilkcgw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtfxiyli.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtvwhkpifw.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtzniywnbk.html

C#:   list.Sort();
来源：http://dali.hysaishi.cn/Article/details/gtarzzkmzx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gogol.net.cn/Article/details/gtpknbjkmb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gaohongyu789.top/Article/details/gtcqymijgn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fengsongda.top/Article/details/gtsdjayxrg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gthbmucxkq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gtxzwmfuix.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangdashe.top/Article/details/gthpizwkdx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuxming.cn/Article/details/gtfocyswvd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gtybqdfbdz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tianlin.xyz/Article/details/gtvwujmyyn.html

[D11] 反转数组
来源：http://dali.0kj1m.cn/Article/details/gtacesyglt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hongshengwenyu.top/Article/details/gttdenpgnc.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtgwiedass.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hongshengwenyu.top/Article/details/gtxiivkxzd.html

TS:   [...arr].reverse();
来源：http://dali.hywenlv.cn/Article/details/gtzczwzpwu.html

Java: Collections.reverse(list);
来源：http://dali.haohaochexian.top/Article/details/gtixgqwhxp.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gtpmmtygdi.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtzqpuzs.html

C#:   list.Reverse();
来源：http://dali.cucudq.cn/Article/details/gtmwiewelw.html

[D12] 查找元素下标
来源：http://dali.316326.xyz/Article/details/gtzcokruma.html

Py:   arr.index(x);  x in arr
来源：http://dali.dashuyun.cn/Article/details/gthdtohbho.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sweek.top/Article/details/gtsfbksrfa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gtvdwrlagi.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtulzmjwbh.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnqzz.top/Article/details/gtiyxkjbcy.html

Go:   slices.Index(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtktjqxbcc.html

Ruby: arr.index(x)
来源：http://dali.jinqigufen.top/Article/details/gtodtfbygx.html

C#:   list.IndexOf(x);
来源：http://dali.cucudq.cn/Article/details/gtqypjkxiy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.iojbl.cn/Article/details/gtqpftrswq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtrgapspkx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.9152youxi.cn/Article/details/gtqokzajdy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcesojezh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtpfaeneqp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.0kj1m.cn/Article/details/gtcnrbnsfx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jyoumei.cn/Article/details/gtccotouts.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.bjfxy.top/Article/details/gtdcakdqjd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtwxmaelhp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yonumen.top/Article/details/gtjreylxdw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gtsmcowxgl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hfpthk.cn/Article/details/gthljodbtt.html

JS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtcvruthti.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gthnscycbq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtrwrowkbn.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gtbogjmpus.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ydzc1.top/Article/details/gtakkhbrcx.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tianlin.xyz/Article/details/gtldvskbmn.html

[D15] 去重
来源：http://dali.cucudq.cn/Article/details/gthovghqxd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gtljwqjbkx.html

PHP:  array_unique($arr);
来源：http://dali.redwolf501.top/Article/details/gttahssdsg.html

JS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtonhggaxw.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gtgonaquvg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jyoumei.cn/Article/details/gtovevjync.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sysykeji.top/Article/details/gtcgkagbjt.html

Ruby: arr.uniq
来源：http://dali.dianchejie.cn/Article/details/gtvkiudvfw.html

C#:   list.Distinct().ToList()
来源：http://dali.sysykeji.top/Article/details/gtlmvjexju.html

[D16] 求和与平均值
来源：http://dali.meibo888.top/Article/details/gtlazkmvuf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gtadggvbxo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gtomkzkzpt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gtvrsfcqxr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtbqrurfls.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenjidiqi.icu/Article/details/gtfyfhpjhm.html

Go:   // 手写循环累加
来源：http://dali.zycfv.cn/Article/details/gtavnuqtcz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gtzvfrefbp.html

C#:   list.Sum();  list.Average()
来源：http://dali.tian-w.cn/Article/details/gtjhirrbym.html

[D17] 最大值与最小值
来源：http://dali.cucudq.cn/Article/details/gtmdiryjlj.html

Py:   max(arr);  min(arr)
来源：http://dali.yuxming.cn/Article/details/gtjecjlyhr.html

PHP:  max($arr);  min($arr);
来源：http://dali.hfpthk.cn/Article/details/gtylvrylph.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtnfynofjy.html

TS:   Math.max(...arr);
来源：http://dali.cheryme.top/Article/details/gtwinasohb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gtsvbauddb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtfdetqcug.html

Ruby: arr.max;  arr.min
来源：http://dali.wangdashe.top/Article/details/gtftrxtryl.html

C#:   list.Max();  list.Min()
来源：http://dali.zdqjudy.top/Article/details/gtkcgydjjg.html

[D18] 扁平化嵌套数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrzavmyu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gaohongyu789.top/Article/details/gtjakhzmkd.html

PHP:  array_merge(...$nested);
来源：http://dali.sysykeji.top/Article/details/gtlfftpvlk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gtzodrcxqz.html

TS:   nested.flat();
来源：http://dali.c1oappe.top/Article/details/gtxffvdnnf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.havefunace.top/Article/details/gtzmarpigr.html

Go:   // 手写双层循环
来源：http://dali.tianlin.xyz/Article/details/gtksbyzuxf.html

Ruby: nested.flatten
来源：http://dali.yvedp.cn/Article/details/gtmbmywqes.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yvedp.cn/Article/details/gtumwmencb.html

[D19] 按字段分组
来源：http://dali.nanxuanxn.top/Article/details/gtgkkfzffq.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shuidangran.top/Article/details/gtgslnxgnb.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ppjwa.cn/Article/details/gtuceolfbz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.shuidangran.top/Article/details/gtoyqpejer.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbwwhbxo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gtoctilsec.html

Go:   // 手写 map[string][]T
来源：http://dali.quarkkingdee.top/Article/details/gtafmdgepo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cucudq.cn/Article/details/gtekjujflv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jinqigufen.top/Article/details/gtwwaqabbl.html

[D20] 统计每个元素出现次数
来源：http://dali.yueranfly.top/Article/details/gtsaqkjwzj.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtqqxmrend.html

PHP:  array_count_values($arr);
来源：http://dali.sufxvd.cn/Article/details/gtncxpkoze.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhengqikj.top/Article/details/gtarrebxlc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gtweswfeqw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jlsjyb.cn/Article/details/gtkckfghrn.html

Go:   // 手写 map[T]int
来源：http://dali.jlsjyb.cn/Article/details/gtyyjgtsoz.html

Ruby: arr.tally
来源：http://dali.zhengqikj.top/Article/details/gtwgmqtpqu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.havefunace.top/Article/details/gtimfveuig.html

[D21] 判断是否包含某元素
来源：http://dali.hammf.cn/Article/details/gtdvxokmkq.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gtlrckeeis.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yj202588.top/Article/details/gtgrlrfaff.html

JS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gtpmhjcfgw.html

TS:   arr.includes(x)
来源：http://dali.sweek.top/Article/details/gtaojdtzhp.html

Java: list.contains(x)
来源：http://dali.pycfn.com/Article/details/gtfbyffoga.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtvuryqded.html

Ruby: arr.include?(x)
来源：http://dali.wangdashe.top/Article/details/gtwnybliba.html

C#:   list.Contains(x)
来源：http://dali.xylfe.cn/Article/details/gtdxygyxfc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.mhx1999.top/Article/details/gtuakfsqjh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhoulong.xyz/Article/details/gttlngnokn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigufen.top/Article/details/gtetqeymue.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gtxdxpwqtr.html

TS:   [...arr];
来源：http://dali.gaohongyu789.top/Article/details/gtsoqisbyg.html

Java: new ArrayList<>(list);
来源：http://dali.hysaishi.cn/Article/details/gtzcnmqnsb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.fengsongda.top/Article/details/gtrtuwtboh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258888.top/Article/details/gtfdvsifjn.html

C#:   new List<int>(list);
来源：http://dali.xuetiantiany.cn/Article/details/gtgktdhhrj.html

[D23] reduce 累积计算
来源：http://dali.zhoulong.xyz/Article/details/gtkhzhjnex.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtjorokitp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gtpcfjkyfs.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yonumen.top/Article/details/gtrfakeagu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.kuanghao11.cn/Article/details/gtvcgymezl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.wangdashe.top/Article/details/gtjragdzlg.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gtefraptar.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.aibaodan.cn/Article/details/gtkxijwuzn.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylhfxzbs.html

[D24] 字典 / Map 基本操作
来源：http://dali.tanke756.top/Article/details/gtpvojwusk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yvedp.cn/Article/details/gtyinqvofu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.wangdashe.top/Article/details/gtocxsxrsx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.hfpthk.cn/Article/details/gtubyzxkdv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtddjpqjwp.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.shangyingyoupin.top/Article/details/gtfiwpqiak.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shuidangran.top/Article/details/gtdxhhxozo.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258.top/Article/details/gtkaqzntno.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbnqbqkg.html

[D25] Set 集合去重与交并差
来源：http://dali.zhengqikj.top/Article/details/gtydejyndn.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.fzhhl.top/Article/details/gtelmdlhaa.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdznexuhb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.gogol.net.cn/Article/details/gtjjntxxnm.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.wangdashe.top/Article/details/gtmxwspfpe.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnskvqhqr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jiagoushi.top/Article/details/gtxlqqrnzm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.gotoacloud.top/Article/details/gtotfxmtiy.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenlongwang.top/Article/details/gtpqgysjyp.html

[D26] 数组转字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjzumtjb.html

Py:   ", ".join(map(str, arr))
来源：http://dali.andypj.xyz/Article/details/gtzfzwsttu.html

PHP:  implode(", ", $arr);
来源：http://dali.cashguo.top/Article/details/gtmfrzycxb.html

JS:   arr.join(", ")
来源：http://dali.sysykeji.top/Article/details/gthiiguszu.html

TS:   arr.join(", ")
来源：http://dali.jlsjyb.cn/Article/details/gtbxporuue.html

Java: String.join(", ", list)
来源：http://dali.zhengqikj.top/Article/details/gtgxhcvgzn.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xziqi.cn/Article/details/gtpxouclyt.html

Ruby: arr.join(", ")
来源：http://dali.yongpay.top/Article/details/gtnxpaqjpo.html

C#:   string.Join(", ", list)
来源：http://dali.sysykeji.top/Article/details/gtmcikayxp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtlyvcqzyv.html

E. 字符串处理
来源：http://dali.kuanghao11.cn/Article/details/gtqqsdltvq.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtplyixsfg.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtbtagzyfn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyiybhakz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hfpthk.cn/Article/details/gthbcflmto.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hnxiangtu.top/Article/details/gtdidloaqo.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigufen.top/Article/details/gtcwpafhze.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nwbrower.top/Article/details/gtsmjblxda.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xuetiantiany.cn/Article/details/gtvvwxlfdu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.aibaodan.cn/Article/details/gtcewkiohm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.aizwys.cn/Article/details/gtxmhpcgdp.html

[E02] 重复字符串
来源：http://dali.iojbl.cn/Article/details/gtkraszxbg.html

Py:   "ab" * 3
来源：http://dali.shanyushiyangtech.top/Article/details/gttuekdnko.html

PHP:  str_repeat("ab", 3);
来源：http://dali.dianchejie.cn/Article/details/gtcbouefwk.html

JS:   "ab".repeat(3)
来源：http://dali.nanxinkj.top/Article/details/gtwcwjkjqr.html

TS:   "ab".repeat(3)
来源：http://dali.hfpthk.cn/Article/details/gtppkqjqva.html

Java: "ab".repeat(3)
来源：http://dali.hywenlv.cn/Article/details/gtllmqrnxd.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.guowangkeji.top/Article/details/gttjbtitru.html

Ruby: "ab" * 3
来源：http://dali.birdmap.top/Article/details/gtdsedokic.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyykkdov.html

[E03] 截取子串
来源：http://dali.hongshengwenyu.top/Article/details/gtrtsgydjs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.ivvv.top/Article/details/gtjulcejho.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtmmdgntsb.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gtijqsxrxm.html

TS:   s.slice(1, 4)
来源：http://dali.ehwqpu.com/Article/details/gtgiouocqz.html

Java: s.substring(1, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gtyrafcamz.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.pycfn.com/Article/details/gtokiwnpdi.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.meibo888.top/Article/details/gtwrqvqhfy.html

C#:   s.Substring(1, 3)
来源：http://dali.quarkkingdee.top/Article/details/gtmemuatgy.html

[E04] 查找子串位置
来源：http://dali.yvedp.cn/Article/details/gtzyjrmqcy.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ybcxt.top/Article/details/gtbjoqmogm.html

PHP:  strpos($s, "x");
来源：http://dali.hammf.cn/Article/details/gthjaxchts.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhongyouzk.top/Article/details/gtqmhfjhzn.html

TS:   s.indexOf("x")
来源：http://dali.nwbrower.top/Article/details/gtlllnvimn.html

Java: s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gtiflaupsl.html

Go:   strings.Index(s, "x")
来源：http://dali.zhijiandao.cn/Article/details/gtfbljntwr.html

Ruby: s.index("x")
来源：http://dali.yanxiufei.cn/Article/details/gtbbodboai.html

C#:   s.IndexOf("x")
来源：http://dali.chenlongwang.top/Article/details/gtfjwdtxrs.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.pengpengdd.cyou/Article/details/gtcekechus.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.ybcxt.top/Article/details/gtjxghczom.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.pycfn.com/Article/details/gtbzfpgiur.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yonumen.top/Article/details/gtdexsxoci.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yangfankeji.com/Article/details/gtfuznibiv.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.cucudq.cn/Article/details/gttzxtjztk.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.sysykeji.top/Article/details/gtlxdpdpqn.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.zdqjudy.top/Article/details/gtpimzvamk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.jianghu66.top/Article/details/gtopmhwoko.html

[E06] 替换子串
来源：http://dali.smart0.xyz/Article/details/gtrrbahlvc.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.hnqzz.top/Article/details/gtyqevvpoj.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.gogol.net.cn/Article/details/gtnlfwtawj.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.vqdsnc.cn/Article/details/gtwykaxduo.html

TS:   s.replaceAll("a", "b")
来源：http://dali.zhijiandao.cn/Article/details/gtwgdprugx.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtscriwtmz.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtxxuzevzt.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.sweek.top/Article/details/gtfehlqgrt.html


<!-- 参考信息 -->