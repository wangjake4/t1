代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gtpbilqrmo.html

[C15] 解构 / 展开参数
来源：http://dali.aizwys.cn/Article/details/gtupmbaxch.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gtuznyvyqk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.kuanghao11.cn/Article/details/gtjdxyvqgn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gtcnqmknjr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.haohaochexian.top/Article/details/gtrwgndfpp.html

Java: // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gtxzqpyqtx.html

Go:   // 无解构
来源：http://dali.nwbrower.top/Article/details/gtlncyfhto.html

Ruby: a, b = pair
来源：http://dali.haohaochexian.top/Article/details/gtlvnxmevm.html

C#:   var (a, b) = pair;
来源：http://dali.jqgufenzy.top/Article/details/gtagzggfuk.html

[C16] 函数 / 方法重载
来源：http://dali.jyoumei.cn/Article/details/gtfrnrdrbz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.9152youxi.cn/Article/details/gtipsuakxr.html

PHP:  // 无重载
来源：http://dali.andypj.xyz/Article/details/gtdkccpvvd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sysykeji.top/Article/details/gtxzqacbzs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gtazmneuxw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.birdmap.top/Article/details/gtnpnzmvyh.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangtech.top/Article/details/gtaibcsbqg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tianlin.xyz/Article/details/gtyemegcsu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.iojbl.cn/Article/details/gtkstjcfyb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtsceuusgr.html

D. 数组 / 列表 / 集合
来源：http://dali.pycfn.com/Article/details/gtaprczcmh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtmxthwnmb.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigufen.top/Article/details/gtfyprcjob.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhongyouzk.top/Article/details/gtswsugxjt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258.top/Article/details/gtgnqosnfn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258888.top/Article/details/gttftqulzn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sxryk.cn/Article/details/gtjoqcxtge.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cdnleiting.top/Article/details/gttbkxlrkg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.0kj1m.cn/Article/details/gtpdbqhgqe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhoulong.xyz/Article/details/gtqzqlgsov.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nwbrower.top/Article/details/gtnajkklew.html

[D02] 追加元素到末尾
来源：http://dali.gogol.net.cn/Article/details/gtmbysuqft.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gtwwboaeac.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tianlin.xyz/Article/details/gtllmdxjyv.html

JS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnolzonkv.html

TS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gtzpcpnvnx.html

Java: list.add(4);
来源：http://dali.tianlin.xyz/Article/details/gtfmlqbxul.html

Go:   arr = append(arr, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtwmgwxiax.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fengsongda.top/Article/details/gtingdtvrz.html

C#:   list.Add(4);
来源：http://dali.cashguo.top/Article/details/gtgrruqwfm.html

[D03] 在指定位置插入元素
来源：http://dali.ehwqpu.com/Article/details/gtevlcuxnt.html

Py:   arr.insert(0, 0)
来源：http://dali.cqqwz.cn/Article/details/gtrmputzdn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xinyue.icu/Article/details/gtnvigkozs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.quarkkingdee.top/Article/details/gtquqixkuf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gtynpfwyuz.html

Java: list.add(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gthnsetxeo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tanke756.top/Article/details/gtzyjjbivz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gaohongyu789.top/Article/details/gtmycyyhjh.html

C#:   list.Insert(0, 0);
来源：http://dali.yongpay.top/Article/details/gtceugrisb.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gtlxhhtujv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jyoumei.cn/Article/details/gtnkimkrbo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sweek.top/Article/details/gtwkkuvvyk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhongyouzk.top/Article/details/gtwthmtcfm.html

TS:   arr.splice(0, 1);
来源：http://dali.jlsjyb.cn/Article/details/gtsbflzzab.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtggzztfir.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gtvkbcsmch.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tianlin.xyz/Article/details/gtnvsratrk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhoulong.xyz/Article/details/gtvfabumxj.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gtuynxjldu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gttdtcuqwq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtldpadlhm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtleaqmiuz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ppjwa.cn/Article/details/gtezqkfzsi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jiagoushi.top/Article/details/gtxqebbxii.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtvfghbznd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtlgvcinoc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtqamiwkdr.html

[D06] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtqowenuqf.html

Py:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtefyztctv.html

PHP:  count($arr);
来源：http://dali.sufxvd.cn/Article/details/gticmzuemd.html

JS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gthugetmzv.html

TS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gtlkytzrng.html

Java: list.size();
来源：http://dali.sweek.top/Article/details/gtiwckifvn.html

Go:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtrfzovbzf.html

Ruby: arr.length; arr.size
来源：http://dali.fengsongda.top/Article/details/gtrpfgvoaw.html

C#:   list.Count;
来源：http://dali.smart0.xyz/Article/details/gtpbbxyndm.html

[D07] 切片 / 取子数组
来源：http://dali.redwolf501.top/Article/details/gtcsnwudoc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dashuyun.cn/Article/details/gttpnukshb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtabwzcpnu.html

JS:   arr.slice(1, 4);
来源：http://dali.sweek.top/Article/details/gtrdyrwyoj.html

TS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtjeuzcheu.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvrscmdrp.html

Go:   arr[1:4]
来源：http://dali.cheryme.top/Article/details/gtwbhmfzwt.html

Ruby: arr[1, 3]
来源：http://dali.aibaodan.cn/Article/details/gtvpjbckqm.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gtixxfzuhi.html

[D08] 合并两个数组
来源：http://dali.cqqwz.cn/Article/details/gtgmsmpqkk.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangdashe.top/Article/details/gtcxeczaux.html

PHP:  array_merge($a, $b);
来源：http://dali.daxiang520.top/Article/details/gtjjexmiyy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenzaomai.com/Article/details/gtxxotquth.html

TS:   [...a, ...b];
来源：http://dali.cheryme.top/Article/details/gtgpvwovgb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yongpay.top/Article/details/gtsmrgfczt.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuurlqelj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtjidyykkw.html

C#:   a.Concat(b).ToList()
来源：http://dali.hfpthk.cn/Article/details/gtknhpjepp.html

[D09] 排序（升序）
来源：http://dali.bjfxy.top/Article/details/gtjkyhfinb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtbgmexmxm.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gtzykhqhzo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiylswltt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gtkgfxscrh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.316326.xyz/Article/details/gtlxgyqmqb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtxnwlnkdh.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gtwjnzrqzv.html

C#:   list.Sort();
来源：http://dali.redwolf501.top/Article/details/gtrovgxsbo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shangyingyoupin.top/Article/details/gttovuibko.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xziqi.cn/Article/details/gtwekitzsa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gtyuefxhsu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gticuntznc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yangfankeji.com/Article/details/gtxihftdyc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yueranfly.top/Article/details/gttuokxkxx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aibaodan.cn/Article/details/gtntiajzpn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gtflrlzpxs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dashuyun.cn/Article/details/gtewcgdhoq.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gtwfywxxtm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhengqikj.top/Article/details/gtvgpluqdy.html

PHP:  array_reverse($arr);
来源：http://dali.cqqwz.cn/Article/details/gtgyacidyl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aibaodan.cn/Article/details/gtjxwrzyqw.html

TS:   [...arr].reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gtjzretdqk.html

Java: Collections.reverse(list);
来源：http://dali.hywenlv.cn/Article/details/gtnusrhrnn.html

Go:   slices.Reverse(arr)
来源：http://dali.hammf.cn/Article/details/gtmhrjzwri.html

Ruby: arr.reverse
来源：http://dali.smart0.xyz/Article/details/gtrjysilsz.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gtuvqifpka.html

[D12] 查找元素下标
来源：http://dali.feifeiyinyue.top/Article/details/gtwodlglmw.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gtgkmbdxca.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.316326.xyz/Article/details/gtfrvulbwh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.havefunace.top/Article/details/gtjifrdpzs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtgmeerqtj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gtrcklelgy.html

Go:   slices.Index(arr, x)
来源：http://dali.xinyue.icu/Article/details/gtjbqatoyi.html

Ruby: arr.index(x)
来源：http://dali.xinyue.icu/Article/details/gttqtvtwhg.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigufen.top/Article/details/gtbjjzqtvu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.quarkkingdee.top/Article/details/gtwnbsnrcw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aibaodan.cn/Article/details/gteaavrckt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zdqjudy.top/Article/details/gtnlsvsoan.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtmsxvwqwc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gthhbukgvk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.birdmap.top/Article/details/gtgaochzmd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangdashe.top/Article/details/gthyxajjus.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daxiang520.top/Article/details/gtqfgdatzz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zdqjudy.top/Article/details/gttlrhpcok.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guowangkeji.top/Article/details/gtvumwitfg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hammf.cn/Article/details/gthobmvdvz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.havefunace.top/Article/details/gtsgffreda.html

JS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtlozqdpok.html

TS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtgvmgattk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtjskkvurp.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gtxkjkerqt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtduyfvgej.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwzlasgqm.html

[D15] 去重
来源：http://dali.sysykeji.top/Article/details/gtcnasazwd.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gtkziotibs.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gtfydmtizz.html

JS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gtpycputbs.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtpkjybvxz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tanke756.top/Article/details/gtsxizsasi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.pengpengdd.cyou/Article/details/gtechfcbkc.html

Ruby: arr.uniq
来源：http://dali.zhixingplan.top/Article/details/gtjfxlqrxv.html

C#:   list.Distinct().ToList()
来源：http://dali.tianlin.xyz/Article/details/gttqvrjxmy.html

[D16] 求和与平均值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrdfrwgz.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtppcdpymi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.9152youxi.cn/Article/details/gteyclzukt.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtpsbclmtq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtgbdwbbdj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigfzy.top/Article/details/gtckjkitqq.html

Go:   // 手写循环累加
来源：http://dali.zhiwuduotai.top/Article/details/gtfuadbagz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gtxszxihke.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gtwdbxfmyu.html

[D17] 最大值与最小值
来源：http://dali.sufxvd.cn/Article/details/gtgjlpgkss.html

Py:   max(arr);  min(arr)
来源：http://dali.haohaochexian.top/Article/details/gtsjvhzizp.html

PHP:  max($arr);  min($arr);
来源：http://dali.guannengcc.top/Article/details/gtftguukvn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gtjdancxao.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gtrpqrwsjn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.shzxlz.cn/Article/details/gtcnjfdokd.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtchoryeyn.html

Ruby: arr.max;  arr.min
来源：http://dali.smart0.xyz/Article/details/gttygwhqbe.html

C#:   list.Max();  list.Min()
来源：http://dali.sysykeji.top/Article/details/gtvfitoyrq.html

[D18] 扁平化嵌套数组
来源：http://dali.hysaishi.cn/Article/details/gttbcotlur.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.dianchejie.cn/Article/details/gtgjlnvqiw.html

PHP:  array_merge(...$nested);
来源：http://dali.pengpengdd.cyou/Article/details/gtesgdndxs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxinkj.top/Article/details/gtcrntgufy.html

TS:   nested.flat();
来源：http://dali.nwbrower.top/Article/details/gthiizvdhf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ydzc1.top/Article/details/gtximxlvls.html

Go:   // 手写双层循环
来源：http://dali.quarkkingdee.top/Article/details/gtzalnmris.html

Ruby: nested.flatten
来源：http://dali.jianghu66.top/Article/details/gtviwhyxio.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xziqi.cn/Article/details/gtzcjjpuxg.html

[D19] 按字段分组
来源：http://dali.cdnleiting.top/Article/details/gtbiuvvttk.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.dashuyun.cn/Article/details/gtvzjyorsd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.redwolf501.top/Article/details/gtyifakxxw.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.guannengcc.top/Article/details/gtoknkrnfy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtuzwbsrim.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zdqjudy.top/Article/details/gtkwuqexdu.html

Go:   // 手写 map[string][]T
来源：http://dali.ydzc1.top/Article/details/gtjizkdfgw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.316326.xyz/Article/details/gtiyixpwcr.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gotoacloud.top/Article/details/gtwlqptwsz.html

[D20] 统计每个元素出现次数
来源：http://dali.zhengqikj.top/Article/details/gtsmgarxsr.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gtaadymfgq.html

PHP:  array_count_values($arr);
来源：http://dali.gotoacloud.top/Article/details/gtrnqsajqf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gtyhtchcwv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gtrgwpaljy.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gtjqtapvai.html

Go:   // 手写 map[T]int
来源：http://dali.daxiang520.top/Article/details/gtflkdvgeq.html

Ruby: arr.tally
来源：http://dali.gogol.net.cn/Article/details/gtbeuyowma.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jlsjyb.cn/Article/details/gtqwoknbsb.html

[D21] 判断是否包含某元素
来源：http://dali.jyoumei.cn/Article/details/gtqgkjyheh.html

Py:   x in arr
来源：http://dali.ybcxt.top/Article/details/gtzluelqbf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ehwqpu.com/Article/details/gtbgkbclcn.html

JS:   arr.includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtkmjdhasq.html

TS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtxxgoeszu.html

Java: list.contains(x)
来源：http://dali.ivvv.top/Article/details/gtlignrski.html

Go:   slices.Contains(arr, x)
来源：http://dali.zycfv.cn/Article/details/gtmcpdgzll.html

Ruby: arr.include?(x)
来源：http://dali.cashguo.top/Article/details/gthumaxxxf.html

C#:   list.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtwyyzrbxc.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hysaishi.cn/Article/details/gtyygxiygf.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtfyaqmkfq.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ydzc1.top/Article/details/gteeerwjrd.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.snrcjt.cn/Article/details/gtfpqsngpi.html

TS:   [...arr];
来源：http://dali.iojbl.cn/Article/details/gtqwmemqqf.html

Java: new ArrayList<>(list);
来源：http://dali.vqdsnc.cn/Article/details/gtnvqvhyfl.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gtftgrmust.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangdashe.top/Article/details/gttzxxxbls.html

C#:   new List<int>(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpcifdpdt.html

[D23] reduce 累积计算
来源：http://dali.haohaochexian.top/Article/details/gtcptveqli.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yonumen.top/Article/details/gthnewaipk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.fengsongda.top/Article/details/gtsbfziwrh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtvjvbduuf.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gtltlnpxfl.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxuanxn.top/Article/details/gtelkicffx.html

Go:   // 手写循环
来源：http://dali.sysykeji.top/Article/details/gthjebpgxj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbampxudo.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aizwys.cn/Article/details/gtibdpzomx.html

[D24] 字典 / Map 基本操作
来源：http://dali.tianlin.xyz/Article/details/gtzbciylxa.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.aibaodan.cn/Article/details/gtxmjbsvuj.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.mhx1999.top/Article/details/gtsazayhjm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gaohongyu789.top/Article/details/gtwrtpocox.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtgnefsnap.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gtgvofwbju.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.wangdashe.top/Article/details/gtcmnllgqx.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ivvv.top/Article/details/gththczvts.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zycfv.cn/Article/details/gtgiaghrjr.html

[D25] Set 集合去重与交并差
来源：http://dali.birdmap.top/Article/details/gtgukjdxcf.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ppjwa.cn/Article/details/gtlnzsznsx.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.wangdashe.top/Article/details/gteoraydvz.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sxryk.cn/Article/details/gtbzmnhihc.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.fengsongda.top/Article/details/gtsjjehsjg.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhongyouzk.top/Article/details/gtqrlrudtx.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.aibaodan.cn/Article/details/gtskumfynn.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.hnqzz.top/Article/details/gternlbeap.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.shangyingyoupin.top/Article/details/gtqoerhyrm.html

[D26] 数组转字符串
来源：http://dali.cashguo.top/Article/details/gtubfvvmen.html

Py:   ", ".join(map(str, arr))
来源：http://dali.haohaochexian.top/Article/details/gtidjnqwtz.html

PHP:  implode(", ", $arr);
来源：http://dali.cdnleiting.top/Article/details/gtogzfpppr.html

JS:   arr.join(", ")
来源：http://dali.yangfankeji.com/Article/details/gtbrynabcg.html

TS:   arr.join(", ")
来源：http://dali.fengsongda.top/Article/details/gtkplfikmj.html

Java: String.join(", ", list)
来源：http://dali.yj20258888.top/Article/details/gtkgeopygm.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxuanxn.top/Article/details/gtuaaoltok.html

Ruby: arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gtoechtffx.html

C#:   string.Join(", ", list)
来源：http://dali.yanxiufei.cn/Article/details/gtpviuzehh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtjuladggc.html

E. 字符串处理
来源：http://dali.sweek.top/Article/details/gtgxjzbgzk.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtpxjzeuiw.html

[E01] 拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtbabufdrc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhoulong.xyz/Article/details/gtfaoxdpyn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.fengsongda.top/Article/details/gtguqzcfds.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.daxiang520.top/Article/details/gtqfinyjvj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.0kj1m.cn/Article/details/gtmdlrwbir.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.fengsongda.top/Article/details/gtjnovjgqk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.andypj.xyz/Article/details/gtyouakwjb.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gotoacloud.top/Article/details/gtvnqmhler.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtfxjrboqp.html

[E02] 重复字符串
来源：http://dali.c1oappe.top/Article/details/gtsmwqmjha.html

Py:   "ab" * 3
来源：http://dali.chenlongwang.top/Article/details/gtnlomzcnn.html

PHP:  str_repeat("ab", 3);
来源：http://dali.chenlongwang.top/Article/details/gtwgiqzkal.html

JS:   "ab".repeat(3)
来源：http://dali.zhoulong.xyz/Article/details/gtrdovwfmi.html

TS:   "ab".repeat(3)
来源：http://dali.meibo888.top/Article/details/gtrzypjnmw.html

Java: "ab".repeat(3)
来源：http://dali.yvedp.cn/Article/details/gtdsdzrklb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqteuxsbn.html

Ruby: "ab" * 3
来源：http://dali.0kj1m.cn/Article/details/gtysqertgl.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.jiagoushi.top/Article/details/gtutvrittg.html

[E03] 截取子串
来源：http://dali.svipenyu.cn/Article/details/gtdaozsjyf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.daria6918.cn/Article/details/gtfowrbgks.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.pycfn.com/Article/details/gtxcqcwjla.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtcxuorjuu.html

TS:   s.slice(1, 4)
来源：http://dali.zdqjudy.top/Article/details/gtbnsoluik.html

Java: s.substring(1, 4)
来源：http://dali.mhx1999.top/Article/details/gtfcoaoicd.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.9152youxi.cn/Article/details/gtfuocbnsm.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhengqikj.top/Article/details/gtxlodzdso.html

C#:   s.Substring(1, 3)
来源：http://dali.yj202588.top/Article/details/gthmhidajr.html

[E04] 查找子串位置
来源：http://dali.gzhubu.top/Article/details/gtnswtibnv.html

Py:   s.find("x");  s.index("x")
来源：http://dali.yj20258.top/Article/details/gtaijwrdrr.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gtmchdsohw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesajoizl.html

TS:   s.indexOf("x")
来源：http://dali.hnxiangtu.top/Article/details/gtbcvsjwjg.html

Java: s.indexOf("x")
来源：http://dali.chenjidiqi.icu/Article/details/gtqheigxmi.html

Go:   strings.Index(s, "x")
来源：http://dali.svipenyu.cn/Article/details/gtzqnggtqf.html

Ruby: s.index("x")
来源：http://dali.pengpengdd.cyou/Article/details/gtfiezkxhd.html

C#:   s.IndexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbuvfmiz.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.chenzaomai.com/Article/details/gtkbullfqw.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinbgeppp.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.sysykeji.top/Article/details/gtecggjuwq.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.jinqigufen.top/Article/details/gtgsfbnexn.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.chenlongwang.top/Article/details/gtfwutxnnk.html


<!-- 参考信息 -->