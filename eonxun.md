代发 wailian999

PHP:  // 无重载
来源：http://dali.jqgfzy.top/Article/details/gtlsbyliqq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fzhhl.top/Article/details/gtylbfxhzy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yongpay.top/Article/details/gtpbbtznxm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yongpay.top/Article/details/gtppxptizc.html

Go:   // 无重载：用不同函数名
来源：http://dali.9152youxi.cn/Article/details/gtemebjkdc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gtjkquivre.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ybcxt.top/Article/details/gtrfzfkspk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtquyguyjo.html

D. 数组 / 列表 / 集合
来源：http://dali.hongshengwenyu.top/Article/details/gtrrtszkep.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtznhdlakt.html

[D01] 创建数组 / 列表
来源：http://dali.xylfe.cn/Article/details/gtrusisviq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jiagoushi.top/Article/details/gtebkiipsm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yvedp.cn/Article/details/gtyuycikzx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258888.top/Article/details/gtpkljhyod.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jyoumei.cn/Article/details/gtzshffxvo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hfpthk.cn/Article/details/gtdftorway.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gtywtdbizo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.0kj1m.cn/Article/details/gtwvaviymc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ppjwa.cn/Article/details/gtzmnraprr.html

[D02] 追加元素到末尾
来源：http://dali.sufxvd.cn/Article/details/gtjvotdffq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sweek.top/Article/details/gtxwaqtsto.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yongpay.top/Article/details/gtbgneinyf.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gthvhzsrzq.html

TS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gtumunouju.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gtnauvnpmj.html

Go:   arr = append(arr, 4)
来源：http://dali.andypj.xyz/Article/details/gtepnnyhyf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.birdmap.top/Article/details/gtkuulrtse.html

C#:   list.Add(4);
来源：http://dali.jiagoushi.top/Article/details/gteupfmpix.html

[D03] 在指定位置插入元素
来源：http://dali.redwolf501.top/Article/details/gtblnsygpu.html

Py:   arr.insert(0, 0)
来源：http://dali.cheryme.top/Article/details/gtmunixerv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.redwolf501.top/Article/details/gtstdfyowc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.9152youxi.cn/Article/details/gtawzhhtyp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gteygkplof.html

Java: list.add(0, 0);
来源：http://dali.ybcxt.top/Article/details/gtqlatdbwn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gotoacloud.top/Article/details/gtczazbghj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gtaajyyhzk.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtbjdhskam.html

[D04] 删除元素
来源：http://dali.guannengcc.top/Article/details/gtfztyzyjp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hywenlv.cn/Article/details/gtwoiaofbp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnxiangtu.top/Article/details/gthparaxqo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nwbrower.top/Article/details/gtlbvksalg.html

TS:   arr.splice(0, 1);
来源：http://dali.dashuyun.cn/Article/details/gtqdbrlubz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hywenlv.cn/Article/details/gtjmnkgtpx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnxiangtu.top/Article/details/gttkpdbsru.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yonumen.top/Article/details/gtablilifz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hywenlv.cn/Article/details/gtmsjmsopl.html

[D05] 访问与修改元素
来源：http://dali.andypj.xyz/Article/details/gtbkxfaais.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtsnlqfsxe.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtjmviklab.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtfitgsucz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nanxinkj.top/Article/details/gtphpceida.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zycfv.cn/Article/details/gtzodvjjcs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtdbqqsypi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtycuhtqor.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtaswnmfsd.html

[D06] 数组长度
来源：http://dali.tanke756.top/Article/details/gtlschcnca.html

Py:   len(arr)
来源：http://dali.cheryme.top/Article/details/gtvvmruhak.html

PHP:  count($arr);
来源：http://dali.xuanzx.com/Article/details/gtnklorjfc.html

JS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtjnkhavbe.html

TS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gtnlfedqml.html

Java: list.size();
来源：http://dali.yj20258888.top/Article/details/gtpplgccxr.html

Go:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtjbcillxw.html

Ruby: arr.length; arr.size
来源：http://dali.xinyue.icu/Article/details/gtqkurqfov.html

C#:   list.Count;
来源：http://dali.wangshuangyany.cn/Article/details/gtaqeprruo.html

[D07] 切片 / 取子数组
来源：http://dali.zhixingplan.top/Article/details/gtutzvskzp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hnqzz.top/Article/details/gtnrkudoch.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ehwqpu.com/Article/details/gtwsbibijt.html

JS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtysynahnk.html

TS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtwxxmczar.html

Java: list.subList(1, 4);
来源：http://dali.ivvv.top/Article/details/gtewmarxjj.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gtvwaituiy.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtmqztqndy.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtsnikbkgx.html

[D08] 合并两个数组
来源：http://dali.iojbl.cn/Article/details/gtmmgrocwz.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gtkglphdzo.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gtxliiqpdp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqmalfbm.html

TS:   [...a, ...b];
来源：http://dali.yongpay.top/Article/details/gthepdulyd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gtboaizumu.html

Go:   append(a, b...)
来源：http://dali.xuanzx.com/Article/details/gtabfztsnm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tian-w.cn/Article/details/gtmaxdasnh.html

C#:   a.Concat(b).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtffnfajkk.html

[D09] 排序（升序）
来源：http://dali.ehwqpu.com/Article/details/gtexrdmmmg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yongpay.top/Article/details/gtfflbboht.html

PHP:  sort($arr);
来源：http://dali.nwbrower.top/Article/details/gtmtgugidc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nanxinkj.top/Article/details/gtabljdded.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guannengcc.top/Article/details/gtmkbbzzep.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangdashe.top/Article/details/gtaeorcrui.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtzrdrywlg.html

Ruby: arr.sort
来源：http://dali.xziqi.cn/Article/details/gtlgygqnug.html

C#:   list.Sort();
来源：http://dali.jiagoushi.top/Article/details/gtvtrqgjom.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gttujsqryb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ivvv.top/Article/details/gtukliehtn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cheryme.top/Article/details/gtcyxdpwyt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gtovxotzen.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtwzffibmj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj20258888.top/Article/details/gtlvsvchve.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgfzy.top/Article/details/gtoemocyzz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gtugrlhshu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cdnleiting.top/Article/details/gtdwpgqavi.html

[D11] 反转数组
来源：http://dali.ppjwa.cn/Article/details/gtnfjloeoa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuanzhike.top/Article/details/gtongilkur.html

PHP:  array_reverse($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtxxkwitpl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daria6918.cn/Article/details/gttocdhdlf.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirfabspm.html

Java: Collections.reverse(list);
来源：http://dali.pycfn.com/Article/details/gtqovxvszv.html

Go:   slices.Reverse(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtgmihdrkp.html

Ruby: arr.reverse
来源：http://dali.shzxlz.cn/Article/details/gtkkgadqfh.html

C#:   list.Reverse();
来源：http://dali.zhongyouzk.top/Article/details/gtvzxpgety.html

[D12] 查找元素下标
来源：http://dali.jlsjyb.cn/Article/details/gtjzrnfacs.html

Py:   arr.index(x);  x in arr
来源：http://dali.pengpengdd.cyou/Article/details/gtcqhcmkrv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtfdouqvme.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gtwwkiravj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtewxszfeu.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sysykeji.top/Article/details/gtfbowvjuv.html

Go:   slices.Index(arr, x)
来源：http://dali.jqgufenzy.top/Article/details/gtcjxuqalq.html

Ruby: arr.index(x)
来源：http://dali.jlsjyb.cn/Article/details/gtplmflzpn.html

C#:   list.IndexOf(x);
来源：http://dali.jianghu66.top/Article/details/gteklaicdw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zdqjudy.top/Article/details/gtoqvrsyma.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dianchejie.cn/Article/details/gtunfoekzd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pycfn.com/Article/details/gtpjmhjuhk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yonumen.top/Article/details/gtwxlevwil.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtahrcfhqv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aizwys.cn/Article/details/gtjbpynsfe.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yuxming.cn/Article/details/gthiulwafu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ppjwa.cn/Article/details/gtozyscmdv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsvsxnuj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xinyue.icu/Article/details/gtnqcjxnyb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtspzfqrqo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthxhinbqq.html

JS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtypcxfpnb.html

TS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gtporqrhsx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtwlfjmdyo.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtpqevtfse.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gthjtwxbtt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jianghu66.top/Article/details/gtdfqmwoal.html

[D15] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gtbuxrgpcd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gtjwrivxae.html

PHP:  array_unique($arr);
来源：http://dali.jiagoushi.top/Article/details/gtvlnpdlxk.html

JS:   [...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtuijamvmh.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtrkefppxo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zdqjudy.top/Article/details/gtbtisuqdo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gtkakywfmy.html

Ruby: arr.uniq
来源：http://dali.jianghu66.top/Article/details/gtlaxagjoh.html

C#:   list.Distinct().ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gtyrtbuibb.html

[D16] 求和与平均值
来源：http://dali.wangshuangyany.cn/Article/details/gtwzrnhvqa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangdashe.top/Article/details/gtgzwuaqqu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cheryme.top/Article/details/gtwlmuwopl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gtoiueppcl.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jqgfzy.top/Article/details/gtzyjgsjzz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.iojbl.cn/Article/details/gtddrlrjub.html

Go:   // 手写循环累加
来源：http://dali.jinqigfzy.top/Article/details/gtwvaumwri.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.guowangkeji.top/Article/details/gtyaeoybuo.html

C#:   list.Sum();  list.Average()
来源：http://dali.daria6918.cn/Article/details/gtwasdyesp.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gtpmpqptds.html

Py:   max(arr);  min(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamascysk.html

PHP:  max($arr);  min($arr);
来源：http://dali.xziqi.cn/Article/details/gttmvtpicf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shuidangran.top/Article/details/gtnccasqax.html

TS:   Math.max(...arr);
来源：http://dali.xuanzx.com/Article/details/gttyvyoymy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhixingplan.top/Article/details/gtjacwjqmi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.birdmap.top/Article/details/gtenmxrnzf.html

Ruby: arr.max;  arr.min
来源：http://dali.xuanzx.com/Article/details/gtwqgxjlez.html

C#:   list.Max();  list.Min()
来源：http://dali.xuanzx.com/Article/details/gtghttdqzg.html

[D18] 扁平化嵌套数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gttbojisyj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dashuyun.cn/Article/details/gtjtczidob.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gtsdeodsoa.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jiagoushi.top/Article/details/gtmclfhngr.html

TS:   nested.flat();
来源：http://dali.nwbrower.top/Article/details/gtnjnzaizb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.aizwys.cn/Article/details/gtefqsoira.html

Go:   // 手写双层循环
来源：http://dali.shangyingyoupin.top/Article/details/gtpfqratto.html

Ruby: nested.flatten
来源：http://dali.yongpay.top/Article/details/gtqyhdaxpb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtozqagcin.html

[D19] 按字段分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcdlzpvz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zdqjudy.top/Article/details/gtrjbcdfbd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hnqzz.top/Article/details/gtuqszebgh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jyoumei.cn/Article/details/gtpphnxwwz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gtbwyqzjuq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.316326.xyz/Article/details/gtohrtwifj.html

Go:   // 手写 map[string][]T
来源：http://dali.dashuyun.cn/Article/details/gtxpssjblr.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xziqi.cn/Article/details/gtmcyjitvk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.c1oappe.top/Article/details/gtjhamaycc.html

[D20] 统计每个元素出现次数
来源：http://dali.cqqwz.cn/Article/details/gtzbwyyahi.html

Py:   Counter(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtqbqnxqkf.html

PHP:  array_count_values($arr);
来源：http://dali.iojbl.cn/Article/details/gteiuddixo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gtyvebcqfo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cdnleiting.top/Article/details/gthpzwiepe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hysaishi.cn/Article/details/gthswyucsr.html

Go:   // 手写 map[T]int
来源：http://dali.cashguo.top/Article/details/gtqzsymmfp.html

Ruby: arr.tally
来源：http://dali.0kj1m.cn/Article/details/gtwewbfqus.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yongpay.top/Article/details/gthrpugnom.html

[D21] 判断是否包含某元素
来源：http://dali.sweek.top/Article/details/gtvqgexdrq.html

Py:   x in arr
来源：http://dali.yonumen.top/Article/details/gtkqymqqwx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.nanxuanxn.top/Article/details/gtgdntgulj.html

JS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtvgzqxvex.html

TS:   arr.includes(x)
来源：http://dali.guannengcc.top/Article/details/gtiqxzdgko.html

Java: list.contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gthuhgzisj.html

Go:   slices.Contains(arr, x)
来源：http://dali.tian-w.cn/Article/details/gtiucyywqz.html

Ruby: arr.include?(x)
来源：http://dali.shzxlz.cn/Article/details/gturavlrgb.html

C#:   list.Contains(x)
来源：http://dali.yongpay.top/Article/details/gtuwgbgnrw.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuxming.cn/Article/details/gthcpjayvm.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.fzhhl.top/Article/details/gtakcwtare.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sysykeji.top/Article/details/gthlwvarnp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.svipenyu.cn/Article/details/gtoyxknmld.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gtstwajbnz.html

Java: new ArrayList<>(list);
来源：http://dali.shzxlz.cn/Article/details/gtbfezhcwt.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gtxfrjnsoz.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yvedp.cn/Article/details/gtpjqnqxsh.html

C#:   new List<int>(list);
来源：http://dali.xylfe.cn/Article/details/gtrzycbctv.html

[D23] reduce 累积计算
来源：http://dali.xylfe.cn/Article/details/gtxmjdnkop.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zycfv.cn/Article/details/gtaunckuat.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.0kj1m.cn/Article/details/gtqbxmkbkp.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.316326.xyz/Article/details/gtoidylpfi.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtysmzfzqg.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gaohongyu789.top/Article/details/gtguhqwwqi.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gtymgvnmrc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.kuanghao11.cn/Article/details/gtqhqkkphc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.guowangkeji.top/Article/details/gtfhfishlu.html

[D24] 字典 / Map 基本操作
来源：http://dali.shzxlz.cn/Article/details/gtcpyhosxv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenzaomai.com/Article/details/gtnnojtfkz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.daxiang520.top/Article/details/gtdozjjrqx.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuetiantiany.cn/Article/details/gttmgvbrrr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtjzqwkzcr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cashguo.top/Article/details/gttyldcuxt.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cashguo.top/Article/details/gtkvbgyxsf.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yvedp.cn/Article/details/gtrnkihqyg.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.gotoacloud.top/Article/details/gtkmmobvox.html

[D25] Set 集合去重与交并差
来源：http://dali.haohaochexian.top/Article/details/gtqmgtwuwo.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gtunocypdr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.vqdsnc.cn/Article/details/gthgtdtjnh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dianchejie.cn/Article/details/gtulajlsmf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.guannengcc.top/Article/details/gtufgufyzg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.hnqzz.top/Article/details/gtwpydawfo.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cucudq.cn/Article/details/gtpmffiwil.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sufxvd.cn/Article/details/gtlsvlyrzr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuzfzgxi.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtjlxzwiug.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gtdyhpxynb.html

PHP:  implode(", ", $arr);
来源：http://dali.zhixingplan.top/Article/details/gtvhemwjox.html

JS:   arr.join(", ")
来源：http://dali.xylfe.cn/Article/details/gthuvspffk.html

TS:   arr.join(", ")
来源：http://dali.nwbrower.top/Article/details/gtgnotoyvk.html

Java: String.join(", ", list)
来源：http://dali.shzxlz.cn/Article/details/gtweuaoozv.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkgmhxpj.html

Ruby: arr.join(", ")
来源：http://dali.cucudq.cn/Article/details/gtnsixrybl.html

C#:   string.Join(", ", list)
来源：http://dali.smart0.xyz/Article/details/gtgsensinh.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtduncypxj.html

E. 字符串处理
来源：http://dali.9152youxi.cn/Article/details/gttfgobbrq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtwoomcjio.html

[E01] 拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtrbtivcdp.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhiwuduotai.top/Article/details/gtqrstjevd.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gtmbpgdtvt.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gtwautkveq.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gtrrpwhjax.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cqqwz.cn/Article/details/gtppiqpyik.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlltewry.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gtjaqsxeyq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtxvyymwzv.html

[E02] 重复字符串
来源：http://dali.9152youxi.cn/Article/details/gtnhdtqbvi.html

Py:   "ab" * 3
来源：http://dali.aibaodan.cn/Article/details/gtzftzuqva.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yj20258.top/Article/details/gtjgrqylmx.html

JS:   "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtsvbuybxf.html

TS:   "ab".repeat(3)
来源：http://dali.yj20258.top/Article/details/gtjoyffaej.html

Java: "ab".repeat(3)
来源：http://dali.chenzaomai.com/Article/details/gtkhdwgwjz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gtmoxnoegn.html

Ruby: "ab" * 3
来源：http://dali.yangfankeji.com/Article/details/gtbtrpazhi.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gtowxictxt.html

[E03] 截取子串
来源：http://dali.bjfxy.top/Article/details/gtzjegcasq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.aizwys.cn/Article/details/gtpzynvinm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gtjjuoislu.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.xuetiantiany.cn/Article/details/gtloypmrnj.html

TS:   s.slice(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtdvgsadxx.html

Java: s.substring(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtefezplmk.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.daria6918.cn/Article/details/gthtonjjee.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.dashuyun.cn/Article/details/gtixbfwapt.html

C#:   s.Substring(1, 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidmpquel.html

[E04] 查找子串位置
来源：http://dali.tanke756.top/Article/details/gttcjuxpcz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.svipenyu.cn/Article/details/gtsibaxmge.html

PHP:  strpos($s, "x");
来源：http://dali.pengpengdd.cyou/Article/details/gtjtemgyvx.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvzfmbyh.html

TS:   s.indexOf("x")
来源：http://dali.xinyue.icu/Article/details/gtlgkixxao.html

Java: s.indexOf("x")
来源：http://dali.mhx1999.top/Article/details/gtlxbnlrsg.html

Go:   strings.Index(s, "x")
来源：http://dali.snrcjt.cn/Article/details/gtemjchkkd.html

Ruby: s.index("x")
来源：http://dali.jinghuilouyu.cn/Article/details/gtgseuynhq.html

C#:   s.IndexOf("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrusnsezy.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.jyoumei.cn/Article/details/gtfozmijhb.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.gotoacloud.top/Article/details/gttgjuomeb.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiafnwcrq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yj20258888.top/Article/details/gtxofrezfw.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.kuanghao11.cn/Article/details/gtkplhlqnw.html

Java: s.contains("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthgznove.html

Go:   strings.Contains(s, "x");  strings.HasPrefix(s, "a");  strings.HasSuffix(s, "z")
来源：http://dali.guowangkeji.top/Article/details/gtwydtsrko.html

Ruby: s.include?("x");  s.start_with?("a");  s.end_with?("z")
来源：http://dali.ehwqpu.com/Article/details/gtpkplcswk.html

C#:   s.Contains("x");  s.StartsWith("a");  s.EndsWith("z")
来源：http://dali.ydzc1.top/Article/details/gtrfopuubt.html

[E06] 替换子串
来源：http://dali.havefunace.top/Article/details/gtuoeovxdm.html

Py:   s.replace("a", "b");  s.replace("a", "b", 1)
来源：http://dali.jqgfzy.top/Article/details/gtzywznguu.html

PHP:  str_replace("a", "b", $s);
来源：http://dali.9152youxi.cn/Article/details/gtptmuxhmu.html

JS:   s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.daria6918.cn/Article/details/gtglnvxuga.html

TS:   s.replaceAll("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjymjutk.html

Java: s.replace("a", "b");  s.replaceAll("a", "b")
来源：http://dali.316326.xyz/Article/details/gtzyuinttr.html

Go:   strings.ReplaceAll(s, "a", "b");  strings.Replace(s, "a", "b", 1)
来源：http://dali.yuxming.cn/Article/details/gtlptgfegn.html

Ruby: s.gsub("a", "b");  s.sub("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gthabmsfql.html


<!-- 参考信息 -->