代发 wailian999

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhixingplan.top/Article/details/gt2leaofqpr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gt2kyvpmski.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnqzz.top/Article/details/gt2ptjdjufp.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gt2xrvzvfwa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.0kj1m.cn/Article/details/gt2ggiuijcu.html

[C15] 解构 / 展开参数
来源：http://dali.316326.xyz/Article/details/gt2jgghpdiw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gt2fuuxoapq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aibaodan.cn/Article/details/gt2gcxnqmjn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tesxlhti.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xziqi.cn/Article/details/gt2uyyrnckx.html

Java: // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gt2pkzwpiet.html

Go:   // 无解构
来源：http://dali.yvedp.cn/Article/details/gt2zfmccgsg.html

Ruby: a, b = pair
来源：http://dali.c1oappe.top/Article/details/gt2oxmhfwwv.html

C#:   var (a, b) = pair;
来源：http://dali.birdmap.top/Article/details/gt2yuowtflb.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gt2jhkwjytx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.316326.xyz/Article/details/gt2qugyzidp.html

PHP:  // 无重载
来源：http://dali.xinyue.icu/Article/details/gt2fccegtog.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuanzx.com/Article/details/gt2sblepbos.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yongpay.top/Article/details/gt2cdmseqbx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daria6918.cn/Article/details/gt2anhfikbh.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnxiangtu.top/Article/details/gt2yadxquev.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gogol.net.cn/Article/details/gt2bftxokdx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.haohaochexian.top/Article/details/gt2fpbosyfu.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2pryychab.html

D. 数组 / 列表 / 集合
来源：http://dali.xinyue.icu/Article/details/gt2lritqxuu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2hutwmxmd.html

[D01] 创建数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gt2hmwgjodw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gotoacloud.top/Article/details/gt2vcmhlpnx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258.top/Article/details/gt2epvcrgsi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daria6918.cn/Article/details/gt2xqtslwmo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.vqdsnc.cn/Article/details/gt2fgzgalny.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj202588.top/Article/details/gt2srdxcdms.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.9152youxi.cn/Article/details/gt2muitrovd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.c1oappe.top/Article/details/gt2alucacwo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuanzhike.top/Article/details/gt2krjfezsi.html

[D02] 追加元素到末尾
来源：http://dali.ydzc1.top/Article/details/gt2innjdpwi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gt2iakgvgxb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkperewf.html

JS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gt2yjibrabm.html

TS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gt2vvsjvxxo.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gt2bvszrvph.html

Go:   arr = append(arr, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umutyfwr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gogol.net.cn/Article/details/gt2mptzcowz.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gt2eraimlvi.html

[D03] 在指定位置插入元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjvxydsl.html

Py:   arr.insert(0, 0)
来源：http://dali.yj202588.top/Article/details/gt2thrfzjdu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.vqdsnc.cn/Article/details/gt2hkiruxyw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dianchejie.cn/Article/details/gt2pmjsedts.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2ksmosprr.html

Java: list.add(0, 0);
来源：http://dali.cucudq.cn/Article/details/gt2glzzxznb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gt2mxyosyay.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.vqdsnc.cn/Article/details/gt2sobysxmu.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2wkolacrc.html

[D04] 删除元素
来源：http://dali.chenzaomai.com/Article/details/gt2jgdzxmdu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2gvzxghxp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2zifjpfra.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqgkmcrn.html

TS:   arr.splice(0, 1);
来源：http://dali.xylfe.cn/Article/details/gt2ewbsqijq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2gimaahpw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ppjwa.cn/Article/details/gt2qeizmwdd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sweek.top/Article/details/gt2satsvaps.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sysykeji.top/Article/details/gt2bzrhnfoz.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gt2qyrxudmd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gt2feqqdrvu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gt2usjbzmob.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gt2bqxpqpvz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yonumen.top/Article/details/gt2dxqgeotz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daria6918.cn/Article/details/gt2gfszzjvo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gt2tligqcvr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gt2ikjwyogx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2omcqhxnx.html

[D06] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gt2urigfocb.html

Py:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2pftyfnfw.html

PHP:  count($arr);
来源：http://dali.guannengcc.top/Article/details/gt2mcsqklsx.html

JS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gt2ixcwecsh.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gt2xqlcvdeb.html

Java: list.size();
来源：http://dali.smart0.xyz/Article/details/gt2koisjovr.html

Go:   len(arr)
来源：http://dali.zycfv.cn/Article/details/gt2xcpmbevn.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gt2wipurlyu.html

C#:   list.Count;
来源：http://dali.0kj1m.cn/Article/details/gt2igpgiunc.html

[D07] 切片 / 取子数组
来源：http://dali.nanxuanxn.top/Article/details/gt2cyddgycx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.0kj1m.cn/Article/details/gt2mtiiznuo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhwkcjye.html

JS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gt2gqsiihkl.html

TS:   arr.slice(1, 4);
来源：http://dali.ehwqpu.com/Article/details/gt2rjlpugkl.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2ybrzugdo.html

Go:   arr[1:4]
来源：http://dali.jinqigfzy.top/Article/details/gt2olkuehez.html

Ruby: arr[1, 3]
来源：http://dali.zhongyouzk.top/Article/details/gt2zxklkrns.html

C#:   list.GetRange(1, 3);
来源：http://dali.guowangkeji.top/Article/details/gt2lrwovatc.html

[D08] 合并两个数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2avoudkxc.html

Py:   a + b;  a.extend(b)
来源：http://dali.fengsongda.top/Article/details/gt2jkmvqads.html

PHP:  array_merge($a, $b);
来源：http://dali.ivvv.top/Article/details/gt2xklczqim.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gotoacloud.top/Article/details/gt2isbumylt.html

TS:   [...a, ...b];
来源：http://dali.jinqigufen.top/Article/details/gt2vlbiflhd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2yifkigqe.html

Go:   append(a, b...)
来源：http://dali.aizwys.cn/Article/details/gt2iciqpvka.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hywenlv.cn/Article/details/gt2vcwgtldq.html

C#:   a.Concat(b).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2rmfrygxm.html

[D09] 排序（升序）
来源：http://dali.tanke756.top/Article/details/gt2ulihpkgm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gt2tjjdtaim.html

PHP:  sort($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2vyxfdxlo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shzxlz.cn/Article/details/gt2bnwqqtoi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cucudq.cn/Article/details/gt2fkyejzuy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fbnzhdig.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2eressppw.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gt2nqzqemoc.html

C#:   list.Sort();
来源：http://dali.birdmap.top/Article/details/gt2wzgxrspx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hfpthk.cn/Article/details/gt2tpvisdyh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.meibo888.top/Article/details/gt2mvxnqwyg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gt2nryuzvma.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gt2iwbqzdwn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gt2mvdjbyas.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dashuyun.cn/Article/details/gt2nalpburj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jyoumei.cn/Article/details/gt2pusyeuqm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sxryk.cn/Article/details/gt2thpcorrn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gogol.net.cn/Article/details/gt2zyfacwvc.html

[D11] 反转数组
来源：http://dali.yuanzhike.top/Article/details/gt2vlrlywkr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinqigfzy.top/Article/details/gt2yafaulam.html

PHP:  array_reverse($arr);
来源：http://dali.ydzc1.top/Article/details/gt2npseenkv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.birdmap.top/Article/details/gt2lfimgldm.html

TS:   [...arr].reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugwnqsty.html

Java: Collections.reverse(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkpbaqkr.html

Go:   slices.Reverse(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2wbuxmccn.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gt2cfkisrel.html

C#:   list.Reverse();
来源：http://dali.daria6918.cn/Article/details/gt2pkgtcqja.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gt2exqkluuf.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258888.top/Article/details/gt2ysfugsjf.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.pycfn.com/Article/details/gt2mfqdafff.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2veyqauei.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sysykeji.top/Article/details/gt2vpoyuhcq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gt2pesfqppt.html

Go:   slices.Index(arr, x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jiudntth.html

Ruby: arr.index(x)
来源：http://dali.havefunace.top/Article/details/gt2xzornkni.html

C#:   list.IndexOf(x);
来源：http://dali.fzhhl.top/Article/details/gt2lnahdlbi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xinyue.icu/Article/details/gt2rludsokm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.havefunace.top/Article/details/gt2oiufzewj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntrrinec.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gt2bauqlvad.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ydzc1.top/Article/details/gt2iymblcsu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jyoumei.cn/Article/details/gt2kbfdxtca.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yueranfly.top/Article/details/gt2eemcupqv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yvedp.cn/Article/details/gt2cnmmoigp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2klvrokqy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gaohongyu789.top/Article/details/gt2zpebwxky.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xylfe.cn/Article/details/gt2vzupadja.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.birdmap.top/Article/details/gt2mrujsfra.html

JS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gt2ynmclaod.html

TS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gt2gqbjpann.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sysykeji.top/Article/details/gt2egzpfuhc.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltnddqmm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2skepgwzj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2ohtmchjx.html

[D15] 去重
来源：http://dali.jyoumei.cn/Article/details/gt2qghqargu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mgizctup.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vksyvgns.html

JS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gt2gufiiivo.html

TS:   [...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gt2bkgvcwmk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gt2ekbjstct.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.wangdashe.top/Article/details/gt2xweanngx.html

Ruby: arr.uniq
来源：http://dali.snrcjt.cn/Article/details/gt2kssdtobt.html

C#:   list.Distinct().ToList()
来源：http://dali.mhx1999.top/Article/details/gt2dnwdzfxs.html

[D16] 求和与平均值
来源：http://dali.bjfxy.top/Article/details/gt2onxumvob.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2augzastz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.meibo888.top/Article/details/gt2cdgztfju.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gt2orbzrevq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gt2mbqxxnwb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cdnleiting.top/Article/details/gt2tawxglgz.html

Go:   // 手写循环累加
来源：http://dali.dianchejie.cn/Article/details/gt2exirgvak.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yangfankeji.com/Article/details/gt2aewtvryx.html

C#:   list.Sum();  list.Average()
来源：http://dali.yangfankeji.com/Article/details/gt2rimkrspx.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gt2bdxjjtbo.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2olpvnyez.html

PHP:  max($arr);  min($arr);
来源：http://dali.yvedp.cn/Article/details/gt2ksyeameu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2apbwfqbl.html

TS:   Math.max(...arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2qpwsfkdy.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.9152youxi.cn/Article/details/gt2xcxodbux.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2zjglkmis.html

Ruby: arr.max;  arr.min
来源：http://dali.jlsjyb.cn/Article/details/gt2dkyjnzhd.html

C#:   list.Max();  list.Min()
来源：http://dali.tian-w.cn/Article/details/gt2bufhiesq.html

[D18] 扁平化嵌套数组
来源：http://dali.gogol.net.cn/Article/details/gt2jxboppch.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangdashe.top/Article/details/gt2sbbcnken.html

PHP:  array_merge(...$nested);
来源：http://dali.hnqzz.top/Article/details/gt2lgsiwiud.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tianlin.xyz/Article/details/gt2vwywruij.html

TS:   nested.flat();
来源：http://dali.daxiang520.top/Article/details/gt2drkjvvcr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ybcxt.top/Article/details/gt2fqcpfmow.html

Go:   // 手写双层循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2yyzdrbzo.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fjsjxiyx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2qzfrrxcs.html

[D19] 按字段分组
来源：http://dali.aizwys.cn/Article/details/gt2veyvegpa.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.xuanzx.com/Article/details/gt2ngjovezm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.vqdsnc.cn/Article/details/gt2shqiafzz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ehwqpu.com/Article/details/gt2vbobugjx.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.316326.xyz/Article/details/gt2tzrdqmaf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xylfe.cn/Article/details/gt2nkjutfdi.html

Go:   // 手写 map[string][]T
来源：http://dali.nwbrower.top/Article/details/gt2vkidxfsq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yueranfly.top/Article/details/gt2bmwxoagb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ydzc1.top/Article/details/gt2ydpynyph.html

[D20] 统计每个元素出现次数
来源：http://dali.hfpthk.cn/Article/details/gt2fprevhfh.html

Py:   Counter(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2rtvxwgst.html

PHP:  array_count_values($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2zkydxxqj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shzxlz.cn/Article/details/gt2rebtptks.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yangfankeji.com/Article/details/gt2nacrszcu.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nwbrower.top/Article/details/gt2nyrrrknh.html

Go:   // 手写 map[T]int
来源：http://dali.wangshuangyany.cn/Article/details/gt2pdqwvvqd.html

Ruby: arr.tally
来源：http://dali.zdqjudy.top/Article/details/gt2xgoyanjt.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.bjfxy.top/Article/details/gt2ugsphbep.html

[D21] 判断是否包含某元素
来源：http://dali.xziqi.cn/Article/details/gt2gkkgpnla.html

Py:   x in arr
来源：http://dali.yanxiufei.cn/Article/details/gt2pqjcdwqd.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yongpay.top/Article/details/gt2jbueqrlf.html

JS:   arr.includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xzwuryhs.html

TS:   arr.includes(x)
来源：http://dali.9152youxi.cn/Article/details/gt2weuqlfme.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2jldwmfei.html

Go:   slices.Contains(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2boxnladg.html

Ruby: arr.include?(x)
来源：http://dali.smart0.xyz/Article/details/gt2fydqtymd.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2grzwhpge.html

[D22] 复制数组（避免共享引用）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xlydoxgz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tian-w.cn/Article/details/gt2qfmlkyas.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinqigfzy.top/Article/details/gt2zigiipkf.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2suiyhajy.html

TS:   [...arr];
来源：http://dali.redwolf501.top/Article/details/gt2kmizothy.html

Java: new ArrayList<>(list);
来源：http://dali.sweek.top/Article/details/gt2cexmusfg.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.zhengqikj.top/Article/details/gt2oxvwwyto.html

Ruby: arr.dup;  arr.clone
来源：http://dali.9152youxi.cn/Article/details/gt2hxesjznp.html

C#:   new List<int>(list);
来源：http://dali.xylfe.cn/Article/details/gt2olseufah.html

[D23] reduce 累积计算
来源：http://dali.wangdashe.top/Article/details/gt2zlhztcpv.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2oihincyr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2vtabkuue.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2reenqynw.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2rbofedtz.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmqexsvc.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gt2stmmzhss.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.chenzaomai.com/Article/details/gt2vpqkpkmw.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.havefunace.top/Article/details/gt2lryblmlv.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwqmhltm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.feifeiyinyue.top/Article/details/gt2twqxbjog.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fvtdbcdb.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.ydzc1.top/Article/details/gt2gqrxctpr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.ivvv.top/Article/details/gt2ysrsftde.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.mhx1999.top/Article/details/gt2nsqtdfvc.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.ydzc1.top/Article/details/gt2talqlidd.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.shuidangran.top/Article/details/gt2fepidapt.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cqqwz.cn/Article/details/gt2zhtmgoez.html

[D25] Set 集合去重与交并差
来源：http://dali.hywenlv.cn/Article/details/gt2ktselokh.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.gotoacloud.top/Article/details/gt2kgurolod.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gogol.net.cn/Article/details/gt2nbmxvpea.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.yanxiufei.cn/Article/details/gt2zpuapzjb.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hnxiangtu.top/Article/details/gt2cxwravfh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.meibo888.top/Article/details/gt2tkhbumch.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guannengcc.top/Article/details/gt2oaittgcm.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.daxiang520.top/Article/details/gt2fdfaxztk.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.cucudq.cn/Article/details/gt2qpbyydtk.html

[D26] 数组转字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2wuktbpia.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hywenlv.cn/Article/details/gt2pqawkjdc.html

PHP:  implode(", ", $arr);
来源：http://dali.xuanzx.com/Article/details/gt2foppbgol.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2okngjypj.html

TS:   arr.join(", ")
来源：http://dali.gzhubu.top/Article/details/gt2xsmlqzwr.html

Java: String.join(", ", list)
来源：http://dali.zycfv.cn/Article/details/gt2upnbcclc.html

Go:   strings.Join(strs, ", ")
来源：http://dali.nanxuanxn.top/Article/details/gt2npkpylxx.html

Ruby: arr.join(", ")
来源：http://dali.ppjwa.cn/Article/details/gt2zhpkkgvf.html

C#:   string.Join(", ", list)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqybctvk.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2bsgmtxzk.html

E. 字符串处理
来源：http://dali.cheryme.top/Article/details/gt2cziiovgv.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2aqqhxxsu.html

[E01] 拼接字符串
来源：http://dali.xziqi.cn/Article/details/gt2bksaspsv.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.hammf.cn/Article/details/gt2djyfqyad.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bzxoyrqj.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.gaohongyu789.top/Article/details/gt2roohajto.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gt2dlyemokk.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jhjnmxrd.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.zhengqikj.top/Article/details/gt2omjqjrdl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cashguo.top/Article/details/gt2wcjsuasr.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.chenzaomai.com/Article/details/gt2tgachlgk.html

[E02] 重复字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2lqrgavdo.html

Py:   "ab" * 3
来源：http://dali.guowangkeji.top/Article/details/gt2gqanlcdj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.haohaochexian.top/Article/details/gt2hwovjwxb.html

JS:   "ab".repeat(3)
来源：http://dali.hammf.cn/Article/details/gt2ohbrghay.html

TS:   "ab".repeat(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sciydbom.html

Java: "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2lpxoqaap.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuxming.cn/Article/details/gt2wbnifein.html

Ruby: "ab" * 3
来源：http://dali.gzhubu.top/Article/details/gt2uacptqyz.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.haohaochexian.top/Article/details/gt2mfjqobrx.html

[E03] 截取子串
来源：http://dali.jqgfzy.top/Article/details/gt2thtqkpge.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.svipenyu.cn/Article/details/gt2kwtsitpj.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2nefrtosy.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.daxiang520.top/Article/details/gt2loaeyagv.html

TS:   s.slice(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gt2cddcjoet.html

Java: s.substring(1, 4)
来源：http://dali.svipenyu.cn/Article/details/gt2upaaksta.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.zhongyouzk.top/Article/details/gt2gybybmli.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.0kj1m.cn/Article/details/gt2nkjrwsmx.html

C#:   s.Substring(1, 3)
来源：http://dali.gzhubu.top/Article/details/gt2aslsfrdm.html

[E04] 查找子串位置
来源：http://dali.wangshuangyany.cn/Article/details/gt2zwtcpkhu.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fkwzdlil.html

PHP:  strpos($s, "x");
来源：http://dali.tianlin.xyz/Article/details/gt2udipafaw.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jqgufenzy.top/Article/details/gt2ezulsukh.html

TS:   s.indexOf("x")
来源：http://dali.cucudq.cn/Article/details/gt2dfrykqzu.html

Java: s.indexOf("x")
来源：http://dali.zhengqikj.top/Article/details/gt2yfmbwjvg.html

Go:   strings.Index(s, "x")
来源：http://dali.meibo888.top/Article/details/gt2kkggfngw.html

Ruby: s.index("x")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gzttptpi.html

C#:   s.IndexOf("x")
来源：http://dali.cashguo.top/Article/details/gt2aaxwhpod.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.ybcxt.top/Article/details/gt2facjxkth.html


<!-- 参考信息 -->