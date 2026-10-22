代发 wailian999

Java: int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2fnaeitak.html

Go:   func add(a, b int) int
来源：http://dali.xylfe.cn/Article/details/gt2hjdqijix.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xogggpli.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tian-w.cn/Article/details/gt2xluprtpn.html

[C14] 泛型函数
来源：http://dali.andypj.xyz/Article/details/gt2vxwoamuk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yonumen.top/Article/details/gt2yiaiploe.html

PHP:  // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gt2giupvvdv.html

JS:   // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gt2ejafexzz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfkitdot.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bkbfzgio.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sufxvd.cn/Article/details/gt2nzweurlx.html

Ruby: # 无泛型
来源：http://dali.yuanzhike.top/Article/details/gt2onbmqxbu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhixingplan.top/Article/details/gt2nfbjmfwp.html

[C15] 解构 / 展开参数
来源：http://dali.chenlongwang.top/Article/details/gt2tvhzeowd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sufxvd.cn/Article/details/gt2zpbpjeso.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sufxvd.cn/Article/details/gt2opqpnnil.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gt2gvhxxmii.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258888.top/Article/details/gt2mfhayxfy.html

Java: // 无解构
来源：http://dali.sweek.top/Article/details/gt2nstmwqsr.html

Go:   // 无解构
来源：http://dali.mhx1999.top/Article/details/gt2lttwwiwo.html

Ruby: a, b = pair
来源：http://dali.zhiwuduotai.top/Article/details/gt2msejgcgt.html

C#:   var (a, b) = pair;
来源：http://dali.wangshuangyany.cn/Article/details/gt2rogjyvdv.html

[C16] 函数 / 方法重载
来源：http://dali.jiagoushi.top/Article/details/gt2dkyzuqkz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ivvv.top/Article/details/gt2vozlmgwa.html

PHP:  // 无重载
来源：http://dali.cucudq.cn/Article/details/gt2tqlxgvvy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hfpthk.cn/Article/details/gt2pdfbifkx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhongyouzk.top/Article/details/gt2bpfuddlt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daxiang520.top/Article/details/gt2evivbvob.html

Go:   // 无重载：用不同函数名
来源：http://dali.sweek.top/Article/details/gt2svgrghfd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hfpthk.cn/Article/details/gt2ywevyrlp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aizwys.cn/Article/details/gt2wtymwyhk.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2wkhqtzud.html

D. 数组 / 列表 / 集合
来源：http://dali.cucudq.cn/Article/details/gt2julsfhyw.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ndixfkuj.html

[D01] 创建数组 / 列表
来源：http://dali.haohaochexian.top/Article/details/gt2gcfshmxx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tian-w.cn/Article/details/gt2iuiiimnr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojmootbg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aibaodan.cn/Article/details/gt2yexmvlcs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2amuqzfmz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daxiang520.top/Article/details/gt2fgqltwbk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tian-w.cn/Article/details/gt2ndbmqzbg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bymxuguu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigufen.top/Article/details/gt2crhipujc.html

[D02] 追加元素到末尾
来源：http://dali.xylfe.cn/Article/details/gt2cfzfubpc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigufen.top/Article/details/gt2clsnckdr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tian-w.cn/Article/details/gt2phlptcxl.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gt2lfejuily.html

TS:   arr.push(4);
来源：http://dali.sysykeji.top/Article/details/gt2sibjqbih.html

Java: list.add(4);
来源：http://dali.aibaodan.cn/Article/details/gt2ndfkbnlk.html

Go:   arr = append(arr, 4)
来源：http://dali.zhongyouzk.top/Article/details/gt2cqcxlamx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuanzx.com/Article/details/gt2ketqnpap.html

C#:   list.Add(4);
来源：http://dali.snrcjt.cn/Article/details/gt2bgypputh.html

[D03] 在指定位置插入元素
来源：http://dali.hysaishi.cn/Article/details/gt2yytksalg.html

Py:   arr.insert(0, 0)
来源：http://dali.dianchejie.cn/Article/details/gt2aixrmozt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gogol.net.cn/Article/details/gt2rciglksg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhoulong.xyz/Article/details/gt2zlsueybg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zdqjudy.top/Article/details/gt2ceglikiz.html

Java: list.add(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gt2nbdnhthh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.andypj.xyz/Article/details/gt2ugjklnny.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gt2yefwjhph.html

C#:   list.Insert(0, 0);
来源：http://dali.ivvv.top/Article/details/gt2iuzvnama.html

[D04] 删除元素
来源：http://dali.yj202588.top/Article/details/gt2fugbijdu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnqzz.top/Article/details/gt2ifsyldyl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2oqerxerq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangdashe.top/Article/details/gt2gplbexaw.html

TS:   arr.splice(0, 1);
来源：http://dali.ppjwa.cn/Article/details/gt2sttwpmqr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhongyouzk.top/Article/details/gt2llpmdqoq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ppjwa.cn/Article/details/gt2ibrmtdor.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukskidfn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gt2exalakhc.html

[D05] 访问与修改元素
来源：http://dali.xinyue.icu/Article/details/gt2wvgajpmw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gt2lhdupxkt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gt2nrcgosvz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gt2nkdcxkmw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.vqdsnc.cn/Article/details/gt2xranmnnw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ydzc1.top/Article/details/gt2cvepqcea.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gt2tauicvjz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gt2iotcipik.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.havefunace.top/Article/details/gt2fblhsayp.html

[D06] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gt2osshxman.html

Py:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spwkpvlv.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbsanrw.html

JS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gt2sxrwujqc.html

TS:   arr.length
来源：http://dali.cucudq.cn/Article/details/gt2bigyoerx.html

Java: list.size();
来源：http://dali.zdqjudy.top/Article/details/gt2tqvhnwqk.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gt2zrkqogwg.html

Ruby: arr.length; arr.size
来源：http://dali.quarkkingdee.top/Article/details/gt2muuleesr.html

C#:   list.Count;
来源：http://dali.jlsjyb.cn/Article/details/gt2jmchtbwd.html

[D07] 切片 / 取子数组
来源：http://dali.hfpthk.cn/Article/details/gt2bwcuqera.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gt2ziwrwzzz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuxming.cn/Article/details/gt2tjstidmi.html

JS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gt2pcwxngix.html

TS:   arr.slice(1, 4);
来源：http://dali.yvedp.cn/Article/details/gt2eyoonddn.html

Java: list.subList(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ebclmpwl.html

Go:   arr[1:4]
来源：http://dali.sysykeji.top/Article/details/gt2myhddzns.html

Ruby: arr[1, 3]
来源：http://dali.jlsjyb.cn/Article/details/gt2wkkrsfoq.html

C#:   list.GetRange(1, 3);
来源：http://dali.0kj1m.cn/Article/details/gt2utusjdtm.html

[D08] 合并两个数组
来源：http://dali.dashuyun.cn/Article/details/gt2jqkmhpnk.html

Py:   a + b;  a.extend(b)
来源：http://dali.nwbrower.top/Article/details/gt2pfdpsuxv.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gt2hhvmdbhv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jianghu66.top/Article/details/gt2vdtqnikx.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gt2tdnivhae.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2vckbjcav.html

Go:   append(a, b...)
来源：http://dali.yj202588.top/Article/details/gt2edkyfxcq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigfzy.top/Article/details/gt2bbqwxxol.html

C#:   a.Concat(b).ToList()
来源：http://dali.haohaochexian.top/Article/details/gt2rvsrwnua.html

[D09] 排序（升序）
来源：http://dali.nwbrower.top/Article/details/gt2hthetctb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yonumen.top/Article/details/gt2tfmgeckt.html

PHP:  sort($arr);
来源：http://dali.yj202588.top/Article/details/gt2xkwncpli.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.quarkkingdee.top/Article/details/gt2qwawhcgf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guannengcc.top/Article/details/gt2solodjcp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wwzlrluw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2avqawrtx.html

Ruby: arr.sort
来源：http://dali.quarkkingdee.top/Article/details/gt2rayacwhr.html

C#:   list.Sort();
来源：http://dali.wangdashe.top/Article/details/gt2qllwrcmt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gt2nilvgjsy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jiagoushi.top/Article/details/gt2udxkffaf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gt2xbkyzrgr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gt2tvpmleic.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gt2qctftfrx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.bjfxy.top/Article/details/gt2zfwmfvps.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guowangkeji.top/Article/details/gt2jfxyxdvx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2whdbezlg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hysaishi.cn/Article/details/gt2wepxxzzk.html

[D11] 反转数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uczlwqch.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.andypj.xyz/Article/details/gt2lmnfeezv.html

PHP:  array_reverse($arr);
来源：http://dali.andypj.xyz/Article/details/gt2efxwminz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.smart0.xyz/Article/details/gt2otuvncax.html

TS:   [...arr].reverse();
来源：http://dali.aibaodan.cn/Article/details/gt2nhymzghw.html

Java: Collections.reverse(list);
来源：http://dali.redwolf501.top/Article/details/gt2qytqwxln.html

Go:   slices.Reverse(arr)
来源：http://dali.xziqi.cn/Article/details/gt2erqluazc.html

Ruby: arr.reverse
来源：http://dali.xylfe.cn/Article/details/gt2xdipddyp.html

C#:   list.Reverse();
来源：http://dali.yj20258.top/Article/details/gt2hutsgcqp.html

[D12] 查找元素下标
来源：http://dali.chenzaomai.com/Article/details/gt2nppcuitl.html

Py:   arr.index(x);  x in arr
来源：http://dali.aizwys.cn/Article/details/gt2ttunazqg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2qzhdkwet.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gt2ncxikefd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gt2ugprqunx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2znwzypdp.html

Go:   slices.Index(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2tzdtkxkg.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gt2ottnqfoc.html

C#:   list.IndexOf(x);
来源：http://dali.aizwys.cn/Article/details/gt2owlvqnzh.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yvedp.cn/Article/details/gt2gnvwdzet.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258888.top/Article/details/gt2yfihznfj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yangfankeji.com/Article/details/gt2ncgwhswx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.chenzaomai.com/Article/details/gt2cuxveukv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.aibaodan.cn/Article/details/gt2zkmsqsai.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.fzhhl.top/Article/details/gt2uwuusqup.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yonumen.top/Article/details/gt2yvnrwegh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnqzz.top/Article/details/gt2mwlcakea.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gt2rdvyttth.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kaxwmlqg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.aizwys.cn/Article/details/gt2joenrpwf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2usqbmapf.html

JS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gt2tlegeyxv.html

TS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2jpxlsjzk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.aibaodan.cn/Article/details/gt2ddiomntu.html

Go:   // 手写循环
来源：http://dali.yonumen.top/Article/details/gt2qnzouejz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yybxozbf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2ufjvivxv.html

[D15] 去重
来源：http://dali.birdmap.top/Article/details/gt2srxjohom.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gt2rjqqglhv.html

PHP:  array_unique($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2ftsfpbgo.html

JS:   [...new Set(arr)]
来源：http://dali.nanxuanxn.top/Article/details/gt2jwugaqfh.html

TS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gt2uoqdreno.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.havefunace.top/Article/details/gt2rfhgutgg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.feifeiyinyue.top/Article/details/gt2zrhxvxmy.html

Ruby: arr.uniq
来源：http://dali.gotoacloud.top/Article/details/gt2qqixnzen.html

C#:   list.Distinct().ToList()
来源：http://dali.svipenyu.cn/Article/details/gt2kitrazvl.html

[D16] 求和与平均值
来源：http://dali.jyoumei.cn/Article/details/gt2kcmmgumd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.meibo888.top/Article/details/gt2orteobxz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.andypj.xyz/Article/details/gt2cbpsygut.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gt2cwdtkqdb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2ovyhxfju.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wbdrkkuh.html

Go:   // 手写循环累加
来源：http://dali.kuanghao11.cn/Article/details/gt2dmgljqge.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.chenjidiqi.icu/Article/details/gt2uwuqofeo.html

C#:   list.Sum();  list.Average()
来源：http://dali.cdnleiting.top/Article/details/gt2vtakafrz.html

[D17] 最大值与最小值
来源：http://dali.smart0.xyz/Article/details/gt2yeplsntz.html

Py:   max(arr);  min(arr)
来源：http://dali.bjfxy.top/Article/details/gt2lwjyhoan.html

PHP:  max($arr);  min($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2hvrpxqcf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kdmdgjbb.html

TS:   Math.max(...arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2asypmnoo.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gt2ewuphuha.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cashguo.top/Article/details/gt2hvnzkzye.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gt2kldfjsqt.html

C#:   list.Max();  list.Min()
来源：http://dali.ybcxt.top/Article/details/gt2vukkakgc.html

[D18] 扁平化嵌套数组
来源：http://dali.hnqzz.top/Article/details/gt2fwwquebz.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.gotoacloud.top/Article/details/gt2rkrlnxta.html

PHP:  array_merge(...$nested);
来源：http://dali.jinqigufen.top/Article/details/gt2pvupyshq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuanzhike.top/Article/details/gt2jdpkgrng.html

TS:   nested.flat();
来源：http://dali.xuanzx.com/Article/details/gt2uvkvurei.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.birdmap.top/Article/details/gt2cuyfsbkc.html

Go:   // 手写双层循环
来源：http://dali.hysaishi.cn/Article/details/gt2gvxxkdbg.html

Ruby: nested.flatten
来源：http://dali.ydzc1.top/Article/details/gt2oetlfxxb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.c1oappe.top/Article/details/gt2uvhuaayd.html

[D19] 按字段分组
来源：http://dali.316326.xyz/Article/details/gt2iufarijm.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.snrcjt.cn/Article/details/gt2iviwnofh.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.guowangkeji.top/Article/details/gt2uradtutc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.daxiang520.top/Article/details/gt2ilhkwfjn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.xziqi.cn/Article/details/gt2ojbrminn.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.haohaochexian.top/Article/details/gt2pcogqhqj.html

Go:   // 手写 map[string][]T
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2spheunpy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.kuanghao11.cn/Article/details/gt2sgkfmjnf.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.c1oappe.top/Article/details/gt2savnrykp.html

[D20] 统计每个元素出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gt2frgljayh.html

Py:   Counter(arr)
来源：http://dali.yvedp.cn/Article/details/gt2htqdvxfu.html

PHP:  array_count_values($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqsuyihc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gogol.net.cn/Article/details/gt2evnffdzp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj20258888.top/Article/details/gt2tyzvtmwe.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.andypj.xyz/Article/details/gt2dxynydzq.html

Go:   // 手写 map[T]int
来源：http://dali.sxryk.cn/Article/details/gt2kaygxenw.html

Ruby: arr.tally
来源：http://dali.iojbl.cn/Article/details/gt2auehctmh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yuxming.cn/Article/details/gt2zpeeawxd.html

[D21] 判断是否包含某元素
来源：http://dali.aibaodan.cn/Article/details/gt2dvnsfbht.html

Py:   x in arr
来源：http://dali.aibaodan.cn/Article/details/gt2ocxfrafs.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jianghu66.top/Article/details/gt2fhncpqzb.html

JS:   arr.includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2asqrgoxf.html

TS:   arr.includes(x)
来源：http://dali.hywenlv.cn/Article/details/gt2rqlmovzq.html

Java: list.contains(x)
来源：http://dali.shzxlz.cn/Article/details/gt2qiovybsw.html

Go:   slices.Contains(arr, x)
来源：http://dali.redwolf501.top/Article/details/gt2wburdvcl.html

Ruby: arr.include?(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmrofreb.html

C#:   list.Contains(x)
来源：http://dali.pycfn.com/Article/details/gt2crfmsswp.html

[D22] 复制数组（避免共享引用）
来源：http://dali.aibaodan.cn/Article/details/gt2wryhbzak.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2scvuosan.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.jinghuilouyu.cn/Article/details/gt2woagkkjl.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2bakzvmko.html

TS:   [...arr];
来源：http://dali.gogol.net.cn/Article/details/gt2wavboxhi.html

Java: new ArrayList<>(list);
来源：http://dali.cashguo.top/Article/details/gt2mnbxasdo.html

Go:   copied := append([]int(nil), arr...)
来源：http://dali.xuanzx.com/Article/details/gt2pjilsvhu.html

Ruby: arr.dup;  arr.clone
来源：http://dali.ivvv.top/Article/details/gt2grtgxejt.html

C#:   new List<int>(list);
来源：http://dali.zhixingplan.top/Article/details/gt2legwknyx.html

[D23] reduce 累积计算
来源：http://dali.cheryme.top/Article/details/gt2thqpbwqa.html

Py:   functools.reduce(lambda a, b: a + b, arr, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sepfhnev.html

PHP:  array_reduce($arr, fn($carry, $x) => $carry + $x, 0);
来源：http://dali.havefunace.top/Article/details/gt2ubnulnwr.html

JS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.wangdashe.top/Article/details/gt2qpwucpfk.html

TS:   arr.reduce((acc, x) => acc + x, 0)
来源：http://dali.yongpay.top/Article/details/gt2lhcroczn.html

Java: list.stream().reduce(0, Integer::sum)
来源：http://dali.gzhubu.top/Article/details/gt2ogyjyhkf.html

Go:   // 手写循环
来源：http://dali.havefunace.top/Article/details/gt2vdwsvsti.html

Ruby: arr.reduce(0) { |acc, x| acc + x };  arr.sum
来源：http://dali.jinqigfzy.top/Article/details/gt2rhpusqaf.html

C#:   list.Aggregate(0, (acc, x) => acc + x)
来源：http://dali.cashguo.top/Article/details/gt2kdehgfpi.html

[D24] 字典 / Map 基本操作
来源：http://dali.chenlongwang.top/Article/details/gt2ptossgzk.html

Py:   d["k"] = 1;  d.get("k");  "k" in d;  d.pop("k")
来源：http://dali.sxryk.cn/Article/details/gt2hvikaalp.html

PHP:  $d["k"] = 1;  $d["k"] ?? null;  isset($d["k"]);  unset($d["k"]);
来源：http://dali.yuanzhike.top/Article/details/gt2ruzbxsyu.html

JS:   obj.k = 1;  "k" in obj;  delete obj.k;  new Map().set("k", 1)
来源：http://dali.xuanzx.com/Article/details/gt2rqnyknau.html

TS:   const d: Record<string, number> = {};  d["k"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2uxzjyequ.html

Java: map.put("k", 1);  map.get("k");  map.containsKey("k");  map.remove("k")
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdyliyma.html

Go:   m := map[string]int{};  m["k"] = 1;  v, ok := m["k"];  delete(m, "k")
来源：http://dali.jyoumei.cn/Article/details/gt2ybmxfjkc.html

Ruby: h["k"] = 1;  h["k"];  h.key?("k");  h.delete("k")
来源：http://dali.jianghu66.top/Article/details/gt2kxmqsgpw.html

C#:   dict["k"] = 1;  dict.TryGetValue("k", out var v);  dict.Remove("k");
来源：http://dali.cqqwz.cn/Article/details/gt2iyfxaywq.html

[D25] Set 集合去重与交并差
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxahbrvr.html

Py:   s = {1, 2, 3};  s | {3, 4};  s & {2};  s - {1}
来源：http://dali.feifeiyinyue.top/Article/details/gt2bitgsrdz.html

PHP:  // 无原生 Set：用数组键或 SplObjectStorage 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhamnmlc.html

JS:   const s = new Set([1, 2, 3]);  s.add(4);  s.has(1);  s.delete(1)
来源：http://dali.sxryk.cn/Article/details/gt2ceuliaij.html

TS:   const s = new Set<number>([1, 2, 3]);
来源：http://dali.nwbrower.top/Article/details/gt2czhwvbyh.html

Java: var s = new HashSet<>(List.of(1, 2, 3));  s.add(4);  s.contains(1)
来源：http://dali.nanxinkj.top/Article/details/gt2eoylaoza.html

Go:   // 无原生 Set：用 map[int]struct{}
来源：http://dali.guowangkeji.top/Article/details/gt2sgmjcvoq.html

Ruby: s = Set[1, 2, 3];  s.add(4);  s.include?(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2rrxvhnbr.html

C#:   var s = new HashSet<int> { 1, 2, 3 };  s.Add(4);  s.Contains(1)
来源：http://dali.zycfv.cn/Article/details/gt2tuwsbsch.html

[D26] 数组转字符串
来源：http://dali.yj20258.top/Article/details/gt2dsbvllbh.html

Py:   ", ".join(map(str, arr))
来源：http://dali.jyoumei.cn/Article/details/gt2hdjfeuik.html

PHP:  implode(", ", $arr);
来源：http://dali.tian-w.cn/Article/details/gt2rrqvaeul.html

JS:   arr.join(", ")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbevkrpg.html

TS:   arr.join(", ")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ohhxhtlf.html

Java: String.join(", ", list)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yjpwcnff.html

Go:   strings.Join(strs, ", ")
来源：http://dali.yj202588.top/Article/details/gt2lrctlymq.html

Ruby: arr.join(", ")
来源：http://dali.guowangkeji.top/Article/details/gt2hlgsueeh.html

C#:   string.Join(", ", list)
来源：http://dali.xuanzx.com/Article/details/gt2hbbvvvec.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ciswhrnr.html

E. 字符串处理
来源：http://dali.jianghu66.top/Article/details/gt2pzuwgwdj.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jgzsksdo.html

[E01] 拼接字符串
来源：http://dali.birdmap.top/Article/details/gt2axhuekfj.html

Py:   "a" + "b";  "".join(["a", "b"])
来源：http://dali.shuidangran.top/Article/details/gt2ymzcywpp.html

PHP:  "a" . "b";  implode("", ["a", "b"]);
来源：http://dali.sweek.top/Article/details/gt2pdnuqqey.html

JS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.9152youxi.cn/Article/details/gt2vwfrhhyt.html

TS:   "a" + "b";  ["a", "b"].join("")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxajldfv.html

Java: "a" + "b";  String.join("", List.of("a", "b"))
来源：http://dali.hysaishi.cn/Article/details/gt2mkwmokjs.html

Go:   "a" + "b";  strings.Join([]string{"a", "b"}, "")
来源：http://dali.jlsjyb.cn/Article/details/gt2aiwkkkqj.html

Ruby: "a" + "b";  ["a", "b"].join
来源：http://dali.gotoacloud.top/Article/details/gt2kldctaxs.html

C#:   "a" + "b";  string.Concat("a", "b")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmardzvh.html

[E02] 重复字符串
来源：http://dali.haohaochexian.top/Article/details/gt2gduacant.html

Py:   "ab" * 3
来源：http://dali.jiagoushi.top/Article/details/gt2cgqqkill.html

PHP:  str_repeat("ab", 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hyyaqqvq.html

JS:   "ab".repeat(3)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zatcurmt.html

TS:   "ab".repeat(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2adoyczoo.html

Java: "ab".repeat(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vgeqxbej.html

Go:   strings.Repeat("ab", 3)
来源：http://dali.wangdashe.top/Article/details/gt2wuluitpl.html

Ruby: "ab" * 3
来源：http://dali.cashguo.top/Article/details/gt2pgkurlxj.html

C#:   string.Concat(Enumerable.Repeat("ab", 3))
来源：http://dali.ppjwa.cn/Article/details/gt2ppimbnbo.html

[E03] 截取子串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jzmfridl.html

Py:   s[1:4];  s[:3];  s[3:]
来源：http://dali.bjfxy.top/Article/details/gt2zoiahkcg.html

PHP:  substr($s, 1, 3);  mb_substr($s, 1, 3, "UTF-8");
来源：http://dali.zhongyouzk.top/Article/details/gt2hovkfigv.html

JS:   s.slice(1, 4);  s.substring(1, 4)
来源：http://dali.pycfn.com/Article/details/gt2ccgcbyjg.html

TS:   s.slice(1, 4)
来源：http://dali.chenlongwang.top/Article/details/gt2pgboodxy.html

Java: s.substring(1, 4)
来源：http://dali.xuanzx.com/Article/details/gt2zkavwmdi.html

Go:   s[1:4]        // 按字节；中文用 []rune(s)[1:4] 再转回 string
来源：http://dali.nwbrower.top/Article/details/gt2fxxwvxmt.html

Ruby: s[1, 3];  s[1..3]
来源：http://dali.cucudq.cn/Article/details/gt2lktlmijl.html

C#:   s.Substring(1, 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jimdbrgx.html

[E04] 查找子串位置
来源：http://dali.pycfn.com/Article/details/gt2tgfvofku.html

Py:   s.find("x");  s.index("x")
来源：http://dali.shzxlz.cn/Article/details/gt2khwkljbl.html


<!-- 参考信息 -->