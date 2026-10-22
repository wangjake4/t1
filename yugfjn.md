代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2wujywrei.html

Go:   func add(a, b int) int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zjghpdbg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guannengcc.top/Article/details/gt2eflyvaeg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.svipenyu.cn/Article/details/gt2uvejxjiw.html

[C14] 泛型函数
来源：http://dali.birdmap.top/Article/details/gt2leqznqlk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigufen.top/Article/details/gt2ilftedkk.html

PHP:  // 无泛型
来源：http://dali.cheryme.top/Article/details/gt2dziapmps.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gt2aojznspj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cucudq.cn/Article/details/gt2nowdmfhv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bpoeyigq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.birdmap.top/Article/details/gt2ceskgjmg.html

Ruby: # 无泛型
来源：http://dali.ivvv.top/Article/details/gt2sdvmurwa.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.feifeiyinyue.top/Article/details/gt2vpquhyvn.html

[C15] 解构 / 展开参数
来源：http://dali.zdqjudy.top/Article/details/gt2lqfaojfp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhoulong.xyz/Article/details/gt2iynplxlb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhengqikj.top/Article/details/gt2dgiuslco.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gt2gsjwswju.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj202588.top/Article/details/gt2xivaszeh.html

Java: // 无解构
来源：http://dali.nanxinkj.top/Article/details/gt2mwzynpjd.html

Go:   // 无解构
来源：http://dali.shuidangran.top/Article/details/gt2zzrrkvrc.html

Ruby: a, b = pair
来源：http://dali.nanxuanxn.top/Article/details/gt2somsqaib.html

C#:   var (a, b) = pair;
来源：http://dali.daria6918.cn/Article/details/gt2zhynbnvn.html

[C16] 函数 / 方法重载
来源：http://dali.tanke756.top/Article/details/gt2vyqwcbrk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gotoacloud.top/Article/details/gt2fylypsss.html

PHP:  // 无重载
来源：http://dali.svipenyu.cn/Article/details/gt2znlezrul.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.9152youxi.cn/Article/details/gt2fpqxztmg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgfzy.top/Article/details/gt2xjuigzuc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sufxvd.cn/Article/details/gt2vksycjij.html

Go:   // 无重载：用不同函数名
来源：http://dali.c1oappe.top/Article/details/gt2cjpfdtel.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gt2mklxosui.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2spmmvdop.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2oxanxihn.html

D. 数组 / 列表 / 集合
来源：http://dali.vqdsnc.cn/Article/details/gt2mzlrudzr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2yvbmazuf.html

[D01] 创建数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gt2tsedajud.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yangfankeji.com/Article/details/gt2dkdzuyuf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cdnleiting.top/Article/details/gt2vadqthrr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wznnloie.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.havefunace.top/Article/details/gt2dqtbacsk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gt2iwijzpkm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pengpengdd.cyou/Article/details/gt2koyvqzkz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gt2raqhymrm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xylfe.cn/Article/details/gt2hcfcxpfu.html

[D02] 追加元素到末尾
来源：http://dali.shuidangran.top/Article/details/gt2bxuwbakq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.birdmap.top/Article/details/gt2ywlydsrp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenzaomai.com/Article/details/gt2breegkty.html

JS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gt2unffxbcg.html

TS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gt2qllfkjbr.html

Java: list.add(4);
来源：http://dali.nwbrower.top/Article/details/gt2nkmfevud.html

Go:   arr = append(arr, 4)
来源：http://dali.tianlin.xyz/Article/details/gt2sqnafxvx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2petsabti.html

C#:   list.Add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vwnragfl.html

[D03] 在指定位置插入元素
来源：http://dali.aizwys.cn/Article/details/gt2xwxsfyhb.html

Py:   arr.insert(0, 0)
来源：http://dali.xziqi.cn/Article/details/gt2prgzrrao.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2eoxxwbxp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gt2iairsrtr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guowangkeji.top/Article/details/gt2fjekekgl.html

Java: list.add(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jxnfoyws.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sysykeji.top/Article/details/gt2rsouvcas.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daria6918.cn/Article/details/gt2hamlottg.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2iqxqxtml.html

[D04] 删除元素
来源：http://dali.yueranfly.top/Article/details/gt2flqfyyma.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.svipenyu.cn/Article/details/gt2xnhxrzzs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.havefunace.top/Article/details/gt2fjrdobze.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.kuanghao11.cn/Article/details/gt2xatysbmq.html

TS:   arr.splice(0, 1);
来源：http://dali.jlsjyb.cn/Article/details/gt2uheihnwq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2agzgxtaz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gt2guejzofx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbgvfuz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yongpay.top/Article/details/gt2nxckxkjp.html

[D05] 访问与修改元素
来源：http://dali.quarkkingdee.top/Article/details/gt2kkioloxh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2ldwnklgb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2mxtzrfea.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gt2jghihbbw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.quarkkingdee.top/Article/details/gt2nkijrhuf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tianlin.xyz/Article/details/gt2yfuxkdln.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gt2irjjhjam.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gt2habsjweg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gt2opwvxkqz.html

[D06] 数组长度
来源：http://dali.zdqjudy.top/Article/details/gt2qhfvudjt.html

Py:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gt2kdewigog.html

PHP:  count($arr);
来源：http://dali.svipenyu.cn/Article/details/gt2ejhlzzqe.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gt2qssiklfu.html

TS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gt2ifiabxrr.html

Java: list.size();
来源：http://dali.hnqzz.top/Article/details/gt2btpmrknv.html

Go:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qdlstrhu.html

Ruby: arr.length; arr.size
来源：http://dali.xinyue.icu/Article/details/gt2daggtobb.html

C#:   list.Count;
来源：http://dali.hammf.cn/Article/details/gt2lxfpifue.html

[D07] 切片 / 取子数组
来源：http://dali.yvedp.cn/Article/details/gt2taopgsmz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jyoumei.cn/Article/details/gt2uazkfbsu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.mhx1999.top/Article/details/gt2wgzjsswy.html

JS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gt2cqfprxjd.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2izcmxdzw.html

Java: list.subList(1, 4);
来源：http://dali.hysaishi.cn/Article/details/gt2bmznbuak.html

Go:   arr[1:4]
来源：http://dali.hnxiangtu.top/Article/details/gt2ammuwlif.html

Ruby: arr[1, 3]
来源：http://dali.hnxiangtu.top/Article/details/gt2zkgxhcsm.html

C#:   list.GetRange(1, 3);
来源：http://dali.yonumen.top/Article/details/gt2ibkxkspg.html

[D08] 合并两个数组
来源：http://dali.hywenlv.cn/Article/details/gt2vtbhaayi.html

Py:   a + b;  a.extend(b)
来源：http://dali.c1oappe.top/Article/details/gt2pdxtfwzr.html

PHP:  array_merge($a, $b);
来源：http://dali.cucudq.cn/Article/details/gt2hlqkfqdq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmpmpqmq.html

TS:   [...a, ...b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2vbpwfkuw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yueranfly.top/Article/details/gt2hyenwnpd.html

Go:   append(a, b...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uttzwppa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuanzhike.top/Article/details/gt2pilqubgg.html

C#:   a.Concat(b).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2buremjkq.html

[D09] 排序（升序）
来源：http://dali.meibo888.top/Article/details/gt2rwenzygh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.meibo888.top/Article/details/gt2xgttimvn.html

PHP:  sort($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hqkrwrfk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ivvv.top/Article/details/gt2hrsrmlis.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uuhhpcrw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenlongwang.top/Article/details/gt2xjlyjjhi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2ybcewqtk.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gt2xdyftufk.html

C#:   list.Sort();
来源：http://dali.zhiwuduotai.top/Article/details/gt2dvgmwesn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jyoumei.cn/Article/details/gt2cvvmmbjh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.birdmap.top/Article/details/gt2affzxbhk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gt2oxtfsslp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gt2qjbtqrxh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gt2jljdgjdj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.guannengcc.top/Article/details/gt2uncsmjdy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dianchejie.cn/Article/details/gt2zcxlpajj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenzaomai.com/Article/details/gt2zedicswi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.redwolf501.top/Article/details/gt2xsbqpktp.html

[D11] 反转数组
来源：http://dali.yuxming.cn/Article/details/gt2mvdwuwfz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xylfe.cn/Article/details/gt2aiddanoa.html

PHP:  array_reverse($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2bwkbuubq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.andypj.xyz/Article/details/gt2gdgafooc.html

TS:   [...arr].reverse();
来源：http://dali.xziqi.cn/Article/details/gt2uvvfwzef.html

Java: Collections.reverse(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2oudbyrci.html

Go:   slices.Reverse(arr)
来源：http://dali.c1oappe.top/Article/details/gt2wldsffeb.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gt2hytmxisq.html

C#:   list.Reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jfesfhqq.html

[D12] 查找元素下标
来源：http://dali.jqgufenzy.top/Article/details/gt2equlzviy.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhixingplan.top/Article/details/gt2qsedxlza.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nwbrower.top/Article/details/gt2bmwyyjds.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gt2bhzmqxfd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uuesxqcw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhixingplan.top/Article/details/gt2eqgabwrj.html

Go:   slices.Index(arr, x)
来源：http://dali.nwbrower.top/Article/details/gt2efsinryw.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bhuujofy.html

C#:   list.IndexOf(x);
来源：http://dali.cucudq.cn/Article/details/gt2dsezgwtj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2tiexbrtr.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.birdmap.top/Article/details/gt2zcvaxlch.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2oahcsryf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gt2pqzjxvme.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gt2tserbzen.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cheryme.top/Article/details/gt2mebvzmci.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.c1oappe.top/Article/details/gt2sufsmqiv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nwbrower.top/Article/details/gt2fjcsazfz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shuidangran.top/Article/details/gt2xlukowgh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ppjwa.cn/Article/details/gt2lmbbvnsy.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zycfv.cn/Article/details/gt2jwyeelis.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tanke756.top/Article/details/gt2voasqjzs.html

JS:   arr.map(x => x * 2)
来源：http://dali.tanke756.top/Article/details/gt2slpouzok.html

TS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gt2ntquxoeq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2vnvvnfqh.html

Go:   // 手写循环
来源：http://dali.ppjwa.cn/Article/details/gt2wqbjfwew.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cucudq.cn/Article/details/gt2ofqytfwg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2koaaogox.html

[D15] 去重
来源：http://dali.c1oappe.top/Article/details/gt2nfuozuuq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gt2znjfdezx.html

PHP:  array_unique($arr);
来源：http://dali.daria6918.cn/Article/details/gt2mktzjyia.html

JS:   [...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gt2gurvwjuz.html

TS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gt2wbmamjtr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinqigfzy.top/Article/details/gt2sennboux.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.kuanghao11.cn/Article/details/gt2ysmjpebf.html

Ruby: arr.uniq
来源：http://dali.meibo888.top/Article/details/gt2fmmqdypk.html

C#:   list.Distinct().ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2rtbvbffe.html

[D16] 求和与平均值
来源：http://dali.jqgfzy.top/Article/details/gt2jhfsnskx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jianghu66.top/Article/details/gt2txyinlgg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2ycmfpgme.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2nicidjkw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2vnvjaibx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.mhx1999.top/Article/details/gt2xtnjmxmn.html

Go:   // 手写循环累加
来源：http://dali.gaohongyu789.top/Article/details/gt2ishpkjnl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gogol.net.cn/Article/details/gt2xmkvtuor.html

C#:   list.Sum();  list.Average()
来源：http://dali.zdqjudy.top/Article/details/gt2mzfbjxps.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gt2cnxpamjq.html

Py:   max(arr);  min(arr)
来源：http://dali.aizwys.cn/Article/details/gt2acteinqv.html

PHP:  max($arr);  min($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2wnuikcde.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.guowangkeji.top/Article/details/gt2rfwfjkwz.html

TS:   Math.max(...arr);
来源：http://dali.cdnleiting.top/Article/details/gt2vbhcrsqr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aizwys.cn/Article/details/gt2eplrodwo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2mbbzflek.html

Ruby: arr.max;  arr.min
来源：http://dali.dianchejie.cn/Article/details/gt2rzrhjeoc.html

C#:   list.Max();  list.Min()
来源：http://dali.pycfn.com/Article/details/gt2pblarrlm.html

[D18] 扁平化嵌套数组
来源：http://dali.yvedp.cn/Article/details/gt2waexuspz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.chenzaomai.com/Article/details/gt2rdbbqrrs.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gt2aclqxpfs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cdnleiting.top/Article/details/gt2xqgfoopj.html

TS:   nested.flat();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lxadniwz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.daxiang520.top/Article/details/gt2aftnnbks.html

Go:   // 手写双层循环
来源：http://dali.ehwqpu.com/Article/details/gt2mezprnxz.html

Ruby: nested.flatten
来源：http://dali.yuxming.cn/Article/details/gt2ibcakfvo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenlongwang.top/Article/details/gt2xvvqdxqq.html

[D19] 按字段分组
来源：http://dali.9152youxi.cn/Article/details/gt2chchjadl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xgbhrhbx.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.xuanzx.com/Article/details/gt2oeyupyws.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yanxiufei.cn/Article/details/gt2brcborkh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cheryme.top/Article/details/gt2dwqsrckv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hysaishi.cn/Article/details/gt2uvwykvtc.html

Go:   // 手写 map[string][]T
来源：http://dali.gzhubu.top/Article/details/gt2fgukgrsq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.svipenyu.cn/Article/details/gt2thkhcrfc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.wangshuangyany.cn/Article/details/gt2rohgxcba.html

[D20] 统计每个元素出现次数
来源：http://dali.havefunace.top/Article/details/gt2rqlxelse.html

Py:   Counter(arr)
来源：http://dali.c1oappe.top/Article/details/gt2svvypxsb.html

PHP:  array_count_values($arr);
来源：http://dali.xinyue.icu/Article/details/gt2fwgovyuc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.xuetiantiany.cn/Article/details/gt2omjezmuk.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guowangkeji.top/Article/details/gt2igznxbnf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gogol.net.cn/Article/details/gt2ajorzatj.html

Go:   // 手写 map[T]int
来源：http://dali.xuanzx.com/Article/details/gt2qyafdvet.html

Ruby: arr.tally
来源：http://dali.ybcxt.top/Article/details/gt2iolbokpu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gt2ulngjain.html

[D21] 判断是否包含某元素
来源：http://dali.cqqwz.cn/Article/details/gt2zdtafzcj.html

Py:   x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ebcmzscf.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sxryk.cn/Article/details/gt2zrpgatcm.html

JS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gt2sngulsno.html

TS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2aekzkcxb.html

Java: list.contains(x)
来源：http://dali.cdnleiting.top/Article/details/gt2rvandnyh.html

Go:   slices.Contains(arr, x)
来源：http://dali.yj20258888.top/Article/details/gt2yqrpgkpp.html

Ruby: arr.include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2lbpgdjli.html

C#:   list.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gt2jgvssick.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ppjwa.cn/Article/details/gt2opelvdps.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2hgucdquw.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pylaelsl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2gljwdekc.html

TS:   [...arr];
来源：http://dali.c1oappe.top/Article/details/gt2fohlfgep.html

Java: new ArrayList<>(list);
来源：http://dali.tianlin.xyz/Article/details/gt2wpxrvgtb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.cqqwz.cn/Article/details/gt2jqxxpsqb.html

Ruby: arr.dup;  arr.clone
来源：http://dali.fzhhl.top/Article/details/gt2aeskjxcz.html

C#:   new List<int>(list);
来源：http://dali.sxryk.cn/Article/details/gt2bgmowgwd.html

[D23] reduce 累积计算
来源：http://dali.gzhubu.top/Article/details/gt2wxwwqfaa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.jinqigufen.top/Article/details/gt2ejpwyyhp.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.guowangkeji.top/Article/details/gt2dmfibrra.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2autnbzgh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.daxiang520.top/Article/details/gt2uvsfwwok.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gaohongyu789.top/Article/details/gt2jjucuxfv.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gt2bfjojszi.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.shuidangran.top/Article/details/gt2dqsqypdz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.aibaodan.cn/Article/details/gt2vkctbiit.html

[D24] 字典 / Map 基本操作
来源：http://dali.yj20258.top/Article/details/gt2rwsqtfza.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.fzhhl.top/Article/details/gt2ozcgppxt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.ivvv.top/Article/details/gt2nctqprqn.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.fzhhl.top/Article/details/gt2tmxtiltv.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.pycfn.com/Article/details/gt2fhmeiwra.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sysykeji.top/Article/details/gt2gbayhwkf.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.shuidangran.top/Article/details/gt2ipcozvxk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sufxvd.cn/Article/details/gt2bhohuibn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.daria6918.cn/Article/details/gt2vlxqnhck.html

[D25] Set 集合去重与交并差
来源：http://dali.sweek.top/Article/details/gt2ozvpmchx.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.jinqigufen.top/Article/details/gt2olgfmfsz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.haohaochexian.top/Article/details/gt2qkusdujl.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2srglrvuf.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhfmkivl.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2awlpnvfz.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.chenjidiqi.icu/Article/details/gt2qgljgzuj.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfevpmc.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.birdmap.top/Article/details/gt2iuojsfzs.html

[D26] 数组转字符串
来源：http://dali.iojbl.cn/Article/details/gt2ujltipsd.html

Py:   ", ".join(map(str, arr))
来源：http://dali.cashguo.top/Article/details/gt2czqfhzzw.html

PHP:  implode(", ", $arr);
来源：http://dali.zdqjudy.top/Article/details/gt2ntefymdn.html

JS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gt2ejnvyhud.html

TS:   arr.join(", ")
来源：http://dali.nanxinkj.top/Article/details/gt2whhlifod.html

Java: String.join(", ", list)
来源：http://dali.cdnleiting.top/Article/details/gt2dizhcaoh.html

Go:   strings.Join(strs, ", ")
来源：http://dali.cheryme.top/Article/details/gt2anljsesm.html

Ruby: arr.join(", ")
来源：http://dali.hongshengwenyu.top/Article/details/gt2lkixtovi.html

C#:   string.Join(", ", list)
来源：http://dali.yuanzhike.top/Article/details/gt2wjivtied.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2psraygua.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gt2kynhohfb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2tzpvoufx.html

[E01] 拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gt2qlrweroz.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.xuanzx.com/Article/details/gt2idynpeam.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.mhx1999.top/Article/details/gt2cgeesjlb.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bumtyeye.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.nanxuanxn.top/Article/details/gt2mceomxwq.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.andypj.xyz/Article/details/gt2isjmrdzh.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.svipenyu.cn/Article/details/gt2snskuggm.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.yj202588.top/Article/details/gt2oxhxbwkt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2egaztdbk.html

[E02] 重复字符串
来源：http://dali.dashuyun.cn/Article/details/gt2zvrlkzfd.html

Py:   "ab" * 3
来源：http://dali.jianghu66.top/Article/details/gt2jxcmoyii.html

PHP:  str_repeat("ab", 3);
来源：http://dali.gotoacloud.top/Article/details/gt2aahrialc.html

JS:   "ab".repeat(3)
来源：http://dali.xuanzx.com/Article/details/gt2bbachmdm.html

TS:   "ab".repeat(3)
来源：http://dali.haohaochexian.top/Article/details/gt2qsikjlrw.html

Java: "ab".repeat(3)
来源：http://dali.zhixingplan.top/Article/details/gt2aotyreko.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mkdduyhj.html

Ruby: "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gt2dgjecgnk.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.haohaochexian.top/Article/details/gt2zkuxlbdi.html

[E03] 截取子串
来源：http://dali.316326.xyz/Article/details/gt2uwncshnv.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.zhoulong.xyz/Article/details/gt2gdyaeevt.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhiwuduotai.top/Article/details/gt2vneewtbh.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.yvedp.cn/Article/details/gt2uzqzipky.html

TS:   s.slice(1, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aaiephln.html

Java: s.substring(1, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dchcktas.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yueranfly.top/Article/details/gt2dtkpxwoj.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cdnleiting.top/Article/details/gt2wrmurmyi.html

C#:   s.Substring(1, 3)
来源：http://dali.zdqjudy.top/Article/details/gt2efzaiwdh.html

[E04] 查找子串位置
来源：http://dali.yuxming.cn/Article/details/gt2xfqapmbx.html

Py:   s.find("x");  s.index("x")
来源：http://dali.ydzc1.top/Article/details/gt2ouqszqts.html


<!-- 参考信息 -->