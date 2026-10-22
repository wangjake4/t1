代发 wailian999

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pycfn.com/Article/details/gt2ovmvwmqm.html

[C15] 解构 / 展开参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2nocchyvb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sweek.top/Article/details/gt2zjbpczcz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shuidangran.top/Article/details/gt2rlvbmlau.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gt2rzqtrauc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj202588.top/Article/details/gt2iupstzco.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gt2gqtuigpk.html

Go:   // 无解构
来源：http://dali.ehwqpu.com/Article/details/gt2lfjaiiit.html

Ruby: a, b = pair
来源：http://dali.mhx1999.top/Article/details/gt2hvffruej.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gt2mqmnjclz.html

[C16] 函数 / 方法重载
来源：http://dali.aizwys.cn/Article/details/gt2gknvqdob.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yanxiufei.cn/Article/details/gt2zlhikctf.html

PHP:  // 无重载
来源：http://dali.fengsongda.top/Article/details/gt2nyzfjlxu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2czlxkgdw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hysaishi.cn/Article/details/gt2nnluknja.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zycfv.cn/Article/details/gt2zolgrcxk.html

Go:   // 无重载：用不同函数名
来源：http://dali.cucudq.cn/Article/details/gt2nohklfrw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yvedp.cn/Article/details/gt2jqfotucm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aibaodan.cn/Article/details/gt2vaeksfpu.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hpqwmwga.html

D. 数组 / 列表 / 集合
来源：http://dali.chenzaomai.com/Article/details/gt2bsixcjsp.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2joxqgwhf.html

[D01] 创建数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gt2wltgczyp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.redwolf501.top/Article/details/gt2dxbosxdh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sufxvd.cn/Article/details/gt2ihbfkxkl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.redwolf501.top/Article/details/gt2qeoxrapn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gt2ydjscimz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.feifeiyinyue.top/Article/details/gt2kuxqkioz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yanxiufei.cn/Article/details/gt2zhurniqr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gt2fxparxaz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shzxlz.cn/Article/details/gt2earfchxh.html

[D02] 追加元素到末尾
来源：http://dali.kuanghao11.cn/Article/details/gt2jhzxicvp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gt2larbafyz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yanxiufei.cn/Article/details/gt2cjsnmapm.html

JS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2ucyvdojt.html

TS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2yctljlcc.html

Java: list.add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndvuisof.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gt2dncgvzht.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.vqdsnc.cn/Article/details/gt2ygkssgwt.html

C#:   list.Add(4);
来源：http://dali.hnqzz.top/Article/details/gt2bdgdhnvi.html

[D03] 在指定位置插入元素
来源：http://dali.zhongyouzk.top/Article/details/gt2fehhizei.html

Py:   arr.insert(0, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2ealyoyij.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2vrngpwig.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shzxlz.cn/Article/details/gt2wbsbupjo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.havefunace.top/Article/details/gt2ihvuqcte.html

Java: list.add(0, 0);
来源：http://dali.yuxming.cn/Article/details/gt2mnsdgzjq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gogol.net.cn/Article/details/gt2ffzuauvu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zycfv.cn/Article/details/gt2hzptwmrb.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258888.top/Article/details/gt2xlxvbplk.html

[D04] 删除元素
来源：http://dali.yueranfly.top/Article/details/gt2klojdncc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2saeafcqt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pycfn.com/Article/details/gt2lzjkhtav.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gzhubu.top/Article/details/gt2sxpfanmu.html

TS:   arr.splice(0, 1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bfmofzdw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2mujhpddm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eovfctqw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.meibo888.top/Article/details/gt2pggnzjmo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.smart0.xyz/Article/details/gt2qdumnpsw.html

[D05] 访问与修改元素
来源：http://dali.xziqi.cn/Article/details/gt2qgtlmfxj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gt2wpqinfby.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gt2edtkxrns.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gt2ispnwspy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fengsongda.top/Article/details/gt2syrermzm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jsjoiaya.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gt2tjbemqih.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gt2pfukfqkv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gt2badtnxyy.html

[D06] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lpntaoel.html

Py:   len(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2zrbcnkbn.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cdnhumxh.html

JS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gt2glszhqtq.html

TS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gt2ekcyydsx.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gt2tabiuitl.html

Go:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2qftcvszn.html

Ruby: arr.length; arr.size
来源：http://dali.birdmap.top/Article/details/gt2sivfbqla.html

C#:   list.Count;
来源：http://dali.jiagoushi.top/Article/details/gt2fwmsfkeq.html

[D07] 切片 / 取子数组
来源：http://dali.yonumen.top/Article/details/gt2kiqxejlf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fengsongda.top/Article/details/gt2nazykjeb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2pkliiogi.html

JS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gt2csmadupz.html

TS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gt2eqmrnqie.html

Java: list.subList(1, 4);
来源：http://dali.aibaodan.cn/Article/details/gt2qxxrhntj.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gt2nfeuwazi.html

Ruby: arr[1, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gt2pbixhyiy.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2nlmknfsm.html

[D08] 合并两个数组
来源：http://dali.quarkkingdee.top/Article/details/gt2xwanwabe.html

Py:   a + b;  a.extend(b)
来源：http://dali.daxiang520.top/Article/details/gt2lfsshqnk.html

PHP:  array_merge($a, $b);
来源：http://dali.cheryme.top/Article/details/gt2pzojejva.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yanxiufei.cn/Article/details/gt2wvfdgdwn.html

TS:   [...a, ...b];
来源：http://dali.iojbl.cn/Article/details/gt2urrmsiwz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2ihyecype.html

Go:   append(a, b...)
来源：http://dali.gaohongyu789.top/Article/details/gt2bqawvrja.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dashuyun.cn/Article/details/gt2rtczmqon.html

C#:   a.Concat(b).ToList()
来源：http://dali.hfpthk.cn/Article/details/gt2mdfrxhon.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gt2eonniaqv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenzaomai.com/Article/details/gt2fjvejrpj.html

PHP:  sort($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2wdshfyeb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.kuanghao11.cn/Article/details/gt2ihlegbzf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gt2zksxhaek.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gt2twgmqrxk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenlongwang.top/Article/details/gt2psnsvbkh.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gt2pebjmicp.html

C#:   list.Sort();
来源：http://dali.hfpthk.cn/Article/details/gt2nvxqtctz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.meibo888.top/Article/details/gt2ofswszlt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gt2vwoiswan.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gt2yjdnysum.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gt2gzyfkagw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gaohongyu789.top/Article/details/gt2yauzqhss.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrpxlox.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2watcvlem.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yuxming.cn/Article/details/gt2hoyyfqkr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aibaodan.cn/Article/details/gt2gqoedjxr.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gt2kpkghtcl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhixingplan.top/Article/details/gt2jluporaz.html

PHP:  array_reverse($arr);
来源：http://dali.xuanzx.com/Article/details/gt2gvobqkrc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhongyouzk.top/Article/details/gt2nhaffbzv.html

TS:   [...arr].reverse();
来源：http://dali.jinqigufen.top/Article/details/gt2esahflvx.html

Java: Collections.reverse(list);
来源：http://dali.feifeiyinyue.top/Article/details/gt2aoqordrj.html

Go:   slices.Reverse(arr)
来源：http://dali.tanke756.top/Article/details/gt2wlfrzyjw.html

Ruby: arr.reverse
来源：http://dali.jinqigfzy.top/Article/details/gt2bldekiaq.html

C#:   list.Reverse();
来源：http://dali.vqdsnc.cn/Article/details/gt2orpcxpie.html

[D12] 查找元素下标
来源：http://dali.0kj1m.cn/Article/details/gt2lvevudrl.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gt2gunphica.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.aizwys.cn/Article/details/gt2dreehzno.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gzhubu.top/Article/details/gt2rknkpxgk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxsbzvpm.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cdnleiting.top/Article/details/gt2pgjntfht.html

Go:   slices.Index(arr, x)
来源：http://dali.tian-w.cn/Article/details/gt2lexbcqhw.html

Ruby: arr.index(x)
来源：http://dali.yj20258.top/Article/details/gt2fxuazjae.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigufen.top/Article/details/gt2acxxfrks.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2uehjmqwe.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2mccfsyfp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.daria6918.cn/Article/details/gt2jzmwrvum.html

JS:   arr.filter(x => x > 3)
来源：http://dali.birdmap.top/Article/details/gt2cmdfrvii.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2tvhisgvi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2qwiviqos.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yvedp.cn/Article/details/gt2qxtxbqer.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.vqdsnc.cn/Article/details/gt2aqxhbdly.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2qhpsevjf.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gogol.net.cn/Article/details/gt2movcebjo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jqgfzy.top/Article/details/gt2ilpsuzrc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.aizwys.cn/Article/details/gt2jvdvnhek.html

JS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gt2eexqifij.html

TS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gt2jlewgfoe.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2vafzdueu.html

Go:   // 手写循环
来源：http://dali.zhongyouzk.top/Article/details/gt2iipjvicx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.iojbl.cn/Article/details/gt2cnlgkjoe.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.aizwys.cn/Article/details/gt2yqjohjlp.html

[D15] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pihxyhiq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gt2wroechzf.html

PHP:  array_unique($arr);
来源：http://dali.hammf.cn/Article/details/gt2xzoburaz.html

JS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lhvpcjlp.html

TS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gt2aqniekdz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gt2hgylgabh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhixingplan.top/Article/details/gt2pmizuqom.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dfnooveh.html

C#:   list.Distinct().ToList()
来源：http://dali.xuanzx.com/Article/details/gt2pxyrlxgp.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gt2cplvqfhf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yj20258888.top/Article/details/gt2wttbxuqq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2zxqaemld.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.dashuyun.cn/Article/details/gt2czsbfepr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sxryk.cn/Article/details/gt2hsomxpph.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shangyingyoupin.top/Article/details/gt2xwrjkiox.html

Go:   // 手写循环累加
来源：http://dali.jqgufenzy.top/Article/details/gt2wcfagcmw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.tanke756.top/Article/details/gt2ovnpyfzz.html

C#:   list.Sum();  list.Average()
来源：http://dali.gzhubu.top/Article/details/gt2egwupogw.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gt2kgajncnk.html

Py:   max(arr);  min(arr)
来源：http://dali.xinyue.icu/Article/details/gt2yymqbsyd.html

PHP:  max($arr);  min($arr);
来源：http://dali.mhx1999.top/Article/details/gt2wcajlwyh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daxiang520.top/Article/details/gt2ndutmfwc.html

TS:   Math.max(...arr);
来源：http://dali.daxiang520.top/Article/details/gt2gdyryzoj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.mhx1999.top/Article/details/gt2nsakppje.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuxming.cn/Article/details/gt2awfbjfuk.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gt2tlvaxhgi.html

C#:   list.Max();  list.Min()
来源：http://dali.yuanzhike.top/Article/details/gt2lgaiwcdt.html

[D18] 扁平化嵌套数组
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bynflnxp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhiwuduotai.top/Article/details/gt2tdwbwksf.html

PHP:  array_merge(...$nested);
来源：http://dali.cdnleiting.top/Article/details/gt2bwonslpn.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gogol.net.cn/Article/details/gt2zbfejnnx.html

TS:   nested.flat();
来源：http://dali.xuetiantiany.cn/Article/details/gt2xebfznnd.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2pfuumtak.html

Go:   // 手写双层循环
来源：http://dali.gaohongyu789.top/Article/details/gt2dpeqonfw.html

Ruby: nested.flatten
来源：http://dali.9152youxi.cn/Article/details/gt2wekcqujj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2htidkjnv.html

[D19] 按字段分组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zgzorjax.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.havefunace.top/Article/details/gt2smngqnnj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.sxryk.cn/Article/details/gt2ecsunrwo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.zhengqikj.top/Article/details/gt2gixdtymg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gt2jvsweivp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.iojbl.cn/Article/details/gt2qunuzrdg.html

Go:   // 手写 map[string][]T
来源：http://dali.gogol.net.cn/Article/details/gt2qfocokcc.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gt2wiisrxef.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.c1oappe.top/Article/details/gt2qlaxcazr.html

[D20] 统计每个元素出现次数
来源：http://dali.xziqi.cn/Article/details/gt2aonalovf.html

Py:   Counter(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2wbnkutak.html

PHP:  array_count_values($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2gkftetms.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jlsjyb.cn/Article/details/gt2ykqjvlvw.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhoulong.xyz/Article/details/gt2nsyziotn.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ivvv.top/Article/details/gt2nxdnrenv.html

Go:   // 手写 map[T]int
来源：http://dali.yvedp.cn/Article/details/gt2zmjoxkjl.html

Ruby: arr.tally
来源：http://dali.fengsongda.top/Article/details/gt2ngldcswp.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.svipenyu.cn/Article/details/gt2rpkeozsy.html

[D21] 判断是否包含某元素
来源：http://dali.ivvv.top/Article/details/gt2yvedbbpm.html

Py:   x in arr
来源：http://dali.jqgufenzy.top/Article/details/gt2qkxijemk.html

PHP:  in_array($x, $arr, true);
来源：http://dali.feifeiyinyue.top/Article/details/gt2oacgyoig.html

JS:   arr.includes(x)
来源：http://dali.hammf.cn/Article/details/gt2ggorhxix.html

TS:   arr.includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2sfioigqu.html

Java: list.contains(x)
来源：http://dali.cdnleiting.top/Article/details/gt2rivlpvzf.html

Go:   slices.Contains(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2qdrzdwjm.html

Ruby: arr.include?(x)
来源：http://dali.cqqwz.cn/Article/details/gt2zgcpffzi.html

C#:   list.Contains(x)
来源：http://dali.sufxvd.cn/Article/details/gt2rjxqpsjn.html

[D22] 复制数组（避免共享引用）
来源：http://dali.ydzc1.top/Article/details/gt2gpawzqdh.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.gzhubu.top/Article/details/gt2tkmwjrsu.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.xinyue.icu/Article/details/gt2qsqnivbq.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.sxryk.cn/Article/details/gt2rbmvvoxy.html

TS:   [...arr];
来源：http://dali.tanke756.top/Article/details/gt2xkgzyaem.html

Java: new ArrayList<>(list);
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrlqfgei.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.hysaishi.cn/Article/details/gt2elkyqwed.html

Ruby: arr.dup;  arr.clone
来源：http://dali.dianchejie.cn/Article/details/gt2gimvadit.html

C#:   new List<int>(list);
来源：http://dali.hongshengwenyu.top/Article/details/gt2gizupeex.html

[D23] reduce 累积计算
来源：http://dali.mhx1999.top/Article/details/gt2mggucxog.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.316326.xyz/Article/details/gt2vzbkxhvk.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.sysykeji.top/Article/details/gt2dudqhhba.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.mhx1999.top/Article/details/gt2lbwutazz.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pfqulkna.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.fzhhl.top/Article/details/gt2rqghbxux.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2eugibwry.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.tanke756.top/Article/details/gt2vvrgahwz.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.zycfv.cn/Article/details/gt2zdpxjbrb.html

[D24] 字典 / Map 基本操作
来源：http://dali.hywenlv.cn/Article/details/gt2vwzvzezv.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.vqdsnc.cn/Article/details/gt2uyvfybkf.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2qihdqnfc.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.guowangkeji.top/Article/details/gt2sfdathjo.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2ngwemikb.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.mhx1999.top/Article/details/gt2mvlogvjm.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.xziqi.cn/Article/details/gt2ytghocxq.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.fengsongda.top/Article/details/gt2ckaibkwk.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.feifeiyinyue.top/Article/details/gt2nzxrkqaz.html

[D25] Set 集合去重与交并差
来源：http://dali.kuanghao11.cn/Article/details/gt2rxbzchmm.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.bjfxy.top/Article/details/gt2xuiorxap.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.gotoacloud.top/Article/details/gt2eletpilk.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojryylve.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.yj20258888.top/Article/details/gt2vcxmjzgt.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.jqgfzy.top/Article/details/gt2wheuahsm.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.xinyue.icu/Article/details/gt2sjvzadye.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.cdnleiting.top/Article/details/gt2rcqrzujq.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.nanxuanxn.top/Article/details/gt2gykmahve.html

[D26] 数组转字符串
来源：http://dali.tian-w.cn/Article/details/gt2zbuiihnj.html

Py:   ", ".join(map(str, arr))
来源：http://dali.gzhubu.top/Article/details/gt2jzvtfvjf.html

PHP:  implode(", ", $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2gxdyjtqx.html

JS:   arr.join(", ")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dcnsgyue.html

TS:   arr.join(", ")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpummdnv.html

Java: String.join(", ", list)
来源：http://dali.birdmap.top/Article/details/gt2plhrtjzt.html

Go:   strings.Join(strs, ", ")
来源：http://dali.dashuyun.cn/Article/details/gt2rgcvpilm.html

Ruby: arr.join(", ")
来源：http://dali.shuidangran.top/Article/details/gt2rrsocekx.html

C#:   string.Join(", ", list)
来源：http://dali.birdmap.top/Article/details/gt2nspzbett.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2xodzbssq.html

E. 字符串处理
来源：http://dali.hongshengwenyu.top/Article/details/gt2mpxhsnsi.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2peqnbdpe.html

[E01] 拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2ejvlvibe.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shuidangran.top/Article/details/gt2htrtqstq.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.yongpay.top/Article/details/gt2osyoccvk.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.xinyue.icu/Article/details/gt2kaxjmvoh.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.cheryme.top/Article/details/gt2gogoexpz.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2xsicutgc.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.quarkkingdee.top/Article/details/gt2maekyzkt.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gogol.net.cn/Article/details/gt2ohmxwizf.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2tchpwtmi.html

[E02] 重复字符串
来源：http://dali.chenlongwang.top/Article/details/gt2ofzymlda.html

Py:   "ab" * 3
来源：http://dali.havefunace.top/Article/details/gt2jqemrelg.html

PHP:  str_repeat("ab", 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2skxphrkx.html

JS:   "ab".repeat(3)
来源：http://dali.shuidangran.top/Article/details/gt2aevxvvrj.html

TS:   "ab".repeat(3)
来源：http://dali.nanxuanxn.top/Article/details/gt2njsryowc.html

Java: "ab".repeat(3)
来源：http://dali.yuanzhike.top/Article/details/gt2thsgxkdb.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.sxryk.cn/Article/details/gt2okiumeii.html

Ruby: "ab" * 3
来源：http://dali.9152youxi.cn/Article/details/gt2ypwwhedp.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.zhengqikj.top/Article/details/gt2oqadoxbj.html

[E03] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gt2scyznkwi.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.kuanghao11.cn/Article/details/gt2fynegztg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.shangyingyoupin.top/Article/details/gt2yjknergl.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xuhqwvex.html

TS:   s.slice(1, 4)
来源：http://dali.shzxlz.cn/Article/details/gt2vnjyykdj.html

Java: s.substring(1, 4)
来源：http://dali.ppjwa.cn/Article/details/gt2ausdowen.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.quarkkingdee.top/Article/details/gt2zmsfrjnt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.zycfv.cn/Article/details/gt2zhnzyotc.html

C#:   s.Substring(1, 3)
来源：http://dali.nanxinkj.top/Article/details/gt2tcgknskr.html

[E04] 查找子串位置
来源：http://dali.0kj1m.cn/Article/details/gt2dupcdenj.html

Py:   s.find("x");  s.index("x")
来源：http://dali.0kj1m.cn/Article/details/gt2iozcclpu.html

PHP:  strpos($s, "x");
来源：http://dali.aibaodan.cn/Article/details/gt2bexxueup.html

JS:   s.indexOf("x");  s.search(/x/)
来源：http://dali.sysykeji.top/Article/details/gt2kxjhrujo.html

TS:   s.indexOf("x")
来源：http://dali.yueranfly.top/Article/details/gt2nenftouh.html

Java: s.indexOf("x")
来源：http://dali.zhoulong.xyz/Article/details/gt2sjggymuf.html

Go:   strings.Index(s, "x")
来源：http://dali.nanxuanxn.top/Article/details/gt2obotdynd.html

Ruby: s.index("x")
来源：http://dali.nwbrower.top/Article/details/gt2rbftxhsk.html

C#:   s.IndexOf("x")
来源：http://dali.yangfankeji.com/Article/details/gt2ifekponl.html

[E05] 判断包含 / 前缀 / 后缀
来源：http://dali.wangshuangyany.cn/Article/details/gt2jzpyquml.html

Py:   "x" in s;  s.startswith("a");  s.endswith("z")
来源：http://dali.zhoulong.xyz/Article/details/gt2mwjyeebj.html

PHP:  str_contains($s, "x");  str_starts_with($s, "a");  str_ends_with($s, "z");
来源：http://dali.shuidangran.top/Article/details/gt2ephxewwo.html

JS:   s.includes("x");  s.startsWith("a");  s.endsWith("z")
来源：http://dali.hnxiangtu.top/Article/details/gt2ukgvjjtv.html

TS:   s.includes("x");  s.startsWith("a")
来源：http://dali.daxiang520.top/Article/details/gt2fbkxyvjj.html


<!-- 参考信息 -->