代发 wailian999

ROLLBACK TO sp1;
来源：http://dali.sxryk.cn/Article/details/gt2llmbzagf.html

[Q69] 查看执行计划
来源：http://dali.yj202588.top/Article/details/gt2xldsozip.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.wangdashe.top/Article/details/gt2hxqkeyyi.html

[Q70] 更新统计信息
来源：http://dali.316326.xyz/Article/details/gt2upzksvlf.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gt2lbqbryeo.html

[Q71] 查看建表语句
来源：http://dali.xuanzx.com/Article/details/gt2lrawuyuz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hongshengwenyu.top/Article/details/gt2utxplszs.html

[Q72] 查看索引
来源：http://dali.ybcxt.top/Article/details/gt2kwokttip.html

SHOW INDEX FROM users;
来源：http://dali.yonumen.top/Article/details/gt2ttwziyoz.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gt2yzyzgaqx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.redwolf501.top/Article/details/gt2pmywurqg.html

[Q74] 强制使用索引
来源：http://dali.wangshuangyany.cn/Article/details/gt2whxfsgoa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.feifeiyinyue.top/Article/details/gt2qzpzgqru.html

[Q75] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gt2ccjaajbk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj20258.top/Article/details/gt2ozvddcso.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rqskqndw.html

[Q76] 按天统计
来源：http://dali.xuetiantiany.cn/Article/details/gt2giouixlr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gt2kjsjfgel.html

[Q77] 时间加减
来源：http://dali.zhiwuduotai.top/Article/details/gt2dpquugnp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sufxvd.cn/Article/details/gt2czerbobp.html

[Q78] 当前时间
来源：http://dali.jianghu66.top/Article/details/gt2yqaqedrh.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yuanzhike.top/Article/details/gt2pylxzxcp.html

[Q79] 字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gt2nvrrbxkl.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.nanxuanxn.top/Article/details/gt2loagmixj.html

[Q80] 字符串截取
来源：http://dali.cqqwz.cn/Article/details/gt2vxcdirfq.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2vmuctznf.html

[Q81] 字符串替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2brhzktcu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cashguo.top/Article/details/gt2vtvwqnbj.html

[Q82] 字符长度与字节长度
来源：http://dali.gzhubu.top/Article/details/gt2ewqaqael.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2agksvnhb.html

[Q83] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gt2ftmqgprd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2vhfpfkdi.html

[Q84] 去除首尾空格
来源：http://dali.sufxvd.cn/Article/details/gt2xadfloxj.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gt2onrgkonp.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gt2pjyslyqq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhoulong.xyz/Article/details/gt2hshsqcex.html

[Q86] 读取 JSON 字段
来源：http://dali.c1oappe.top/Article/details/gt2aeqdriqf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jlsjyb.cn/Article/details/gt2ulecuevt.html

[Q87] JSON 字段做条件
来源：http://dali.yongpay.top/Article/details/gt2kjbygolg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dianchejie.cn/Article/details/gt2aabdsxtx.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gt2lteoiqfw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ehwqpu.com/Article/details/gt2wzkmkbat.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2ozyxlxsi.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gt2ajihsfcb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.316326.xyz/Article/details/gt2zgiptvqi.html

[Q90] 生成序号列
来源：http://dali.yongpay.top/Article/details/gt2gajzxxye.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ydzc1.top/Article/details/gt2oeyqkxvy.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2dpfpltga.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gt2kwnjyipl.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2ldeiicpt.html

[R01] shebang 与严格模式
来源：http://dali.yj20258888.top/Article/details/gt2ybqypqjp.html

#!/usr/bin/env bash
来源：http://dali.yanxiufei.cn/Article/details/gt2rupukusw.html

set -euo pipefail
来源：http://dali.xuanzx.com/Article/details/gt2eftkynwi.html

[R02] 变量赋值与使用
来源：http://dali.c1oappe.top/Article/details/gt2npxfmuds.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gt2jutwocrl.html

[R03] 只读变量
来源：http://dali.iojbl.cn/Article/details/gt2jezhmrgo.html

readonly PI=3.14
来源：http://dali.meibo888.top/Article/details/gt2cfaecdnu.html

[R04] 位置参数
来源：http://dali.316326.xyz/Article/details/gt2phxixtuo.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuxming.cn/Article/details/gt2ivhvommy.html

[R05] 参数默认值
来源：http://dali.pycfn.com/Article/details/gt2uhayponp.html

name="${1:-default}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2swftweph.html

[R06] 判断命令是否存在
来源：http://dali.xuanzx.com/Article/details/gt2cmugfdbp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.cheryme.top/Article/details/gt2adaaeyeh.html

[R07] if 判断文件
来源：http://dali.xinyue.icu/Article/details/gt2pemiwqax.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tianlin.xyz/Article/details/gt2fnsehycu.html

[R08] 数值比较
来源：http://dali.pycfn.com/Article/details/gt2ewmyecnm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnxiangtu.top/Article/details/gt2lhdnnksz.html

[R09] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gt2ccjibihz.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.pycfn.com/Article/details/gt2dbwjsigb.html

[R10] 正则匹配
来源：http://dali.daria6918.cn/Article/details/gt2dtsujgde.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ydzc1.top/Article/details/gt2yymklzyf.html

[R11] case 多分支
来源：http://dali.dianchejie.cn/Article/details/gt2xlyvvypr.html

case "$1" in
来源：http://dali.haohaochexian.top/Article/details/gt2wcxaxnij.html

start) echo "启动" ;;
来源：http://dali.tianlin.xyz/Article/details/gt2qylptkti.html

stop)  echo "停止" ;;
来源：http://dali.9152youxi.cn/Article/details/gt2ykrnjmmm.html

*)     echo "未知命令" ;;
来源：http://dali.nanxuanxn.top/Article/details/gt2kqjukxmq.html

esac
来源：http://dali.meibo888.top/Article/details/gt2oxfmupra.html

[R12] for 遍历文件
来源：http://dali.bjfxy.top/Article/details/gt2xeazjtmq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ybcxt.top/Article/details/gt2wxhkyzbl.html

[R13] for 计数循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2teqykyri.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.dashuyun.cn/Article/details/gt2nuimqyjt.html

[R14] C 风格 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uniephki.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.snrcjt.cn/Article/details/gt2qkleabio.html

[R15] while 逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gt2qsfdsdwr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj202588.top/Article/details/gt2mvkqlktc.html

[R16] until 等待条件
来源：http://dali.zycfv.cn/Article/details/gt2rqdeuxbo.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ysewoxyn.html

[R17] 数组定义与取值
来源：http://dali.redwolf501.top/Article/details/gt2cydeihbu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2jhxdyknp.html

[R18] 遍历数组
来源：http://dali.zdqjudy.top/Article/details/gt2znuwowmc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xinyue.icu/Article/details/gt2yygheial.html

[R19] 数组长度
来源：http://dali.ivvv.top/Article/details/gt2expxdgnj.html

echo "${#arr[@]}"
来源：http://dali.hywenlv.cn/Article/details/gt2jjovepjt.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gt2axokykaf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sweek.top/Article/details/gt2uacjifit.html

[R21] 字符串长度
来源：http://dali.zdqjudy.top/Article/details/gt2pltjloir.html

echo "${#s}"
来源：http://dali.zycfv.cn/Article/details/gt2jxftkwdl.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gt2zmcovzhr.html

echo "${s:0:5}"
来源：http://dali.fengsongda.top/Article/details/gt2wyhkocov.html

[R23] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gt2suvayiyh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yj20258888.top/Article/details/gt2xenrpqqc.html

[R24] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gt2itqfwpad.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.smart0.xyz/Article/details/gt2qcpdxzes.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gt2wrqhowbj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gt2ggcctsru.html

[R26] 命令替换
来源：http://dali.zhiwuduotai.top/Article/details/gt2uilxcgox.html

now=$(date +%F); echo "$now"
来源：http://dali.daxiang520.top/Article/details/gt2wxotjhvu.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gt2buitoktl.html

echo $((1 + 2 * 3))
来源：http://dali.gaohongyu789.top/Article/details/gt2cehiyoov.html

[R28] 浮点运算
来源：http://dali.yonumen.top/Article/details/gt2xsiazwwf.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhiwuduotai.top/Article/details/gt2drfdtcpn.html

[R29] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ceeenazn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hywenlv.cn/Article/details/gt2xapwxnix.html

[R30] 函数返回状态码
来源：http://dali.shangyingyoupin.top/Article/details/gt2edxzlruy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sysykeji.top/Article/details/gt2ecdyqkja.html

[R31] 局部变量
来源：http://dali.shuidangran.top/Article/details/gt2mfmschfv.html

f() { local x=1; echo "$x"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2gefluget.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aozwavcw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gt2dnmunivz.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gt2asegmfig.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yuanzhike.top/Article/details/gt2hvoktfej.html

[R34] 退出时清理
来源：http://dali.dianchejie.cn/Article/details/gt2wgzorvyj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gt2kcgagvqi.html

[R35] 后台执行并等待
来源：http://dali.zycfv.cn/Article/details/gt2ifkfikdw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.aibaodan.cn/Article/details/gt2qidnnzfp.html

[R36] 并发执行多个任务
来源：http://dali.smart0.xyz/Article/details/gt2zvacxrdv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pengpengdd.cyou/Article/details/gt2esqhrfwe.html

[R37] 把输出赋给变量
来源：http://dali.pycfn.com/Article/details/gt2ihbneyws.html

files=$(ls -1)
来源：http://dali.wangshuangyany.cn/Article/details/gt2wgcambih.html

[R38] 管道串联
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sftqdian.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gt2tlybybsd.html

[R39] 重定向标准输出与错误
来源：http://dali.vqdsnc.cn/Article/details/gt2vtjepylw.html

cmd > out.log 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xhxrlkwh.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wtpljxde.html

echo "log" >> out.log
来源：http://dali.wangdashe.top/Article/details/gt2uchgftgp.html

[R41] 丢弃输出
来源：http://dali.yangfankeji.com/Article/details/gt2cfwektgo.html

cmd >/dev/null 2>&1
来源：http://dali.jqgfzy.top/Article/details/gt2qhwmditq.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gt2njwxuczz.html

wc -l < a.txt
来源：http://dali.bjfxy.top/Article/details/gt2epeqqewy.html

[R43] 按名字查找文件
来源：http://dali.svipenyu.cn/Article/details/gt2zvtxckqz.html

find . -name "*.log" -type f
来源：http://dali.yongpay.top/Article/details/gt2cjbetnhn.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gt2vucfnool.html

find . -mtime -7 -type f
来源：http://dali.redwolf501.top/Article/details/gt2peelytku.html

[R45] 批量删除
来源：http://dali.daria6918.cn/Article/details/gt2tepeeyla.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gt2zfjvtvwe.html

[R46] 递归替换文件内容
来源：http://dali.zhongyouzk.top/Article/details/gt2kogbjiks.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gt2fubbxezy.html

[R47] sed 单行替换
来源：http://dali.shuidangran.top/Article/details/gt2bxsnbtsh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2jyvzqgez.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gt2icoxpbgv.html

awk '{print $1, $3}' a.txt
来源：http://dali.ivvv.top/Article/details/gt2xajlsvuz.html

[R49] awk 带条件
来源：http://dali.meibo888.top/Article/details/gt2gxqvnkom.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xuanzx.com/Article/details/gt2tibmdqjh.html

[R50] awk 求和
来源：http://dali.0kj1m.cn/Article/details/gt2pizuvkom.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yvedp.cn/Article/details/gt2quilajxj.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gt2ldrbaaqk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aizwys.cn/Article/details/gt2aenipomz.html

[R52] 统计行数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wgznyvvv.html

wc -l a.txt
来源：http://dali.nanxuanxn.top/Article/details/gt2vcbaazco.html

[R53] 查看文件头与实时尾
来源：http://dali.fengsongda.top/Article/details/gt2tiljuajn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gt2aveuxqgg.html

[R54] 比较两个文件
来源：http://dali.xuanzx.com/Article/details/gt2ehqrdeqp.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gt2kaaiiyfy.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gt2nmjtkwyx.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.9152youxi.cn/Article/details/gt2xaimysjc.html

[R56] 远程拷贝
来源：http://dali.ydzc1.top/Article/details/gt2vdhpkuhf.html

scp file user@host:/path/
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybpzfkix.html

[R57] 远程执行命令
来源：http://dali.hnqzz.top/Article/details/gt2trlhnfvz.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gt2ooxjznrf.html

[R58] 下载文件
来源：http://dali.jyoumei.cn/Article/details/gt2nfdltagf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jiagoushi.top/Article/details/gt2gfrergmz.html

[R59] 发 POST JSON
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmliokiz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hysaishi.cn/Article/details/gt2ikojtrdx.html

[R60] 只看 HTTP 状态码
来源：http://dali.daria6918.cn/Article/details/gt2juekyajm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnxiangtu.top/Article/details/gt2lhmpernt.html

[R61] 磁盘占用
来源：http://dali.sufxvd.cn/Article/details/gt2lttfqauo.html

df -h;  du -sh *
来源：http://dali.ydzc1.top/Article/details/gt2znotjreb.html

[R62] 找最占空间的文件
来源：http://dali.pycfn.com/Article/details/gt2znrtgjuw.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gt2ozohpmoy.html

[R63] 内存与进程
来源：http://dali.xuanzx.com/Article/details/gt2xjrhzkvk.html

free -h;  ps aux | grep nginx
来源：http://dali.aizwys.cn/Article/details/gt2ymozxcxd.html

[R64] 结束进程
来源：http://dali.iojbl.cn/Article/details/gt2jjatyzxu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gt2pytcxlec.html

[R65] 查看端口占用
来源：http://dali.wangshuangyany.cn/Article/details/gt2qlxnqbih.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gt2iraupucs.html

[R66] 定时任务
来源：http://dali.haohaochexian.top/Article/details/gt2qutefwwv.html

crontab -e;  crontab -l
来源：http://dali.jinqigfzy.top/Article/details/gt2ikpusjah.html

[R67] 生成随机十六进制串
来源：http://dali.quarkkingdee.top/Article/details/gt2tlhzienm.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gt2zmnnsnzc.html

[R68] 计算文件校验值
来源：http://dali.yangfankeji.com/Article/details/gt2ontoyrwh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258.top/Article/details/gt2fivppjjp.html

[R69] 生成随机密码
来源：http://dali.9152youxi.cn/Article/details/gt2tfhnoezs.html

head -c 16 /dev/urandom | base64
来源：http://dali.cdnleiting.top/Article/details/gt2jqnzixtp.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gt2lokgoqyo.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gt2hjibgokt.html

[R71] 日期格式化
来源：http://dali.cqqwz.cn/Article/details/gt2bkoxjvmq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.fengsongda.top/Article/details/gt2wtbbuuvw.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gt2odmxdfeh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gt2qszcgmor.html

[R73] 分割大日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2egiqezui.html

split -l 1000 big.log part_
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qjhwaslj.html

[R74] 批量重命名
来源：http://dali.nwbrower.top/Article/details/gt2eemqxzqb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gt2ahkcclsp.html

[R75] 导出环境变量
来源：http://dali.aibaodan.cn/Article/details/gt2hnyxttwx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gt2mofozkag.html

[R76] 使用临时文件
来源：http://dali.kuanghao11.cn/Article/details/gt2yzrelhzg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gt2tscaecwn.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gt2hjvykrup.html

read -rp "请输入: " ans
来源：http://dali.vqdsnc.cn/Article/details/gt2sxeywrao.html

[R78] 交互式菜单
来源：http://dali.hongshengwenyu.top/Article/details/gt2vmlvbavj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gt2epkqnuly.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gt2pbkqlkak.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2lsnxpkwk.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kixwcnhh.html

time ./run.sh
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mvmoahnz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2yswtjsuo.html

S. C / C++ 专题
来源：http://dali.yangfankeji.com/Article/details/gt2fahqtflq.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2kpfcupge.html

[S01] C：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gt2mswjhqzs.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gt2rixqqsqv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.9152youxi.cn/Article/details/gt2tnrydxxl.html

[S02] C：变量与格式化输出
来源：http://dali.gzhubu.top/Article/details/gt2wjtrfkxd.html

int a = 10; printf("%d\n", a);
来源：http://dali.redwolf501.top/Article/details/gt2etkscsfa.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gt2fetrhfad.html

int x; scanf("%d", &x);
来源：http://dali.xylfe.cn/Article/details/gt2nivatqby.html

[S04] C：字符串复制
来源：http://dali.pycfn.com/Article/details/gt2rxsdekjf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gt2mebvksef.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngojavvw.html

strlen(s)
来源：http://dali.guowangkeji.top/Article/details/gt2nnlemsjf.html

[S06] C：字符串比较
来源：http://dali.9152youxi.cn/Article/details/gt2dhmjeriy.html

strcmp(a, b) == 0
来源：http://dali.aibaodan.cn/Article/details/gt2jyjdmaqg.html

[S07] C：数组遍历求和
来源：http://dali.chenlongwang.top/Article/details/gt2jhqlktxx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gt2cfzbimzq.html

[S08] C：动态内存分配与释放
来源：http://dali.guannengcc.top/Article/details/gt2hqrpajbr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fzhhl.top/Article/details/gt2wpiyqtpi.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgufenzy.top/Article/details/gt2igruckmg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gt2pkjaupbc.html

[S10] C：指针与解引用
来源：http://dali.jlsjyb.cn/Article/details/gt2toaaogxo.html

int *p = &a;  *p = 5;
来源：http://dali.chenzaomai.com/Article/details/gt2tdvvgkeh.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fwilzheq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenjidiqi.icu/Article/details/gt2qpbtwofq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ydzc1.top/Article/details/gt2dnehcjmx.html

fclose(f);
来源：http://dali.shuidangran.top/Article/details/gt2gtxnysqf.html

[S12] C：写文件
来源：http://dali.316326.xyz/Article/details/gt2zofhgcfx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gt2bnihqfld.html

[S13] C：宏定义
来源：http://dali.jinqigufen.top/Article/details/gt2hblmtjfr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xylfe.cn/Article/details/gt2fhlyidrz.html

[S14] C：枚举
来源：http://dali.dianchejie.cn/Article/details/gt2ulubptcm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gt2hshxjsmh.html

[S15] C：类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqqwplns.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gt2uamtmnpa.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gt2xwxkapfy.html

x |= (1 << 3);
来源：http://dali.andypj.xyz/Article/details/gt2xczunynv.html

[S17] C：安全拼接字符串
来源：http://dali.xziqi.cn/Article/details/gt2pdifoogk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tian-w.cn/Article/details/gt2ttlbifqt.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gt2oizvbdxt.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gt2tgmooljt.html

[S19] C：快速排序
来源：http://dali.yj202588.top/Article/details/gt2opgwdbgn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gt2jzwntvnr.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gt2dlexicwb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gt2eawftkns.html

[S21] C：字符类别判断
来源：http://dali.yj202588.top/Article/details/gt2wargnmwh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ppjwa.cn/Article/details/gt2bhyrreec.html

[S22] C：字符串转数字
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqiellma.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gt2jddfxyvg.html

[S23] C：随机数
来源：http://dali.bjfxy.top/Article/details/gt2ciqivuwl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gotoacloud.top/Article/details/gt2wvvnpbns.html

[S24] C：获取本地时间
来源：http://dali.sufxvd.cn/Article/details/gt2gdqjzcjz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgufenzy.top/Article/details/gt2dxtiwakz.html

[S25] C：内存拷贝
来源：http://dali.aizwys.cn/Article/details/gt2mvmmfhwa.html

memcpy(dst, src, n);
来源：http://dali.jiagoushi.top/Article/details/gt2edkncvwg.html

[S26] C：内存清零
来源：http://dali.yuxming.cn/Article/details/gt2agiyjmpi.html

memset(a, 0, sizeof a);
来源：http://dali.yanxiufei.cn/Article/details/gt2waikckbg.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gt2wfyuocls.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gt2ccsyneye.html

[S28] C：静态变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2fdiwybgf.html

static int counter = 0;
来源：http://dali.tian-w.cn/Article/details/gt2fvzkapno.html

[S29] C：变参函数
来源：http://dali.aibaodan.cn/Article/details/gt2mhmkleip.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sxryk.cn/Article/details/gt2nhxuwvvi.html

[S30] C：头文件保护
来源：http://dali.guannengcc.top/Article/details/gt2flmaveuh.html

#ifndef X_H
来源：http://dali.ydzc1.top/Article/details/gt2ysmntbwd.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gt2nzzabzgf.html

#endif
来源：http://dali.havefunace.top/Article/details/gt2soindany.html

[S31] C++：Hello World
来源：http://dali.yj202588.top/Article/details/gt2blokkifm.html

#include <iostream>
来源：http://dali.zhongyouzk.top/Article/details/gt2xgnegjmr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tian-w.cn/Article/details/gt2pawloafj.html

[S32] C++：字符串
来源：http://dali.jyoumei.cn/Article/details/gt2hacsfhgo.html

std::string s = "hi";  s += "!";
来源：http://dali.sxryk.cn/Article/details/gt2xthjcsnd.html

[S33] C++：vector 增删
来源：http://dali.hammf.cn/Article/details/gt2yowkokdu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hywenlv.cn/Article/details/gt2fmonujpj.html

[S34] C++：遍历 vector
来源：http://dali.hammf.cn/Article/details/gt2zlynylem.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jiagoushi.top/Article/details/gt2xhcbnxdl.html

[S35] C++：map
来源：http://dali.jiagoushi.top/Article/details/gt2sgwnlyau.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gt2mwsvfllk.html

[S36] C++：unordered_map
来源：http://dali.hammf.cn/Article/details/gt2supfvfqd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2hoxmhjcq.html

[S37] C++：set
来源：http://dali.jlsjyb.cn/Article/details/gt2onxonprs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gt2gligjvge.html

[S38] C++：排序
来源：http://dali.guowangkeji.top/Article/details/gt2ybcbhhyb.html

std::sort(v.begin(), v.end());
来源：http://dali.ppjwa.cn/Article/details/gt2mnaopeey.html


<!-- 参考信息 -->