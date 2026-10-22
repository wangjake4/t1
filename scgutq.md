代发 wailian999

[G14] 数据类 / record
来源：http://dali.snrcjt.cn/Article/details/gtgjnonihz.html

Py:   @dataclass⏎class User: name: str; age: int
来源：http://dali.guowangkeji.top/Article/details/gtolqsomom.html

PHP:  // 用 readonly 属性模拟
来源：http://dali.zhijiandao.cn/Article/details/gtiwgbyjey.html

JS:   // 无内置：普通类或对象字面量
来源：http://dali.chenjidiqi.icu/Article/details/gtcdybtsgw.html

TS:   type User = { name: string; age: number };
来源：http://dali.zhiwuduotai.top/Article/details/gttnpyckjj.html

Java: record User(String name, int age) {}
来源：http://dali.yonumen.top/Article/details/gtcsaixkhk.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xylfe.cn/Article/details/gtscyfyxcy.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.chenlongwang.top/Article/details/gtboqoxupg.html

C#:   record User(string Name, int Age);
来源：http://dali.sysykeji.top/Article/details/gthrktfczy.html

[G15] 枚举
来源：http://dali.quarkkingdee.top/Article/details/gtsqkrcmjb.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.shzxlz.cn/Article/details/gtpdujamuh.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.fzhhl.top/Article/details/gtcweoqqop.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.9152youxi.cn/Article/details/gtcrkuhnky.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.tianlin.xyz/Article/details/gtxtlolcle.html

Java: enum Color { RED, GREEN }
来源：http://dali.zhixingplan.top/Article/details/gttpcbcflp.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yuxming.cn/Article/details/gtvqumawza.html

Ruby: Color = %i[red green].freeze
来源：http://dali.iojbl.cn/Article/details/gtujhbbbiu.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jianghu66.top/Article/details/gtlhehkzpx.html

[G16] 对象转数组 / 字典
来源：http://dali.ivvv.top/Article/details/gthufyireq.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.ybcxt.top/Article/details/gtcwprzhmw.html

PHP:  get_object_vars($obj);
来源：http://dali.yj20258.top/Article/details/gtbhqztgaw.html

JS:   Object.entries(obj)
来源：http://dali.birdmap.top/Article/details/gtvqwspeln.html

TS:   Object.entries(obj)
来源：http://dali.yongpay.top/Article/details/gtnivrxjsb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.xziqi.cn/Article/details/gtkvztvrmn.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.meibo888.top/Article/details/gtqxwehjro.html

Ruby: obj.instance_variables
来源：http://dali.snrcjt.cn/Article/details/gtubxcdboj.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.cheryme.top/Article/details/gtbmibonfz.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtbrexsrkq.html

H. 异常与错误处理
来源：http://dali.yueranfly.top/Article/details/gttcybnvcu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzftruttd.html

[H01] try / catch 基础
来源：http://dali.yj202588.top/Article/details/gtqtgctyav.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.quarkkingdee.top/Article/details/gtwsnlfgoc.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.jqgufenzy.top/Article/details/gtczvsbrkd.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.feifeiyinyue.top/Article/details/gtmivsbujz.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.xuanzx.com/Article/details/gtapmwboef.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.cqqwz.cn/Article/details/gtkiufmfuz.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.tanke756.top/Article/details/gtsebmtyrq.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.jinqigfzy.top/Article/details/gtdpoxykuy.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.zhixingplan.top/Article/details/gttbprefqm.html

[H02] finally / ensure 收尾
来源：http://dali.gogol.net.cn/Article/details/gtivlixidb.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.tian-w.cn/Article/details/gtcrgjsbeq.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jlsjyb.cn/Article/details/gtvekchjjr.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.mhx1999.top/Article/details/gtkfvizjca.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.vqdsnc.cn/Article/details/gtzczpcauw.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gtcnsnoxnh.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.nanxuanxn.top/Article/details/gtczxsotyr.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.yanxiufei.cn/Article/details/gtrtfwqfwf.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.redwolf501.top/Article/details/gtzfenfdxv.html

[H03] 主动抛出异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgidrjid.html

Py:   raise ValueError("错误信息")
来源：http://dali.ydzc1.top/Article/details/gtptsuhisj.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.fzhhl.top/Article/details/gtanfugbsf.html

JS:   throw new Error("错误信息");
来源：http://dali.svipenyu.cn/Article/details/gtzrvgualv.html

TS:   throw new Error("错误信息");
来源：http://dali.ydzc1.top/Article/details/gthsbxbdcm.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.yuxming.cn/Article/details/gtmugnbpeq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfojnnbtu.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.iojbl.cn/Article/details/gtkabozjsl.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.gogol.net.cn/Article/details/gtsehzhier.html

[H04] 自定义异常类型
来源：http://dali.bjfxy.top/Article/details/gtxeugtsfe.html

Py:   class MyError(Exception): pass
来源：http://dali.nanxuanxn.top/Article/details/gtwzpfashg.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gtzefhyboy.html

JS:   class MyError extends Error {}
来源：http://dali.haohaochexian.top/Article/details/gtcjgbjoso.html

TS:   class MyError extends Error {}
来源：http://dali.yangfankeji.com/Article/details/gtelbzxvhv.html

Java: class MyException extends RuntimeException {}
来源：http://dali.cheryme.top/Article/details/gtmfixnxub.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.feifeiyinyue.top/Article/details/gttglolcus.html

Ruby: class MyError < StandardError; end
来源：http://dali.c1oappe.top/Article/details/gtvpptjiqp.html

C#:   class MyException : Exception {}
来源：http://dali.dianchejie.cn/Article/details/gthurwcmvt.html

[H05] 捕获特定类型
来源：http://dali.sysykeji.top/Article/details/gtoftndnjq.html

Py:   except ValueError as e:
来源：http://dali.ppjwa.cn/Article/details/gtestpucsx.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.xuanzx.com/Article/details/gtnzqhzrcx.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtqjhccrar.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.tian-w.cn/Article/details/gtpizfcrrc.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.gzhubu.top/Article/details/gtntulgwbx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.redwolf501.top/Article/details/gtwikbiytx.html

Ruby: rescue ArgumentError => e
来源：http://dali.hfpthk.cn/Article/details/gtvvutkisx.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.daxiang520.top/Article/details/gtjklqbasx.html

[H06] 可选值 / 空值安全访问
来源：http://dali.sysykeji.top/Article/details/gtcsqizkbf.html

Py:   value = d.get("k") or default
来源：http://dali.zhengqikj.top/Article/details/gtnwlbfnrw.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.shuidangran.top/Article/details/gtwfmgzunm.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gtejohqzzk.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.smart0.xyz/Article/details/gtuoqvvhkz.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.xziqi.cn/Article/details/gtbbfvvpjc.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.zhijiandao.cn/Article/details/gtdtaeixeh.html

Ruby: d&.dig(:a, :b)
来源：http://dali.zhixingplan.top/Article/details/gtpyyjddaa.html

C#:   obj?.A?.B ?? default
来源：http://dali.andypj.xyz/Article/details/gtcvxzsyys.html

[H07] 断言
来源：http://dali.ybcxt.top/Article/details/gtznjyzuil.html

Py:   assert x > 0, "必须为正"
来源：http://dali.chenlongwang.top/Article/details/gtudhwaanb.html

PHP:  assert($x > 0);
来源：http://dali.hywenlv.cn/Article/details/gtkmhkziji.html

JS:   console.assert(x > 0);
来源：http://dali.yongpay.top/Article/details/gtfilpgraf.html

TS:   console.assert(x > 0);
来源：http://dali.jyoumei.cn/Article/details/gtjohpievq.html

Java: assert x > 0 : "必须为正";
来源：http://dali.gzhubu.top/Article/details/gtfstflxpt.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.gzhubu.top/Article/details/gtmthxlcif.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hammf.cn/Article/details/gtejmgwqas.html

C#:   Debug.Assert(x > 0);
来源：http://dali.aibaodan.cn/Article/details/gtzbxyavhh.html

[H08] 获取错误信息与堆栈
来源：http://dali.xuanzx.com/Article/details/gtrnvlzjni.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.yj20258888.top/Article/details/gtedwzixri.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.ivvv.top/Article/details/gtldsvbewz.html

JS:   e.message;  e.stack
来源：http://dali.haohaochexian.top/Article/details/gtozpslqin.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ybcxt.top/Article/details/gtwjgsfavw.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.wangdashe.top/Article/details/gtpikhyfbj.html

Go:   err.Error()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrkbjvew.html

Ruby: e.message;  e.backtrace
来源：http://dali.ybcxt.top/Article/details/gtyeeaipao.html

C#:   e.Message;  e.StackTrace
来源：http://dali.andypj.xyz/Article/details/gtoafxsxrb.html

[H09] 带错误码的异常
来源：http://dali.tianlin.xyz/Article/details/gtsjfoootg.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yuxming.cn/Article/details/gtdlrhdflm.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yj20258888.top/Article/details/gthdjagbhq.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cdnleiting.top/Article/details/gtwbaifjaz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.yj20258.top/Article/details/gtefegbonk.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yanxiufei.cn/Article/details/gtqzqyhslq.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.nanxinkj.top/Article/details/gtbesejsqi.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.gotoacloud.top/Article/details/gtwwbtcfrv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.gotoacloud.top/Article/details/gtpmvbmftf.html

[H10] 资源自动释放
来源：http://dali.bjfxy.top/Article/details/gtuiyngnrk.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.vqdsnc.cn/Article/details/gtnyytkszh.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.yvedp.cn/Article/details/gthmxtntgg.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.feifeiyinyue.top/Article/details/gtrqcgrrsl.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.hnqzz.top/Article/details/gtcvzrgtmn.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.chenlongwang.top/Article/details/gtqdwtrdtq.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopveubkw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.jinqigfzy.top/Article/details/gtnmzwycxy.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.316326.xyz/Article/details/gtshngxjbg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtxymcfyyb.html

I. 正则表达式
来源：http://dali.zhengqikj.top/Article/details/gtsrkcmxzl.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtyaxhrgar.html

[I01] 判断是否匹配
来源：http://dali.c1oappe.top/Article/details/gtvtvzhcez.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.ivvv.top/Article/details/gtolepatyl.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.dashuyun.cn/Article/details/gttzxwxigo.html

JS:   /\d+/.test(s)
来源：http://dali.gotoacloud.top/Article/details/gtfpbyzktu.html

TS:   /\d+/.test(s)
来源：http://dali.ehwqpu.com/Article/details/gtskrxgnlg.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.hnxiangtu.top/Article/details/gtzkcoyftm.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.tanke756.top/Article/details/gtcaeygpqb.html

Ruby: s.match?(/\d+/)
来源：http://dali.9152youxi.cn/Article/details/gtbkvlnako.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.iojbl.cn/Article/details/gtmobstelp.html

[I02] 提取所有匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbjvbgyf.html

Py:   re.findall(r"\d+", s)
来源：http://dali.zycfv.cn/Article/details/gtnxbvgenj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aizwys.cn/Article/details/gtuhexxhst.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.yanxiufei.cn/Article/details/gthjjxrwve.html

TS:   s.match(/\d+/g)
来源：http://dali.yvedp.cn/Article/details/gtnuexbnbi.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.yj20258888.top/Article/details/gtnyqhhtyk.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.nanxinkj.top/Article/details/gtbqhjjazo.html

Ruby: s.scan(/\d+/)
来源：http://dali.gogol.net.cn/Article/details/gtrvripetl.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtrcluefzm.html

[I03] 提取捕获分组
来源：http://dali.cdnleiting.top/Article/details/gtkatrwwzw.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.yangfankeji.com/Article/details/gtnkidbvzz.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.gaohongyu789.top/Article/details/gtjllvwtfi.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.xuanzx.com/Article/details/gtuqkhjgyo.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbontbra.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.bjfxy.top/Article/details/gtqfywcdko.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jqgufenzy.top/Article/details/gtjwyxasgd.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.gzhubu.top/Article/details/gtntahlezi.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.gotoacloud.top/Article/details/gtprqxcycp.html

[I04] 正则替换
来源：http://dali.birdmap.top/Article/details/gtbodwdzmf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.yuxming.cn/Article/details/gtkmzuepcr.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gtsrwqujti.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yueranfly.top/Article/details/gtucfzszph.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.hywenlv.cn/Article/details/gtukoiespj.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.gogol.net.cn/Article/details/gtyghskuhw.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.hysaishi.cn/Article/details/gtxamdivns.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinghuilouyu.cn/Article/details/gtukrzqozm.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.tian-w.cn/Article/details/gtnecijudh.html

[I05] 按正则拆分
来源：http://dali.xziqi.cn/Article/details/gtnbikeuxv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.xuetiantiany.cn/Article/details/gttnmukead.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.haohaochexian.top/Article/details/gtucdpvnfp.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.tianlin.xyz/Article/details/gtcmoyahpg.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.wangdashe.top/Article/details/gtgfxjrsqd.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zhongyouzk.top/Article/details/gtettmgdyr.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.0kj1m.cn/Article/details/gtlsbzkzaq.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.nanxuanxn.top/Article/details/gtruhdvlav.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfdrrins.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.pycfn.com/Article/details/gtqbzkrjnl.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.pengpengdd.cyou/Article/details/gtzjdvjlhv.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.cdnleiting.top/Article/details/gtdrmtwgrt.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxinkj.top/Article/details/gtvpmigxko.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldieksdz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.hnxiangtu.top/Article/details/gtvosxkuxn.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.gotoacloud.top/Article/details/gtdolcqkul.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.andypj.xyz/Article/details/gtwpnkwfpj.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.iojbl.cn/Article/details/gtqmjokuhj.html

[I07] 忽略大小写与多行模式
来源：http://dali.wangshuangyany.cn/Article/details/gtigadrhyd.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.tanke756.top/Article/details/gtlovpxwfy.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.havefunace.top/Article/details/gtprbxndns.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.feifeiyinyue.top/Article/details/gtdjfqizru.html

TS:   /error/gim
来源：http://dali.yanxiufei.cn/Article/details/gtytkqhatv.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.hammf.cn/Article/details/gtnpddmyei.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.hammf.cn/Article/details/gthlnqkwwn.html

Ruby: s.scan(/error/i)
来源：http://dali.jianghu66.top/Article/details/gtzjtbaosk.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.cdnleiting.top/Article/details/gtrdgvczla.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jqgfzy.top/Article/details/gtmjffckxl.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.yuanzhike.top/Article/details/gttduckliz.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtugzekkjz.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.tanke756.top/Article/details/gtmgxuquwv.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gtkoprdtji.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.jyoumei.cn/Article/details/gthvlxvnwa.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yanxiufei.cn/Article/details/gtltnxzebp.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.yuxming.cn/Article/details/gtthjcwwkj.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cucudq.cn/Article/details/gtyfogculz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtwsqcnrqq.html

J. 日期与时间
来源：http://dali.pycfn.com/Article/details/gtpzgaofhy.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gthltwqmql.html

[J01] 获取当前时间
来源：http://dali.ehwqpu.com/Article/details/gtomjiiwhj.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.gaohongyu789.top/Article/details/gtuscnrljz.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.aizwys.cn/Article/details/gtymkwsgvg.html

JS:   new Date();  Date.now()
来源：http://dali.9152youxi.cn/Article/details/gttgjeoxnm.html

TS:   new Date();  Date.now()
来源：http://dali.yuanzhike.top/Article/details/gtsyldcett.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yuxming.cn/Article/details/gtpesnhrur.html

Go:   time.Now()
来源：http://dali.smart0.xyz/Article/details/gtuznsyika.html

Ruby: Time.now
来源：http://dali.xylfe.cn/Article/details/gtihsirtct.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jlsjyb.cn/Article/details/gtmgokqoay.html

[J02] 格式化输出
来源：http://dali.nanxinkj.top/Article/details/gtqbwshkoe.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.0kj1m.cn/Article/details/gtkfvkvxka.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.shangyingyoupin.top/Article/details/gtbolomndj.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.zhixingplan.top/Article/details/gtcbubdzad.html

TS:   d.toISOString()
来源：http://dali.svipenyu.cn/Article/details/gtwwdbsgho.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.hnqzz.top/Article/details/gtgepimnsj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.jlsjyb.cn/Article/details/gtrrehdspx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.ydzc1.top/Article/details/gtlvcpyjyt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.meibo888.top/Article/details/gtmfeqoaux.html

[J03] 字符串解析为日期
来源：http://dali.9152youxi.cn/Article/details/gtkeokkctd.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.gaohongyu789.top/Article/details/gtvceavaga.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.zycfv.cn/Article/details/gtevhelhbb.html

JS:   new Date("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gtoqdtmdce.html

TS:   new Date("2024-01-02")
来源：http://dali.zycfv.cn/Article/details/gtdmexeeky.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.9152youxi.cn/Article/details/gtpafrzzqj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.zdqjudy.top/Article/details/gtmvnjqouy.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gtheghzoas.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.chenzaomai.com/Article/details/gtvjzxbmdy.html

[J04] 时间戳与日期互转
来源：http://dali.svipenyu.cn/Article/details/gtvqqcupiv.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.yvedp.cn/Article/details/gtlcnbvoea.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.nwbrower.top/Article/details/gtevcsjquk.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yonumen.top/Article/details/gtprdyvdoz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.jinqigfzy.top/Article/details/gtvrcltkrz.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.shuidangran.top/Article/details/gtijnokiuu.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cheryme.top/Article/details/gtgvvgmosb.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.pengpengdd.cyou/Article/details/gtigyshpxw.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.snrcjt.cn/Article/details/gteodsfhgr.html

[J05] 时间加减（加 7 天）
来源：http://dali.fengsongda.top/Article/details/gtoahgnovv.html

Py:   now + timedelta(days=7)
来源：http://dali.xuetiantiany.cn/Article/details/gtdmpiqrig.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yj20258888.top/Article/details/gtyjgiopdq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.zycfv.cn/Article/details/gtuevxxpda.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cucudq.cn/Article/details/gtuvbnakkb.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.meibo888.top/Article/details/gtwhvqtrhm.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbwetnbf.html

Ruby: Time.now + 7 * 86400
来源：http://dali.hnqzz.top/Article/details/gturgyweal.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yuxming.cn/Article/details/gtiojtppnt.html

[J06] 计算两时间之差
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzcqhfsj.html

Py:   (end - start).total_seconds()
来源：http://dali.yj20258888.top/Article/details/gteooybazl.html

PHP:  $end->diff($start)->days;
来源：http://dali.jqgfzy.top/Article/details/gtsqficfhp.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.yj20258888.top/Article/details/gtznqlxaht.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.yangfankeji.com/Article/details/gtdmnnfdtt.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.hfpthk.cn/Article/details/gtlqqwycjp.html

Go:   end.Sub(start).Hours()
来源：http://dali.yonumen.top/Article/details/gtltkzttrc.html

Ruby: end - start                 # 返回秒数
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzidnhcg.html

C#:   (end - start).TotalSeconds
来源：http://dali.hnxiangtu.top/Article/details/gtwggmaxsu.html

[J07] 比较两个日期
来源：http://dali.nanxinkj.top/Article/details/gtudosnvuc.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.0kj1m.cn/Article/details/gtztkioocz.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.pycfn.com/Article/details/gtgfrvsyqt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.gaohongyu789.top/Article/details/gtznzpxrwq.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.zhiwuduotai.top/Article/details/gtdbihboae.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hnqzz.top/Article/details/gtgcqggnxy.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yvedp.cn/Article/details/gtyhyercvx.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.xylfe.cn/Article/details/gtxmhgvfeg.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.hywenlv.cn/Article/details/gtntprgavx.html

[J08] 提取年月日与星期
来源：http://dali.guowangkeji.top/Article/details/gttykiupcm.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.cqqwz.cn/Article/details/gtfkqxnixs.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.zhiwuduotai.top/Article/details/gtejptttov.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.mhx1999.top/Article/details/gtelnohjgp.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.zhengqikj.top/Article/details/gtilmrkpks.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.kuanghao11.cn/Article/details/gtrzwunvyf.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.cdnleiting.top/Article/details/gtywswkptn.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.shuidangran.top/Article/details/gtaijodqce.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.cucudq.cn/Article/details/gtuwnxnjcw.html

[J09] 时区处理
来源：http://dali.dashuyun.cn/Article/details/gtjlalytkh.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.gaohongyu789.top/Article/details/gtajymeesz.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.aizwys.cn/Article/details/gtipneqewj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.gzhubu.top/Article/details/gtwnifggdr.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.zhixingplan.top/Article/details/gtzrovqqta.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.hnxiangtu.top/Article/details/gtemendqvn.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.yj20258.top/Article/details/gtgzjlxnkn.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.xuanzx.com/Article/details/gtwphyfibi.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.ydzc1.top/Article/details/gtyxwxubev.html

[J10] 取今天 / 本月第一天
来源：http://dali.zhixingplan.top/Article/details/gtflxsrdsk.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.yj202588.top/Article/details/gtjweitvtg.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jiagoushi.top/Article/details/gttuhnzrre.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.cashguo.top/Article/details/gtxcwqrsxu.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtnoyyrazb.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.andypj.xyz/Article/details/gtuvejyuyi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.zhengqikj.top/Article/details/gtnbnuafak.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.jqgfzy.top/Article/details/gtzqpugjwg.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.guannengcc.top/Article/details/gtopbxrewp.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtzzksxofx.html

K. JSON 与序列化
来源：http://dali.yj20258888.top/Article/details/gtemtftlaa.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtvjydqnms.html

[K01] 对象转 JSON 字符串
来源：http://dali.kuanghao11.cn/Article/details/gtjotymlkt.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.iojbl.cn/Article/details/gtumcjbfqi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.nwbrower.top/Article/details/gtdkgooxtz.html

JS:   JSON.stringify(obj)
来源：http://dali.cheryme.top/Article/details/gtfpfzhlwz.html

TS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gtxftxgigz.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.cheryme.top/Article/details/gtmgigsnrk.html

Go:   json.Marshal(obj)
来源：http://dali.shangyingyoupin.top/Article/details/gtztmkents.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.haohaochexian.top/Article/details/gtqhebemwh.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.cashguo.top/Article/details/gtczkefexs.html


<!-- 参考信息 -->