代发 wailian999

[Q63] 开启事务
来源：http://dali.shzxlz.cn/Article/details/gtqhnkplfw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.svipenyu.cn/Article/details/gtghqraxqf.html

[Q64] 提交事务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqxxuksc.html

COMMIT;
来源：http://dali.xylfe.cn/Article/details/gtelnrulsg.html

[Q65] 回滚事务
来源：http://dali.birdmap.top/Article/details/gtebspharu.html

ROLLBACK;
来源：http://dali.xuanzx.com/Article/details/gtldqczert.html

[Q66] 行锁查询
来源：http://dali.shuidangran.top/Article/details/gtoyrojdnh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yj20258.top/Article/details/gtxfmakekx.html

[Q67] 设置隔离级别
来源：http://dali.havefunace.top/Article/details/gtndylqgkj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.hnqzz.top/Article/details/gtdvwekfoq.html

[Q68] 保存点
来源：http://dali.ybcxt.top/Article/details/gtmkmlbkri.html

SAVEPOINT sp1;
来源：http://dali.meibo888.top/Article/details/gtunmsuaro.html

ROLLBACK TO sp1;
来源：http://dali.jiagoushi.top/Article/details/gtfwwtmvvh.html

[Q69] 查看执行计划
来源：http://dali.ybcxt.top/Article/details/gtgwdkiswa.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.xinyue.icu/Article/details/gtzykqqbdv.html

[Q70] 更新统计信息
来源：http://dali.zdqjudy.top/Article/details/gtskcwbchk.html

ANALYZE TABLE users;
来源：http://dali.yonumen.top/Article/details/gtoatajuxp.html

[Q71] 查看建表语句
来源：http://dali.shuidangran.top/Article/details/gtdukabrig.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yvedp.cn/Article/details/gtxcwjzshh.html

[Q72] 查看索引
来源：http://dali.zhengqikj.top/Article/details/gtarfbgles.html

SHOW INDEX FROM users;
来源：http://dali.cucudq.cn/Article/details/gttaamoeuv.html

[Q73] 查看表状态
来源：http://dali.zhoulong.xyz/Article/details/gtbywjjegw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdspjyskv.html

[Q74] 强制使用索引
来源：http://dali.hongshengwenyu.top/Article/details/gtrnjbifyd.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.bjfxy.top/Article/details/gtwtnghcau.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtrmtmyxev.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofpskjpc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gzhubu.top/Article/details/gtvamcxlmg.html

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gtboewzkhu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gtvyzqrhni.html

[Q77] 时间加减
来源：http://dali.daria6918.cn/Article/details/gtlftyhjtn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yj202588.top/Article/details/gtgclapysw.html

[Q78] 当前时间
来源：http://dali.nwbrower.top/Article/details/gtpzomuene.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzzpabhw.html

[Q79] 字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gtdejxkpzx.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinyuanbaomall.cn/Article/details/gtblgllevd.html

[Q80] 字符串截取
来源：http://dali.chenzaomai.com/Article/details/gtirsjvyyy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxleuqph.html

[Q81] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gtkjccqrdc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.redwolf501.top/Article/details/gthehsxtva.html

[Q82] 字符长度与字节长度
来源：http://dali.guowangkeji.top/Article/details/gtkvntuzro.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtcodbmcad.html

[Q83] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtleyrhvfv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jianghu66.top/Article/details/gtoxozbulh.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gtptlpndwk.html

SELECT TRIM(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbmsgespk.html

[Q85] 数值取整
来源：http://dali.quarkkingdee.top/Article/details/gtnkrdcruz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.andypj.xyz/Article/details/gtisbfeeqp.html

[Q86] 读取 JSON 字段
来源：http://dali.ehwqpu.com/Article/details/gtckdjhggu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yongpay.top/Article/details/gtqewjgcop.html

[Q87] JSON 字段做条件
来源：http://dali.hysaishi.cn/Article/details/gtqbgbxbkq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gtcwnvbhcv.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gtxovjyxfy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhixingplan.top/Article/details/gtwekbybyg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtmeummsqh.html

[Q89] 判断表是否存在
来源：http://dali.ivvv.top/Article/details/gtmquvjsmf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zycfv.cn/Article/details/gtobcwnfgu.html

[Q90] 生成序号列
来源：http://dali.shangyingyoupin.top/Article/details/gtfixgjdhy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daria6918.cn/Article/details/gtxshukfpu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtjgxyikqv.html

R. Bash 专题
来源：http://dali.hnxiangtu.top/Article/details/gtevmprglc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gttmbjqmwp.html

[R01] shebang 与严格模式
来源：http://dali.birdmap.top/Article/details/gtgyyruaeh.html

#!/usr/bin/env bash
来源：http://dali.aizwys.cn/Article/details/gtayrqhplh.html

set -euo pipefail
来源：http://dali.iojbl.cn/Article/details/gttylmljkj.html

[R02] 变量赋值与使用
来源：http://dali.jinqigfzy.top/Article/details/gtvpzgfwym.html

name="Tom"; echo "$name"
来源：http://dali.sysykeji.top/Article/details/gtqxyhpaus.html

[R03] 只读变量
来源：http://dali.guowangkeji.top/Article/details/gtzwuybryh.html

readonly PI=3.14
来源：http://dali.quarkkingdee.top/Article/details/gtqqzwptnr.html

[R04] 位置参数
来源：http://dali.bjfxy.top/Article/details/gturkbwofp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.cucudq.cn/Article/details/gtescrllco.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gtwoaeoyda.html

name="${1:-default}"
来源：http://dali.jiagoushi.top/Article/details/gtcszgjvab.html

[R06] 判断命令是否存在
来源：http://dali.ehwqpu.com/Article/details/gtfgirqglu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.sxryk.cn/Article/details/gtdykicdlr.html

[R07] if 判断文件
来源：http://dali.yuanzhike.top/Article/details/gtkeaaxzzj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gtbcuoqbkg.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gtirsndeui.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yueranfly.top/Article/details/gtpmrvohhl.html

[R09] 字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtevpwnhki.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.sxryk.cn/Article/details/gtfqzgnssp.html

[R10] 正则匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtseqypmfn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xylfe.cn/Article/details/gtymumesfr.html

[R11] case 多分支
来源：http://dali.aibaodan.cn/Article/details/gtyegoceud.html

case "$1" in
来源：http://dali.snrcjt.cn/Article/details/gtvlyzvobm.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgzihjvc.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftqdoeqp.html

*)     echo "未知命令" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtisvlyyvj.html

esac
来源：http://dali.cucudq.cn/Article/details/gthfviklkh.html

[R12] for 遍历文件
来源：http://dali.zhengqikj.top/Article/details/gtvnenhvzx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hywenlv.cn/Article/details/gtawwzjpxz.html

[R13] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gtfgoimvtx.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gtvjgsoyqe.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gthdfzyemr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtsljcbeya.html

[R15] while 逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzutowaa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.c1oappe.top/Article/details/gtbzltlfzb.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gtwraqseuc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtofttonjp.html

[R17] 数组定义与取值
来源：http://dali.ivvv.top/Article/details/gtkvbijhej.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.daria6918.cn/Article/details/gtvfxnzjse.html

[R18] 遍历数组
来源：http://dali.ydzc1.top/Article/details/gtcgmzgyqu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jyoumei.cn/Article/details/gtxeryafsn.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtcdxutili.html

echo "${#arr[@]}"
来源：http://dali.jlsjyb.cn/Article/details/gtsmnogjet.html

[R20] 关联数组（字典）
来源：http://dali.yj202588.top/Article/details/gtjmgexwda.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ppjwa.cn/Article/details/gtnazljkqb.html

[R21] 字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqmnnpif.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gtvfrulvqk.html

[R22] 截取子串
来源：http://dali.tian-w.cn/Article/details/gtegvhuwjx.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gtaryermqb.html

[R23] 字符串替换
来源：http://dali.cdnleiting.top/Article/details/gttisgfbfy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guannengcc.top/Article/details/gtzjvrnddm.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtlygdeesh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gtnangbnco.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuanzhike.top/Article/details/gtjbsladdr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.sufxvd.cn/Article/details/gttxswgujq.html

[R26] 命令替换
来源：http://dali.xuanzx.com/Article/details/gthwmbymhd.html

now=$(date +%F); echo "$now"
来源：http://dali.jyoumei.cn/Article/details/gtcmfsiaao.html

[R27] 算术展开
来源：http://dali.cheryme.top/Article/details/gtlvcmpjra.html

echo $((1 + 2 * 3))
来源：http://dali.jianghu66.top/Article/details/gtyyvqmmbj.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gthihhxbna.html

echo "scale=2; 10/3" | bc
来源：http://dali.jianghu66.top/Article/details/gtxnxgmdpi.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtrawoajgr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yueranfly.top/Article/details/gtlbhpbrei.html

[R30] 函数返回状态码
来源：http://dali.fengsongda.top/Article/details/gtuukwpdju.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dianchejie.cn/Article/details/gtjpjameds.html

[R31] 局部变量
来源：http://dali.hywenlv.cn/Article/details/gtqhsbbbyn.html

f() { local x=1; echo "$x"; }
来源：http://dali.sxryk.cn/Article/details/gtfxomepnm.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gttwwsnejr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtlybxfsnz.html

[R33] 捕获错误并提示行号
来源：http://dali.sxryk.cn/Article/details/gtvrqeqjww.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinqigfzy.top/Article/details/gteggciold.html

[R34] 退出时清理
来源：http://dali.yuanzhike.top/Article/details/gtglqlevas.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtwyelqioe.html

[R35] 后台执行并等待
来源：http://dali.jinqigfzy.top/Article/details/gtfbzmidox.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuxming.cn/Article/details/gtkltyeplp.html

[R36] 并发执行多个任务
来源：http://dali.birdmap.top/Article/details/gtwekvzktv.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gtxsqbqrbl.html

[R37] 把输出赋给变量
来源：http://dali.ybcxt.top/Article/details/gtxdntvjcq.html

files=$(ls -1)
来源：http://dali.cqqwz.cn/Article/details/gtmgkxztgt.html

[R38] 管道串联
来源：http://dali.hnxiangtu.top/Article/details/gtdmolrqhr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gtxasuhxfa.html

[R39] 重定向标准输出与错误
来源：http://dali.nwbrower.top/Article/details/gtqdkizftz.html

cmd > out.log 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtjqycrxah.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gtljglqnte.html

echo "log" >> out.log
来源：http://dali.sysykeji.top/Article/details/gtgechwgrb.html

[R41] 丢弃输出
来源：http://dali.ydzc1.top/Article/details/gtogykijzv.html

cmd >/dev/null 2>&1
来源：http://dali.yj20258888.top/Article/details/gtkoavoezy.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gtfeovupdh.html

wc -l < a.txt
来源：http://dali.yuanzhike.top/Article/details/gtolftnxgg.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepumakrr.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gtjerdxgcn.html

[R44] 按修改时间查找
来源：http://dali.zhongyouzk.top/Article/details/gtfozoenfo.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gtwysgeutn.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gtxdwlzfbo.html

find . -name "*.tmp" -delete
来源：http://dali.316326.xyz/Article/details/gtzvoqzvxl.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmylzkbj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ybcxt.top/Article/details/gtdowwucxg.html

[R47] sed 单行替换
来源：http://dali.yangfankeji.com/Article/details/gtbhkuymxl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtuxprzycu.html

[R48] awk 取指定列
来源：http://dali.hysaishi.cn/Article/details/gtkufdnboj.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtiewoheqp.html

[R49] awk 带条件
来源：http://dali.sufxvd.cn/Article/details/gtsodvsyrc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pycfn.com/Article/details/gtpoimwzxq.html

[R50] awk 求和
来源：http://dali.jqgfzy.top/Article/details/gtppexhknc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtaerjtlwi.html

[R51] 排序去重取前几
来源：http://dali.jinqigfzy.top/Article/details/gtvhdmjpmb.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gtybaqrkrw.html

[R52] 统计行数
来源：http://dali.wangshuangyany.cn/Article/details/gtjbemapwy.html

wc -l a.txt
来源：http://dali.sufxvd.cn/Article/details/gtpscpgtwc.html

[R53] 查看文件头与实时尾
来源：http://dali.tianlin.xyz/Article/details/gtzxuslyyc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jyoumei.cn/Article/details/gtdxrfefnm.html

[R54] 比较两个文件
来源：http://dali.kuanghao11.cn/Article/details/gtaswrjntg.html

diff a.txt b.txt
来源：http://dali.jinqigufen.top/Article/details/gtriohhaxi.html

[R55] 压缩与解压
来源：http://dali.chenjidiqi.icu/Article/details/gtifjelgka.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ivvv.top/Article/details/gtxgfwqqnw.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gttagxydhu.html

scp file user@host:/path/
来源：http://dali.nanxuanxn.top/Article/details/gtwijkruaf.html

[R57] 远程执行命令
来源：http://dali.dashuyun.cn/Article/details/gtbpoyxbgr.html

ssh user@host 'uptime'
来源：http://dali.ybcxt.top/Article/details/gtumicwhze.html

[R58] 下载文件
来源：http://dali.pycfn.com/Article/details/gtkhyrwlov.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jlsjyb.cn/Article/details/gteiwzrgde.html

[R59] 发 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfxnynxh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yonumen.top/Article/details/gtmibtngji.html

[R60] 只看 HTTP 状态码
来源：http://dali.ivvv.top/Article/details/gtebjotayk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gtrajujkaf.html

[R61] 磁盘占用
来源：http://dali.daxiang520.top/Article/details/gtzrmjilgy.html

df -h;  du -sh *
来源：http://dali.yuanzhike.top/Article/details/gtzkoutrcy.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gtkrkfrcoi.html

du -ah . | sort -rh | head -10
来源：http://dali.hysaishi.cn/Article/details/gtzzhijext.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gtltxzrhnp.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gtxboaryqm.html

[R64] 结束进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzufbnrim.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhvcqedp.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gtbblwyqxa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhqyawrp.html

[R66] 定时任务
来源：http://dali.yanxiufei.cn/Article/details/gtvtwsihgs.html

crontab -e;  crontab -l
来源：http://dali.nanxinkj.top/Article/details/gtrbjptvku.html

[R67] 生成随机十六进制串
来源：http://dali.kuanghao11.cn/Article/details/gtucjvwqqy.html

openssl rand -hex 16
来源：http://dali.cdnleiting.top/Article/details/gthsdzpcnq.html

[R68] 计算文件校验值
来源：http://dali.jlsjyb.cn/Article/details/gtqsnflflp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtpwdqbdwp.html

[R69] 生成随机密码
来源：http://dali.hammf.cn/Article/details/gtdamihshn.html

head -c 16 /dev/urandom | base64
来源：http://dali.dashuyun.cn/Article/details/gtjldbsruh.html

[R70] 时间戳与互转
来源：http://dali.wangshuangyany.cn/Article/details/gtmmevbwvm.html

date +%s;  date -d @1700000000
来源：http://dali.jqgufenzy.top/Article/details/gtrtqoizxe.html

[R71] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtwgsanvgc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ydzc1.top/Article/details/gtvgofzjaj.html

[R72] 等待端口就绪
来源：http://dali.9152youxi.cn/Article/details/gtkxrqhnng.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtihlhievt.html

[R73] 分割大日志
来源：http://dali.feifeiyinyue.top/Article/details/gtxyglbasw.html

split -l 1000 big.log part_
来源：http://dali.ehwqpu.com/Article/details/gtxlmebbsu.html

[R74] 批量重命名
来源：http://dali.zhengqikj.top/Article/details/gtwhurvvfs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.316326.xyz/Article/details/gtwdzgmctv.html

[R75] 导出环境变量
来源：http://dali.bjfxy.top/Article/details/gthcmjsoqv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gtlgrbhdik.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gtsurpalqp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtwwucoitb.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gtxgiimfmy.html

read -rp "请输入: " ans
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtceygigjd.html

[R78] 交互式菜单
来源：http://dali.chenzaomai.com/Article/details/gthjhdtruu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.c1oappe.top/Article/details/gtmuamdkpp.html

[R79] 解析命令行选项
来源：http://dali.ehwqpu.com/Article/details/gtwbmvybht.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gtqqkmknzf.html

[R80] 查看脚本执行耗时
来源：http://dali.nwbrower.top/Article/details/gtqfafxqbm.html

time ./run.sh
来源：http://dali.gotoacloud.top/Article/details/gtvlvceooc.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtjqyzouwz.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gtqubjpzqx.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtziykvtav.html

[S01] C：Hello World
来源：http://dali.xuanzx.com/Article/details/gtmeahvzag.html

#include <stdio.h>
来源：http://dali.jlsjyb.cn/Article/details/gtkngmvpws.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sufxvd.cn/Article/details/gtfvltoszc.html

[S02] C：变量与格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtetlcydpt.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gtfmmorvdu.html

[S03] C：读入整数
来源：http://dali.yongpay.top/Article/details/gtktsvadde.html

int x; scanf("%d", &x);
来源：http://dali.yj20258888.top/Article/details/gtsjbzmggc.html

[S04] C：字符串复制
来源：http://dali.guannengcc.top/Article/details/gtdhsfijhv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gtppyqyexo.html

[S05] C：字符串长度
来源：http://dali.cashguo.top/Article/details/gtbleowecz.html

strlen(s)
来源：http://dali.snrcjt.cn/Article/details/gtnxdsryig.html

[S06] C：字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtlpnddjqh.html

strcmp(a, b) == 0
来源：http://dali.pengpengdd.cyou/Article/details/gtjisxxilu.html

[S07] C：数组遍历求和
来源：http://dali.jinqigufen.top/Article/details/gtbjzntbmr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gtgcloxiti.html

[S08] C：动态内存分配与释放
来源：http://dali.yangfankeji.com/Article/details/gtuorlubec.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cucudq.cn/Article/details/gtfoukpurw.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtclqkoyaq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hongshengwenyu.top/Article/details/gtfsryobeu.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gtmcmckudf.html

int *p = &a;  *p = 5;
来源：http://dali.wangshuangyany.cn/Article/details/gtolksnxde.html

[S11] C：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtnvclzuxp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gtfsmvdakj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gtiphmbbbx.html

fclose(f);
来源：http://dali.shuidangran.top/Article/details/gtfnzvnlny.html

[S12] C：写文件
来源：http://dali.xziqi.cn/Article/details/gtditdaelo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shuidangran.top/Article/details/gttmjdrebn.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gthhdhwtia.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gtzjejpilf.html

[S14] C：枚举
来源：http://dali.birdmap.top/Article/details/gtpzlxibmr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gtjbvkkxgu.html

[S15] C：类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gtvgvbrwxv.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gtwmmiqmhc.html

[S16] C：位操作置位
来源：http://dali.zhengqikj.top/Article/details/gtcqrvmipb.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gtlpacdezi.html

[S17] C：安全拼接字符串
来源：http://dali.fengsongda.top/Article/details/gthgtqiasm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangshuangyany.cn/Article/details/gtfrzlzysp.html

[S18] C：命令行参数
来源：http://dali.shuidangran.top/Article/details/gtrxjtnjal.html

int main(int argc, char **argv)
来源：http://dali.svipenyu.cn/Article/details/gtkpgtpzub.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gtfikzurof.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfknbhtwo.html

[S20] C：二分查找
来源：http://dali.jlsjyb.cn/Article/details/gtgzqdnufg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gtzbdprxeo.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gtyunwqixd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gtohykzuph.html

[S22] C：字符串转数字
来源：http://dali.pycfn.com/Article/details/gtztkkulab.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zycfv.cn/Article/details/gtibrzlhjo.html

[S23] C：随机数
来源：http://dali.hnqzz.top/Article/details/gtgqemfmnp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.iojbl.cn/Article/details/gtgjbjeyop.html

[S24] C：获取本地时间
来源：http://dali.tanke756.top/Article/details/gtzcaiopyk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.feifeiyinyue.top/Article/details/gtynwygpsc.html

[S25] C：内存拷贝
来源：http://dali.gogol.net.cn/Article/details/gtwzkbqcqb.html

memcpy(dst, src, n);
来源：http://dali.cashguo.top/Article/details/gtyamtesnl.html

[S26] C：内存清零
来源：http://dali.andypj.xyz/Article/details/gtutykpqhi.html

memset(a, 0, sizeof a);
来源：http://dali.kuanghao11.cn/Article/details/gtxhyndmwp.html

[S27] C：定义常量
来源：http://dali.jlsjyb.cn/Article/details/gtlmspixbh.html

const double PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gtlmtbfchy.html

[S28] C：静态变量
来源：http://dali.xuanzx.com/Article/details/gtcgnpbmok.html

static int counter = 0;
来源：http://dali.fzhhl.top/Article/details/gtoflsuqbl.html

[S29] C：变参函数
来源：http://dali.hfpthk.cn/Article/details/gtowcamons.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jianghu66.top/Article/details/gtoiuilwms.html

[S30] C：头文件保护
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzuysgiyk.html

#ifndef X_H
来源：http://dali.316326.xyz/Article/details/gtvaybiclt.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gtmwrmhepx.html

#endif
来源：http://dali.tian-w.cn/Article/details/gtepycflbp.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtuecomhkl.html

#include <iostream>
来源：http://dali.meibo888.top/Article/details/gtclsseind.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gtsznxmngm.html

[S32] C++：字符串
来源：http://dali.yuxming.cn/Article/details/gtztkkautp.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgfzy.top/Article/details/gtjhedloiq.html


<!-- 参考信息 -->