代发 wailian999

TS:   type User = { name: string; age: number };
来源：http://dali.pengpengdd.cyou/Article/details/gt2qocuicbz.html

Java: record User(String name, int age) {}
来源：http://dali.9152youxi.cn/Article/details/gt2tfudqmej.html

Go:   type User struct { Name string; Age int }
来源：http://dali.xinyue.icu/Article/details/gt2uuuqrtgc.html

Ruby: User = Struct.new(:name, :age)   # 或 Ruby 3.2+ 的 Data.define
来源：http://dali.xuanzx.com/Article/details/gt2bigqxocz.html

C#:   record User(string Name, int Age);
来源：http://dali.sxryk.cn/Article/details/gt2gvjrczhl.html

[G15] 枚举
来源：http://dali.hnqzz.top/Article/details/gt2hmpmpyin.html

Py:   from enum import Enum;  class Color(Enum): RED = 1
来源：http://dali.guannengcc.top/Article/details/gt2dpxopsue.html

PHP:  enum Color: string { case Red = "red"; }
来源：http://dali.iojbl.cn/Article/details/gt2pwjlfdrw.html

JS:   const Color = Object.freeze({ RED: 1, GREEN: 2 });
来源：http://dali.316326.xyz/Article/details/gt2kzuxduju.html

TS:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nwbrower.top/Article/details/gt2donagmlc.html

Java: enum Color { RED, GREEN }
来源：http://dali.xinyue.icu/Article/details/gt2penyhvup.html

Go:   type Color int;  const (Red Color = iota; Green)
来源：http://dali.yongpay.top/Article/details/gt2mrbwouhr.html

Ruby: Color = %i[red green].freeze
来源：http://dali.zhongyouzk.top/Article/details/gt2ypzcbzil.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.jqgfzy.top/Article/details/gt2tqgzkevx.html

[G16] 对象转数组 / 字典
来源：http://dali.xuanzx.com/Article/details/gt2dgxskfzm.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.sweek.top/Article/details/gt2viriwuam.html

PHP:  get_object_vars($obj);
来源：http://dali.ivvv.top/Article/details/gt2ipaajlbt.html

JS:   Object.entries(obj)
来源：http://dali.cucudq.cn/Article/details/gt2wmybzosb.html

TS:   Object.entries(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2pbckdvxb.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.aibaodan.cn/Article/details/gt2wroufuju.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.guowangkeji.top/Article/details/gt2kwfnucwg.html

Ruby: obj.instance_variables
来源：http://dali.gogol.net.cn/Article/details/gt2inrhvpfl.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.guowangkeji.top/Article/details/gt2wpbpbgfj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2znqxnzlx.html

H. 异常与错误处理
来源：http://dali.jianghu66.top/Article/details/gt2tryqjjnr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2prjldhyg.html

[H01] try / catch 基础
来源：http://dali.ehwqpu.com/Article/details/gt2hwyrbfxo.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dashuyun.cn/Article/details/gt2iswndqff.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.guannengcc.top/Article/details/gt2zzumqtvy.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.cqqwz.cn/Article/details/gt2wjpwknzv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.aizwys.cn/Article/details/gt2jtmmatwz.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.birdmap.top/Article/details/gt2prfketok.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.quarkkingdee.top/Article/details/gt2mdrbsylm.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.yangfankeji.com/Article/details/gt2gcksiqlb.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2loueqltj.html

[H02] finally / ensure 收尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbpidyad.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.fzhhl.top/Article/details/gt2vqmwsdyz.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cashguo.top/Article/details/gt2yiyjaojl.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cukdryfe.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.tanke756.top/Article/details/gt2mgkfvhbn.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.snrcjt.cn/Article/details/gt2jqnpdfzo.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.daria6918.cn/Article/details/gt2yottudza.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.dashuyun.cn/Article/details/gt2khsdcsrs.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2abpinslo.html

[H03] 主动抛出异常
来源：http://dali.zdqjudy.top/Article/details/gt2qoyouore.html

Py:   raise ValueError("错误信息")
来源：http://dali.gzhubu.top/Article/details/gt2uvrvxahn.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oizobcdy.html

JS:   throw new Error("错误信息");
来源：http://dali.smart0.xyz/Article/details/gt2zlzuuqwt.html

TS:   throw new Error("错误信息");
来源：http://dali.shangyingyoupin.top/Article/details/gt2jeaevzni.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.zdqjudy.top/Article/details/gt2gowsreuq.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.chenlongwang.top/Article/details/gt2lmqlkmsx.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.cdnleiting.top/Article/details/gt2dejkyfjn.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.hysaishi.cn/Article/details/gt2laoikrjd.html

[H04] 自定义异常类型
来源：http://dali.zhoulong.xyz/Article/details/gt2raugshrc.html

Py:   class MyError(Exception): pass
来源：http://dali.yueranfly.top/Article/details/gt2yklkztcm.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.zdqjudy.top/Article/details/gt2yxydpuju.html

JS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2tlrdiuxd.html

TS:   class MyError extends Error {}
来源：http://dali.tian-w.cn/Article/details/gt2llsqrwxj.html

Java: class MyException extends RuntimeException {}
来源：http://dali.jiagoushi.top/Article/details/gt2wlgpqaqg.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.guowangkeji.top/Article/details/gt2logtulur.html

Ruby: class MyError < StandardError; end
来源：http://dali.jlsjyb.cn/Article/details/gt2sdmqovci.html

C#:   class MyException : Exception {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjhnwuac.html

[H05] 捕获特定类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xfywtuag.html

Py:   except ValueError as e:
来源：http://dali.aizwys.cn/Article/details/gt2liawkwar.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nfzmgivl.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2whqoaczx.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.svipenyu.cn/Article/details/gt2wodzimhb.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.daria6918.cn/Article/details/gt2etmlbupb.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.yj20258888.top/Article/details/gt2gxbmlivj.html

Ruby: rescue ArgumentError => e
来源：http://dali.birdmap.top/Article/details/gt2xoyjzmaw.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.cdnleiting.top/Article/details/gt2htfgyakc.html

[H06] 可选值 / 空值安全访问
来源：http://dali.pycfn.com/Article/details/gt2fsgumicn.html

Py:   value = d.get("k") or default
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lczjdbud.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.c1oappe.top/Article/details/gt2xjkyzhvg.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xgeccjqz.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.jiagoushi.top/Article/details/gt2mxfrkgoo.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.dianchejie.cn/Article/details/gt2jbrrhiix.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.gzhubu.top/Article/details/gt2dkjltqsg.html

Ruby: d&.dig(:a, :b)
来源：http://dali.iojbl.cn/Article/details/gt2sbsbhfyz.html

C#:   obj?.A?.B ?? default
来源：http://dali.yueranfly.top/Article/details/gt2jxsudobl.html

[H07] 断言
来源：http://dali.svipenyu.cn/Article/details/gt2mfbyteqw.html

Py:   assert x > 0, "必须为正"
来源：http://dali.cucudq.cn/Article/details/gt2smutswpc.html

PHP:  assert($x > 0);
来源：http://dali.9152youxi.cn/Article/details/gt2avcrthmm.html

JS:   console.assert(x > 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2njdxdxzc.html

TS:   console.assert(x > 0);
来源：http://dali.svipenyu.cn/Article/details/gt2mqautxfa.html

Java: assert x > 0 : "必须为正";
来源：http://dali.havefunace.top/Article/details/gt2moepcoxj.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.tianlin.xyz/Article/details/gt2gaastgag.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.chenjidiqi.icu/Article/details/gt2xzjlaeip.html

C#:   Debug.Assert(x > 0);
来源：http://dali.jinqigufen.top/Article/details/gt2ngxddzia.html

[H08] 获取错误信息与堆栈
来源：http://dali.yonumen.top/Article/details/gt2umzhscxz.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.fengsongda.top/Article/details/gt2yjfnbevj.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.yj20258.top/Article/details/gt2smrgcecf.html

JS:   e.message;  e.stack
来源：http://dali.yongpay.top/Article/details/gt2ztkbapdr.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.yuanzhike.top/Article/details/gt2wsrtcvbe.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.feifeiyinyue.top/Article/details/gt2qaagewac.html

Go:   err.Error()
来源：http://dali.daria6918.cn/Article/details/gt2irrjghfs.html

Ruby: e.message;  e.backtrace
来源：http://dali.nwbrower.top/Article/details/gt2xjudadvu.html

C#:   e.Message;  e.StackTrace
来源：http://dali.svipenyu.cn/Article/details/gt2rputgxfh.html

[H09] 带错误码的异常
来源：http://dali.bjfxy.top/Article/details/gt2zxuahnbd.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hysaishi.cn/Article/details/gt2ucpxclta.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.316326.xyz/Article/details/gt2meqlqbpf.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.cheryme.top/Article/details/gt2tzmumhhz.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.chenzaomai.com/Article/details/gt2rtvfetna.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.snrcjt.cn/Article/details/gt2njftfoad.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.haohaochexian.top/Article/details/gt2naphcuan.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.birdmap.top/Article/details/gt2ugsvfgbv.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.dianchejie.cn/Article/details/gt2szewqccu.html

[H10] 资源自动释放
来源：http://dali.jqgufenzy.top/Article/details/gt2ytghxpor.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.xylfe.cn/Article/details/gt2nabafyyq.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.iojbl.cn/Article/details/gt2vqqazrbo.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.gotoacloud.top/Article/details/gt2mfcezgfk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.jqgfzy.top/Article/details/gt2bboxojmo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.yueranfly.top/Article/details/gt2uekbthle.html

Go:   defer f.Close()
来源：http://dali.ivvv.top/Article/details/gt2rgdbesxw.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wwinieix.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.yanxiufei.cn/Article/details/gt2kzssrilk.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2oeiojnnv.html

I. 正则表达式
来源：http://dali.gogol.net.cn/Article/details/gt2aemmshky.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2vlqpswsw.html

[I01] 判断是否匹配
来源：http://dali.shuidangran.top/Article/details/gt2nrlroakf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhoulong.xyz/Article/details/gt2aquosmqa.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xjtsvjew.html

JS:   /\d+/.test(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jqavjawh.html

TS:   /\d+/.test(s)
来源：http://dali.ydzc1.top/Article/details/gt2flovadqb.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gotoacloud.top/Article/details/gt2eltwhfsr.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.shzxlz.cn/Article/details/gt2pmqpnstb.html

Ruby: s.match?(/\d+/)
来源：http://dali.gotoacloud.top/Article/details/gt2bslojobc.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.9152youxi.cn/Article/details/gt2kcoxzuyq.html

[I02] 提取所有匹配
来源：http://dali.pycfn.com/Article/details/gt2uetqkaua.html

Py:   re.findall(r"\d+", s)
来源：http://dali.9152youxi.cn/Article/details/gt2crlqxsfa.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.feifeiyinyue.top/Article/details/gt2dgmtfest.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.zhijiandao.cn/Article/details/gt2qbmljdrw.html

TS:   s.match(/\d+/g)
来源：http://dali.gzhubu.top/Article/details/gt2mvclpwlb.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.hywenlv.cn/Article/details/gt2zouncjxj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.aibaodan.cn/Article/details/gt2mhljtrsc.html

Ruby: s.scan(/\d+/)
来源：http://dali.hysaishi.cn/Article/details/gt2ahhvsdjn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2hljtbnog.html

[I03] 提取捕获分组
来源：http://dali.c1oappe.top/Article/details/gt2kvbyozyv.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.sufxvd.cn/Article/details/gt2efdkibyv.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.yueranfly.top/Article/details/gt2izxcfetw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.zhixingplan.top/Article/details/gt2irdmwkuc.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.vqdsnc.cn/Article/details/gt2ritktyax.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.guowangkeji.top/Article/details/gt2mjtyqpxy.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.guannengcc.top/Article/details/gt2srewmiah.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.zycfv.cn/Article/details/gt2uiccbggk.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.redwolf501.top/Article/details/gt2hlcfgsvb.html

[I04] 正则替换
来源：http://dali.sxryk.cn/Article/details/gt2pnzmdsdj.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.zycfv.cn/Article/details/gt2dufqcfuu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gt2gdskaida.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tianlin.xyz/Article/details/gt2xalexiez.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.svipenyu.cn/Article/details/gt2ddmxalut.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bwogpbti.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.tian-w.cn/Article/details/gt2fwleeaii.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.gzhubu.top/Article/details/gt2goxtjjfn.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.andypj.xyz/Article/details/gt2rprvpxca.html

[I05] 按正则拆分
来源：http://dali.hongshengwenyu.top/Article/details/gt2gqzrdzhv.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.yuxming.cn/Article/details/gt2poyeuhbs.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2gsuxxvbl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigfzy.top/Article/details/gt2yvgfiuyn.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.shuidangran.top/Article/details/gt2mtxfirod.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yuxming.cn/Article/details/gt2mdiqwrvt.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.hnxiangtu.top/Article/details/gt2qpxnuntx.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.ybcxt.top/Article/details/gt2hztvhcmy.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.nanxuanxn.top/Article/details/gt2tpsibktx.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gtgmwpgp.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.nwbrower.top/Article/details/gt2fhrrthde.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.hnxiangtu.top/Article/details/gt2hwoavsyh.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jianghu66.top/Article/details/gt2lrcmjioo.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agxhjrxm.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.ppjwa.cn/Article/details/gt2tccyayjp.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cehbynvs.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.vqdsnc.cn/Article/details/gt2udzgqtqu.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.cashguo.top/Article/details/gt2dclavfuk.html

[I07] 忽略大小写与多行模式
来源：http://dali.ydzc1.top/Article/details/gt2kuhnsabj.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.dianchejie.cn/Article/details/gt2hrrtiapu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.chenlongwang.top/Article/details/gt2qiokjigz.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.daxiang520.top/Article/details/gt2axgotkkz.html

TS:   /error/gim
来源：http://dali.chenjidiqi.icu/Article/details/gt2omwzvjth.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.snrcjt.cn/Article/details/gt2xlitgvbh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.yangfankeji.com/Article/details/gt2zmeryqqg.html

Ruby: s.scan(/error/i)
来源：http://dali.smart0.xyz/Article/details/gt2bdtkqgly.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.haohaochexian.top/Article/details/gt2ajcrvjfa.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.cucudq.cn/Article/details/gt2detwiimx.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.feifeiyinyue.top/Article/details/gt2yvctxvqk.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.hongshengwenyu.top/Article/details/gt2mxewyzfa.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sweek.top/Article/details/gt2zywcmzgt.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.sysykeji.top/Article/details/gt2pfehqqtk.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwmqnxcq.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.kuanghao11.cn/Article/details/gt2lsutclzl.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.gotoacloud.top/Article/details/gt2agwhtzwm.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.yj20258.top/Article/details/gt2fghwogyo.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2cjraexhu.html

J. 日期与时间
来源：http://dali.0kj1m.cn/Article/details/gt2qxzdokke.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2lromxftv.html

[J01] 获取当前时间
来源：http://dali.zhongyouzk.top/Article/details/gt2oupukuyb.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.svipenyu.cn/Article/details/gt2qeqbuyfa.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.c1oappe.top/Article/details/gt2yclduvht.html

JS:   new Date();  Date.now()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2butbofay.html

TS:   new Date();  Date.now()
来源：http://dali.pycfn.com/Article/details/gt2bcywfnyz.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.hysaishi.cn/Article/details/gt2bbltlcvc.html

Go:   time.Now()
来源：http://dali.yj20258888.top/Article/details/gt2bdwynpdf.html

Ruby: Time.now
来源：http://dali.tian-w.cn/Article/details/gt2fvotzvao.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.9152youxi.cn/Article/details/gt2zvhhjqxe.html

[J02] 格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tsnypuaf.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.havefunace.top/Article/details/gt2rufjjstv.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2flvbvywa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.snrcjt.cn/Article/details/gt2jsnuzwcr.html

TS:   d.toISOString()
来源：http://dali.tanke756.top/Article/details/gt2skrpfghm.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.pycfn.com/Article/details/gt2aojgckax.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.ybcxt.top/Article/details/gt2bdkvplzj.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.redwolf501.top/Article/details/gt2lgypdpxw.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vuqqmwpr.html

[J03] 字符串解析为日期
来源：http://dali.andypj.xyz/Article/details/gt2rmugrotq.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.yonumen.top/Article/details/gt2xhhrqurx.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.hnxiangtu.top/Article/details/gt2dueezogv.html

JS:   new Date("2024-01-02")
来源：http://dali.xuanzx.com/Article/details/gt2mormcttu.html

TS:   new Date("2024-01-02")
来源：http://dali.wangdashe.top/Article/details/gt2vdsjcfmd.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.jinqigufen.top/Article/details/gt2mmeglqxg.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.shzxlz.cn/Article/details/gt2wczwfclz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2cwqikesl.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.aizwys.cn/Article/details/gt2qlgcxzst.html

[J04] 时间戳与日期互转
来源：http://dali.ppjwa.cn/Article/details/gt2eduqaprh.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.ivvv.top/Article/details/gt2frhffweq.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.vqdsnc.cn/Article/details/gt2nkcvdczv.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.snrcjt.cn/Article/details/gt2hdglvcpm.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.snrcjt.cn/Article/details/gt2ealudtpi.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.cucudq.cn/Article/details/gt2quymdlmc.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2qeivnaee.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.hammf.cn/Article/details/gt2jxwruvkf.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.fzhhl.top/Article/details/gt2erddoczu.html

[J05] 时间加减（加 7 天）
来源：http://dali.dashuyun.cn/Article/details/gt2sircgvbk.html

Py:   now + timedelta(days=7)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ehjkthfq.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yuxming.cn/Article/details/gt2iazwmggq.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.jqgufenzy.top/Article/details/gt2vahwvdne.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.shangyingyoupin.top/Article/details/gt2veldiqnr.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.ehwqpu.com/Article/details/gt2itujzerz.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yuanzhike.top/Article/details/gt2pcckkwnj.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gt2emygoeby.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.yj202588.top/Article/details/gt2pjpsltzr.html

[J06] 计算两时间之差
来源：http://dali.dianchejie.cn/Article/details/gt2cykseczu.html

Py:   (end - start).total_seconds()
来源：http://dali.yj202588.top/Article/details/gt2ygncfmxl.html

PHP:  $end->diff($start)->days;
来源：http://dali.hysaishi.cn/Article/details/gt2mbadrsye.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pjcxeknm.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.ehwqpu.com/Article/details/gt2ctwurrzq.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.nanxuanxn.top/Article/details/gt2aqdwxfdo.html

Go:   end.Sub(start).Hours()
来源：http://dali.jlsjyb.cn/Article/details/gt2arhdzcvu.html

Ruby: end - start                 # 返回秒数
来源：http://dali.nwbrower.top/Article/details/gt2sfdkhdic.html

C#:   (end - start).TotalSeconds
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mtdzkzmi.html

[J07] 比较两个日期
来源：http://dali.ehwqpu.com/Article/details/gt2ldykcdod.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.sxryk.cn/Article/details/gt2aiusmxky.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.tianlin.xyz/Article/details/gt2ubckowhv.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.bjfxy.top/Article/details/gt2fugkihug.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.tanke756.top/Article/details/gt2bfnqieha.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.cdnleiting.top/Article/details/gt2crtrwxzg.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.jianghu66.top/Article/details/gt2xpsbxwlq.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.cashguo.top/Article/details/gt2xctsorkl.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.9152youxi.cn/Article/details/gt2geeoaadi.html

[J08] 提取年月日与星期
来源：http://dali.jinghuilouyu.cn/Article/details/gt2khxrwzuq.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.yangfankeji.com/Article/details/gt2dqowijgh.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.aibaodan.cn/Article/details/gt2dgvzzktf.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.pengpengdd.cyou/Article/details/gt2bfhoxvjc.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.316326.xyz/Article/details/gt2bntwiigk.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.sufxvd.cn/Article/details/gt2emqqwmqh.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.316326.xyz/Article/details/gt2scfeporl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.sxryk.cn/Article/details/gt2rwfggkcl.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2myisszux.html

[J09] 时区处理
来源：http://dali.nanxinkj.top/Article/details/gt2auusjnie.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhiwuduotai.top/Article/details/gt2eefsgpyo.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.zhengqikj.top/Article/details/gt2kjijxamb.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.redwolf501.top/Article/details/gt2extdsxru.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.kuanghao11.cn/Article/details/gt2jtqtrsfc.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.gogol.net.cn/Article/details/gt2jmrmpyuv.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.nanxinkj.top/Article/details/gt2ntqelefp.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.gaohongyu789.top/Article/details/gt2bjsvkcfx.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.hfpthk.cn/Article/details/gt2jgqtdcxq.html

[J10] 取今天 / 本月第一天
来源：http://dali.dashuyun.cn/Article/details/gt2ubysvxje.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mltulrze.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.gaohongyu789.top/Article/details/gt2ivvzyvnc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.gotoacloud.top/Article/details/gt2uodnnkxt.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2eybmsmjx.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.mhx1999.top/Article/details/gt2plqbovhi.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.hammf.cn/Article/details/gt2dsgwbsgn.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.zycfv.cn/Article/details/gt2xsxkcuwd.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.c1oappe.top/Article/details/gt2jhdxfpnb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2yjaqwogl.html

K. JSON 与序列化
来源：http://dali.haohaochexian.top/Article/details/gt2fxjlrcfk.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2gpnuthyh.html

[K01] 对象转 JSON 字符串
来源：http://dali.yuxming.cn/Article/details/gt2jjmlesch.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.316326.xyz/Article/details/gt2joqtdusi.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.feifeiyinyue.top/Article/details/gt2lyimifeo.html

JS:   JSON.stringify(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2srxceycw.html

TS:   JSON.stringify(obj)
来源：http://dali.yueranfly.top/Article/details/gt2dzpbsuxm.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2doeckhlz.html

Go:   json.Marshal(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2xrcfibbw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rlaordbe.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.vqdsnc.cn/Article/details/gt2kbyceecx.html

[K02] JSON 字符串转对象
来源：http://dali.quarkkingdee.top/Article/details/gt2ebkqxtxh.html

Py:   json.loads(s)
来源：http://dali.cdnleiting.top/Article/details/gt2nximxxod.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.jqgufenzy.top/Article/details/gt2yhhdjnsx.html

JS:   JSON.parse(s)
来源：http://dali.havefunace.top/Article/details/gt2usmaimdq.html


<!-- 参考信息 -->