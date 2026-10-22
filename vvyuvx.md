代发 wailian999

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gtpuccfxqj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dashuyun.cn/Article/details/gtdaopevfu.html

Java: // 无解构
来源：http://dali.yj20258.top/Article/details/gtattrbrfp.html

Go:   // 无解构
来源：http://dali.fzhhl.top/Article/details/gtrgpfmwym.html

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gtvhxcsyfo.html

C#:   var (a, b) = pair;
来源：http://dali.gzhubu.top/Article/details/gtfizdpocy.html

[C16] 函数 / 方法重载
来源：http://dali.guowangkeji.top/Article/details/gtdnujdyut.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zycfv.cn/Article/details/gtisojwguj.html

PHP:  // 无重载
来源：http://dali.sysykeji.top/Article/details/gtjylxdgrq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ppjwa.cn/Article/details/gttzqjgyre.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.c1oappe.top/Article/details/gttjbobfjf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guowangkeji.top/Article/details/gtiyixmbdb.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258888.top/Article/details/gtknmddmhy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangdashe.top/Article/details/gtddlwftmp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbatessj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtjmhktmds.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gtubmpjynn.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbnjoyahu.html

[D01] 创建数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gtoqcrivdh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hfpthk.cn/Article/details/gtwinudpkt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdznltjx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtoqcgvvid.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhiwuduotai.top/Article/details/gtffmrwsdi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenjidiqi.icu/Article/details/gtaivckacj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aizwys.cn/Article/details/gtjvguhsjc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenzaomai.com/Article/details/gtiygqyxrt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yangfankeji.com/Article/details/gtsheneuwb.html

[D02] 追加元素到末尾
来源：http://dali.0kj1m.cn/Article/details/gtdflquddk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gtyojjrbms.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtanqrgyzo.html

JS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gtjomojygn.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtxzqqzicf.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gtzltjvbou.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gtugwjxpls.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.haohaochexian.top/Article/details/gtswfgiyts.html

C#:   list.Add(4);
来源：http://dali.sweek.top/Article/details/gtifzaakzu.html

[D03] 在指定位置插入元素
来源：http://dali.gzhubu.top/Article/details/gtftsdtseh.html

Py:   arr.insert(0, 0)
来源：http://dali.jianghu66.top/Article/details/gtcbvhkpwg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhixingplan.top/Article/details/gtyrfvebhd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gotoacloud.top/Article/details/gtpittlmev.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtxwyugati.html

Java: list.add(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gteytlsckc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yueranfly.top/Article/details/gtasgolgyq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ppjwa.cn/Article/details/gtmvdjoprt.html

C#:   list.Insert(0, 0);
来源：http://dali.havefunace.top/Article/details/gtaflrrkrb.html

[D04] 删除元素
来源：http://dali.316326.xyz/Article/details/gtpifpdqcw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtpuoekqnw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucnvfhex.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangdashe.top/Article/details/gtywqmumso.html

TS:   arr.splice(0, 1);
来源：http://dali.gzhubu.top/Article/details/gtmqcwxqbg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guannengcc.top/Article/details/gtfpthdexl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hywenlv.cn/Article/details/gtehjervua.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtciktibqy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gzhubu.top/Article/details/gtlpwuqfeu.html

[D05] 访问与修改元素
来源：http://dali.yuanzhike.top/Article/details/gtwhqujhdk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtwrknlzre.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtbsxjmmnu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtyvwzhlts.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gzhubu.top/Article/details/gtswxrarcd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenjidiqi.icu/Article/details/gtjudaovxd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtgjqqqdpx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtqcfurpmn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtstjwacjy.html

[D06] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtelcznaye.html

Py:   len(arr)
来源：http://dali.cheryme.top/Article/details/gtxdzkhmis.html

PHP:  count($arr);
来源：http://dali.bjfxy.top/Article/details/gtxryoxuko.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtatjhzgjr.html

TS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gtylpypupu.html

Java: list.size();
来源：http://dali.guannengcc.top/Article/details/gtbmhwdqrs.html

Go:   len(arr)
来源：http://dali.yj20258888.top/Article/details/gtaclsbxra.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gthjlqximi.html

C#:   list.Count;
来源：http://dali.sweek.top/Article/details/gtdyuywdsv.html

[D07] 切片 / 取子数组
来源：http://dali.tianlin.xyz/Article/details/gtatfgzqsi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gzhubu.top/Article/details/gtcdahkkua.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtbghsycih.html

JS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtxewtnots.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gtdbssjqad.html

Java: list.subList(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtjezqeasp.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gtbjfgtkke.html

Ruby: arr[1, 3]
来源：http://dali.nanxinkj.top/Article/details/gtbmflymdm.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtuqbgnqht.html

[D08] 合并两个数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtevknjeet.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gtkbbikyww.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxinkj.top/Article/details/gtvczmggba.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenjidiqi.icu/Article/details/gtgerofkjl.html

TS:   [...a, ...b];
来源：http://dali.fengsongda.top/Article/details/gtdpojhwtt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cucudq.cn/Article/details/gttugpzaea.html

Go:   append(a, b...)
来源：http://dali.vqdsnc.cn/Article/details/gthfnnfcda.html

Ruby: a + b;  a.concat(b)
来源：http://dali.iojbl.cn/Article/details/gtmqlhjkqt.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtlyolvvly.html

[D09] 排序（升序）
来源：http://dali.hongshengwenyu.top/Article/details/gtdqwmouju.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtegbhvpch.html

PHP:  sort($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtcopjdzlp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfkxjfas.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gtvmuuyzey.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gtprbsvmso.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhoulong.xyz/Article/details/gttsyfhivj.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhievldf.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gtimgllvgq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.smart0.xyz/Article/details/gtmdjoekyd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.svipenyu.cn/Article/details/gtxfbyvlka.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gtratrngxe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtfxxfmypl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtdbadedwp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.bjfxy.top/Article/details/gtmvugnzrq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhongyouzk.top/Article/details/gtpryjthdy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyljlodow.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daxiang520.top/Article/details/gtejgmpovo.html

[D11] 反转数组
来源：http://dali.xuetiantiany.cn/Article/details/gtmppbfxon.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guowangkeji.top/Article/details/gtzfivtmwg.html

PHP:  array_reverse($arr);
来源：http://dali.sxryk.cn/Article/details/gtazxpffrh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guowangkeji.top/Article/details/gtfeufttfd.html

TS:   [...arr].reverse();
来源：http://dali.hysaishi.cn/Article/details/gtrxjaykuc.html

Java: Collections.reverse(list);
来源：http://dali.cucudq.cn/Article/details/gtperdxhjv.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtgczgkofn.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbswmxtu.html

C#:   list.Reverse();
来源：http://dali.jianghu66.top/Article/details/gtlngufpeu.html

[D12] 查找元素下标
来源：http://dali.xuanzx.com/Article/details/gtbbcdhdfu.html

Py:   arr.index(x);  x in arr
来源：http://dali.316326.xyz/Article/details/gtavowqnrd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guannengcc.top/Article/details/gtbhhderrp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtuvbuqrdv.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.svipenyu.cn/Article/details/gtesnvclam.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.bjfxy.top/Article/details/gtqxwralxv.html

Go:   slices.Index(arr, x)
来源：http://dali.meibo888.top/Article/details/gtkrexwavq.html

Ruby: arr.index(x)
来源：http://dali.zhongyouzk.top/Article/details/gtynldesba.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258.top/Article/details/gtbbvohfng.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yonumen.top/Article/details/gtuznyfumr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtypkwbxhh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.snrcjt.cn/Article/details/gtgippvcam.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtvcbqxnfn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gtqdzoqzcn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ydzc1.top/Article/details/gtpaildwpk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cashguo.top/Article/details/gtjnpgdfcq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gtlkjvxwbq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtasieisth.html

[D14] 映射转换（每个元素变形）
来源：http://dali.meibo888.top/Article/details/gtrzpwhdzs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hysaishi.cn/Article/details/gtbfsisbom.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtysdrcefb.html

JS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtqjouhhgp.html

TS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gtcwvmdbsq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yj20258888.top/Article/details/gtwgqzelef.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtvyinoghy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtabgydbdb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtrujztnst.html

[D15] 去重
来源：http://dali.pycfn.com/Article/details/gtlrqxtbny.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtxhxnbrxu.html

PHP:  array_unique($arr);
来源：http://dali.meibo888.top/Article/details/gtsplxmiwd.html

JS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtqctldmyg.html

TS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gtskjhvcyv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gtlukptwjq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.haohaochexian.top/Article/details/gtrnrzxfvj.html

Ruby: arr.uniq
来源：http://dali.shuidangran.top/Article/details/gtrmxurrry.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrpcidgb.html

[D16] 求和与平均值
来源：http://dali.guowangkeji.top/Article/details/gtengtjchr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtrbtvyypc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cucudq.cn/Article/details/gtwfwcwigi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gtbbxvnrsx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gtnlhnyqft.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangtech.top/Article/details/gttjxyqqye.html

Go:   // 手写循环累加
来源：http://dali.jyoumei.cn/Article/details/gtwtkvbndv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gtpyapielq.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258.top/Article/details/gthzlwncvk.html

[D17] 最大值与最小值
来源：http://dali.yangfankeji.com/Article/details/gtgvifofpw.html

Py:   max(arr);  min(arr)
来源：http://dali.hnqzz.top/Article/details/gtdpiouzwc.html

PHP:  max($arr);  min($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtrrpprmiz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.haohaochexian.top/Article/details/gtxfjnfucn.html

TS:   Math.max(...arr);
来源：http://dali.zdqjudy.top/Article/details/gtygyhxdpr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jyoumei.cn/Article/details/gtszlbpiig.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aizwys.cn/Article/details/gttlftlqqc.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxinkj.top/Article/details/gtmwjehqiy.html

C#:   list.Max();  list.Min()
来源：http://dali.daxiang520.top/Article/details/gtpzuaksik.html

[D18] 扁平化嵌套数组
来源：http://dali.snrcjt.cn/Article/details/gtccyazyqs.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.guowangkeji.top/Article/details/gtxpowvlha.html

PHP:  array_merge(...$nested);
来源：http://dali.zhiwuduotai.top/Article/details/gtkdtouzwi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cqqwz.cn/Article/details/gtvnbkmzbh.html

TS:   nested.flat();
来源：http://dali.chenjidiqi.icu/Article/details/gtdrqpxivb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gttyvkxqnx.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gtlngbvsou.html

Ruby: nested.flatten
来源：http://dali.haohaochexian.top/Article/details/gtobsklnrn.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shuidangran.top/Article/details/gtbvkldqgr.html

[D19] 按字段分组
来源：http://dali.smart0.xyz/Article/details/gtqhvxbsco.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.316326.xyz/Article/details/gtsxmyrdoz.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ydzc1.top/Article/details/gtqwqjcbyy.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinqigufen.top/Article/details/gtjieiwzzk.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangdashe.top/Article/details/gtxcolqdmm.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.pycfn.com/Article/details/gtdposvisv.html

Go:   // 手写 map[string][]T
来源：http://dali.hywenlv.cn/Article/details/gteikukxry.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.haohaochexian.top/Article/details/gteklrltbn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gtermrimtz.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxinkj.top/Article/details/gtwltalozn.html

Py:   Counter(arr)
来源：http://dali.tian-w.cn/Article/details/gtwcaztrtk.html

PHP:  array_count_values($arr);
来源：http://dali.xinyue.icu/Article/details/gtvrtdbzxr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtwnpojbzr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtqhygmwzf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.c1oappe.top/Article/details/gtddctdedt.html

Go:   // 手写 map[T]int
来源：http://dali.yanxiufei.cn/Article/details/gtmxiuirsi.html

Ruby: arr.tally
来源：http://dali.yueranfly.top/Article/details/gtfksltflc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258888.top/Article/details/gtkpynkims.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gtdqchrigw.html

Py:   x in arr
来源：http://dali.xinyue.icu/Article/details/gtruovcsxj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ppjwa.cn/Article/details/gtzklcstlp.html

JS:   arr.includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtxusffmjs.html

TS:   arr.includes(x)
来源：http://dali.andypj.xyz/Article/details/gtcikkucuo.html

Java: list.contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtkuanovvb.html

Go:   slices.Contains(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtxvcnlouv.html

Ruby: arr.include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixfccviq.html

C#:   list.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gthkavssqe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.nanxinkj.top/Article/details/gttavneblh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.birdmap.top/Article/details/gtkqykgjel.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.redwolf501.top/Article/details/gtxyokvtck.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hnqzz.top/Article/details/gtbphbusve.html

TS:   [...arr];
来源：http://dali.quarkkingdee.top/Article/details/gtqdkhhhuc.html

Java: new ArrayList<>(list);
来源：http://dali.hnqzz.top/Article/details/gttfvelxac.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.c1oappe.top/Article/details/gtjcphcnds.html

Ruby: arr.dup;  arr.clone
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujdchppu.html

C#:   new List<int>(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuissrxui.html

[D23] reduce 累积计算
来源：http://dali.yj202588.top/Article/details/gtsgcfjqez.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jqgufenzy.top/Article/details/gtwwcontgp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gtirnylpsy.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zdqjudy.top/Article/details/gtpgxshcos.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gtwsbzsopn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.quarkkingdee.top/Article/details/gtuamhwrbh.html

Go:   // 手写循环
来源：http://dali.cucudq.cn/Article/details/gtluldqxko.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.yanxiufei.cn/Article/details/gtwajjsuiq.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.c1oappe.top/Article/details/gtabdjmhps.html

[D24] 字典 / Map 基本操作
来源：http://dali.daxiang520.top/Article/details/gtefvjjybz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.redwolf501.top/Article/details/gtmzqvvxiq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shzxlz.cn/Article/details/gtmuzkunze.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.nwbrower.top/Article/details/gtwvcjmjjt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshwdbcps.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gthvvsitbg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhijiandao.cn/Article/details/gtbhvxlefc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jinqigfzy.top/Article/details/gtemoptiel.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.jyoumei.cn/Article/details/gtzvohyhpm.html

[D25] Set 集合去重与交并差
来源：http://dali.xuanzx.com/Article/details/gtusniakfs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cashguo.top/Article/details/gtrqktcbjx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.svipenyu.cn/Article/details/gtiivouqxu.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yj202588.top/Article/details/gtigcvsokl.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shangyingyoupin.top/Article/details/gtyafmgypq.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtsjusxelg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqgwbgjs.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hysaishi.cn/Article/details/gtpoeenrxg.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shuidangran.top/Article/details/gtmvwuiwez.html

[D26] 数组转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlbcincj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fzhhl.top/Article/details/gtgyzndvzh.html

PHP:  implode(", ", $arr);
来源：http://dali.daxiang520.top/Article/details/gtdztwicfh.html

JS:   arr.join(", ")
来源：http://dali.cheryme.top/Article/details/gtnivbxjxy.html

TS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtdmyexbwo.html

Java: String.join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtruhkdidu.html

Go:   strings.Join(strs, ", ")
来源：http://dali.chenlongwang.top/Article/details/gtijyjdtaa.html

Ruby: arr.join(", ")
来源：http://dali.andypj.xyz/Article/details/gtdgymvjnp.html

C#:   string.Join(", ", list)
来源：http://dali.iojbl.cn/Article/details/gtxkwosbne.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqfwofuv.html

E. 字符串处理
来源：http://dali.gaohongyu789.top/Article/details/gtovtoibro.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtcexrmcoa.html

[E01] 拼接字符串
来源：http://dali.yuanzhike.top/Article/details/gtbbqitzqr.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yangfankeji.com/Article/details/gtyejoxllj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jqgfzy.top/Article/details/gtpkurtvzd.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinqigfzy.top/Article/details/gtmypnjvir.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jianghu66.top/Article/details/gtsblbunzd.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.dianchejie.cn/Article/details/gtcxyhueea.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jqgfzy.top/Article/details/gtlofjpsrb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.0kj1m.cn/Article/details/gtlopgkrbc.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yongpay.top/Article/details/gtepqbppwg.html

[E02] 重复字符串
来源：http://dali.jqgfzy.top/Article/details/gtcmoixesm.html

Py:   "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gtfwreqemj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cashguo.top/Article/details/gttczuwxgu.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gtxozpikdv.html

TS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gttxdcwfnq.html

Java: "ab".repeat(3)
来源：http://dali.tian-w.cn/Article/details/gtzcqbrpfr.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yanxiufei.cn/Article/details/gtulwbwyeh.html

Ruby: "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujedoipd.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj202588.top/Article/details/gtznrfgham.html

[E03] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gtoeddmdoj.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shangyingyoupin.top/Article/details/gttvccsovq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.cheryme.top/Article/details/gtvjqqbgxt.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xylfe.cn/Article/details/gtcimmvily.html

TS:   s.slice(1, 4)
来源：http://dali.redwolf501.top/Article/details/gtoibwyzmt.html

Java: s.substring(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gtuiagukwf.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hysaishi.cn/Article/details/gtlsfpypxs.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigufen.top/Article/details/gthctybpyu.html

C#:   s.Substring(1, 3)
来源：http://dali.sweek.top/Article/details/gtphwabsdc.html

[E04] 查找子串位置
来源：http://dali.0kj1m.cn/Article/details/gtgxttxqdn.html

Py:   s.find("x");  s.index("x")
来源：http://dali.zhengqikj.top/Article/details/gtuzosttqq.html

PHP:  strpos($s, "x");
来源：http://dali.dianchejie.cn/Article/details/gtsiyskvme.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.birdmap.top/Article/details/gtwtnnddhb.html

TS:   s.indexOf("x")
来源：http://dali.dashuyun.cn/Article/details/gtaymuakhq.html

Java: s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gtnddotsrv.html

Go:   strings.Index(s, "x")
来源：http://dali.sufxvd.cn/Article/details/gtuhiyjoeq.html

Ruby: s.index("x")
来源：http://dali.mhx1999.top/Article/details/gtvxdzlytt.html

C#:   s.IndexOf("x")
来源：http://dali.snrcjt.cn/Article/details/gtcjowbokp.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jqgufenzy.top/Article/details/gtejuoaxsw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.hfpthk.cn/Article/details/gtworljpgk.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yj20258.top/Article/details/gtdplgfxbx.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.daxiang520.top/Article/details/gtryzbzlpz.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.gotoacloud.top/Article/details/gtzrroxndf.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.guannengcc.top/Article/details/gthcdlamiq.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.ivvv.top/Article/details/gtrgmrlsvh.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.gzhubu.top/Article/details/gthogplkha.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ybcxt.top/Article/details/gtmasfoucx.html


<!-- 参考信息 -->