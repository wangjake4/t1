代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zycfv.cn/Article/details/gtukjbqsbl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtcbafvzyf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yvedp.cn/Article/details/gtzxprbdfs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtbobxntko.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtxuntkclv.html

Go:   func add(a, b int) int
来源：http://dali.smart0.xyz/Article/details/gtqaosezfo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhongyouzk.top/Article/details/gtrebhgwqk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gttitdkysa.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjfkfafp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.smart0.xyz/Article/details/gtexsugvcc.html

PHP:  // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtslkoqnmw.html

JS:   // 无泛型
来源：http://dali.daxiang520.top/Article/details/gtstwxxmpo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gterpkhczj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangdashe.top/Article/details/gtzfrmukdt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cucudq.cn/Article/details/gtntkeiwgs.html

Ruby: # 无泛型
来源：http://dali.yj202588.top/Article/details/gtjjfiyscp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangshuangyany.cn/Article/details/gtauvpjigb.html

[C15] 解构 / 展开参数
来源：http://dali.zdqjudy.top/Article/details/gtolckwoyn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shzxlz.cn/Article/details/gtoambngsx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.redwolf501.top/Article/details/gtevaqwtwp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gtccakbepa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guannengcc.top/Article/details/gtwqtqnuga.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gtiahyfhez.html

Go:   // 无解构
来源：http://dali.meibo888.top/Article/details/gtmdvtpded.html

Ruby: a, b = pair
来源：http://dali.birdmap.top/Article/details/gtvlfbixlu.html

C#:   var (a, b) = pair;
来源：http://dali.hywenlv.cn/Article/details/gtxboyjdvh.html

[C16] 函数 / 方法重载
来源：http://dali.yuanzhike.top/Article/details/gtjmmcrlkw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtvdcoijwf.html

PHP:  // 无重载
来源：http://dali.c1oappe.top/Article/details/gtlsqdnhar.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guannengcc.top/Article/details/gtnuuxryef.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fzhhl.top/Article/details/gtjjwmsjjt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.redwolf501.top/Article/details/gtwjohwynq.html

Go:   // 无重载：用不同函数名
来源：http://dali.ivvv.top/Article/details/gtlzzxsaiw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xylfe.cn/Article/details/gtudrreicv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtcsvjyyvg.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdlrprrxz.html

D. 数组 / 列表 / 集合
来源：http://dali.gzhubu.top/Article/details/gtkptmiqdd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtewkvtlvb.html

[D01] 创建数组 / 列表
来源：http://dali.ivvv.top/Article/details/gtexaandgr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sufxvd.cn/Article/details/gtfeiqhqrr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gogol.net.cn/Article/details/gtplibfibn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.iojbl.cn/Article/details/gtnsvpfzqx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gtzspqatuf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ehwqpu.com/Article/details/gtvgctvljl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.svipenyu.cn/Article/details/gtdyynhtav.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenlongwang.top/Article/details/gtuigpjuft.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gzhubu.top/Article/details/gtiddprczu.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gtsevmthuj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gtcgwtuykz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fzhhl.top/Article/details/gtwkjydyir.html

JS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gtcfaadwhr.html

TS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtficevzia.html

Java: list.add(4);
来源：http://dali.jiagoushi.top/Article/details/gtnbkubdxe.html

Go:   arr = append(arr, 4)
来源：http://dali.bjfxy.top/Article/details/gtxkrnusbr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgufenzy.top/Article/details/gtpjporiqc.html

C#:   list.Add(4);
来源：http://dali.hnqzz.top/Article/details/gteoalpzni.html

[D03] 在指定位置插入元素
来源：http://dali.shuidangran.top/Article/details/gtlzasrovd.html

Py:   arr.insert(0, 0)
来源：http://dali.redwolf501.top/Article/details/gtvlmudoab.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuetiantiany.cn/Article/details/gthmhsvaby.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuxming.cn/Article/details/gtgnxfwjmz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtvzjvvhuf.html

Java: list.add(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtlbspxszt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258.top/Article/details/gtlcrtillz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.andypj.xyz/Article/details/gtlcxzjeep.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gtfzdbyjhk.html

[D04] 删除元素
来源：http://dali.9152youxi.cn/Article/details/gtqleihuhg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yongpay.top/Article/details/gtnfsnhved.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shzxlz.cn/Article/details/gtyclidwgf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhongyouzk.top/Article/details/gtrxddaxsn.html

TS:   arr.splice(0, 1);
来源：http://dali.zhoulong.xyz/Article/details/gthxvwesdi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gtvbkldcup.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aizwys.cn/Article/details/gtlsfeidzm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hfpthk.cn/Article/details/gtbjlzxfuz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gtdevkbelb.html

[D05] 访问与修改元素
来源：http://dali.quarkkingdee.top/Article/details/gtqoflhwmv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtiznexfel.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsiresce.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gthjceumch.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuxming.cn/Article/details/gtyvskarhp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hammf.cn/Article/details/gtsyjwyrwn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtmcjlymld.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtprwevbmu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtomaiqlvs.html

[D06] 数组长度
来源：http://dali.cashguo.top/Article/details/gtpocmgttc.html

Py:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gtsvzhdezx.html

PHP:  count($arr);
来源：http://dali.cashguo.top/Article/details/gtaokfmppc.html

JS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtukwcaiqr.html

TS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gtgzqqwtrt.html

Java: list.size();
来源：http://dali.jqgufenzy.top/Article/details/gtnuvxnskk.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvkudnycc.html

Ruby: arr.length; arr.size
来源：http://dali.yangfankeji.com/Article/details/gtlwqvdoyn.html

C#:   list.Count;
来源：http://dali.daxiang520.top/Article/details/gtkryoqiwk.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gtsnkchrab.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shzxlz.cn/Article/details/gtusdbucln.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtlddnimvz.html

JS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxwmldod.html

TS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gtpbhsnhlp.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtostrttbv.html

Go:   arr[1:4]
来源：http://dali.ywan-chungtsiang.top/Article/details/gttymapjxf.html

Ruby: arr[1, 3]
来源：http://dali.gogol.net.cn/Article/details/gtvrjabgdg.html

C#:   list.GetRange(1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtpqdrdnqd.html

[D08] 合并两个数组
来源：http://dali.guowangkeji.top/Article/details/gtaauxoxfd.html

Py:   a + b;  a.extend(b)
来源：http://dali.shuidangran.top/Article/details/gtvhumbsbc.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gthpiraydr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fengsongda.top/Article/details/gtcgxtvnqp.html

TS:   [...a, ...b];
来源：http://dali.nwbrower.top/Article/details/gtymzmwtqm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gttmhzmqkm.html

Go:   append(a, b...)
来源：http://dali.hammf.cn/Article/details/gtcknlaguz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhengqikj.top/Article/details/gtvueoyvwi.html

C#:   a.Concat(b).ToList()
来源：http://dali.xylfe.cn/Article/details/gtgzcefiqd.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gtkllgahdj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ybcxt.top/Article/details/gtxtkqnvpi.html

PHP:  sort($arr);
来源：http://dali.daxiang520.top/Article/details/gttyoglsew.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlicbabst.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.andypj.xyz/Article/details/gthinzyxxl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gotoacloud.top/Article/details/gtytozagew.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtfklqjuwy.html

Ruby: arr.sort
来源：http://dali.shangyingyoupin.top/Article/details/gtbgsqtxuq.html

C#:   list.Sort();
来源：http://dali.snrcjt.cn/Article/details/gtmmaqbhlp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gtaqdleorb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.svipenyu.cn/Article/details/gthqjojuhd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gtlzjxqaqc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gtftasvqws.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhixingplan.top/Article/details/gtonadzcwb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zycfv.cn/Article/details/gtbcxpmtjb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnqzz.top/Article/details/gtfhfqnvjq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gttjbegkhm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guowangkeji.top/Article/details/gtfimyllhv.html

[D11] 反转数组
来源：http://dali.chenzaomai.com/Article/details/gtvytuzdqh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yanxiufei.cn/Article/details/gtvidvqzuf.html

PHP:  array_reverse($arr);
来源：http://dali.chenzaomai.com/Article/details/gtglugjlor.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.mhx1999.top/Article/details/gtpymjiize.html

TS:   [...arr].reverse();
来源：http://dali.jlsjyb.cn/Article/details/gthuimvbxc.html

Java: Collections.reverse(list);
来源：http://dali.daxiang520.top/Article/details/gtngrurkbj.html

Go:   slices.Reverse(arr)
来源：http://dali.316326.xyz/Article/details/gtoqqmoaae.html

Ruby: arr.reverse
来源：http://dali.xylfe.cn/Article/details/gtqskhjmfh.html

C#:   list.Reverse();
来源：http://dali.fengsongda.top/Article/details/gtndmlmadg.html

[D12] 查找元素下标
来源：http://dali.xinyue.icu/Article/details/gtfatlifcy.html

Py:   arr.index(x);  x in arr
来源：http://dali.hfpthk.cn/Article/details/gtjklieayd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zdqjudy.top/Article/details/gtlylzmpff.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gtpgwuudyj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gtxvrihkmw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuanzhike.top/Article/details/gtvrcnfmro.html

Go:   slices.Index(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgxufcwms.html

Ruby: arr.index(x)
来源：http://dali.cashguo.top/Article/details/gttlvqykrd.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigfzy.top/Article/details/gtzczhzlhn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuetiantiany.cn/Article/details/gtwuncflyf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hywenlv.cn/Article/details/gtxgcmnolp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guowangkeji.top/Article/details/gtfwabtuxz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gttayijplu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gtkgamwhvf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtnepaykqj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gtotyqblbk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gogol.net.cn/Article/details/gtjyffyxyw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gzhubu.top/Article/details/gtvboflgxb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guowangkeji.top/Article/details/gtwwiyhjmi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xziqi.cn/Article/details/gtghppwebv.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tianlin.xyz/Article/details/gthnboicbd.html

JS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtrhubfseq.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gtmhbzdhsf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtlkmuzrrx.html

Go:   // 手写循环
来源：http://dali.iojbl.cn/Article/details/gteuzpmrcg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtnkjgbksi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gaohongyu789.top/Article/details/gtknqlihge.html

[D15] 去重
来源：http://dali.xuanzx.com/Article/details/gtpnvsgtwg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gttgqutuyl.html

PHP:  array_unique($arr);
来源：http://dali.guowangkeji.top/Article/details/gtgomweoyd.html

JS:   [...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gtzjescnax.html

TS:   [...new Set(arr)]
来源：http://dali.pycfn.com/Article/details/gthvlzksqj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangshuangyany.cn/Article/details/gtolnfbeec.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ybcxt.top/Article/details/gtafphwowv.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gtojbljupc.html

C#:   list.Distinct().ToList()
来源：http://dali.shuidangran.top/Article/details/gtoffwcthl.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gtexkskhqn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtcebyurtj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtdwnfanay.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtobbczmed.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtnhpnsacx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xylfe.cn/Article/details/gtqdqotjvl.html

Go:   // 手写循环累加
来源：http://dali.jianghu66.top/Article/details/gtdrfpclgj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.vqdsnc.cn/Article/details/gtlzvebfnp.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gtcjpldbew.html

[D17] 最大值与最小值
来源：http://dali.guowangkeji.top/Article/details/gtmkitotui.html

Py:   max(arr);  min(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtypqznjer.html

PHP:  max($arr);  min($arr);
来源：http://dali.xylfe.cn/Article/details/gttyavtmct.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.gogol.net.cn/Article/details/gtvyyjligw.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gtkccdqqbe.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.smart0.xyz/Article/details/gtcdnmxwwt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zdqjudy.top/Article/details/gtjlhdactm.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gtysfwysom.html

C#:   list.Max();  list.Min()
来源：http://dali.bjfxy.top/Article/details/gtvbnbmtpw.html

[D18] 扁平化嵌套数组
来源：http://dali.yangfankeji.com/Article/details/gtynxkhsmu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gtiagdybzx.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigufen.top/Article/details/gtxocoizug.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.mhx1999.top/Article/details/gtjurxgkdu.html

TS:   nested.flat();
来源：http://dali.tian-w.cn/Article/details/gtmxdsntay.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gtvxpkhmad.html

Go:   // 手写双层循环
来源：http://dali.zhijiandao.cn/Article/details/gtlruzqcwa.html

Ruby: nested.flatten
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfokmauwe.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dianchejie.cn/Article/details/gtoccplgbd.html

[D19] 按字段分组
来源：http://dali.tian-w.cn/Article/details/gtebcgguxe.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hammf.cn/Article/details/gttnfnvdmc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zdqjudy.top/Article/details/gtzkgpgmfx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.aibaodan.cn/Article/details/gtjtnwpbao.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gaohongyu789.top/Article/details/gtxvbqopdj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gtzndqivhd.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gtbwwcevmt.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nwbrower.top/Article/details/gttgimwrvk.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.nanxuanxn.top/Article/details/gtxijtxjdp.html

[D20] 统计每个元素出现次数
来源：http://dali.zhengqikj.top/Article/details/gtgohaiciw.html

Py:   Counter(arr)
来源：http://dali.316326.xyz/Article/details/gtxfbrxqzg.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gtcvmyiczz.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gtcdrkhrzz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jianghu66.top/Article/details/gtnokefedr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.haohaochexian.top/Article/details/gtwblzijrp.html

Go:   // 手写 map[T]int
来源：http://dali.yongpay.top/Article/details/gtpzilfuvu.html

Ruby: arr.tally
来源：http://dali.aizwys.cn/Article/details/gtalxfnscn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sxryk.cn/Article/details/gtfxpmlhbl.html

[D21] 判断是否包含某元素
来源：http://dali.zhoulong.xyz/Article/details/gtrjltenue.html

Py:   x in arr
来源：http://dali.0kj1m.cn/Article/details/gtblwmwnrb.html

PHP:  in_array($x, $arr, true);
来源：http://dali.c1oappe.top/Article/details/gtxnikkgzs.html

JS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gtsbzaovyr.html

TS:   arr.includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrnhjhty.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtyqfpnrkk.html

Go:   slices.Contains(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtssilmjdo.html

Ruby: arr.include?(x)
来源：http://dali.yj202588.top/Article/details/gtdrrdhzbj.html

C#:   list.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtiswucrnk.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuxming.cn/Article/details/gtfakcopmz.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.cashguo.top/Article/details/gtejpfosur.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sweek.top/Article/details/gtyceweoqe.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zhixingplan.top/Article/details/gtbnfmlmzp.html

TS:   [...arr];
来源：http://dali.ybcxt.top/Article/details/gtvzaednpq.html

Java: new ArrayList<>(list);
来源：http://dali.gzhubu.top/Article/details/gtlpvfjouy.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.haohaochexian.top/Article/details/gtznwyhedf.html

Ruby: arr.dup;  arr.clone
来源：http://dali.tian-w.cn/Article/details/gtmylytrym.html

C#:   new List<int>(list);
来源：http://dali.yangfankeji.com/Article/details/gtqxpeprjf.html

[D23] reduce 累积计算
来源：http://dali.cdnleiting.top/Article/details/gtmnlntzkl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.cqqwz.cn/Article/details/gtnwoudrgx.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.tianlin.xyz/Article/details/gturposrbo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gtxkoxlwyb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.cdnleiting.top/Article/details/gtffxmqjah.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.yanxiufei.cn/Article/details/gtqzupuxds.html

Go:   // 手写循环
来源：http://dali.daria6918.cn/Article/details/gtipwpelfr.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.kuanghao11.cn/Article/details/gtumvxnvvl.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.iojbl.cn/Article/details/gtdcsuqteh.html

[D24] 字典 / Map 基本操作
来源：http://dali.sweek.top/Article/details/gtqsqkjfxo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cucudq.cn/Article/details/gtpbpyabco.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.redwolf501.top/Article/details/gtwlpgxnvm.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jyoumei.cn/Article/details/gtxlmrqoqo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtdmyriiwr.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtdarznikw.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jinghuilouyu.cn/Article/details/gtscrapocj.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhengqikj.top/Article/details/gtehoeprye.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nwbrower.top/Article/details/gtalplincv.html

[D25] Set 集合去重与交并差
来源：http://dali.hysaishi.cn/Article/details/gtyquiftbu.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.hammf.cn/Article/details/gtmqdjfplp.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gzhubu.top/Article/details/gtdpmjxcih.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.chenjidiqi.icu/Article/details/gtalvsefro.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtespjshjz.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.yuxming.cn/Article/details/gtxlbkajhd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.daria6918.cn/Article/details/gteqkmjiye.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.c1oappe.top/Article/details/gtzhmloyjl.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.pycfn.com/Article/details/gtrmiwgqwk.html

[D26] 数组转字符串
来源：http://dali.cucudq.cn/Article/details/gtcjzmxwex.html

Py:   ", ".join(map(str, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtmjxlzlvj.html

PHP:  implode(", ", $arr);
来源：http://dali.fzhhl.top/Article/details/gtcjnstnwc.html

JS:   arr.join(", ")
来源：http://dali.dashuyun.cn/Article/details/gteqbmxemc.html

TS:   arr.join(", ")
来源：http://dali.bjfxy.top/Article/details/gtwqocslef.html

Java: String.join(", ", list)
来源：http://dali.ivvv.top/Article/details/gtruntmrns.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hysaishi.cn/Article/details/gtzilsdkxt.html

Ruby: arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gtukkhveje.html

C#:   string.Join(", ", list)
来源：http://dali.tanke756.top/Article/details/gtsxgvkorj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gteshewsyv.html

E. 字符串处理
来源：http://dali.zycfv.cn/Article/details/gtabnjeumz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtsfqaosql.html

[E01] 拼接字符串
来源：http://dali.sweek.top/Article/details/gtzewvxxbc.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xziqi.cn/Article/details/gtyixwmoxl.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.hammf.cn/Article/details/gttblldexg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ydzc1.top/Article/details/gtsbmbqpnj.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.chenlongwang.top/Article/details/gtsxffzbjm.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.yonumen.top/Article/details/gtllaiwtgk.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yanxiufei.cn/Article/details/gtmfilkefn.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.cucudq.cn/Article/details/gtyarjpuyo.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.tanke756.top/Article/details/gtfdbfpipi.html

[E02] 重复字符串
来源：http://dali.0kj1m.cn/Article/details/gtylpmnkuk.html

Py:   "ab" * 3
来源：http://dali.ppjwa.cn/Article/details/gtxjzcmtmb.html

PHP:  str_repeat("ab", 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtepbdpf.html

JS:   "ab".repeat(3)
来源：http://dali.svipenyu.cn/Article/details/gteffyjwjt.html

TS:   "ab".repeat(3)
来源：http://dali.316326.xyz/Article/details/gtiausyltm.html

Java: "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gtrexnstit.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.ydzc1.top/Article/details/gtvcbozfeo.html

Ruby: "ab" * 3
来源：http://dali.tanke756.top/Article/details/gtxebkfgkk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.fzhhl.top/Article/details/gtbpqtylif.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtemsgibod.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shuidangran.top/Article/details/gtltptlkyb.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.gaohongyu789.top/Article/details/gtrobpcpss.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gtmapsghza.html

TS:   s.slice(1, 4)
来源：http://dali.fengsongda.top/Article/details/gtznhojbjz.html

Java: s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gtrxgwjwow.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.0kj1m.cn/Article/details/gtppjtmmma.html


<!-- 参考信息 -->