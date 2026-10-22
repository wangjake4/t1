代发 wailian999

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gt2zokadone.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhongyouzk.top/Article/details/gt2coxwesge.html

PHP:  // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gt2bbsruloj.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2dgkkdlan.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xylfe.cn/Article/details/gt2xtirwaot.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aizwys.cn/Article/details/gt2wptqmmnq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.iojbl.cn/Article/details/gt2zbtrzjhv.html

Ruby: # 无泛型
来源：http://dali.ydzc1.top/Article/details/gt2gtewrcvr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhiwuduotai.top/Article/details/gt2ybyrnvrf.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gt2zislfpzd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nwbrower.top/Article/details/gt2fleyeecj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lsjllwia.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gt2hczkwptf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenzaomai.com/Article/details/gt2wzztbbrh.html

Java: // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tzkucosb.html

Go:   // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ucrctoby.html

Ruby: a, b = pair
来源：http://dali.yuanzhike.top/Article/details/gt2qqdnbmip.html

C#:   var (a, b) = pair;
来源：http://dali.xylfe.cn/Article/details/gt2xcoyomga.html

[C16] 函数 / 方法重载
来源：http://dali.zhengqikj.top/Article/details/gt2kacwjcge.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenlongwang.top/Article/details/gt2ygdjhupo.html

PHP:  // 无重载
来源：http://dali.birdmap.top/Article/details/gt2vmvkjpbf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxuanxn.top/Article/details/gt2yfwhbonh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hammf.cn/Article/details/gt2xsixicwk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gt2cvdfaitj.html

Go:   // 无重载：用不同函数名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uedvazvz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2sssvwkpd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigufen.top/Article/details/gt2mngganys.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2itaeqcgu.html

D. 数组 / 列表 / 集合
来源：http://dali.hfpthk.cn/Article/details/gt2xhjleusn.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2usboexnz.html

[D01] 创建数组 / 列表
来源：http://dali.cheryme.top/Article/details/gt2wjykdavd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.0kj1m.cn/Article/details/gt2cblesyxh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sweek.top/Article/details/gt2lkvbpkna.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xinyue.icu/Article/details/gt2wstsowry.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ivvv.top/Article/details/gt2bpuchytx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cheryme.top/Article/details/gt2cqlzccnb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.9152youxi.cn/Article/details/gt2nubveiqv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhengqikj.top/Article/details/gt2fwyofola.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258.top/Article/details/gt2ivwfpeyc.html

[D02] 追加元素到末尾
来源：http://dali.guannengcc.top/Article/details/gt2fgdtqizi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ivvv.top/Article/details/gt2lpzdlldv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ivvv.top/Article/details/gt2bzqasael.html

JS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gt2ctusgrcv.html

TS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gt2qrihfkzh.html

Java: list.add(4);
来源：http://dali.cdnleiting.top/Article/details/gt2fwxfehki.html

Go:   arr = append(arr, 4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rdtgspkj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigfzy.top/Article/details/gt2anofismr.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gt2orgscrql.html

[D03] 在指定位置插入元素
来源：http://dali.yonumen.top/Article/details/gt2lxjesvyh.html

Py:   arr.insert(0, 0)
来源：http://dali.sxryk.cn/Article/details/gt2qnvwukks.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuanzx.com/Article/details/gt2lzjkmdan.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.quarkkingdee.top/Article/details/gt2znljvlte.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2cthtotcd.html

Java: list.add(0, 0);
来源：http://dali.zycfv.cn/Article/details/gt2hrjvibmy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xinyue.icu/Article/details/gt2wmkjmcmv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gzhubu.top/Article/details/gt2hflqfwtx.html

C#:   list.Insert(0, 0);
来源：http://dali.pycfn.com/Article/details/gt2vdvgyqth.html

[D04] 删除元素
来源：http://dali.sxryk.cn/Article/details/gt2qwagxlyi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.snrcjt.cn/Article/details/gt2zoqclsmk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aizwys.cn/Article/details/gt2dvadklxz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hongshengwenyu.top/Article/details/gt2bzrpslvm.html

TS:   arr.splice(0, 1);
来源：http://dali.hywenlv.cn/Article/details/gt2dskwjkvs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ekhnsukk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ppjwa.cn/Article/details/gt2nfgrxxrh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhixingplan.top/Article/details/gt2sjkrklyh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gogol.net.cn/Article/details/gt2wvdniemw.html

[D05] 访问与修改元素
来源：http://dali.smart0.xyz/Article/details/gt2hkwsbvfz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gt2cpliwtva.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cashguo.top/Article/details/gt2htqnlohu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gt2ndmtomaa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.iojbl.cn/Article/details/gt2wldzpukm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gotoacloud.top/Article/details/gt2kgkuowdq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gt2qmqmkzrp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gt2vjgflakr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gt2hmxnwnji.html

[D06] 数组长度
来源：http://dali.jianghu66.top/Article/details/gt2bqzlvhar.html

Py:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gt2hvfrprty.html

PHP:  count($arr);
来源：http://dali.xuanzx.com/Article/details/gt2bzlwhoev.html

JS:   arr.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmwhfije.html

TS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gt2jgjjaomq.html

Java: list.size();
来源：http://dali.havefunace.top/Article/details/gt2qrmaqbzp.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zbpwqaec.html

Ruby: arr.length; arr.size
来源：http://dali.sxryk.cn/Article/details/gt2efsmyjdr.html

C#:   list.Count;
来源：http://dali.zdqjudy.top/Article/details/gt2pcjrcpop.html

[D07] 切片 / 取子数组
来源：http://dali.chenlongwang.top/Article/details/gt2hlbrfmsr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sweek.top/Article/details/gt2wuxbncbn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xinyue.icu/Article/details/gt2aqofvikk.html

JS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gt2eanfeyuu.html

TS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2eylzjjog.html

Java: list.subList(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gt2gkcgfhwr.html

Go:   arr[1:4]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zjelkcwy.html

Ruby: arr[1, 3]
来源：http://dali.dianchejie.cn/Article/details/gt2ymudhnii.html

C#:   list.GetRange(1, 3);
来源：http://dali.xylfe.cn/Article/details/gt2gdcjnguj.html

[D08] 合并两个数组
来源：http://dali.nwbrower.top/Article/details/gt2zcnmszjj.html

Py:   a + b;  a.extend(b)
来源：http://dali.vqdsnc.cn/Article/details/gt2iggugpiy.html

PHP:  array_merge($a, $b);
来源：http://dali.nwbrower.top/Article/details/gt2blkneexd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.bjfxy.top/Article/details/gt2tlkboets.html

TS:   [...a, ...b];
来源：http://dali.xuanzx.com/Article/details/gt2wecxkcuc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2xwnovaqr.html

Go:   append(a, b...)
来源：http://dali.zycfv.cn/Article/details/gt2yxdfgdud.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yangfankeji.com/Article/details/gt2ivggnogy.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gt2ffgzyoqy.html

[D09] 排序（升序）
来源：http://dali.yonumen.top/Article/details/gt2ebgceqzk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.9152youxi.cn/Article/details/gt2rkhqrwqn.html

PHP:  sort($arr);
来源：http://dali.iojbl.cn/Article/details/gt2bryyowgc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.mhx1999.top/Article/details/gt2jkmtoxrq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yanxiufei.cn/Article/details/gt2feaadftk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nanxuanxn.top/Article/details/gt2gwthcwfq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj20258.top/Article/details/gt2ithritqc.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gt2ewssfqxz.html

C#:   list.Sort();
来源：http://dali.xinyue.icu/Article/details/gt2wzmjhovk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuetiantiany.cn/Article/details/gt2mswulkvw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.daria6918.cn/Article/details/gt2fqkngdtg.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vrwehwho.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gt2gbjdhjlp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gt2rwiehjqz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2myozatti.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigufen.top/Article/details/gt2graqfdtf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.fengsongda.top/Article/details/gt2wnwmmkee.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2upoczqqb.html

[D11] 反转数组
来源：http://dali.0kj1m.cn/Article/details/gt2dyemrohm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hywenlv.cn/Article/details/gt2sragefvh.html

PHP:  array_reverse($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2oedlanoc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pengpengdd.cyou/Article/details/gt2joqjzpac.html

TS:   [...arr].reverse();
来源：http://dali.daxiang520.top/Article/details/gt2jdjihwvq.html

Java: Collections.reverse(list);
来源：http://dali.ybcxt.top/Article/details/gt2bhtoogfd.html

Go:   slices.Reverse(arr)
来源：http://dali.cucudq.cn/Article/details/gt2ljscoyvx.html

Ruby: arr.reverse
来源：http://dali.yueranfly.top/Article/details/gt2rpqjdwzp.html

C#:   list.Reverse();
来源：http://dali.yvedp.cn/Article/details/gt2grxxpfdo.html

[D12] 查找元素下标
来源：http://dali.jlsjyb.cn/Article/details/gt2zvwgiiwx.html

Py:   arr.index(x);  x in arr
来源：http://dali.hywenlv.cn/Article/details/gt2dknorqkt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhixingplan.top/Article/details/gt2xcfaxdpd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gt2zokupgnq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ybwzvjws.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tanke756.top/Article/details/gt2tffrxnru.html

Go:   slices.Index(arr, x)
来源：http://dali.andypj.xyz/Article/details/gt2sahggfyp.html

Ruby: arr.index(x)
来源：http://dali.sxryk.cn/Article/details/gt2pjssaghy.html

C#:   list.IndexOf(x);
来源：http://dali.shuidangran.top/Article/details/gt2qwajggvk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ehwqpu.com/Article/details/gt2fnrkcpwy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xylfe.cn/Article/details/gt2onsbimmr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.wangdashe.top/Article/details/gt2fzdzadqx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbfgviwk.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2pmweojgo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2zrhiwjoi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ppjwa.cn/Article/details/gt2uplocdoq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.9152youxi.cn/Article/details/gt2yjlhnjhq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2svdzpwkq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gt2izwhhxcn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xinyue.icu/Article/details/gt2cuymurwk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.c1oappe.top/Article/details/gt2zustwdvg.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjkaoikh.html

TS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gt2wfeevzvt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gt2zktyceog.html

Go:   // 手写循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oexsevur.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj20258.top/Article/details/gt2vsxwpwjk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2uchzhfrl.html

[D15] 去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2horpyato.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gt2wxiqngfy.html

PHP:  array_unique($arr);
来源：http://dali.xylfe.cn/Article/details/gt2mmpkahan.html

JS:   [...new Set(arr)]
来源：http://dali.0kj1m.cn/Article/details/gt2zlotlppd.html

TS:   [...new Set(arr)]
来源：http://dali.tian-w.cn/Article/details/gt2fxbmifwj.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yanxiufei.cn/Article/details/gt2dnwakszh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mdqtydye.html

Ruby: arr.uniq
来源：http://dali.shuidangran.top/Article/details/gt2kfpohbdf.html

C#:   list.Distinct().ToList()
来源：http://dali.wangdashe.top/Article/details/gt2couvneah.html

[D16] 求和与平均值
来源：http://dali.yueranfly.top/Article/details/gt2lhwlwttx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2pucrbruu.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cashguo.top/Article/details/gt2iwuipouq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gt2hvlgjalo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gt2mmobheyx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gt2jjrrgaak.html

Go:   // 手写循环累加
来源：http://dali.nanxinkj.top/Article/details/gt2kgtdzxbq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dianchejie.cn/Article/details/gt2uxhywnvw.html

C#:   list.Sum();  list.Average()
来源：http://dali.tianlin.xyz/Article/details/gt2fxjksgon.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gt2mqjysgui.html

Py:   max(arr);  min(arr)
来源：http://dali.cashguo.top/Article/details/gt2kfkomgly.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2ftgygaan.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gt2oilzacrm.html

TS:   Math.max(...arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2pocrcalp.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sxryk.cn/Article/details/gt2kedljpuc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2monylikc.html

Ruby: arr.max;  arr.min
来源：http://dali.daxiang520.top/Article/details/gt2eqiwfbiq.html

C#:   list.Max();  list.Min()
来源：http://dali.wangdashe.top/Article/details/gt2abzvavkt.html

[D18] 扁平化嵌套数组
来源：http://dali.c1oappe.top/Article/details/gt2baxjwyug.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gt2hvekgiyj.html

PHP:  array_merge(...$nested);
来源：http://dali.dashuyun.cn/Article/details/gt2nmqafhuz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xuanzx.com/Article/details/gt2fpfdbihs.html

TS:   nested.flat();
来源：http://dali.shuidangran.top/Article/details/gt2ghtcktqe.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sxryk.cn/Article/details/gt2gqjpeuqh.html

Go:   // 手写双层循环
来源：http://dali.ydzc1.top/Article/details/gt2fdndivvk.html

Ruby: nested.flatten
来源：http://dali.gaohongyu789.top/Article/details/gt2qawbopfz.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2gwshepta.html

[D19] 按字段分组
来源：http://dali.yj20258.top/Article/details/gt2iotsmmcm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.daria6918.cn/Article/details/gt2djatncom.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.fzhhl.top/Article/details/gt2bfxkcdsq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gt2ojubhufz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.iojbl.cn/Article/details/gt2fuysahjb.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.gotoacloud.top/Article/details/gt2jzjfppqo.html

Go:   // 手写 map[string][]T
来源：http://dali.hnqzz.top/Article/details/gt2apycjqbu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tian-w.cn/Article/details/gt2qhjkjgoj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.yanxiufei.cn/Article/details/gt2ndeyplvo.html

[D20] 统计每个元素出现次数
来源：http://dali.jinqigufen.top/Article/details/gt2ubhtqdqk.html

Py:   Counter(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2kghhavva.html

PHP:  array_count_values($arr);
来源：http://dali.xinyue.icu/Article/details/gt2rrgbywud.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.haohaochexian.top/Article/details/gt2vkrsucgz.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.c1oappe.top/Article/details/gt2clgpooeh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shangyingyoupin.top/Article/details/gt2egqzmogj.html

Go:   // 手写 map[T]int
来源：http://dali.hywenlv.cn/Article/details/gt2eqmdydtr.html

Ruby: arr.tally
来源：http://dali.yuxming.cn/Article/details/gt2pxbvcvpe.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.nanxinkj.top/Article/details/gt2ksezhgdl.html

[D21] 判断是否包含某元素
来源：http://dali.iojbl.cn/Article/details/gt2aoqybggt.html

Py:   x in arr
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kpcssoaz.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zdqjudy.top/Article/details/gt2tbjbrpwp.html

JS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2pefnoeyb.html

TS:   arr.includes(x)
来源：http://dali.mhx1999.top/Article/details/gt2ngmphlzj.html

Java: list.contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2hufpflpx.html

Go:   slices.Contains(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rcmoihnd.html

Ruby: arr.include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2byhzlvtq.html

C#:   list.Contains(x)
来源：http://dali.c1oappe.top/Article/details/gt2duzsusgi.html

[D22] 复制数组（避免共享引用）
来源：http://dali.jqgfzy.top/Article/details/gt2jfegqkix.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzxaumfp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shangyingyoupin.top/Article/details/gt2pkjwmdjy.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.mhx1999.top/Article/details/gt2wrigaqpw.html

TS:   [...arr];
来源：http://dali.xuetiantiany.cn/Article/details/gt2kabynkyr.html

Java: new ArrayList<>(list);
来源：http://dali.cucudq.cn/Article/details/gt2bumywwpq.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ldlsltwi.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yuanzhike.top/Article/details/gt2mbceckdv.html

C#:   new List<int>(list);
来源：http://dali.hnqzz.top/Article/details/gt2pkowpelj.html

[D23] reduce 累积计算
来源：http://dali.zhijiandao.cn/Article/details/gt2qjttnanb.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.birdmap.top/Article/details/gt2eoyvgvml.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2qopkmmpa.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.sysykeji.top/Article/details/gt2ftswwabg.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxuayxch.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggvkrhsr.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gt2fsoiieuc.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigufen.top/Article/details/gt2gsqeddwb.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.bjfxy.top/Article/details/gt2aajtqhqn.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenjidiqi.icu/Article/details/gt2tuimkvfa.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.jqgufenzy.top/Article/details/gt2pnluvade.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.zhixingplan.top/Article/details/gt2bvyyjqcr.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.chenzaomai.com/Article/details/gt2arbrkeok.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2pyxgarae.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.gaohongyu789.top/Article/details/gt2mycpkwfv.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.zycfv.cn/Article/details/gt2efnwgeza.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.daria6918.cn/Article/details/gt2tzixkgiu.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.tianlin.xyz/Article/details/gt2ccbviuch.html

[D25] Set 集合去重与交并差
来源：http://dali.jianghu66.top/Article/details/gt2dcvqqeyv.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.cucudq.cn/Article/details/gt2axxouvpf.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lididzfy.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.cheryme.top/Article/details/gt2nkwcyosz.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhongyouzk.top/Article/details/gt2nlnqurdb.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.andypj.xyz/Article/details/gt2nyotoypr.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.nanxinkj.top/Article/details/gt2ldxapyrh.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.yvedp.cn/Article/details/gt2ltfifdxd.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.yuanzhike.top/Article/details/gt2rvpypgsc.html

[D26] 数组转字符串
来源：http://dali.aibaodan.cn/Article/details/gt2uzuiigix.html

Py:   ", ".join(map(str, arr))
来源：http://dali.yuxming.cn/Article/details/gt2ckvgvkxg.html

PHP:  implode(", ", $arr);
来源：http://dali.birdmap.top/Article/details/gt2wtreusxr.html

JS:   arr.join(", ")
来源：http://dali.hfpthk.cn/Article/details/gt2mdodkqgx.html

TS:   arr.join(", ")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jcryvhro.html

Java: String.join(", ", list)
来源：http://dali.yueranfly.top/Article/details/gt2fvgiieui.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jqgufenzy.top/Article/details/gt2rxzvtycg.html

Ruby: arr.join(", ")
来源：http://dali.jyoumei.cn/Article/details/gt2fxyoquqc.html

C#:   string.Join(", ", list)
来源：http://dali.zhixingplan.top/Article/details/gt2fdktnriq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekesnign.html

E. 字符串处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2dnukkbnl.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2vcbxarhx.html

[E01] 拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gt2uozwkdgg.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.tianlin.xyz/Article/details/gt2pmbvnphn.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.zhongyouzk.top/Article/details/gt2wquahcsg.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.dashuyun.cn/Article/details/gt2wdkwgryv.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.hfpthk.cn/Article/details/gt2hcdvdsem.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.tanke756.top/Article/details/gt2xcmgzjxc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.andypj.xyz/Article/details/gt2qyeldmbu.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.xylfe.cn/Article/details/gt2ihpdujmk.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yuxming.cn/Article/details/gt2bzjkqyhe.html

[E02] 重复字符串
来源：http://dali.jlsjyb.cn/Article/details/gt2efzmvsjr.html

Py:   "ab" * 3
来源：http://dali.cashguo.top/Article/details/gt2uwpasmoe.html

PHP:  str_repeat("ab", 3);
来源：http://dali.fengsongda.top/Article/details/gt2kpzqjbks.html

JS:   "ab".repeat(3)
来源：http://dali.iojbl.cn/Article/details/gt2qccbmuvu.html

TS:   "ab".repeat(3)
来源：http://dali.ivvv.top/Article/details/gt2izygzqyn.html

Java: "ab".repeat(3)
来源：http://dali.shzxlz.cn/Article/details/gt2qqwmlpmz.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.jinqigufen.top/Article/details/gt2eqpsorml.html

Ruby: "ab" * 3
来源：http://dali.cheryme.top/Article/details/gt2cbqnhftu.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.wangshuangyany.cn/Article/details/gt2cbkrjqut.html

[E03] 截取子串
来源：http://dali.smart0.xyz/Article/details/gt2kaxybbdh.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.c1oappe.top/Article/details/gt2otmsextq.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.tanke756.top/Article/details/gt2qhtbndak.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.wangdashe.top/Article/details/gt2zneigwvf.html

TS:   s.slice(1, 4)
来源：http://dali.aibaodan.cn/Article/details/gt2wawqhyrh.html

Java: s.substring(1, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dlbmjcqr.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.cheryme.top/Article/details/gt2cklmsdmq.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.shangyingyoupin.top/Article/details/gt2zouvbsbd.html

C#:   s.Substring(1, 3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2blaygdvj.html

[E04] 查找子串位置
来源：http://dali.meibo888.top/Article/details/gt2qqhhpyqo.html

Py:   s.find("x");  s.index("x")
来源：http://dali.gogol.net.cn/Article/details/gt2jepkaavk.html

PHP:  strpos($s, "x");
来源：http://dali.hnqzz.top/Article/details/gt2lwxexhjk.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.dianchejie.cn/Article/details/gt2rypqomhu.html

TS:   s.indexOf("x")
来源：http://dali.yuxming.cn/Article/details/gt2vslznqiq.html

Java: s.indexOf("x")
来源：http://dali.cheryme.top/Article/details/gt2iwygzmsf.html


<!-- 参考信息 -->