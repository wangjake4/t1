代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtropacodj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gotoacloud.top/Article/details/gtxtnuwmlp.html

Java: // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtlisncpri.html

Go:   // 无解构
来源：http://dali.xylfe.cn/Article/details/gtnwtiwwyk.html

Ruby: a, b = pair
来源：http://dali.aibaodan.cn/Article/details/gtncwaplem.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtidrczrtf.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gtslgzowwi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pycfn.com/Article/details/gtchcahiqn.html

PHP:  // 无重载
来源：http://dali.zdqjudy.top/Article/details/gtipewpdxn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gtjijraseb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhixingplan.top/Article/details/gtcvgpbral.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cdnleiting.top/Article/details/gtlzjjbykd.html

Go:   // 无重载：用不同函数名
来源：http://dali.bjfxy.top/Article/details/gtahagrnuo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sysykeji.top/Article/details/gtpdosiqny.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gtucltnulj.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfsjmbrdf.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gtsvlxapeu.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtuljvotlb.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gtwshomyhr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdirdhgz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdokauxzx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtgcygcijt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gtdluptjmq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhiwuduotai.top/Article/details/gtzqmnhopn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ivvv.top/Article/details/gtcuyggcym.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj202588.top/Article/details/gtsyqiacjo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuanzhike.top/Article/details/gtqywkuagv.html

[D02] 追加元素到末尾
来源：http://dali.jlsjyb.cn/Article/details/gtanxfbves.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgufenzy.top/Article/details/gttlbwobau.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.vqdsnc.cn/Article/details/gtaeerndrf.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtcsrrsaby.html

TS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtpsegdzuw.html

Java: list.add(4);
来源：http://dali.andypj.xyz/Article/details/gtfukahyul.html

Go:   arr = append(arr, 4)
来源：http://dali.birdmap.top/Article/details/gtlxkyjpof.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.quarkkingdee.top/Article/details/gtpzskdwjd.html

C#:   list.Add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtmunztadc.html

[D03] 在指定位置插入元素
来源：http://dali.hywenlv.cn/Article/details/gtpndcscny.html

Py:   arr.insert(0, 0)
来源：http://dali.yonumen.top/Article/details/gtmexcptba.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zycfv.cn/Article/details/gtovmkapff.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nanxinkj.top/Article/details/gtgxmulsrg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtyvjznqbd.html

Java: list.add(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtcctgfbff.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aizwys.cn/Article/details/gtqtgwhbrd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hysaishi.cn/Article/details/gtcqtyrdpt.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtdjdbkkbs.html

[D04] 删除元素
来源：http://dali.dianchejie.cn/Article/details/gtowtdbnvo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.iojbl.cn/Article/details/gtujkbigsm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sxryk.cn/Article/details/gtyowhithv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjmxrsyrn.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgufenzy.top/Article/details/gtwugqgymr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daxiang520.top/Article/details/gtckwcihhs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hysaishi.cn/Article/details/gtjarfujii.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pycfn.com/Article/details/gtcuvjclqe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fzhhl.top/Article/details/gthzkhsyia.html

[D05] 访问与修改元素
来源：http://dali.hnqzz.top/Article/details/gtwvobzlkn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtkcsxxzlp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gthuboncds.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtcxfjvjye.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cqqwz.cn/Article/details/gtkjifyzjg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.meibo888.top/Article/details/gtsfcvawma.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtbejbaepl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtwjjkfvym.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtppstekrw.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtlkcqdadl.html

Py:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gttfnwfnpw.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtxmryeech.html

JS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtivnbamkd.html

TS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gtmiidabol.html

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gtlyodutkr.html

Go:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gtvbycbvoj.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gtdoopbeww.html

C#:   list.Count;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlsoryiu.html

[D07] 切片 / 取子数组
来源：http://dali.ppjwa.cn/Article/details/gtvoygakip.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangtech.top/Article/details/gtldvexqvy.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daria6918.cn/Article/details/gtruewxrqc.html

JS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtzffbvjbw.html

TS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtusykbnmc.html

Java: list.subList(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzaceuuby.html

Go:   arr[1:4]
来源：http://dali.yongpay.top/Article/details/gtsnxwlrtn.html

Ruby: arr[1, 3]
来源：http://dali.shzxlz.cn/Article/details/gtlpxzkogh.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gtofwulxev.html

[D08] 合并两个数组
来源：http://dali.hammf.cn/Article/details/gtnokmoppq.html

Py:   a + b;  a.extend(b)
来源：http://dali.tianlin.xyz/Article/details/gtauzgords.html

PHP:  array_merge($a, $b);
来源：http://dali.yuanzhike.top/Article/details/gtsnflsbgq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhengqikj.top/Article/details/gtdakyxclu.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzflwlkb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tian-w.cn/Article/details/gtjuwsintt.html

Go:   append(a, b...)
来源：http://dali.xinyue.icu/Article/details/gtbilqcvzl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yvedp.cn/Article/details/gtxoknhxza.html

C#:   a.Concat(b).ToList()
来源：http://dali.yvedp.cn/Article/details/gtxetbitek.html

[D09] 排序（升序）
来源：http://dali.ppjwa.cn/Article/details/gtghsckqnn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gtwkfgupik.html

PHP:  sort($arr);
来源：http://dali.chenzaomai.com/Article/details/gtgrybjshh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hammf.cn/Article/details/gtihabsauu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daria6918.cn/Article/details/gtqiqegcvc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gtabsentsp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtndmxuans.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtxamcdwkd.html

C#:   list.Sort();
来源：http://dali.yj20258888.top/Article/details/gtqoujxyea.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258888.top/Article/details/gtrbeucihm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yj20258.top/Article/details/gtacshyrpn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gtwuzfnznb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gtlxghbvas.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhiwuduotai.top/Article/details/gtomiqgpbs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjkbmnem.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhiwuduotai.top/Article/details/gtplspwokr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.birdmap.top/Article/details/gtoxatmwxz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ybcxt.top/Article/details/gtrehzxqxc.html

[D11] 反转数组
来源：http://dali.jqgfzy.top/Article/details/gtgsscnifo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daxiang520.top/Article/details/gtgurmteep.html

PHP:  array_reverse($arr);
来源：http://dali.gotoacloud.top/Article/details/gtaafxeqgc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ehwqpu.com/Article/details/gtcadrcqzo.html

TS:   [...arr].reverse();
来源：http://dali.c1oappe.top/Article/details/gtwrrxnofd.html

Java: Collections.reverse(list);
来源：http://dali.wangdashe.top/Article/details/gteevnficf.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gthuwbxunj.html

Ruby: arr.reverse
来源：http://dali.ehwqpu.com/Article/details/gtetxmhtxn.html

C#:   list.Reverse();
来源：http://dali.nanxuanxn.top/Article/details/gtpftumkxw.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gtpcoiaxnr.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gtwryoptqf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yongpay.top/Article/details/gtghhxbwpe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gtqdrvpcgb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtbcwqonra.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cdnleiting.top/Article/details/gtindhumyx.html

Go:   slices.Index(arr, x)
来源：http://dali.yvedp.cn/Article/details/gteqwlwcvy.html

Ruby: arr.index(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtwooskwro.html

C#:   list.IndexOf(x);
来源：http://dali.guowangkeji.top/Article/details/gtldzxtvhr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.vqdsnc.cn/Article/details/gtjromtnks.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnqzz.top/Article/details/gtrfiwlefl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhongyouzk.top/Article/details/gtqlssnali.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tianlin.xyz/Article/details/gtcpliibka.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtocyrdksm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tian-w.cn/Article/details/gtdochqjbs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhengqikj.top/Article/details/gthyvrlpoc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.redwolf501.top/Article/details/gtjgpogdrk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jyoumei.cn/Article/details/gtqkepvlsi.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cheryme.top/Article/details/gttfnqroxf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hammf.cn/Article/details/gtutwzxghu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtfcgudavi.html

JS:   arr.map(x => x * 2)
来源：http://dali.daria6918.cn/Article/details/gtjbfrggwb.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtzrjnpvyf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ppjwa.cn/Article/details/gtlutsmywz.html

Go:   // 手写循环
来源：http://dali.sufxvd.cn/Article/details/gtjivshmae.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtfyngvyln.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtxtechywe.html

[D15] 去重
来源：http://dali.zhengqikj.top/Article/details/gtfccmbkoh.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gtjwtfzusd.html

PHP:  array_unique($arr);
来源：http://dali.jianghu66.top/Article/details/gtsberxzwg.html

JS:   [...new Set(arr)]
来源：http://dali.zhoulong.xyz/Article/details/gtqovtqhsp.html

TS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gtpenmyfwf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yonumen.top/Article/details/gtsdzsumri.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenzaomai.com/Article/details/gtaahkflak.html

Ruby: arr.uniq
来源：http://dali.yuxming.cn/Article/details/gtbbgzgczk.html

C#:   list.Distinct().ToList()
来源：http://dali.9152youxi.cn/Article/details/gtdpzgyajl.html

[D16] 求和与平均值
来源：http://dali.cqqwz.cn/Article/details/gtibasbmak.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nwbrower.top/Article/details/gtpyaxdqtf.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangdashe.top/Article/details/gtyalypaaf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gtacgqhjvn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtpgntcohf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.9152youxi.cn/Article/details/gtvdkhrlrx.html

Go:   // 手写循环累加
来源：http://dali.jqgufenzy.top/Article/details/gthkvmxhnh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtugfuhwbb.html

C#:   list.Sum();  list.Average()
来源：http://dali.cashguo.top/Article/details/gtwszwtbre.html

[D17] 最大值与最小值
来源：http://dali.jqgfzy.top/Article/details/gtyhfesoeq.html

Py:   max(arr);  min(arr)
来源：http://dali.yueranfly.top/Article/details/gtlvntxnnh.html

PHP:  max($arr);  min($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqoteruf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangdashe.top/Article/details/gtnszbeyby.html

TS:   Math.max(...arr);
来源：http://dali.yonumen.top/Article/details/gtdudwiqyv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.birdmap.top/Article/details/gtqajnvvdr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtfmyzcqjn.html

Ruby: arr.max;  arr.min
来源：http://dali.gogol.net.cn/Article/details/gtgcnrotwz.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258.top/Article/details/gtvpmobisu.html

[D18] 扁平化嵌套数组
来源：http://dali.birdmap.top/Article/details/gtvmxkljan.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.tanke756.top/Article/details/gtfyxfgnnq.html

PHP:  array_merge(...$nested);
来源：http://dali.ydzc1.top/Article/details/gtyivnjizr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.9152youxi.cn/Article/details/gtrmjqhjkp.html

TS:   nested.flat();
来源：http://dali.jlsjyb.cn/Article/details/gtvdxhtpez.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtvlnwmrkg.html

Go:   // 手写双层循环
来源：http://dali.sxryk.cn/Article/details/gtsczhbayp.html

Ruby: nested.flatten
来源：http://dali.vqdsnc.cn/Article/details/gtvntcgcix.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtpotycisr.html

[D19] 按字段分组
来源：http://dali.0kj1m.cn/Article/details/gtkziklsyc.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ivvv.top/Article/details/gtcpbvtrhg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnqzz.top/Article/details/gtqcmnnyzw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.bjfxy.top/Article/details/gtmzlicybu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gthexnphbo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhengqikj.top/Article/details/gtxlwmxzmd.html

Go:   // 手写 map[string][]T
来源：http://dali.hywenlv.cn/Article/details/gtutotahlx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zhoulong.xyz/Article/details/gtjzncsski.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ydzc1.top/Article/details/gtiddnfoox.html

[D20] 统计每个元素出现次数
来源：http://dali.sufxvd.cn/Article/details/gthcmhmiqr.html

Py:   Counter(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxhndufj.html

PHP:  array_count_values($arr);
来源：http://dali.gzhubu.top/Article/details/gtpaqkfiaa.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ydzc1.top/Article/details/gtwqanwqmm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xziqi.cn/Article/details/gtrsasnmew.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.chenlongwang.top/Article/details/gtkmubimpj.html

Go:   // 手写 map[T]int
来源：http://dali.guowangkeji.top/Article/details/gtdmkolank.html

Ruby: arr.tally
来源：http://dali.wangshuangyany.cn/Article/details/gtkrxsdnvq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.hnqzz.top/Article/details/gtymtfldua.html

[D21] 判断是否包含某元素
来源：http://dali.0kj1m.cn/Article/details/gtcvrdqhaz.html

Py:   x in arr
来源：http://dali.ppjwa.cn/Article/details/gtvhnqmdtm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.havefunace.top/Article/details/gtaizfwoox.html

JS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gtzfrmvigt.html

TS:   arr.includes(x)
来源：http://dali.yonumen.top/Article/details/gtkhxqpblo.html

Java: list.contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtufjozfej.html

Go:   slices.Contains(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtlfbbwxsk.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gtohhgtcmr.html

C#:   list.Contains(x)
来源：http://dali.yj202588.top/Article/details/gtcxqfqduz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gtgsqfiazf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jianghu66.top/Article/details/gthofacfjh.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.tanke756.top/Article/details/gtqbuwaomd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.cashguo.top/Article/details/gttizunscv.html

TS:   [...arr];
来源：http://dali.nanxinkj.top/Article/details/gtkzlskjnd.html

Java: new ArrayList<>(list);
来源：http://dali.jlsjyb.cn/Article/details/gtcfsoajvq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cheryme.top/Article/details/gtcvgypnmj.html

Ruby: arr.dup;  arr.clone
来源：http://dali.c1oappe.top/Article/details/gttulkdlhc.html

C#:   new List<int>(list);
来源：http://dali.tian-w.cn/Article/details/gtlznnglyv.html

[D23] reduce 累积计算
来源：http://dali.snrcjt.cn/Article/details/gtetgswobh.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnqzz.top/Article/details/gtatlkogsk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gtxguisunu.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtljorrxgq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtkvozwmfl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.zycfv.cn/Article/details/gteewijmqq.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwgzsexdd.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xziqi.cn/Article/details/gtxogmuduc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysdnoxbu.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhongyouzk.top/Article/details/gtsifgjtdv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gtazudgxcg.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ybcxt.top/Article/details/gtvbzdwemt.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigufen.top/Article/details/gtgmchwozw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtmqacjuvl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.hongshengwenyu.top/Article/details/gtlikujqgm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.feifeiyinyue.top/Article/details/gtjxzoczvr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.vqdsnc.cn/Article/details/gtockadwxq.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nanxuanxn.top/Article/details/gtkrygwidg.html

[D25] Set 集合去重与交并差
来源：http://dali.yj20258.top/Article/details/gtshthtljw.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.smart0.xyz/Article/details/gtieigeita.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangshuangyany.cn/Article/details/gtmwrtrdjd.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenlongwang.top/Article/details/gtugxstwmd.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fengsongda.top/Article/details/gtpdamgkjh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ehwqpu.com/Article/details/gttctncssl.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jqgfzy.top/Article/details/gtnprykcra.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtouzbgiws.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.mhx1999.top/Article/details/gtzcqjgttq.html

[D26] 数组转字符串
来源：http://dali.jinqigfzy.top/Article/details/gtgjktxjxu.html

Py:   ", ".join(map(str, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gthjkrvsef.html

PHP:  implode(", ", $arr);
来源：http://dali.havefunace.top/Article/details/gtcltbqupb.html

JS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gtsguioyhh.html

TS:   arr.join(", ")
来源：http://dali.redwolf501.top/Article/details/gtyuqwtkfb.html

Java: String.join(", ", list)
来源：http://dali.jqgfzy.top/Article/details/gtqcmaqihi.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guannengcc.top/Article/details/gtjkhugnnr.html

Ruby: arr.join(", ")
来源：http://dali.meibo888.top/Article/details/gtwjbqdvja.html

C#:   string.Join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gtsguqpqaj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtchiqhuxv.html

E. 字符串处理
来源：http://dali.wangshuangyany.cn/Article/details/gtjdfjtgsh.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtejcrodjr.html

[E01] 拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtknkkdliz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xziqi.cn/Article/details/gtboulgxjo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.xinyue.icu/Article/details/gtxyojmpaq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcjbdmzc.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gtebnkeiel.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.aibaodan.cn/Article/details/gtecvruqlb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.xinyue.icu/Article/details/gtmclcvndl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhongyouzk.top/Article/details/gtizqidmxi.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.hammf.cn/Article/details/gtvamutqmw.html

[E02] 重复字符串
来源：http://dali.ydzc1.top/Article/details/gthveyjwrx.html

Py:   "ab" * 3
来源：http://dali.ybcxt.top/Article/details/gtqyplyivp.html

PHP:  str_repeat("ab", 3);
来源：http://dali.guannengcc.top/Article/details/gtwzbvugeu.html

JS:   "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtwhukfiqy.html

TS:   "ab".repeat(3)
来源：http://dali.jyoumei.cn/Article/details/gtqfmwlsrs.html

Java: "ab".repeat(3)
来源：http://dali.daxiang520.top/Article/details/gtrxpmbldk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.aibaodan.cn/Article/details/gtvgpuehzb.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpolzcxiv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.iojbl.cn/Article/details/gtvsqfqeqh.html

[E03] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtsdhfirqs.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yanxiufei.cn/Article/details/gttxstjzdr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.sysykeji.top/Article/details/gtjqfjcutn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtvwxqhvex.html

TS:   s.slice(1, 4)
来源：http://dali.birdmap.top/Article/details/gteueofobk.html

Java: s.substring(1, 4)
来源：http://dali.sweek.top/Article/details/gtdvmsmvax.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jinqigfzy.top/Article/details/gtvcrwgumw.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hywenlv.cn/Article/details/gtxckkcrre.html

C#:   s.Substring(1, 3)
来源：http://dali.shzxlz.cn/Article/details/gtgttyqwwi.html

[E04] 查找子串位置
来源：http://dali.gogol.net.cn/Article/details/gthawxhztd.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xylfe.cn/Article/details/gtfgypryvo.html

PHP:  strpos($s, "x");
来源：http://dali.dianchejie.cn/Article/details/gtvmapfokj.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.havefunace.top/Article/details/gtgoznjugb.html

TS:   s.indexOf("x")
来源：http://dali.ivvv.top/Article/details/gtzeicqxza.html

Java: s.indexOf("x")
来源：http://dali.meibo888.top/Article/details/gtgwbagpcg.html

Go:   strings.Index(s, "x")
来源：http://dali.andypj.xyz/Article/details/gteouoquax.html

Ruby: s.index("x")
来源：http://dali.havefunace.top/Article/details/gtppitffbm.html

C#:   s.IndexOf("x")
来源：http://dali.yonumen.top/Article/details/gtrzcqfgpx.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.haohaochexian.top/Article/details/gtescvcdbc.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.dashuyun.cn/Article/details/gtgfplzsyt.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.havefunace.top/Article/details/gtaivubybv.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yuxming.cn/Article/details/gtlgorlcbc.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.cqqwz.cn/Article/details/gtqommfvxa.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.shanyushiyangtech.top/Article/details/gtncnnpqhh.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.c1oappe.top/Article/details/gtrhwyfyds.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.svipenyu.cn/Article/details/gtnncmnzot.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.mhx1999.top/Article/details/gtyptofzlb.html


<!-- 参考信息 -->