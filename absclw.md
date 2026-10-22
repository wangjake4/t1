代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gt2tkaidici.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2sdrtdvtl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gt2ajeozeza.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2hwnzxztw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2lqtevktn.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gt2jkylsmct.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gt2xqwsxcvs.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.svipenyu.cn/Article/details/gt2ynhgwqbo.html

[C14] 泛型函数
来源：http://dali.cashguo.top/Article/details/gt2rziqrivz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gt2fybwpgav.html

PHP:  // 无泛型
来源：http://dali.redwolf501.top/Article/details/gt2ziffwjmg.html

JS:   // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gt2ibkswsww.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.0kj1m.cn/Article/details/gt2nmfnstcb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ppjwa.cn/Article/details/gt2fhvsjasp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cucudq.cn/Article/details/gt2ucesoksm.html

Ruby: # 无泛型
来源：http://dali.havefunace.top/Article/details/gt2xxvsfrbo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ppjwa.cn/Article/details/gt2nziuntql.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gt2vnqfdkwd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnroygyd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuanzx.com/Article/details/gt2tovnrqml.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fcmodhek.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zycfv.cn/Article/details/gt2jzlsgqnz.html

Java: // 无解构
来源：http://dali.jianghu66.top/Article/details/gt2sdofspit.html

Go:   // 无解构
来源：http://dali.andypj.xyz/Article/details/gt2sxajeqvo.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cpjczxqj.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gt2gnyitmig.html

[C16] 函数 / 方法重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cvgtsftz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xziqi.cn/Article/details/gt2vrimkpwt.html

PHP:  // 无重载
来源：http://dali.xinyue.icu/Article/details/gt2eevnnsdl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgufenzy.top/Article/details/gt2kjhbxyjd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gt2kcijkgdi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxinkj.top/Article/details/gt2etjfncdx.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gt2ujtoofqr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hwxllqoo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhxoaste.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ektmhyum.html

D. 数组 / 列表 / 集合
来源：http://dali.daria6918.cn/Article/details/gt2esfctmkj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2rhhdybfv.html

[D01] 创建数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gt2rpgejznq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gt2dbwiabsx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gt2nxpgaxky.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xylfe.cn/Article/details/gt2hqavoksp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhengqikj.top/Article/details/gt2rrhcgqfq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yangfankeji.com/Article/details/gt2biukpcuq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnqzz.top/Article/details/gt2xwdsqoir.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tanke756.top/Article/details/gt2sviwsqtt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gpweldis.html

[D02] 追加元素到末尾
来源：http://dali.zhengqikj.top/Article/details/gt2dhzbewwe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gt2ekkqcebj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sxryk.cn/Article/details/gt2qwugpair.html

JS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gt2wgeyqxwg.html

TS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bckglzzd.html

Java: list.add(4);
来源：http://dali.gaohongyu789.top/Article/details/gt2gtzjdotk.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgufenzy.top/Article/details/gt2ylckgkwz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zdqjudy.top/Article/details/gt2ynboeacq.html

C#:   list.Add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2exkaeeff.html

[D03] 在指定位置插入元素
来源：http://dali.shzxlz.cn/Article/details/gt2nwzjlaiv.html

Py:   arr.insert(0, 0)
来源：http://dali.fzhhl.top/Article/details/gt2blmjwboe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jianghu66.top/Article/details/gt2aygylhau.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tian-w.cn/Article/details/gt2jtrwhwht.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2fxsbsnak.html

Java: list.add(0, 0);
来源：http://dali.fzhhl.top/Article/details/gt2yljypfii.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aizwys.cn/Article/details/gt2xdtqatwk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tian-w.cn/Article/details/gt2mdsavrui.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2atrxfrwy.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gt2kndhobpn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oyhjqyif.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2jqitfgqk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gotoacloud.top/Article/details/gt2lifapdop.html

TS:   arr.splice(0, 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmjunydy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.andypj.xyz/Article/details/gt2sehfptgo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sufxvd.cn/Article/details/gt2rnrbaaab.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gt2ljnorgsg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fzhhl.top/Article/details/gt2sipejaxe.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gt2ttawxjmu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gt2imhiocsf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gt2pcfkqhhz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gt2hivrcdun.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.c1oappe.top/Article/details/gt2bdvqwraw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhongyouzk.top/Article/details/gt2uwqwuiee.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kngycqqb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gt2ctirmqov.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gt2pgtviiav.html

[D06] 数组长度
来源：http://dali.yj20258.top/Article/details/gt2ltcnwcdt.html

Py:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2epadwkdx.html

PHP:  count($arr);
来源：http://dali.cashguo.top/Article/details/gt2loajwyrf.html

JS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2tysbxltr.html

TS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gt2vpcbjdcg.html

Java: list.size();
来源：http://dali.cucudq.cn/Article/details/gt2srotlpgc.html

Go:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2mjiminoe.html

Ruby: arr.length; arr.size
来源：http://dali.chenlongwang.top/Article/details/gt2cdiybvfk.html

C#:   list.Count;
来源：http://dali.zhoulong.xyz/Article/details/gt2ylkluwze.html

[D07] 切片 / 取子数组
来源：http://dali.yongpay.top/Article/details/gt2dhmxetmg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cucudq.cn/Article/details/gt2jrcgmbwf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gt2zlolexha.html

JS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gt2grwejovv.html

TS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2vnkdwrcb.html

Java: list.subList(1, 4);
来源：http://dali.ydzc1.top/Article/details/gt2xjupfgex.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gt2gahhbteh.html

Ruby: arr[1, 3]
来源：http://dali.aizwys.cn/Article/details/gt2livoodfr.html

C#:   list.GetRange(1, 3);
来源：http://dali.hammf.cn/Article/details/gt2hknzuxuu.html

[D08] 合并两个数组
来源：http://dali.smart0.xyz/Article/details/gt2rcjyupeb.html

Py:   a + b;  a.extend(b)
来源：http://dali.yanxiufei.cn/Article/details/gt2wpcxhpxp.html

PHP:  array_merge($a, $b);
来源：http://dali.yj20258888.top/Article/details/gt2atxjihxl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aibaodan.cn/Article/details/gt2kigvpgdb.html

TS:   [...a, ...b];
来源：http://dali.fengsongda.top/Article/details/gt2xydsybvk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xfimjfui.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gt2ximhvrlo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gt2yorrrmfe.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gt2grqyligm.html

[D09] 排序（升序）
来源：http://dali.316326.xyz/Article/details/gt2teliyjde.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gt2jpuxybrj.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbccrlwp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zdqjudy.top/Article/details/gt2xffvojye.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2senixkqu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwuzbufo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gt2bsnfwdcf.html

Ruby: arr.sort
来源：http://dali.316326.xyz/Article/details/gt2eoakotcb.html

C#:   list.Sort();
来源：http://dali.havefunace.top/Article/details/gt2nshmjmql.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jlsjyb.cn/Article/details/gt2jjmxijss.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhengqikj.top/Article/details/gt2tnbnptay.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gt2krelnnge.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gt2fgxugbod.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gt2jysfsghf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gt2ptyvlgkv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tianlin.xyz/Article/details/gt2fgptggzq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.mhx1999.top/Article/details/gt2wlxnznaj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjywsmkz.html

[D11] 反转数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2frvjwrzd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gt2jjuirwzm.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gt2pztigvmt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xinyue.icu/Article/details/gt2wklcqhgh.html

TS:   [...arr].reverse();
来源：http://dali.yj202588.top/Article/details/gt2bdxadujd.html

Java: Collections.reverse(list);
来源：http://dali.ppjwa.cn/Article/details/gt2lsevkrhs.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gt2kenoazsk.html

Ruby: arr.reverse
来源：http://dali.gaohongyu789.top/Article/details/gt2ebcfxevg.html

C#:   list.Reverse();
来源：http://dali.andypj.xyz/Article/details/gt2cjwjzycw.html

[D12] 查找元素下标
来源：http://dali.chenjidiqi.icu/Article/details/gt2fqrgrpad.html

Py:   arr.index(x);  x in arr
来源：http://dali.guannengcc.top/Article/details/gt2hqxppryo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ivvv.top/Article/details/gt2vbxppdkp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.bjfxy.top/Article/details/gt2cvxmaffw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gt2iwzbxwaa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aibaodan.cn/Article/details/gt2hsbedmbc.html

Go:   slices.Index(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2emhpcrnv.html

Ruby: arr.index(x)
来源：http://dali.birdmap.top/Article/details/gt2gtchgdlv.html

C#:   list.IndexOf(x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvnznbbu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.9152youxi.cn/Article/details/gt2isqozlvn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpfphood.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.smart0.xyz/Article/details/gt2zsddcyvp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xinyue.icu/Article/details/gt2sobuhzji.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gt2qhtuxuey.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sxryk.cn/Article/details/gt2pkwlyknf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nanxuanxn.top/Article/details/gt2kxdunzjy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ykrqjisr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2vilihsoy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gt2hhtjrizy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yangfankeji.com/Article/details/gt2vrryxrsw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2cfmoylek.html

JS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2tsovrgqm.html

TS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gt2rmnblgth.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bpdyfsoz.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gt2ocnpdjwa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.c1oappe.top/Article/details/gt2hludceda.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2lureefce.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gt2yfdbgsyg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gt2mhthvvfr.html

PHP:  array_unique($arr);
来源：http://dali.daria6918.cn/Article/details/gt2lxztaxua.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gt2luemsekz.html

TS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gt2zoetgnot.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yangfankeji.com/Article/details/gt2efgufpjj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnqzz.top/Article/details/gt2tpuzrevi.html

Ruby: arr.uniq
来源：http://dali.quarkkingdee.top/Article/details/gt2ffnbdjqs.html

C#:   list.Distinct().ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2bkknpmgc.html

[D16] 求和与平均值
来源：http://dali.c1oappe.top/Article/details/gt2ybcvmpiu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fengsongda.top/Article/details/gt2dosuqwqx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2pilidpht.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2yykksgku.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2xokrfjtr.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gt2lrzpipli.html

Go:   // 手写循环累加
来源：http://dali.meibo888.top/Article/details/gt2tgcvhvfy.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.nanxinkj.top/Article/details/gt2xqycidhv.html

C#:   list.Sum();  list.Average()
来源：http://dali.iojbl.cn/Article/details/gt2qqidurxl.html

[D17] 最大值与最小值
来源：http://dali.zhiwuduotai.top/Article/details/gt2hqfaxxff.html

Py:   max(arr);  min(arr)
来源：http://dali.redwolf501.top/Article/details/gt2xrjjcroh.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2crfsbpug.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hnqzz.top/Article/details/gt2mtyjurdv.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2jmvrdtva.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sufxvd.cn/Article/details/gt2lvynrucu.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ybcxt.top/Article/details/gt2ciuawtsf.html

Ruby: arr.max;  arr.min
来源：http://dali.yonumen.top/Article/details/gt2yrfgoaap.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258888.top/Article/details/gt2djbadhag.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fihmhvmm.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hywenlv.cn/Article/details/gt2uufojack.html

PHP:  array_merge(...$nested);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mhxccnvg.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sweek.top/Article/details/gt2qwqyivap.html

TS:   nested.flat();
来源：http://dali.ehwqpu.com/Article/details/gt2iywounnh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuxming.cn/Article/details/gt2grdemipm.html

Go:   // 手写双层循环
来源：http://dali.nanxinkj.top/Article/details/gt2fwnsxoxt.html

Ruby: nested.flatten
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2elrbwnij.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzewrga.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gt2xbofwkyi.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shuidangran.top/Article/details/gt2wugegycr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.cashguo.top/Article/details/gt2rhrywifp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj202588.top/Article/details/gt2txfyqorq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cdnleiting.top/Article/details/gt2tjyhmtbq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnxiangtu.top/Article/details/gt2zjlssbyn.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gt2aqtwoyoz.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gt2antpofzy.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yueranfly.top/Article/details/gt2yinoqprt.html

[D20] 统计每个元素出现次数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qkvplfwj.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gt2mluicocx.html

PHP:  array_count_values($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2gilrqutj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gt2ijefjikj.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.9152youxi.cn/Article/details/gt2brvnailb.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sysykeji.top/Article/details/gt2rjwjlpmp.html

Go:   // 手写 map[T]int
来源：http://dali.ybcxt.top/Article/details/gt2ggqeopbh.html

Ruby: arr.tally
来源：http://dali.kuanghao11.cn/Article/details/gt2bfysjiiw.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.guannengcc.top/Article/details/gt2qtlewkaa.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mscscywk.html

Py:   x in arr
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2esbenlhm.html

PHP:  in_array($x, $arr, true);
来源：http://dali.yongpay.top/Article/details/gt2mjkfppfx.html

JS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2lxfztuuh.html

TS:   arr.includes(x)
来源：http://dali.316326.xyz/Article/details/gt2vdcauaiv.html

Java: list.contains(x)
来源：http://dali.xziqi.cn/Article/details/gt2naaqjzou.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2vtbdhutk.html

Ruby: arr.include?(x)
来源：http://dali.chenlongwang.top/Article/details/gt2bvoivrij.html

C#:   list.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2ksmqlqpn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jinqigfzy.top/Article/details/gt2lgjsrbvk.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2diccpjdw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zdqjudy.top/Article/details/gt2wzqsrnlv.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.ivvv.top/Article/details/gt2zidnrpwo.html

TS:   [...arr];
来源：http://dali.ydzc1.top/Article/details/gt2atxfcoht.html

Java: new ArrayList<>(list);
来源：http://dali.fzhhl.top/Article/details/gt2atdgxzzi.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj20258888.top/Article/details/gt2dqumakvw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ydzc1.top/Article/details/gt2mhsgujxq.html

C#:   new List<int>(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2adorhyyj.html

[D23] reduce 累积计算
来源：http://dali.chenjidiqi.icu/Article/details/gt2bgkvstzc.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvjvhylk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.yueranfly.top/Article/details/gt2izkhmktz.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.guannengcc.top/Article/details/gt2megbzsdn.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2verdqhco.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.sxryk.cn/Article/details/gt2rvgigvog.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gt2swaygefe.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zhoulong.xyz/Article/details/gt2tpsbhvxm.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jyoumei.cn/Article/details/gt2jfhvxsme.html

[D24] 字典 / Map 基本操作
来源：http://dali.guowangkeji.top/Article/details/gt2exzqhglm.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.c1oappe.top/Article/details/gt2xwzxdxhq.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.smart0.xyz/Article/details/gt2gznqqlwv.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jiagoushi.top/Article/details/gt2eanhdito.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.andypj.xyz/Article/details/gt2kgwnyrcm.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.cdnleiting.top/Article/details/gt2eerkuisv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.bjfxy.top/Article/details/gt2vcrhgtsr.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.hnxiangtu.top/Article/details/gt2pwhimkev.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.hfpthk.cn/Article/details/gt2bzgexiir.html

[D25] Set 集合去重与交并差
来源：http://dali.hammf.cn/Article/details/gt2docyximu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.nwbrower.top/Article/details/gt2jxtnwttf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.tian-w.cn/Article/details/gt2wbbsnxkb.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.dianchejie.cn/Article/details/gt2ajxaszbs.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.havefunace.top/Article/details/gt2mwcjiigx.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.chenzaomai.com/Article/details/gt2ezcrbvqb.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.vqdsnc.cn/Article/details/gt2vbudkpff.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tianlin.xyz/Article/details/gt2qpnstlhl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.jqgufenzy.top/Article/details/gt2pgpbnmxw.html

[D26] 数组转字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2egthpznz.html

Py:   ", ".join(map(str, arr))
来源：http://dali.dashuyun.cn/Article/details/gt2uxizokxf.html

PHP:  implode(", ", $arr);
来源：http://dali.sysykeji.top/Article/details/gt2zqcenbgo.html

JS:   arr.join(", ")
来源：http://dali.birdmap.top/Article/details/gt2acdujbxt.html

TS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gt2mravczrr.html

Java: String.join(", ", list)
来源：http://dali.sxryk.cn/Article/details/gt2orauqrgf.html

Go:   strings.Join(strs, ", ")
来源：http://dali.guowangkeji.top/Article/details/gt2rrhfiiqz.html

Ruby: arr.join(", ")
来源：http://dali.wangdashe.top/Article/details/gt2ezidvdsu.html

C#:   string.Join(", ", list)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fzjbvsff.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2twvfcsvr.html

E. 字符串处理
来源：http://dali.tanke756.top/Article/details/gt2gzcoafcq.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2trcqvoum.html

[E01] 拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gt2smyvlnln.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvsaujvq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.vqdsnc.cn/Article/details/gt2vposngeq.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.316326.xyz/Article/details/gt2uhpdstzr.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhixingplan.top/Article/details/gt2zqbtkxqi.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwqpbvzk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.meibo888.top/Article/details/gt2ddrbjnie.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zhengqikj.top/Article/details/gt2vwzfasjl.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2okkpwblh.html

[E02] 重复字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pkqlkfkr.html

Py:   "ab" * 3
来源：http://dali.pengpengdd.cyou/Article/details/gt2qyjysqgw.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hammf.cn/Article/details/gt2kagtnrzu.html

JS:   "ab".repeat(3)
来源：http://dali.chenlongwang.top/Article/details/gt2mxcfkpey.html

TS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gt2avhwbjud.html

Java: "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gt2yruunhwu.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yuanzhike.top/Article/details/gt2dujgqaxb.html

Ruby: "ab" * 3
来源：http://dali.pycfn.com/Article/details/gt2vaqcrjpa.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.pengpengdd.cyou/Article/details/gt2pyctzpdt.html

[E03] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gt2gpzwuagn.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.yonumen.top/Article/details/gt2uwjomccx.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.fengsongda.top/Article/details/gt2grjffkid.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnwbsip.html

TS:   s.slice(1, 4)
来源：http://dali.hywenlv.cn/Article/details/gt2lmvtxyle.html

Java: s.substring(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gt2igwkwtte.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ivvv.top/Article/details/gt2cunzwunu.html


<!-- 参考信息 -->