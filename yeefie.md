代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.316326.xyz/Article/details/gtljpjmdad.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj202588.top/Article/details/gtpynqcmxu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tianlin.xyz/Article/details/gtvgpoidxs.html

Ruby: # 无泛型
来源：http://dali.c1oappe.top/Article/details/gtfxybewgk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.smart0.xyz/Article/details/gtwwjnopqi.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gtkjplucqn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.guannengcc.top/Article/details/gtbiaqrord.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gogol.net.cn/Article/details/gtlholcypz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gtzxjxyoad.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daria6918.cn/Article/details/gtyscdftkx.html

Java: // 无解构
来源：http://dali.gotoacloud.top/Article/details/gtaevmdhys.html

Go:   // 无解构
来源：http://dali.gotoacloud.top/Article/details/gtsrjrnwhe.html

Ruby: a, b = pair
来源：http://dali.jinyuanbaomall.cn/Article/details/gteadiokjm.html

C#:   var (a, b) = pair;
来源：http://dali.ehwqpu.com/Article/details/gtxihhbyqy.html

[C16] 函数 / 方法重载
来源：http://dali.cqqwz.cn/Article/details/gtmtukvdjz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gtlygqpaob.html

PHP:  // 无重载
来源：http://dali.0kj1m.cn/Article/details/gtembfrwhx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuanzx.com/Article/details/gtaxdryocd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hongshengwenyu.top/Article/details/gtikacsqzu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.snrcjt.cn/Article/details/gtagsjmrqb.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigfzy.top/Article/details/gtravauuac.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nwbrower.top/Article/details/gtjrrenrhf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gtbluitrvg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtqhwwmqgr.html

D. 数组 / 列表 / 集合
来源：http://dali.zycfv.cn/Article/details/gtkdnxfsqq.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtpujbewdz.html

[D01] 创建数组 / 列表
来源：http://dali.hnqzz.top/Article/details/gtzsfsrydf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hongshengwenyu.top/Article/details/gtvqkilbzy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gtonpvuruv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj202588.top/Article/details/gtjsomztrg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nwbrower.top/Article/details/gtmtxzxyjq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xinyue.icu/Article/details/gtrfzgolnq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aibaodan.cn/Article/details/gtolroheus.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xylfe.cn/Article/details/gtmakvktjf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenlongwang.top/Article/details/gtjsmclybh.html

[D02] 追加元素到末尾
来源：http://dali.wangdashe.top/Article/details/gtmdqvvdyq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sysykeji.top/Article/details/gtxiwichnh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sxryk.cn/Article/details/gtadkxvtpv.html

JS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gtyaxoustf.html

TS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gtijmpwvfp.html

Java: list.add(4);
来源：http://dali.wangdashe.top/Article/details/gtqsngeghs.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gtsipunmme.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cdnleiting.top/Article/details/gtircluynz.html

C#:   list.Add(4);
来源：http://dali.xylfe.cn/Article/details/gthykpplvt.html

[D03] 在指定位置插入元素
来源：http://dali.yvedp.cn/Article/details/gtxxoagbkx.html

Py:   arr.insert(0, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtzetvskha.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pycfn.com/Article/details/gtzzampzmq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gtapkejibm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258888.top/Article/details/gtptnwhtmw.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gttixwrmsb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gtiavttbna.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjoyoipdu.html

C#:   list.Insert(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gthcrthjos.html

[D04] 删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gthabwvimv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xylfe.cn/Article/details/gtyzyghust.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gtibcmotcn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.316326.xyz/Article/details/gtfmjkdnpn.html

TS:   arr.splice(0, 1);
来源：http://dali.hfpthk.cn/Article/details/gtwknzbgrd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cqqwz.cn/Article/details/gtljduapxx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.316326.xyz/Article/details/gtamlifxvi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.haohaochexian.top/Article/details/gtlhsntniz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwigskstg.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gtcqgxaqje.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtwhuyjgdh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gthblwxpkf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtoqqhomfo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.havefunace.top/Article/details/gtuotiqkuv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tian-w.cn/Article/details/gtaijsrwak.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtlosarxva.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtzxrsllgh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtmdcrssgr.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gtqstgzqvf.html

Py:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtnuuqnowe.html

PHP:  count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gteanbfvzv.html

JS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gtvjpgpqnf.html

TS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtrahnskpr.html

Java: list.size();
来源：http://dali.ydzc1.top/Article/details/gtjqrpldvd.html

Go:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gttrwdykga.html

Ruby: arr.length; arr.size
来源：http://dali.shanyushiyangkeji.top/Article/details/gtioocnukz.html

C#:   list.Count;
来源：http://dali.pengpengdd.cyou/Article/details/gtfhocsodp.html

[D07] 切片 / 取子数组
来源：http://dali.daxiang520.top/Article/details/gtihuyleds.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yvedp.cn/Article/details/gtqbtbstvu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtysymolku.html

JS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtqdakaqbl.html

TS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqcphbww.html

Java: list.subList(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtkjxjzkle.html

Go:   arr[1:4]
来源：http://dali.andypj.xyz/Article/details/gtupdvrszu.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gtimrnbavh.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtbdujbohl.html

[D08] 合并两个数组
来源：http://dali.yuanzhike.top/Article/details/gtsfylprqj.html

Py:   a + b;  a.extend(b)
来源：http://dali.daxiang520.top/Article/details/gtatsftsyn.html

PHP:  array_merge($a, $b);
来源：http://dali.chenlongwang.top/Article/details/gttbrgkcyw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuxming.cn/Article/details/gtmfuynrgi.html

TS:   [...a, ...b];
来源：http://dali.yuanzhike.top/Article/details/gtkokrbpnv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzhvsdxu.html

Go:   append(a, b...)
来源：http://dali.nanxinkj.top/Article/details/gtbalyofla.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzeszlgz.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtietkmksf.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gtvnpedghb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgufenzy.top/Article/details/gtcehgbzmi.html

PHP:  sort($arr);
来源：http://dali.redwolf501.top/Article/details/gtawoaffzf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cashguo.top/Article/details/gtgsjlpbkp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hysaishi.cn/Article/details/gtapeymhma.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yanxiufei.cn/Article/details/gtdyequvso.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbyefmij.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtidwdlfgf.html

C#:   list.Sort();
来源：http://dali.yvedp.cn/Article/details/gtfofuhhjf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.iojbl.cn/Article/details/gtitjiwubl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.quarkkingdee.top/Article/details/gtccmjtjxf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtuhcvfjnl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtbvbslavc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtygmkawxa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gtvnigrzva.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dashuyun.cn/Article/details/gtivibyriz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgufenzy.top/Article/details/gtjneihuio.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zdqjudy.top/Article/details/gtugxuvnuq.html

[D11] 反转数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgjkbfit.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yueranfly.top/Article/details/gtdesadytc.html

PHP:  array_reverse($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzcxovyh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gtomboinoi.html

TS:   [...arr].reverse();
来源：http://dali.ehwqpu.com/Article/details/gtbrukutkx.html

Java: Collections.reverse(list);
来源：http://dali.jyoumei.cn/Article/details/gtermhoqpp.html

Go:   slices.Reverse(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtvvpfbphg.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtdqbkliws.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gtpicydmet.html

[D12] 查找元素下标
来源：http://dali.pengpengdd.cyou/Article/details/gtpuplxvhm.html

Py:   arr.index(x);  x in arr
来源：http://dali.hywenlv.cn/Article/details/gttaqbuqrg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hysaishi.cn/Article/details/gtsbcfgebe.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gtlhjxbpqs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gtwrgmespa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dashuyun.cn/Article/details/gtgjwfvuju.html

Go:   slices.Index(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtfalmvarv.html

Ruby: arr.index(x)
来源：http://dali.xziqi.cn/Article/details/gtetgxyhgy.html

C#:   list.IndexOf(x);
来源：http://dali.c1oappe.top/Article/details/gtismobphf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.svipenyu.cn/Article/details/gtiwtuczkc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dianchejie.cn/Article/details/gtshestiqz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cashguo.top/Article/details/gtgoswbwaa.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shzxlz.cn/Article/details/gtrawkuaef.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gthainstqd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzczlrkm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylxrqouh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangdashe.top/Article/details/gtrmpmjimh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtmrouzgzt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gtyshmazfl.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cheryme.top/Article/details/gtumdinhhr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hywenlv.cn/Article/details/gtjkemnhos.html

JS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gteycqarpj.html

TS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gtyquatrbp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhengqikj.top/Article/details/gteepeqdkg.html

Go:   // 手写循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfplftdbw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gthbtezlde.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtkpxtzpgr.html

[D15] 去重
来源：http://dali.hnqzz.top/Article/details/gtmgqjvrrm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gtwqyoyaka.html

PHP:  array_unique($arr);
来源：http://dali.guowangkeji.top/Article/details/gtopyipgfu.html

JS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtahyuqfwc.html

TS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtenhrswpo.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gtpwcvrqqs.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xinyue.icu/Article/details/gtmjbubxkk.html

Ruby: arr.uniq
来源：http://dali.bjfxy.top/Article/details/gthetocjps.html

C#:   list.Distinct().ToList()
来源：http://dali.nwbrower.top/Article/details/gtzsphyybq.html

[D16] 求和与平均值
来源：http://dali.dashuyun.cn/Article/details/gtbhiowvhg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shuidangran.top/Article/details/gtvcqftfef.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.dashuyun.cn/Article/details/gtxedanolw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtqmzlphue.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hysaishi.cn/Article/details/gtixmflsti.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ppjwa.cn/Article/details/gtgkwdhfdk.html

Go:   // 手写循环累加
来源：http://dali.aibaodan.cn/Article/details/gtuhfatrvn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zycfv.cn/Article/details/gtwxffjcgm.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangdashe.top/Article/details/gtumzkkjjv.html

[D17] 最大值与最小值
来源：http://dali.zhiwuduotai.top/Article/details/gthbmgcghz.html

Py:   max(arr);  min(arr)
来源：http://dali.smart0.xyz/Article/details/gtnqvqizeo.html

PHP:  max($arr);  min($arr);
来源：http://dali.gotoacloud.top/Article/details/gtavflluis.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnxiangtu.top/Article/details/gtgjfshndm.html

TS:   Math.max(...arr);
来源：http://dali.jianghu66.top/Article/details/gtxcifflsq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gotoacloud.top/Article/details/gtsulycfpb.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtsxylhyde.html

Ruby: arr.max;  arr.min
来源：http://dali.xuanzx.com/Article/details/gttvqpgigz.html

C#:   list.Max();  list.Min()
来源：http://dali.bjfxy.top/Article/details/gtwkqiylvv.html

[D18] 扁平化嵌套数组
来源：http://dali.shangyingyoupin.top/Article/details/gtewweovvg.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gogol.net.cn/Article/details/gturcpdbpq.html

PHP:  array_merge(...$nested);
来源：http://dali.tanke756.top/Article/details/gtlzgrexes.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.jyoumei.cn/Article/details/gtrdzdqnvo.html

TS:   nested.flat();
来源：http://dali.mhx1999.top/Article/details/gtbudaxkxb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gthbimewwd.html

Go:   // 手写双层循环
来源：http://dali.wangdashe.top/Article/details/gtdhvisxxu.html

Ruby: nested.flatten
来源：http://dali.wangdashe.top/Article/details/gtbmrlujis.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cashguo.top/Article/details/gtftywdpdc.html

[D19] 按字段分组
来源：http://dali.hnqzz.top/Article/details/gtdcvhttke.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cheryme.top/Article/details/gtlwwonisr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuetiantiany.cn/Article/details/gtuxbzmvmd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.c1oappe.top/Article/details/gtsiwlqlfu.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yuanzhike.top/Article/details/gtfapqljgy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gtbvzpmzdv.html

Go:   // 手写 map[string][]T
来源：http://dali.dashuyun.cn/Article/details/gtdutvqsif.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.daria6918.cn/Article/details/gtfyylmcxc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jiagoushi.top/Article/details/gthmlsaqkn.html

[D20] 统计每个元素出现次数
来源：http://dali.birdmap.top/Article/details/gtvblclzbo.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gteqyqkabo.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtabdubjjy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gtjblehyqs.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgufenzy.top/Article/details/gtpmxjuhkl.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgufenzy.top/Article/details/gtcmofcpmx.html

Go:   // 手写 map[T]int
来源：http://dali.jiagoushi.top/Article/details/gtqobxklnx.html

Ruby: arr.tally
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwquqpmg.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhiwuduotai.top/Article/details/gttkolmyoe.html

[D21] 判断是否包含某元素
来源：http://dali.xuanzx.com/Article/details/gtpnbhatpb.html

Py:   x in arr
来源：http://dali.meibo888.top/Article/details/gtukzclsrf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gzhubu.top/Article/details/gtwdenxhlb.html

JS:   arr.includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtninpalor.html

TS:   arr.includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtebldlsew.html

Java: list.contains(x)
来源：http://dali.smart0.xyz/Article/details/gteyvgjasq.html

Go:   slices.Contains(arr, x)
来源：http://dali.yuxming.cn/Article/details/gtliexooon.html

Ruby: arr.include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtbroqjrfb.html

C#:   list.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gtgkofwyhl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigfzy.top/Article/details/gtlquqnghb.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtqhsmcfkw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.redwolf501.top/Article/details/gtapwzirpw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yvedp.cn/Article/details/gtizpetvni.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gtnrfcpglj.html

Java: new ArrayList<>(list);
来源：http://dali.316326.xyz/Article/details/gtbibeheik.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.9152youxi.cn/Article/details/gtpssgqkkh.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tianlin.xyz/Article/details/gtzdcaaeqt.html

C#:   new List<int>(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gthgriblfa.html

[D23] reduce 累积计算
来源：http://dali.nwbrower.top/Article/details/gtcjxtglie.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtglpogbdl.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cheryme.top/Article/details/gtolegzmns.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtzfufhgsl.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.gzhubu.top/Article/details/gttfioobxm.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yuanzhike.top/Article/details/gtuasjuzlm.html

Go:   // 手写循环
来源：http://dali.9152youxi.cn/Article/details/gtklhozgdm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhongyouzk.top/Article/details/gtgbwoeqph.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinqigufen.top/Article/details/gtjiqtcaey.html

[D24] 字典 / Map 基本操作
来源：http://dali.yonumen.top/Article/details/gthuxmumzt.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.chenlongwang.top/Article/details/gtyxtrywvk.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhoulong.xyz/Article/details/gtwgoymdfq.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ppjwa.cn/Article/details/gtdnhhfbof.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtbxhnhewx.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfmeshil.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.vqdsnc.cn/Article/details/gtnbpcrsoi.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.ppjwa.cn/Article/details/gtsyqqrouz.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.yonumen.top/Article/details/gtkajfqoaq.html

[D25] Set 集合去重与交并差
来源：http://dali.mhx1999.top/Article/details/gtvraqxonm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhongyouzk.top/Article/details/gtajbonued.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ppjwa.cn/Article/details/gtfjebbwwq.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hongshengwenyu.top/Article/details/gtokdkxxdg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifhhibwa.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.xziqi.cn/Article/details/gtkdhqbqtg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.gogol.net.cn/Article/details/gtytkqyfwt.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.sxryk.cn/Article/details/gtugfcyzxf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cashguo.top/Article/details/gtdnrewzfp.html

[D26] 数组转字符串
来源：http://dali.316326.xyz/Article/details/gtjbafyvhw.html

Py:   ", ".join(map(str, arr))
来源：http://dali.svipenyu.cn/Article/details/gthotkflwr.html

PHP:  implode(", ", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtsmedjwtp.html

JS:   arr.join(", ")
来源：http://dali.feifeiyinyue.top/Article/details/gtqkylokee.html

TS:   arr.join(", ")
来源：http://dali.aibaodan.cn/Article/details/gtghrpmauw.html

Java: String.join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gtqvzmrflx.html

Go:   strings.Join(strs, ", ")
来源：http://dali.fzhhl.top/Article/details/gternkgqqg.html

Ruby: arr.join(", ")
来源：http://dali.vqdsnc.cn/Article/details/gtzmooiodw.html

C#:   string.Join(", ", list)
来源：http://dali.jyoumei.cn/Article/details/gtaxtkwfgq.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtqddikbyd.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gtnjwdpmby.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gttojmlahn.html

[E01] 拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtottibyfn.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyvrhzsp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yuxming.cn/Article/details/gthkkqixdm.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.aizwys.cn/Article/details/gtcmvxwzkz.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.andypj.xyz/Article/details/gtuybjxcdt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.redwolf501.top/Article/details/gtybkcreso.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.guannengcc.top/Article/details/gtxbjztefd.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.hongshengwenyu.top/Article/details/gtlvjbxqei.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guannengcc.top/Article/details/gtipnerlmd.html

[E02] 重复字符串
来源：http://dali.jqgufenzy.top/Article/details/gtkamyocfv.html

Py:   "ab" * 3
来源：http://dali.hfpthk.cn/Article/details/gthskxabdr.html

PHP:  str_repeat("ab", 3);
来源：http://dali.cdnleiting.top/Article/details/gtnoxieaxi.html

JS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtkpljgzci.html

TS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtgtjrikmm.html

Java: "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gtepnldizm.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.havefunace.top/Article/details/gthhsnaivr.html

Ruby: "ab" * 3
来源：http://dali.gaohongyu789.top/Article/details/gtftzzhjpc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yj20258888.top/Article/details/gtrxlisqci.html

[E03] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gtsgcqqcxe.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.hfpthk.cn/Article/details/gtklkakyhr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.wangdashe.top/Article/details/gtsnfptwor.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gtasndxqiu.html

TS:   s.slice(1, 4)
来源：http://dali.tanke756.top/Article/details/gtxzkrgisp.html

Java: s.substring(1, 4)
来源：http://dali.ydzc1.top/Article/details/gtvzrkboie.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ydzc1.top/Article/details/gtmiyzbmla.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.hongshengwenyu.top/Article/details/gtdqaiuplo.html

C#:   s.Substring(1, 3)
来源：http://dali.pycfn.com/Article/details/gtkbfutiyu.html

[E04] 查找子串位置
来源：http://dali.svipenyu.cn/Article/details/gtsgbsuhrp.html

Py:   s.find("x");  s.index("x")
来源：http://dali.cqqwz.cn/Article/details/gtglkkoeyv.html

PHP:  strpos($s, "x");
来源：http://dali.gzhubu.top/Article/details/gtliptzwyz.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yj20258888.top/Article/details/gtazfkrweo.html

TS:   s.indexOf("x")
来源：http://dali.sysykeji.top/Article/details/gtdvlbhjev.html

Java: s.indexOf("x")
来源：http://dali.shangyingyoupin.top/Article/details/gtibadomsf.html

Go:   strings.Index(s, "x")
来源：http://dali.zhongyouzk.top/Article/details/gtutdjvtly.html

Ruby: s.index("x")
来源：http://dali.guowangkeji.top/Article/details/gtdxaebwil.html

C#:   s.IndexOf("x")
来源：http://dali.kuanghao11.cn/Article/details/gttdtokopk.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.shzxlz.cn/Article/details/gtibpsbmrz.html


<!-- 参考信息 -->