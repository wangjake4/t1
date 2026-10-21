代发 wailian999

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yonumen.top/Article/details/gtlbfbsnnk.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gtpnnvtidy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtvcpydnsk.html

[Q59] 分组内累计
来源：http://dali.kuanghao11.cn/Article/details/gtegpcabiz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtzvtprmwg.html

[Q60] 取上一行 / 下一行
来源：http://dali.yj20258888.top/Article/details/gtbtnvxzat.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gaohongyu789.top/Article/details/gtvrgbhhic.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtekwdqjrq.html

[Q61] 移动平均
来源：http://dali.cashguo.top/Article/details/gtjbqripuw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtrojzkisk.html

[Q62] 分组占比
来源：http://dali.aizwys.cn/Article/details/gtbvbjbwoy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gtrugqljlh.html

[Q63] 开启事务
来源：http://dali.hfpthk.cn/Article/details/gtepnbjtse.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hongshengwenyu.top/Article/details/gtweawrobl.html

[Q64] 提交事务
来源：http://dali.yongpay.top/Article/details/gtvhfpeosr.html

COMMIT;
来源：http://dali.zhiwuduotai.top/Article/details/gtnmivdujj.html

[Q65] 回滚事务
来源：http://dali.0kj1m.cn/Article/details/gtpvyqjkju.html

ROLLBACK;
来源：http://dali.hnxiangtu.top/Article/details/gtzxovprmy.html

[Q66] 行锁查询
来源：http://dali.fzhhl.top/Article/details/gtoqjeaqyb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.dianchejie.cn/Article/details/gtvpkfpvxy.html

[Q67] 设置隔离级别
来源：http://dali.zhiwuduotai.top/Article/details/gtplbihwca.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxinkj.top/Article/details/gtlzhontnb.html

[Q68] 保存点
来源：http://dali.ehwqpu.com/Article/details/gtrzjsmzci.html

SAVEPOINT sp1;
来源：http://dali.gaohongyu789.top/Article/details/gtkotqzjcy.html

ROLLBACK TO sp1;
来源：http://dali.yuxming.cn/Article/details/gtxtrcmnkk.html

[Q69] 查看执行计划
来源：http://dali.zhengqikj.top/Article/details/gtvhryujsd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hfpthk.cn/Article/details/gtkcurqfmo.html

[Q70] 更新统计信息
来源：http://dali.cucudq.cn/Article/details/gtrifmmndj.html

ANALYZE TABLE users;
来源：http://dali.zhoulong.xyz/Article/details/gtfieoijmq.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gtqqlopntp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yanxiufei.cn/Article/details/gtrlrlzbuw.html

[Q72] 查看索引
来源：http://dali.cqqwz.cn/Article/details/gtklzswhpm.html

SHOW INDEX FROM users;
来源：http://dali.redwolf501.top/Article/details/gtbslcpjeh.html

[Q73] 查看表状态
来源：http://dali.snrcjt.cn/Article/details/gtaevznahg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sxryk.cn/Article/details/gthsiruvak.html

[Q74] 强制使用索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmmuuuxl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigufen.top/Article/details/gtnpcltmut.html

[Q75] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gtrzntgstt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ybcxt.top/Article/details/gtczwehyeq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yanxiufei.cn/Article/details/gtqqyodclp.html

[Q76] 按天统计
来源：http://dali.yj202588.top/Article/details/gtmxlasoth.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ydzc1.top/Article/details/gtforfqode.html

[Q77] 时间加减
来源：http://dali.redwolf501.top/Article/details/gtplklkami.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yongpay.top/Article/details/gtngjghcrv.html

[Q78] 当前时间
来源：http://dali.pycfn.com/Article/details/gtihuwihdi.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.bjfxy.top/Article/details/gtdzivkqff.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gttqyggwar.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gtcrhpglaj.html

[Q80] 字符串截取
来源：http://dali.sysykeji.top/Article/details/gtjjpjttrd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtqggierbh.html

[Q81] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtcwdinzzk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yongpay.top/Article/details/gtvxxewkum.html

[Q82] 字符长度与字节长度
来源：http://dali.jyoumei.cn/Article/details/gtpcenunme.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtvpgjijlv.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtxvlwghos.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtwuteniht.html

[Q84] 去除首尾空格
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrrzhhkx.html

SELECT TRIM(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtxwdwoaga.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gtioolmdrr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daxiang520.top/Article/details/gtoxgdltqs.html

[Q86] 读取 JSON 字段
来源：http://dali.hysaishi.cn/Article/details/gtibxabppm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tanke756.top/Article/details/gtpryvmbaw.html

[Q87] JSON 字段做条件
来源：http://dali.nanxuanxn.top/Article/details/gtxomnopqq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.havefunace.top/Article/details/gttmagucjv.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gtdfyifblc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hywenlv.cn/Article/details/gtutzagfwj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj202588.top/Article/details/gttrxhyjgw.html

[Q89] 判断表是否存在
来源：http://dali.havefunace.top/Article/details/gtqboapijj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtefbckhpi.html

[Q90] 生成序号列
来源：http://dali.andypj.xyz/Article/details/gtlekyjnxc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigufen.top/Article/details/gtadpnwymo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtoypairvz.html

R. Bash 专题
来源：http://dali.svipenyu.cn/Article/details/gtlwfnamfp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzzbundjx.html

[R01] shebang 与严格模式
来源：http://dali.ydzc1.top/Article/details/gtrbpzpaol.html

#!/usr/bin/env bash
来源：http://dali.tanke756.top/Article/details/gtuqueqdnu.html

set -euo pipefail
来源：http://dali.daxiang520.top/Article/details/gtyigoelgl.html

[R02] 变量赋值与使用
来源：http://dali.pycfn.com/Article/details/gtbwyyudep.html

name="Tom"; echo "$name"
来源：http://dali.jqgufenzy.top/Article/details/gtlodjbprx.html

[R03] 只读变量
来源：http://dali.daxiang520.top/Article/details/gtbgbvyvxb.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gtgcgnxxem.html

[R04] 位置参数
来源：http://dali.guannengcc.top/Article/details/gtckkkgszk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gtmlnblrsm.html

[R05] 参数默认值
来源：http://dali.cdnleiting.top/Article/details/gtydoznpje.html

name="${1:-default}"
来源：http://dali.yj20258888.top/Article/details/gtmkrentzo.html

[R06] 判断命令是否存在
来源：http://dali.daxiang520.top/Article/details/gtsgbouicb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtqqaighvw.html

[R07] if 判断文件
来源：http://dali.yvedp.cn/Article/details/gtlkppkhrf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jqgfzy.top/Article/details/gtufcgtstf.html

[R08] 数值比较
来源：http://dali.gotoacloud.top/Article/details/gtxtycfgcg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtrlzpsnyr.html

[R09] 字符串比较
来源：http://dali.jianghu66.top/Article/details/gtbfiplejj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.aizwys.cn/Article/details/gtjopddsfm.html

[R10] 正则匹配
来源：http://dali.hnqzz.top/Article/details/gtptjpykjz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj202588.top/Article/details/gtejewtkqk.html

[R11] case 多分支
来源：http://dali.hysaishi.cn/Article/details/gtvawxcxca.html

case "$1" in
来源：http://dali.jinqigfzy.top/Article/details/gtchqrocge.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gtdmeusaav.html

stop)  echo "停止" ;;
来源：http://dali.svipenyu.cn/Article/details/gtpdowseah.html

*)     echo "未知命令" ;;
来源：http://dali.yuxming.cn/Article/details/gtzfuowljf.html

esac
来源：http://dali.svipenyu.cn/Article/details/gtsuywvchx.html

[R12] for 遍历文件
来源：http://dali.xuanzx.com/Article/details/gtwopcozsd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shzxlz.cn/Article/details/gtfzyrvmud.html

[R13] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglpivyvm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtzibwqyqp.html

[R14] C 风格 for
来源：http://dali.gotoacloud.top/Article/details/gtepdchhlm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gtgvwtvfip.html

[R15] while 逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtpvhprivn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtacxhetlo.html

[R16] until 等待条件
来源：http://dali.tanke756.top/Article/details/gtlqqyjymv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtlaecdwbh.html

[R17] 数组定义与取值
来源：http://dali.tianlin.xyz/Article/details/gtohafmneg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yanxiufei.cn/Article/details/gtorgyetmr.html

[R18] 遍历数组
来源：http://dali.ybcxt.top/Article/details/gtxqsgosxd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xinyue.icu/Article/details/gtvlgfbydw.html

[R19] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gtlriuprlw.html

echo "${#arr[@]}"
来源：http://dali.wangdashe.top/Article/details/gtfpixtqxh.html

[R20] 关联数组（字典）
来源：http://dali.tanke756.top/Article/details/gtyzxjmtri.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj202588.top/Article/details/gtlgozywts.html

[R21] 字符串长度
来源：http://dali.zycfv.cn/Article/details/gtcfjmlrln.html

echo "${#s}"
来源：http://dali.yj20258.top/Article/details/gtauateoqs.html

[R22] 截取子串
来源：http://dali.quarkkingdee.top/Article/details/gtdhuetmog.html

echo "${s:0:5}"
来源：http://dali.iojbl.cn/Article/details/gtsmnneqvq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gtklrunqrj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gtlflisrrd.html

[R24] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamdsrgyw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.9152youxi.cn/Article/details/gthdadoiig.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenlongwang.top/Article/details/gtlhyrngxa.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.redwolf501.top/Article/details/gtdypqpwiy.html

[R26] 命令替换
来源：http://dali.nanxinkj.top/Article/details/gtzbhjlmvx.html

now=$(date +%F); echo "$now"
来源：http://dali.sufxvd.cn/Article/details/gtbbjzpbuq.html

[R27] 算术展开
来源：http://dali.yj202588.top/Article/details/gtfejcryip.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gtrtgevruq.html

[R28] 浮点运算
来源：http://dali.zdqjudy.top/Article/details/gtrtvhkdza.html

echo "scale=2; 10/3" | bc
来源：http://dali.guowangkeji.top/Article/details/gtrggolvbr.html

[R29] 定义函数
来源：http://dali.0kj1m.cn/Article/details/gtrvwxyncs.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gtlkgpovfm.html

[R30] 函数返回状态码
来源：http://dali.hongshengwenyu.top/Article/details/gthatmxbxk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.316326.xyz/Article/details/gtvvoycwrq.html

[R31] 局部变量
来源：http://dali.wangdashe.top/Article/details/gtlrttfcxr.html

f() { local x=1; echo "$x"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjpcbmkas.html

[R32] 参数个数校验
来源：http://dali.birdmap.top/Article/details/gtzilrntgk.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gtgvvojvki.html

[R33] 捕获错误并提示行号
来源：http://dali.xziqi.cn/Article/details/gtqrjrgxqh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqhpylqk.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gtiwgstras.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtfuwtoyfi.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gtaqczioek.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xylfe.cn/Article/details/gtfzjtqqrv.html

[R36] 并发执行多个任务
来源：http://dali.jianghu66.top/Article/details/gtozeipwww.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gaohongyu789.top/Article/details/gtjeglujyx.html

[R37] 把输出赋给变量
来源：http://dali.sxryk.cn/Article/details/gtyhokuodu.html

files=$(ls -1)
来源：http://dali.yueranfly.top/Article/details/gtvzgaxltz.html

[R38] 管道串联
来源：http://dali.shzxlz.cn/Article/details/gtsugghigc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinqigfzy.top/Article/details/gtwjjyfmez.html

[R39] 重定向标准输出与错误
来源：http://dali.snrcjt.cn/Article/details/gtkqzhocsc.html

cmd > out.log 2>&1
来源：http://dali.ydzc1.top/Article/details/gtmcifxfbg.html

[R40] 追加写日志
来源：http://dali.haohaochexian.top/Article/details/gtrdqvcdki.html

echo "log" >> out.log
来源：http://dali.cheryme.top/Article/details/gtqouwoulo.html

[R41] 丢弃输出
来源：http://dali.yueranfly.top/Article/details/gthsewnexu.html

cmd >/dev/null 2>&1
来源：http://dali.xinyue.icu/Article/details/gttkdstsaa.html

[R42] 输入重定向
来源：http://dali.wangshuangyany.cn/Article/details/gtitlikryn.html

wc -l < a.txt
来源：http://dali.daxiang520.top/Article/details/gtqnjgglkj.html

[R43] 按名字查找文件
来源：http://dali.ydzc1.top/Article/details/gtjtgaoqva.html

find . -name "*.log" -type f
来源：http://dali.fzhhl.top/Article/details/gtmvjmoaxq.html

[R44] 按修改时间查找
来源：http://dali.jqgufenzy.top/Article/details/gtodqvputw.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiolobovr.html

[R45] 批量删除
来源：http://dali.shanyushiyangtech.top/Article/details/gtloakhgqd.html

find . -name "*.tmp" -delete
来源：http://dali.zycfv.cn/Article/details/gtwnktkkay.html

[R46] 递归替换文件内容
来源：http://dali.chenzaomai.com/Article/details/gtgmteexbw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gtuumsvcdx.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcsxhkxq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtfrpdxlnt.html

[R48] awk 取指定列
来源：http://dali.sysykeji.top/Article/details/gtkomfstgq.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtivteapwf.html

[R49] awk 带条件
来源：http://dali.yangfankeji.com/Article/details/gtdolrpbii.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gtmclxkeut.html

[R50] awk 求和
来源：http://dali.ppjwa.cn/Article/details/gtihkhxctf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtoymdhzzj.html

[R51] 排序去重取前几
来源：http://dali.ehwqpu.com/Article/details/gtptxtrlsh.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhongyouzk.top/Article/details/gtpsxowdjb.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gtnpsgnunl.html

wc -l a.txt
来源：http://dali.yuxming.cn/Article/details/gtrfcncrsc.html

[R53] 查看文件头与实时尾
来源：http://dali.yanxiufei.cn/Article/details/gtwevtsdlg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gtuvoofugd.html

[R54] 比较两个文件
来源：http://dali.cheryme.top/Article/details/gtikpzszmz.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gtdvocswnt.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gtxdbbxhju.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhlnsklv.html

[R56] 远程拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtyrcofxjv.html

scp file user@host:/path/
来源：http://dali.316326.xyz/Article/details/gtqsnsabol.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gtavlyvkaf.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gtjpxezbew.html

[R58] 下载文件
来源：http://dali.hammf.cn/Article/details/gtidrfwtpw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.mhx1999.top/Article/details/gtjdpwideo.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtcasxrzbb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigfzy.top/Article/details/gtgcemyecd.html

[R60] 只看 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtccofxzsb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daria6918.cn/Article/details/gtuuyvncnd.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gtikjckqxu.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gtsbdsmeav.html

[R62] 找最占空间的文件
来源：http://dali.jianghu66.top/Article/details/gtsenotshk.html

du -ah . | sort -rh | head -10
来源：http://dali.nwbrower.top/Article/details/gtvnzqpgca.html

[R63] 内存与进程
来源：http://dali.tanke756.top/Article/details/gttqprkftb.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gtgrkdlabv.html

[R64] 结束进程
来源：http://dali.9152youxi.cn/Article/details/gtywkskwnq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gtvxlwctbg.html

[R65] 查看端口占用
来源：http://dali.tianlin.xyz/Article/details/gttpgtptvc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tanke756.top/Article/details/gtrgsigwmp.html

[R66] 定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttllehqll.html

crontab -e;  crontab -l
来源：http://dali.yangfankeji.com/Article/details/gtjnqjtcmz.html

[R67] 生成随机十六进制串
来源：http://dali.wangshuangyany.cn/Article/details/gtzritsyke.html

openssl rand -hex 16
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupyiyhhz.html

[R68] 计算文件校验值
来源：http://dali.yj20258.top/Article/details/gtgotbtklh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtrfuabjys.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gtpcbrgyjm.html

head -c 16 /dev/urandom | base64
来源：http://dali.feifeiyinyue.top/Article/details/gtpktlyvgb.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gtpmhdwbhe.html

date +%s;  date -d @1700000000
来源：http://dali.kuanghao11.cn/Article/details/gtdeuumjdh.html

[R71] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtwlueybkz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangkeji.top/Article/details/gturisnzmi.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gtbpmuceuu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtegmrehry.html

[R73] 分割大日志
来源：http://dali.guannengcc.top/Article/details/gtahytsuai.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gtmhvdftal.html

[R74] 批量重命名
来源：http://dali.shuidangran.top/Article/details/gttjezmqee.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.316326.xyz/Article/details/gtabfymzdw.html

[R75] 导出环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtglvbqarf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhoulong.xyz/Article/details/gtvzfargxv.html

[R76] 使用临时文件
来源：http://dali.fengsongda.top/Article/details/gtgpgxvveh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gttstrxhbp.html

[R77] 读取用户输入
来源：http://dali.hywenlv.cn/Article/details/gtrvqbnkdi.html

read -rp "请输入: " ans
来源：http://dali.xuanzx.com/Article/details/gtjiaqeste.html

[R78] 交互式菜单
来源：http://dali.xuetiantiany.cn/Article/details/gtysrjdchd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gtshfkbkyd.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gtxeinvrlg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.svipenyu.cn/Article/details/gtylrbiizn.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gtbvsiymwt.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gtjknxbpfk.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtfjbwqefn.html

S. C / C++ 专题
来源：http://dali.yuxming.cn/Article/details/gtifwjegus.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtarkjixtx.html

[S01] C：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtwrrojbqw.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gtmljumkfh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxinkj.top/Article/details/gtttuabaen.html

[S02] C：变量与格式化输出
来源：http://dali.hnqzz.top/Article/details/gtwjmweaoa.html

int a = 10; printf("%d\n", a);
来源：http://dali.nanxinkj.top/Article/details/gtruownsuv.html

[S03] C：读入整数
来源：http://dali.yj202588.top/Article/details/gtxmkugtui.html

int x; scanf("%d", &x);
来源：http://dali.gogol.net.cn/Article/details/gtageizbnj.html

[S04] C：字符串复制
来源：http://dali.hnxiangtu.top/Article/details/gtfnwalznc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtznzwxrcf.html

[S05] C：字符串长度
来源：http://dali.sweek.top/Article/details/gtjakpfsvs.html

strlen(s)
来源：http://dali.andypj.xyz/Article/details/gtpbepraqy.html

[S06] C：字符串比较
来源：http://dali.sysykeji.top/Article/details/gtcdbzvpoc.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gtckwshfbt.html

[S07] C：数组遍历求和
来源：http://dali.meibo888.top/Article/details/gtdqqsnhna.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ydzc1.top/Article/details/gtpnabetrw.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gtnnkumgcx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuanzx.com/Article/details/gtekqgmkul.html

[S09] C：结构体定义与初始化
来源：http://dali.yangfankeji.com/Article/details/gtwzzzrepi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nwbrower.top/Article/details/gtyqizkevg.html

[S10] C：指针与解引用
来源：http://dali.aizwys.cn/Article/details/gtmfinfspw.html

int *p = &a;  *p = 5;
来源：http://dali.vqdsnc.cn/Article/details/gtstatiojz.html

[S11] C：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtnnmobuvs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shuidangran.top/Article/details/gtfurdbjaw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwumvnmtu.html

fclose(f);
来源：http://dali.yonumen.top/Article/details/gtyngzwlzu.html

[S12] C：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtunokoqmm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gtjkiomcoz.html

[S13] C：宏定义
来源：http://dali.hfpthk.cn/Article/details/gttcvluaoa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gtrjnrcmyi.html

[S14] C：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtmrkjholj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gtsswqculv.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtbdbxjahf.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gtinyepcea.html

[S16] C：位操作置位
来源：http://dali.ybcxt.top/Article/details/gtdxxgqltv.html

x |= (1 << 3);
来源：http://dali.ppjwa.cn/Article/details/gtvxhmcqkq.html

[S17] C：安全拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtwjlekygn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.havefunace.top/Article/details/gtjnbzkcdf.html

[S18] C：命令行参数
来源：http://dali.fzhhl.top/Article/details/gtqgbsvewj.html

int main(int argc, char **argv)
来源：http://dali.jqgfzy.top/Article/details/gtptdcbkza.html

[S19] C：快速排序
来源：http://dali.smart0.xyz/Article/details/gtweznxysf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtcnzldabl.html

[S20] C：二分查找
来源：http://dali.shuidangran.top/Article/details/gtkjlxtxld.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gtwlpqgvcc.html

[S21] C：字符类别判断
来源：http://dali.hfpthk.cn/Article/details/gtlpiyvfel.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hywenlv.cn/Article/details/gtaexuvxxw.html

[S22] C：字符串转数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjfdstaq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yonumen.top/Article/details/gtgjfajdns.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gtmvtvtbmh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.birdmap.top/Article/details/gtdaqvorhc.html

[S24] C：获取本地时间
来源：http://dali.hysaishi.cn/Article/details/gtzasqkjno.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvctpicq.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gtwavicelj.html

memcpy(dst, src, n);
来源：http://dali.dashuyun.cn/Article/details/gtflsigvkb.html

[S26] C：内存清零
来源：http://dali.yongpay.top/Article/details/gtumqogpxp.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gtijgqsnjc.html

[S27] C：定义常量
来源：http://dali.hongshengwenyu.top/Article/details/gtvqqzaybt.html

const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gtzjcbeapp.html

[S28] C：静态变量
来源：http://dali.xuetiantiany.cn/Article/details/gtldqjsgyj.html


<!-- 参考信息 -->