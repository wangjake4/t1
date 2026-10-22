代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yonumen.top/Article/details/gtigwuxmko.html

[Q60] 取上一行 / 下一行
来源：http://dali.guannengcc.top/Article/details/gtddratwdq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.316326.xyz/Article/details/gtzkszipdg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtogdachua.html

[Q61] 移动平均
来源：http://dali.cqqwz.cn/Article/details/gtfqulpaki.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtfhhadwbv.html

[Q62] 分组占比
来源：http://dali.bjfxy.top/Article/details/gtdantgyvh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.nanxuanxn.top/Article/details/gtemwmaqys.html

[Q63] 开启事务
来源：http://dali.xylfe.cn/Article/details/gtpyzplocw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangshuangyany.cn/Article/details/gtjmwktebc.html

[Q64] 提交事务
来源：http://dali.sxryk.cn/Article/details/gtfkhzyspk.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gtdzwecllu.html

[Q65] 回滚事务
来源：http://dali.jiagoushi.top/Article/details/gthqnjjbtl.html

ROLLBACK;
来源：http://dali.xuetiantiany.cn/Article/details/gtqmrockvs.html

[Q66] 行锁查询
来源：http://dali.yuanzhike.top/Article/details/gtfganmals.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yanxiufei.cn/Article/details/gthateimik.html

[Q67] 设置隔离级别
来源：http://dali.daxiang520.top/Article/details/gteuyreiyb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cdnleiting.top/Article/details/gtqaomphli.html

[Q68] 保存点
来源：http://dali.ybcxt.top/Article/details/gtyfwcceqk.html

SAVEPOINT sp1;
来源：http://dali.hywenlv.cn/Article/details/gtfgrmrnuv.html

ROLLBACK TO sp1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtznbesrnw.html

[Q69] 查看执行计划
来源：http://dali.yuanzhike.top/Article/details/gtvislwcsu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.birdmap.top/Article/details/gtbegzvjig.html

[Q70] 更新统计信息
来源：http://dali.snrcjt.cn/Article/details/gtfbjnlqkh.html

ANALYZE TABLE users;
来源：http://dali.ppjwa.cn/Article/details/gtzesxgjdy.html

[Q71] 查看建表语句
来源：http://dali.9152youxi.cn/Article/details/gtditvubcw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhiqligj.html

[Q72] 查看索引
来源：http://dali.yj20258888.top/Article/details/gtwgpvbwlp.html

SHOW INDEX FROM users;
来源：http://dali.aizwys.cn/Article/details/gtgrvzbywn.html

[Q73] 查看表状态
来源：http://dali.vqdsnc.cn/Article/details/gtmybpmuis.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daria6918.cn/Article/details/gtzaeedeoz.html

[Q74] 强制使用索引
来源：http://dali.gaohongyu789.top/Article/details/gtflaiwmrm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.aizwys.cn/Article/details/gtyzrhveig.html

[Q75] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gtksohzkri.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtjqwvmelj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ydzc1.top/Article/details/gtnyvfstxr.html

[Q76] 按天统计
来源：http://dali.cheryme.top/Article/details/gtrdzycwgw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.9152youxi.cn/Article/details/gtyqvcnaqu.html

[Q77] 时间加减
来源：http://dali.guowangkeji.top/Article/details/gtdtxwrzuo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zdqjudy.top/Article/details/gtjtbatjwe.html

[Q78] 当前时间
来源：http://dali.shzxlz.cn/Article/details/gtephheqkg.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.sufxvd.cn/Article/details/gtfkrprmzw.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhatagep.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zdqjudy.top/Article/details/gthivferbd.html

[Q80] 字符串截取
来源：http://dali.andypj.xyz/Article/details/gtadvmuqwn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtfeydpwlt.html

[Q81] 字符串替换
来源：http://dali.chenzaomai.com/Article/details/gtdevykpuk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtqnipylzs.html

[Q82] 字符长度与字节长度
来源：http://dali.zycfv.cn/Article/details/gtfnkjicbu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtzhfkvphi.html

[Q83] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gthrgmndja.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtenriayoq.html

[Q84] 去除首尾空格
来源：http://dali.hnxiangtu.top/Article/details/gtknvyhyad.html

SELECT TRIM(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtkvgwvrob.html

[Q85] 数值取整
来源：http://dali.ivvv.top/Article/details/gtagjkjlbt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigufen.top/Article/details/gtynrcksqy.html

[Q86] 读取 JSON 字段
来源：http://dali.meibo888.top/Article/details/gtabbfknkx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.guowangkeji.top/Article/details/gtiqhkowsw.html

[Q87] JSON 字段做条件
来源：http://dali.chenzaomai.com/Article/details/gtymdkwqko.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gotoacloud.top/Article/details/gtczxeejsq.html

[Q88] 行转列（条件聚合）
来源：http://dali.haohaochexian.top/Article/details/gtkkhmwncb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sxryk.cn/Article/details/gtneengpyg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gttudfbboz.html

[Q89] 判断表是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtokwivajv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ehwqpu.com/Article/details/gtsglozffy.html

[Q90] 生成序号列
来源：http://dali.gaohongyu789.top/Article/details/gtanqlksit.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xuanzx.com/Article/details/gtoyvmhxaa.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtmrxehxyn.html

R. Bash 专题
来源：http://dali.pycfn.com/Article/details/gtvnxddwjj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtjpvcpmwx.html

[R01] shebang 与严格模式
来源：http://dali.xziqi.cn/Article/details/gtpznitxci.html

#!/usr/bin/env bash
来源：http://dali.andypj.xyz/Article/details/gtkhfcepfm.html

set -euo pipefail
来源：http://dali.wangdashe.top/Article/details/gtehzwtufl.html

[R02] 变量赋值与使用
来源：http://dali.cheryme.top/Article/details/gtkcthtrxz.html

name="Tom"; echo "$name"
来源：http://dali.yuxming.cn/Article/details/gtrxgprbfc.html

[R03] 只读变量
来源：http://dali.wangshuangyany.cn/Article/details/gtjzguxlwr.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gtjwwixhoj.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gtwcvlilks.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgxioxnf.html

[R05] 参数默认值
来源：http://dali.tian-w.cn/Article/details/gtwmkwbmcj.html

name="${1:-default}"
来源：http://dali.dianchejie.cn/Article/details/gtmmvdnpcp.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gtvxtvvyoh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.vqdsnc.cn/Article/details/gtxlnlzhlx.html

[R07] if 判断文件
来源：http://dali.shangyingyoupin.top/Article/details/gtozjdeild.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dashuyun.cn/Article/details/gtwwddygsx.html

[R08] 数值比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfjooywuk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigfzy.top/Article/details/gteziixjoa.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gtirxtvuvg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.0kj1m.cn/Article/details/gtdioowpzq.html

[R10] 正则匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagpyotzf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfvhdcwh.html

[R11] case 多分支
来源：http://dali.aizwys.cn/Article/details/gtgwstcsfa.html

case "$1" in
来源：http://dali.guowangkeji.top/Article/details/gthalwhbnx.html

start) echo "启动" ;;
来源：http://dali.hysaishi.cn/Article/details/gtwsopmodf.html

stop)  echo "停止" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtenzeixnu.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gttvbnmnfp.html

esac
来源：http://dali.zhongyouzk.top/Article/details/gtebgzoxgm.html

[R12] for 遍历文件
来源：http://dali.gotoacloud.top/Article/details/gtumlsfuei.html

for f in *.txt; do echo "$f"; done
来源：http://dali.havefunace.top/Article/details/gtbcqlzjci.html

[R13] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gtgyhdibom.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gtihdtghsi.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gtkftrrlju.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gtshjiokod.html

[R15] while 逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtofmoctuc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangdashe.top/Article/details/gtsptnvitb.html

[R16] until 等待条件
来源：http://dali.guannengcc.top/Article/details/gtivzjdsch.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtmdqwigtu.html

[R17] 数组定义与取值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhzavkjv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gtbienpvrh.html

[R18] 遍历数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwlicvrb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.wangshuangyany.cn/Article/details/gttorggrfa.html

[R19] 数组长度
来源：http://dali.birdmap.top/Article/details/gtdojbvzam.html

echo "${#arr[@]}"
来源：http://dali.jiagoushi.top/Article/details/gtldqwwlkn.html

[R20] 关联数组（字典）
来源：http://dali.shuidangran.top/Article/details/gtnhhgluib.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gtsnpudxwr.html

[R21] 字符串长度
来源：http://dali.aizwys.cn/Article/details/gtsopymqal.html

echo "${#s}"
来源：http://dali.zhengqikj.top/Article/details/gtvlkhjhiw.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtadmholqm.html

echo "${s:0:5}"
来源：http://dali.gaohongyu789.top/Article/details/gthbaoiwch.html

[R23] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gtkegiarki.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.kuanghao11.cn/Article/details/gtvmedgrdg.html

[R24] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gtmspvlgpt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daxiang520.top/Article/details/gtnkragbgl.html

[R25] 去后缀 / 去前缀
来源：http://dali.316326.xyz/Article/details/gttewhbkdr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hfpthk.cn/Article/details/gtewjkqarf.html

[R26] 命令替换
来源：http://dali.nanxuanxn.top/Article/details/gtbiaueqfc.html

now=$(date +%F); echo "$now"
来源：http://dali.chenzaomai.com/Article/details/gtchkpjzeu.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gtbejoohaf.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtftbidsei.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbxqswrl.html

echo "scale=2; 10/3" | bc
来源：http://dali.fzhhl.top/Article/details/gtemzjgfdr.html

[R29] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gtfkubmiic.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aizwys.cn/Article/details/gtyskmzhpz.html

[R30] 函数返回状态码
来源：http://dali.xuetiantiany.cn/Article/details/gtuqzuiqln.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gtemgywpoe.html

[R31] 局部变量
来源：http://dali.ybcxt.top/Article/details/gtkopklgnn.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gtcrupoarw.html

[R32] 参数个数校验
来源：http://dali.cheryme.top/Article/details/gtobcmcoka.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gtpwptgxrg.html

[R33] 捕获错误并提示行号
来源：http://dali.hongshengwenyu.top/Article/details/gtwahfamlx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258.top/Article/details/gtrceuffnl.html

[R34] 退出时清理
来源：http://dali.chenzaomai.com/Article/details/gtlhbfjnwv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtygrmhpgd.html

[R35] 后台执行并等待
来源：http://dali.svipenyu.cn/Article/details/gtrirjqguv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigfzy.top/Article/details/gtnetssabp.html

[R36] 并发执行多个任务
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhdkaskr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.feifeiyinyue.top/Article/details/gtrrbamrci.html

[R37] 把输出赋给变量
来源：http://dali.havefunace.top/Article/details/gtodshpmeq.html

files=$(ls -1)
来源：http://dali.zhongyouzk.top/Article/details/gtlfqwaecy.html

[R38] 管道串联
来源：http://dali.zhoulong.xyz/Article/details/gtmyhuecdu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.0kj1m.cn/Article/details/gtvulzkopq.html

[R39] 重定向标准输出与错误
来源：http://dali.fzhhl.top/Article/details/gtkshikptm.html

cmd > out.log 2>&1
来源：http://dali.pycfn.com/Article/details/gtjohevude.html

[R40] 追加写日志
来源：http://dali.ivvv.top/Article/details/gtytvpbulz.html

echo "log" >> out.log
来源：http://dali.hammf.cn/Article/details/gtdvvvcavf.html

[R41] 丢弃输出
来源：http://dali.zdqjudy.top/Article/details/gtijsmhpcm.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gtfuxlpamk.html

[R42] 输入重定向
来源：http://dali.hfpthk.cn/Article/details/gtqibqcsig.html

wc -l < a.txt
来源：http://dali.shuidangran.top/Article/details/gtlzvlwiuu.html

[R43] 按名字查找文件
来源：http://dali.jinqigfzy.top/Article/details/gtjegyxgpq.html

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gtqefcgwxj.html

[R44] 按修改时间查找
来源：http://dali.yanxiufei.cn/Article/details/gtplmbbswl.html

find . -mtime -7 -type f
来源：http://dali.ppjwa.cn/Article/details/gtadqelshp.html

[R45] 批量删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvpwdfvve.html

find . -name "*.tmp" -delete
来源：http://dali.zhixingplan.top/Article/details/gthicxfjip.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gtllzodhgd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gtccpzfkhy.html

[R47] sed 单行替换
来源：http://dali.xuanzx.com/Article/details/gtmrzgfayh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtbkzltbdk.html

[R48] awk 取指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxmtduiy.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj202588.top/Article/details/gtvdkqxjjr.html

[R49] awk 带条件
来源：http://dali.ehwqpu.com/Article/details/gtuwzkdtnf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gtmpgqauvz.html

[R50] awk 求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gthatnpgoq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtozwkswwi.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gtcomcldpf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hysaishi.cn/Article/details/gtnpiphfxq.html

[R52] 统计行数
来源：http://dali.daria6918.cn/Article/details/gtfdnbfmkg.html

wc -l a.txt
来源：http://dali.yj20258.top/Article/details/gtlzqaawfb.html

[R53] 查看文件头与实时尾
来源：http://dali.hnxiangtu.top/Article/details/gtsuorrgnp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xziqi.cn/Article/details/gtsjspazgg.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gtnmdaffen.html

diff a.txt b.txt
来源：http://dali.redwolf501.top/Article/details/gtdtafxhrb.html

[R55] 压缩与解压
来源：http://dali.sysykeji.top/Article/details/gtkypbibih.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yueranfly.top/Article/details/gtvxlesmlz.html

[R56] 远程拷贝
来源：http://dali.gotoacloud.top/Article/details/gtbpzwhtem.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gtqvtgwfwq.html

[R57] 远程执行命令
来源：http://dali.bjfxy.top/Article/details/gtiqczbtqr.html

ssh user@host 'uptime'
来源：http://dali.guowangkeji.top/Article/details/gtzluvvnlb.html

[R58] 下载文件
来源：http://dali.wangdashe.top/Article/details/gttjxchweg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cucudq.cn/Article/details/gtpqoukwza.html

[R59] 发 POST JSON
来源：http://dali.hnxiangtu.top/Article/details/gtyxidkrzm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aizwys.cn/Article/details/gtinshfvoh.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwdfouee.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangshuangyany.cn/Article/details/gthuucvojh.html

[R61] 磁盘占用
来源：http://dali.nwbrower.top/Article/details/gtznaloszo.html

df -h;  du -sh *
来源：http://dali.yanxiufei.cn/Article/details/gtwzniroxv.html

[R62] 找最占空间的文件
来源：http://dali.hammf.cn/Article/details/gtndnmrwtv.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gtqeytyazu.html

[R63] 内存与进程
来源：http://dali.kuanghao11.cn/Article/details/gtzyolhkcg.html

free -h;  ps aux | grep nginx
来源：http://dali.yuanzhike.top/Article/details/gtusluevtk.html

[R64] 结束进程
来源：http://dali.jyoumei.cn/Article/details/gtfnstxkra.html

kill -9 $(pgrep -f app.py)
来源：http://dali.meibo888.top/Article/details/gtpoutwwev.html

[R65] 查看端口占用
来源：http://dali.ppjwa.cn/Article/details/gtgrinicek.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zycfv.cn/Article/details/gtfhggbtzf.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gtgphsyqts.html

crontab -e;  crontab -l
来源：http://dali.ivvv.top/Article/details/gtabvvcgwe.html

[R67] 生成随机十六进制串
来源：http://dali.snrcjt.cn/Article/details/gtmmayevbf.html

openssl rand -hex 16
来源：http://dali.yuanzhike.top/Article/details/gtyqlcyirn.html

[R68] 计算文件校验值
来源：http://dali.sxryk.cn/Article/details/gtiseeuglz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnqzz.top/Article/details/gtldvxdtna.html

[R69] 生成随机密码
来源：http://dali.guowangkeji.top/Article/details/gtizohnvun.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gtpnlvswkt.html

[R70] 时间戳与互转
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagfceujk.html

date +%s;  date -d @1700000000
来源：http://dali.nwbrower.top/Article/details/gtrtbvflzd.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtcnqvhlis.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jianghu66.top/Article/details/gtcacjnbwc.html

[R72] 等待端口就绪
来源：http://dali.tianlin.xyz/Article/details/gtelcdykky.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtjgohiomv.html

[R73] 分割大日志
来源：http://dali.gaohongyu789.top/Article/details/gtsqjsytmb.html

split -l 1000 big.log part_
来源：http://dali.yongpay.top/Article/details/gtzedhklbg.html

[R74] 批量重命名
来源：http://dali.xuanzx.com/Article/details/gtyjhrmqhe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtxygloiex.html

[R75] 导出环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtiyxugcnw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gtmtcfuikv.html

[R76] 使用临时文件
来源：http://dali.cucudq.cn/Article/details/gtlbukduki.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtxjpbtyne.html

[R77] 读取用户输入
来源：http://dali.shuidangran.top/Article/details/gtpfdmuwar.html

read -rp "请输入: " ans
来源：http://dali.zhengqikj.top/Article/details/gthqbidrzm.html

[R78] 交互式菜单
来源：http://dali.hnxiangtu.top/Article/details/gtwrxmrmgo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cashguo.top/Article/details/gtemqkiykt.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangtech.top/Article/details/gtyyuzmejz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuxming.cn/Article/details/gtmkgmkzhd.html

[R80] 查看脚本执行耗时
来源：http://dali.yonumen.top/Article/details/gtyhjevrei.html

time ./run.sh
来源：http://dali.xuetiantiany.cn/Article/details/gtgueyhlqw.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdteynbfz.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gthbfxhvwj.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtlujeafwd.html

[S01] C：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtdpxegwer.html

#include <stdio.h>
来源：http://dali.fengsongda.top/Article/details/gttwxspkjk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gtivucwbut.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpqektbx.html

int a = 10; printf("%d\n", a);
来源：http://dali.sufxvd.cn/Article/details/gtycrjlshy.html

[S03] C：读入整数
来源：http://dali.yuanzhike.top/Article/details/gtoijwyfzd.html

int x; scanf("%d", &x);
来源：http://dali.quarkkingdee.top/Article/details/gtnirinyvc.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gtjmtukjhx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xinyue.icu/Article/details/gtqyvcngyg.html

[S05] C：字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtxwfwsgkj.html

strlen(s)
来源：http://dali.gzhubu.top/Article/details/gtvvfcexul.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gthekxkopl.html

strcmp(a, b) == 0
来源：http://dali.hammf.cn/Article/details/gtwrjnqjhf.html

[S07] C：数组遍历求和
来源：http://dali.guowangkeji.top/Article/details/gtcqmkfgvn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xylfe.cn/Article/details/gtqoxpppab.html

[S08] C：动态内存分配与释放
来源：http://dali.dianchejie.cn/Article/details/gtauqdzdus.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenzaomai.com/Article/details/gtftraqedu.html

[S09] C：结构体定义与初始化
来源：http://dali.yvedp.cn/Article/details/gtevacegsy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shuidangran.top/Article/details/gtsigjijwj.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gtxarexqmr.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gtbjyeqgzo.html

[S11] C：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtxkkevuga.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.kuanghao11.cn/Article/details/gtakiqftkm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhixingplan.top/Article/details/gtvimmfsns.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtaylpranm.html

[S12] C：写文件
来源：http://dali.zycfv.cn/Article/details/gtcmnymhht.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gthvkunzxn.html

[S13] C：宏定义
来源：http://dali.kuanghao11.cn/Article/details/gthendzlrq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pengpengdd.cyou/Article/details/gtnaacfljq.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gtsxuncwfe.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guannengcc.top/Article/details/gtxwdermgh.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gtvjcrlbdq.html

(double) a / b
来源：http://dali.jianghu66.top/Article/details/gtjhlopwkk.html

[S16] C：位操作置位
来源：http://dali.yj202588.top/Article/details/gtxrdgqmbj.html

x |= (1 << 3);
来源：http://dali.ehwqpu.com/Article/details/gtfgehyfzo.html

[S17] C：安全拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtzzmskomc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ydzc1.top/Article/details/gtpxuzaiau.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gtadhcjqfx.html

int main(int argc, char **argv)
来源：http://dali.xylfe.cn/Article/details/gtopkxbezx.html

[S19] C：快速排序
来源：http://dali.daria6918.cn/Article/details/gtlmqxryaw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtgzgsqdsn.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gtwzihejwh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtjumjmpli.html

[S21] C：字符类别判断
来源：http://dali.hfpthk.cn/Article/details/gtpueppxvt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtgifnta.html

[S22] C：字符串转数字
来源：http://dali.hnxiangtu.top/Article/details/gtsyiqrgub.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gtcqqswqdm.html

[S23] C：随机数
来源：http://dali.havefunace.top/Article/details/gtxblsnovh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigufen.top/Article/details/gtyxpxlxkq.html

[S24] C：获取本地时间
来源：http://dali.yj20258.top/Article/details/gtjbqaylue.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tanke756.top/Article/details/gtmcxdyqke.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gtdzmenbcw.html

memcpy(dst, src, n);
来源：http://dali.c1oappe.top/Article/details/gteuqluurx.html

[S26] C：内存清零
来源：http://dali.nanxinkj.top/Article/details/gtcorlthdo.html

memset(a, 0, sizeof a);
来源：http://dali.gotoacloud.top/Article/details/gtcnwdfrmp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gtnhqrfuie.html

const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtpkdonkec.html

[S28] C：静态变量
来源：http://dali.chenzaomai.com/Article/details/gtzfxfikzj.html

static int counter = 0;
来源：http://dali.yvedp.cn/Article/details/gtrmvdlghi.html

[S29] C：变参函数
来源：http://dali.yvedp.cn/Article/details/gtgajbxkno.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinghuilouyu.cn/Article/details/gtinhseknn.html

[S30] C：头文件保护
来源：http://dali.dashuyun.cn/Article/details/gttlzcovbg.html


<!-- 参考信息 -->