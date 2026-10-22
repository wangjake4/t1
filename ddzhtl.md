代发 wailian999

PHP:  get_object_vars($obj);
来源：http://dali.cucudq.cn/Article/details/gt2fbhsqzmu.html

JS:   Object.entries(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2ealiydey.html

TS:   Object.entries(obj)
来源：http://dali.jqgufenzy.top/Article/details/gt2svtjobru.html

Java: // 用 Jackson 等序列化库，或手写 toMap()
来源：http://dali.316326.xyz/Article/details/gt2gktzxqas.html

Go:   // 手写转换，或用 mapstructure 库
来源：http://dali.ppjwa.cn/Article/details/gt2pmpxnxar.html

Ruby: obj.instance_variables
来源：http://dali.hnqzz.top/Article/details/gt2npfcxqar.html

C#:   // 用反射或 System.Text.Json
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2chkaonfx.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfndartn.html

H. 异常与错误处理
来源：http://dali.dianchejie.cn/Article/details/gt2ykwmxotw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2pssczfiu.html

[H01] try / catch 基础
来源：http://dali.wangshuangyany.cn/Article/details/gt2kwtpteyv.html

Py:   try: f()⏎except Exception as e: print(e)
来源：http://dali.dianchejie.cn/Article/details/gt2pbneojqm.html

PHP:  try { f(); } catch (Exception $e) { echo $e->getMessage(); }
来源：http://dali.hnxiangtu.top/Article/details/gt2obgthaop.html

JS:   try { f(); } catch (e) { console.error(e); }
来源：http://dali.hnxiangtu.top/Article/details/gt2tkinwfdi.html

TS:   try { f(); } catch (e: unknown) { console.error(e); }
来源：http://dali.nwbrower.top/Article/details/gt2txctzwpk.html

Java: try { f(); } catch (Exception e) { System.out.println(e.getMessage()); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ditfdbdl.html

Go:   if err := f(); err != nil { log.Println(err) }   // Go 用返回值而非异常
来源：http://dali.cucudq.cn/Article/details/gt2vllqrbku.html

Ruby: begin; f; rescue => e; puts e.message; end
来源：http://dali.aizwys.cn/Article/details/gt2wvmnqcah.html

C#:   try { F(); } catch (Exception e) { Console.WriteLine(e.Message); }
来源：http://dali.ppjwa.cn/Article/details/gt2ywnqrscd.html

[H02] finally / ensure 收尾
来源：http://dali.yueranfly.top/Article/details/gt2dpxwneki.html

Py:   try: f()⏎finally: cleanup()
来源：http://dali.yuanzhike.top/Article/details/gt2jgxhoeyr.html

PHP:  try { f(); } finally { cleanup(); }
来源：http://dali.jiagoushi.top/Article/details/gt2tuodzcit.html

JS:   try { f(); } finally { cleanup(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2plvsubps.html

TS:   try { f(); } finally { cleanup(); }
来源：http://dali.zhixingplan.top/Article/details/gt2bbtnivog.html

Java: try { f(); } finally { cleanup(); }
来源：http://dali.hnqzz.top/Article/details/gt2spbqprje.html

Go:   defer cleanup()             // 函数返回时执行
来源：http://dali.cucudq.cn/Article/details/gt2bhxplvbv.html

Ruby: begin; f; ensure; cleanup; end
来源：http://dali.shzxlz.cn/Article/details/gt2mwbsyoje.html

C#:   try { F(); } finally { Cleanup(); }
来源：http://dali.jyoumei.cn/Article/details/gt2ylmkdrkq.html

[H03] 主动抛出异常
来源：http://dali.gogol.net.cn/Article/details/gt2xquisdpl.html

Py:   raise ValueError("错误信息")
来源：http://dali.tian-w.cn/Article/details/gt2typqnslx.html

PHP:  throw new InvalidArgumentException("错误信息");
来源：http://dali.gzhubu.top/Article/details/gt2jerxsipa.html

JS:   throw new Error("错误信息");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2duhzramb.html

TS:   throw new Error("错误信息");
来源：http://dali.andypj.xyz/Article/details/gt2emscoylg.html

Java: throw new IllegalArgumentException("错误信息");
来源：http://dali.xziqi.cn/Article/details/gt2uwlsrvpe.html

Go:   return fmt.Errorf("错误信息: %w", err)
来源：http://dali.andypj.xyz/Article/details/gt2pnfaqdaz.html

Ruby: raise ArgumentError, "错误信息"
来源：http://dali.chenlongwang.top/Article/details/gt2uwwyzvro.html

C#:   throw new ArgumentException("错误信息");
来源：http://dali.yanxiufei.cn/Article/details/gt2rqpxgccd.html

[H04] 自定义异常类型
来源：http://dali.havefunace.top/Article/details/gt2axlkkvij.html

Py:   class MyError(Exception): pass
来源：http://dali.wangdashe.top/Article/details/gt2bgrrpcxq.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yonumen.top/Article/details/gt2dlivcrpa.html

JS:   class MyError extends Error {}
来源：http://dali.hfpthk.cn/Article/details/gt2ppifeqti.html

TS:   class MyError extends Error {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oucbhxki.html

Java: class MyException extends RuntimeException {}
来源：http://dali.iojbl.cn/Article/details/gt2qrvvsxtr.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.aibaodan.cn/Article/details/gt2tkkzfcel.html

Ruby: class MyError < StandardError; end
来源：http://dali.gaohongyu789.top/Article/details/gt2oasfzyrj.html

C#:   class MyException : Exception {}
来源：http://dali.hnxiangtu.top/Article/details/gt2etwabwyg.html

[H05] 捕获特定类型
来源：http://dali.hysaishi.cn/Article/details/gt2ofqdigax.html

Py:   except ValueError as e:
来源：http://dali.hammf.cn/Article/details/gt2geievoka.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.shuidangran.top/Article/details/gt2xxosfksb.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.xylfe.cn/Article/details/gt2vjblplyf.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.fengsongda.top/Article/details/gt2fnhonyit.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.tian-w.cn/Article/details/gt2iiqhqcxd.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.xylfe.cn/Article/details/gt2kqxfchvg.html

Ruby: rescue ArgumentError => e
来源：http://dali.yangfankeji.com/Article/details/gt2rzbdxuye.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmpydwhb.html

[H06] 可选值 / 空值安全访问
来源：http://dali.zhijiandao.cn/Article/details/gt2hbynvgsd.html

Py:   value = d.get("k") or default
来源：http://dali.cheryme.top/Article/details/gt2pgcnlgsk.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hnqzz.top/Article/details/gt2btgmurmw.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.guannengcc.top/Article/details/gt2ckpvzebq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.shuidangran.top/Article/details/gt2mtjumsrb.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.yongpay.top/Article/details/gt2iqmwoatv.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.nanxuanxn.top/Article/details/gt2qkechkio.html

Ruby: d&.dig(:a, :b)
来源：http://dali.sysykeji.top/Article/details/gt2mzidftwj.html

C#:   obj?.A?.B ?? default
来源：http://dali.mhx1999.top/Article/details/gt2hbfeqqlc.html

[H07] 断言
来源：http://dali.yuxming.cn/Article/details/gt2orfvlrjz.html

Py:   assert x > 0, "必须为正"
来源：http://dali.meibo888.top/Article/details/gt2gpfxehlx.html

PHP:  assert($x > 0);
来源：http://dali.yuxming.cn/Article/details/gt2forabapw.html

JS:   console.assert(x > 0);
来源：http://dali.gotoacloud.top/Article/details/gt2jrhtynng.html

TS:   console.assert(x > 0);
来源：http://dali.yj202588.top/Article/details/gt2qnkogxxn.html

Java: assert x > 0 : "必须为正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kslywsoh.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.mhx1999.top/Article/details/gt2vcckqcgj.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.hongshengwenyu.top/Article/details/gt2gedwntjx.html

C#:   Debug.Assert(x > 0);
来源：http://dali.guannengcc.top/Article/details/gt2gxowszkv.html

[H08] 获取错误信息与堆栈
来源：http://dali.dashuyun.cn/Article/details/gt2hlagimrb.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.cqqwz.cn/Article/details/gt2tomxvino.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.jyoumei.cn/Article/details/gt2nnocuybp.html

JS:   e.message;  e.stack
来源：http://dali.snrcjt.cn/Article/details/gt2pidbeoaq.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.birdmap.top/Article/details/gt2leaalosr.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.yj20258888.top/Article/details/gt2tjjoaysy.html

Go:   err.Error()
来源：http://dali.yangfankeji.com/Article/details/gt2zdsoykem.html

Ruby: e.message;  e.backtrace
来源：http://dali.jqgufenzy.top/Article/details/gt2palpyouh.html

C#:   e.Message;  e.StackTrace
来源：http://dali.xylfe.cn/Article/details/gt2spzuewii.html

[H09] 带错误码的异常
来源：http://dali.xuetiantiany.cn/Article/details/gt2jehbymwz.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.shangyingyoupin.top/Article/details/gt2fyksyifi.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.tianlin.xyz/Article/details/gt2kqtpcgyx.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.bjfxy.top/Article/details/gt2ttopdlbf.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.daxiang520.top/Article/details/gt2tdaxxqus.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.ehwqpu.com/Article/details/gt2tepciyrl.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.yonumen.top/Article/details/gt2zwrxlsyr.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fthvtlak.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jianghu66.top/Article/details/gt2fcrsnrye.html

[H10] 资源自动释放
来源：http://dali.xuanzx.com/Article/details/gt2kwumvgdo.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.yongpay.top/Article/details/gt2dojyymiy.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.vqdsnc.cn/Article/details/gt2afroduae.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.redwolf501.top/Article/details/gt2lwcekadk.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2obvkirbo.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.ivvv.top/Article/details/gt2hhntllvz.html

Go:   defer f.Close()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uohnynzn.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.xziqi.cn/Article/details/gt2dafgjmnm.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.cucudq.cn/Article/details/gt2iiqzrorv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2htjatwum.html

I. 正则表达式
来源：http://dali.yangfankeji.com/Article/details/gt2qshdbdbh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qwxwycir.html

[I01] 判断是否匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2vpfobobf.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qilqbfow.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.xinyue.icu/Article/details/gt2hsbkgohd.html

JS:   /\d+/.test(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2kyzslxby.html

TS:   /\d+/.test(s)
来源：http://dali.redwolf501.top/Article/details/gt2bbhjaiom.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.gzhubu.top/Article/details/gt2cljjnshq.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.fengsongda.top/Article/details/gt2xjcbphpw.html

Ruby: s.match?(/\d+/)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ohdlxsbk.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gt2awjmoffe.html

[I02] 提取所有匹配
来源：http://dali.tanke756.top/Article/details/gt2qydczuwh.html

Py:   re.findall(r"\d+", s)
来源：http://dali.dianchejie.cn/Article/details/gt2wkbhersj.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.nwbrower.top/Article/details/gt2ruotjkrc.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.gaohongyu789.top/Article/details/gt2ysifenqu.html

TS:   s.match(/\d+/g)
来源：http://dali.yuanzhike.top/Article/details/gt2ujrnvqse.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2bubkrmqr.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.yueranfly.top/Article/details/gt2tczznawj.html

Ruby: s.scan(/\d+/)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bkfvnawv.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2zgdncbpg.html

[I03] 提取捕获分组
来源：http://dali.pycfn.com/Article/details/gt2fhcfoogp.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gyynosxy.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.0kj1m.cn/Article/details/gt2qjjycvph.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.yueranfly.top/Article/details/gt2ngdxgdtj.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yanxiufei.cn/Article/details/gt2qtdgygse.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.fzhhl.top/Article/details/gt2asxyrlbx.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.zhiwuduotai.top/Article/details/gt2xbejuwwx.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.yvedp.cn/Article/details/gt2bzwutdws.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jlsjyb.cn/Article/details/gt2mlfjbcqm.html

[I04] 正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ompbvngn.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.316326.xyz/Article/details/gt2ukjicwko.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fkiekswl.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.yj20258888.top/Article/details/gt2iqahyqye.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.andypj.xyz/Article/details/gt2brhektqu.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.dashuyun.cn/Article/details/gt2ofyzaykh.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.ivvv.top/Article/details/gt2otvobgnb.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.jqgfzy.top/Article/details/gt2tgogkpnj.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.zycfv.cn/Article/details/gt2cfihnhck.html

[I05] 按正则拆分
来源：http://dali.jyoumei.cn/Article/details/gt2xabcdxdi.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ydzc1.top/Article/details/gt2lvlbrsvp.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2birwmuah.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2euyqmkvr.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.fengsongda.top/Article/details/gt2bkgahsrs.html

Java: s.split("\\s*,\\s*")
来源：http://dali.yonumen.top/Article/details/gt2axpjuhra.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.kuanghao11.cn/Article/details/gt2ncmjnrbe.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.haohaochexian.top/Article/details/gt2qumvtxye.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.havefunace.top/Article/details/gt2dtiojujd.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.zycfv.cn/Article/details/gt2lumrvamk.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2owuitwbr.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.quarkkingdee.top/Article/details/gt2plwrlboz.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.aizwys.cn/Article/details/gt2ulikhwqg.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.svipenyu.cn/Article/details/gt2hnujpsaz.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.guowangkeji.top/Article/details/gt2fjyvocfg.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.chenjidiqi.icu/Article/details/gt2pgsfuiva.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.nanxinkj.top/Article/details/gt2cmjbtyyf.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.zhongyouzk.top/Article/details/gt2kvzxxtes.html

[I07] 忽略大小写与多行模式
来源：http://dali.xziqi.cn/Article/details/gt2esjhsldn.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.fzhhl.top/Article/details/gt2qtajpbgw.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.xziqi.cn/Article/details/gt2qguoxzbd.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.jianghu66.top/Article/details/gt2qxnlpizk.html

TS:   /error/gim
来源：http://dali.yueranfly.top/Article/details/gt2cozblmhe.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.yonumen.top/Article/details/gt2ebyfzdpy.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.wangdashe.top/Article/details/gt2dipypwsb.html

Ruby: s.scan(/error/i)
来源：http://dali.aibaodan.cn/Article/details/gt2adwsjtyg.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.ybcxt.top/Article/details/gt2nbsmxxfh.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2tiuwbwtb.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.zhijiandao.cn/Article/details/gt2qccgujpn.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.zhengqikj.top/Article/details/gt2qtomefvx.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xziqi.cn/Article/details/gt2tficiokf.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.zycfv.cn/Article/details/gt2dzaxyvbx.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nzaizeoy.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.yongpay.top/Article/details/gt2itgcnkkd.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.ydzc1.top/Article/details/gt2vwzybuqt.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.cqqwz.cn/Article/details/gt2dfemuyxr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ylwskcfb.html

J. 日期与时间
来源：http://dali.yonumen.top/Article/details/gt2librpkkr.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2nlvqzdri.html

[J01] 获取当前时间
来源：http://dali.andypj.xyz/Article/details/gt2golnvtly.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.zhoulong.xyz/Article/details/gt2glcbityc.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.gaohongyu789.top/Article/details/gt2mxbotivq.html

JS:   new Date();  Date.now()
来源：http://dali.sweek.top/Article/details/gt2rubggacn.html

TS:   new Date();  Date.now()
来源：http://dali.jqgufenzy.top/Article/details/gt2exzqwpyt.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.0kj1m.cn/Article/details/gt2jdjwahik.html

Go:   time.Now()
来源：http://dali.fengsongda.top/Article/details/gt2vobqniic.html

Ruby: Time.now
来源：http://dali.sxryk.cn/Article/details/gt2jdwdunzx.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jqgufenzy.top/Article/details/gt2aoqdpokd.html

[J02] 格式化输出
来源：http://dali.snrcjt.cn/Article/details/gt2nmjkjord.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rzgishkc.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.jinqigfzy.top/Article/details/gt2bhmhspnd.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.9152youxi.cn/Article/details/gt2ftoyysvw.html

TS:   d.toISOString()
来源：http://dali.jyoumei.cn/Article/details/gt2lgugyfao.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.dianchejie.cn/Article/details/gt2bhmdnvqw.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.cqqwz.cn/Article/details/gt2xvpklnpu.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.xinyue.icu/Article/details/gt2chttjvig.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.daria6918.cn/Article/details/gt2gydhxfff.html

[J03] 字符串解析为日期
来源：http://dali.jianghu66.top/Article/details/gt2dgmdcvwg.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.9152youxi.cn/Article/details/gt2rjmnxvkp.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.wangshuangyany.cn/Article/details/gt2hzxvrnla.html

JS:   new Date("2024-01-02")
来源：http://dali.xylfe.cn/Article/details/gt2gdjpdvbo.html

TS:   new Date("2024-01-02")
来源：http://dali.yangfankeji.com/Article/details/gt2dypfhqol.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.zhoulong.xyz/Article/details/gt2cgothfsj.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.tanke756.top/Article/details/gt2ntpnaejl.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.xinyue.icu/Article/details/gt2uauyqvxj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.redwolf501.top/Article/details/gt2hqcnimey.html

[J04] 时间戳与日期互转
来源：http://dali.hnxiangtu.top/Article/details/gt2drhfkmen.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.jqgufenzy.top/Article/details/gt2omgeaxbt.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.sweek.top/Article/details/gt2kaijiwyj.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.jqgufenzy.top/Article/details/gt2tuvbetgi.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.yueranfly.top/Article/details/gt2qfuwadvy.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.jiagoushi.top/Article/details/gt2rspycdvw.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.cheryme.top/Article/details/gt2zxufvups.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.meibo888.top/Article/details/gt2jfhzpmob.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ytfkmlvn.html

[J05] 时间加减（加 7 天）
来源：http://dali.havefunace.top/Article/details/gt2pdfikwai.html

Py:   now + timedelta(days=7)
来源：http://dali.aibaodan.cn/Article/details/gt2nerbhzue.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.yueranfly.top/Article/details/gt2wsaujhax.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.cheryme.top/Article/details/gt2ldmfiluy.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.yueranfly.top/Article/details/gt2icivuded.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftkzywwt.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.yj20258888.top/Article/details/gt2wtgfbeuw.html

Ruby: Time.now + 7 * 86400
来源：http://dali.yonumen.top/Article/details/gt2ncmaywgi.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.iojbl.cn/Article/details/gt2droalzse.html

[J06] 计算两时间之差
来源：http://dali.wangdashe.top/Article/details/gt2xvrhlgjw.html

Py:   (end - start).total_seconds()
来源：http://dali.yonumen.top/Article/details/gt2rvqcblzc.html

PHP:  $end->diff($start)->days;
来源：http://dali.ydzc1.top/Article/details/gt2rxdksllb.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.ivvv.top/Article/details/gt2vskydqdc.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2urphglju.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.jyoumei.cn/Article/details/gt2ghcqsymx.html

Go:   end.Sub(start).Hours()
来源：http://dali.xuetiantiany.cn/Article/details/gt2frrrfvdn.html

Ruby: end - start                 # 返回秒数
来源：http://dali.andypj.xyz/Article/details/gt2qvgevxex.html

C#:   (end - start).TotalSeconds
来源：http://dali.fengsongda.top/Article/details/gt2qbgolszb.html

[J07] 比较两个日期
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmdaelq.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.andypj.xyz/Article/details/gt2lttkrszb.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.nanxuanxn.top/Article/details/gt2dtnklhmp.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.yj202588.top/Article/details/gt2glzsohlc.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rdhivonv.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.quarkkingdee.top/Article/details/gt2uhnylcay.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.tianlin.xyz/Article/details/gt2cbpneppo.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.dashuyun.cn/Article/details/gt2fdfqmzkq.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.yangfankeji.com/Article/details/gt2wepokdwy.html

[J08] 提取年月日与星期
来源：http://dali.nanxuanxn.top/Article/details/gt2bebqhprt.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.fengsongda.top/Article/details/gt2xxasmgzy.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.316326.xyz/Article/details/gt2uhvjbuow.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxinkj.top/Article/details/gt2gfdcinoa.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.vqdsnc.cn/Article/details/gt2cdzoklhd.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.yonumen.top/Article/details/gt2oohctbno.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.yanxiufei.cn/Article/details/gt2bnbchvjx.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.tanke756.top/Article/details/gt2oslyethx.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2udvjgkqs.html

[J09] 时区处理
来源：http://dali.zhixingplan.top/Article/details/gt2cvcoxnek.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zycfv.cn/Article/details/gt2msuqqdvm.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.jqgfzy.top/Article/details/gt2qgnjipje.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.aibaodan.cn/Article/details/gt2tmcbhrvv.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.pycfn.com/Article/details/gt2qpiyrcnw.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.ppjwa.cn/Article/details/gt2edikwhie.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.ppjwa.cn/Article/details/gt2onoogeuo.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.ivvv.top/Article/details/gt2pgkvblcb.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.vqdsnc.cn/Article/details/gt2ylfmtqmh.html

[J10] 取今天 / 本月第一天
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqhlnuki.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenlongwang.top/Article/details/gt2mkkfxuqf.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.chenzaomai.com/Article/details/gt2lyfknhpk.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.mhx1999.top/Article/details/gt2odqnlvya.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nvkcqsez.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.kuanghao11.cn/Article/details/gt2tukuxsbh.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.aibaodan.cn/Article/details/gt2wpzqvvnb.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.xinyue.icu/Article/details/gt2dzcapfzf.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.sysykeji.top/Article/details/gt2wrjpbgkb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2ysnlgezi.html

K. JSON 与序列化
来源：http://dali.daria6918.cn/Article/details/gt2wfxzktio.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2hllprchm.html

[K01] 对象转 JSON 字符串
来源：http://dali.shuidangran.top/Article/details/gt2lyyjhcno.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.haohaochexian.top/Article/details/gt2lhjzzgnq.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.ydzc1.top/Article/details/gt2ywdbuiby.html

JS:   JSON.stringify(obj)
来源：http://dali.tanke756.top/Article/details/gt2mehdqqex.html

TS:   JSON.stringify(obj)
来源：http://dali.zhengqikj.top/Article/details/gt2loulbdpx.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.wangshuangyany.cn/Article/details/gt2nylecgqx.html

Go:   json.Marshal(obj)
来源：http://dali.daxiang520.top/Article/details/gt2lccknsfw.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.yangfankeji.com/Article/details/gt2mhabuwmg.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.gzhubu.top/Article/details/gt2iyjbtjdw.html

[K02] JSON 字符串转对象
来源：http://dali.meibo888.top/Article/details/gt2llzctxmw.html

Py:   json.loads(s)
来源：http://dali.sufxvd.cn/Article/details/gt2tarkcunu.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.cucudq.cn/Article/details/gt2pvtwvqfx.html

JS:   JSON.parse(s)
来源：http://dali.zhixingplan.top/Article/details/gt2oqbzmgap.html

TS:   JSON.parse(s)
来源：http://dali.snrcjt.cn/Article/details/gt2yjrjiicv.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.quarkkingdee.top/Article/details/gt2lhtvokld.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.meibo888.top/Article/details/gt2oahobglw.html

Ruby: JSON.parse(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2kjvhujmq.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.9152youxi.cn/Article/details/gt2ooqfuaba.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.mhx1999.top/Article/details/gt2fnlagcwn.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.jqgfzy.top/Article/details/gt2lusgcmnv.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.tianlin.xyz/Article/details/gt2gezrdbtz.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.daria6918.cn/Article/details/gt2ydsriijq.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.birdmap.top/Article/details/gt2xbzmmfei.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.shzxlz.cn/Article/details/gt2gcqunlrk.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.redwolf501.top/Article/details/gt2acczeiap.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2gpftflxs.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.xuetiantiany.cn/Article/details/gt2agvljayw.html

[K04] 读取 JSON 文件
来源：http://dali.yj202588.top/Article/details/gt2lfoqfkyz.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.cashguo.top/Article/details/gt2zeqjluhx.html


<!-- 参考信息 -->