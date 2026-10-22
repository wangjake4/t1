代发 wailian999

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gt2tanyqean.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhixingplan.top/Article/details/gt2jjsjqpxl.html

PHP:  // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gt2jhavghed.html

JS:   // 无泛型
来源：http://dali.316326.xyz/Article/details/gt2pvoqnmmw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2yqzumiur.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tianlin.xyz/Article/details/gt2diwctfgk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gt2oniithps.html

Ruby: # 无泛型
来源：http://dali.xziqi.cn/Article/details/gt2vvymwhgh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258888.top/Article/details/gt2qrhzojbc.html

[C15] 解构 / 展开参数
来源：http://dali.ybcxt.top/Article/details/gt2ucxtezvi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jyoumei.cn/Article/details/gt2hzphoutc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywutdvlq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2thqlkcdz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.bjfxy.top/Article/details/gt2uusbsoss.html

Java: // 无解构
来源：http://dali.0kj1m.cn/Article/details/gt2wsjiiqfx.html

Go:   // 无解构
来源：http://dali.meibo888.top/Article/details/gt2wbghqfez.html

Ruby: a, b = pair
来源：http://dali.meibo888.top/Article/details/gt2rmnoqjpt.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gt2vjylvxpp.html

[C16] 函数 / 方法重载
来源：http://dali.yvedp.cn/Article/details/gt2ajbsdkcv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fengsongda.top/Article/details/gt2soksbivp.html

PHP:  // 无重载
来源：http://dali.c1oappe.top/Article/details/gt2usmmlyou.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tanke756.top/Article/details/gt2sbaofopz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.havefunace.top/Article/details/gt2eegmrkoq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2spjegkde.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigfzy.top/Article/details/gt2hzbqiakg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258.top/Article/details/gt2ipbdwlpg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aibaodan.cn/Article/details/gt2wfchgrng.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kebmlnlt.html

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gt2clrjcwln.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2nfdmxaqj.html

[D01] 创建数组 / 列表
来源：http://dali.meibo888.top/Article/details/gt2zpatzqrf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258888.top/Article/details/gt2onjfcuuj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jianghu66.top/Article/details/gt2stpewxbp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gt2dkiplbir.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.snrcjt.cn/Article/details/gt2amfdfrdg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sufxvd.cn/Article/details/gt2urqlgnwx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgufenzy.top/Article/details/gt2ehuugbxh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nwbrower.top/Article/details/gt2pwglxmfw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ehwqpu.com/Article/details/gt2rqqbellp.html

[D02] 追加元素到末尾
来源：http://dali.jinqigufen.top/Article/details/gt2qmsxqydi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gt2ezjcyfzl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258.top/Article/details/gt2pkckweoi.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gt2ujorqsol.html

TS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gt2pngoyvkn.html

Java: list.add(4);
来源：http://dali.chenzaomai.com/Article/details/gt2dagovcqb.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2zudtwciq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gaohongyu789.top/Article/details/gt2yktynior.html

C#:   list.Add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wygdnlqo.html

[D03] 在指定位置插入元素
来源：http://dali.tianlin.xyz/Article/details/gt2wyatadtg.html

Py:   arr.insert(0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hdvfviji.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ehwqpu.com/Article/details/gt2qgixartn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.9152youxi.cn/Article/details/gt2xnhtarsi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2qkcxcyob.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2ckrjwxhd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhengqikj.top/Article/details/gt2dvkkbvlh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aizwys.cn/Article/details/gt2zbfcafwu.html

C#:   list.Insert(0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2vylkwzfp.html

[D04] 删除元素
来源：http://dali.jinqigufen.top/Article/details/gt2yckjbtcy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daxiang520.top/Article/details/gt2hzojeaea.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2yeosgazr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hammf.cn/Article/details/gt2gdwzkwms.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gt2oagabzyw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2npsoxkfm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yvedp.cn/Article/details/gt2jqixtjly.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gt2jisqbndl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sysykeji.top/Article/details/gt2zfbuiyik.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gt2podmikes.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gt2bibznege.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gt2nkennveo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gt2lwhvypbh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gt2lptnqwar.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgufenzy.top/Article/details/gt2nuyhuhep.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gt2mghqbbwy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfytjhkv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gt2qwpijlyv.html

[D06] 数组长度
来源：http://dali.cashguo.top/Article/details/gt2weutrcav.html

Py:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2sahmrvtl.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gt2vpqqgiil.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2xcqhptjg.html

TS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gt2qxpsmxcc.html

Java: list.size();
来源：http://dali.meibo888.top/Article/details/gt2dhtqtwpq.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubztlqjt.html

Ruby: arr.length; arr.size
来源：http://dali.daxiang520.top/Article/details/gt2dmsbsnlq.html

C#:   list.Count;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2frqvymfb.html

[D07] 切片 / 取子数组
来源：http://dali.hfpthk.cn/Article/details/gt2tjoukiuu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.iojbl.cn/Article/details/gt2lgfntcgv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cashguo.top/Article/details/gt2ozrltcnr.html

JS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gt2dbuvvmlg.html

TS:   arr.slice(1, 4);
来源：http://dali.hfpthk.cn/Article/details/gt2lvfzuzky.html

Java: list.subList(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gt2xakafwqm.html

Go:   arr[1:4]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nuhybtvl.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqspurvo.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gt2tngglmiv.html

[D08] 合并两个数组
来源：http://dali.cashguo.top/Article/details/gt2wrdadrfp.html

Py:   a + b;  a.extend(b)
来源：http://dali.cdnleiting.top/Article/details/gt2hvffombp.html

PHP:  array_merge($a, $b);
来源：http://dali.zhiwuduotai.top/Article/details/gt2tsnajoiy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.0kj1m.cn/Article/details/gt2gmcfauxr.html

TS:   [...a, ...b];
来源：http://dali.0kj1m.cn/Article/details/gt2fmrjqrci.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fwfthtet.html

Go:   append(a, b...)
来源：http://dali.sysykeji.top/Article/details/gt2lxklzzbv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2nzgxsxja.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gt2gijntywn.html

[D09] 排序（升序）
来源：http://dali.yj202588.top/Article/details/gt2rziuvmmp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gt2vlobpwpg.html

PHP:  sort($arr);
来源：http://dali.daxiang520.top/Article/details/gt2kvrkbraw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guowangkeji.top/Article/details/gt2ymrzzcts.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigufen.top/Article/details/gt2dkknmetq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xinyue.icu/Article/details/gt2uxcimkjj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sxryk.cn/Article/details/gt2eyzlqhak.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gt2xkbjftvf.html

C#:   list.Sort();
来源：http://dali.shangyingyoupin.top/Article/details/gt2xfipvbak.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.9152youxi.cn/Article/details/gt2vknstdyx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.quarkkingdee.top/Article/details/gt2loewxqmo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cqqwz.cn/Article/details/gt2vmzjlaey.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wsanuthg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gt2xbgszorx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ztojajrv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.daria6918.cn/Article/details/gt2ofidcdtl.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yuanzhike.top/Article/details/gt2oztstopu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wtlekrgo.html

[D11] 反转数组
来源：http://dali.ybcxt.top/Article/details/gt2rymjttfa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shuidangran.top/Article/details/gt2wmnmxvyu.html

PHP:  array_reverse($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2zqjmheoh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cashguo.top/Article/details/gt2qaowuqnw.html

TS:   [...arr].reverse();
来源：http://dali.zhengqikj.top/Article/details/gt2pjfitqqw.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gt2euedrbfj.html

Go:   slices.Reverse(arr)
来源：http://dali.cheryme.top/Article/details/gt2wgugiwtr.html

Ruby: arr.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2dskdkwmn.html

C#:   list.Reverse();
来源：http://dali.cashguo.top/Article/details/gt2zumrqvtk.html

[D12] 查找元素下标
来源：http://dali.sufxvd.cn/Article/details/gt2wqjpydjt.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gt2rlatqgwt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shzxlz.cn/Article/details/gt2fdjtjpvb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2eyllcfou.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gt2koznnjhz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ehwqpu.com/Article/details/gt2larnjqnv.html

Go:   slices.Index(arr, x)
来源：http://dali.aibaodan.cn/Article/details/gt2mcqyvqiw.html

Ruby: arr.index(x)
来源：http://dali.xuanzx.com/Article/details/gt2dgevbhjo.html

C#:   list.IndexOf(x);
来源：http://dali.xuetiantiany.cn/Article/details/gt2rvdyelqe.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenjidiqi.icu/Article/details/gt2xfxkkcyj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cheryme.top/Article/details/gt2wuxlllhg.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2owilsyls.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gt2eabebsng.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gt2zousknnd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.redwolf501.top/Article/details/gt2cwbpphzg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gt2pcpyrmxa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.kuanghao11.cn/Article/details/gt2cbvcsiri.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yongpay.top/Article/details/gt2subbidrp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.feifeiyinyue.top/Article/details/gt2zhkyvefx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guowangkeji.top/Article/details/gt2ouzcninw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2barvshfq.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gt2pmhbtkea.html

TS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gt2ozlngeaz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daria6918.cn/Article/details/gt2vyvacdoy.html

Go:   // 手写循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rvinszvi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2ywhqycgc.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2wetsojag.html

[D15] 去重
来源：http://dali.birdmap.top/Article/details/gt2hwefoqkm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gt2yhtdbyfr.html

PHP:  array_unique($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dapoxwur.html

JS:   [...new Set(arr)]
来源：http://dali.hammf.cn/Article/details/gt2lseuxkzd.html

TS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gt2pldusrvg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.aibaodan.cn/Article/details/gt2swsrytbo.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.andypj.xyz/Article/details/gt2fzvhwcba.html

Ruby: arr.uniq
来源：http://dali.aibaodan.cn/Article/details/gt2ovbrxbnp.html

C#:   list.Distinct().ToList()
来源：http://dali.gaohongyu789.top/Article/details/gt2irlpmsju.html

[D16] 求和与平均值
来源：http://dali.tianlin.xyz/Article/details/gt2etyfwpac.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2xercttyr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2owtwvost.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gt2tktckbta.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2kbsospkn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.smart0.xyz/Article/details/gt2tqioizni.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gt2dnobhuqs.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fengsongda.top/Article/details/gt2xhztwwme.html

C#:   list.Sum();  list.Average()
来源：http://dali.fzhhl.top/Article/details/gt2tbgabbds.html

[D17] 最大值与最小值
来源：http://dali.chenlongwang.top/Article/details/gt2qaeryycp.html

Py:   max(arr);  min(arr)
来源：http://dali.yj202588.top/Article/details/gt2shhkbuzs.html

PHP:  max($arr);  min($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2nssesldv.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cheryme.top/Article/details/gt2fqomvewy.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gt2bmvtforf.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gogol.net.cn/Article/details/gt2hpujaylk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xuthzeid.html

Ruby: arr.max;  arr.min
来源：http://dali.daria6918.cn/Article/details/gt2recmgbnu.html

C#:   list.Max();  list.Min()
来源：http://dali.cdnleiting.top/Article/details/gt2upwohhhm.html

[D18] 扁平化嵌套数组
来源：http://dali.guowangkeji.top/Article/details/gt2kpzqokgu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.andypj.xyz/Article/details/gt2yzaqjxvy.html

PHP:  array_merge(...$nested);
来源：http://dali.tanke756.top/Article/details/gt2ssdbxeya.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.snrcjt.cn/Article/details/gt2zbmejlxp.html

TS:   nested.flat();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zybpveqs.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.nanxinkj.top/Article/details/gt2vbumaxvi.html

Go:   // 手写双层循环
来源：http://dali.gotoacloud.top/Article/details/gt2qlfpdrrl.html

Ruby: nested.flatten
来源：http://dali.tanke756.top/Article/details/gt2dsnzacho.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gotoacloud.top/Article/details/gt2wjidfpem.html

[D19] 按字段分组
来源：http://dali.yangfankeji.com/Article/details/gt2qeneoemd.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yuxming.cn/Article/details/gt2jxjzmhxc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.chenjidiqi.icu/Article/details/gt2ejzlhpuj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.316326.xyz/Article/details/gt2ezvcrtso.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.gaohongyu789.top/Article/details/gt2oiafuubj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yanxiufei.cn/Article/details/gt2bgexrbts.html

Go:   // 手写 map[string][]T
来源：http://dali.pengpengdd.cyou/Article/details/gt2hkytdjal.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gogol.net.cn/Article/details/gt2xsrhlwew.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.sufxvd.cn/Article/details/gt2lnqodcob.html

[D20] 统计每个元素出现次数
来源：http://dali.zhijiandao.cn/Article/details/gt2pxmgwknw.html

Py:   Counter(arr)
来源：http://dali.bjfxy.top/Article/details/gt2gsvjsxej.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gt2fhhocfou.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gt2vjryghwh.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gt2tjnznjfd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hysaishi.cn/Article/details/gt2woayjhho.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gt2azuismyw.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gt2aiaoiwra.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gt2fwfitfix.html

[D21] 判断是否包含某元素
来源：http://dali.pengpengdd.cyou/Article/details/gt2nbhxjcku.html

Py:   x in arr
来源：http://dali.ppjwa.cn/Article/details/gt2ztwppejh.html

PHP:  in_array($x, $arr, true);
来源：http://dali.meibo888.top/Article/details/gt2qydjmzrr.html

JS:   arr.includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jvbkhwjn.html

TS:   arr.includes(x)
来源：http://dali.ybcxt.top/Article/details/gt2bmgoahre.html

Java: list.contains(x)
来源：http://dali.shuidangran.top/Article/details/gt2kpxlalcq.html

Go:   slices.Contains(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2tjhjmkuz.html

Ruby: arr.include?(x)
来源：http://dali.hnqzz.top/Article/details/gt2sjrtkrld.html

C#:   list.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gt2xkxkfozm.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ybcxt.top/Article/details/gt2hlwpxwom.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.xylfe.cn/Article/details/gt2tyavzifj.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.yangfankeji.com/Article/details/gt2atiqyqri.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.c1oappe.top/Article/details/gt2oxesrlcm.html

TS:   [...arr];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rqdcpwko.html

Java: new ArrayList<>(list);
来源：http://dali.bjfxy.top/Article/details/gt2nurcpnxb.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.gotoacloud.top/Article/details/gt2xymxaocc.html

Ruby: arr.dup;  arr.clone
来源：http://dali.gzhubu.top/Article/details/gt2etusrjlf.html

C#:   new List<int>(list);
来源：http://dali.jinqigfzy.top/Article/details/gt2ffthhmms.html

[D23] reduce 累积计算
来源：http://dali.zhoulong.xyz/Article/details/gt2mijiyoib.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.ydzc1.top/Article/details/gt2kpmucqkr.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.xylfe.cn/Article/details/gt2duvwzomm.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2qhroollh.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fzkldext.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.andypj.xyz/Article/details/gt2lxlogqbq.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gt2rcruqlyt.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.hammf.cn/Article/details/gt2gxrppxkb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.hysaishi.cn/Article/details/gt2ajgnmcum.html

[D24] 字典 / Map 基本操作
来源：http://dali.nwbrower.top/Article/details/gt2lagbmiwp.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sufxvd.cn/Article/details/gt2tmarebwu.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.jinqigufen.top/Article/details/gt2mjwxewab.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.yueranfly.top/Article/details/gt2jrgrwsti.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2ebzmuxob.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.yuanzhike.top/Article/details/gt2rsovfwkl.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.iojbl.cn/Article/details/gt2ybyijxlk.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.dashuyun.cn/Article/details/gt2rgehldpn.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.zhoulong.xyz/Article/details/gt2dwacbhoz.html

[D25] Set 集合去重与交并差
来源：http://dali.cqqwz.cn/Article/details/gt2tmxyvkqs.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.zhixingplan.top/Article/details/gt2iddvtrvk.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nanxuanxn.top/Article/details/gt2lguqtykj.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.xziqi.cn/Article/details/gt2elzftumg.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.smart0.xyz/Article/details/gt2cousyfwm.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.cucudq.cn/Article/details/gt2zsvdifyy.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.zhengqikj.top/Article/details/gt2tpgnbikf.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.zhengqikj.top/Article/details/gt2tiwnoevo.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhengqikj.top/Article/details/gt2otaunyoa.html

[D26] 数组转字符串
来源：http://dali.guannengcc.top/Article/details/gt2lyhogozl.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jrtwjvjo.html

PHP:  implode(", ", $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2qxwjwdpr.html

JS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2cahzbbol.html

TS:   arr.join(", ")
来源：http://dali.tian-w.cn/Article/details/gt2odtymnlc.html

Java: String.join(", ", list)
来源：http://dali.guannengcc.top/Article/details/gt2esyhaopk.html

Go:   strings.Join(strs, ", ")
来源：http://dali.hysaishi.cn/Article/details/gt2udadcvbp.html

Ruby: arr.join(", ")
来源：http://dali.yuanzhike.top/Article/details/gt2qqcfhpng.html

C#:   string.Join(", ", list)
来源：http://dali.hnxiangtu.top/Article/details/gt2dxbkkugs.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2akeczgiq.html

E. 字符串处理
来源：http://dali.xylfe.cn/Article/details/gt2iokczcmg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2haizpwdk.html

[E01] 拼接字符串
来源：http://dali.yongpay.top/Article/details/gt2zcyoxnsm.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iijcpyqt.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.smart0.xyz/Article/details/gt2ezrljifx.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fwceinmv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gt2pdbhgiuf.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.xinyue.icu/Article/details/gt2lefcpupj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2fbzlsfrl.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.jinqigfzy.top/Article/details/gt2yerplvio.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.316326.xyz/Article/details/gt2wcvuxpwe.html

[E02] 重复字符串
来源：http://dali.andypj.xyz/Article/details/gt2yvgrhufz.html

Py:   "ab" * 3
来源：http://dali.cheryme.top/Article/details/gt2snrhzbzz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vcxoambf.html

JS:   "ab".repeat(3)
来源：http://dali.wangdashe.top/Article/details/gt2hzxfeuoq.html

TS:   "ab".repeat(3)
来源：http://dali.gogol.net.cn/Article/details/gt2mgcwcvea.html

Java: "ab".repeat(3)
来源：http://dali.havefunace.top/Article/details/gt2kossjxlk.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.meibo888.top/Article/details/gt2qxynpzoq.html

Ruby: "ab" * 3
来源：http://dali.xuetiantiany.cn/Article/details/gt2fugubyot.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.chenlongwang.top/Article/details/gt2vfxxosjx.html

[E03] 截取子串
来源：http://dali.guannengcc.top/Article/details/gt2sqfupunq.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.jinqigufen.top/Article/details/gt2azsptugm.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.redwolf501.top/Article/details/gt2xrkzbqfw.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.bjfxy.top/Article/details/gt2ogcqdths.html

TS:   s.slice(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gt2edllqfcr.html

Java: s.substring(1, 4)
来源：http://dali.zycfv.cn/Article/details/gt2yrxxjtpo.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.hnxiangtu.top/Article/details/gt2uwktzfsd.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.feifeiyinyue.top/Article/details/gt2aanpsrst.html

C#:   s.Substring(1, 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2xfryfwho.html

[E04] 查找子串位置
来源：http://dali.sufxvd.cn/Article/details/gt2ydeeewbj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.tianlin.xyz/Article/details/gt2jyzbjwvg.html

PHP:  strpos($s, "x");
来源：http://dali.smart0.xyz/Article/details/gt2ifqgdrey.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mtrbzeau.html

TS:   s.indexOf("x")
来源：http://dali.smart0.xyz/Article/details/gt2lrkerpds.html

Java: s.indexOf("x")
来源：http://dali.gotoacloud.top/Article/details/gt2rftvbexv.html


<!-- 参考信息 -->