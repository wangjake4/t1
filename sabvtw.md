代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.0kj1m.cn/Article/details/gtjmqebhrx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgufenzy.top/Article/details/gtddrbqxej.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jianghu66.top/Article/details/gtbtgwkgoz.html

Ruby: # 无泛型
来源：http://dali.xziqi.cn/Article/details/gtqwciuouz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daxiang520.top/Article/details/gtoyiasbfy.html

[C15] 解构 / 展开参数
来源：http://dali.sweek.top/Article/details/gttriozyeb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hongshengwenyu.top/Article/details/gthexcgvui.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhoulong.xyz/Article/details/gtyghkfowe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtnlxlpocz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hammf.cn/Article/details/gtwyigcyud.html

Java: // 无解构
来源：http://dali.wangdashe.top/Article/details/gtokgrwiqr.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtnwopmqfi.html

Ruby: a, b = pair
来源：http://dali.zycfv.cn/Article/details/gtvpicdhyg.html

C#:   var (a, b) = pair;
来源：http://dali.sxryk.cn/Article/details/gtwsytbfef.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gtwpuriuhr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guannengcc.top/Article/details/gtkjfgsqtq.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gtasouhnnj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hysaishi.cn/Article/details/gtqgdopghg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cdnleiting.top/Article/details/gtitjqxoxr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigufen.top/Article/details/gtnazuhymh.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuanzx.com/Article/details/gtqelkhnne.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuxming.cn/Article/details/gthnugcgoz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ydzc1.top/Article/details/gtshxrqkrq.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtkxtvaube.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gtwcxdqyyg.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gthloynagt.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gtuqqqjrjh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gttctvisqi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daxiang520.top/Article/details/gthvvmudsp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gtwiywfeog.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gtgjvrnthj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuxming.cn/Article/details/gtjoaplppv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guannengcc.top/Article/details/gtbechyisr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hywenlv.cn/Article/details/gtpaofxbua.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jiagoushi.top/Article/details/gtqgtqtnqp.html

[D02] 追加元素到末尾
来源：http://dali.yj20258888.top/Article/details/gtrfwuxnsr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangtech.top/Article/details/gtugnutapo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tianlin.xyz/Article/details/gtliyugwcq.html

JS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gtibgkwsyx.html

TS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtdqtwgzdz.html

Java: list.add(4);
来源：http://dali.yangfankeji.com/Article/details/gtzvnpcukp.html

Go:   arr = append(arr, 4)
来源：http://dali.shzxlz.cn/Article/details/gtdxnbzgve.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ydzc1.top/Article/details/gtsdkpwgvi.html

C#:   list.Add(4);
来源：http://dali.quarkkingdee.top/Article/details/gtdkkfmdox.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gtsyaxwrrr.html

Py:   arr.insert(0, 0)
来源：http://dali.ehwqpu.com/Article/details/gthgfuhina.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xinyue.icu/Article/details/gtpnxpkinn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.mhx1999.top/Article/details/gtvbvrflik.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtggjabnej.html

Java: list.add(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtapodupsu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cashguo.top/Article/details/gtzpyedobt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gtrchkdlfo.html

C#:   list.Insert(0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gturznyoxu.html

[D04] 删除元素
来源：http://dali.yueranfly.top/Article/details/gtosqrrknp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.svipenyu.cn/Article/details/gtaektcxhu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gotoacloud.top/Article/details/gtljmralpc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fengsongda.top/Article/details/gteyeoyuej.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgufenzy.top/Article/details/gtmskbpafa.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.0kj1m.cn/Article/details/gtsicceydo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shuidangran.top/Article/details/gtpoikcjuy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrblvtooj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fzhhl.top/Article/details/gtekcxklkf.html

[D05] 访问与修改元素
来源：http://dali.gotoacloud.top/Article/details/gtstbwdeue.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtlwbbusna.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtnlrlktyr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gteokgkptv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.pycfn.com/Article/details/gthvkfiwyh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yonumen.top/Article/details/gtcldlsplk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtmjmactcf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtqedbyorh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtewabinkc.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtnqvkjsei.html

Py:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gtpapjpfus.html

PHP:  count($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtardannay.html

JS:   arr.length
来源：http://dali.yj202588.top/Article/details/gtkomikdtt.html

TS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtyjkurank.html

Java: list.size();
来源：http://dali.c1oappe.top/Article/details/gtdjouamqi.html

Go:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtbjlaudxd.html

Ruby: arr.length; arr.size
来源：http://dali.sysykeji.top/Article/details/gtrfvirnhf.html

C#:   list.Count;
来源：http://dali.xziqi.cn/Article/details/gtqgmyikej.html

[D07] 切片 / 取子数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsaczsxz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.c1oappe.top/Article/details/gtapcaatnt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtumbyekye.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtgodvqldz.html

TS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrmuteuo.html

Java: list.subList(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtaqhnfaas.html

Go:   arr[1:4]
来源：http://dali.jqgfzy.top/Article/details/gtqnsmqzfj.html

Ruby: arr[1, 3]
来源：http://dali.aizwys.cn/Article/details/gtsnevdptl.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdribbax.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gtzsubbuit.html

Py:   a + b;  a.extend(b)
来源：http://dali.sxryk.cn/Article/details/gtrovukglx.html

PHP:  array_merge($a, $b);
来源：http://dali.svipenyu.cn/Article/details/gtnfishgbu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgflugpa.html

TS:   [...a, ...b];
来源：http://dali.ehwqpu.com/Article/details/gtaqnygpdr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cheryme.top/Article/details/gtdgbdgthg.html

Go:   append(a, b...)
来源：http://dali.316326.xyz/Article/details/gtrjgudsba.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenhoztap.html

C#:   a.Concat(b).ToList()
来源：http://dali.redwolf501.top/Article/details/gtycbpporq.html

[D09] 排序（升序）
来源：http://dali.xuanzx.com/Article/details/gtvpvhjsrf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtsrlpnvux.html

PHP:  sort($arr);
来源：http://dali.chenzaomai.com/Article/details/gtrmwqlkkr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenlongwang.top/Article/details/gtisotveri.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gtvgpksffn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.kuanghao11.cn/Article/details/gtrlwhlfil.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cqqwz.cn/Article/details/gtrwlqrkvf.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaeqgebxe.html

C#:   list.Sort();
来源：http://dali.daxiang520.top/Article/details/gttybfbsef.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dashuyun.cn/Article/details/gtdiffupsm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuanzhike.top/Article/details/gtznhiyljx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gtnurcfjac.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yangfankeji.com/Article/details/gtnkjewtjg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gtijiflheu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zdqjudy.top/Article/details/gtwxiwdhrq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sysykeji.top/Article/details/gtvaxallax.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tian-w.cn/Article/details/gtotxkzntd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xylfe.cn/Article/details/gtsejovasp.html

[D11] 反转数组
来源：http://dali.0kj1m.cn/Article/details/gtertvlvjc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jiagoushi.top/Article/details/gtuxmbuvbi.html

PHP:  array_reverse($arr);
来源：http://dali.fengsongda.top/Article/details/gtjigeaahx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj202588.top/Article/details/gtfkaznnlk.html

TS:   [...arr].reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtineivtnr.html

Java: Collections.reverse(list);
来源：http://dali.yangfankeji.com/Article/details/gtgobpeabt.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gtnixdytkx.html

Ruby: arr.reverse
来源：http://dali.jianghu66.top/Article/details/gtmbyvckvd.html

C#:   list.Reverse();
来源：http://dali.fzhhl.top/Article/details/gtzbflstty.html

[D12] 查找元素下标
来源：http://dali.316326.xyz/Article/details/gtfvcfjzpk.html

Py:   arr.index(x);  x in arr
来源：http://dali.sxryk.cn/Article/details/gtivnrnhgo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jyoumei.cn/Article/details/gtfbspmxey.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gtkesxrici.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtebhvaend.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xinyue.icu/Article/details/gtcrdvddow.html

Go:   slices.Index(arr, x)
来源：http://dali.aizwys.cn/Article/details/gtjkuvownx.html

Ruby: arr.index(x)
来源：http://dali.aibaodan.cn/Article/details/gtdoloczqw.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gttizykttm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhkdhvab.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cdnleiting.top/Article/details/gtebgliddk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ydzc1.top/Article/details/gtmujcsuzr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtvsmwxavs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtqupvdbuf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sweek.top/Article/details/gtxznpsgxf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hammf.cn/Article/details/gtktzeqazk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gtssqqiooy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgufenzy.top/Article/details/gtgdfoblvn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.fzhhl.top/Article/details/gtfxaenmze.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj20258.top/Article/details/gtdlpocwjg.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.redwolf501.top/Article/details/gtgmpjuhtp.html

JS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gtimmucjml.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gthcsnbwfp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtqduuqeqs.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gtkktgtxvz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtkergcyeh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrksgcxnv.html

[D15] 去重
来源：http://dali.bjfxy.top/Article/details/gtbbatpqbc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gtkaldzedr.html

PHP:  array_unique($arr);
来源：http://dali.guannengcc.top/Article/details/gtleanfxef.html

JS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtlpkmtuwe.html

TS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtczbbqwfi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.dashuyun.cn/Article/details/gtjtczowwl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.quarkkingdee.top/Article/details/gtmlpomamn.html

Ruby: arr.uniq
来源：http://dali.smart0.xyz/Article/details/gttxkybnkz.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtsjhlbuhi.html

[D16] 求和与平均值
来源：http://dali.hfpthk.cn/Article/details/gtqvxcdbzn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ydzc1.top/Article/details/gtrygnfnod.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aizwys.cn/Article/details/gtyzmoykgl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gtwpjecocv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtbkbqtdqz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jlsjyb.cn/Article/details/gtcqpkcqse.html

Go:   // 手写循环累加
来源：http://dali.xuetiantiany.cn/Article/details/gtykmvhxos.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.mhx1999.top/Article/details/gtddgognjg.html

C#:   list.Sum();  list.Average()
来源：http://dali.sweek.top/Article/details/gtioznxuwu.html

[D17] 最大值与最小值
来源：http://dali.jlsjyb.cn/Article/details/gtcqvcfcsr.html

Py:   max(arr);  min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtneqyuzpi.html

PHP:  max($arr);  min($arr);
来源：http://dali.yongpay.top/Article/details/gtlsnkauqo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zdqjudy.top/Article/details/gtnwczauas.html

TS:   Math.max(...arr);
来源：http://dali.pengpengdd.cyou/Article/details/gttkllbmib.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pycfn.com/Article/details/gthxbanael.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cqqwz.cn/Article/details/gtcvhtcufw.html

Ruby: arr.max;  arr.min
来源：http://dali.hammf.cn/Article/details/gtmbgtfrum.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgufenzy.top/Article/details/gtmomowrhd.html

[D18] 扁平化嵌套数组
来源：http://dali.yj20258888.top/Article/details/gtfzbxbnqo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gogol.net.cn/Article/details/gtuvwxplir.html

PHP:  array_merge(...$nested);
来源：http://dali.jqgfzy.top/Article/details/gtynnyfheu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gtdeobzgic.html

TS:   nested.flat();
来源：http://dali.tianlin.xyz/Article/details/gtjdfsbome.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnqzz.top/Article/details/gtgctuhxsz.html

Go:   // 手写双层循环
来源：http://dali.dianchejie.cn/Article/details/gtiiookjeg.html

Ruby: nested.flatten
来源：http://dali.zhengqikj.top/Article/details/gtzidtnzrf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtanzoomxs.html

[D19] 按字段分组
来源：http://dali.svipenyu.cn/Article/details/gtlpapuvmi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nanxinkj.top/Article/details/gtsxvfgdvo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.kuanghao11.cn/Article/details/gtkjwcgwmp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jinghuilouyu.cn/Article/details/gtztnwlebe.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fengsongda.top/Article/details/gtmnvqsesn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yvedp.cn/Article/details/gtjanrqsgu.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gtqocssjzf.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnjvthdmc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jiagoushi.top/Article/details/gtbpehsqze.html

[D20] 统计每个元素出现次数
来源：http://dali.havefunace.top/Article/details/gtyvijrsys.html

Py:   Counter(arr)
来源：http://dali.cashguo.top/Article/details/gtddbvpyzp.html

PHP:  array_count_values($arr);
来源：http://dali.hysaishi.cn/Article/details/gtsuvyxefm.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shuidangran.top/Article/details/gteyvgqxjk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pengpengdd.cyou/Article/details/gtgvvfqsmt.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tian-w.cn/Article/details/gtvouysbjv.html

Go:   // 手写 map[T]int
来源：http://dali.zhongyouzk.top/Article/details/gtqkhdvffz.html

Ruby: arr.tally
来源：http://dali.havefunace.top/Article/details/gtjwqiwhod.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sweek.top/Article/details/gtlhcmudfy.html

[D21] 判断是否包含某元素
来源：http://dali.meibo888.top/Article/details/gtztauvnuk.html

Py:   x in arr
来源：http://dali.hfpthk.cn/Article/details/gtxtqkfpfx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.vqdsnc.cn/Article/details/gtckwwtcfy.html

JS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gtwqlhqqzi.html

TS:   arr.includes(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtrkjzwtge.html

Java: list.contains(x)
来源：http://dali.aizwys.cn/Article/details/gtuawwtjvo.html

Go:   slices.Contains(arr, x)
来源：http://dali.haohaochexian.top/Article/details/gtygjhzxok.html

Ruby: arr.include?(x)
来源：http://dali.hfpthk.cn/Article/details/gtsrxnlglx.html

C#:   list.Contains(x)
来源：http://dali.cucudq.cn/Article/details/gtfvtodbqa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jyoumei.cn/Article/details/gtiwrozoms.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.9152youxi.cn/Article/details/gtkenfvlqr.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gtxrdbmejp.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.hammf.cn/Article/details/gtcyuqmike.html

TS:   [...arr];
来源：http://dali.daxiang520.top/Article/details/gtnsfzcpxf.html

Java: new ArrayList<>(list);
来源：http://dali.hammf.cn/Article/details/gtheojcebi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yonumen.top/Article/details/gtloxxepys.html

Ruby: arr.dup;  arr.clone
来源：http://dali.wangdashe.top/Article/details/gthgdvyfoe.html

C#:   new List<int>(list);
来源：http://dali.yvedp.cn/Article/details/gtrgcxpllt.html

[D23] reduce 累积计算
来源：http://dali.yj20258888.top/Article/details/gtvsgiyadp.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gtpkegczxj.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.0kj1m.cn/Article/details/gtxxkrxfqh.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yuanzhike.top/Article/details/gtshhyafxq.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guowangkeji.top/Article/details/gtbzsaccel.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yonumen.top/Article/details/gtpujhipfq.html

Go:   // 手写循环
来源：http://dali.hysaishi.cn/Article/details/gtjzhtpcvz.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.xziqi.cn/Article/details/gtmltpxllp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aibaodan.cn/Article/details/gtayuvleri.html

[D24] 字典 / Map 基本操作
来源：http://dali.xinyue.icu/Article/details/gtbphlxjrm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yanxiufei.cn/Article/details/gtkwgkhdax.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.316326.xyz/Article/details/gtnqedilwp.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jyoumei.cn/Article/details/gtucdtnpcm.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.havefunace.top/Article/details/gtyblyzsii.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.bjfxy.top/Article/details/gtawtcsgka.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zhiwuduotai.top/Article/details/gtxwbdsdke.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.chenjidiqi.icu/Article/details/gtxmrlvmjr.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.xinyue.icu/Article/details/gthbsimbko.html

[D25] Set 集合去重与交并差
来源：http://dali.fzhhl.top/Article/details/gtqrfeofto.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.havefunace.top/Article/details/gtgiemtqxh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jinqigufen.top/Article/details/gtmbvxcijm.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.shuidangran.top/Article/details/gtjigmapnj.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.jinqigfzy.top/Article/details/gtqiylzugz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gtimeedzdr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.fengsongda.top/Article/details/gtibajmebt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sxryk.cn/Article/details/gtoequnmqw.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jianghu66.top/Article/details/gtlnbaagnq.html

[D26] 数组转字符串
来源：http://dali.ydzc1.top/Article/details/gtvvvjtahk.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dianchejie.cn/Article/details/gtszohohed.html

PHP:  implode(", ", $arr);
来源：http://dali.daria6918.cn/Article/details/gtzqwfmgix.html

JS:   arr.join(", ")
来源：http://dali.cqqwz.cn/Article/details/gtlcrrjoml.html

TS:   arr.join(", ")
来源：http://dali.hnxiangtu.top/Article/details/gtulvnvhpi.html

Java: String.join(", ", list)
来源：http://dali.xylfe.cn/Article/details/gtupegurus.html

Go:   strings.Join(strs, ", ")
来源：http://dali.sysykeji.top/Article/details/gtjytgmwop.html

Ruby: arr.join(", ")
来源：http://dali.pengpengdd.cyou/Article/details/gtsubtaeth.html

C#:   string.Join(", ", list)
来源：http://dali.haohaochexian.top/Article/details/gttrwzqafv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtzfxigvju.html

E. 字符串处理
来源：http://dali.pycfn.com/Article/details/gtwycltuis.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvesqxsgr.html

[E01] 拼接字符串
来源：http://dali.cucudq.cn/Article/details/gtosifhiqo.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gtjilaldfn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.nanxinkj.top/Article/details/gtwcfdpsgp.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hongshengwenyu.top/Article/details/gtbcysbaoi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hysaishi.cn/Article/details/gtejcdfhms.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.haohaochexian.top/Article/details/gtgtimcqog.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.quarkkingdee.top/Article/details/gtczrvhluw.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.vqdsnc.cn/Article/details/gtevvlnxdm.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.gaohongyu789.top/Article/details/gtswttkoso.html

[E02] 重复字符串
来源：http://dali.yuxming.cn/Article/details/gtgathgsaa.html

Py:   "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzsjinmpm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yangfankeji.com/Article/details/gtwcuopidx.html

JS:   "ab".repeat(3)
来源：http://dali.daria6918.cn/Article/details/gtvzwrjkkp.html

TS:   "ab".repeat(3)
来源：http://dali.zhijiandao.cn/Article/details/gtywintkes.html

Java: "ab".repeat(3)
来源：http://dali.c1oappe.top/Article/details/gtbhncixie.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtqnsiygfy.html

Ruby: "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gtqnifpmsh.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xuanzx.com/Article/details/gtaqmpogkw.html

[E03] 截取子串
来源：http://dali.jlsjyb.cn/Article/details/gtpzrmesds.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.wangshuangyany.cn/Article/details/gttrpwjwpi.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yuxming.cn/Article/details/gtvnlfpxry.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtsznttcxo.html

TS:   s.slice(1, 4)
来源：http://dali.fzhhl.top/Article/details/gtdhkjdxao.html

Java: s.substring(1, 4)
来源：http://dali.tanke756.top/Article/details/gtdxvdsaix.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.jyoumei.cn/Article/details/gtrtvmxtqe.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zhixingplan.top/Article/details/gtgthjszrf.html

C#:   s.Substring(1, 3)
来源：http://dali.chenlongwang.top/Article/details/gtsabhbydu.html

[E04] 查找子串位置
来源：http://dali.daria6918.cn/Article/details/gtexfqkbgj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.aibaodan.cn/Article/details/gtdaplwxys.html

PHP:  strpos($s, "x");
来源：http://dali.gotoacloud.top/Article/details/gttxhcwtfa.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nwbrower.top/Article/details/gtaubkbqya.html

TS:   s.indexOf("x")
来源：http://dali.hongshengwenyu.top/Article/details/gtuoqoscgq.html

Java: s.indexOf("x")
来源：http://dali.jiagoushi.top/Article/details/gtnjkzlxvj.html

Go:   strings.Index(s, "x")
来源：http://dali.wangshuangyany.cn/Article/details/gthfrdbzrn.html

Ruby: s.index("x")
来源：http://dali.nanxinkj.top/Article/details/gtzcqxzjgt.html

C#:   s.IndexOf("x")
来源：http://dali.c1oappe.top/Article/details/gtffgynsdt.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.316326.xyz/Article/details/gtcnnofesd.html


<!-- 参考信息 -->