代发 wailian999

[Q76] 按天统计
来源：http://dali.zhongyouzk.top/Article/details/gt2knhmfinb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pengpengdd.cyou/Article/details/gt2vzokpuwp.html

[Q77] 时间加减
来源：http://dali.shzxlz.cn/Article/details/gt2yinyczfr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jianghu66.top/Article/details/gt2wpgghaox.html

[Q78] 当前时间
来源：http://dali.yvedp.cn/Article/details/gt2vfzdjcnu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gotoacloud.top/Article/details/gt2qkpjbtyr.html

[Q79] 字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gt2verlzyle.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gt2xcaytzch.html

[Q80] 字符串截取
来源：http://dali.jinqigufen.top/Article/details/gt2xxbpnikh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.iojbl.cn/Article/details/gt2chbhqyrt.html

[Q81] 字符串替换
来源：http://dali.yongpay.top/Article/details/gt2pcfkzvvr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2ecjcctyl.html

[Q82] 字符长度与字节长度
来源：http://dali.0kj1m.cn/Article/details/gt2wylpfksc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gt2vxjrhwmy.html

[Q83] 大小写转换
来源：http://dali.havefunace.top/Article/details/gt2dvwgbege.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2hnmzdfid.html

[Q84] 去除首尾空格
来源：http://dali.yonumen.top/Article/details/gt2qqfvlcot.html

SELECT TRIM(name) FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2hitigdtn.html

[Q85] 数值取整
来源：http://dali.svipenyu.cn/Article/details/gt2nsbvvabm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sweek.top/Article/details/gt2vizrunei.html

[Q86] 读取 JSON 字段
来源：http://dali.iojbl.cn/Article/details/gt2nyekvaxe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aibaodan.cn/Article/details/gt2fxmtpcuv.html

[Q87] JSON 字段做条件
来源：http://dali.xinyue.icu/Article/details/gt2nujmmokj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbddqtvj.html

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gt2xzduujhv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gzhubu.top/Article/details/gt2ybukxglv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.tianlin.xyz/Article/details/gt2zuifmlme.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gt2erafeiep.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hammf.cn/Article/details/gt2uikarwod.html

[Q90] 生成序号列
来源：http://dali.yvedp.cn/Article/details/gt2fynjwvvp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jahokmxt.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2loexsess.html

R. Bash 专题
来源：http://dali.daxiang520.top/Article/details/gt2grrbkavu.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2lcxvfebo.html

[R01] shebang 与严格模式
来源：http://dali.kuanghao11.cn/Article/details/gt2yjiuutnm.html

#!/usr/bin/env bash
来源：http://dali.fzhhl.top/Article/details/gt2cmkeimxv.html

set -euo pipefail
来源：http://dali.pycfn.com/Article/details/gt2fabwvpoi.html

[R02] 变量赋值与使用
来源：http://dali.smart0.xyz/Article/details/gt2mwjeeqjd.html

name="Tom"; echo "$name"
来源：http://dali.zycfv.cn/Article/details/gt2yaqoetma.html

[R03] 只读变量
来源：http://dali.pycfn.com/Article/details/gt2cycqempk.html

readonly PI=3.14
来源：http://dali.yvedp.cn/Article/details/gt2xpxrkwmx.html

[R04] 位置参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2rdzstmvy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yongpay.top/Article/details/gt2zrepgaxb.html

[R05] 参数默认值
来源：http://dali.jlsjyb.cn/Article/details/gt2jkqqvwrr.html

name="${1:-default}"
来源：http://dali.sufxvd.cn/Article/details/gt2iwfjkxin.html

[R06] 判断命令是否存在
来源：http://dali.dianchejie.cn/Article/details/gt2xsiqtmfa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gt2vubxswvw.html

[R07] if 判断文件
来源：http://dali.daria6918.cn/Article/details/gt2clbvbfnw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hfpthk.cn/Article/details/gt2nrevihen.html

[R08] 数值比较
来源：http://dali.meibo888.top/Article/details/gt2mbvoqzds.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gt2cexnnoxy.html

[R09] 字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gt2adaskhmi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xylfe.cn/Article/details/gt2mxzkmpwu.html

[R10] 正则匹配
来源：http://dali.aizwys.cn/Article/details/gt2mvnrxpgl.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gt2gxinnpyv.html

[R11] case 多分支
来源：http://dali.nanxuanxn.top/Article/details/gt2ttvnpfvc.html

case "$1" in
来源：http://dali.chenzaomai.com/Article/details/gt2owxzmnpx.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gt2pituasqo.html

stop)  echo "停止" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gbprbeur.html

*)     echo "未知命令" ;;
来源：http://dali.yj202588.top/Article/details/gt2doruklcm.html

esac
来源：http://dali.fzhhl.top/Article/details/gt2xexxcaeq.html

[R12] for 遍历文件
来源：http://dali.zdqjudy.top/Article/details/gt2pcxadzvf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gt2xqhggacx.html

[R13] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gt2hbfespxb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gt2mmilveps.html

[R14] C 风格 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wsmmxztx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gt2rcvchopx.html

[R15] while 逐行读文件
来源：http://dali.havefunace.top/Article/details/gt2jbkeodna.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2agsjzilv.html

[R16] until 等待条件
来源：http://dali.hfpthk.cn/Article/details/gt2vvesoech.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2drhxgdba.html

[R17] 数组定义与取值
来源：http://dali.fzhhl.top/Article/details/gt2aaledars.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xinyue.icu/Article/details/gt2xeoueknn.html

[R18] 遍历数组
来源：http://dali.cucudq.cn/Article/details/gt2gogixdly.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shzxlz.cn/Article/details/gt2ixfpvelp.html

[R19] 数组长度
来源：http://dali.yvedp.cn/Article/details/gt2bdwzzcuo.html

echo "${#arr[@]}"
来源：http://dali.redwolf501.top/Article/details/gt2vksevoaz.html

[R20] 关联数组（字典）
来源：http://dali.yonumen.top/Article/details/gt2fjxggkul.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gt2flatxrue.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dvliooln.html

echo "${#s}"
来源：http://dali.guannengcc.top/Article/details/gt2fmoyophd.html

[R22] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gt2fcnpgbeq.html

echo "${s:0:5}"
来源：http://dali.jqgufenzy.top/Article/details/gt2uvbuqnor.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gt2kzyliyxl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sysykeji.top/Article/details/gt2zcrniklk.html

[R24] 大小写转换
来源：http://dali.meibo888.top/Article/details/gt2sshwfljo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.andypj.xyz/Article/details/gt2rpkcusxb.html

[R25] 去后缀 / 去前缀
来源：http://dali.cdnleiting.top/Article/details/gt2amnqmbzb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cqqwz.cn/Article/details/gt2teqwkmtn.html

[R26] 命令替换
来源：http://dali.yj20258.top/Article/details/gt2iinwqcio.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gt2kowiwjxz.html

[R27] 算术展开
来源：http://dali.jqgufenzy.top/Article/details/gt2qbzchubd.html

echo $((1 + 2 * 3))
来源：http://dali.zhoulong.xyz/Article/details/gt2wtutnkfn.html

[R28] 浮点运算
来源：http://dali.guannengcc.top/Article/details/gt2kgsdttbj.html

echo "scale=2; 10/3" | bc
来源：http://dali.pycfn.com/Article/details/gt2axlhfubd.html

[R29] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gt2cpjueade.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kqqhheji.html

[R30] 函数返回状态码
来源：http://dali.dianchejie.cn/Article/details/gt2ejupewff.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gt2kxqumwtv.html

[R31] 局部变量
来源：http://dali.ehwqpu.com/Article/details/gt2nzlfirdx.html

f() { local x=1; echo "$x"; }
来源：http://dali.316326.xyz/Article/details/gt2ylwjdhat.html

[R32] 参数个数校验
来源：http://dali.havefunace.top/Article/details/gt2ajghfwqx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gt2tfcvahzk.html

[R33] 捕获错误并提示行号
来源：http://dali.dianchejie.cn/Article/details/gt2spcsuyep.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.andypj.xyz/Article/details/gt2zrbojloi.html

[R34] 退出时清理
来源：http://dali.xinyue.icu/Article/details/gt2gwzbaycv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gt2kawshxbg.html

[R35] 后台执行并等待
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzxrpzit.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gt2grurbmuj.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gt2unhxougg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guannengcc.top/Article/details/gt2dtvzhvlz.html

[R37] 把输出赋给变量
来源：http://dali.zhixingplan.top/Article/details/gt2neygggcf.html

files=$(ls -1)
来源：http://dali.sweek.top/Article/details/gt2gzjxqzvl.html

[R38] 管道串联
来源：http://dali.zhongyouzk.top/Article/details/gt2mmzpictb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gt2smtmxbnt.html

[R39] 重定向标准输出与错误
来源：http://dali.zhongyouzk.top/Article/details/gt2qwatwioe.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gt2crhckdvd.html

[R40] 追加写日志
来源：http://dali.xuetiantiany.cn/Article/details/gt2fywyknxi.html

echo "log" >> out.log
来源：http://dali.wangshuangyany.cn/Article/details/gt2vcgwttse.html

[R41] 丢弃输出
来源：http://dali.cashguo.top/Article/details/gt2eevwzmwj.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gt2avvcmzdw.html

[R42] 输入重定向
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mkgufpoj.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2sibxggkc.html

[R43] 按名字查找文件
来源：http://dali.gzhubu.top/Article/details/gt2rnfchpvt.html

find . -name "*.log" -type f
来源：http://dali.yongpay.top/Article/details/gt2fexdioxy.html

[R44] 按修改时间查找
来源：http://dali.xuanzx.com/Article/details/gt2ipimegea.html

find . -mtime -7 -type f
来源：http://dali.sysykeji.top/Article/details/gt2rqdpzlpt.html

[R45] 批量删除
来源：http://dali.jinqigfzy.top/Article/details/gt2hwqyppsp.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gt2jvqhbuqw.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gt2kmcyqmcy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.kuanghao11.cn/Article/details/gt2xkzbuver.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gt2udletibk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2wnlnqfwn.html

[R48] awk 取指定列
来源：http://dali.redwolf501.top/Article/details/gt2idcxjimv.html

awk '{print $1, $3}' a.txt
来源：http://dali.yueranfly.top/Article/details/gt2iuuukfra.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kryrpnmq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yvedp.cn/Article/details/gt2nydafxjd.html

[R50] awk 求和
来源：http://dali.andypj.xyz/Article/details/gt2epcykdsk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fengsongda.top/Article/details/gt2ryqlljxh.html

[R51] 排序去重取前几
来源：http://dali.zhengqikj.top/Article/details/gt2cqlfcfgz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.guannengcc.top/Article/details/gt2msgtkyxu.html

[R52] 统计行数
来源：http://dali.zhengqikj.top/Article/details/gt2sxbpmmsh.html

wc -l a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2onimwpab.html

[R53] 查看文件头与实时尾
来源：http://dali.daria6918.cn/Article/details/gt2oxyrtdqk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hnqzz.top/Article/details/gt2tykbklit.html

[R54] 比较两个文件
来源：http://dali.yj20258.top/Article/details/gt2rwuiyabn.html

diff a.txt b.txt
来源：http://dali.jyoumei.cn/Article/details/gt2kgtpjips.html

[R55] 压缩与解压
来源：http://dali.9152youxi.cn/Article/details/gt2oygrvixc.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ivvv.top/Article/details/gt2wxmcecok.html

[R56] 远程拷贝
来源：http://dali.fengsongda.top/Article/details/gt2giszennl.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gt2ziwevgrp.html

[R57] 远程执行命令
来源：http://dali.sufxvd.cn/Article/details/gt2plcgimdr.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ofvrkatt.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2kasfmlpt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sxryk.cn/Article/details/gt2fgfyaigs.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gt2hqdcrkuj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pengpengdd.cyou/Article/details/gt2eqsdoxhs.html

[R60] 只看 HTTP 状态码
来源：http://dali.bjfxy.top/Article/details/gt2ruesthta.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gt2jkkznbbf.html

[R61] 磁盘占用
来源：http://dali.redwolf501.top/Article/details/gt2nleolgfp.html

df -h;  du -sh *
来源：http://dali.tianlin.xyz/Article/details/gt2etuuuyoj.html

[R62] 找最占空间的文件
来源：http://dali.yonumen.top/Article/details/gt2lbprmwyw.html

du -ah . | sort -rh | head -10
来源：http://dali.andypj.xyz/Article/details/gt2iplqdtxe.html

[R63] 内存与进程
来源：http://dali.gaohongyu789.top/Article/details/gt2mbdfcxli.html

free -h;  ps aux | grep nginx
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lefpfwzz.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gt2ofndwhfo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gt2negoxudy.html

[R65] 查看端口占用
来源：http://dali.jlsjyb.cn/Article/details/gt2mnudjzey.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yonumen.top/Article/details/gt2ioybhexq.html

[R66] 定时任务
来源：http://dali.0kj1m.cn/Article/details/gt2bldbzvwd.html

crontab -e;  crontab -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ttanfhzw.html

[R67] 生成随机十六进制串
来源：http://dali.sysykeji.top/Article/details/gt2xybxssah.html

openssl rand -hex 16
来源：http://dali.xuanzx.com/Article/details/gt2krplvhxy.html

[R68] 计算文件校验值
来源：http://dali.chenlongwang.top/Article/details/gt2szaovcqc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2oztxmewi.html

[R69] 生成随机密码
来源：http://dali.aizwys.cn/Article/details/gt2ojzrzyzt.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iznnjpyp.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gt2yyihjtef.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gt2npgqbahh.html

[R71] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gt2tjwastge.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daria6918.cn/Article/details/gt2ugdnttzx.html

[R72] 等待端口就绪
来源：http://dali.guannengcc.top/Article/details/gt2qswyylun.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gt2dnyxfpvt.html

[R73] 分割大日志
来源：http://dali.ivvv.top/Article/details/gt2fuejtpdg.html

split -l 1000 big.log part_
来源：http://dali.yj20258.top/Article/details/gt2qeuulnwr.html

[R74] 批量重命名
来源：http://dali.xinyue.icu/Article/details/gt2odbvdsil.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2nckzqfie.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gt2egwbdkhp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuanzhike.top/Article/details/gt2uoydzfyy.html

[R76] 使用临时文件
来源：http://dali.daxiang520.top/Article/details/gt2sctppmtd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ehwqpu.com/Article/details/gt2rdkiniqm.html

[R77] 读取用户输入
来源：http://dali.xinyue.icu/Article/details/gt2jbqjpwoa.html

read -rp "请输入: " ans
来源：http://dali.birdmap.top/Article/details/gt2lwtorlie.html

[R78] 交互式菜单
来源：http://dali.jiagoushi.top/Article/details/gt2wililszg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dashuyun.cn/Article/details/gt2deyadszx.html

[R79] 解析命令行选项
来源：http://dali.zhiwuduotai.top/Article/details/gt2kdzrvmry.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gt2rvriwpks.html

[R80] 查看脚本执行耗时
来源：http://dali.wangshuangyany.cn/Article/details/gt2ogkvolag.html

time ./run.sh
来源：http://dali.cqqwz.cn/Article/details/gt2jloxuedp.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2qpdbrwjp.html

S. C / C++ 专题
来源：http://dali.cdnleiting.top/Article/details/gt2xtkpzlev.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2bddpuxlu.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2mddbvevw.html

#include <stdio.h>
来源：http://dali.shzxlz.cn/Article/details/gt2icrhfovg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2latxpilm.html

[S02] C：变量与格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gt2nvupjjod.html

int a = 10; printf("%d\n", a);
来源：http://dali.ydzc1.top/Article/details/gt2aocttbdk.html

[S03] C：读入整数
来源：http://dali.hywenlv.cn/Article/details/gt2xvahboch.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gt2oowjppll.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gt2swpnrymh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2mrznqznw.html

[S05] C：字符串长度
来源：http://dali.jiagoushi.top/Article/details/gt2jgfmytgb.html

strlen(s)
来源：http://dali.shzxlz.cn/Article/details/gt2pzqxdyzh.html

[S06] C：字符串比较
来源：http://dali.guannengcc.top/Article/details/gt2xjcotrtt.html

strcmp(a, b) == 0
来源：http://dali.hnqzz.top/Article/details/gt2tqmjahhy.html

[S07] C：数组遍历求和
来源：http://dali.yj20258888.top/Article/details/gt2enxkntjj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gotoacloud.top/Article/details/gt2snejtkbt.html

[S08] C：动态内存分配与释放
来源：http://dali.yonumen.top/Article/details/gt2mythieef.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bnotnmvc.html

[S09] C：结构体定义与初始化
来源：http://dali.aibaodan.cn/Article/details/gt2farqivpc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj202588.top/Article/details/gt2zcofciuy.html

[S10] C：指针与解引用
来源：http://dali.shangyingyoupin.top/Article/details/gt2dyqlsskw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2efxzqtlt.html

[S11] C：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2rrqoqwph.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gt2fdoebvqg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daria6918.cn/Article/details/gt2rwzxronx.html

fclose(f);
来源：http://dali.cheryme.top/Article/details/gt2txcnqsel.html

[S12] C：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2uqudquzy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gt2amcksqun.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2znietyac.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ragdcdiq.html

[S14] C：枚举
来源：http://dali.snrcjt.cn/Article/details/gt2yovikvlg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hfpthk.cn/Article/details/gt2fcaoistd.html

[S15] C：类型转换
来源：http://dali.guannengcc.top/Article/details/gt2klwqnujn.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gt2wxmtfmex.html

[S16] C：位操作置位
来源：http://dali.jlsjyb.cn/Article/details/gt2nnuelvxg.html

x |= (1 << 3);
来源：http://dali.jiagoushi.top/Article/details/gt2ydhmblze.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gt2nlprfgjx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jzuireis.html

[S18] C：命令行参数
来源：http://dali.snrcjt.cn/Article/details/gt2uijbnkrz.html

int main(int argc, char **argv)
来源：http://dali.sweek.top/Article/details/gt2wpwtfrkx.html

[S19] C：快速排序
来源：http://dali.yangfankeji.com/Article/details/gt2anxwjhjz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gt2kotrzhae.html

[S20] C：二分查找
来源：http://dali.hysaishi.cn/Article/details/gt2tfchrwgi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gt2cywyfgxx.html

[S21] C：字符类别判断
来源：http://dali.snrcjt.cn/Article/details/gt2dkgsmnmu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yanxiufei.cn/Article/details/gt2fzzkunlw.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gt2scteaioq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xziqi.cn/Article/details/gt2ekpyqzcx.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gibgcrro.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jyoumei.cn/Article/details/gt2pkqsikpc.html

[S24] C：获取本地时间
来源：http://dali.zycfv.cn/Article/details/gt2suprwtyg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgfzy.top/Article/details/gt2ebppocqi.html

[S25] C：内存拷贝
来源：http://dali.wangdashe.top/Article/details/gt2qaksdohh.html

memcpy(dst, src, n);
来源：http://dali.yj20258.top/Article/details/gt2bezbkogw.html

[S26] C：内存清零
来源：http://dali.hfpthk.cn/Article/details/gt2ybqfnwqx.html

memset(a, 0, sizeof a);
来源：http://dali.cucudq.cn/Article/details/gt2qffdyfdx.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gt2eypghlfv.html

const double PI = 3.14159;
来源：http://dali.shuidangran.top/Article/details/gt2iydfgmxu.html

[S28] C：静态变量
来源：http://dali.xziqi.cn/Article/details/gt2tngkdkwj.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gt2bltpaags.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gt2doccixbx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yueranfly.top/Article/details/gt2bwauioek.html

[S30] C：头文件保护
来源：http://dali.yuanzhike.top/Article/details/gt2omoyprjm.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gt2xjiixuod.html

#define X_H
来源：http://dali.bjfxy.top/Article/details/gt2dextxfyx.html

#endif
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2peagchev.html

[S31] C++：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2arklundo.html

#include <iostream>
来源：http://dali.svipenyu.cn/Article/details/gt2vsdjcuut.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cashguo.top/Article/details/gt2tqwlptcj.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvorncdo.html

std::string s = "hi";  s += "!";
来源：http://dali.c1oappe.top/Article/details/gt2rhmgvjbj.html

[S33] C++：vector 增删
来源：http://dali.smart0.xyz/Article/details/gt2dyoofsgn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.c1oappe.top/Article/details/gt2tridwymj.html

[S34] C++：遍历 vector
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2twmadbpc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jlsjyb.cn/Article/details/gt2eaknifaj.html

[S35] C++：map
来源：http://dali.yonumen.top/Article/details/gt2bkhnaewy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vwdvnecf.html

[S36] C++：unordered_map
来源：http://dali.hammf.cn/Article/details/gt2nrybcpcc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2eygczuwn.html

[S37] C++：set
来源：http://dali.yuanzhike.top/Article/details/gt2pfabkfwf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gt2cqcgrtrm.html

[S38] C++：排序
来源：http://dali.zdqjudy.top/Article/details/gt2hetdpdey.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gt2ptzhscej.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxinkj.top/Article/details/gt2gevxplez.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gt2anxjfczl.html

[S40] C++：查找元素
来源：http://dali.yvedp.cn/Article/details/gt2rforuaem.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cucudq.cn/Article/details/gt2drrqdjwa.html

[S41] C++：类与构造函数
来源：http://dali.ivvv.top/Article/details/gt2hfqlqktp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kypmcsvn.html

[S42] C++：继承与虚函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2huclhaxl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gt2shbhahea.html

[S43] C++：智能指针
来源：http://dali.cheryme.top/Article/details/gt2ahdgczdf.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gt2ytjnacwx.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gt2zrzmszep.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gt2npdmpzxe.html

[S45] C++：lambda
来源：http://dali.hnqzz.top/Article/details/gt2shtchkpc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.snrcjt.cn/Article/details/gt2jbqoqszq.html

[S46] C++：函数模板
来源：http://dali.shuidangran.top/Article/details/gt2bkrbwiam.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gt2ywqnoick.html


<!-- 参考信息 -->