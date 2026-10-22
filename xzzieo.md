代发 wailian999

C#:   throw new ArgumentException("错误信息");
来源：http://dali.cheryme.top/Article/details/gt2uabtdxdl.html

[H04] 自定义异常类型
来源：http://dali.ydzc1.top/Article/details/gt2mrggyslm.html

Py:   class MyError(Exception): pass
来源：http://dali.shuidangran.top/Article/details/gt2mnokzbqr.html

PHP:  class MyError extends RuntimeException {}
来源：http://dali.yj20258.top/Article/details/gt2bkobxtgu.html

JS:   class MyError extends Error {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2lzzxrmjz.html

TS:   class MyError extends Error {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2afkjqtjh.html

Java: class MyException extends RuntimeException {}
来源：http://dali.nanxinkj.top/Article/details/gt2mxxtwkag.html

Go:   type MyError struct{ Msg string };  func (e MyError) Error() string { return e.Msg }
来源：http://dali.hnqzz.top/Article/details/gt2gqhpqrpx.html

Ruby: class MyError < StandardError; end
来源：http://dali.ydzc1.top/Article/details/gt2dnfcgfcl.html

C#:   class MyException : Exception {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2zizhjtsd.html

[H05] 捕获特定类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nrpaaqrg.html

Py:   except ValueError as e:
来源：http://dali.tian-w.cn/Article/details/gt2mpshdtpi.html

PHP:  catch (InvalidArgumentException | RuntimeException $e) {}   // 支持多类型
来源：http://dali.chenlongwang.top/Article/details/gt2fbfldpar.html

JS:   if (e instanceof TypeError) {}
来源：http://dali.gogol.net.cn/Article/details/gt2eukxjodg.html

TS:   if (e instanceof TypeError) {}
来源：http://dali.aizwys.cn/Article/details/gt2sfpicxby.html

Java: catch (IOException | SQLException e) {}
来源：http://dali.zhixingplan.top/Article/details/gt2lbibhptm.html

Go:   errors.Is(err, os.ErrNotExist)
来源：http://dali.zycfv.cn/Article/details/gt2psanolyr.html

Ruby: rescue ArgumentError => e
来源：http://dali.chenjidiqi.icu/Article/details/gt2sprrvyqg.html

C#:   catch (IOException e) when (e.HResult == -1) {}
来源：http://dali.sufxvd.cn/Article/details/gt2pupscmlh.html

[H06] 可选值 / 空值安全访问
来源：http://dali.cheryme.top/Article/details/gt2bpyvlxfy.html

Py:   value = d.get("k") or default
来源：http://dali.dianchejie.cn/Article/details/gt2asqvzxnv.html

PHP:  $v = $d["k"] ?? null;
来源：http://dali.hywenlv.cn/Article/details/gt2mplbcpiv.html

JS:   obj?.a?.b;  d ?? default
来源：http://dali.tanke756.top/Article/details/gt2vvsiqkmq.html

TS:   obj?.a?.b;  d ?? default
来源：http://dali.feifeiyinyue.top/Article/details/gt2meyhxlxe.html

Java: Optional.ofNullable(x).map(...).orElse(default)
来源：http://dali.zhengqikj.top/Article/details/gt2ubdkrhfh.html

Go:   if v, ok := m["k"]; ok { }
来源：http://dali.yonumen.top/Article/details/gt2cqblmzoy.html

Ruby: d&.dig(:a, :b)
来源：http://dali.tianlin.xyz/Article/details/gt2roxqgxbh.html

C#:   obj?.A?.B ?? default
来源：http://dali.gogol.net.cn/Article/details/gt2zrqdzaxy.html

[H07] 断言
来源：http://dali.gzhubu.top/Article/details/gt2tczmvsbu.html

Py:   assert x > 0, "必须为正"
来源：http://dali.zycfv.cn/Article/details/gt2lhloeued.html

PHP:  assert($x > 0);
来源：http://dali.smart0.xyz/Article/details/gt2gwiekpwn.html

JS:   console.assert(x > 0);
来源：http://dali.gogol.net.cn/Article/details/gt2esbkikzm.html

TS:   console.assert(x > 0);
来源：http://dali.zhengqikj.top/Article/details/gt2heijfwcd.html

Java: assert x > 0 : "必须为正";
来源：http://dali.pengpengdd.cyou/Article/details/gt2legrpsrx.html

Go:   // 无 assert：手写 if 后 panic 或返回错误
来源：http://dali.daria6918.cn/Article/details/gt2sjkkbkev.html

Ruby: raise "必须为正" unless x > 0
来源：http://dali.ybcxt.top/Article/details/gt2qmiobjkf.html

C#:   Debug.Assert(x > 0);
来源：http://dali.hnqzz.top/Article/details/gt2ushesdqf.html

[H08] 获取错误信息与堆栈
来源：http://dali.havefunace.top/Article/details/gt2uwvmevll.html

Py:   str(e);  traceback.format_exc()
来源：http://dali.jiagoushi.top/Article/details/gt2fksxjmky.html

PHP:  $e->getMessage();  $e->getTraceAsString();
来源：http://dali.nanxuanxn.top/Article/details/gt2gcnblttm.html

JS:   e.message;  e.stack
来源：http://dali.haohaochexian.top/Article/details/gt2wtjnunmf.html

TS:   e instanceof Error ? e.message : String(e)
来源：http://dali.ivvv.top/Article/details/gt2qcjjidaa.html

Java: e.getMessage();  e.printStackTrace()
来源：http://dali.hysaishi.cn/Article/details/gt2flqcbpca.html

Go:   err.Error()
来源：http://dali.vqdsnc.cn/Article/details/gt2drqtjoce.html

Ruby: e.message;  e.backtrace
来源：http://dali.xylfe.cn/Article/details/gt2egdsxdnj.html

C#:   e.Message;  e.StackTrace
来源：http://dali.zhongyouzk.top/Article/details/gt2bftbrhbs.html

[H09] 带错误码的异常
来源：http://dali.chenlongwang.top/Article/details/gt2qchstewr.html

Py:   class HttpError(Exception):⏎    def __init__(self, msg, code): self.code = code
来源：http://dali.hnxiangtu.top/Article/details/gt2oujrwdfj.html

PHP:  throw new RuntimeException("fail", 500);
来源：http://dali.yanxiufei.cn/Article/details/gt2ludnwpxn.html

JS:   const err = new Error("fail");  err.code = 500;
来源：http://dali.ybcxt.top/Article/details/gt2llsyuonp.html

TS:   class HttpError extends Error { constructor(public status: number) { super("fail"); } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2thdlfrtl.html

Java: class HttpException extends RuntimeException { private final int code; }
来源：http://dali.zhengqikj.top/Article/details/gt2ytoablag.html

Go:   return fmt.Errorf("%w", ErrNotFound)     // 用 sentinel error 判断
来源：http://dali.havefunace.top/Article/details/gt2gnpfwyui.html

Ruby: raise MyError.new("fail", 500)
来源：http://dali.pengpengdd.cyou/Article/details/gt2llgmpgsx.html

C#:   // 自定义异常类中加 Code 属性
来源：http://dali.jiagoushi.top/Article/details/gt2xcipojqx.html

[H10] 资源自动释放
来源：http://dali.jianghu66.top/Article/details/gt2gfamaewq.html

Py:   with open("a.txt") as f: data = f.read()
来源：http://dali.redwolf501.top/Article/details/gt2sirhinyk.html

PHP:  // 无 with：在 finally 里 fclose()
来源：http://dali.xziqi.cn/Article/details/gt2dwiznmgh.html

JS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.tanke756.top/Article/details/gt2nllzmdvq.html

TS:   // 无 with：在 finally 里关闭句柄
来源：http://dali.xuanzx.com/Article/details/gt2baxyqeiy.html

Java: try (var in = new FileInputStream("a")) { }   // try-with-resources
来源：http://dali.fzhhl.top/Article/details/gt2sayarafp.html

Go:   defer f.Close()
来源：http://dali.guannengcc.top/Article/details/gt2qpgldemv.html

Ruby: File.open("a.txt") { |f| f.read }
来源：http://dali.daxiang520.top/Article/details/gt2tjupogph.html

C#:   using var stream = File.OpenRead("a.txt");
来源：http://dali.zhijiandao.cn/Article/details/gt2rkccyjsg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2vzcmtbro.html

I. 正则表达式
来源：http://dali.nwbrower.top/Article/details/gt2divmswrq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2szyamdtn.html

[I01] 判断是否匹配
来源：http://dali.zhixingplan.top/Article/details/gt2ajegevqa.html

Py:   re.search(r"\d+", s);  re.fullmatch(r"\d+", s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zoqywfkj.html

PHP:  preg_match('/\d+/', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2glowqekk.html

JS:   /\d+/.test(s)
来源：http://dali.jlsjyb.cn/Article/details/gt2iwtuehgo.html

TS:   /\d+/.test(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2wbrrjmmm.html

Java: Pattern.compile("\\d+").matcher(s).find()
来源：http://dali.haohaochexian.top/Article/details/gt2cyrixvia.html

Go:   regexp.MustCompile(`\d+`).MatchString(s)
来源：http://dali.ydzc1.top/Article/details/gt2lwutpfnl.html

Ruby: s.match?(/\d+/)
来源：http://dali.smart0.xyz/Article/details/gt2etikagog.html

C#:   Regex.IsMatch(s, @"\d+")
来源：http://dali.fengsongda.top/Article/details/gt2nzshhwdk.html

[I02] 提取所有匹配
来源：http://dali.ivvv.top/Article/details/gt2waiijkwp.html

Py:   re.findall(r"\d+", s)
来源：http://dali.yuxming.cn/Article/details/gt2fsoufmax.html

PHP:  preg_match_all('/\d+/', $s, $m);  $m[0]
来源：http://dali.aizwys.cn/Article/details/gt2ugnyhwim.html

JS:   s.match(/\d+/g);  [...s.matchAll(/\d+/g)]
来源：http://dali.chenzaomai.com/Article/details/gt2iouevfsq.html

TS:   s.match(/\d+/g)
来源：http://dali.jinqigufen.top/Article/details/gt2ixzpefyl.html

Java: Pattern.compile("\\d+").matcher(s).results().toList()
来源：http://dali.gzhubu.top/Article/details/gt2ezrgpeeo.html

Go:   regexp.MustCompile(`\d+`).FindAllString(s, -1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2omefadyt.html

Ruby: s.scan(/\d+/)
来源：http://dali.wangdashe.top/Article/details/gt2wkcelfem.html

C#:   Regex.Matches(s, @"\d+").Select(m => m.Value).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2fwexerlv.html

[I03] 提取捕获分组
来源：http://dali.yj20258.top/Article/details/gt2achxnwjg.html

Py:   m = re.search(r"(\d+)-(\d+)", s);  m.group(1)
来源：http://dali.xinyue.icu/Article/details/gt2awdkpvjg.html

PHP:  preg_match('/(\d+)-(\d+)/', $s, $m);  $m[1]
来源：http://dali.guowangkeji.top/Article/details/gt2eidakphw.html

JS:   const m = s.match(/(\d+)-(\d+)/);  m[1]
来源：http://dali.mhx1999.top/Article/details/gt2ofuacnql.html

TS:   const m = s.match(/(\d+)-(\d+)/);  m?.[1]
来源：http://dali.yj20258.top/Article/details/gt2vuqcgela.html

Java: Matcher m = p.matcher(s);  if (m.find()) m.group(1);
来源：http://dali.c1oappe.top/Article/details/gt2dhuccqwh.html

Go:   m := re.FindStringSubmatch(s);  m[1]     // [0] 是整段
来源：http://dali.birdmap.top/Article/details/gt2rfciqmdb.html

Ruby: s.match(/(\d+)-(\d+)/)[1]
来源：http://dali.sufxvd.cn/Article/details/gt2xsbyhvov.html

C#:   Regex.Match(s, @"(\d+)-(\d+)").Groups[1].Value
来源：http://dali.jinghuilouyu.cn/Article/details/gt2goojtair.html

[I04] 正则替换
来源：http://dali.c1oappe.top/Article/details/gt2fswonwuo.html

Py:   re.sub(r"\d+", "#", s)
来源：http://dali.hnqzz.top/Article/details/gt2lrjxrdhu.html

PHP:  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gt2nhvkxshu.html

JS:   s.replace(/\d+/g, "#")
来源：http://dali.0kj1m.cn/Article/details/gt2yvjzybrs.html

TS:   s.replace(/\d+/g, "#")
来源：http://dali.ybcxt.top/Article/details/gt2cxtejurc.html

Java: s.replaceAll("\\d+", "#")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gnuzhwvd.html

Go:   re.ReplaceAllString(s, "#")
来源：http://dali.jiagoushi.top/Article/details/gt2zrltmykp.html

Ruby: s.gsub(/\d+/, "#")
来源：http://dali.ybcxt.top/Article/details/gt2vekkwnut.html

C#:   Regex.Replace(s, @"\d+", "#")
来源：http://dali.jianghu66.top/Article/details/gt2idhmcjjg.html

[I05] 按正则拆分
来源：http://dali.zhiwuduotai.top/Article/details/gt2qraswuoy.html

Py:   re.split(r"\s*,\s*", s)
来源：http://dali.ppjwa.cn/Article/details/gt2ztyovgkw.html

PHP:  preg_split('/\s*,\s*/', $s);
来源：http://dali.smart0.xyz/Article/details/gt2zqivywng.html

JS:   s.split(/\s*,\s*/)
来源：http://dali.jinqigufen.top/Article/details/gt2kujlnpte.html

TS:   s.split(/\s*,\s*/)
来源：http://dali.gotoacloud.top/Article/details/gt2hqgtsuxp.html

Java: s.split("\\s*,\\s*")
来源：http://dali.guowangkeji.top/Article/details/gt2tbmejspd.html

Go:   regexp.MustCompile(`\s*,\s*`).Split(s, -1)
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjkysxyt.html

Ruby: s.split(/\s*,\s*/)
来源：http://dali.hfpthk.cn/Article/details/gt2rflpxkmd.html

C#:   Regex.Split(s, @"\s*,\s*")
来源：http://dali.ppjwa.cn/Article/details/gt2xpiadxny.html

[I06] 常用校验模式（邮箱 / 手机号）
来源：http://dali.mhx1999.top/Article/details/gt2ihcpzpao.html

Py:   r"[^@]+@[^@]+\.[^@]+"；r"^1[3-9]\d{9}$"
来源：http://dali.cqqwz.cn/Article/details/gt2nsutmbff.html

PHP:  '/^[^\s@]+@[^\s@]+\.[^\s@]+$/'；'/^1[3-9]\d{9}$/'
来源：http://dali.316326.xyz/Article/details/gt2ytlmeusw.html

JS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.yuanzhike.top/Article/details/gt2lmcdedgy.html

TS:   /^[^\s@]+@[^\s@]+\.[^\s@]+$/；/^1[3-9]\d{9}$/
来源：http://dali.haohaochexian.top/Article/details/gt2gwtsxrgq.html

Java: "^[\\w.+-]+@[\\w-]+\\.[\\w.]+$"；"^1[3-9]\\d{9}$"
来源：http://dali.yj20258888.top/Article/details/gt2jihmfyyt.html

Go:   `^[\w.+-]+@[\w-]+\.[\w.]+$`   // RE2 不支持反向引用与前瞻
来源：http://dali.ppjwa.cn/Article/details/gt2otzeoprh.html

Ruby: /\A[\w.+-]+@[\w-]+\.[\w.]+\z/；/\A1[3-9]\d{9}\z/
来源：http://dali.sufxvd.cn/Article/details/gt2juboerpn.html

C#:   @"^[\w.+-]+@[\w-]+\.[\w.]+$"；@"^1[3-9]\d{9}$"
来源：http://dali.jqgfzy.top/Article/details/gt2vyyypejn.html

[I07] 忽略大小写与多行模式
来源：http://dali.ybcxt.top/Article/details/gt2qmslxuvt.html

Py:   re.findall(r"error", s, re.I | re.M)
来源：http://dali.c1oappe.top/Article/details/gt2hawsuvwa.html

PHP:  preg_match_all('/error/im', $s, $m);
来源：http://dali.ydzc1.top/Article/details/gt2lbuljbkx.html

JS:   /error/gim；new RegExp("error", "gim")
来源：http://dali.gotoacloud.top/Article/details/gt2awjdelkk.html

TS:   /error/gim
来源：http://dali.xylfe.cn/Article/details/gt2enhnwxqk.html

Java: Pattern.compile("error", Pattern.CASE_INSENSITIVE | Pattern.MULTILINE)
来源：http://dali.svipenyu.cn/Article/details/gt2qnjjjyhh.html

Go:   regexp.MustCompile(`(?im)error`)
来源：http://dali.sxryk.cn/Article/details/gt2jcrvxgqb.html

Ruby: s.scan(/error/i)
来源：http://dali.shzxlz.cn/Article/details/gt2pamnoddc.html

C#:   Regex.Match(s, "error", RegexOptions.IgnoreCase | RegexOptions.Multiline)
来源：http://dali.jinqigufen.top/Article/details/gt2iinkczou.html

[I08] 贪婪与非贪婪匹配
来源：http://dali.hysaishi.cn/Article/details/gt2fwfndwmi.html

Py:   re.findall(r"<b>.*?</b>", s)       # 加 ? 变非贪婪
来源：http://dali.xylfe.cn/Article/details/gt2dmxljtjg.html

PHP:  preg_match_all('/<b>.*?<\/b>/', $s, $m);
来源：http://dali.yongpay.top/Article/details/gt2cwyqnabg.html

JS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kkonqnsm.html

TS:   s.match(/<b>.*?<\/b>/g)
来源：http://dali.jinqigufen.top/Article/details/gt2zqaqcgnc.html

Java: Pattern.compile("<b>.*?</b>")
来源：http://dali.hnxiangtu.top/Article/details/gt2jbfpqqcg.html

Go:   `<b>.*?</b>`                      # RE2 默认贪婪，同样用 ? 抑制
来源：http://dali.vqdsnc.cn/Article/details/gt2jmtxocqz.html

Ruby: s.scan(/<b>.*?<\/b>/)
来源：http://dali.snrcjt.cn/Article/details/gt2bwatdkbi.html

C#:   Regex.Matches(s, @"<b>.*?</b>")
来源：http://dali.gotoacloud.top/Article/details/gt2rjanhnkq.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2ekdczheq.html

J. 日期与时间
来源：http://dali.hysaishi.cn/Article/details/gt2jvbilabk.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2ujmxdcjn.html

[J01] 获取当前时间
来源：http://dali.andypj.xyz/Article/details/gt2xmoednof.html

Py:   datetime.now();  datetime.now(UTC)
来源：http://dali.hammf.cn/Article/details/gt2btlyeinr.html

PHP:  new DateTimeImmutable();  date("Y-m-d H:i:s");
来源：http://dali.pengpengdd.cyou/Article/details/gt2fbckhlgu.html

JS:   new Date();  Date.now()
来源：http://dali.zhiwuduotai.top/Article/details/gt2numpufub.html

TS:   new Date();  Date.now()
来源：http://dali.jlsjyb.cn/Article/details/gt2eqroknsu.html

Java: LocalDateTime.now();  Instant.now()
来源：http://dali.yanxiufei.cn/Article/details/gt2rfstaxzw.html

Go:   time.Now()
来源：http://dali.xuetiantiany.cn/Article/details/gt2erctpnwu.html

Ruby: Time.now
来源：http://dali.hywenlv.cn/Article/details/gt2jeddbglg.html

C#:   DateTime.Now;  DateTime.UtcNow
来源：http://dali.jlsjyb.cn/Article/details/gt2gvqgltom.html

[J02] 格式化输出
来源：http://dali.yueranfly.top/Article/details/gt2vidwvfxr.html

Py:   now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.dianchejie.cn/Article/details/gt2tcbkoeci.html

PHP:  (new DateTime())->format("Y-m-d H:i:s");
来源：http://dali.ydzc1.top/Article/details/gt2hiljloaa.html

JS:   d.toISOString();  d.toLocaleString("zh-CN")
来源：http://dali.gotoacloud.top/Article/details/gt2ybvhhjbc.html

TS:   d.toISOString()
来源：http://dali.ybcxt.top/Article/details/gt2tybmincd.html

Java: DateTimeFormatter.ofPattern("yyyy-MM-dd HH:mm:ss").format(LocalDateTime.now())
来源：http://dali.yanxiufei.cn/Article/details/gt2vzuhxrer.html

Go:   time.Now().Format("2006-01-02 15:04:05")     // Go 用参考时间做格式
来源：http://dali.yanxiufei.cn/Article/details/gt2hxjnrocx.html

Ruby: Time.now.strftime("%Y-%m-%d %H:%M:%S")
来源：http://dali.svipenyu.cn/Article/details/gt2metmfssr.html

C#:   DateTime.Now.ToString("yyyy-MM-dd HH:mm:ss")
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgauybz.html

[J03] 字符串解析为日期
来源：http://dali.ehwqpu.com/Article/details/gt2dnzkvhkc.html

Py:   datetime.strptime("2024-01-02", "%Y-%m-%d")
来源：http://dali.daxiang520.top/Article/details/gt2duoonadk.html

PHP:  DateTimeImmutable::createFromFormat("Y-m-d", "2024-01-02");
来源：http://dali.ydzc1.top/Article/details/gt2ggdyzxog.html

JS:   new Date("2024-01-02")
来源：http://dali.wangshuangyany.cn/Article/details/gt2jepaajum.html

TS:   new Date("2024-01-02")
来源：http://dali.hysaishi.cn/Article/details/gt2jddfaeoo.html

Java: LocalDate.parse("2024-01-02")
来源：http://dali.sweek.top/Article/details/gt2htatffrs.html

Go:   time.Parse("2006-01-02", "2024-01-02")
来源：http://dali.chenlongwang.top/Article/details/gt2rshwrndv.html

Ruby: Date.parse("2024-01-02")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xehdwcvj.html

C#:   DateTime.Parse("2024-01-02");  DateTime.ParseExact("2024-01-02", "yyyy-MM-dd", null)
来源：http://dali.jiagoushi.top/Article/details/gt2xjweskcj.html

[J04] 时间戳与日期互转
来源：http://dali.tianlin.xyz/Article/details/gt2pebapgxg.html

Py:   int(now.timestamp());  datetime.fromtimestamp(ts)
来源：http://dali.9152youxi.cn/Article/details/gt2vqesyulg.html

PHP:  time();  (new DateTime())->getTimestamp();
来源：http://dali.andypj.xyz/Article/details/gt2ehqrbtsq.html

JS:   Math.floor(Date.now() / 1000);  new Date(ts * 1000)
来源：http://dali.yongpay.top/Article/details/gt2mskxuulz.html

TS:   Math.floor(Date.now() / 1000)
来源：http://dali.gzhubu.top/Article/details/gt2yhxbqrfx.html

Java: Instant.now().getEpochSecond();  Instant.ofEpochSecond(ts)
来源：http://dali.meibo888.top/Article/details/gt2xhjvqlnx.html

Go:   time.Now().Unix();  time.Unix(ts, 0)
来源：http://dali.yj20258.top/Article/details/gt2cjedneik.html

Ruby: Time.now.to_i;  Time.at(ts)
来源：http://dali.jqgfzy.top/Article/details/gt2zdsnpyix.html

C#:   DateTimeOffset.UtcNow.ToUnixTimeSeconds();  DateTimeOffset.FromUnixTimeSeconds(ts)
来源：http://dali.zhoulong.xyz/Article/details/gt2kjtogpuc.html

[J05] 时间加减（加 7 天）
来源：http://dali.shzxlz.cn/Article/details/gt2yxtysexa.html

Py:   now + timedelta(days=7)
来源：http://dali.ybcxt.top/Article/details/gt2qpwtbvsk.html

PHP:  (new DateTime())->modify("+7 days");
来源：http://dali.guowangkeji.top/Article/details/gt2dresrzyr.html

JS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.hnqzz.top/Article/details/gt2jpmrqkmv.html

TS:   new Date(Date.now() + 7 * 86400000)
来源：http://dali.0kj1m.cn/Article/details/gt2odryhrrl.html

Java: LocalDate.now().plusDays(7)
来源：http://dali.c1oappe.top/Article/details/gt2ndgzscxu.html

Go:   time.Now().AddDate(0, 0, 7)
来源：http://dali.chenlongwang.top/Article/details/gt2llertjwb.html

Ruby: Time.now + 7 * 86400
来源：http://dali.havefunace.top/Article/details/gt2mzydhsky.html

C#:   DateTime.Now.AddDays(7)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owsqwfyr.html

[J06] 计算两时间之差
来源：http://dali.wangshuangyany.cn/Article/details/gt2qhigipfg.html

Py:   (end - start).total_seconds()
来源：http://dali.jiagoushi.top/Article/details/gt2bhmwrktc.html

PHP:  $end->diff($start)->days;
来源：http://dali.feifeiyinyue.top/Article/details/gt2sycidlnm.html

JS:   (end - start) / 1000        // 毫秒差转秒
来源：http://dali.daria6918.cn/Article/details/gt2aniuxymd.html

TS:   (end.getTime() - start.getTime()) / 1000
来源：http://dali.guowangkeji.top/Article/details/gt2yvygbapv.html

Java: Duration.between(start, end).toSeconds()
来源：http://dali.yonumen.top/Article/details/gt2utnzjgot.html

Go:   end.Sub(start).Hours()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ughgxlis.html

Ruby: end - start                 # 返回秒数
来源：http://dali.wangdashe.top/Article/details/gt2yuhcygdq.html

C#:   (end - start).TotalSeconds
来源：http://dali.cashguo.top/Article/details/gt2tsbflocg.html

[J07] 比较两个日期
来源：http://dali.hnqzz.top/Article/details/gt2hnrtspnx.html

Py:   d1 < d2;  d1 == d2
来源：http://dali.pengpengdd.cyou/Article/details/gt2xepgniyy.html

PHP:  $d1 < $d2;  $d1 == $d2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jynfdoxr.html

JS:   d1.getTime() < d2.getTime()
来源：http://dali.vqdsnc.cn/Article/details/gt2ucfcpqww.html

TS:   d1.getTime() < d2.getTime()
来源：http://dali.cqqwz.cn/Article/details/gt2jnpzngbl.html

Java: d1.isBefore(d2);  d1.isEqual(d2)
来源：http://dali.hammf.cn/Article/details/gt2xvoeiuai.html

Go:   d1.Before(d2);  d1.Equal(d2)
来源：http://dali.yanxiufei.cn/Article/details/gt2hwalnswh.html

Ruby: d1 < d2;  d1 == d2
来源：http://dali.yuanzhike.top/Article/details/gt2fdrqggww.html

C#:   d1 < d2;  d1 == d2
来源：http://dali.redwolf501.top/Article/details/gt2wlrgmngn.html

[J08] 提取年月日与星期
来源：http://dali.0kj1m.cn/Article/details/gt2prbxzjaj.html

Py:   d.year;  d.month;  d.day;  d.weekday()
来源：http://dali.zhixingplan.top/Article/details/gt2fjswhvyk.html

PHP:  (int) date("Y");  (int) date("n");  (int) date("j");  (int) date("w");
来源：http://dali.snrcjt.cn/Article/details/gt2nbxivlfp.html

JS:   d.getFullYear();  d.getMonth() + 1;  d.getDate();  d.getDay()
来源：http://dali.nanxinkj.top/Article/details/gt2yhcbnlzv.html

TS:   d.getFullYear();  d.getMonth() + 1;  d.getDate()
来源：http://dali.yonumen.top/Article/details/gt2qizjvedh.html

Java: ld.getYear();  ld.getMonthValue();  ld.getDayOfMonth()
来源：http://dali.gzhubu.top/Article/details/gt2kjpataak.html

Go:   t.Year();  int(t.Month());  t.Day();  int(t.Weekday())
来源：http://dali.dashuyun.cn/Article/details/gt2ognjnrzy.html

Ruby: d.year;  d.month;  d.day;  d.wday
来源：http://dali.vqdsnc.cn/Article/details/gt2dzdkwqab.html

C#:   d.Year;  d.Month;  d.Day;  (int)d.DayOfWeek
来源：http://dali.svipenyu.cn/Article/details/gt2eqetxkdf.html

[J09] 时区处理
来源：http://dali.nwbrower.top/Article/details/gt2mvtzmhak.html

Py:   ZoneInfo("Asia/Shanghai");  now.astimezone(tz)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pqvxiaxn.html

PHP:  new DateTimeZone("Asia/Shanghai");
来源：http://dali.birdmap.top/Article/details/gt2ddqorzoj.html

JS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.nanxuanxn.top/Article/details/gt2rgjiiuxt.html

TS:   Intl.DateTimeFormat("zh-CN", { timeZone: "Asia/Shanghai" }).format(d)
来源：http://dali.yuxming.cn/Article/details/gt2dtqrxrrg.html

Java: ZoneId.of("Asia/Shanghai");  ZonedDateTime.now(zone)
来源：http://dali.nanxuanxn.top/Article/details/gt2cvbayvov.html

Go:   time.LoadLocation("Asia/Shanghai");  time.Now().In(loc)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvoihwv.html

Ruby: Time.now.getlocal("+08:00")
来源：http://dali.zhoulong.xyz/Article/details/gt2vehpenca.html

C#:   TimeZoneInfo.FindSystemTimeZoneById("China Standard Time")
来源：http://dali.chenlongwang.top/Article/details/gt2ktptusdx.html

[J10] 取今天 / 本月第一天
来源：http://dali.zdqjudy.top/Article/details/gt2wtwsfbmh.html

Py:   date.today();  date.today().replace(day=1)
来源：http://dali.chenzaomai.com/Article/details/gt2jmuazuhh.html

PHP:  new DateTime("today");  new DateTime("first day of this month");
来源：http://dali.fzhhl.top/Article/details/gt2xflnjljc.html

JS:   new Date().setHours(0, 0, 0, 0);  new Date(y, m, 1)
来源：http://dali.meibo888.top/Article/details/gt2hlavnlhv.html

TS:   new Date().setHours(0, 0, 0, 0)
来源：http://dali.vqdsnc.cn/Article/details/gt2zancxwkh.html

Java: LocalDate.now();  LocalDate.now().withDayOfMonth(1)
来源：http://dali.gogol.net.cn/Article/details/gt2idalsyqx.html

Go:   now := time.Now();  time.Date(now.Year(), now.Month(), 1, 0, 0, 0, 0, now.Location())
来源：http://dali.birdmap.top/Article/details/gt2pjjfhdcf.html

Ruby: Date.today;  Date.today.next_month - Date.today.day   # 本月最后一天思路
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjrcllwa.html

C#:   DateTime.Today;  new DateTime(now.Year, now.Month, 1)
来源：http://dali.nwbrower.top/Article/details/gt2esynnsxh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2mceudbrd.html

K. JSON 与序列化
来源：http://dali.svipenyu.cn/Article/details/gt2katoygpc.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2lnqmjfeb.html

[K01] 对象转 JSON 字符串
来源：http://dali.shzxlz.cn/Article/details/gt2lnfswerm.html

Py:   json.dumps(obj, ensure_ascii=False)
来源：http://dali.yueranfly.top/Article/details/gt2zqqdyqcp.html

PHP:  json_encode($obj, JSON_UNESCAPED_UNICODE);
来源：http://dali.vqdsnc.cn/Article/details/gt2evseilya.html

JS:   JSON.stringify(obj)
来源：http://dali.bjfxy.top/Article/details/gt2guodcsuy.html

TS:   JSON.stringify(obj)
来源：http://dali.yongpay.top/Article/details/gt2rscxafxh.html

Java: new ObjectMapper().writeValueAsString(obj)      // Jackson
来源：http://dali.gogol.net.cn/Article/details/gt2kpctjrva.html

Go:   json.Marshal(obj)
来源：http://dali.yonumen.top/Article/details/gt2vksdjlbl.html

Ruby: obj.to_json                                     // require "json"
来源：http://dali.tian-w.cn/Article/details/gt2iuqjtktw.html

C#:   JsonSerializer.Serialize(obj)
来源：http://dali.tanke756.top/Article/details/gt2ujigycxu.html

[K02] JSON 字符串转对象
来源：http://dali.yj20258888.top/Article/details/gt2jibxfgil.html

Py:   json.loads(s)
来源：http://dali.yueranfly.top/Article/details/gt2zvurukkc.html

PHP:  json_decode($s, true);                          // true 得关联数组
来源：http://dali.dashuyun.cn/Article/details/gt2vudroofb.html

JS:   JSON.parse(s)
来源：http://dali.xinyue.icu/Article/details/gt2itkcuvlu.html

TS:   JSON.parse(s)
来源：http://dali.smart0.xyz/Article/details/gt2itebodwu.html

Java: new ObjectMapper().readValue(s, Map.class)
来源：http://dali.sysykeji.top/Article/details/gt2xdddfttd.html

Go:   json.Unmarshal(data, &v)
来源：http://dali.hnqzz.top/Article/details/gt2nhqvkvri.html

Ruby: JSON.parse(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2lbxuietn.html

C#:   JsonSerializer.Deserialize<T>(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2lhbnkvrr.html

[K03] JSON 美化输出（带缩进）
来源：http://dali.yuxming.cn/Article/details/gt2ktdnbbxr.html

Py:   json.dumps(obj, indent=2, ensure_ascii=False)
来源：http://dali.yvedp.cn/Article/details/gt2tpozoqsy.html

PHP:  json_encode($obj, JSON_PRETTY_PRINT | JSON_UNESCAPED_UNICODE);
来源：http://dali.jinqigufen.top/Article/details/gt2upiqlxvp.html

JS:   JSON.stringify(obj, null, 2)
来源：http://dali.cqqwz.cn/Article/details/gt2aptehepp.html

TS:   JSON.stringify(obj, null, 2)
来源：http://dali.haohaochexian.top/Article/details/gt2xgcilgkk.html

Java: mapper.writerWithDefaultPrettyPrinter().writeValueAsString(obj)
来源：http://dali.gotoacloud.top/Article/details/gt2pavnfvlq.html

Go:   json.MarshalIndent(obj, "", "  ")
来源：http://dali.hnqzz.top/Article/details/gt2jsnqqmzt.html

Ruby: JSON.pretty_generate(obj)
来源：http://dali.redwolf501.top/Article/details/gt2plbuivjl.html

C#:   JsonSerializer.Serialize(obj, new JsonSerializerOptions { WriteIndented = true })
来源：http://dali.shuidangran.top/Article/details/gt2ysrzldje.html

[K04] 读取 JSON 文件
来源：http://dali.jqgufenzy.top/Article/details/gt2jtbjjrlg.html

Py:   json.load(open("a.json", encoding="utf-8"))
来源：http://dali.daria6918.cn/Article/details/gt2qxongkes.html

PHP:  json_decode(file_get_contents("a.json"), true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gzlmrgjg.html

JS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.aibaodan.cn/Article/details/gt2vdgqlgsr.html

TS:   JSON.parse(fs.readFileSync("a.json", "utf8"))
来源：http://dali.bjfxy.top/Article/details/gt2pmnekmjd.html

Java: mapper.readValue(new File("a.json"), Map.class)
来源：http://dali.xylfe.cn/Article/details/gt2bfdxsiao.html

Go:   data, _ := os.ReadFile("a.json");  json.Unmarshal(data, &v)
来源：http://dali.nwbrower.top/Article/details/gt2ygwfktfj.html

Ruby: JSON.parse(File.read("a.json"))
来源：http://dali.zdqjudy.top/Article/details/gt2fvkilzeq.html

C#:   JsonSerializer.Deserialize<T>(File.ReadAllText("a.json"))
来源：http://dali.cheryme.top/Article/details/gt2iwncmkso.html

[K05] 深拷贝对象
来源：http://dali.zhengqikj.top/Article/details/gt2wkrzesuw.html

Py:   copy.deepcopy(obj)
来源：http://dali.jlsjyb.cn/Article/details/gt2iiqungml.html

PHP:  unserialize(serialize($obj));
来源：http://dali.kuanghao11.cn/Article/details/gt2myuejtre.html

JS:   structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gt2uivndvgn.html

TS:   structuredClone(obj)
来源：http://dali.meibo888.top/Article/details/gt2brdvayhc.html

Java: // 手写拷贝构造，或序列化往返
来源：http://dali.smart0.xyz/Article/details/gt2hwypzeab.html

Go:   // 结构体值赋值即复制（注意指针/切片字段）
来源：http://dali.wangdashe.top/Article/details/gt2gugmzojx.html

Ruby: Marshal.load(Marshal.dump(obj))
来源：http://dali.redwolf501.top/Article/details/gt2dekprshy.html

C#:   // 序列化往返，或自定义 Clone
来源：http://dali.guannengcc.top/Article/details/gt2adzhjuko.html

[K06] 解析 URL 查询串
来源：http://dali.nanxinkj.top/Article/details/gt2xahsbkhk.html

Py:   parse_qs("a=1&b=2");  urlencode({"a": 1})
来源：http://dali.yj202588.top/Article/details/gt2uobewjca.html

PHP:  parse_str("a=1&b=2", $out);  http_build_query(["a" => 1]);
来源：http://dali.yvedp.cn/Article/details/gt2xggvqbwv.html

JS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.gogol.net.cn/Article/details/gt2idgatuqj.html

TS:   new URLSearchParams("a=1&b=2").get("a")
来源：http://dali.wangdashe.top/Article/details/gt2lifhoyom.html

Java: // 手动 split & 与 =，或 UriComponentsBuilder
来源：http://dali.nanxinkj.top/Article/details/gt2qkhobbcl.html

Go:   url.ParseQuery("a=1&b=2")
来源：http://dali.andypj.xyz/Article/details/gt2gcrfpldd.html

Ruby: URI.decode_www_form("a=1&b=2")
来源：http://dali.bjfxy.top/Article/details/gt2selhlpwb.html

C#:   HttpUtility.ParseQueryString("a=1&b=2")
来源：http://dali.cqqwz.cn/Article/details/gt2jjahzbvn.html

[K07] 进制转换
来源：http://dali.aibaodan.cn/Article/details/gt2cfeqzxht.html

Py:   bin(10);  hex(255);  int("ff", 16)
来源：http://dali.yonumen.top/Article/details/gt2zjndomlt.html

PHP:  decbin(10);  dechex(255);  hexdec("ff");
来源：http://dali.yongpay.top/Article/details/gt2ewfahzzu.html

JS:   (10).toString(2);  (255).toString(16);  parseInt("ff", 16)
来源：http://dali.xinyue.icu/Article/details/gt2hfyxgvoy.html

TS:   (10).toString(2);  parseInt("ff", 16)
来源：http://dali.tian-w.cn/Article/details/gt2acfqzinx.html

Java: Integer.toBinaryString(10);  Integer.toHexString(255);  Integer.parseInt("ff", 16)
来源：http://dali.kuanghao11.cn/Article/details/gt2gvudvqea.html

Go:   strconv.FormatInt(10, 2);  strconv.ParseInt("ff", 16, 64)
来源：http://dali.guannengcc.top/Article/details/gt2wshomwfa.html

Ruby: 10.to_s(2);  255.to_s(16);  "ff".to_i(16)
来源：http://dali.nwbrower.top/Article/details/gt2hnmsmajr.html

C#:   Convert.ToString(10, 2);  Convert.ToString(255, 16);  Convert.ToInt32("ff", 16)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fzsznnbt.html

[K08] 二进制序列化（非 JSON）
来源：http://dali.c1oappe.top/Article/details/gt2consbppl.html

Py:   pickle.dumps(obj)
来源：http://dali.xinyue.icu/Article/details/gt2nojaspzk.html


<!-- 参考信息 -->