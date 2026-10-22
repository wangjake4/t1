代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.birdmap.top/Article/details/gt2yrtqmonl.html

[C15] 解构 / 展开参数
来源：http://dali.yueranfly.top/Article/details/gt2kwkhgygf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gt2qwwlqldy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xylfe.cn/Article/details/gt2jqkjvcww.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jiqnsqgu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.andypj.xyz/Article/details/gt2kvjpmckh.html

Java: // 无解构
来源：http://dali.jianghu66.top/Article/details/gt2twmsuupw.html

Go:   // 无解构
来源：http://dali.gotoacloud.top/Article/details/gt2grlszqnc.html

Ruby: a, b = pair
来源：http://dali.xylfe.cn/Article/details/gt2ajnqqbzq.html

C#:   var (a, b) = pair;
来源：http://dali.yuanzhike.top/Article/details/gt2myaebzrd.html

[C16] 函数 / 方法重载
来源：http://dali.quarkkingdee.top/Article/details/gt2faooqcwu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gt2beqxyenu.html

PHP:  // 无重载
来源：http://dali.xinyue.icu/Article/details/gt2nxbxikgy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258888.top/Article/details/gt2kbxrxcnq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.smart0.xyz/Article/details/gt2byhfxall.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gt2zlemoknx.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gt2faehxulb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnqzz.top/Article/details/gt2ohoclekz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xylfe.cn/Article/details/gt2sypucemm.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2njcqhien.html

D. 数组 / 列表 / 集合
来源：http://dali.gaohongyu789.top/Article/details/gt2boqtmyxl.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2znsxvddi.html

[D01] 创建数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gt2hydidxgs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yangfankeji.com/Article/details/gt2ffsiiuqh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2grceajdl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gt2yarxntmb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bphkqvbi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jiagoushi.top/Article/details/gt2pciuepvc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258888.top/Article/details/gt2gqrweboy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fengsongda.top/Article/details/gt2zfakgzha.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuxming.cn/Article/details/gt2znlcazun.html

[D02] 追加元素到末尾
来源：http://dali.cheryme.top/Article/details/gt2nshmmjyx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangshuangyany.cn/Article/details/gt2acsyrakz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fengsongda.top/Article/details/gt2fubrrqtp.html

JS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2calatjtf.html

TS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2rcutumxn.html

Java: list.add(4);
来源：http://dali.haohaochexian.top/Article/details/gt2unajzcbh.html

Go:   arr = append(arr, 4)
来源：http://dali.cucudq.cn/Article/details/gt2pblrknfy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.iojbl.cn/Article/details/gt2gyeghqzf.html

C#:   list.Add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2eecmzopi.html

[D03] 在指定位置插入元素
来源：http://dali.chenzaomai.com/Article/details/gt2xpsgdkva.html

Py:   arr.insert(0, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2gjczjbwf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gt2fefwswyn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cqqwz.cn/Article/details/gt2sesmwibd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pnftewuw.html

Java: list.add(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2ufirraqw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.smart0.xyz/Article/details/gt2jraaziek.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aibaodan.cn/Article/details/gt2aujcqzbm.html

C#:   list.Insert(0, 0);
来源：http://dali.xylfe.cn/Article/details/gt2abkgodcs.html

[D04] 删除元素
来源：http://dali.gotoacloud.top/Article/details/gt2ljveaeyl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.svipenyu.cn/Article/details/gt2mbwnooqp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2hczeeulb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cashguo.top/Article/details/gt2npvlzadh.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2ebrkmbch.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tian-w.cn/Article/details/gt2eneenbuq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daria6918.cn/Article/details/gt2qsnpdjzf.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sjwsoezu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gsbwcuco.html

[D05] 访问与修改元素
来源：http://dali.snrcjt.cn/Article/details/gt2syigzlhz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gt2evlpddxo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gt2ziubvpbb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gt2hieijgvy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aizwys.cn/Article/details/gt2rybkcoap.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gtfookeg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gt2yureejas.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gt2igozyyyj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iqcoagso.html

[D06] 数组长度
来源：http://dali.aibaodan.cn/Article/details/gt2ngbakqhl.html

Py:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gsjojeou.html

PHP:  count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qrmlbjhm.html

JS:   arr.length
来源：http://dali.meibo888.top/Article/details/gt2hxmohhev.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvkgbtg.html

Java: list.size();
来源：http://dali.shzxlz.cn/Article/details/gt2jsxseoex.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gt2lyxjntcu.html

Ruby: arr.length; arr.size
来源：http://dali.andypj.xyz/Article/details/gt2ydnbeccr.html

C#:   list.Count;
来源：http://dali.yueranfly.top/Article/details/gt2mktyjlyn.html

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gt2fribscjb.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daxiang520.top/Article/details/gt2xbpttute.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2eyrgcavc.html

JS:   arr.slice(1, 4);
来源：http://dali.daria6918.cn/Article/details/gt2zolksawo.html

TS:   arr.slice(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gt2oyccvgib.html

Java: list.subList(1, 4);
来源：http://dali.iojbl.cn/Article/details/gt2apwodhip.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gt2kdolnyco.html

Ruby: arr[1, 3]
来源：http://dali.guannengcc.top/Article/details/gt2kohayqoq.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urcwlwkm.html

[D08] 合并两个数组
来源：http://dali.zdqjudy.top/Article/details/gt2cmzxophu.html

Py:   a + b;  a.extend(b)
来源：http://dali.quarkkingdee.top/Article/details/gt2fpfakagu.html

PHP:  array_merge($a, $b);
来源：http://dali.quarkkingdee.top/Article/details/gt2tiwnnpyu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhengqikj.top/Article/details/gt2zpjasaob.html

TS:   [...a, ...b];
来源：http://dali.yuanzhike.top/Article/details/gt2ewvkaexd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sysykeji.top/Article/details/gt2pnmubive.html

Go:   append(a, b...)
来源：http://dali.daria6918.cn/Article/details/gt2gjcmloxh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenjidiqi.icu/Article/details/gt2iovbrhtm.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2inbhjgmq.html

[D09] 排序（升序）
来源：http://dali.zhongyouzk.top/Article/details/gt2oowubqyv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gt2tdvpoxbq.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaauqso.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhongyouzk.top/Article/details/gt2lkqpvljm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aizwys.cn/Article/details/gt2oilgbkdb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.smart0.xyz/Article/details/gt2qqpurakn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2obpenwse.html

Ruby: arr.sort
来源：http://dali.yj20258.top/Article/details/gt2turwctil.html

C#:   list.Sort();
来源：http://dali.hysaishi.cn/Article/details/gt2ozepsxxh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhiwuduotai.top/Article/details/gt2jvzlkuqv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxinkj.top/Article/details/gt2abfoqkhj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gt2livfwekl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gt2nvsqskha.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gt2fumoocsq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dianchejie.cn/Article/details/gt2ixpvnyfg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuetiantiany.cn/Article/details/gt2zoujszxa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gt2rahgzwhu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sufxvd.cn/Article/details/gt2smvpfllk.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kihtiwaw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sysykeji.top/Article/details/gt2kloszlog.html

PHP:  array_reverse($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2bemdadmc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258.top/Article/details/gt2cjdxuyxu.html

TS:   [...arr].reverse();
来源：http://dali.gogol.net.cn/Article/details/gt2zwopjuzn.html

Java: Collections.reverse(list);
来源：http://dali.jinqigfzy.top/Article/details/gt2oyjywngs.html

Go:   slices.Reverse(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2ltypcifp.html

Ruby: arr.reverse
来源：http://dali.jiagoushi.top/Article/details/gt2facsfsdm.html

C#:   list.Reverse();
来源：http://dali.meibo888.top/Article/details/gt2qlnhlaeq.html

[D12] 查找元素下标
来源：http://dali.chenjidiqi.icu/Article/details/gt2zzzmwbru.html

Py:   arr.index(x);  x in arr
来源：http://dali.yanxiufei.cn/Article/details/gt2idyqgorq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2rrtbrtkv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gt2lsgaufhx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gt2rqubnijm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zycfv.cn/Article/details/gt2peqqwjpn.html

Go:   slices.Index(arr, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rpcswhkm.html

Ruby: arr.index(x)
来源：http://dali.jqgfzy.top/Article/details/gt2lwqxfusy.html

C#:   list.IndexOf(x);
来源：http://dali.yanxiufei.cn/Article/details/gt2ehinybqp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigufen.top/Article/details/gt2kvuvsxbl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aizwys.cn/Article/details/gt2kkfjlnst.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xjzavfvz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fuyftspw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinqigufen.top/Article/details/gt2pwdyflce.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.havefunace.top/Article/details/gt2znnqughx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aibaodan.cn/Article/details/gt2oalmspbd.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guowangkeji.top/Article/details/gt2wdfepjnv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2ktqhbzgq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sxryk.cn/Article/details/gt2ecarigpj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xziqi.cn/Article/details/gt2gxudebrs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.wangdashe.top/Article/details/gt2qatlghra.html

JS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gt2eotldadm.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2oqblmzxg.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nwbrower.top/Article/details/gt2ytnxxevk.html

Go:   // 手写循环
来源：http://dali.tian-w.cn/Article/details/gt2yizmcvwn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dtljrwxw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2dgzdbafq.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gt2glqpowuz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gt2iichohyv.html

PHP:  array_unique($arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2gdjxagmt.html

JS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2ksebimzs.html

TS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gt2jzmwufiw.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cdnleiting.top/Article/details/gt2haknagax.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gt2oeujujqc.html

Ruby: arr.uniq
来源：http://dali.yuanzhike.top/Article/details/gt2xloftajq.html

C#:   list.Distinct().ToList()
来源：http://dali.xinyue.icu/Article/details/gt2jodnutns.html

[D16] 求和与平均值
来源：http://dali.xylfe.cn/Article/details/gt2nvwzyywa.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2fppswstk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gecqfwul.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gt2ukmnpyky.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gt2xujksfah.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yanxiufei.cn/Article/details/gt2ckracjub.html

Go:   // 手写循环累加
来源：http://dali.hnqzz.top/Article/details/gt2jqnghanr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjnpgepg.html

C#:   list.Sum();  list.Average()
来源：http://dali.iojbl.cn/Article/details/gt2enfkguvt.html

[D17] 最大值与最小值
来源：http://dali.aizwys.cn/Article/details/gt2ckkijksk.html

Py:   max(arr);  min(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2gqhbvfqj.html

PHP:  max($arr);  min($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2pwhhrmgr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xylfe.cn/Article/details/gt2ltmgrfux.html

TS:   Math.max(...arr);
来源：http://dali.gzhubu.top/Article/details/gt2pkgtziak.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gt2teasnryn.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2ogmozyyz.html

Ruby: arr.max;  arr.min
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oowmbcvp.html

C#:   list.Max();  list.Min()
来源：http://dali.chenjidiqi.icu/Article/details/gt2swuhzoam.html

[D18] 扁平化嵌套数组
来源：http://dali.jiagoushi.top/Article/details/gt2rqcqhfkf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.fengsongda.top/Article/details/gt2grcaakfy.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigufen.top/Article/details/gt2juddamge.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lvkmzrzi.html

TS:   nested.flat();
来源：http://dali.cheryme.top/Article/details/gt2dixelrsd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2klhcitka.html

Go:   // 手写双层循环
来源：http://dali.cucudq.cn/Article/details/gt2bubjayfz.html

Ruby: nested.flatten
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2josraeoj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gt2rikkxiag.html

[D19] 按字段分组
来源：http://dali.zycfv.cn/Article/details/gt2gqggiqxv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.0kj1m.cn/Article/details/gt2bwsspjpc.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zdqjudy.top/Article/details/gt2vhjlxema.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yuanzhike.top/Article/details/gt2jhtzbdcy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnxiangtu.top/Article/details/gt2ksxlsfju.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yangfankeji.com/Article/details/gt2dlujvthk.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gt2kkscwiyk.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhyjpgib.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zycfv.cn/Article/details/gt2fxbtajtt.html

[D20] 统计每个元素出现次数
来源：http://dali.xuetiantiany.cn/Article/details/gt2gwmptmxb.html

Py:   Counter(arr)
来源：http://dali.ehwqpu.com/Article/details/gt2ohzaydge.html

PHP:  array_count_values($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2oqqqgztl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.ybcxt.top/Article/details/gt2rcfvbimw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gt2dosscpwx.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hysaishi.cn/Article/details/gt2lxgpsqzm.html

Go:   // 手写 map[T]int
来源：http://dali.cucudq.cn/Article/details/gt2stdxnmoq.html

Ruby: arr.tally
来源：http://dali.vqdsnc.cn/Article/details/gt2zravqlek.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.havefunace.top/Article/details/gt2ywzqiglo.html

[D21] 判断是否包含某元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dsiybpie.html

Py:   x in arr
来源：http://dali.andypj.xyz/Article/details/gt2lroisswo.html

PHP:  in_array($x, $arr, true);
来源：http://dali.ivvv.top/Article/details/gt2afhtclwr.html

JS:   arr.includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2dpmzowhf.html

TS:   arr.includes(x)
来源：http://dali.wangdashe.top/Article/details/gt2xiigvqwp.html

Java: list.contains(x)
来源：http://dali.chenlongwang.top/Article/details/gt2memhbzum.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gt2yqqmrgxa.html

Ruby: arr.include?(x)
来源：http://dali.daria6918.cn/Article/details/gt2sqykqlto.html

C#:   list.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2kingylvq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.xuanzx.com/Article/details/gt2dxuehlat.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2kdlksism.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rgclojhw.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2lccwdvoc.html

TS:   [...arr];
来源：http://dali.sufxvd.cn/Article/details/gt2xvoyizmb.html

Java: new ArrayList<>(list);
来源：http://dali.snrcjt.cn/Article/details/gt2mgyjpotz.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.iojbl.cn/Article/details/gt2vwfwzchs.html

Ruby: arr.dup;  arr.clone
来源：http://dali.havefunace.top/Article/details/gt2mkqijltw.html

C#:   new List<int>(list);
来源：http://dali.gzhubu.top/Article/details/gt2kdjpdrnd.html

[D23] reduce 累积计算
来源：http://dali.aibaodan.cn/Article/details/gt2iyzqcurl.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2kwenlfqc.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.shuidangran.top/Article/details/gt2hosbdofx.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ehwqpu.com/Article/details/gt2dwevapdb.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2cewxbqmx.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.jinqigufen.top/Article/details/gt2ilqgewug.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gt2jpqwvlnm.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.zycfv.cn/Article/details/gt2elbsnikr.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.yuxming.cn/Article/details/gt2azmgjbnn.html

[D24] 字典 / Map 基本操作
来源：http://dali.tian-w.cn/Article/details/gt2iokdkljo.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.cdnleiting.top/Article/details/gt2ozxsqkmt.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2pmluqepu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenzaomai.com/Article/details/gt2rjytousr.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2wosztfre.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.jqgfzy.top/Article/details/gt2hazcxkpg.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.hnxiangtu.top/Article/details/gt2lrhzhfbh.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.sysykeji.top/Article/details/gt2oushxrvh.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cashguo.top/Article/details/gt2ubncueni.html

[D25] Set 集合去重与交并差
来源：http://dali.zhoulong.xyz/Article/details/gt2qjppgntr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.daria6918.cn/Article/details/gt2nhioqtpc.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.nwbrower.top/Article/details/gt2xsyihrmf.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.fzhhl.top/Article/details/gt2ipnpwacx.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.mhx1999.top/Article/details/gt2gaahdwzn.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfoexbhv.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.cdnleiting.top/Article/details/gt2yxrpuvwz.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.bjfxy.top/Article/details/gt2ralexlim.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.sweek.top/Article/details/gt2gochlxyy.html

[D26] 数组转字符串
来源：http://dali.birdmap.top/Article/details/gt2tyvzbwbi.html

Py:   ", ".join(map(str, arr))
来源：http://dali.fengsongda.top/Article/details/gt2hlrbwdoc.html

PHP:  implode(", ", $arr);
来源：http://dali.fengsongda.top/Article/details/gt2luxxxgcs.html

JS:   arr.join(", ")
来源：http://dali.ehwqpu.com/Article/details/gt2cfpicdyh.html

TS:   arr.join(", ")
来源：http://dali.tanke756.top/Article/details/gt2ctgqkhjv.html

Java: String.join(", ", list)
来源：http://dali.ppjwa.cn/Article/details/gt2ddvaukxt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.xinyue.icu/Article/details/gt2ixjwbfjc.html

Ruby: arr.join(", ")
来源：http://dali.cdnleiting.top/Article/details/gt2oiwvthyo.html

C#:   string.Join(", ", list)
来源：http://dali.wangdashe.top/Article/details/gt2rqxayglj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2fwtcqsfx.html

E. 字符串处理
来源：http://dali.sxryk.cn/Article/details/gt2ononxlnt.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbwwsoku.html

[E01] 拼接字符串
来源：http://dali.yj20258.top/Article/details/gt2ejwfqdzq.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.havefunace.top/Article/details/gt2retlhhma.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2olbwcbnn.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.iojbl.cn/Article/details/gt2wowskcno.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xziqi.cn/Article/details/gt2tjoprlwb.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.chenlongwang.top/Article/details/gt2gxrtltoj.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.nanxuanxn.top/Article/details/gt2ryrenmfh.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.guowangkeji.top/Article/details/gt2lkawnkpq.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2qhnkenei.html

[E02] 重复字符串
来源：http://dali.birdmap.top/Article/details/gt2kjdxqexo.html

Py:   "ab" * 3
来源：http://dali.shzxlz.cn/Article/details/gt2actgeajz.html

PHP:  str_repeat("ab", 3);
来源：http://dali.yuxming.cn/Article/details/gt2uhrjgsmz.html

JS:   "ab".repeat(3)
来源：http://dali.birdmap.top/Article/details/gt2lzzetetk.html

TS:   "ab".repeat(3)
来源：http://dali.ybcxt.top/Article/details/gt2akcldhqr.html

Java: "ab".repeat(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dmyyubhl.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.dianchejie.cn/Article/details/gt2dgpdrbjf.html

Ruby: "ab" * 3
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yykuchnc.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.yangfankeji.com/Article/details/gt2ssnhxmge.html

[E03] 截取子串
来源：http://dali.gzhubu.top/Article/details/gt2hdkdufkf.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.dianchejie.cn/Article/details/gt2isiomvtr.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhoulong.xyz/Article/details/gt2dgoexcyo.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.jinqigufen.top/Article/details/gt2bcfcdtet.html

TS:   s.slice(1, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2npoubklj.html

Java: s.substring(1, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2tyvhqata.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gt2rlilhyge.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.chenlongwang.top/Article/details/gt2cudkajbd.html

C#:   s.Substring(1, 3)
来源：http://dali.vqdsnc.cn/Article/details/gt2miduafwa.html

[E04] 查找子串位置
来源：http://dali.redwolf501.top/Article/details/gt2eghyvnql.html

Py:   s.find("x");  s.index("x")
来源：http://dali.xuanzx.com/Article/details/gt2xlqouvaj.html

PHP:  strpos($s, "x");
来源：http://dali.hywenlv.cn/Article/details/gt2kiclfabo.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.gzhubu.top/Article/details/gt2hbdizjpx.html

TS:   s.indexOf("x")
来源：http://dali.ppjwa.cn/Article/details/gt2jrybtohw.html

Java: s.indexOf("x")
来源：http://dali.havefunace.top/Article/details/gt2qudxhfaq.html

Go:   strings.Index(s, "x")
来源：http://dali.gaohongyu789.top/Article/details/gt2btifsyib.html

Ruby: s.index("x")
来源：http://dali.zhiwuduotai.top/Article/details/gt2bpszerfw.html

C#:   s.IndexOf("x")
来源：http://dali.9152youxi.cn/Article/details/gt2eyfafhzh.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.gogol.net.cn/Article/details/gt2lfektlgy.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.yueranfly.top/Article/details/gt2vggnkiql.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yangfankeji.com/Article/details/gt2hxfvtgxd.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.xylfe.cn/Article/details/gt2hqlbwlgj.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yongpay.top/Article/details/gt2hbelgppi.html


<!-- 参考信息 -->