代发 wailian999

Java: u instanceof User
来源：http://dali.jyoumei.cn/Article/details/gtpqjtehgt.html

Go:   u, ok := v.(User)            // 类型断言
来源：http://dali.bjfxy.top/Article/details/gtlnqxkqwu.html

Ruby: u.is_a?(User)
来源：http://dali.haohaochexian.top/Article/details/gtqmsvwiag.html

C#:   u is User
来源：http://dali.sufxvd.cn/Article/details/gtpljwcodk.html

[G14] 数据类 / record
来源：http://dali.svipenyu.cn/Article/details/gtsxmemqrd.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.shangyingyoupin.top/Article/details/gtczyairmd.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.tianlin.xyz/Article/details/gtaykwprcl.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.yongpay.top/Article/details/gtdbrnkkel.html

TS:   type User = { name: string; age: number };
来源：http://dali.iojbl.cn/Article/details/gtthtstdqt.html

Java: record User(String name, int age) {}
来源：http://dali.zhixingplan.top/Article/details/gtpaevkxza.html

Go:   type User struct { Name string; Age int }
来源：http://dali.gaohongyu789.top/Article/details/gtbmobhuqe.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.316326.xyz/Article/details/gtupulkxwf.html

C#:   record User(string Name, int Age);
来源：http://dali.jyoumei.cn/Article/details/gtwelazqfv.html

[G15] 枚举
来源：http://dali.cqqwz.cn/Article/details/gtwuzghhtl.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.gogol.net.cn/Article/details/gtsbhauwrk.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.sufxvd.cn/Article/details/gtfchpqyaw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.tian-w.cn/Article/details/gtuamvetae.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtxkykjssp.html

Java: enum Color { RED, GREEN }
来源：http://dali.xylfe.cn/Article/details/gtahgtahsv.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gtmggpujre.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhixingplan.top/Article/details/gtmvaszigr.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.yuxming.cn/Article/details/gtcsotwdvn.html

[G16] 对象转数组 / 字典
来源：http://dali.kuanghao11.cn/Article/details/gtanqrainl.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gtvowdjhbm.html

PHP:  get_object_vars($obj);
来源：http://dali.wangdashe.top/Article/details/gtozxclxtz.html

JS:   Object.entries(obj)
来源：http://dali.ybcxt.top/Article/details/gtlglegqtf.html

TS:   Object.entries(obj)
来源：http://dali.zycfv.cn/Article/details/gtrqgtkyne.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.yj202588.top/Article/details/gtizrqbpys.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.quarkkingdee.top/Article/details/gtdzziuwku.html

Ruby: obj.instance_variables
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhcgqbgm.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xuanzx.com/Article/details/gtlpzpxlxh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtgeugdrdo.html

H. 异常与错误处理
来源：http://dali.316326.xyz/Article/details/gtcucnqwuu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtwojzotvl.html

[H01] try / catch 基础
来源：http://dali.hnxiangtu.top/Article/details/gtgleissev.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.andypj.xyz/Article/details/gtacuobxtz.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxckzvhe.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.daxiang520.top/Article/details/gtwjybbqdk.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.tanke756.top/Article/details/gtsseswtmy.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.daxiang520.top/Article/details/gtmnuyjrbl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.iojbl.cn/Article/details/gtuszbunga.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.birdmap.top/Article/details/gtgkeafnoc.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.gzhubu.top/Article/details/gtiukeziya.html

[H02] finally / ensure 收尾
来源：http://dali.jinqigufen.top/Article/details/gtyjsmmyjs.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yj20258888.top/Article/details/gtezrlqagc.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gttwgftxfm.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.nwbrower.top/Article/details/gtntscntqg.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.daria6918.cn/Article/details/gthgopqbon.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.nanxinkj.top/Article/details/gtgutiyhit.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.hongshengwenyu.top/Article/details/gtpsamezrh.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.tianlin.xyz/Article/details/gtsiomblth.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.9152youxi.cn/Article/details/gtnemmnjud.html

[H03] 主动抛出异常
来源：http://dali.guowangkeji.top/Article/details/gthbardkfg.html

Py:   raise ValueError("错误信息")
来源：http://dali.jyoumei.cn/Article/details/gtcbmllrpd.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqsdbuluj.html

JS:   throw new Error("错误信息");
来源：http://dali.wangdashe.top/Article/details/gthnsxqlwr.html

TS:   throw new Error("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gtvxyawumu.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zhongyouzk.top/Article/details/gtuzvwmuho.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.aibaodan.cn/Article/details/gtbhiyqrwp.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sxryk.cn/Article/details/gtqhbbfetp.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yangfankeji.com/Article/details/gtuyjefzdm.html

[H04] 自定义异常类型
来源：http://dali.gotoacloud.top/Article/details/gtzhcgcinq.html

Py:   class MyError(Exception): pass
来源：http://dali.hammf.cn/Article/details/gtrzmfrrdk.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.9152youxi.cn/Article/details/gtndrgmfol.html

JS:   class MyError extends Error {}
来源：http://dali.chenjidiqi.icu/Article/details/gtxhwgnuwm.html

TS:   class MyError extends Error {}
来源：http://dali.ybcxt.top/Article/details/gtuosojnld.html

Java: class MyException extends RuntimeException {}
来源：http://dali.kuanghao11.cn/Article/details/gtzdthmrny.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.nwbrower.top/Article/details/gtujluowqi.html

Ruby: class MyError < StandardError; end
来源：http://dali.gzhubu.top/Article/details/gtrscldbgj.html

C#:   class MyException : Exception {}
来源：http://dali.jinqigufen.top/Article/details/gtsxmliltn.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gtyhtyolwq.html

Py:   except ValueError as e:
来源：http://dali.bjfxy.top/Article/details/gtdiuafwqy.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.yj202588.top/Article/details/gtecheqdjv.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.snrcjt.cn/Article/details/gtxifqugbm.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.jqgufenzy.top/Article/details/gtdytrkbxf.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.yanxiufei.cn/Article/details/gtmuzdcyqh.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yvedp.cn/Article/details/gtupqfexxt.html

Ruby: rescue ArgumentError => e
来源：http://dali.gotoacloud.top/Article/details/gtydynewgb.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.fzhhl.top/Article/details/gtufwbryvr.html

[H06] 可选值 / 空值安全访问
来源：http://dali.snrcjt.cn/Article/details/gtbzqdnmee.html

Py:   value = d.get("k") or default
来源：http://dali.zhiwuduotai.top/Article/details/gtgmgwukcl.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hongshengwenyu.top/Article/details/gtmzeswhmb.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.ivvv.top/Article/details/gtytencdim.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.c1oappe.top/Article/details/gtgepauziz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.shangyingyoupin.top/Article/details/gtladvzxxh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.cashguo.top/Article/details/gttysggyuk.html

Ruby: d&.dig(:a, :b)
来源：http://dali.daxiang520.top/Article/details/gtcybvycbr.html

C#:   obj?.A?.B ?? default
来源：http://dali.nanxinkj.top/Article/details/gtoiqoyzfx.html

[H07] 断言
来源：http://dali.sysykeji.top/Article/details/gtsqhfeaua.html

Py:   assert x > 0, "必须为正"
来源：http://dali.smart0.xyz/Article/details/gtiyzehnmg.html

PHP:  assert($x > 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcyvtetdu.html

JS:   console.assert(x > 0);
来源：http://dali.aizwys.cn/Article/details/gtzejwpjvn.html

TS:   console.assert(x > 0);
来源：http://dali.fzhhl.top/Article/details/gtcjnbvgvh.html

Java: assert x > 0 : "必须为正";
来源：http://dali.tanke756.top/Article/details/gtyaalykwi.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.ydzc1.top/Article/details/gtehxizkkk.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.redwolf501.top/Article/details/gtzqknxmpo.html

C#:   Debug.Assert(x > 0);
来源：http://dali.cdnleiting.top/Article/details/gtczyiexhj.html

[H08] 获取错误信息与堆栈
来源：http://dali.yanxiufei.cn/Article/details/gtrroqgayi.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.nanxuanxn.top/Article/details/gtzzujhwha.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.gotoacloud.top/Article/details/gtnaiobbuq.html

JS:   e.message;  e.stack
来源：http://dali.haohaochexian.top/Article/details/gthrnhlnhw.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.kuanghao11.cn/Article/details/gtdqesjxky.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.zhengqikj.top/Article/details/gtfxzyxnpa.html

Go:   err.Error()
来源：http://dali.yj20258.top/Article/details/gtimdfmjdt.html

Ruby: e.message;  e.backtrace
来源：http://dali.vqdsnc.cn/Article/details/gtuzejlmxi.html

C#:   e.Message;  e.StackTrace
来源：http://dali.c1oappe.top/Article/details/gtupaxsfsm.html

[H09] 带错误码的异常
来源：http://dali.cqqwz.cn/Article/details/gtxxrtylni.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.ppjwa.cn/Article/details/gtbkhwlfpl.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj202588.top/Article/details/gtgywffkvj.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.gotoacloud.top/Article/details/gtutdpyvma.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.pycfn.com/Article/details/gtrcqvyann.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yvedp.cn/Article/details/gtwcbfepkv.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.aizwys.cn/Article/details/gtrwazvzdu.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.cheryme.top/Article/details/gtoddrwqch.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.yonumen.top/Article/details/gtvpascfde.html

[H10] 资源自动释放
来源：http://dali.pycfn.com/Article/details/gtbxoihant.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.jianghu66.top/Article/details/gtgrrcanqx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.gzhubu.top/Article/details/gtshyznold.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.zhiwuduotai.top/Article/details/gtmergvzfp.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xinyue.icu/Article/details/gtzgaebcyg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.wangshuangyany.cn/Article/details/gtzvcpzwws.html

Go:   defer f.Close()
来源：http://dali.wangdashe.top/Article/details/gtrrhzpetg.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.sweek.top/Article/details/gtqmxhrxvt.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.gzhubu.top/Article/details/gtmdzqapzt.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmjjjqklt.html

I. 正则表达式
来源：http://dali.yanxiufei.cn/Article/details/gtmaqpkawz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxqkffwq.html

[I01] 判断是否匹配
来源：http://dali.jianghu66.top/Article/details/gtvrrmdnky.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.shangyingyoupin.top/Article/details/gtltbfduwf.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.kuanghao11.cn/Article/details/gtiuacetwv.html

JS:   /\d+/.test(s)
来源：http://dali.jianghu66.top/Article/details/gtvzgbkpcu.html

TS:   /\d+/.test(s)
来源：http://dali.xylfe.cn/Article/details/gtucmrxpyo.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gzhubu.top/Article/details/gtlxbsbbrl.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtnczsntdc.html

Ruby: s.match?(/\d+/)
来源：http://dali.jiagoushi.top/Article/details/gtfmlkeqmf.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.cdnleiting.top/Article/details/gtmbzszxks.html

[I02] 提取所有匹配
来源：http://dali.jinqigufen.top/Article/details/gtqzchfzbs.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gtskjzdqzb.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.xuanzx.com/Article/details/gtgkdscasy.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yonumen.top/Article/details/gttnefmxim.html

TS:   s.match(/\d+/g)
来源：http://dali.zhiwuduotai.top/Article/details/gtflibdtgq.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtlhglxwht.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.jlsjyb.cn/Article/details/gtahiydbbk.html

Ruby: s.scan(/\d+/)
来源：http://dali.birdmap.top/Article/details/gtnyedkxcr.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.daxiang520.top/Article/details/gtcmolnlnk.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gtwslucfjr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.nanxinkj.top/Article/details/gtqyziofie.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjewmsctu.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.fzhhl.top/Article/details/gtvrukmwzm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gtgzkbxjow.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.zhiwuduotai.top/Article/details/gtjyecxljt.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.feifeiyinyue.top/Article/details/gtnrnqqexs.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.fzhhl.top/Article/details/gtvkrowrnv.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.ybcxt.top/Article/details/gtrwlytomi.html

[I04] 正则替换
来源：http://dali.aizwys.cn/Article/details/gtkybyxpwj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.cashguo.top/Article/details/gtenihbidb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgfzy.top/Article/details/gtoxzjftow.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.jinqigfzy.top/Article/details/gtgdnjlxdq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.gogol.net.cn/Article/details/gtjwavyrth.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.chenzaomai.com/Article/details/gtjuvmhfil.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.shuidangran.top/Article/details/gtyafufvun.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.andypj.xyz/Article/details/gtvdeyugtu.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.yvedp.cn/Article/details/gthbfipmsq.html

[I05] 按正则拆分
来源：http://dali.zhijiandao.cn/Article/details/gtwefonrci.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.shuidangran.top/Article/details/gtvmsjgedx.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.chenlongwang.top/Article/details/gtutbrylhz.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.vqdsnc.cn/Article/details/gtnfqdkqrx.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.zdqjudy.top/Article/details/gtbrgxsjox.html

Java: s.split("\\s*,\\s*")
来源：http://dali.andypj.xyz/Article/details/gtiwenttwv.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.cqqwz.cn/Article/details/gttaazwupa.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzradfzy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.yj20258.top/Article/details/gtfspsffqa.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.aibaodan.cn/Article/details/gtkqkwexvn.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gtarhqanwb.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.birdmap.top/Article/details/gtqyreknqm.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenzaomai.com/Article/details/gtefuylima.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.chenlongwang.top/Article/details/gtdcbyehug.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.0kj1m.cn/Article/details/gtcjiwwzrk.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.xinyue.icu/Article/details/gthcbzrjhg.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.fengsongda.top/Article/details/gtzyfyskzk.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.tanke756.top/Article/details/gtcjkgexmi.html

[I07] 忽略大小写与多行模式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnbbpryr.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.aizwys.cn/Article/details/gteslmjwbd.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.vqdsnc.cn/Article/details/gtnognvzpc.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.nwbrower.top/Article/details/gtdykwdmna.html

TS:   /error/gim
来源：http://dali.dashuyun.cn/Article/details/gtauvjhofi.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.bjfxy.top/Article/details/gtaubrjekp.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.pengpengdd.cyou/Article/details/gtcmqpyphc.html

Ruby: s.scan(/error/i)
来源：http://dali.yanxiufei.cn/Article/details/gtkpxwqybq.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.yonumen.top/Article/details/gtzyctkvcd.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.zhijiandao.cn/Article/details/gtqvmxarrx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsugivus.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.xuanzx.com/Article/details/gtuxrvozcy.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.snrcjt.cn/Article/details/gtskrnavny.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tianlin.xyz/Article/details/gtojfecyhu.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.andypj.xyz/Article/details/gtppnmtujf.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.sxryk.cn/Article/details/gtayddfnft.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yj202588.top/Article/details/gtdbletncg.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.nanxinkj.top/Article/details/gthzqorzox.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gthtnpkfrh.html

J. 日期与时间
来源：http://dali.nanxinkj.top/Article/details/gtbgwfiolt.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtsiumbmhz.html

[J01] 获取当前时间
来源：http://dali.gotoacloud.top/Article/details/gtddhdqykc.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.bjfxy.top/Article/details/gtgyykweoq.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.nanxinkj.top/Article/details/gtiamjlphu.html

JS:   new Date();  Date.now()
来源：http://dali.gzhubu.top/Article/details/gthsjlglxt.html

TS:   new Date();  Date.now()
来源：http://dali.zhixingplan.top/Article/details/gtggpcbnqs.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.wangshuangyany.cn/Article/details/gtqhnuhrzw.html

Go:   time.Now()
来源：http://dali.jqgufenzy.top/Article/details/gtuojyqflb.html

Ruby: Time.now
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbchotyvh.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.hfpthk.cn/Article/details/gthuoyvoea.html

[J02] 格式化输出
来源：http://dali.yj202588.top/Article/details/gtodlzwjgr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.9152youxi.cn/Article/details/gtovsqigvi.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.aibaodan.cn/Article/details/gtliqwiqiy.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.xuetiantiany.cn/Article/details/gtnxehjfbl.html

TS:   d.toISOString()
来源：http://dali.zhengqikj.top/Article/details/gtjyfqicaq.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.cucudq.cn/Article/details/gtdgxungky.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.havefunace.top/Article/details/gtjgrjpvqq.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.bjfxy.top/Article/details/gtxlpayifm.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.chenlongwang.top/Article/details/gtvpywyguo.html

[J03] 字符串解析为日期
来源：http://dali.haohaochexian.top/Article/details/gtosmykoic.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.fengsongda.top/Article/details/gtblfhrqgv.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.xylfe.cn/Article/details/gtbygpmzrj.html

JS:   new Date("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtbjawhaec.html

TS:   new Date("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gtxjbeguru.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.ivvv.top/Article/details/gtnzmgbxhb.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.cqqwz.cn/Article/details/gtphtyvpgr.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.hongshengwenyu.top/Article/details/gthflwypxb.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.quarkkingdee.top/Article/details/gtxdfkciex.html

[J04] 时间戳与日期互转
来源：http://dali.meibo888.top/Article/details/gtkmhadqhc.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.pycfn.com/Article/details/gtvwazffja.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.gaohongyu789.top/Article/details/gtjeufevdt.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.pengpengdd.cyou/Article/details/gthmrlihje.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.sufxvd.cn/Article/details/gtvscthyci.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.xuanzx.com/Article/details/gtdujactju.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.dianchejie.cn/Article/details/gtahbixdcm.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygtwmiiq.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.shangyingyoupin.top/Article/details/gtjvtkxaay.html

[J05] 时间加减（加 7 天）
来源：http://dali.yueranfly.top/Article/details/gtezzpjjnf.html

Py:   now + timedelta(days=7)
来源：http://dali.zhiwuduotai.top/Article/details/gtrhywrrct.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yonumen.top/Article/details/gtjimyrnaa.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cqqwz.cn/Article/details/gtobovrcdz.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.pycfn.com/Article/details/gtmpkkycfm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gtdfibyksj.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinqigufen.top/Article/details/gthzusaqyb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.fzhhl.top/Article/details/gtjnelknqe.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.hnqzz.top/Article/details/gtzuuypdty.html

[J06] 计算两时间之差
来源：http://dali.xylfe.cn/Article/details/gtsfmytafw.html

Py:   (end - start).total_seconds()
来源：http://dali.quarkkingdee.top/Article/details/gtxcyntojz.html

PHP:  $end->diff($start)->days;
来源：http://dali.birdmap.top/Article/details/gthmecoexl.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ehwqpu.com/Article/details/gttfrzkfux.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.nanxuanxn.top/Article/details/gtkpgjptur.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.zhiwuduotai.top/Article/details/gtbiziwpru.html

Go:   end.Sub(start).Hours()
来源：http://dali.pengpengdd.cyou/Article/details/gtyvzipjdy.html

Ruby: end - start                 # 返回秒数
来源：http://dali.gzhubu.top/Article/details/gtzkxblgqy.html

C#:   (end - start).TotalSeconds
来源：http://dali.yanxiufei.cn/Article/details/gtsimrubsf.html

[J07] 比较两个日期
来源：http://dali.xinyue.icu/Article/details/gtfdbldwjb.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sufxvd.cn/Article/details/gtqtcgfnjj.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.daria6918.cn/Article/details/gtvipxlpol.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.pengpengdd.cyou/Article/details/gtpbaikaya.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.jinqigufen.top/Article/details/gthoktlvpl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.jqgufenzy.top/Article/details/gtinhoizzk.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.shangyingyoupin.top/Article/details/gtvysfkhyt.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.gzhubu.top/Article/details/gtxpqbtrwu.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.jinqigufen.top/Article/details/gtiuvpgmtt.html

[J08] 提取年月日与星期
来源：http://dali.ivvv.top/Article/details/gtveqrxsat.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gtapihpbdo.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.yuanzhike.top/Article/details/gtjcpqhyom.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.316326.xyz/Article/details/gthhmpvofb.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.havefunace.top/Article/details/gtldwbngne.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.ppjwa.cn/Article/details/gtslrawreo.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.havefunace.top/Article/details/gtxlprbouq.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.316326.xyz/Article/details/gtowtqahgo.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.tanke756.top/Article/details/gtjimypxib.html

[J09] 时区处理
来源：http://dali.hysaishi.cn/Article/details/gtxnleiaqi.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.smart0.xyz/Article/details/gtjqxwsxqo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.ppjwa.cn/Article/details/gtwrloomtw.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.wangshuangyany.cn/Article/details/gtnbwtlclu.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.daria6918.cn/Article/details/gtbomrdvoh.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.havefunace.top/Article/details/gtdtmxgiwc.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.mhx1999.top/Article/details/gtyceexpak.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.yvedp.cn/Article/details/gtgjjfhgre.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.wangdashe.top/Article/details/gthbhdwqng.html

[J10] 取今天 / 本月第一天
来源：http://dali.sufxvd.cn/Article/details/gtqilyhusl.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmieorzi.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gtgaabhjwt.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.quarkkingdee.top/Article/details/gthjbrujth.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.yuxming.cn/Article/details/gtxpbdqwdb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.smart0.xyz/Article/details/gtnztjteun.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.pengpengdd.cyou/Article/details/gtzfrkgckg.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.havefunace.top/Article/details/gtdfkpnhdh.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.yj20258888.top/Article/details/gtvfbmxrew.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtwdskltoi.html

K. JSON 与序列化
来源：http://dali.shzxlz.cn/Article/details/gtvyzdihbm.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzupllaag.html

[K01] 对象转 JSON 字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnxuiukt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.shuidangran.top/Article/details/gtzhbhtzus.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.sweek.top/Article/details/gtzhyebjhg.html

JS:   JSON.stringify(obj)
来源：http://dali.mhx1999.top/Article/details/gtjetjhfun.html

TS:   JSON.stringify(obj)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthgpjmvab.html


<!-- 参考信息 -->