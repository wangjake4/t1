代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2imtwezkf.html

Go:   func add(a, b int) int
来源：http://dali.pycfn.com/Article/details/gt2hddsydxt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gt2yeeccigf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhongyouzk.top/Article/details/gt2cachndly.html

[C14] 泛型函数
来源：http://dali.gaohongyu789.top/Article/details/gt2fmfagutv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxuanxn.top/Article/details/gt2qzrnxjey.html

PHP:  // 无泛型
来源：http://dali.pycfn.com/Article/details/gt2oqaxdlqm.html

JS:   // 无泛型
来源：http://dali.daxiang520.top/Article/details/gt2lgyxbbwa.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tianlin.xyz/Article/details/gt2dzslbvol.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.birdmap.top/Article/details/gt2emjfeklv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yangfankeji.com/Article/details/gt2axgvqath.html

Ruby: # 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2lrrpxdoe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuetiantiany.cn/Article/details/gt2xxebnsnk.html

[C15] 解构 / 展开参数
来源：http://dali.tianlin.xyz/Article/details/gt2guiedpza.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ezgyantj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qiexzxzh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gt2rbmbyiqo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258888.top/Article/details/gt2lndwyusj.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zriethpy.html

Go:   // 无解构
来源：http://dali.redwolf501.top/Article/details/gt2canckeyc.html

Ruby: a, b = pair
来源：http://dali.daria6918.cn/Article/details/gt2huzwiene.html

C#:   var (a, b) = pair;
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwakubhm.html

[C16] 函数 / 方法重载
来源：http://dali.yuxming.cn/Article/details/gt2jdrpexpa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pycfn.com/Article/details/gt2eysieczb.html

PHP:  // 无重载
来源：http://dali.ivvv.top/Article/details/gt2fkjtlkir.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gt2huwkelaw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuxming.cn/Article/details/gt2nikvqlqn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hywenlv.cn/Article/details/gt2bxpdalve.html

Go:   // 无重载：用不同函数名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dbuzhsgh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.mhx1999.top/Article/details/gt2pupkakkb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2lqkygnhb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2narmmupp.html

D. 数组 / 列表 / 集合
来源：http://dali.yuxming.cn/Article/details/gt2cqlyxvtl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2dkllubnn.html

[D01] 创建数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gt2ucridwwz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yueranfly.top/Article/details/gt2eezqpbsm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hysaishi.cn/Article/details/gt2tkxjumdb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hnqzz.top/Article/details/gt2oizvgagf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gt2tebdnuxc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gt2zkyiwtgk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.dashuyun.cn/Article/details/gt2twuielnm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gt2vckbjvib.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ydzc1.top/Article/details/gt2absrrdal.html

[D02] 追加元素到末尾
来源：http://dali.tianlin.xyz/Article/details/gt2mlcepwli.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xziqi.cn/Article/details/gt2mwqdxjbp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cdnleiting.top/Article/details/gt2dkgspzaw.html

JS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gt2wdcfsrgm.html

TS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2zhrvpcbw.html

Java: list.add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rflcikwq.html

Go:   arr = append(arr, 4)
来源：http://dali.tianlin.xyz/Article/details/gt2hpdmihsk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgfzy.top/Article/details/gt2dwhkftny.html

C#:   list.Add(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2thqoqdaz.html

[D03] 在指定位置插入元素
来源：http://dali.yangfankeji.com/Article/details/gt2mvlcufrw.html

Py:   arr.insert(0, 0)
来源：http://dali.ydzc1.top/Article/details/gt2dfvibgln.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxinkj.top/Article/details/gt2grnbzxpw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.snrcjt.cn/Article/details/gt2zqmghbvj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2isixzqtt.html

Java: list.add(0, 0);
来源：http://dali.ybcxt.top/Article/details/gt2xjpeykcl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuanzhike.top/Article/details/gt2iaztrufe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yanxiufei.cn/Article/details/gt2vffdcfby.html

C#:   list.Insert(0, 0);
来源：http://dali.zycfv.cn/Article/details/gt2mfbdrgce.html

[D04] 删除元素
来源：http://dali.daria6918.cn/Article/details/gt2wphkuhbw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ivvv.top/Article/details/gt2vnfqwgke.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2yurjbyav.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cqqwz.cn/Article/details/gt2pmhvifsz.html

TS:   arr.splice(0, 1);
来源：http://dali.sxryk.cn/Article/details/gt2fgyihkcd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258.top/Article/details/gt2qqwfdqfy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zdqjudy.top/Article/details/gt2bgsalnyw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.iojbl.cn/Article/details/gt2nnjghfit.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bhrqccpd.html

[D05] 访问与修改元素
来源：http://dali.zhixingplan.top/Article/details/gt2jgtgxmqs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gt2fgjlsavv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gt2myhfeatu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gt2dumijrsk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhixingplan.top/Article/details/gt2iookkqxf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gzhubu.top/Article/details/gt2svuexbkx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gt2mjuplkjl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gt2drqcuhbl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258.top/Article/details/gt2dfdesvqy.html

[D06] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gt2yfdnncfh.html

Py:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xvpgqcbb.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2hnbtsjcw.html

JS:   arr.length
来源：http://dali.meibo888.top/Article/details/gt2kprmhbla.html

TS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tiubsgoj.html

Java: list.size();
来源：http://dali.chenlongwang.top/Article/details/gt2idwdotri.html

Go:   len(arr)
来源：http://dali.yongpay.top/Article/details/gt2hytfpyyj.html

Ruby: arr.length; arr.size
来源：http://dali.cdnleiting.top/Article/details/gt2soviikjl.html

C#:   list.Count;
来源：http://dali.hnqzz.top/Article/details/gt2bwanlqkh.html

[D07] 切片 / 取子数组
来源：http://dali.gzhubu.top/Article/details/gt2miikspct.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xziqi.cn/Article/details/gt2hpjfyvgb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jyoumei.cn/Article/details/gt2tcjteumx.html

JS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kxeduifs.html

TS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gt2lcocpbro.html

Java: list.subList(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxcexqsp.html

Go:   arr[1:4]
来源：http://dali.hysaishi.cn/Article/details/gt2djwkkbtl.html

Ruby: arr[1, 3]
来源：http://dali.xylfe.cn/Article/details/gt2qblepclp.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenzaomai.com/Article/details/gt2isyvxdwi.html

[D08] 合并两个数组
来源：http://dali.jinqigufen.top/Article/details/gt2ritrpmih.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmpzwxcs.html

PHP:  array_merge($a, $b);
来源：http://dali.dianchejie.cn/Article/details/gt2mzbnolsp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgufenzy.top/Article/details/gt2oquccqmw.html

TS:   [...a, ...b];
来源：http://dali.hongshengwenyu.top/Article/details/gt2vujmxxvp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ybcxt.top/Article/details/gt2zztwjwbj.html

Go:   append(a, b...)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fozwbmzr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qobqdfmv.html

C#:   a.Concat(b).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2ysqnsqsf.html

[D09] 排序（升序）
来源：http://dali.gaohongyu789.top/Article/details/gt2wezjfajh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gt2msknwitr.html

PHP:  sort($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2gksbgnxk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fzhhl.top/Article/details/gt2tbwciryy.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.andypj.xyz/Article/details/gt2xbfuwevq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.9152youxi.cn/Article/details/gt2huvncfui.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gt2qhezvdkc.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gt2qlffdcuj.html

C#:   list.Sort();
来源：http://dali.hammf.cn/Article/details/gt2wmymxcat.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuetiantiany.cn/Article/details/gt2cyehmwuk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.redwolf501.top/Article/details/gt2qwlelxgr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhixingplan.top/Article/details/gt2eglsvops.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gt2rvlawgec.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gt2zhgqkjdu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xinyue.icu/Article/details/gt2vifsmubs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2fprigylu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.redwolf501.top/Article/details/gt2rarrtahx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.mhx1999.top/Article/details/gt2benjdwqc.html

[D11] 反转数组
来源：http://dali.andypj.xyz/Article/details/gt2alclstse.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gt2yzeiwyhw.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2btkosefp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.svipenyu.cn/Article/details/gt2jkdgttod.html

TS:   [...arr].reverse();
来源：http://dali.daxiang520.top/Article/details/gt2vmruouqo.html

Java: Collections.reverse(list);
来源：http://dali.xylfe.cn/Article/details/gt2abgezzry.html

Go:   slices.Reverse(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xbptujte.html

Ruby: arr.reverse
来源：http://dali.havefunace.top/Article/details/gt2pdljgtjm.html

C#:   list.Reverse();
来源：http://dali.316326.xyz/Article/details/gt2bkmabzti.html

[D12] 查找元素下标
来源：http://dali.cdnleiting.top/Article/details/gt2hrcexovv.html

Py:   arr.index(x);  x in arr
来源：http://dali.yangfankeji.com/Article/details/gt2glkplnpg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2otjlxqfc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gt2cccptozw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gt2nbbdtsho.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pengpengdd.cyou/Article/details/gt2zmafilit.html

Go:   slices.Index(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gt2hkaendwz.html

Ruby: arr.index(x)
来源：http://dali.hywenlv.cn/Article/details/gt2kwxemadk.html

C#:   list.IndexOf(x);
来源：http://dali.quarkkingdee.top/Article/details/gt2dvvbvasu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gt2azdpfagn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gt2egomhpxd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj202588.top/Article/details/gt2qfjfnjtm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tanke756.top/Article/details/gt2eurywsqv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gt2ghlrhxzj.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2tnxyawia.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ppjwa.cn/Article/details/gt2yqgcxlhi.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.meibo888.top/Article/details/gt2sputgqyf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2yhrmplpe.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shzxlz.cn/Article/details/gt2aorjsdhn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cheryme.top/Article/details/gt2wjbdrndp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2rtwpanzp.html

JS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gt2hjwbduah.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gt2osniwxou.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gotoacloud.top/Article/details/gt2uhlmvvmp.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gt2piszypva.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gt2odyjopxp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qomfazvo.html

[D15] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2agtxswxq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gt2mzcdmywk.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ufcaaafd.html

JS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gt2vzcinkoj.html

TS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gt2rewgcujy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gt2oiufrsvp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnxiangtu.top/Article/details/gt2hyxumqyv.html

Ruby: arr.uniq
来源：http://dali.zhoulong.xyz/Article/details/gt2ipywpcrv.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gt2fqgwbgfa.html

[D16] 求和与平均值
来源：http://dali.hnqzz.top/Article/details/gt2puyizlng.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2xgrnxcje.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2mjekwtme.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gt2tyemjwww.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gt2gyvqknyf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.meibo888.top/Article/details/gt2yirxmqmp.html

Go:   // 手写循环累加
来源：http://dali.cqqwz.cn/Article/details/gt2uqdozvqp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnqzz.top/Article/details/gt2gsblgorl.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj202588.top/Article/details/gt2nkzzxdbw.html

[D17] 最大值与最小值
来源：http://dali.zdqjudy.top/Article/details/gt2jamzantj.html

Py:   max(arr);  min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2xhuatpfo.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2nqlcpcwl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jwwmpbjk.html

TS:   Math.max(...arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2ewhxspjl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.guowangkeji.top/Article/details/gt2hphstwqj.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.bjfxy.top/Article/details/gt2temdgpnd.html

Ruby: arr.max;  arr.min
来源：http://dali.yuxming.cn/Article/details/gt2ndkfibvl.html

C#:   list.Max();  list.Min()
来源：http://dali.nwbrower.top/Article/details/gt2oanzftgb.html

[D18] 扁平化嵌套数组
来源：http://dali.snrcjt.cn/Article/details/gt2xhpnvkwa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ppjwa.cn/Article/details/gt2wpcopcoe.html

PHP:  array_merge(...$nested);
来源：http://dali.tanke756.top/Article/details/gt2rvttoosw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hfpthk.cn/Article/details/gt2sarxezxy.html

TS:   nested.flat();
来源：http://dali.dashuyun.cn/Article/details/gt2ydqrykuy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.smart0.xyz/Article/details/gt2sbsjzamk.html

Go:   // 手写双层循环
来源：http://dali.shuidangran.top/Article/details/gt2epmjcool.html

Ruby: nested.flatten
来源：http://dali.sufxvd.cn/Article/details/gt2gotrwgui.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guannengcc.top/Article/details/gt2bmrxjtlh.html

[D19] 按字段分组
来源：http://dali.hammf.cn/Article/details/gt2edszqfst.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2wpastdue.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jlsjyb.cn/Article/details/gt2cfraifcx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daria6918.cn/Article/details/gt2egbxrghd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vnrbmssq.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.316326.xyz/Article/details/gt2wwjzkcsq.html

Go:   // 手写 map[string][]T
来源：http://dali.zdqjudy.top/Article/details/gt2agayrvsm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aibaodan.cn/Article/details/gt2xdmruzbp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.mhx1999.top/Article/details/gt2ynyuuycy.html

[D20] 统计每个元素出现次数
来源：http://dali.ppjwa.cn/Article/details/gt2tflijqjt.html

Py:   Counter(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2qkbzwcdx.html

PHP:  array_count_values($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2qgtrmxtf.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gt2ncbbjktx.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gt2jxioowca.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhiwuduotai.top/Article/details/gt2ralkfkah.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gt2xgxqiztc.html

Ruby: arr.tally
来源：http://dali.xuetiantiany.cn/Article/details/gt2wzwkcjxb.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxinkj.top/Article/details/gt2pgwgspxt.html

[D21] 判断是否包含某元素
来源：http://dali.jyoumei.cn/Article/details/gt2htcwjlii.html

Py:   x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gt2recrqwdj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.aizwys.cn/Article/details/gt2nwyxnodr.html

JS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2tglnspwg.html

TS:   arr.includes(x)
来源：http://dali.haohaochexian.top/Article/details/gt2demevkmy.html

Java: list.contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2mnbhomph.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gt2rkbjqiih.html

Ruby: arr.include?(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2hieoogjd.html

C#:   list.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2helgcswa.html

[D22] 复制数组（避免共享引用）
来源：http://dali.chenlongwang.top/Article/details/gt2uhgkdtmc.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2exjvjvgv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.cheryme.top/Article/details/gt2fydjtxgu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.tianlin.xyz/Article/details/gt2rolmticl.html

TS:   [...arr];
来源：http://dali.yonumen.top/Article/details/gt2zwrlimhp.html

Java: new ArrayList<>(list);
来源：http://dali.yanxiufei.cn/Article/details/gt2pohbsljp.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.sweek.top/Article/details/gt2cichudci.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gaohongyu789.top/Article/details/gt2tconajfz.html

C#:   new List<int>(list);
来源：http://dali.hnqzz.top/Article/details/gt2fokxqboi.html

[D23] reduce 累积计算
来源：http://dali.shuidangran.top/Article/details/gt2jcujwvdk.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.haohaochexian.top/Article/details/gt2omowxktp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2jbadvejm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2umlbdtkg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oojihdlb.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bygotxnh.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gt2uudqtgbn.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hongshengwenyu.top/Article/details/gt2eyyhfpfc.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpmbsnll.html

[D24] 字典 / Map 基本操作
来源：http://dali.hammf.cn/Article/details/gt2gdievmir.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.zhongyouzk.top/Article/details/gt2wkdsndaw.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yueranfly.top/Article/details/gt2tecqjvtz.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fzhhl.top/Article/details/gt2qduqhnuw.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yuxming.cn/Article/details/gt2ilxtihug.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.andypj.xyz/Article/details/gt2brfbpjes.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.cucudq.cn/Article/details/gt2tiulmmwp.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.andypj.xyz/Article/details/gt2buruigte.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ezhvmjve.html

[D25] Set 集合去重与交并差
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvruaxdq.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.tanke756.top/Article/details/gt2poiptlhr.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shuidangran.top/Article/details/gt2hesymqwh.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ybcxt.top/Article/details/gt2swjlqjho.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yongpay.top/Article/details/gt2nqcxkkxw.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gt2yvmwledd.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.smart0.xyz/Article/details/gt2yqkxplhk.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gt2wnrrtpoh.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.snrcjt.cn/Article/details/gt2ysdlldtw.html

[D26] 数组转字符串
来源：http://dali.zycfv.cn/Article/details/gt2nphqrlbi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.meibo888.top/Article/details/gt2rjofbpzg.html

PHP:  implode(", ", $arr);
来源：http://dali.zycfv.cn/Article/details/gt2gfgaxuhq.html

JS:   arr.join(", ")
来源：http://dali.jiagoushi.top/Article/details/gt2neixnqkt.html

TS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2pwfvphwa.html

Java: String.join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gt2uniyfkxp.html

Go:   strings.Join(strs, ", ")
来源：http://dali.pycfn.com/Article/details/gt2dqjhywkd.html

Ruby: arr.join(", ")
来源：http://dali.c1oappe.top/Article/details/gt2pkdsjcos.html

C#:   string.Join(", ", list)
来源：http://dali.jiagoushi.top/Article/details/gt2xuitdwxl.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2dhgmrebq.html

E. 字符串处理
来源：http://dali.hnxiangtu.top/Article/details/gt2xyhgwajt.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2mljezqvh.html

[E01] 拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gt2alyvpzkg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.yj20258.top/Article/details/gt2hbibwwoj.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.aizwys.cn/Article/details/gt2mgasfmsc.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yj20258.top/Article/details/gt2mhqxjdyy.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.yueranfly.top/Article/details/gt2laqzdlle.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.cdnleiting.top/Article/details/gt2wjxiwdza.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.chenlongwang.top/Article/details/gt2krbinuds.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.bjfxy.top/Article/details/gt2cehctxyg.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2zmidkghe.html

[E02] 重复字符串
来源：http://dali.zycfv.cn/Article/details/gt2winindvu.html

Py:   "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gt2xwhmlfgq.html

PHP:  str_repeat("ab", 3);
来源：http://dali.hfpthk.cn/Article/details/gt2nusaollr.html

JS:   "ab".repeat(3)
来源：http://dali.fengsongda.top/Article/details/gt2tnrdpmsc.html

TS:   "ab".repeat(3)
来源：http://dali.andypj.xyz/Article/details/gt2fknokbqa.html

Java: "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gt2qhoroirz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.mhx1999.top/Article/details/gt2shzaxicj.html

Ruby: "ab" * 3
来源：http://dali.tianlin.xyz/Article/details/gt2jncmdnba.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpnbdvxx.html

[E03] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gt2yrbdggcu.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.9152youxi.cn/Article/details/gt2yqxwkgoo.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gt2tpdxxpqo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jianghu66.top/Article/details/gt2nrbjvltl.html

TS:   s.slice(1, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2ifxfdbbz.html

Java: s.substring(1, 4)
来源：http://dali.yongpay.top/Article/details/gt2ngpmhadn.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cqqwz.cn/Article/details/gt2kkjpftys.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.daria6918.cn/Article/details/gt2ctbmulpf.html

C#:   s.Substring(1, 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2kjprsrak.html

[E04] 查找子串位置
来源：http://dali.ehwqpu.com/Article/details/gt2itetmdwk.html

Py:   s.find("x");  s.index("x")
来源：http://dali.guannengcc.top/Article/details/gt2qnvbdfmc.html


<!-- 参考信息 -->