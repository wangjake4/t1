代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtuzhfkjcf.html

Go:   func add(a, b int) int
来源：http://dali.pycfn.com/Article/details/gtfelzyrle.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yvedp.cn/Article/details/gtlgaerzqf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.snrcjt.cn/Article/details/gtghdswzpo.html

[C14] 泛型函数
来源：http://dali.vqdsnc.cn/Article/details/gtuqagdokn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhiwuduotai.top/Article/details/gtjwmxeypz.html

PHP:  // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtpeqgljuf.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtcwoeemff.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xylfe.cn/Article/details/gttbsriqxb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnxiangtu.top/Article/details/gtrmfnhgfw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfedafnq.html

Ruby: # 无泛型
来源：http://dali.shzxlz.cn/Article/details/gttfcfajrj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ehwqpu.com/Article/details/gtvmotbqrz.html

[C15] 解构 / 展开参数
来源：http://dali.yuanzhike.top/Article/details/gtiuxstnob.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cashguo.top/Article/details/gtutqgektc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.meibo888.top/Article/details/gtsycrhujm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtrgyhrlva.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.meibo888.top/Article/details/gtpypfifhw.html

Java: // 无解构
来源：http://dali.tanke756.top/Article/details/gtjmysiicz.html

Go:   // 无解构
来源：http://dali.gzhubu.top/Article/details/gtqsrcqvws.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gtfdwsbytw.html

C#:   var (a, b) = pair;
来源：http://dali.zhixingplan.top/Article/details/gtczixymoh.html

[C16] 函数 / 方法重载
来源：http://dali.zhongyouzk.top/Article/details/gttlaascst.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yonumen.top/Article/details/gtmohnijik.html

PHP:  // 无重载
来源：http://dali.aizwys.cn/Article/details/gtwxvubowm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jiagoushi.top/Article/details/gtyhbvyaqh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shuidangran.top/Article/details/gtxynbffur.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gthxzsozuh.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuanzhike.top/Article/details/gtgnmugqvp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gtlcohyqxg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhoulong.xyz/Article/details/gtigvpzlnw.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzlxugugo.html

D. 数组 / 列表 / 集合
来源：http://dali.tian-w.cn/Article/details/gtbxhirarp.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gterhzskke.html

[D01] 创建数组 / 列表
来源：http://dali.tanke756.top/Article/details/gtupebxpvh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.haohaochexian.top/Article/details/gtlkasmgfj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.birdmap.top/Article/details/gtdyupixts.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigfzy.top/Article/details/gtyopsilpi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqqlcipk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.9152youxi.cn/Article/details/gticfzakdm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shangyingyoupin.top/Article/details/gtkzsarzzq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtjhrnjknf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cdnleiting.top/Article/details/gtazrrdgha.html

[D02] 追加元素到末尾
来源：http://dali.vqdsnc.cn/Article/details/gtwrjfngol.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gtgqhasxrt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guowangkeji.top/Article/details/gtzhgxtobk.html

JS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gtqoehtria.html

TS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gtghwlvakb.html

Java: list.add(4);
来源：http://dali.ybcxt.top/Article/details/gtkuufckxt.html

Go:   arr = append(arr, 4)
来源：http://dali.haohaochexian.top/Article/details/gtroexaoag.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jiagoushi.top/Article/details/gtcqbaincm.html

C#:   list.Add(4);
来源：http://dali.fzhhl.top/Article/details/gtzmomkuxw.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigufen.top/Article/details/gtoikwroft.html

Py:   arr.insert(0, 0)
来源：http://dali.yuanzhike.top/Article/details/gtilmdtwtc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.meibo888.top/Article/details/gtqmhqwglu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigufen.top/Article/details/gtyxqcmftp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtjtmncskg.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gtiiwafdmq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aizwys.cn/Article/details/gtovruqgur.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yongpay.top/Article/details/gtgotderfd.html

C#:   list.Insert(0, 0);
来源：http://dali.pycfn.com/Article/details/gtrgdcrapj.html

[D04] 删除元素
来源：http://dali.haohaochexian.top/Article/details/gttpeuvjjj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gtjicckmtu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtdbunthsz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gthrucwjsm.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gtthcfdmus.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gogol.net.cn/Article/details/gtdatmsjne.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgufenzy.top/Article/details/gtkrgwrfcp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yongpay.top/Article/details/gtwqhdzwqc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cqqwz.cn/Article/details/gtfbmotwvf.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gthmqtzwzf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtjtayyklx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffsjxskz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtcogjhuye.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gtaktqvhgh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yonumen.top/Article/details/gtxiuuuapa.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gttkcgpzby.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtghxeriwi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtiwafzxma.html

[D06] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtoppqzabs.html

Py:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtlqqpwcsm.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtnoakddpb.html

JS:   arr.length
来源：http://dali.meibo888.top/Article/details/gthlxtexnv.html

TS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gthfhswsbr.html

Java: list.size();
来源：http://dali.cheryme.top/Article/details/gttyvyutet.html

Go:   len(arr)
来源：http://dali.316326.xyz/Article/details/gtklhubwmi.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gtbnzouzzo.html

C#:   list.Count;
来源：http://dali.jqgfzy.top/Article/details/gtabvbhlng.html

[D07] 切片 / 取子数组
来源：http://dali.xylfe.cn/Article/details/gtzjzjxcls.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hammf.cn/Article/details/gtabtqsoad.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tanke756.top/Article/details/gtzggfjtxq.html

JS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gtbfmbivwk.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtqbpilcjo.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtjadtzkis.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gtdljhiygx.html

Ruby: arr[1, 3]
来源：http://dali.mhx1999.top/Article/details/gttqzazshh.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtosotrall.html

[D08] 合并两个数组
来源：http://dali.yuanzhike.top/Article/details/gtgvsjebfm.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangdashe.top/Article/details/gtjgrdqcju.html

PHP:  array_merge($a, $b);
来源：http://dali.cucudq.cn/Article/details/gtvlskyntp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.snrcjt.cn/Article/details/gtnyrhpgrt.html

TS:   [...a, ...b];
来源：http://dali.wangdashe.top/Article/details/gtfjuxaimw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtybivehlf.html

Go:   append(a, b...)
来源：http://dali.sxryk.cn/Article/details/gtjhxciiow.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnqzz.top/Article/details/gtvdngbtwf.html

C#:   a.Concat(b).ToList()
来源：http://dali.sweek.top/Article/details/gtateybbze.html

[D09] 排序（升序）
来源：http://dali.zhengqikj.top/Article/details/gtpvuwkcnw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuanzx.com/Article/details/gtcmseokek.html

PHP:  sort($arr);
来源：http://dali.mhx1999.top/Article/details/gtdlqagujz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj202588.top/Article/details/gtvyhqqpyv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ehwqpu.com/Article/details/gtozkcrpjt.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cheryme.top/Article/details/gtutofplmn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gtnnfwgbcu.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gtvhhjhcar.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gtqlycdaor.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.daria6918.cn/Article/details/gtthtlplyc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fzhhl.top/Article/details/gtbkahcnml.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guowangkeji.top/Article/details/gtmpicryde.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtiwdqiozz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gtdpsmkdgh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.birdmap.top/Article/details/gtmiungnwn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tianlin.xyz/Article/details/gthjsxkcmx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cheryme.top/Article/details/gtrgbhygcu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jyoumei.cn/Article/details/gtiwoyiqyd.html

[D11] 反转数组
来源：http://dali.gaohongyu789.top/Article/details/gtvfesnird.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigufen.top/Article/details/gtfvwmtxfh.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtogwblhzl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shanyushiyangtech.top/Article/details/gtovqnktfm.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gtxnhzrbnm.html

Java: Collections.reverse(list);
来源：http://dali.sysykeji.top/Article/details/gtiigaawdk.html

Go:   slices.Reverse(arr)
来源：http://dali.zhixingplan.top/Article/details/gtrodtnqad.html

Ruby: arr.reverse
来源：http://dali.zhixingplan.top/Article/details/gtdxboykmf.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gtrjszuiko.html

[D12] 查找元素下标
来源：http://dali.jinghuilouyu.cn/Article/details/gthiidfxsp.html

Py:   arr.index(x);  x in arr
来源：http://dali.yonumen.top/Article/details/gtlsbwuvob.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.mhx1999.top/Article/details/gtskwnrhpr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtsrbjigss.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtnoingcei.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258.top/Article/details/gtcgutbmpa.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxinkj.top/Article/details/gtcoqbcblo.html

Ruby: arr.index(x)
来源：http://dali.zhoulong.xyz/Article/details/gtykkblczs.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258888.top/Article/details/gtlfbidsjy.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangshuangyany.cn/Article/details/gttqxubrvy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigfzy.top/Article/details/gthwwraipr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.iojbl.cn/Article/details/gtgvisahew.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtldrpndke.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gttjcgkoqf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangdashe.top/Article/details/gtiqtvlyvh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxyvwsvh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jlsjyb.cn/Article/details/gtpnartqqo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yueranfly.top/Article/details/gtexecufig.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gtjxdbacdk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtwaohwter.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtberuqjbv.html

JS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtkzqxezvx.html

TS:   arr.map(x => x * 2)
来源：http://dali.snrcjt.cn/Article/details/gtopwjqovt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tanke756.top/Article/details/gtpddrgthf.html

Go:   // 手写循环
来源：http://dali.hnxiangtu.top/Article/details/gthcczotsd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtumhgnmbp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtreejhbjw.html

[D15] 去重
来源：http://dali.svipenyu.cn/Article/details/gtjluxejvq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gtumcquvmz.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gtvvruluwt.html

JS:   [...new Set(arr)]
来源：http://dali.jinqigfzy.top/Article/details/gtjfsvwrco.html

TS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtvvcnlpev.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yonumen.top/Article/details/gtbcrsenmr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shangyingyoupin.top/Article/details/gtnswfhdax.html

Ruby: arr.uniq
来源：http://dali.cdnleiting.top/Article/details/gtuzdmjmxn.html

C#:   list.Distinct().ToList()
来源：http://dali.zdqjudy.top/Article/details/gtptpjpzfn.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gtdniymybk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.andypj.xyz/Article/details/gtwacsvoru.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pycfn.com/Article/details/gtaycdwijj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gtiuhwvhes.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gtcubrljau.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.wangshuangyany.cn/Article/details/gtkfxghkcw.html

Go:   // 手写循环累加
来源：http://dali.yvedp.cn/Article/details/gtggrlxebo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hywenlv.cn/Article/details/gtlhfdryjl.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gtjcctsrkp.html

[D17] 最大值与最小值
来源：http://dali.mhx1999.top/Article/details/gtryssqedu.html

Py:   max(arr);  min(arr)
来源：http://dali.316326.xyz/Article/details/gtvuitcigd.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gthprwzlsg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfoyztpul.html

TS:   Math.max(...arr);
来源：http://dali.tianlin.xyz/Article/details/gtvhgfauwx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangdashe.top/Article/details/gtvgkhuybs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtdjwicvkx.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gtcxzopxrn.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gtrepmhnnm.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gtaivhydrq.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.mhx1999.top/Article/details/gtzmhqlkey.html

PHP:  array_merge(...$nested);
来源：http://dali.hnqzz.top/Article/details/gttqpxfaoi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ivvv.top/Article/details/gtiqowxlux.html

TS:   nested.flat();
来源：http://dali.jinyuanbaomall.cn/Article/details/gttmaoxjdb.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.iojbl.cn/Article/details/gtckaovybw.html

Go:   // 手写双层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtfuroloki.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvckfdllb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtwjgmdgut.html

[D19] 按字段分组
来源：http://dali.tian-w.cn/Article/details/gtyxfllcjj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuanzx.com/Article/details/gtvqxyhzzk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.vqdsnc.cn/Article/details/gtmshpzkom.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gzhubu.top/Article/details/gthfsqvdwg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hywenlv.cn/Article/details/gtnoxyxkct.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnqzz.top/Article/details/gtsarhoucg.html

Go:   // 手写 map[string][]T
来源：http://dali.yongpay.top/Article/details/gtcvvtrkso.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aibaodan.cn/Article/details/gtlxbwiedc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlggamdus.html

[D20] 统计每个元素出现次数
来源：http://dali.nanxinkj.top/Article/details/gthpbajchn.html

Py:   Counter(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtqnbcetll.html

PHP:  array_count_values($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtaabzsqxd.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gtgmwbvvlt.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuanzx.com/Article/details/gtzordbvcm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gtitpkgknd.html

Go:   // 手写 map[T]int
来源：http://dali.aibaodan.cn/Article/details/gtacncello.html

Ruby: arr.tally
来源：http://dali.havefunace.top/Article/details/gtafbaeyit.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.dianchejie.cn/Article/details/gtefoklsul.html

[D21] 判断是否包含某元素
来源：http://dali.cqqwz.cn/Article/details/gteemtjmjf.html

Py:   x in arr
来源：http://dali.c1oappe.top/Article/details/gtmvttvzfb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hfpthk.cn/Article/details/gtbtokjjwj.html

JS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwbhlzwlz.html

TS:   arr.includes(x)
来源：http://dali.zycfv.cn/Article/details/gticlozshf.html

Java: list.contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtrakybvyr.html

Go:   slices.Contains(arr, x)
来源：http://dali.0kj1m.cn/Article/details/gtibvzvfwj.html

Ruby: arr.include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gttaluekkr.html

C#:   list.Contains(x)
来源：http://dali.yj202588.top/Article/details/gtakkopokz.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sxryk.cn/Article/details/gtobuxddbk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shzxlz.cn/Article/details/gtrfglcazn.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yj20258.top/Article/details/gtlylrkmgl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.xinyue.icu/Article/details/gtwtbxoprp.html

TS:   [...arr];
来源：http://dali.ppjwa.cn/Article/details/gtppfwsvmn.html

Java: new ArrayList<>(list);
来源：http://dali.yj202588.top/Article/details/gtkfqfnrjz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gtbyyvciac.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gtzfgwkezj.html

C#:   new List<int>(list);
来源：http://dali.9152youxi.cn/Article/details/gtjyfqabvx.html

[D23] reduce 累积计算
来源：http://dali.feifeiyinyue.top/Article/details/gtafrogggn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ivvv.top/Article/details/gtynvqgsfa.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtycjdrpwl.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.smart0.xyz/Article/details/gtgyhchuuu.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zycfv.cn/Article/details/gtqwedtkoe.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.svipenyu.cn/Article/details/gtuomkznyt.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gtzcvtjnuf.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.vqdsnc.cn/Article/details/gtofogtrou.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.pycfn.com/Article/details/gtoerogmko.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gtsfwhjnwk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.yangfankeji.com/Article/details/gtuymxaugp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhoulong.xyz/Article/details/gtzemendxj.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gotoacloud.top/Article/details/gtdmuadohi.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrhfthed.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.ppjwa.cn/Article/details/gtyfxdcizl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yangfankeji.com/Article/details/gtmkoiiuys.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.bjfxy.top/Article/details/gtlzzoytvj.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tianlin.xyz/Article/details/gtewxopdbv.html

[D25] Set 集合去重与交并差
来源：http://dali.316326.xyz/Article/details/gtpfhkbexh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.guannengcc.top/Article/details/gtoxhrzsoy.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.xziqi.cn/Article/details/gteiukezzb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxlzokdy.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.chenzaomai.com/Article/details/gtivlwbxjd.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gtonozlprh.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hnxiangtu.top/Article/details/gtekcltqrw.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gtvueuaifi.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.tanke756.top/Article/details/gtwfrvaxtx.html

[D26] 数组转字符串
来源：http://dali.hammf.cn/Article/details/gttpromqde.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gtjkfnehtd.html

PHP:  implode(", ", $arr);
来源：http://dali.cheryme.top/Article/details/gtqjleixbk.html

JS:   arr.join(", ")
来源：http://dali.hnqzz.top/Article/details/gtxqjznlbr.html

TS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gtnqwleyxl.html

Java: String.join(", ", list)
来源：http://dali.yangfankeji.com/Article/details/gtrlzswutz.html

Go:   strings.Join(strs, ", ")
来源：http://dali.feifeiyinyue.top/Article/details/gthbxdapnj.html

Ruby: arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtkmvtustn.html

C#:   string.Join(", ", list)
来源：http://dali.bjfxy.top/Article/details/gtvsmzgnqu.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtshoybbvq.html

E. 字符串处理
来源：http://dali.sufxvd.cn/Article/details/gtrypxpeuf.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtdyyryjiw.html

[E01] 拼接字符串
来源：http://dali.zhoulong.xyz/Article/details/gtarvianbv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.zhongyouzk.top/Article/details/gtcgzqlqpg.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxorktkar.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjpgylda.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gtbcrfywmi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yongpay.top/Article/details/gthjbsdcaa.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.hammf.cn/Article/details/gtgugrsrsk.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.pycfn.com/Article/details/gtmmojuuft.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.sweek.top/Article/details/gtyjukvgwo.html

[E02] 重复字符串
来源：http://dali.xinyue.icu/Article/details/gtoomgtfqv.html

Py:   "ab" * 3
来源：http://dali.zhengqikj.top/Article/details/gtproqlwue.html

PHP:  str_repeat("ab", 3);
来源：http://dali.316326.xyz/Article/details/gtmhiitnja.html

JS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gtyfmiaujx.html

TS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtwwqrxusi.html

Java: "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gtyurlqifs.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jianghu66.top/Article/details/gtiuhglnjf.html

Ruby: "ab" * 3
来源：http://dali.jqgfzy.top/Article/details/gtlxzirpqa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhixingplan.top/Article/details/gtqpdjiliv.html

[E03] 截取子串
来源：http://dali.cheryme.top/Article/details/gtzkmdqzhx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.redwolf501.top/Article/details/gtvrmzyuuv.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.dianchejie.cn/Article/details/gteswoctje.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gtavlxyrgs.html

TS:   s.slice(1, 4)
来源：http://dali.tanke756.top/Article/details/gtaoqjyhxc.html

Java: s.substring(1, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtcfdwuofj.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yanxiufei.cn/Article/details/gtcpxdghyh.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.c1oappe.top/Article/details/gtzuayoyco.html

C#:   s.Substring(1, 3)
来源：http://dali.jqgfzy.top/Article/details/gtqgflztmx.html

[E04] 查找子串位置
来源：http://dali.xziqi.cn/Article/details/gtkwqifhkr.html

Py:   s.find("x");  s.index("x")
来源：http://dali.jlsjyb.cn/Article/details/gtrsfcqcke.html


<!-- 参考信息 -->