代发 wailian999

Ruby: Color = %i[red green].freeze
来源：http://dali.yj20258.top/Article/details/gt2cmdmnfuk.html

C#:   enum Color { Red = 1, Green = 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2nvduaqxn.html

[G16] 对象转数组 / 字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrpidvbw.html

Py:   dataclasses.asdict(obj);  obj.__dict__
来源：http://dali.chenjidiqi.icu/Article/details/gt2vrdgqvqu.html

PHP:  get_object_vars($obj);
来源：http://dali.hongshengwenyu.top/Article/details/gt2kokeaugj.html

JS:   Object.entries(obj)
来源：http://dali.wangdashe.top/Article/details/gt2ebuazwcq.html

TS:   Object.entries(obj)
来源：http://dali.havefunace.top/Article/details/gt2dsokxocl.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.zhijiandao.cn/Article/details/gt2zxvgxtng.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.zhongyouzk.top/Article/details/gt2sybtflnn.html

Ruby: obj.instance_variables
来源：http://dali.jinqigfzy.top/Article/details/gt2xvmwzoli.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.fengsongda.top/Article/details/gt2ucibrhuj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2fxaikity.html

H. 异常与错误处理
来源：http://dali.c1oappe.top/Article/details/gt2khepuxpn.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2crrvnopg.html

[H01] try / catch 基础
来源：http://dali.jinqigfzy.top/Article/details/gt2nxhzgnsq.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.smart0.xyz/Article/details/gt2llmwatjk.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.ehwqpu.com/Article/details/gt2iutuwdkt.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.bjfxy.top/Article/details/gt2fdifuugv.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.cdnleiting.top/Article/details/gt2icajpteo.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.birdmap.top/Article/details/gt2fivwlclw.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.gzhubu.top/Article/details/gt2wylvbyim.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.xziqi.cn/Article/details/gt2oialfjeo.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.wangdashe.top/Article/details/gt2humyxzbn.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gt2nurcjbua.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.zhixingplan.top/Article/details/gt2psfudris.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.cqqwz.cn/Article/details/gt2icsflsrk.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2htgifjey.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2tebrklcg.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.tianlin.xyz/Article/details/gt2uigcqrxn.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.xylfe.cn/Article/details/gt2fzqqtgqa.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.jqgfzy.top/Article/details/gt2gsbxgfkx.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqlwclkn.html

[H03] 主动抛出异常
来源：http://dali.nanxuanxn.top/Article/details/gt2qxcegfwy.html

Py:   raise ValueError("错误信息")
来源：http://dali.gaohongyu789.top/Article/details/gt2rsjumqtt.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.zhoulong.xyz/Article/details/gt2lewitovv.html

JS:   throw new Error("错误信息");
来源：http://dali.jqgfzy.top/Article/details/gt2tberjqiv.html

TS:   throw new Error("错误信息");
来源：http://dali.chenlongwang.top/Article/details/gt2jmspunaj.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.vqdsnc.cn/Article/details/gt2aakbglrj.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.sweek.top/Article/details/gt2kgukfehw.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.sysykeji.top/Article/details/gt2nhneyihf.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.snrcjt.cn/Article/details/gt2jcdfvbju.html

[H04] 自定义异常类型
来源：http://dali.xuanzx.com/Article/details/gt2popvrznk.html

Py:   class MyError(Exception): pass
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nhighzto.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.xylfe.cn/Article/details/gt2ufrydlcv.html

JS:   class MyError extends Error {}
来源：http://dali.shuidangran.top/Article/details/gt2kvfxwgvx.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2olxexvpm.html

Java: class MyException extends RuntimeException {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oazpnizj.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.cqqwz.cn/Article/details/gt2frrzmcdp.html

Ruby: class MyError < StandardError; end
来源：http://dali.sweek.top/Article/details/gt2ctydvppw.html

C#:   class MyException : Exception {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2loimlgge.html

[H05] 捕获特定类型
来源：http://dali.gogol.net.cn/Article/details/gt2pnddxslm.html

Py:   except ValueError as e:
来源：http://dali.iojbl.cn/Article/details/gt2kcrjilkh.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.jyoumei.cn/Article/details/gt2iguigdwg.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.sysykeji.top/Article/details/gt2inrqgmls.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.yangfankeji.com/Article/details/gt2ewoncwuz.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2rmnygrdx.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.vqdsnc.cn/Article/details/gt2vganhygw.html

Ruby: rescue ArgumentError => e
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gplfmhtn.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.xuanzx.com/Article/details/gt2lalpyins.html

[H06] 可选值 / 空值安全访问
来源：http://dali.hysaishi.cn/Article/details/gt2guscbksy.html

Py:   value = d.get("k") or default
来源：http://dali.hysaishi.cn/Article/details/gt2goojypth.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.xylfe.cn/Article/details/gt2yiopbxmz.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.havefunace.top/Article/details/gt2cmnvzycs.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.zdqjudy.top/Article/details/gt2ebojagkm.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.316326.xyz/Article/details/gt2zduvijjg.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.svipenyu.cn/Article/details/gt2emjlfvee.html

Ruby: d&.dig(:a, :b)
来源：http://dali.gogol.net.cn/Article/details/gt2jgeyjaqn.html

C#:   obj?.A?.B ?? default
来源：http://dali.wangshuangyany.cn/Article/details/gt2tulkbynl.html

[H07] 断言
来源：http://dali.jianghu66.top/Article/details/gt2ziiwbbdt.html

Py:   assert x > 0, "必须为正"
来源：http://dali.sweek.top/Article/details/gt2ougngigt.html

PHP:  assert($x > 0);
来源：http://dali.ydzc1.top/Article/details/gt2rbhdlyin.html

JS:   console.assert(x > 0);
来源：http://dali.tian-w.cn/Article/details/gt2kksvueux.html

TS:   console.assert(x > 0);
来源：http://dali.yj20258.top/Article/details/gt2pkgvgzvw.html

Java: assert x > 0 : "必须为正";
来源：http://dali.meibo888.top/Article/details/gt2wvuakeas.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.iojbl.cn/Article/details/gt2gnxtvjqu.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.yj20258888.top/Article/details/gt2hqgqstbr.html

C#:   Debug.Assert(x > 0);
来源：http://dali.shzxlz.cn/Article/details/gt2kqfkrdnl.html

[H08] 获取错误信息与堆栈
来源：http://dali.daria6918.cn/Article/details/gt2pcwxyxvt.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.smart0.xyz/Article/details/gt2dblfyskx.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.hfpthk.cn/Article/details/gt2reoponay.html

JS:   e.message;  e.stack
来源：http://dali.zhixingplan.top/Article/details/gt2otwsvfez.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avomwxza.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.jianghu66.top/Article/details/gt2rsnjnewz.html

Go:   err.Error()
来源：http://dali.kuanghao11.cn/Article/details/gt2subemgxe.html

Ruby: e.message;  e.backtrace
来源：http://dali.zycfv.cn/Article/details/gt2bvkqmmay.html

C#:   e.Message;  e.StackTrace
来源：http://dali.yj20258888.top/Article/details/gt2ggelvvqr.html

[H09] 带错误码的异常
来源：http://dali.yanxiufei.cn/Article/details/gt2ncbxaivw.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.yj20258888.top/Article/details/gt2bljpcksh.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.dashuyun.cn/Article/details/gt2iaifllvt.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.hfpthk.cn/Article/details/gt2mtgeoxaf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.ivvv.top/Article/details/gt2zokxymmf.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.yj202588.top/Article/details/gt2zvlssgeb.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.0kj1m.cn/Article/details/gt2srupzeed.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.meibo888.top/Article/details/gt2rttsxqbe.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.vqdsnc.cn/Article/details/gt2jtfgljut.html

[H10] 资源自动释放
来源：http://dali.dashuyun.cn/Article/details/gt2anifldns.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.guowangkeji.top/Article/details/gt2wgaldvqx.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yulirqdv.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.cdnleiting.top/Article/details/gt2gsnfulcb.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.fzhhl.top/Article/details/gt2eshlwodg.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.nanxinkj.top/Article/details/gt2giuytxfb.html

Go:   defer f.Close()
来源：http://dali.zdqjudy.top/Article/details/gt2vesjwexa.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.tanke756.top/Article/details/gt2muvmykco.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbrmions.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2jggfwcph.html

I. 正则表达式
来源：http://dali.havefunace.top/Article/details/gt2ebjzvlts.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2qyijfkfp.html

[I01] 判断是否匹配
来源：http://dali.hnqzz.top/Article/details/gt2kjalgisa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iozmkpsj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2lhmbgyzj.html

JS:   /\d+/.test(s)
来源：http://dali.daxiang520.top/Article/details/gt2cybetpmr.html

TS:   /\d+/.test(s)
来源：http://dali.hywenlv.cn/Article/details/gt2seaqosyu.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.cheryme.top/Article/details/gt2nuajysem.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2obpbadfp.html

Ruby: s.match?(/\d+/)
来源：http://dali.yongpay.top/Article/details/gt2hlmmrtbs.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.nanxinkj.top/Article/details/gt2myexopvm.html

[I02] 提取所有匹配
来源：http://dali.jianghu66.top/Article/details/gt2qszpotri.html

Py:   re.findall(r"\d+", s)
来源：http://dali.kuanghao11.cn/Article/details/gt2yewbkiye.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.zhijiandao.cn/Article/details/gt2suxhtibx.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.redwolf501.top/Article/details/gt2jhmwdzje.html

TS:   s.match(/\d+/g)
来源：http://dali.jianghu66.top/Article/details/gt2ckidffxt.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.0kj1m.cn/Article/details/gt2nccmthxj.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.ybcxt.top/Article/details/gt2bmsghkok.html

Ruby: s.scan(/\d+/)
来源：http://dali.pycfn.com/Article/details/gt2qjdklkjn.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aiookdnc.html

[I03] 提取捕获分组
来源：http://dali.gaohongyu789.top/Article/details/gt2tqzbgpgr.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvnsxyqc.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ylmxdcdf.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.svipenyu.cn/Article/details/gt2iazvwdqm.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.redwolf501.top/Article/details/gt2yfgrgyyi.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.redwolf501.top/Article/details/gt2rygwtyfs.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.jianghu66.top/Article/details/gt2kgizgles.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.wangdashe.top/Article/details/gt2zketmznx.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.yj20258888.top/Article/details/gt2ftywebvr.html

[I04] 正则替换
来源：http://dali.hnxiangtu.top/Article/details/gt2aerkrxpf.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dtgifafb.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.sufxvd.cn/Article/details/gt2kvumdyow.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.tanke756.top/Article/details/gt2vpekvffq.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.9152youxi.cn/Article/details/gt2hbovwvyc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.yj20258.top/Article/details/gt2dagxfgqi.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.316326.xyz/Article/details/gt2strtftck.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jinqigufen.top/Article/details/gt2oyqozcby.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.xinyue.icu/Article/details/gt2tnvwngxz.html

[I05] 按正则拆分
来源：http://dali.iojbl.cn/Article/details/gt2pplttnaw.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yimztude.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.yongpay.top/Article/details/gt2lcoymnfl.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2obzaallr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2codegdtt.html

Java: s.split("\\s*,\\s*")
来源：http://dali.zycfv.cn/Article/details/gt2nzsmcvfx.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.meibo888.top/Article/details/gt2ynfsowed.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.cheryme.top/Article/details/gt2aytpfyvd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.gogol.net.cn/Article/details/gt2vuxgpuxr.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.vqdsnc.cn/Article/details/gt2glcqdukv.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.xylfe.cn/Article/details/gt2qsirdvzz.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.shzxlz.cn/Article/details/gt2xljnvuat.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.nanxuanxn.top/Article/details/gt2vfvklxtm.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.dashuyun.cn/Article/details/gt2cjwwczyb.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.xuetiantiany.cn/Article/details/gt2emwvskju.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenjidiqi.icu/Article/details/gt2gqvyxdlu.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.gogol.net.cn/Article/details/gt2hhbmxeuy.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.smart0.xyz/Article/details/gt2ywkflhfx.html

[I07] 忽略大小写与多行模式
来源：http://dali.gogol.net.cn/Article/details/gt2xtxwuqao.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rjudimwu.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.316326.xyz/Article/details/gt2eizkdbif.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.xziqi.cn/Article/details/gt2wslytxyy.html

TS:   /error/gim
来源：http://dali.daxiang520.top/Article/details/gt2nubcxfpa.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gkidzwou.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.jinqigfzy.top/Article/details/gt2slginocf.html

Ruby: s.scan(/error/i)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kaeyoign.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigfzy.top/Article/details/gt2roszzohf.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.shuidangran.top/Article/details/gt2thfftsig.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqxxsexi.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.daria6918.cn/Article/details/gt2sstapety.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.yonumen.top/Article/details/gt2nljlgkfr.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gt2nackbxoh.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.sweek.top/Article/details/gt2tpzzymkl.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.aibaodan.cn/Article/details/gt2najsirll.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.hnqzz.top/Article/details/gt2zssgfbym.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.zhengqikj.top/Article/details/gt2obttrodm.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2pxkhueec.html

J. 日期与时间
来源：http://dali.zhiwuduotai.top/Article/details/gt2iwgdseuh.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2ojljfihb.html

[J01] 获取当前时间
来源：http://dali.daxiang520.top/Article/details/gt2suvwuegs.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.xuanzx.com/Article/details/gt2sbypvazr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.dashuyun.cn/Article/details/gt2fozjkhxy.html

JS:   new Date();  Date.now()
来源：http://dali.haohaochexian.top/Article/details/gt2zsuaeupl.html

TS:   new Date();  Date.now()
来源：http://dali.jinqigufen.top/Article/details/gt2uqmqjfll.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yueranfly.top/Article/details/gt2vuzmmzxq.html

Go:   time.Now()
来源：http://dali.bjfxy.top/Article/details/gt2cgwfekju.html

Ruby: Time.now
来源：http://dali.dashuyun.cn/Article/details/gt2qkpdkpdu.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uvfrteuf.html

[J02] 格式化输出
来源：http://dali.tanke756.top/Article/details/gt2iflnrikb.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.daria6918.cn/Article/details/gt2bfewlqwr.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.tian-w.cn/Article/details/gt2moolwfsf.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uswkelsj.html

TS:   d.toISOString()
来源：http://dali.pengpengdd.cyou/Article/details/gt2axipznka.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.chenjidiqi.icu/Article/details/gt2skmwtupj.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.zdqjudy.top/Article/details/gt2bwliajsv.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gt2pfxomkbt.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhoulong.xyz/Article/details/gt2vshcqvzm.html

[J03] 字符串解析为日期
来源：http://dali.yj20258888.top/Article/details/gt2xxezeolk.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.nwbrower.top/Article/details/gt2ocvglckt.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.aizwys.cn/Article/details/gt2jtecoufo.html

JS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2nrazizfe.html

TS:   new Date("2024-01-02")
来源：http://dali.gotoacloud.top/Article/details/gt2ymxvivhw.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sufxvd.cn/Article/details/gt2rifsivhq.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.vqdsnc.cn/Article/details/gt2keqkvztz.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.zhiwuduotai.top/Article/details/gt2xunmrwoj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjjsoxio.html

[J04] 时间戳与日期互转
来源：http://dali.vqdsnc.cn/Article/details/gt2lkeczyci.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcyletz.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wzntybzm.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fhfjsvoi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.hysaishi.cn/Article/details/gt2vcawneku.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jamvfioh.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.c1oappe.top/Article/details/gt2vyypddpa.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jiagoushi.top/Article/details/gt2mpnemohe.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.iojbl.cn/Article/details/gt2rmibzuzz.html

[J05] 时间加减（加 7 天）
来源：http://dali.haohaochexian.top/Article/details/gt2qedjgyol.html

Py:   now + timedelta(days=7)
来源：http://dali.andypj.xyz/Article/details/gt2tmgcmawn.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.gotoacloud.top/Article/details/gt2khibszud.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.xziqi.cn/Article/details/gt2vesfewsq.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hammf.cn/Article/details/gt2wepjythm.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.xziqi.cn/Article/details/gt2dlhgqkxi.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.nanxinkj.top/Article/details/gt2olbiktln.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yj20258.top/Article/details/gt2tkmhdgsm.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.cqqwz.cn/Article/details/gt2amlqojpl.html

[J06] 计算两时间之差
来源：http://dali.quarkkingdee.top/Article/details/gt2vcweqcho.html

Py:   (end - start).total_seconds()
来源：http://dali.hongshengwenyu.top/Article/details/gt2kqoltwov.html

PHP:  $end->diff($start)->days;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xwwtwltj.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.zycfv.cn/Article/details/gt2cywijwvs.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.bjfxy.top/Article/details/gt2fswtemtf.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.cashguo.top/Article/details/gt2yssraphq.html

Go:   end.Sub(start).Hours()
来源：http://dali.kuanghao11.cn/Article/details/gt2sanhrurk.html

Ruby: end - start                 # 返回秒数
来源：http://dali.guowangkeji.top/Article/details/gt2iqdftmlp.html

C#:   (end - start).TotalSeconds
来源：http://dali.guannengcc.top/Article/details/gt2wkjfzwop.html

[J07] 比较两个日期
来源：http://dali.jinqigufen.top/Article/details/gt2fklaeyna.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ualvrwyc.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.jiagoushi.top/Article/details/gt2zsowlhlt.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.tian-w.cn/Article/details/gt2octuoytf.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gt2wbaleidk.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.pycfn.com/Article/details/gt2bbkgdugb.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pyuuwtvl.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.havefunace.top/Article/details/gt2wxidfwhs.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kiojaqgq.html

[J08] 提取年月日与星期
来源：http://dali.hnxiangtu.top/Article/details/gt2mvhioqlw.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.shuidangran.top/Article/details/gt2iecevzbe.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.havefunace.top/Article/details/gt2rejnjrqi.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.yuxming.cn/Article/details/gt2zxeaifcv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yj20258888.top/Article/details/gt2ipxussqb.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.0kj1m.cn/Article/details/gt2dlnlnzch.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.zhiwuduotai.top/Article/details/gt2imibbxcl.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.daria6918.cn/Article/details/gt2jihpqara.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.yanxiufei.cn/Article/details/gt2fucozhyg.html

[J09] 时区处理
来源：http://dali.fengsongda.top/Article/details/gt2psatwmee.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.svipenyu.cn/Article/details/gt2mhxibwot.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.9152youxi.cn/Article/details/gt2zawkahns.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yj20258888.top/Article/details/gt2gtemxlhk.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gt2wqdlvvbe.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ydzc1.top/Article/details/gt2nmzbdnub.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.chenzaomai.com/Article/details/gt2hmcnakjb.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.jyoumei.cn/Article/details/gt2iqykdthz.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.yuxming.cn/Article/details/gt2kjvipaon.html

[J10] 取今天 / 本月第一天
来源：http://dali.chenjidiqi.icu/Article/details/gt2zexmudjn.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.zhijiandao.cn/Article/details/gt2izxaazuq.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.jinqigufen.top/Article/details/gt2tayedutd.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.ybcxt.top/Article/details/gt2aqbtohoi.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.chenlongwang.top/Article/details/gt2jubyfgbd.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.dianchejie.cn/Article/details/gt2pxdkrvjs.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.meibo888.top/Article/details/gt2vnhzkcpy.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.316326.xyz/Article/details/gt2vcnjzuez.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.hnqzz.top/Article/details/gt2aonjbicx.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2esvithqz.html

K. JSON 与序列化
来源：http://dali.zhijiandao.cn/Article/details/gt2lwcrbjya.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2bcfvsftd.html

[K01] 对象转 JSON 字符串
来源：http://dali.shangyingyoupin.top/Article/details/gt2momcsxpr.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pyvfbclw.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.fzhhl.top/Article/details/gt2nsosguhc.html

JS:   JSON.stringify(obj)
来源：http://dali.sxryk.cn/Article/details/gt2bgqlxrrh.html

TS:   JSON.stringify(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2zycjeqfl.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.svipenyu.cn/Article/details/gt2svjkyozp.html

Go:   json.Marshal(obj)
来源：http://dali.nanxinkj.top/Article/details/gt2ckmdscla.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.sxryk.cn/Article/details/gt2lkwnpfto.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tian-w.cn/Article/details/gt2kfdzwoqc.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gt2laziebox.html

Py:   json.loads(s)
来源：http://dali.hfpthk.cn/Article/details/gt2ugldjzmz.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cbvnfzvg.html

JS:   JSON.parse(s)
来源：http://dali.cucudq.cn/Article/details/gt2rkpktpdg.html

TS:   JSON.parse(s)
来源：http://dali.ydzc1.top/Article/details/gt2wrjjyzjw.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sweek.top/Article/details/gt2heafhsqs.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.yueranfly.top/Article/details/gt2ntprsjfv.html

Ruby: JSON.parse(s)
来源：http://dali.jiagoushi.top/Article/details/gt2gcenpjmh.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.cqqwz.cn/Article/details/gt2ubxfgqof.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.iojbl.cn/Article/details/gt2flmhlxte.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.gogol.net.cn/Article/details/gt2kbhtorza.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.iojbl.cn/Article/details/gt2qvldmdim.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.yvedp.cn/Article/details/gt2fmhhinwz.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2yveofqfg.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.hysaishi.cn/Article/details/gt2gkkalptv.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.cashguo.top/Article/details/gt2mboljykc.html


<!-- 参考信息 -->