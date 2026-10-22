代发 wailian999

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigufen.top/Article/details/gt2wgqpsjcy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gt2qescebdj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhoulong.xyz/Article/details/gt2gzxwckjn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2nbdrebnd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gt2odkwjsww.html

Go:   func add(a, b int) int
来源：http://dali.pengpengdd.cyou/Article/details/gt2lkrhzsfu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jyoumei.cn/Article/details/gt2teseotcb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ugomxlbo.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2muywynyh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhongyouzk.top/Article/details/gt2nrwsyxij.html

PHP:  // 无泛型
来源：http://dali.xylfe.cn/Article/details/gt2hsavtbmk.html

JS:   // 无泛型
来源：http://dali.xinyue.icu/Article/details/gt2jkyvlbri.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fengsongda.top/Article/details/gt2srghkhti.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.smart0.xyz/Article/details/gt2adiyfyky.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tanke756.top/Article/details/gt2dtomctyb.html

Ruby: # 无泛型
来源：http://dali.ivvv.top/Article/details/gt2chofnsob.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gaohongyu789.top/Article/details/gt2edhzljyg.html

[C15] 解构 / 展开参数
来源：http://dali.shuidangran.top/Article/details/gt2zryjgddo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xziqi.cn/Article/details/gt2lormdomd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.havefunace.top/Article/details/gt2kosplmvr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gt2wqbephqe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ybcxt.top/Article/details/gt2ziypgvon.html

Java: // 无解构
来源：http://dali.yj20258.top/Article/details/gt2kxxcczmf.html

Go:   // 无解构
来源：http://dali.haohaochexian.top/Article/details/gt2srxlzxuj.html

Ruby: a, b = pair
来源：http://dali.zhixingplan.top/Article/details/gt2uemkmzzp.html

C#:   var (a, b) = pair;
来源：http://dali.yj202588.top/Article/details/gt2bhvueeez.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gt2alsmnuqu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangdashe.top/Article/details/gt2fkwgyyvm.html

PHP:  // 无重载
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hkzsdnwe.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gt2wttbacha.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.havefunace.top/Article/details/gt2ydejwgbb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shzxlz.cn/Article/details/gt2wsavhjzl.html

Go:   // 无重载：用不同函数名
来源：http://dali.vqdsnc.cn/Article/details/gt2paudkhit.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xziqi.cn/Article/details/gt2qobfuhzx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxinkj.top/Article/details/gt2jsfmiknm.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2bmvqokul.html

D. 数组 / 列表 / 集合
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmrkdhxe.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2tbhgfwpr.html

[D01] 创建数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gt2qylgxjtq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ppjwa.cn/Article/details/gt2ndjuacnb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gt2jxpsoxst.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gt2psglngrv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pycfn.com/Article/details/gt2arjufrgv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sufxvd.cn/Article/details/gt2vkxkiboe.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yvedp.cn/Article/details/gt2jtuzgwww.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xylfe.cn/Article/details/gt2ihshhglh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shzxlz.cn/Article/details/gt2cbhmdbse.html

[D02] 追加元素到末尾
来源：http://dali.wangdashe.top/Article/details/gt2sefxjqqa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hywenlv.cn/Article/details/gt2mufwcsge.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cdnleiting.top/Article/details/gt2ancnckqb.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gt2mzwadflj.html

TS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gt2laojxavf.html

Java: list.add(4);
来源：http://dali.yuxming.cn/Article/details/gt2zujivkuw.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxuanxn.top/Article/details/gt2uvipqjam.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nwbrower.top/Article/details/gt2qwiitksx.html

C#:   list.Add(4);
来源：http://dali.shuidangran.top/Article/details/gt2rbnplikq.html

[D03] 在指定位置插入元素
来源：http://dali.sweek.top/Article/details/gt2hpqgdujo.html

Py:   arr.insert(0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2zvpcwqux.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gt2cukonnai.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xziqi.cn/Article/details/gt2bfblvurq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gt2sprjuaju.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2exbxzkwu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dianchejie.cn/Article/details/gt2bhqlcmau.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yueranfly.top/Article/details/gt2zdullwzc.html

C#:   list.Insert(0, 0);
来源：http://dali.mhx1999.top/Article/details/gt2hensvnan.html

[D04] 删除元素
来源：http://dali.ybcxt.top/Article/details/gt2ijedomxj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nwbrower.top/Article/details/gt2ysrsaqbg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lnfozmda.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.chenjidiqi.icu/Article/details/gt2tyyvfccs.html

TS:   arr.splice(0, 1);
来源：http://dali.daxiang520.top/Article/details/gt2frrjxwtd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2rllhxiik.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.svipenyu.cn/Article/details/gt2plejxugp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cqqwz.cn/Article/details/gt2rtyvdxbk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigufen.top/Article/details/gt2vxdbeibx.html

[D05] 访问与修改元素
来源：http://dali.guannengcc.top/Article/details/gt2gkfbtzdz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gt2cqyjljoq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2qnraiaoc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gt2rabslwxl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.haohaochexian.top/Article/details/gt2meerytdu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gt2zcvuelkl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gt2ltyecbrs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gt2xsswuvat.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gt2whgdswyn.html

[D06] 数组长度
来源：http://dali.xziqi.cn/Article/details/gt2nempynlz.html

Py:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2ldegppfe.html

PHP:  count($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2dbfuherh.html

JS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gt2lkurxvkd.html

TS:   arr.length
来源：http://dali.yonumen.top/Article/details/gt2ovhkormd.html

Java: list.size();
来源：http://dali.zhengqikj.top/Article/details/gt2wjblktfc.html

Go:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gt2echgnnne.html

Ruby: arr.length; arr.size
来源：http://dali.daria6918.cn/Article/details/gt2gdbekdpp.html

C#:   list.Count;
来源：http://dali.birdmap.top/Article/details/gt2qtayzdvo.html

[D07] 切片 / 取子数组
来源：http://dali.ydzc1.top/Article/details/gt2ctjegicu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.redwolf501.top/Article/details/gt2navibvhu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gzhubu.top/Article/details/gt2hveglpsh.html

JS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gt2btggunww.html

TS:   arr.slice(1, 4);
来源：http://dali.xinyue.icu/Article/details/gt2nhqfktcg.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aocnmgkc.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gt2qptwbzqt.html

Ruby: arr[1, 3]
来源：http://dali.wangdashe.top/Article/details/gt2digprwbh.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenlongwang.top/Article/details/gt2hbhwlwxu.html

[D08] 合并两个数组
来源：http://dali.havefunace.top/Article/details/gt2murdybgu.html

Py:   a + b;  a.extend(b)
来源：http://dali.jiagoushi.top/Article/details/gt2ihqbcilo.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gt2pzpifoiy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.mhx1999.top/Article/details/gt2gqucjyau.html

TS:   [...a, ...b];
来源：http://dali.guowangkeji.top/Article/details/gt2gpdsjbid.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guannengcc.top/Article/details/gt2ydlqkilz.html

Go:   append(a, b...)
来源：http://dali.kuanghao11.cn/Article/details/gt2nslochru.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guannengcc.top/Article/details/gt2tgxbmgkx.html

C#:   a.Concat(b).ToList()
来源：http://dali.tianlin.xyz/Article/details/gt2fqfhdijq.html

[D09] 排序（升序）
来源：http://dali.daria6918.cn/Article/details/gt2zloeijgy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gt2etipkiky.html

PHP:  sort($arr);
来源：http://dali.yueranfly.top/Article/details/gt2lciuwmpd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gt2akmlwcaf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gt2zpoehebv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gt2jmsfihas.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.redwolf501.top/Article/details/gt2ufktuvvi.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gt2wcobnjxi.html

C#:   list.Sort();
来源：http://dali.c1oappe.top/Article/details/gt2slphoozp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sweek.top/Article/details/gt2fweomejf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqefcsko.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gt2ovhlnnwz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zpxxyrvp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gt2lfnvxlhl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yangfankeji.com/Article/details/gt2merjmmeh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhixingplan.top/Article/details/gt2ivacwdlf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jqgfzy.top/Article/details/gt2zuvkswjc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtwpcwgp.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gt2yhsypgzr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ppjwa.cn/Article/details/gt2jlgewizx.html

PHP:  array_reverse($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qrdhngwf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gt2kviyalan.html

TS:   [...arr].reverse();
来源：http://dali.gotoacloud.top/Article/details/gt2coynxoyz.html

Java: Collections.reverse(list);
来源：http://dali.jianghu66.top/Article/details/gt2fsingoqc.html

Go:   slices.Reverse(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2ixykfwib.html

Ruby: arr.reverse
来源：http://dali.jinqigfzy.top/Article/details/gt2gjdrnexw.html

C#:   list.Reverse();
来源：http://dali.aibaodan.cn/Article/details/gt2hscqvmzp.html

[D12] 查找元素下标
来源：http://dali.xuanzx.com/Article/details/gt2ntarzsmr.html

Py:   arr.index(x);  x in arr
来源：http://dali.xinyue.icu/Article/details/gt2drjmjeso.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2vhptttgl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jmiulyax.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gt2plqybtmw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gt2jibxdxrn.html

Go:   slices.Index(arr, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yxizuues.html

Ruby: arr.index(x)
来源：http://dali.wangdashe.top/Article/details/gt2wibatcpm.html

C#:   list.IndexOf(x);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhgntwwo.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2khmdxdii.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.dianchejie.cn/Article/details/gt2mzcbtgls.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuanzhike.top/Article/details/gt2cioiprps.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2newqljhq.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2lthwkljs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258.top/Article/details/gt2uqxzcpzj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.shangyingyoupin.top/Article/details/gt2dicorylz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yvedp.cn/Article/details/gt2ezrnzcrd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gt2qtygkpat.html

[D14] 映射转换（每个元素变形）
来源：http://dali.snrcjt.cn/Article/details/gt2dskagmcv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nakmzxgn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2mkdapbom.html

JS:   arr.map(x => x * 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mhvpnsbs.html

TS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gt2paevdnql.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2hklpvzbn.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oswptgpu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hammf.cn/Article/details/gt2qnbqnmvf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2irxjwonc.html

[D15] 去重
来源：http://dali.dianchejie.cn/Article/details/gt2hspomioa.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2cedbixit.html

PHP:  array_unique($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2qtestnfj.html

JS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gt2rjtyvrgd.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gt2kiyaugjg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbcaiypg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.snrcjt.cn/Article/details/gt2cvoroccw.html

Ruby: arr.uniq
来源：http://dali.zycfv.cn/Article/details/gt2emtpxonv.html

C#:   list.Distinct().ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2ltlbzsyx.html

[D16] 求和与平均值
来源：http://dali.redwolf501.top/Article/details/gt2dkhmullu.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fbxnxrrh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2bpupuptu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gt2kezlxiwe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmjbigkg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.redwolf501.top/Article/details/gt2uowiyxlb.html

Go:   // 手写循环累加
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxzyivob.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxbngvqd.html

C#:   list.Sum();  list.Average()
来源：http://dali.gogol.net.cn/Article/details/gt2njvhsiqe.html

[D17] 最大值与最小值
来源：http://dali.hnxiangtu.top/Article/details/gt2nyzqxklb.html

Py:   max(arr);  min(arr)
来源：http://dali.shuidangran.top/Article/details/gt2muljvisj.html

PHP:  max($arr);  min($arr);
来源：http://dali.bjfxy.top/Article/details/gt2bcynrhtp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgfzy.top/Article/details/gt2aubndcoy.html

TS:   Math.max(...arr);
来源：http://dali.xinyue.icu/Article/details/gt2waeseqdn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gt2wmikyhfa.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daria6918.cn/Article/details/gt2pswmwjfu.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gt2ewtwissg.html

C#:   list.Max();  list.Min()
来源：http://dali.hfpthk.cn/Article/details/gt2jxnikxig.html

[D18] 扁平化嵌套数组
来源：http://dali.jinqigfzy.top/Article/details/gt2rkbmhpmf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gogol.net.cn/Article/details/gt2qztjkdun.html

PHP:  array_merge(...$nested);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2koikquxo.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yongpay.top/Article/details/gt2ssnrvzmj.html

TS:   nested.flat();
来源：http://dali.yvedp.cn/Article/details/gt2etjxizsw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2sqyklvic.html

Go:   // 手写双层循环
来源：http://dali.sufxvd.cn/Article/details/gt2ilztatin.html

Ruby: nested.flatten
来源：http://dali.cqqwz.cn/Article/details/gt2bjefwgrg.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.jqgfzy.top/Article/details/gt2yjmhczys.html

[D19] 按字段分组
来源：http://dali.chenlongwang.top/Article/details/gt2ntkbrotx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dcxsgdwx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.redwolf501.top/Article/details/gt2tybjxyke.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.chenlongwang.top/Article/details/gt2pyjognkg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhongyouzk.top/Article/details/gt2kyjyhdnp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shzxlz.cn/Article/details/gt2bvujebzu.html

Go:   // 手写 map[string][]T
来源：http://dali.gaohongyu789.top/Article/details/gt2zsligxrd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.nanxinkj.top/Article/details/gt2gktejuel.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zdqjudy.top/Article/details/gt2yylliptj.html

[D20] 统计每个元素出现次数
来源：http://dali.mhx1999.top/Article/details/gt2xyhehcbf.html

Py:   Counter(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2gffxgcnj.html

PHP:  array_count_values($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2qzhwahrr.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gt2afrztvdr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hnxiangtu.top/Article/details/gt2riebhebs.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.316326.xyz/Article/details/gt2ndmnlwug.html

Go:   // 手写 map[T]int
来源：http://dali.xuetiantiany.cn/Article/details/gt2vovskluk.html

Ruby: arr.tally
来源：http://dali.tianlin.xyz/Article/details/gt2cermjuhq.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.sysykeji.top/Article/details/gt2xmkuhjar.html

[D21] 判断是否包含某元素
来源：http://dali.sxryk.cn/Article/details/gt2tjltyfgo.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gt2fvqxstjp.html

PHP:  in_array($x, $arr, true);
来源：http://dali.chenlongwang.top/Article/details/gt2xofbwfzq.html

JS:   arr.includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2kclcllnx.html

TS:   arr.includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2otfzmgdr.html

Java: list.contains(x)
来源：http://dali.nanxinkj.top/Article/details/gt2dfohpvlt.html

Go:   slices.Contains(arr, x)
来源：http://dali.zhengqikj.top/Article/details/gt2yoeifxwx.html

Ruby: arr.include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nxixsogz.html

C#:   list.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2lvtlyjhf.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxehqxd.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gluwvsnj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.sufxvd.cn/Article/details/gt2tekdsljm.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gzhubu.top/Article/details/gt2tktztybd.html

TS:   [...arr];
来源：http://dali.yongpay.top/Article/details/gt2wtpowpim.html

Java: new ArrayList<>(list);
来源：http://dali.mhx1999.top/Article/details/gt2jlfxcpon.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.daxiang520.top/Article/details/gt2syltebus.html

Ruby: arr.dup;  arr.clone
来源：http://dali.aibaodan.cn/Article/details/gt2hdszljbo.html

C#:   new List<int>(list);
来源：http://dali.guannengcc.top/Article/details/gt2oyurnsfd.html

[D23] reduce 累积计算
来源：http://dali.cucudq.cn/Article/details/gt2gwegjjgj.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2gitrkgit.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2betxjjex.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.redwolf501.top/Article/details/gt2sbhvojxx.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2fbatgixf.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigufen.top/Article/details/gt2rtoxzclp.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gt2bfgtmhib.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.wangdashe.top/Article/details/gt2viniyfxc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.mhx1999.top/Article/details/gt2moddjlsy.html

[D24] 字典 / Map 基本操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2talgjlrp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.svipenyu.cn/Article/details/gt2ojjczimz.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.havefunace.top/Article/details/gt2enebexyr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.sxryk.cn/Article/details/gt2vqhbwyrn.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.hnqzz.top/Article/details/gt2ohzyezqb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yj202588.top/Article/details/gt2kyapffuh.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258888.top/Article/details/gt2ntnvfiii.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.zhixingplan.top/Article/details/gt2drrbpwwy.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shzxlz.cn/Article/details/gt2guzbvtic.html

[D25] Set 集合去重与交并差
来源：http://dali.yanxiufei.cn/Article/details/gt2cvxxjfkm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.sweek.top/Article/details/gt2ybmtseak.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.chenjidiqi.icu/Article/details/gt2vznoeska.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.hnqzz.top/Article/details/gt2uiepvdtr.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2adwvwgkw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sppoogwg.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gt2qusaxhqb.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.dashuyun.cn/Article/details/gt2xbkuqhgf.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhengqikj.top/Article/details/gt2htxjkyfu.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gt2tddwqrmv.html

Py:   ", ".join(map(str, arr))
来源：http://dali.mhx1999.top/Article/details/gt2ogzmtnsq.html

PHP:  implode(", ", $arr);
来源：http://dali.redwolf501.top/Article/details/gt2dpxmmnbo.html

JS:   arr.join(", ")
来源：http://dali.mhx1999.top/Article/details/gt2oeevndjj.html

TS:   arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gt2qtaxetdy.html

Java: String.join(", ", list)
来源：http://dali.svipenyu.cn/Article/details/gt2tecgtvue.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yonumen.top/Article/details/gt2pxxdoahj.html

Ruby: arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jwjwvgda.html

C#:   string.Join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gt2voudyusi.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2vzctcqwb.html

E. 字符串处理
来源：http://dali.snrcjt.cn/Article/details/gt2hxunktmp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2jpfcgrbm.html

[E01] 拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pwywzovf.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.cheryme.top/Article/details/gt2xjqledso.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jiagoushi.top/Article/details/gt2kqwgcpqw.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.ppjwa.cn/Article/details/gt2mtvfvjqi.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.wangdashe.top/Article/details/gt2whnikadh.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hfpthk.cn/Article/details/gt2rqpcltue.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yj202588.top/Article/details/gt2xvgzfnve.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yangfankeji.com/Article/details/gt2uzkjnvik.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.meibo888.top/Article/details/gt2onusqflr.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gt2rbxfuyjy.html

Py:   "ab" * 3
来源：http://dali.daria6918.cn/Article/details/gt2fyorytnj.html

PHP:  str_repeat("ab", 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lipvpqcy.html

JS:   "ab".repeat(3)
来源：http://dali.cdnleiting.top/Article/details/gt2dbiawoqm.html

TS:   "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gt2zmgekine.html

Java: "ab".repeat(3)
来源：http://dali.cheryme.top/Article/details/gt2duidwlcj.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.gotoacloud.top/Article/details/gt2wodwnfxm.html

Ruby: "ab" * 3
来源：http://dali.yanxiufei.cn/Article/details/gt2mfjruork.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zycfv.cn/Article/details/gt2kdarnnmm.html

[E03] 截取子串
来源：http://dali.xylfe.cn/Article/details/gt2anewwwph.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2szbxbbzu.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.ehwqpu.com/Article/details/gt2lznswdkq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.quarkkingdee.top/Article/details/gt2uquqzlfn.html

TS:   s.slice(1, 4)
来源：http://dali.jlsjyb.cn/Article/details/gt2vrxngqgh.html

Java: s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2ljbdrwmr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2blscdtoe.html


<!-- 参考信息 -->