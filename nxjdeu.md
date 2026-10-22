代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hammf.cn/Article/details/gt2whglkkta.html

[C15] 解构 / 展开参数
来源：http://dali.daria6918.cn/Article/details/gt2mygobsvb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cdnleiting.top/Article/details/gt2gqbeprwg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yvedp.cn/Article/details/gt2tzriedkx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gt2mmugfsun.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2koqfnhnk.html

Java: // 无解构
来源：http://dali.0kj1m.cn/Article/details/gt2scninqty.html

Go:   // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2klxkrsfs.html

Ruby: a, b = pair
来源：http://dali.chenlongwang.top/Article/details/gt2qlcoshky.html

C#:   var (a, b) = pair;
来源：http://dali.sysykeji.top/Article/details/gt2kzpxwtae.html

[C16] 函数 / 方法重载
来源：http://dali.andypj.xyz/Article/details/gt2emgxoueg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gt2uthyspth.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gt2gbzyzjih.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dianchejie.cn/Article/details/gt2xdnbgxil.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gt2pgahzrzw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuxming.cn/Article/details/gt2ihnlmuhz.html

Go:   // 无重载：用不同函数名
来源：http://dali.birdmap.top/Article/details/gt2msbbngwm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xylfe.cn/Article/details/gt2kchjpilg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.andypj.xyz/Article/details/gt2vgdakymm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2nixkqyir.html

D. 数组 / 列表 / 集合
来源：http://dali.daxiang520.top/Article/details/gt2kyolnqvj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fjjiizph.html

[D01] 创建数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gt2lqhpcyab.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hysaishi.cn/Article/details/gt2addllkxk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yueranfly.top/Article/details/gt2fjnieqoo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuanzhike.top/Article/details/gt2uizjquyb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daria6918.cn/Article/details/gt2orqbkczg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yonumen.top/Article/details/gt2fmiazios.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gt2vrfilups.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zycfv.cn/Article/details/gt2idlodhmn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sysykeji.top/Article/details/gt2wfymqzkw.html

[D02] 追加元素到末尾
来源：http://dali.svipenyu.cn/Article/details/gt2botrycds.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuanzhike.top/Article/details/gt2ckkphftz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigfzy.top/Article/details/gt2tjygvjel.html

JS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2uemyrhnr.html

TS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gt2yjvhczoj.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gt2tcnvdxkb.html

Go:   arr = append(arr, 4)
来源：http://dali.snrcjt.cn/Article/details/gt2zjkpprne.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nwbrower.top/Article/details/gt2qrjxrqjt.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gt2xciiunrv.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2otouuwpl.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gt2bhmjbjss.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ybcxt.top/Article/details/gt2hskmizqx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj202588.top/Article/details/gt2bbegrzcf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.316326.xyz/Article/details/gt2xmaxlpcx.html

Java: list.add(0, 0);
来源：http://dali.cheryme.top/Article/details/gt2iptqcwkk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pycfn.com/Article/details/gt2nzyyxnsl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gt2tzoqqnye.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2qgcbakyw.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gt2jlaihggy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2vjfcfgun.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2bgebwyoj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.vqdsnc.cn/Article/details/gt2djtkqvts.html

TS:   arr.splice(0, 1);
来源：http://dali.fengsongda.top/Article/details/gt2bkhfqofy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hywenlv.cn/Article/details/gt2zrabpuok.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ppjwa.cn/Article/details/gt2wdvetxvx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258.top/Article/details/gt2hafihprb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gt2knkpsawf.html

[D05] 访问与修改元素
来源：http://dali.aizwys.cn/Article/details/gt2qlecevfq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gt2oitaadfj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2xmtcqbzi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vqrdugmp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ybcxt.top/Article/details/gt2ysdczrsk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxuanxn.top/Article/details/gt2zzepzcju.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gt2llttgmqu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gt2ibwkwzsp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gt2vhslqhmq.html

[D06] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2obcmxjde.html

Py:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2kyghgehm.html

PHP:  count($arr);
来源：http://dali.andypj.xyz/Article/details/gt2pelyuotg.html

JS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gt2edkzbzyp.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gt2ilohhqnp.html

Java: list.size();
来源：http://dali.feifeiyinyue.top/Article/details/gt2pjhtinwr.html

Go:   len(arr)
来源：http://dali.yonumen.top/Article/details/gt2asdpuvio.html

Ruby: arr.length; arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yijahyhz.html

C#:   list.Count;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rgnoikwk.html

[D07] 切片 / 取子数组
来源：http://dali.birdmap.top/Article/details/gt2vxiccnuw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yj20258888.top/Article/details/gt2cyzcprlq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xylfe.cn/Article/details/gt2rrxyfmip.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gt2ilzngssh.html

TS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gt2yiajvewd.html

Java: list.subList(1, 4);
来源：http://dali.sweek.top/Article/details/gt2ruvkmizb.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gt2hdsqayki.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rezkbtll.html

C#:   list.GetRange(1, 3);
来源：http://dali.fengsongda.top/Article/details/gt2mjogkgxd.html

[D08] 合并两个数组
来源：http://dali.xuetiantiany.cn/Article/details/gt2lxxcdzfl.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxuanxn.top/Article/details/gt2ghegcjjg.html

PHP:  array_merge($a, $b);
来源：http://dali.jinqigufen.top/Article/details/gt2aisyqqnb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigufen.top/Article/details/gt2dxhcfblv.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2izkzugqg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.andypj.xyz/Article/details/gt2ztpjoioi.html

Go:   append(a, b...)
来源：http://dali.yangfankeji.com/Article/details/gt2ayklsovr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gt2cqdrying.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258.top/Article/details/gt2iemhlsji.html

[D09] 排序（升序）
来源：http://dali.sxryk.cn/Article/details/gt2korplnnz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gt2niyhafab.html

PHP:  sort($arr);
来源：http://dali.birdmap.top/Article/details/gt2penxvfkz.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ydzc1.top/Article/details/gt2nyddtfft.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.aibaodan.cn/Article/details/gt2llptxcuq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aizwys.cn/Article/details/gt2hrsgggsu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ybcxt.top/Article/details/gt2iogcubbr.html

Ruby: arr.sort
来源：http://dali.fengsongda.top/Article/details/gt2xfehobui.html

C#:   list.Sort();
来源：http://dali.yuanzhike.top/Article/details/gt2cqrludfh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yangfankeji.com/Article/details/gt2lwqilscu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gt2nlfmmpqk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gt2gfqaidyu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gt2ulrtlzrj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gt2hibjleuu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zycfv.cn/Article/details/gt2tcbquapx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cashguo.top/Article/details/gt2qcjedvzk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gt2jqxbrkwe.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhiwuduotai.top/Article/details/gt2spsbiibk.html

[D11] 反转数组
来源：http://dali.iojbl.cn/Article/details/gt2wiqnqher.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daria6918.cn/Article/details/gt2chhgdetf.html

PHP:  array_reverse($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pzhyygdu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sweek.top/Article/details/gt2yrupjxgi.html

TS:   [...arr].reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fsyierwl.html

Java: Collections.reverse(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cstxgldb.html

Go:   slices.Reverse(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxbwcaun.html

Ruby: arr.reverse
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqfvktgj.html

C#:   list.Reverse();
来源：http://dali.yj20258888.top/Article/details/gt2imjrlpge.html

[D12] 查找元素下标
来源：http://dali.zhengqikj.top/Article/details/gt2xdhptrtd.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ahpfxvhm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.smart0.xyz/Article/details/gt2bftacayz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2nsvyopvq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2saezgqtv.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guannengcc.top/Article/details/gt2jyrktnbv.html

Go:   slices.Index(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gt2sqehsyjw.html

Ruby: arr.index(x)
来源：http://dali.tianlin.xyz/Article/details/gt2zwtpsebx.html

C#:   list.IndexOf(x);
来源：http://dali.dashuyun.cn/Article/details/gt2afpwszcr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuanzx.com/Article/details/gt2vavoqxiw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2johubpih.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.mhx1999.top/Article/details/gt2uhkgmxom.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2omkklkxs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gt2rehdiavu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.redwolf501.top/Article/details/gt2jrgmkxad.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.meibo888.top/Article/details/gt2oxxvshqw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ybcxt.top/Article/details/gt2zfrkyppp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xinyue.icu/Article/details/gt2nvvkqivn.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gt2eqalytam.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cashguo.top/Article/details/gt2pnmttwol.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.bjfxy.top/Article/details/gt2mnbzeghx.html

JS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gt2mnhegfyb.html

TS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gt2piknomwn.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhengqikj.top/Article/details/gt2byemolhd.html

Go:   // 手写循环
来源：http://dali.yueranfly.top/Article/details/gt2sovxlcei.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2rrwyspzz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2sdvqgsta.html

[D15] 去重
来源：http://dali.hongshengwenyu.top/Article/details/gt2wfeafptm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gt2lcnxzlbn.html

PHP:  array_unique($arr);
来源：http://dali.xinyue.icu/Article/details/gt2ywuwfcbu.html

JS:   [...new Set(arr)]
来源：http://dali.c1oappe.top/Article/details/gt2vkhtudgf.html

TS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gt2czuanjln.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gt2zffemiaq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenlongwang.top/Article/details/gt2oakolfbe.html

Ruby: arr.uniq
来源：http://dali.pengpengdd.cyou/Article/details/gt2abqlusyt.html

C#:   list.Distinct().ToList()
来源：http://dali.yj20258888.top/Article/details/gt2uawszhxx.html

[D16] 求和与平均值
来源：http://dali.jiagoushi.top/Article/details/gt2nlxfgsnk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gdmlgydn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.daxiang520.top/Article/details/gt2dycezebz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hywenlv.cn/Article/details/gt2kdqyigna.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cucudq.cn/Article/details/gt2usrneduu.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hwzhzicf.html

Go:   // 手写循环累加
来源：http://dali.quarkkingdee.top/Article/details/gt2ricfvfrt.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.0kj1m.cn/Article/details/gt2ulfyogcx.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuanzx.com/Article/details/gt2uubbyoql.html

[D17] 最大值与最小值
来源：http://dali.bjfxy.top/Article/details/gt2qsnarfvl.html

Py:   max(arr);  min(arr)
来源：http://dali.316326.xyz/Article/details/gt2exgbyope.html

PHP:  max($arr);  min($arr);
来源：http://dali.jyoumei.cn/Article/details/gt2ijccgmzb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigufen.top/Article/details/gt2nlijtoip.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2wxoxthoc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.xinyue.icu/Article/details/gt2jvabonoi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.bjfxy.top/Article/details/gt2mvusyxfr.html

Ruby: arr.max;  arr.min
来源：http://dali.yueranfly.top/Article/details/gt2pfrgkwsf.html

C#:   list.Max();  list.Min()
来源：http://dali.havefunace.top/Article/details/gt2ypnjicqs.html

[D18] 扁平化嵌套数组
来源：http://dali.yuanzhike.top/Article/details/gt2tzzxpjrz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sxryk.cn/Article/details/gt2fmgvjegu.html

PHP:  array_merge(...$nested);
来源：http://dali.yvedp.cn/Article/details/gt2xqiohofs.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.feifeiyinyue.top/Article/details/gt2czvqabah.html

TS:   nested.flat();
来源：http://dali.xylfe.cn/Article/details/gt2afbiutms.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imfzpdjv.html

Go:   // 手写双层循环
来源：http://dali.sysykeji.top/Article/details/gt2nfijcbtw.html

Ruby: nested.flatten
来源：http://dali.gaohongyu789.top/Article/details/gt2uhboaugy.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhengqikj.top/Article/details/gt2wwxjzgbl.html

[D19] 按字段分组
来源：http://dali.nanxinkj.top/Article/details/gt2amzzkizj.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gogol.net.cn/Article/details/gt2mxpueztm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.tanke756.top/Article/details/gt2xcfvlbsz.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.havefunace.top/Article/details/gt2xemgcloj.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gt2mdnmajuk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xinyue.icu/Article/details/gt2mdzxovst.html

Go:   // 手写 map[string][]T
来源：http://dali.xuetiantiany.cn/Article/details/gt2qpttkxxx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.c1oappe.top/Article/details/gt2xxiuvnaj.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.jlsjyb.cn/Article/details/gt2nhjzjije.html

[D20] 统计每个元素出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nxutdvwr.html

Py:   Counter(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2nylnfmcf.html

PHP:  array_count_values($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jkxvhtjh.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jqgfzy.top/Article/details/gt2tvtnfune.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gt2dmoznvhw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.sweek.top/Article/details/gt2jpjaggun.html

Go:   // 手写 map[T]int
来源：http://dali.quarkkingdee.top/Article/details/gt2tumdywxa.html

Ruby: arr.tally
来源：http://dali.ivvv.top/Article/details/gt2jrvhnakv.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.gotoacloud.top/Article/details/gt2hazkcefs.html

[D21] 判断是否包含某元素
来源：http://dali.fengsongda.top/Article/details/gt2cwuzzith.html

Py:   x in arr
来源：http://dali.redwolf501.top/Article/details/gt2cbzcylmg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhoulong.xyz/Article/details/gt2pywidtuu.html

JS:   arr.includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2wvqzuzij.html

TS:   arr.includes(x)
来源：http://dali.nanxinkj.top/Article/details/gt2rtqzxlpw.html

Java: list.contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2tclrpjbq.html

Go:   slices.Contains(arr, x)
来源：http://dali.ppjwa.cn/Article/details/gt2damlxlhx.html

Ruby: arr.include?(x)
来源：http://dali.zhixingplan.top/Article/details/gt2ztnnwpvo.html

C#:   list.Contains(x)
来源：http://dali.ivvv.top/Article/details/gt2ywabnyqe.html

[D22] 复制数组（避免共享引用）
来源：http://dali.yuanzhike.top/Article/details/gt2fqdqpvkl.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2izjxvkpp.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.ivvv.top/Article/details/gt2gxrsziwc.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2mxfjztbx.html

TS:   [...arr];
来源：http://dali.hysaishi.cn/Article/details/gt2jjuhqcfa.html

Java: new ArrayList<>(list);
来源：http://dali.jyoumei.cn/Article/details/gt2ypmajepo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.yj202588.top/Article/details/gt2fbiuxuyt.html

Ruby: arr.dup;  arr.clone
来源：http://dali.yj20258.top/Article/details/gt2aylttgzl.html

C#:   new List<int>(list);
来源：http://dali.havefunace.top/Article/details/gt2grcbxrao.html

[D23] reduce 累积计算
来源：http://dali.jqgufenzy.top/Article/details/gt2ceasiwaa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.bjfxy.top/Article/details/gt2edhgfdzd.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.ivvv.top/Article/details/gt2oiuwfmfo.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.iojbl.cn/Article/details/gt2bkxxodvy.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.fengsongda.top/Article/details/gt2xkkvopue.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.birdmap.top/Article/details/gt2iuclgfkr.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gt2ixbqfkne.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.kuanghao11.cn/Article/details/gt2gphtsdyj.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.xinyue.icu/Article/details/gt2bbvdxopn.html

[D24] 字典 / Map 基本操作
来源：http://dali.wangdashe.top/Article/details/gt2monvfsuf.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.tianlin.xyz/Article/details/gt2zfzaonnx.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.meibo888.top/Article/details/gt2qdkpoaso.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.gzhubu.top/Article/details/gt2xqoaqssz.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2bgyvszbl.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.sweek.top/Article/details/gt2vhpiepic.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.yj20258.top/Article/details/gt2sipeeqql.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.yj20258888.top/Article/details/gt2tqyjkxos.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.nwbrower.top/Article/details/gt2vnzbzezi.html

[D25] Set 集合去重与交并差
来源：http://dali.xuetiantiany.cn/Article/details/gt2djnowvud.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.aizwys.cn/Article/details/gt2mtvnnbxs.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.hnxiangtu.top/Article/details/gt2uykzayev.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ilxiuoto.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2yhauiztv.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jyoumei.cn/Article/details/gt2ycnqpnli.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.hfpthk.cn/Article/details/gt2rfvsaova.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.tianlin.xyz/Article/details/gt2jwipmlye.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxmbgxcu.html

[D26] 数组转字符串
来源：http://dali.cdnleiting.top/Article/details/gt2rhaxliie.html

Py:   ", ".join(map(str, arr))
来源：http://dali.shuidangran.top/Article/details/gt2fdgvmscp.html

PHP:  implode(", ", $arr);
来源：http://dali.jiagoushi.top/Article/details/gt2nxdcdqws.html

JS:   arr.join(", ")
来源：http://dali.jqgfzy.top/Article/details/gt2ivunhnzs.html

TS:   arr.join(", ")
来源：http://dali.xziqi.cn/Article/details/gt2chflapbs.html

Java: String.join(", ", list)
来源：http://dali.fengsongda.top/Article/details/gt2qsozskif.html

Go:   strings.Join(strs, ", ")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emvsshwp.html

Ruby: arr.join(", ")
来源：http://dali.gotoacloud.top/Article/details/gt2fytycduf.html

C#:   string.Join(", ", list)
来源：http://dali.xziqi.cn/Article/details/gt2ugaarijd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2ztagxivx.html

E. 字符串处理
来源：http://dali.ivvv.top/Article/details/gt2tgknauuh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2fyphaolb.html

[E01] 拼接字符串
来源：http://dali.havefunace.top/Article/details/gt2fvaoinba.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.pycfn.com/Article/details/gt2renidvau.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2yatfgsor.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yrmqbcio.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.guowangkeji.top/Article/details/gt2stjusctv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.nwbrower.top/Article/details/gt2dgcjimfn.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.yueranfly.top/Article/details/gt2fmluqgfc.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.zdqjudy.top/Article/details/gt2gtmduvyt.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.havefunace.top/Article/details/gt2igyadapz.html

[E02] 重复字符串
来源：http://dali.jqgufenzy.top/Article/details/gt2vtksoubf.html

Py:   "ab" * 3
来源：http://dali.nanxuanxn.top/Article/details/gt2ybohodla.html

PHP:  str_repeat("ab", 3);
来源：http://dali.xziqi.cn/Article/details/gt2ovqkjegd.html

JS:   "ab".repeat(3)
来源：http://dali.yj202588.top/Article/details/gt2xhquxqbi.html

TS:   "ab".repeat(3)
来源：http://dali.quarkkingdee.top/Article/details/gt2dbdfqwdl.html

Java: "ab".repeat(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aoyirytw.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.yvedp.cn/Article/details/gt2rcdefgla.html

Ruby: "ab" * 3
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtqqyfgv.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.hammf.cn/Article/details/gt2qavqutzi.html

[E03] 截取子串
来源：http://dali.nwbrower.top/Article/details/gt2ecvchdet.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.gotoacloud.top/Article/details/gt2xldiqnvk.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.yj20258.top/Article/details/gt2phjwvpkn.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.hammf.cn/Article/details/gt2tpwwfxta.html

TS:   s.slice(1, 4)
来源：http://dali.snrcjt.cn/Article/details/gt2sazniywj.html

Java: s.substring(1, 4)
来源：http://dali.hfpthk.cn/Article/details/gt2dadqdnhq.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.yj202588.top/Article/details/gt2adtajlhg.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.jinqigufen.top/Article/details/gt2lpcdstsr.html

C#:   s.Substring(1, 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bujstaoc.html

[E04] 查找子串位置
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ocghslsz.html

Py:   s.find("x");  s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gt2gomilayq.html

PHP:  strpos($s, "x");
来源：http://dali.hysaishi.cn/Article/details/gt2chschyog.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.nanxinkj.top/Article/details/gt2sknqpnuw.html

TS:   s.indexOf("x")
来源：http://dali.yonumen.top/Article/details/gt2vnoxsadl.html

Java: s.indexOf("x")
来源：http://dali.yj202588.top/Article/details/gt2xwltdrzz.html

Go:   strings.Index(s, "x")
来源：http://dali.birdmap.top/Article/details/gt2ffsgherl.html

Ruby: s.index("x")
来源：http://dali.fzhhl.top/Article/details/gt2gmypgbja.html

C#:   s.IndexOf("x")
来源：http://dali.cqqwz.cn/Article/details/gt2fszbltjj.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qtfogtgp.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oagjgjbq.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.yangfankeji.com/Article/details/gt2kdpfoerj.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.yvedp.cn/Article/details/gt2rintozpu.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.yuxming.cn/Article/details/gt2wtnygjtv.html


<!-- 参考信息 -->