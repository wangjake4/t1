代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2ayxatzyd.html

Go:   func add(a, b int) int
来源：http://dali.wangdashe.top/Article/details/gt2vcmjsyyi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mnxuytfw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.snrcjt.cn/Article/details/gt2asqetnub.html

[C14] 泛型函数
来源：http://dali.sufxvd.cn/Article/details/gt2mvdftekk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guowangkeji.top/Article/details/gt2omoceqej.html

PHP:  // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gt2trmipbpb.html

JS:   // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gt2koaskrmp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xkubgpdr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cdnleiting.top/Article/details/gt2hmkbljgi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypdwwbai.html

Ruby: # 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2aeyitfvp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.0kj1m.cn/Article/details/gt2prflqlby.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2irkydrkj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sufxvd.cn/Article/details/gt2kcpnxkkg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zbawvhzz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gt2yiaomckb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2dblnpsbd.html

Java: // 无解构
来源：http://dali.birdmap.top/Article/details/gt2jmdxtjtx.html

Go:   // 无解构
来源：http://dali.andypj.xyz/Article/details/gt2vbxngppr.html

Ruby: a, b = pair
来源：http://dali.jyoumei.cn/Article/details/gt2xtrdxnht.html

C#:   var (a, b) = pair;
来源：http://dali.c1oappe.top/Article/details/gt2sisxjaxv.html

[C16] 函数 / 方法重载
来源：http://dali.cqqwz.cn/Article/details/gt2rfxgxeig.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.smart0.xyz/Article/details/gt2sitovkcm.html

PHP:  // 无重载
来源：http://dali.zdqjudy.top/Article/details/gt2tdsslvld.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxinkj.top/Article/details/gt2fasyzvbd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.316326.xyz/Article/details/gt2upeqvqii.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ydzc1.top/Article/details/gt2fpysjesd.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dyljswqz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gt2ahrtwewa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.smart0.xyz/Article/details/gt2dkhhkkzx.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2azbotvzd.html

D. 数组 / 列表 / 集合
来源：http://dali.yuxming.cn/Article/details/gt2nhawvijg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2descdvji.html

[D01] 创建数组 / 列表
来源：http://dali.haohaochexian.top/Article/details/gt2xlvvhygk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ehwqpu.com/Article/details/gt2hdkgcjpz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tian-w.cn/Article/details/gt2syqxuxtk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ybcxt.top/Article/details/gt2bezzvfjg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnqzz.top/Article/details/gt2iultiliv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ehwqpu.com/Article/details/gt2cjkekfvo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ivvv.top/Article/details/gt2ezddqzxe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aipcmxzh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aizwys.cn/Article/details/gt2rryoxigo.html

[D02] 追加元素到末尾
来源：http://dali.c1oappe.top/Article/details/gt2hqvrkego.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.birdmap.top/Article/details/gt2kmvlmgpp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yanxiufei.cn/Article/details/gt2jnzfmayr.html

JS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gt2lefdcsnw.html

TS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gt2bwaqmleo.html

Java: list.add(4);
来源：http://dali.cqqwz.cn/Article/details/gt2icszysbl.html

Go:   arr = append(arr, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2btfdlfoa.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2djeqybql.html

C#:   list.Add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2rocokivj.html

[D03] 在指定位置插入元素
来源：http://dali.chenlongwang.top/Article/details/gt2wesyxmbn.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2zsydiqgv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtyelsdo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yueranfly.top/Article/details/gt2lgebwver.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yonumen.top/Article/details/gt2nmkpuaex.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fgpfpqzm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.kuanghao11.cn/Article/details/gt2nuwqvmpr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ppjwa.cn/Article/details/gt2mzfnkfhl.html

C#:   list.Insert(0, 0);
来源：http://dali.zycfv.cn/Article/details/gt2vqlycovt.html

[D04] 删除元素
来源：http://dali.hfpthk.cn/Article/details/gt2bovnkgnn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gogol.net.cn/Article/details/gt2evqlqjsu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.bjfxy.top/Article/details/gt2ecapzwxf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuetiantiany.cn/Article/details/gt2edmnehei.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gt2cjqlivnz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sysykeji.top/Article/details/gt2hkaujdig.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sweek.top/Article/details/gt2zvobxqkw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2bgoyxcso.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yonumen.top/Article/details/gt2rovmqusv.html

[D05] 访问与修改元素
来源：http://dali.iojbl.cn/Article/details/gt2cfscpebc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gt2xgudcqdk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gt2fieqiilj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gt2fbrdtcps.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xinyue.icu/Article/details/gt2yxwrxhtg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lqwvyarr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gt2fdiwpkxt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gt2tdjecuht.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cheryme.top/Article/details/gt2ajmczthw.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gt2vcolafuq.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2zfhcffkx.html

PHP:  count($arr);
来源：http://dali.yj20258888.top/Article/details/gt2smymudil.html

JS:   arr.length
来源：http://dali.ppjwa.cn/Article/details/gt2kxdeiyef.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qerbdshm.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gt2mwiasifa.html

Go:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2evmramnk.html

Ruby: arr.length; arr.size
来源：http://dali.kuanghao11.cn/Article/details/gt2fzzytuxu.html

C#:   list.Count;
来源：http://dali.jinqigufen.top/Article/details/gt2uylhafaf.html

[D07] 切片 / 取子数组
来源：http://dali.guannengcc.top/Article/details/gt2icvynzou.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cashguo.top/Article/details/gt2fqqcicaj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2tmgtslmb.html

JS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gt2urkkmwkl.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gt2xobvpamv.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmpqfbah.html

Go:   arr[1:4]
来源：http://dali.yj20258888.top/Article/details/gt2kugtiebb.html

Ruby: arr[1, 3]
来源：http://dali.gotoacloud.top/Article/details/gt2xtegjnkh.html

C#:   list.GetRange(1, 3);
来源：http://dali.andypj.xyz/Article/details/gt2qfjtbhvq.html

[D08] 合并两个数组
来源：http://dali.zdqjudy.top/Article/details/gt2iiirlesz.html

Py:   a + b;  a.extend(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2yrgjesob.html

PHP:  array_merge($a, $b);
来源：http://dali.jyoumei.cn/Article/details/gt2wdjejzjt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.kuanghao11.cn/Article/details/gt2jrswzibk.html

TS:   [...a, ...b];
来源：http://dali.bjfxy.top/Article/details/gt2aaavkavv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2guxlcgbd.html

Go:   append(a, b...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ovgjyidm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ceubvjvx.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2bgmqntwe.html

[D09] 排序（升序）
来源：http://dali.dianchejie.cn/Article/details/gt2ktntpmnz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gt2iczyhttq.html

PHP:  sort($arr);
来源：http://dali.yj202588.top/Article/details/gt2misqktbd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258.top/Article/details/gt2xyawvxzj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258.top/Article/details/gt2jqfmhygv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuetiantiany.cn/Article/details/gt2luafczjs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gt2vczrldgf.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gt2hdjqehgg.html

C#:   list.Sort();
来源：http://dali.yongpay.top/Article/details/gt2minoktqh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shuidangran.top/Article/details/gt2tovfprgg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgufenzy.top/Article/details/gt2viciqqya.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gt2jemgttgv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gt2bpxhrrow.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrvgamc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ndfbcapa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iuetmufm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj202588.top/Article/details/gt2kpgsyzkw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.andypj.xyz/Article/details/gt2ccwlycay.html

[D11] 反转数组
来源：http://dali.jiagoushi.top/Article/details/gt2wlbfwnsj.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yonumen.top/Article/details/gt2jbezqgyd.html

PHP:  array_reverse($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2ksvggvrg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sweek.top/Article/details/gt2jvixcgaa.html

TS:   [...arr].reverse();
来源：http://dali.yueranfly.top/Article/details/gt2szhinhlq.html

Java: Collections.reverse(list);
来源：http://dali.jianghu66.top/Article/details/gt2bixrpfsz.html

Go:   slices.Reverse(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2reshdica.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gt2osfddawl.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2zcupatel.html

[D12] 查找元素下标
来源：http://dali.zdqjudy.top/Article/details/gt2zkiadfka.html

Py:   arr.index(x);  x in arr
来源：http://dali.dianchejie.cn/Article/details/gt2zsztjsgy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cdnleiting.top/Article/details/gt2fgmcvhst.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gt2ppneqcxz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yueranfly.top/Article/details/gt2flbjyrdo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lhuylhuj.html

Go:   slices.Index(arr, x)
来源：http://dali.aizwys.cn/Article/details/gt2puuxnyxb.html

Ruby: arr.index(x)
来源：http://dali.daria6918.cn/Article/details/gt2kdbzkbvy.html

C#:   list.IndexOf(x);
来源：http://dali.yvedp.cn/Article/details/gt2laxukavw.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xylfe.cn/Article/details/gt2jlakluak.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tunsmmqt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtkzztdk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2ermonent.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuxming.cn/Article/details/gt2zofhpjqo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2jpxamejo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.0kj1m.cn/Article/details/gt2sbjpbsez.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgfzy.top/Article/details/gt2akfazepk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2nlykkcuj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.mhx1999.top/Article/details/gt2wqhszvbj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xziqi.cn/Article/details/gt2rajtphgq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.pycfn.com/Article/details/gt2yrohnmjy.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzyijsqb.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2somebwfg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2gfmuhbwq.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gt2gnsvdwjw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2sirraxkb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gt2ctbiaxqq.html

[D15] 去重
来源：http://dali.gaohongyu789.top/Article/details/gt2fhjbdxas.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2cmwdqlvx.html

PHP:  array_unique($arr);
来源：http://dali.aibaodan.cn/Article/details/gt2mvobkmcq.html

JS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gt2towwjtwp.html

TS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gt2ttnniowc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.kuanghao11.cn/Article/details/gt2gehdqujk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yuxming.cn/Article/details/gt2bronjtmn.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvqncyzo.html

C#:   list.Distinct().ToList()
来源：http://dali.gzhubu.top/Article/details/gt2yzclwhut.html

[D16] 求和与平均值
来源：http://dali.hywenlv.cn/Article/details/gt2praevjrk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258.top/Article/details/gt2eaubcepo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2iserjvqx.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gt2tdmzbjnp.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tianlin.xyz/Article/details/gt2wwgpnqdn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guowangkeji.top/Article/details/gt2bqqtksof.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gt2bbmyyqev.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.smart0.xyz/Article/details/gt2pezxdvuv.html

C#:   list.Sum();  list.Average()
来源：http://dali.yvedp.cn/Article/details/gt2kfoprbwe.html

[D17] 最大值与最小值
来源：http://dali.tian-w.cn/Article/details/gt2rwbonbwl.html

Py:   max(arr);  min(arr)
来源：http://dali.ybcxt.top/Article/details/gt2mbnsyrkd.html

PHP:  max($arr);  min($arr);
来源：http://dali.tian-w.cn/Article/details/gt2bpamlilm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.tianlin.xyz/Article/details/gt2lxnydxzr.html

TS:   Math.max(...arr);
来源：http://dali.jyoumei.cn/Article/details/gt2wqvjryrf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj202588.top/Article/details/gt2avcffelt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2wbwqswrh.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kyvonkrd.html

C#:   list.Max();  list.Min()
来源：http://dali.birdmap.top/Article/details/gt2uctntfzg.html

[D18] 扁平化嵌套数组
来源：http://dali.hfpthk.cn/Article/details/gt2befaferw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ivvv.top/Article/details/gt2ivwatwbn.html

PHP:  array_merge(...$nested);
来源：http://dali.daxiang520.top/Article/details/gt2dtptauks.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.havefunace.top/Article/details/gt2uvbpapyb.html

TS:   nested.flat();
来源：http://dali.yongpay.top/Article/details/gt2gycmjidz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.guowangkeji.top/Article/details/gt2xyvehpif.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gt2rclunqeh.html

Ruby: nested.flatten
来源：http://dali.guowangkeji.top/Article/details/gt2qngqabmi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2clndsvfj.html

[D19] 按字段分组
来源：http://dali.hammf.cn/Article/details/gt2rixsjgin.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fzhhl.top/Article/details/gt2sqpjshcd.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.mhx1999.top/Article/details/gt2fegfvqbi.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hywenlv.cn/Article/details/gt2vtjthqdt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xylfe.cn/Article/details/gt2yvfhysjx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gt2mkxqfxyp.html

Go:   // 手写 map[string][]T
来源：http://dali.mhx1999.top/Article/details/gt2dzwrfruj.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gaohongyu789.top/Article/details/gt2muwcoqsw.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.svipenyu.cn/Article/details/gt2kywxmums.html

[D20] 统计每个元素出现次数
来源：http://dali.quarkkingdee.top/Article/details/gt2iaaouaef.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2yggshjgy.html

PHP:  array_count_values($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2kgnwbsoc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hysaishi.cn/Article/details/gt2mlvwnyuc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gt2pidtttxe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jqgufenzy.top/Article/details/gt2fqechauk.html

Go:   // 手写 map[T]int
来源：http://dali.yvedp.cn/Article/details/gt2aduxmafi.html

Ruby: arr.tally
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhwkulx.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.pengpengdd.cyou/Article/details/gt2rjbnirai.html

[D21] 判断是否包含某元素
来源：http://dali.hammf.cn/Article/details/gt2zvrpsozs.html

Py:   x in arr
来源：http://dali.meibo888.top/Article/details/gt2eejyromx.html

PHP:  in_array($x, $arr, true);
来源：http://dali.hnxiangtu.top/Article/details/gt2aozgefdn.html

JS:   arr.includes(x)
来源：http://dali.redwolf501.top/Article/details/gt2pprgzuye.html

TS:   arr.includes(x)
来源：http://dali.ivvv.top/Article/details/gt2sdfaxuuz.html

Java: list.contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2gkbpxbxw.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2ylwqyvhc.html

Ruby: arr.include?(x)
来源：http://dali.zycfv.cn/Article/details/gt2afaxcmde.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2mhtlvvek.html

[D22] 复制数组（避免共享引用）
来源：http://dali.hywenlv.cn/Article/details/gt2yrlscpbz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2gilegaxs.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.nanxinkj.top/Article/details/gt2wutfizkz.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2esexvich.html

TS:   [...arr];
来源：http://dali.sufxvd.cn/Article/details/gt2rsmvijra.html

Java: new ArrayList<>(list);
来源：http://dali.redwolf501.top/Article/details/gt2djcnceuq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.tianlin.xyz/Article/details/gt2kmywvjri.html

Ruby: arr.dup;  arr.clone
来源：http://dali.shuidangran.top/Article/details/gt2tltjlell.html

C#:   new List<int>(list);
来源：http://dali.gaohongyu789.top/Article/details/gt2xnlhloev.html

[D23] reduce 累积计算
来源：http://dali.vqdsnc.cn/Article/details/gt2xrauapdn.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.smart0.xyz/Article/details/gt2hkslrebg.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhuwkrmd.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gt2wezyhhrj.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2umvzxhho.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yongpay.top/Article/details/gt2iljshhru.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gt2ajecbcyj.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.gzhubu.top/Article/details/gt2ewimrzsp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.nwbrower.top/Article/details/gt2jyarkxuf.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj202588.top/Article/details/gt2idivqjzw.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jianghu66.top/Article/details/gt2nwrbbnqc.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.xylfe.cn/Article/details/gt2dwmyowoi.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2fdstrigl.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2pljcwgbj.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.fzhhl.top/Article/details/gt2jhkehzwm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnxiangtu.top/Article/details/gt2enfnueze.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zycfv.cn/Article/details/gt2qteyzkfk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.redwolf501.top/Article/details/gt2tukiivyk.html

[D25] Set 集合去重与交并差
来源：http://dali.cashguo.top/Article/details/gt2lhsfkulu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gt2ksnwjeht.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.jiagoushi.top/Article/details/gt2zdxojkda.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dffhmmer.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.tanke756.top/Article/details/gt2gbnuhcor.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.zhoulong.xyz/Article/details/gt2lnncpxay.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.ppjwa.cn/Article/details/gt2ukxfoiay.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tanke756.top/Article/details/gt2molclrxm.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.chenzaomai.com/Article/details/gt2kyukrezh.html

[D26] 数组转字符串
来源：http://dali.yueranfly.top/Article/details/gt2ykalsicf.html

Py:   ", ".join(map(str, arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2faxhtrwn.html

PHP:  implode(", ", $arr);
来源：http://dali.chenlongwang.top/Article/details/gt2hgaxsqtn.html

JS:   arr.join(", ")
来源：http://dali.iojbl.cn/Article/details/gt2myrrgejx.html

TS:   arr.join(", ")
来源：http://dali.svipenyu.cn/Article/details/gt2wbwaulbu.html

Java: String.join(", ", list)
来源：http://dali.andypj.xyz/Article/details/gt2patsssdb.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hammf.cn/Article/details/gt2wyputrvw.html

Ruby: arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2weqybhqf.html

C#:   string.Join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gt2wzhhrbzy.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2bcwcufxz.html

E. 字符串处理
来源：http://dali.vqdsnc.cn/Article/details/gt2fsvronbs.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2otuvcega.html

[E01] 拼接字符串
来源：http://dali.guannengcc.top/Article/details/gt2nnryjlis.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.dashuyun.cn/Article/details/gt2xyperzxo.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbdcfqts.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.c1oappe.top/Article/details/gt2unmykjbp.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dianchejie.cn/Article/details/gt2jiywpnzt.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jqgufenzy.top/Article/details/gt2uqfnzijk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.wangdashe.top/Article/details/gt2ugpirufn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zdqjudy.top/Article/details/gt2ibskibkj.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yonumen.top/Article/details/gt2zuplrohh.html

[E02] 重复字符串
来源：http://dali.cdnleiting.top/Article/details/gt2nqvgugkr.html

Py:   "ab" * 3
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uumlhpdg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yangfankeji.com/Article/details/gt2ndxdggqs.html

JS:   "ab".repeat(3)
来源：http://dali.bjfxy.top/Article/details/gt2jbhbexex.html

TS:   "ab".repeat(3)
来源：http://dali.guowangkeji.top/Article/details/gt2fbglmpdd.html

Java: "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gt2cnmmlwku.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxiydkkx.html

Ruby: "ab" * 3
来源：http://dali.pycfn.com/Article/details/gt2gomxxbks.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hnxiangtu.top/Article/details/gt2dzyhuvmt.html

[E03] 截取子串
来源：http://dali.wangshuangyany.cn/Article/details/gt2kplopxqx.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jqgufenzy.top/Article/details/gt2wetqlofm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gt2xcqweadc.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gt2xzjljiub.html

TS:   s.slice(1, 4)
来源：http://dali.hysaishi.cn/Article/details/gt2oyfhwcvx.html

Java: s.substring(1, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2nodzgdml.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nwbrower.top/Article/details/gt2smpmwvbf.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.haohaochexian.top/Article/details/gt2wjgstrcw.html

C#:   s.Substring(1, 3)
来源：http://dali.shzxlz.cn/Article/details/gt2slzsdfws.html

[E04] 查找子串位置
来源：http://dali.cheryme.top/Article/details/gt2troatafa.html

Py:   s.find("x");  s.index("x")
来源：http://dali.c1oappe.top/Article/details/gt2hwubrplg.html


<!-- 参考信息 -->