代发 wailian999

[Q61] 移动平均
来源：http://dali.hfpthk.cn/Article/details/gt2djyffiyl.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.sxryk.cn/Article/details/gt2eldqahvy.html

[Q62] 分组占比
来源：http://dali.yj20258888.top/Article/details/gt2vhewbtqm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hongshengwenyu.top/Article/details/gt2htbslqqq.html

[Q63] 开启事务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ulfzwonl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yongpay.top/Article/details/gt2ivnsjyeq.html

[Q64] 提交事务
来源：http://dali.aibaodan.cn/Article/details/gt2glnpqiba.html

COMMIT;
来源：http://dali.9152youxi.cn/Article/details/gt2qgmuxekw.html

[Q65] 回滚事务
来源：http://dali.shangyingyoupin.top/Article/details/gt2rixyeuar.html

ROLLBACK;
来源：http://dali.jlsjyb.cn/Article/details/gt2jfevxmsp.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gt2kymfeznm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgufenzy.top/Article/details/gt2pevnpvzc.html

[Q67] 设置隔离级别
来源：http://dali.gotoacloud.top/Article/details/gt2qaolahbn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xylfe.cn/Article/details/gt2lizjppsg.html

[Q68] 保存点
来源：http://dali.shangyingyoupin.top/Article/details/gt2iaqfernw.html

SAVEPOINT sp1;
来源：http://dali.yangfankeji.com/Article/details/gt2vbrqsytd.html

ROLLBACK TO sp1;
来源：http://dali.fzhhl.top/Article/details/gt2dpsswnjl.html

[Q69] 查看执行计划
来源：http://dali.hnxiangtu.top/Article/details/gt2oapnfbxk.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vskfihgr.html

[Q70] 更新统计信息
来源：http://dali.smart0.xyz/Article/details/gt2btxujhul.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gt2bjxwehoi.html

[Q71] 查看建表语句
来源：http://dali.jinqigufen.top/Article/details/gt2ugehpgea.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxuanxn.top/Article/details/gt2byajivsb.html

[Q72] 查看索引
来源：http://dali.xylfe.cn/Article/details/gt2szrkpack.html

SHOW INDEX FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2zkjzjlso.html

[Q73] 查看表状态
来源：http://dali.jqgufenzy.top/Article/details/gt2lnrgubxp.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ivvv.top/Article/details/gt2urvodkdj.html

[Q74] 强制使用索引
来源：http://dali.sweek.top/Article/details/gt2hxmrdvks.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yonumen.top/Article/details/gt2ikirtmeo.html

[Q75] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gt2xzwkduan.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tdyxzsfk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.meibo888.top/Article/details/gt2qrodpqov.html

[Q76] 按天统计
来源：http://dali.yj20258888.top/Article/details/gt2imfjbhdo.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gt2mxlknfqm.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2iotcfoyn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.mhx1999.top/Article/details/gt2qrpznffn.html

[Q78] 当前时间
来源：http://dali.pengpengdd.cyou/Article/details/gt2gujqaksw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gt2aaxxgygt.html

[Q79] 字符串拼接
来源：http://dali.tanke756.top/Article/details/gt2ylffltnk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinqigfzy.top/Article/details/gt2ycqwgjjs.html

[Q80] 字符串截取
来源：http://dali.chenlongwang.top/Article/details/gt2lyfwxlck.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.havefunace.top/Article/details/gt2tzbpbhne.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gt2fgajfhvr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2lfnblqhy.html

[Q82] 字符长度与字节长度
来源：http://dali.cucudq.cn/Article/details/gt2mfkscfio.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gt2prqyhjdk.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gt2fcvwmctq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ydzc1.top/Article/details/gt2wwjrcguo.html

[Q84] 去除首尾空格
来源：http://dali.quarkkingdee.top/Article/details/gt2arwcuocd.html

SELECT TRIM(name) FROM users;
来源：http://dali.yongpay.top/Article/details/gt2vrzdzgix.html

[Q85] 数值取整
来源：http://dali.chenjidiqi.icu/Article/details/gt2btdtdtbi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gzhubu.top/Article/details/gt2txgxwtnv.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gt2evmuhzen.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gt2yfqnbpsc.html

[Q87] JSON 字段做条件
来源：http://dali.nwbrower.top/Article/details/gt2bgpiglab.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxinkj.top/Article/details/gt2nijsejij.html

[Q88] 行转列（条件聚合）
来源：http://dali.ivvv.top/Article/details/gt2fhhpudug.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcwvrcno.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hywenlv.cn/Article/details/gt2aqslurcm.html

[Q89] 判断表是否存在
来源：http://dali.fengsongda.top/Article/details/gt2idovdgem.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gt2quigwezh.html

[Q90] 生成序号列
来源：http://dali.tian-w.cn/Article/details/gt2rwxeiatm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fengsongda.top/Article/details/gt2jiiwhygd.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2ehhboons.html

R. Bash 专题
来源：http://dali.ppjwa.cn/Article/details/gt2mxlbgxxq.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2ytpmuydx.html

[R01] shebang 与严格模式
来源：http://dali.yj20258.top/Article/details/gt2sehkngjs.html

#!/usr/bin/env bash
来源：http://dali.tanke756.top/Article/details/gt2qozfgtfo.html

set -euo pipefail
来源：http://dali.cdnleiting.top/Article/details/gt2podlzwez.html

[R02] 变量赋值与使用
来源：http://dali.smart0.xyz/Article/details/gt2dtdpkaoe.html

name="Tom"; echo "$name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmaciytg.html

[R03] 只读变量
来源：http://dali.zhongyouzk.top/Article/details/gt2emixlrgb.html

readonly PI=3.14
来源：http://dali.yj20258.top/Article/details/gt2thfexunr.html

[R04] 位置参数
来源：http://dali.aizwys.cn/Article/details/gt2psrravkd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifygefja.html

[R05] 参数默认值
来源：http://dali.yj202588.top/Article/details/gt2lvzfphqp.html

name="${1:-default}"
来源：http://dali.hysaishi.cn/Article/details/gt2qmovbghn.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2lfcqaaqe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gt2nhxpxwsd.html

[R07] if 判断文件
来源：http://dali.yj20258.top/Article/details/gt2hhcdasey.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yj202588.top/Article/details/gt2viaocwij.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gt2hbypqqti.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gt2wezgshoo.html

[R09] 字符串比较
来源：http://dali.meibo888.top/Article/details/gt2izpwvces.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj202588.top/Article/details/gt2czhgmzdz.html

[R10] 正则匹配
来源：http://dali.yueranfly.top/Article/details/gt2nkzujyzy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2tzknxmyp.html

[R11] case 多分支
来源：http://dali.yj20258.top/Article/details/gt2fzelfsfn.html

case "$1" in
来源：http://dali.yuxming.cn/Article/details/gt2erhajghu.html

start) echo "启动" ;;
来源：http://dali.yvedp.cn/Article/details/gt2dberlzkf.html

stop)  echo "停止" ;;
来源：http://dali.sysykeji.top/Article/details/gt2aqfjvqje.html

*)     echo "未知命令" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gt2nwcgjpbc.html

esac
来源：http://dali.jqgfzy.top/Article/details/gt2qlvbjabp.html

[R12] for 遍历文件
来源：http://dali.hammf.cn/Article/details/gt2sosvzlwn.html

for f in *.txt; do echo "$f"; done
来源：http://dali.birdmap.top/Article/details/gt2tfdgekwd.html

[R13] for 计数循环
来源：http://dali.zhongyouzk.top/Article/details/gt2yxrfbbsp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gt2zzmhntim.html

[R14] C 风格 for
来源：http://dali.ivvv.top/Article/details/gt2kfostxtx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gt2pjuangsl.html

[R15] while 逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2hntfojcw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tianlin.xyz/Article/details/gt2ixlhebir.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gt2ofaygdvc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gt2kxltnapz.html

[R17] 数组定义与取值
来源：http://dali.zhengqikj.top/Article/details/gt2lhxzdjvi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shuidangran.top/Article/details/gt2ljgcadxn.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wyxwbhoo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.chenlongwang.top/Article/details/gt2kuvmdtec.html

[R19] 数组长度
来源：http://dali.iojbl.cn/Article/details/gt2anudmppw.html

echo "${#arr[@]}"
来源：http://dali.smart0.xyz/Article/details/gt2zmpvwgqc.html

[R20] 关联数组（字典）
来源：http://dali.meibo888.top/Article/details/gt2srothzlm.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hywenlv.cn/Article/details/gt2yxbojztz.html

[R21] 字符串长度
来源：http://dali.yuanzhike.top/Article/details/gt2qnkhxtvy.html

echo "${#s}"
来源：http://dali.zycfv.cn/Article/details/gt2puimailv.html

[R22] 截取子串
来源：http://dali.andypj.xyz/Article/details/gt2fwxrewxf.html

echo "${s:0:5}"
来源：http://dali.shzxlz.cn/Article/details/gt2lgdxfzba.html

[R23] 字符串替换
来源：http://dali.zhixingplan.top/Article/details/gt2xaqljsrf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gt2fatoukfj.html

[R24] 大小写转换
来源：http://dali.316326.xyz/Article/details/gt2xcvspxxm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gt2ecfcxdgd.html

[R25] 去后缀 / 去前缀
来源：http://dali.c1oappe.top/Article/details/gt2ttnsembf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.meibo888.top/Article/details/gt2jvtkqwae.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ajfiktkd.html

now=$(date +%F); echo "$now"
来源：http://dali.cheryme.top/Article/details/gt2kvmgdkvj.html

[R27] 算术展开
来源：http://dali.hfpthk.cn/Article/details/gt2thwonond.html

echo $((1 + 2 * 3))
来源：http://dali.ybcxt.top/Article/details/gt2aboagruo.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gt2xaoofjko.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gt2bygplmfq.html

[R29] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gt2roltyiur.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.quarkkingdee.top/Article/details/gt2bxrvbkxf.html

[R30] 函数返回状态码
来源：http://dali.zhoulong.xyz/Article/details/gt2dofbenna.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gt2xqbwnmlw.html

[R31] 局部变量
来源：http://dali.jqgufenzy.top/Article/details/gt2lxvewtcw.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mbvehkkn.html

[R32] 参数个数校验
来源：http://dali.ybcxt.top/Article/details/gt2xpbajczi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gt2tqjgviwj.html

[R33] 捕获错误并提示行号
来源：http://dali.c1oappe.top/Article/details/gt2wdlabvwf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.smart0.xyz/Article/details/gt2ftsvvwok.html

[R34] 退出时清理
来源：http://dali.daria6918.cn/Article/details/gt2rrqebaxj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gt2ojnjpmlv.html

[R35] 后台执行并等待
来源：http://dali.zycfv.cn/Article/details/gt2oddxpehe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gt2nevpkktt.html

[R36] 并发执行多个任务
来源：http://dali.sysykeji.top/Article/details/gt2tfxcqrre.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.c1oappe.top/Article/details/gt2jfhcrrma.html

[R37] 把输出赋给变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2pdskopoh.html

files=$(ls -1)
来源：http://dali.yj20258.top/Article/details/gt2mfqxrgtw.html

[R38] 管道串联
来源：http://dali.nanxinkj.top/Article/details/gt2stgqsrjt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jpfszqlj.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gt2fcwfwyfz.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gt2xhmiicri.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gt2ljhatpcb.html

echo "log" >> out.log
来源：http://dali.cashguo.top/Article/details/gt2qvsfwgym.html

[R41] 丢弃输出
来源：http://dali.cucudq.cn/Article/details/gt2ghmidbtl.html

cmd >/dev/null 2>&1
来源：http://dali.smart0.xyz/Article/details/gt2pbhrtxpb.html

[R42] 输入重定向
来源：http://dali.hysaishi.cn/Article/details/gt2czntywim.html

wc -l < a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2ipgrzwie.html

[R43] 按名字查找文件
来源：http://dali.ivvv.top/Article/details/gt2qiujnquj.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gt2hnqkxegk.html

[R44] 按修改时间查找
来源：http://dali.yvedp.cn/Article/details/gt2intaurod.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gt2ngorxytk.html

[R45] 批量删除
来源：http://dali.birdmap.top/Article/details/gt2jcobqahq.html

find . -name "*.tmp" -delete
来源：http://dali.jqgfzy.top/Article/details/gt2aeoqurmo.html

[R46] 递归替换文件内容
来源：http://dali.pycfn.com/Article/details/gt2hnuogmfq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hfpthk.cn/Article/details/gt2phzwflfx.html

[R47] sed 单行替换
来源：http://dali.sufxvd.cn/Article/details/gt2glnqczvp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aibaodan.cn/Article/details/gt2syvcujmo.html

[R48] awk 取指定列
来源：http://dali.hnxiangtu.top/Article/details/gt2ctacqhjs.html

awk '{print $1, $3}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gt2dtrquoqs.html

[R49] awk 带条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2kwfypkvp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2povjuvvt.html

[R50] awk 求和
来源：http://dali.quarkkingdee.top/Article/details/gt2wdrzzlrt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gt2wdtwzqga.html

[R51] 排序去重取前几
来源：http://dali.gotoacloud.top/Article/details/gt2copbjapj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gt2yznbqhax.html

[R52] 统计行数
来源：http://dali.daxiang520.top/Article/details/gt2tbjmeqtx.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gt2bnjandvz.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gt2sjxyyohq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigufen.top/Article/details/gt2brrpvoak.html

[R54] 比较两个文件
来源：http://dali.yj20258.top/Article/details/gt2ihadldja.html

diff a.txt b.txt
来源：http://dali.cqqwz.cn/Article/details/gt2cnerxfrd.html

[R55] 压缩与解压
来源：http://dali.nanxinkj.top/Article/details/gt2ystdvhgo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yueranfly.top/Article/details/gt2dhekojpx.html

[R56] 远程拷贝
来源：http://dali.hnxiangtu.top/Article/details/gt2oenryqbd.html

scp file user@host:/path/
来源：http://dali.pycfn.com/Article/details/gt2mrztwisa.html

[R57] 远程执行命令
来源：http://dali.xylfe.cn/Article/details/gt2hzjvmwnr.html

ssh user@host 'uptime'
来源：http://dali.tanke756.top/Article/details/gt2vqhzmncf.html

[R58] 下载文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tuphytzy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ivvv.top/Article/details/gt2cowetajs.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gt2lownjruw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jianghu66.top/Article/details/gt2mbqbqsed.html

[R60] 只看 HTTP 状态码
来源：http://dali.jyoumei.cn/Article/details/gt2kvotvwwy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tanke756.top/Article/details/gt2fholufye.html

[R61] 磁盘占用
来源：http://dali.ybcxt.top/Article/details/gt2xlvfgxsh.html

df -h;  du -sh *
来源：http://dali.andypj.xyz/Article/details/gt2tbaueqxj.html

[R62] 找最占空间的文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2dosvzlyy.html

du -ah . | sort -rh | head -10
来源：http://dali.yuxming.cn/Article/details/gt2kbkhnfif.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gt2naiphalf.html

free -h;  ps aux | grep nginx
来源：http://dali.yuxming.cn/Article/details/gt2cgtgbvlw.html

[R64] 结束进程
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbhuqoyt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.smart0.xyz/Article/details/gt2xjqfsvir.html

[R65] 查看端口占用
来源：http://dali.ivvv.top/Article/details/gt2cuiadrvl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.kuanghao11.cn/Article/details/gt2anmsilyh.html

[R66] 定时任务
来源：http://dali.ppjwa.cn/Article/details/gt2gdxptcfu.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gt2fdjgzsxm.html

[R67] 生成随机十六进制串
来源：http://dali.hfpthk.cn/Article/details/gt2kjzqotqy.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gt2wnltxcgn.html

[R68] 计算文件校验值
来源：http://dali.wangdashe.top/Article/details/gt2numhigxl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2qnuvdtkx.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gt2sehblfrg.html

head -c 16 /dev/urandom | base64
来源：http://dali.yonumen.top/Article/details/gt2jooqomwr.html

[R70] 时间戳与互转
来源：http://dali.jinqigufen.top/Article/details/gt2nkhdfexo.html

date +%s;  date -d @1700000000
来源：http://dali.jqgufenzy.top/Article/details/gt2mlyuzapk.html

[R71] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gt2ucomlpwy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yanxiufei.cn/Article/details/gt2sapbshef.html

[R72] 等待端口就绪
来源：http://dali.quarkkingdee.top/Article/details/gt2mninndwf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gt2ksqryvgf.html

[R73] 分割大日志
来源：http://dali.dianchejie.cn/Article/details/gt2uiwdlvqy.html

split -l 1000 big.log part_
来源：http://dali.guowangkeji.top/Article/details/gt2ontxeoer.html

[R74] 批量重命名
来源：http://dali.fengsongda.top/Article/details/gt2lrguhcfu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gt2byxgkqlm.html

[R75] 导出环境变量
来源：http://dali.nanxuanxn.top/Article/details/gt2gaxpgysx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gt2uvxtsyqv.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gt2vdooavrp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gt2hjfuhrrz.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gt2kksuuizy.html

read -rp "请输入: " ans
来源：http://dali.shangyingyoupin.top/Article/details/gt2hpcskzxr.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gt2awgyfkht.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj202588.top/Article/details/gt2kbzihdns.html

[R79] 解析命令行选项
来源：http://dali.jqgfzy.top/Article/details/gt2neyfjqdo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.quarkkingdee.top/Article/details/gt2kkbnvfhn.html

[R80] 查看脚本执行耗时
来源：http://dali.jlsjyb.cn/Article/details/gt2qfogzlrn.html

time ./run.sh
来源：http://dali.jinqigufen.top/Article/details/gt2snyfqtnk.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2yyuczzpn.html

S. C / C++ 专题
来源：http://dali.xuanzx.com/Article/details/gt2qanhbmcj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2tvcjxpbb.html

[S01] C：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2dxijsteq.html

#include <stdio.h>
来源：http://dali.yanxiufei.cn/Article/details/gt2tnmftdwa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.meibo888.top/Article/details/gt2fdplwrek.html

[S02] C：变量与格式化输出
来源：http://dali.yj202588.top/Article/details/gt2oetbslzl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhoulong.xyz/Article/details/gt2qhmcnyej.html

[S03] C：读入整数
来源：http://dali.jiagoushi.top/Article/details/gt2evnpozty.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jweasopk.html

[S04] C：字符串复制
来源：http://dali.ybcxt.top/Article/details/gt2zbafhkli.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yongpay.top/Article/details/gt2eajujglw.html

[S05] C：字符串长度
来源：http://dali.guannengcc.top/Article/details/gt2pjijipdh.html

strlen(s)
来源：http://dali.birdmap.top/Article/details/gt2ycjntrmt.html

[S06] C：字符串比较
来源：http://dali.meibo888.top/Article/details/gt2czouryzw.html

strcmp(a, b) == 0
来源：http://dali.hongshengwenyu.top/Article/details/gt2jqmphxex.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gt2iufubwqb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zycfv.cn/Article/details/gt2wsvghfoz.html

[S08] C：动态内存分配与释放
来源：http://dali.hnqzz.top/Article/details/gt2bouobdoi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.smart0.xyz/Article/details/gt2kcxzapgq.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gt2zfysufwn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ppjwa.cn/Article/details/gt2bozzrrdv.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gt2xammmlcn.html

int *p = &a;  *p = 5;
来源：http://dali.xinyue.icu/Article/details/gt2kpybwfxy.html

[S11] C：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2kqcpccom.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.smart0.xyz/Article/details/gt2hzoprihw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.316326.xyz/Article/details/gt2itgpezzk.html

fclose(f);
来源：http://dali.fzhhl.top/Article/details/gt2njtxoxyt.html

[S12] C：写文件
来源：http://dali.yuxming.cn/Article/details/gt2gqosfbrh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gt2fqnjjatn.html

[S13] C：宏定义
来源：http://dali.jianghu66.top/Article/details/gt2mzpzlhbi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sufxvd.cn/Article/details/gt2uuwoepqy.html

[S14] C：枚举
来源：http://dali.birdmap.top/Article/details/gt2exjvtlsr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guannengcc.top/Article/details/gt2fiubxzwx.html

[S15] C：类型转换
来源：http://dali.havefunace.top/Article/details/gt2prclkhdc.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gt2tluhkvee.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gt2ehuchyhj.html

x |= (1 << 3);
来源：http://dali.birdmap.top/Article/details/gt2ltkyrqgf.html

[S17] C：安全拼接字符串
来源：http://dali.bjfxy.top/Article/details/gt2qtdzvnni.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ybcxt.top/Article/details/gt2kdenfbok.html

[S18] C：命令行参数
来源：http://dali.cucudq.cn/Article/details/gt2ybounkky.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gt2tuouixkd.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gt2qbqxdfkl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gt2tbyhwkxl.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gt2oavsdtim.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gt2lxmhorgr.html

[S21] C：字符类别判断
来源：http://dali.tian-w.cn/Article/details/gt2nvdnzhun.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dianchejie.cn/Article/details/gt2weelehpi.html

[S22] C：字符串转数字
来源：http://dali.birdmap.top/Article/details/gt2cdlddpzi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pycfn.com/Article/details/gt2pndvqrmr.html

[S23] C：随机数
来源：http://dali.redwolf501.top/Article/details/gt2fzgdlqgr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.pycfn.com/Article/details/gt2zwqsovqw.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gt2myzkhitz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.redwolf501.top/Article/details/gt2qiogdmik.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gt2kqtzomnn.html

memcpy(dst, src, n);
来源：http://dali.dianchejie.cn/Article/details/gt2bcboufae.html

[S26] C：内存清零
来源：http://dali.gaohongyu789.top/Article/details/gt2algnmmek.html

memset(a, 0, sizeof a);
来源：http://dali.zhongyouzk.top/Article/details/gt2mefpzfxa.html

[S27] C：定义常量
来源：http://dali.shzxlz.cn/Article/details/gt2ltqtxmub.html

const double PI = 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gt2opcwkskc.html

[S28] C：静态变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vchhqvou.html

static int counter = 0;
来源：http://dali.tianlin.xyz/Article/details/gt2yhjzfwxa.html

[S29] C：变参函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jbpinwyr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hongshengwenyu.top/Article/details/gt2whdbxltm.html

[S30] C：头文件保护
来源：http://dali.zhixingplan.top/Article/details/gt2pusthpqa.html

#ifndef X_H
来源：http://dali.mhx1999.top/Article/details/gt2dstivogm.html

#define X_H
来源：http://dali.meibo888.top/Article/details/gt2kywyymvq.html

#endif
来源：http://dali.xuetiantiany.cn/Article/details/gt2nliujrmx.html

[S31] C++：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gt2zesvsyfr.html


<!-- 参考信息 -->