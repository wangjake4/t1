代发 wailian999

[C14] 泛型函数
来源：http://dali.haohaochexian.top/Article/details/gt2rgnnrwub.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhiwuduotai.top/Article/details/gt2ewrdtlaw.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gt2kxumhxri.html

JS:   // 无泛型
来源：http://dali.daxiang520.top/Article/details/gt2lrhctmdd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gt2uhkumydw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ehzlgjpc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hpjsapgx.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gt2edaxrdwl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnxiangtu.top/Article/details/gt2xhypgutf.html

[C15] 解构 / 展开参数
来源：http://dali.zhongyouzk.top/Article/details/gt2fkbrwwru.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.bjfxy.top/Article/details/gt2gwacjgob.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenjidiqi.icu/Article/details/gt2bxbvotiz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gt2pdfahbbu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rbhnvcqj.html

Java: // 无解构
来源：http://dali.haohaochexian.top/Article/details/gt2wujpjsjr.html

Go:   // 无解构
来源：http://dali.yongpay.top/Article/details/gt2wtqlggdl.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gt2pcufwcic.html

C#:   var (a, b) = pair;
来源：http://dali.mhx1999.top/Article/details/gt2lreojvxe.html

[C16] 函数 / 方法重载
来源：http://dali.svipenyu.cn/Article/details/gt2ltkhavtb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daxiang520.top/Article/details/gt2lmoynyca.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gt2okoxeedc.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jlsjyb.cn/Article/details/gt2nopbqdbk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cdnleiting.top/Article/details/gt2gbhocskr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xziqi.cn/Article/details/gt2qtbbjumj.html

Go:   // 无重载：用不同函数名
来源：http://dali.316326.xyz/Article/details/gt2puvjsvqa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xziqi.cn/Article/details/gt2atvyuflk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2smlsjnrq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ajrrzzjf.html

D. 数组 / 列表 / 集合
来源：http://dali.ehwqpu.com/Article/details/gt2iljglyps.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhzgcsvu.html

[D01] 创建数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gt2iagadjqn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.vqdsnc.cn/Article/details/gt2mtgsgbid.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.316326.xyz/Article/details/gt2hjaxosbj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ehwqpu.com/Article/details/gt2qjvissma.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cdnleiting.top/Article/details/gt2htjhvcgw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gt2dbwxjbhg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fengsongda.top/Article/details/gt2gtphzbyz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gt2biynnayz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgufenzy.top/Article/details/gt2hujhyisw.html

[D02] 追加元素到末尾
来源：http://dali.kuanghao11.cn/Article/details/gt2smsyyter.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangshuangyany.cn/Article/details/gt2bbjoujbs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tanke756.top/Article/details/gt2vewcrczt.html

JS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gt2hewxdnlf.html

TS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gt2kpflxaek.html

Java: list.add(4);
来源：http://dali.ehwqpu.com/Article/details/gt2jejdxzjh.html

Go:   arr = append(arr, 4)
来源：http://dali.fzhhl.top/Article/details/gt2hdlkassz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tianlin.xyz/Article/details/gt2pyswxeox.html

C#:   list.Add(4);
来源：http://dali.316326.xyz/Article/details/gt2xtqjanas.html

[D03] 在指定位置插入元素
来源：http://dali.chenzaomai.com/Article/details/gt2fwfiglts.html

Py:   arr.insert(0, 0)
来源：http://dali.svipenyu.cn/Article/details/gt2ggflbwke.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258888.top/Article/details/gt2idtxsitt.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gt2epithxsw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.c1oappe.top/Article/details/gt2ocbuootr.html

Java: list.add(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2lxxmgopa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gdphnyna.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258888.top/Article/details/gt2acjxomat.html

C#:   list.Insert(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hgaxkgwo.html

[D04] 删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgxwpbyi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.iojbl.cn/Article/details/gt2wvflctbn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tian-w.cn/Article/details/gt2pqqpazgl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pengpengdd.cyou/Article/details/gt2vuzoeujw.html

TS:   arr.splice(0, 1);
来源：http://dali.smart0.xyz/Article/details/gt2dlwudpwh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jianghu66.top/Article/details/gt2dbuptbrh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ybcxt.top/Article/details/gt2kvsscfki.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.birdmap.top/Article/details/gt2rtxobtza.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guowangkeji.top/Article/details/gt2jcnewczu.html

[D05] 访问与修改元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2qixqtbrr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gt2vgkifrhl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gt2cozuuvjg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gt2fvmjvldf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ybcxt.top/Article/details/gt2tjfcyihg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ehwqpu.com/Article/details/gt2kvpiycwf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gt2vcrriuhn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gt2dykpetsq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hinmrmbl.html

[D06] 数组长度
来源：http://dali.zhixingplan.top/Article/details/gt2zvnhjomn.html

Py:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gt2ociskziw.html

PHP:  count($arr);
来源：http://dali.fengsongda.top/Article/details/gt2gyhlqaej.html

JS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gt2ogejxdde.html

TS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gt2ynxzeqgy.html

Java: list.size();
来源：http://dali.zhiwuduotai.top/Article/details/gt2nsvnlvzs.html

Go:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2qcofyvzc.html

Ruby: arr.length; arr.size
来源：http://dali.hnxiangtu.top/Article/details/gt2fllnvmxf.html

C#:   list.Count;
来源：http://dali.chenzaomai.com/Article/details/gt2xdgztqlw.html

[D07] 切片 / 取子数组
来源：http://dali.fengsongda.top/Article/details/gt2wpdhumhn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sxryk.cn/Article/details/gt2snvcyqpx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gt2wdvquvpd.html

JS:   arr.slice(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gt2pglokglx.html

TS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gt2vfoexebm.html

Java: list.subList(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gt2snubrwqi.html

Go:   arr[1:4]
来源：http://dali.cheryme.top/Article/details/gt2ezoknvyh.html

Ruby: arr[1, 3]
来源：http://dali.zhengqikj.top/Article/details/gt2gvqmpusq.html

C#:   list.GetRange(1, 3);
来源：http://dali.aizwys.cn/Article/details/gt2czucxzbw.html

[D08] 合并两个数组
来源：http://dali.yongpay.top/Article/details/gt2dcrvnhti.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2ijdrjgmw.html

PHP:  array_merge($a, $b);
来源：http://dali.haohaochexian.top/Article/details/gt2vxldunvr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yonumen.top/Article/details/gt2oyrufvcq.html

TS:   [...a, ...b];
来源：http://dali.sysykeji.top/Article/details/gt2jcuttozg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2askbhkrk.html

Go:   append(a, b...)
来源：http://dali.bjfxy.top/Article/details/gt2suaigdjy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gt2wneitfcb.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj202588.top/Article/details/gt2kqgoptvy.html

[D09] 排序（升序）
来源：http://dali.sufxvd.cn/Article/details/gt2cqbqdxbb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gt2tnzphkpk.html

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2calbmftm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258.top/Article/details/gt2tehsztol.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.svipenyu.cn/Article/details/gt2fhvbjogb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jwmlpqeb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2hmdoxkuu.html

Ruby: arr.sort
来源：http://dali.yj20258888.top/Article/details/gt2rxwoigqt.html

C#:   list.Sort();
来源：http://dali.tanke756.top/Article/details/gt2ywinfgzd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guowangkeji.top/Article/details/gt2lzybaamy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xylfe.cn/Article/details/gt2fdnybhar.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gt2apiwmaox.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lptwginz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gt2ywwmphnd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.feifeiyinyue.top/Article/details/gt2humnzlhd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnxiangtu.top/Article/details/gt2gcsndwgx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shangyingyoupin.top/Article/details/gt2bywnueps.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ivvv.top/Article/details/gt2tkhhehgo.html

[D11] 反转数组
来源：http://dali.hywenlv.cn/Article/details/gt2ivlbpfbp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gt2glkllsqc.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gt2evvdeopc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmnygqmm.html

TS:   [...arr].reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwphflqc.html

Java: Collections.reverse(list);
来源：http://dali.nanxuanxn.top/Article/details/gt2qdgtesbh.html

Go:   slices.Reverse(arr)
来源：http://dali.316326.xyz/Article/details/gt2kwlvhjtc.html

Ruby: arr.reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2jhrlxipq.html

C#:   list.Reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gt2tiaexyon.html

[D12] 查找元素下标
来源：http://dali.cheryme.top/Article/details/gt2odizutbr.html

Py:   arr.index(x);  x in arr
来源：http://dali.aizwys.cn/Article/details/gt2wyzycwfe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tmtaqgrw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zvikpaxs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.316326.xyz/Article/details/gt2csgfzsxm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj20258.top/Article/details/gt2rkvvbloa.html

Go:   slices.Index(arr, x)
来源：http://dali.yonumen.top/Article/details/gt2wwqappoy.html

Ruby: arr.index(x)
来源：http://dali.yj202588.top/Article/details/gt2pkrperpw.html

C#:   list.IndexOf(x);
来源：http://dali.fengsongda.top/Article/details/gt2oiunovbc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jianghu66.top/Article/details/gt2pqiazetd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yangfankeji.com/Article/details/gt2qjqwlxhm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cashguo.top/Article/details/gt2smrooruk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gt2aquznmvn.html

TS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gt2vzyteync.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.redwolf501.top/Article/details/gt2nupztkep.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.haohaochexian.top/Article/details/gt2sikitwva.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.0kj1m.cn/Article/details/gt2jaqxbknb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.fengsongda.top/Article/details/gt2kuvghrsc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xuetiantiany.cn/Article/details/gt2ryvfknmz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yj202588.top/Article/details/gt2rcxaoaew.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2jfvrlmmj.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gt2wesgfwpx.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nquzolej.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sufxvd.cn/Article/details/gt2akjvbgud.html

Go:   // 手写循环
来源：http://dali.shzxlz.cn/Article/details/gt2gpdnfhbr.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cucudq.cn/Article/details/gt2ftstbskn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2zkszrdqn.html

[D15] 去重
来源：http://dali.jyoumei.cn/Article/details/gt2gixwdjse.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkpexvml.html

PHP:  array_unique($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2gwfvvbhy.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eeqehjsu.html

TS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gt2shwgvvmu.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.kuanghao11.cn/Article/details/gt2etbjnlsn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj20258.top/Article/details/gt2gdsugrjn.html

Ruby: arr.uniq
来源：http://dali.chenjidiqi.icu/Article/details/gt2pvlljrto.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gt2dbryihmv.html

[D16] 求和与平均值
来源：http://dali.zhongyouzk.top/Article/details/gt2yajkjiye.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yonumen.top/Article/details/gt2nknncqah.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangdashe.top/Article/details/gt2lkywaoru.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gt2ptmpdmid.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gt2esnlcnqg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pycfn.com/Article/details/gt2jdtzxcpb.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xudfkwky.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daria6918.cn/Article/details/gt2wxnzhlpz.html

C#:   list.Sum();  list.Average()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uevddrrc.html

[D17] 最大值与最小值
来源：http://dali.pycfn.com/Article/details/gt2tizdrqrx.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2oozktcga.html

PHP:  max($arr);  min($arr);
来源：http://dali.fengsongda.top/Article/details/gt2cavwtvga.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yangfankeji.com/Article/details/gt2hondfqae.html

TS:   Math.max(...arr);
来源：http://dali.ppjwa.cn/Article/details/gt2wlilyyyz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gt2ecyrtfrq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajgswcag.html

Ruby: arr.max;  arr.min
来源：http://dali.haohaochexian.top/Article/details/gt2mnylkuwq.html

C#:   list.Max();  list.Min()
来源：http://dali.jqgufenzy.top/Article/details/gt2dnkvoifk.html

[D18] 扁平化嵌套数组
来源：http://dali.gogol.net.cn/Article/details/gt2kypyhaki.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gt2dxgvduas.html

PHP:  array_merge(...$nested);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmpikvfc.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj202588.top/Article/details/gt2xpjmljda.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gt2cbclylep.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.pycfn.com/Article/details/gt2pmryhhly.html

Go:   // 手写双层循环
来源：http://dali.aibaodan.cn/Article/details/gt2gcuqtgzg.html

Ruby: nested.flatten
来源：http://dali.nwbrower.top/Article/details/gt2hjkqplpp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gt2okbuxwcg.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gt2iukbdkow.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.ybcxt.top/Article/details/gt2apiybddh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yueranfly.top/Article/details/gt2zdivrgdr.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jqgfzy.top/Article/details/gt2kamvkrrp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhengqikj.top/Article/details/gt2fyxpsibx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhengqikj.top/Article/details/gt2yxgowqrm.html

Go:   // 手写 map[string][]T
来源：http://dali.wangshuangyany.cn/Article/details/gt2rrkyoadw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.redwolf501.top/Article/details/gt2nvsbfqjp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmkordtm.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigufen.top/Article/details/gt2cbhtlocm.html

Py:   Counter(arr)
来源：http://dali.hfpthk.cn/Article/details/gt2ltoweqtp.html

PHP:  array_count_values($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2btsapiha.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.andypj.xyz/Article/details/gt2qbtqlzsn.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daxiang520.top/Article/details/gt2tglzffik.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.iojbl.cn/Article/details/gt2tpbdxatz.html

Go:   // 手写 map[T]int
来源：http://dali.shzxlz.cn/Article/details/gt2djxavexw.html

Ruby: arr.tally
来源：http://dali.zhongyouzk.top/Article/details/gt2dlyihhic.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qtkwmbvl.html

[D21] 判断是否包含某元素
来源：http://dali.aizwys.cn/Article/details/gt2jdwqtcah.html

Py:   x in arr
来源：http://dali.gogol.net.cn/Article/details/gt2gmccewhw.html

PHP:  in_array($x, $arr, true);
来源：http://dali.snrcjt.cn/Article/details/gt2ptyodpww.html

JS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gt2qtcrvvlu.html

TS:   arr.includes(x)
来源：http://dali.yongpay.top/Article/details/gt2lkqrsrna.html

Java: list.contains(x)
来源：http://dali.xylfe.cn/Article/details/gt2jbqrmwnz.html

Go:   slices.Contains(arr, x)
来源：http://dali.yvedp.cn/Article/details/gt2npsxttmw.html

Ruby: arr.include?(x)
来源：http://dali.haohaochexian.top/Article/details/gt2gvmxtwdu.html

C#:   list.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2rjbloefh.html

[D22] 复制数组（避免共享引用）
来源：http://dali.sweek.top/Article/details/gt2cgsityjy.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.yj20258.top/Article/details/gt2rxwnobsv.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.hfpthk.cn/Article/details/gt2ngchhoiy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2droibunj.html

TS:   [...arr];
来源：http://dali.jinqigfzy.top/Article/details/gt2hzptswyd.html

Java: new ArrayList<>(list);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lvilreav.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hongshengwenyu.top/Article/details/gt2uncxvryw.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ppjwa.cn/Article/details/gt2ilotyenu.html

C#:   new List<int>(list);
来源：http://dali.pycfn.com/Article/details/gt2dvwddhih.html

[D23] reduce 累积计算
来源：http://dali.shzxlz.cn/Article/details/gt2kifvache.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2gllulkhb.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.wangdashe.top/Article/details/gt2vwsvyebf.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2afmcnfvk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.jianghu66.top/Article/details/gt2ypwwqkxy.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.nanxuanxn.top/Article/details/gt2wyhvirlc.html

Go:   // 手写循环
来源：http://dali.aibaodan.cn/Article/details/gt2oqixwaox.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jlsjyb.cn/Article/details/gt2onvrnxsp.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.gaohongyu789.top/Article/details/gt2vyembohx.html

[D24] 字典 / Map 基本操作
来源：http://dali.yvedp.cn/Article/details/gt2refosejz.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.9152youxi.cn/Article/details/gt2znnjtrqr.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.meibo888.top/Article/details/gt2ocflhzpe.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.jinqigufen.top/Article/details/gt2rnlnfojt.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2gfcegxnq.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.daria6918.cn/Article/details/gt2imjlcwgz.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.9152youxi.cn/Article/details/gt2sjjfcbmz.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.tianlin.xyz/Article/details/gt2tbnfclwm.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.dianchejie.cn/Article/details/gt2slscucbu.html

[D25] Set 集合去重与交并差
来源：http://dali.nwbrower.top/Article/details/gt2dgknahkc.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rgcojefh.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.snrcjt.cn/Article/details/gt2xesohwef.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.nwbrower.top/Article/details/gt2ldcxlcpi.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.xylfe.cn/Article/details/gt2yvoupuhv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.bjfxy.top/Article/details/gt2bgwbceth.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ibereicg.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.wangdashe.top/Article/details/gt2cnvlphwj.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.c1oappe.top/Article/details/gt2ozdnnzvb.html

[D26] 数组转字符串
来源：http://dali.shuidangran.top/Article/details/gt2jtzhvoaa.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gotoacloud.top/Article/details/gt2pydqhbrj.html

PHP:  implode(", ", $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2apjlalgx.html

JS:   arr.join(", ")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mccgdutq.html

TS:   arr.join(", ")
来源：http://dali.smart0.xyz/Article/details/gt2rnzuwddi.html

Java: String.join(", ", list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fhddzdfa.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xylfe.cn/Article/details/gt2elualxfv.html

Ruby: arr.join(", ")
来源：http://dali.0kj1m.cn/Article/details/gt2veifhtvy.html

C#:   string.Join(", ", list)
来源：http://dali.dianchejie.cn/Article/details/gt2abcckroa.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2qxertxkm.html

E. 字符串处理
来源：http://dali.shzxlz.cn/Article/details/gt2mqaiacgr.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2fybznwwz.html

[E01] 拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gt2llftdgwk.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ppjwa.cn/Article/details/gt2jvykydbz.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jyoumei.cn/Article/details/gt2msrmjdai.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gt2iciywncv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bbjvxwsl.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.quarkkingdee.top/Article/details/gt2rnbglgjb.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jinqigfzy.top/Article/details/gt2rbbvrmdv.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigfzy.top/Article/details/gt2fiaibpsf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gt2lufysamo.html

[E02] 重复字符串
来源：http://dali.mhx1999.top/Article/details/gt2nrxeohlm.html

Py:   "ab" * 3
来源：http://dali.yonumen.top/Article/details/gt2qwsuazrm.html

PHP:  str_repeat("ab", 3);
来源：http://dali.andypj.xyz/Article/details/gt2hwetaonz.html

JS:   "ab".repeat(3)
来源：http://dali.fzhhl.top/Article/details/gt2nnjgifzk.html

TS:   "ab".repeat(3)
来源：http://dali.yueranfly.top/Article/details/gt2bvkvmpqg.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rypfkbgt.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sufxvd.cn/Article/details/gt2efietqte.html

Ruby: "ab" * 3
来源：http://dali.yvedp.cn/Article/details/gt2uvpcjzch.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.gzhubu.top/Article/details/gt2kykqiuxm.html

[E03] 截取子串
来源：http://dali.fzhhl.top/Article/details/gt2rwfnfbzh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.cqqwz.cn/Article/details/gt2mnavcsup.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gt2bzkithaq.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.nwbrower.top/Article/details/gt2zqbxlwmn.html

TS:   s.slice(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gt2civgcbmf.html

Java: s.substring(1, 4)
来源：http://dali.shuidangran.top/Article/details/gt2qerivhij.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj20258.top/Article/details/gt2qrhcqlxo.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.sweek.top/Article/details/gt2fjbzcpbe.html

C#:   s.Substring(1, 3)
来源：http://dali.tian-w.cn/Article/details/gt2ntmvfvfv.html

[E04] 查找子串位置
来源：http://dali.zdqjudy.top/Article/details/gt2mtrglrhf.html

Py:   s.find("x");  s.index("x")
来源：http://dali.nanxuanxn.top/Article/details/gt2rxqckzkc.html

PHP:  strpos($s, "x");
来源：http://dali.xylfe.cn/Article/details/gt2cuibjlxp.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.yuanzhike.top/Article/details/gt2qkybzken.html

TS:   s.indexOf("x")
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmcwecex.html

Java: s.indexOf("x")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bsyfjsrw.html


<!-- 参考信息 -->