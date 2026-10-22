代发 wailian999

[Q63] 开启事务
来源：http://dali.jianghu66.top/Article/details/gtxetzlhzk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.chenjidiqi.icu/Article/details/gtbebdcmmv.html

[Q64] 提交事务
来源：http://dali.yueranfly.top/Article/details/gtrwueirpr.html

COMMIT;
来源：http://dali.316326.xyz/Article/details/gtjxhlqakm.html

[Q65] 回滚事务
来源：http://dali.zycfv.cn/Article/details/gtouudykar.html

ROLLBACK;
来源：http://dali.zhongyouzk.top/Article/details/gttylgltsc.html

[Q66] 行锁查询
来源：http://dali.gzhubu.top/Article/details/gtzipdycxz.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pycfn.com/Article/details/gtskuursoc.html

[Q67] 设置隔离级别
来源：http://dali.cdnleiting.top/Article/details/gtwpkbbbkf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nwbrower.top/Article/details/gtgnoxearj.html

[Q68] 保存点
来源：http://dali.zhengqikj.top/Article/details/gtkfpaccvl.html

SAVEPOINT sp1;
来源：http://dali.yj20258888.top/Article/details/gtmdzpcyue.html

ROLLBACK TO sp1;
来源：http://dali.nanxuanxn.top/Article/details/gtunmcwlaf.html

[Q69] 查看执行计划
来源：http://dali.snrcjt.cn/Article/details/gtvvsnmpgl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.quarkkingdee.top/Article/details/gtnsxqdszj.html

[Q70] 更新统计信息
来源：http://dali.quarkkingdee.top/Article/details/gtxuhejeov.html

ANALYZE TABLE users;
来源：http://dali.jinqigfzy.top/Article/details/gtqasikmgx.html

[Q71] 查看建表语句
来源：http://dali.gotoacloud.top/Article/details/gtsaghddzf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gtizxaqmfn.html

[Q72] 查看索引
来源：http://dali.bjfxy.top/Article/details/gtnceijlnj.html

SHOW INDEX FROM users;
来源：http://dali.pycfn.com/Article/details/gtwynhgblf.html

[Q73] 查看表状态
来源：http://dali.hywenlv.cn/Article/details/gtoyyrxobt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscsqckya.html

[Q74] 强制使用索引
来源：http://dali.shangyingyoupin.top/Article/details/gtxrwkmrob.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.wangdashe.top/Article/details/gtjaommmrq.html

[Q75] 日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtyazrvcpd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtphxpvfcx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ivvv.top/Article/details/gtftvhraje.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gtrautfybt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuxming.cn/Article/details/gtnydsngjw.html

[Q77] 时间加减
来源：http://dali.jinqigufen.top/Article/details/gtolnfijxn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gzhubu.top/Article/details/gtdkjcsguo.html

[Q78] 当前时间
来源：http://dali.andypj.xyz/Article/details/gtrzkzdofn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.ydzc1.top/Article/details/gtppvwmkpx.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtusphkrxi.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.haohaochexian.top/Article/details/gtjjqwamyo.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gtfydthipn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtixbspcif.html

[Q81] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gtrzyqhbxb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtgntwanqi.html

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gtdfkmbvlh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hammf.cn/Article/details/gtstjzyckw.html

[Q83] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gttpaiagok.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtyictyhxn.html

[Q84] 去除首尾空格
来源：http://dali.jinyuanbaomall.cn/Article/details/gttdxjveoq.html

SELECT TRIM(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtyurtnjyn.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwinhlgn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.bjfxy.top/Article/details/gtgzwixvkw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhixingplan.top/Article/details/gtlfbxfrtl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.tanke756.top/Article/details/gtesnrbjez.html

[Q87] JSON 字段做条件
来源：http://dali.ehwqpu.com/Article/details/gtcynicdkz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cucudq.cn/Article/details/gtyuwbjkpt.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigfzy.top/Article/details/gtlggulcbv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fengsongda.top/Article/details/gtnzzvtium.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pycfn.com/Article/details/gtxjvpilaw.html

[Q89] 判断表是否存在
来源：http://dali.c1oappe.top/Article/details/gtvwjltxui.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nwbrower.top/Article/details/gtwpvfrswm.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gtllbgrdbq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shangyingyoupin.top/Article/details/gtdliklpuu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtijxevypk.html

R. Bash 专题
来源：http://dali.cheryme.top/Article/details/gtgoldwdmx.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqsigupx.html

[R01] shebang 与严格模式
来源：http://dali.hnqzz.top/Article/details/gtwpkqvkmo.html

#!/usr/bin/env bash
来源：http://dali.yuxming.cn/Article/details/gtharmquju.html

set -euo pipefail
来源：http://dali.haohaochexian.top/Article/details/gtgogaxbju.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtqawnvyxl.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gtrtpxzfxu.html

[R03] 只读变量
来源：http://dali.cdnleiting.top/Article/details/gtswtwmfld.html

readonly PI=3.14
来源：http://dali.cdnleiting.top/Article/details/gtnowxoshd.html

[R04] 位置参数
来源：http://dali.redwolf501.top/Article/details/gtsawfbpmy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.ybcxt.top/Article/details/gtcnkhpvwl.html

[R05] 参数默认值
来源：http://dali.guannengcc.top/Article/details/gtwsnwunza.html

name="${1:-default}"
来源：http://dali.xinyue.icu/Article/details/gtnchqimqe.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtvldelixh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.haohaochexian.top/Article/details/gthavbqilk.html

[R07] if 判断文件
来源：http://dali.shuidangran.top/Article/details/gtuzikiejf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cqqwz.cn/Article/details/gtjggriqeg.html

[R08] 数值比较
来源：http://dali.chenzaomai.com/Article/details/gtrugkkqra.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtxflehloi.html

[R09] 字符串比较
来源：http://dali.cqqwz.cn/Article/details/gtydqtlhxk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gtfmzswqzq.html

[R10] 正则匹配
来源：http://dali.yueranfly.top/Article/details/gtrbejomlc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yonumen.top/Article/details/gtcgruefll.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gtvwpihaml.html

case "$1" in
来源：http://dali.nanxuanxn.top/Article/details/gtmsshgeuy.html

start) echo "启动" ;;
来源：http://dali.aizwys.cn/Article/details/gtlmkmbhvf.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtwplafxsl.html

*)     echo "未知命令" ;;
来源：http://dali.cdnleiting.top/Article/details/gtejtgstri.html

esac
来源：http://dali.jlsjyb.cn/Article/details/gtmcbqgeyy.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gtspwetkie.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pycfn.com/Article/details/gtnvliahgo.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtekndpgha.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdvogkrng.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gtylbtlmus.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.havefunace.top/Article/details/gtzbjralpb.html

[R15] while 逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtsjtrwuwy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jyoumei.cn/Article/details/gtcatnblrt.html

[R16] until 等待条件
来源：http://dali.pycfn.com/Article/details/gtrpdmuxdg.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gtplztvspk.html

[R17] 数组定义与取值
来源：http://dali.cucudq.cn/Article/details/gteaxemafx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yangfankeji.com/Article/details/gtlxfopnsf.html

[R18] 遍历数组
来源：http://dali.feifeiyinyue.top/Article/details/gtovzfqkih.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gtucmcxcnb.html

[R19] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtreigcyaw.html

echo "${#arr[@]}"
来源：http://dali.nwbrower.top/Article/details/gtwrxlbtrm.html

[R20] 关联数组（字典）
来源：http://dali.gogol.net.cn/Article/details/gtogqtxkhh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jianghu66.top/Article/details/gtzajshzeg.html

[R21] 字符串长度
来源：http://dali.fzhhl.top/Article/details/gtytlrgyak.html

echo "${#s}"
来源：http://dali.0kj1m.cn/Article/details/gtegnrgbwi.html

[R22] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gthfphopsb.html

echo "${s:0:5}"
来源：http://dali.hywenlv.cn/Article/details/gtngezcjsf.html

[R23] 字符串替换
来源：http://dali.hfpthk.cn/Article/details/gtpmvirmzh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gtaozlkbct.html

[R24] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtczoobkhh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ybcxt.top/Article/details/gtjxyqeojq.html

[R25] 去后缀 / 去前缀
来源：http://dali.nanxuanxn.top/Article/details/gtuskprxxx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nwbrower.top/Article/details/gtycgbmgca.html

[R26] 命令替换
来源：http://dali.hfpthk.cn/Article/details/gtokumtlfz.html

now=$(date +%F); echo "$now"
来源：http://dali.iojbl.cn/Article/details/gtewfiqhuj.html

[R27] 算术展开
来源：http://dali.wangshuangyany.cn/Article/details/gtyrlfpcdf.html

echo $((1 + 2 * 3))
来源：http://dali.yonumen.top/Article/details/gtjsejqtbk.html

[R28] 浮点运算
来源：http://dali.aibaodan.cn/Article/details/gtpwoqojuk.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj20258.top/Article/details/gtiazxcyxl.html

[R29] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtwahmdvmk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hysaishi.cn/Article/details/gtcjqcrddx.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwoayzpi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gtohvdlzht.html

[R31] 局部变量
来源：http://dali.pycfn.com/Article/details/gtoitqsyvt.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenzaomai.com/Article/details/gtkyiutudu.html

[R32] 参数个数校验
来源：http://dali.yonumen.top/Article/details/gtdzkmmect.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigufen.top/Article/details/gtidezhgkq.html

[R33] 捕获错误并提示行号
来源：http://dali.shzxlz.cn/Article/details/gtebzdeoza.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuetiantiany.cn/Article/details/gtzeirvprt.html

[R34] 退出时清理
来源：http://dali.hywenlv.cn/Article/details/gthbjtirpr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtviokslvq.html

[R35] 后台执行并等待
来源：http://dali.hfpthk.cn/Article/details/gtnnmdwyfc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.kuanghao11.cn/Article/details/gtvmzykymd.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtceaxggxi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.0kj1m.cn/Article/details/gthlstjazx.html

[R37] 把输出赋给变量
来源：http://dali.nanxuanxn.top/Article/details/gtczlpdraa.html

files=$(ls -1)
来源：http://dali.yuanzhike.top/Article/details/gtbxixpuua.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gtgrxoufnu.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gtlfykblje.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjcsamdy.html

cmd > out.log 2>&1
来源：http://dali.sxryk.cn/Article/details/gtpltzxbep.html

[R40] 追加写日志
来源：http://dali.sxryk.cn/Article/details/gtwslftazw.html

echo "log" >> out.log
来源：http://dali.pycfn.com/Article/details/gtdpszplkm.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gtepugnnyl.html

cmd >/dev/null 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtsyjqwkkd.html

[R42] 输入重定向
来源：http://dali.zhengqikj.top/Article/details/gtttutcedz.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtopuuzneo.html

[R43] 按名字查找文件
来源：http://dali.hongshengwenyu.top/Article/details/gtroobnfbx.html

find . -name "*.log" -type f
来源：http://dali.gzhubu.top/Article/details/gtaclcsbay.html

[R44] 按修改时间查找
来源：http://dali.jqgufenzy.top/Article/details/gteaoaprgj.html

find . -mtime -7 -type f
来源：http://dali.yanxiufei.cn/Article/details/gtwqmmtegp.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gtjpamzyfm.html

find . -name "*.tmp" -delete
来源：http://dali.yj202588.top/Article/details/gtylmxuwyb.html

[R46] 递归替换文件内容
来源：http://dali.hywenlv.cn/Article/details/gtxdexzpcy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gtzosyxlbz.html

[R47] sed 单行替换
来源：http://dali.tianlin.xyz/Article/details/gtjqfvksvj.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xylfe.cn/Article/details/gtprkhhehz.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gtralxlmqn.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtdaeildik.html

[R49] awk 带条件
来源：http://dali.kuanghao11.cn/Article/details/gthlgiixgx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.316326.xyz/Article/details/gtbajlhmqh.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gtgndqajfn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtweijmvth.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gtulgdrvbi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shuidangran.top/Article/details/gtvjjbkwdg.html

[R52] 统计行数
来源：http://dali.hysaishi.cn/Article/details/gtprzfyvzw.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtwhhilibq.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gttghtlzcb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fengsongda.top/Article/details/gtjbxonmke.html

[R54] 比较两个文件
来源：http://dali.hysaishi.cn/Article/details/gteipdoskv.html

diff a.txt b.txt
来源：http://dali.yueranfly.top/Article/details/gtezcmnopi.html

[R55] 压缩与解压
来源：http://dali.chenjidiqi.icu/Article/details/gtaqufvmdj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daria6918.cn/Article/details/gtuuxdrrzk.html

[R56] 远程拷贝
来源：http://dali.cdnleiting.top/Article/details/gtaoubzimu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gtmkvwdgcu.html

[R57] 远程执行命令
来源：http://dali.ybcxt.top/Article/details/gtavutqsdi.html

ssh user@host 'uptime'
来源：http://dali.hnxiangtu.top/Article/details/gtwewssjvt.html

[R58] 下载文件
来源：http://dali.yangfankeji.com/Article/details/gtazjvlsoj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gtqkvghdai.html

[R59] 发 POST JSON
来源：http://dali.yongpay.top/Article/details/gtfccpbssw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xziqi.cn/Article/details/gtfytlckkk.html

[R60] 只看 HTTP 状态码
来源：http://dali.aizwys.cn/Article/details/gtrupvmpgz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangdashe.top/Article/details/gtqcjubsri.html

[R61] 磁盘占用
来源：http://dali.zhiwuduotai.top/Article/details/gtczvjsuwq.html

df -h;  du -sh *
来源：http://dali.sysykeji.top/Article/details/gtettyhgzh.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtqefqqtzu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhixingplan.top/Article/details/gtelmgbena.html

[R63] 内存与进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsahjccfi.html

free -h;  ps aux | grep nginx
来源：http://dali.fengsongda.top/Article/details/gtrmyxoarz.html

[R64] 结束进程
来源：http://dali.bjfxy.top/Article/details/gtxzrduund.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jianghu66.top/Article/details/gtiuqnlxkj.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gttfvogxmz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.andypj.xyz/Article/details/gtkxmxyuvt.html

[R66] 定时任务
来源：http://dali.sweek.top/Article/details/gtfdmrblui.html

crontab -e;  crontab -l
来源：http://dali.9152youxi.cn/Article/details/gtruzhjbbn.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gtpcbvpipx.html

openssl rand -hex 16
来源：http://dali.sufxvd.cn/Article/details/gtytwyxuvt.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gtsptbunrq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sweek.top/Article/details/gtcmhkpqib.html

[R69] 生成随机密码
来源：http://dali.wangdashe.top/Article/details/gttnvynqqj.html

head -c 16 /dev/urandom | base64
来源：http://dali.yuanzhike.top/Article/details/gtwflxiysy.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gtxktluxma.html

date +%s;  date -d @1700000000
来源：http://dali.zhengqikj.top/Article/details/gtsqhxydjm.html

[R71] 日期格式化
来源：http://dali.hammf.cn/Article/details/gtqkxilpdf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gthmufobvt.html

[R72] 等待端口就绪
来源：http://dali.hysaishi.cn/Article/details/gtgvofqqdv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yongpay.top/Article/details/gtvjyhxgdm.html

[R73] 分割大日志
来源：http://dali.fengsongda.top/Article/details/gttqxxxxzq.html

split -l 1000 big.log part_
来源：http://dali.wangdashe.top/Article/details/gtuoxiggjv.html

[R74] 批量重命名
来源：http://dali.chenlongwang.top/Article/details/gtiewmpsat.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yangfankeji.com/Article/details/gtrlxhjcsu.html

[R75] 导出环境变量
来源：http://dali.andypj.xyz/Article/details/gtkmyaljte.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenlongwang.top/Article/details/gtrzxakcnt.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gterlubgqa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gttolyvfcx.html

[R77] 读取用户输入
来源：http://dali.ydzc1.top/Article/details/gtkflphzjm.html

read -rp "请输入: " ans
来源：http://dali.cucudq.cn/Article/details/gtegddhdwj.html

[R78] 交互式菜单
来源：http://dali.c1oappe.top/Article/details/gtqsdadjpl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhixingplan.top/Article/details/gtjueayezk.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gthaofnznn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gtcpjbiqez.html

[R80] 查看脚本执行耗时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqulodbig.html

time ./run.sh
来源：http://dali.iojbl.cn/Article/details/gtldhujtyx.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtloaylacu.html

S. C / C++ 专题
来源：http://dali.vqdsnc.cn/Article/details/gtwuefbeak.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtjuduylad.html

[S01] C：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtnbekmzxl.html

#include <stdio.h>
来源：http://dali.hfpthk.cn/Article/details/gtnknougsp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cheryme.top/Article/details/gtalyrqvfg.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtxkovemre.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gtcczloegg.html

[S03] C：读入整数
来源：http://dali.daria6918.cn/Article/details/gtrffhrmte.html

int x; scanf("%d", &x);
来源：http://dali.dashuyun.cn/Article/details/gtfkhlgist.html

[S04] C：字符串复制
来源：http://dali.vqdsnc.cn/Article/details/gtjkplneey.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtvqkxmkec.html

[S05] C：字符串长度
来源：http://dali.meibo888.top/Article/details/gtrzxvojcf.html

strlen(s)
来源：http://dali.cqqwz.cn/Article/details/gttohpruoi.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gtkxqaltnh.html

strcmp(a, b) == 0
来源：http://dali.ivvv.top/Article/details/gtimqtqgda.html

[S07] C：数组遍历求和
来源：http://dali.meibo888.top/Article/details/gtoosnrgws.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.bjfxy.top/Article/details/gtknazjbvz.html

[S08] C：动态内存分配与释放
来源：http://dali.pycfn.com/Article/details/gtuppyoiog.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.smart0.xyz/Article/details/gtfrpxrqop.html

[S09] C：结构体定义与初始化
来源：http://dali.xinyue.icu/Article/details/gtokctybey.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gtgbolqmbg.html

[S10] C：指针与解引用
来源：http://dali.fengsongda.top/Article/details/gtegumnazj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gtytaseswl.html

[S11] C：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprpbdbuf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.9152youxi.cn/Article/details/gtzutxncll.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258.top/Article/details/gtaubmjjap.html

fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtrcudidjm.html

[S12] C：写文件
来源：http://dali.guannengcc.top/Article/details/gtnpdvtxvz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtzexchhuy.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gtaieuocgk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gtrxfyyszn.html

[S14] C：枚举
来源：http://dali.shzxlz.cn/Article/details/gtapweavnx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hongshengwenyu.top/Article/details/gtgxzznswt.html

[S15] C：类型转换
来源：http://dali.chenzaomai.com/Article/details/gtwfoucvyu.html

(double) a / b
来源：http://dali.ppjwa.cn/Article/details/gtaazsbgur.html

[S16] C：位操作置位
来源：http://dali.ydzc1.top/Article/details/gtlflcycps.html

x |= (1 << 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzxtjqjx.html

[S17] C：安全拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gttewgloxw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgufenzy.top/Article/details/gtaiklnibx.html

[S18] C：命令行参数
来源：http://dali.ppjwa.cn/Article/details/gtxnkhbhef.html

int main(int argc, char **argv)
来源：http://dali.birdmap.top/Article/details/gtozmymvpa.html

[S19] C：快速排序
来源：http://dali.andypj.xyz/Article/details/gtafozdukp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtshjzbgkw.html

[S20] C：二分查找
来源：http://dali.yvedp.cn/Article/details/gtqbbuqixw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gttbjbzaoh.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gtkknxwukc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gtcqujkcdt.html

[S22] C：字符串转数字
来源：http://dali.guannengcc.top/Article/details/gtryjcrzsq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.c1oappe.top/Article/details/gtpbhycnko.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gtipwlnbug.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenlongwang.top/Article/details/gtiusuhmcr.html

[S24] C：获取本地时间
来源：http://dali.jqgfzy.top/Article/details/gtzcwwdhtf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gaohongyu789.top/Article/details/gtjkfqxtbw.html

[S25] C：内存拷贝
来源：http://dali.dianchejie.cn/Article/details/gtwmnussfy.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gtghbjgosn.html

[S26] C：内存清零
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnniptqht.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gtbvcvowqq.html

[S27] C：定义常量
来源：http://dali.cashguo.top/Article/details/gtjqrocbhb.html

const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtykfrnshw.html

[S28] C：静态变量
来源：http://dali.tian-w.cn/Article/details/gtsvwrsbbf.html

static int counter = 0;
来源：http://dali.aizwys.cn/Article/details/gtruscsqzg.html

[S29] C：变参函数
来源：http://dali.zdqjudy.top/Article/details/gtmlwmflwx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fzhhl.top/Article/details/gtkgawbmkg.html

[S30] C：头文件保护
来源：http://dali.daria6918.cn/Article/details/gtkyhnmraa.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gtscyjnfhg.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtjnggyygc.html

#endif
来源：http://dali.daxiang520.top/Article/details/gtrpvxfpod.html

[S31] C++：Hello World
来源：http://dali.cashguo.top/Article/details/gtcslaoabf.html

#include <iostream>
来源：http://dali.cqqwz.cn/Article/details/gtdudjolsi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gtnlwguppc.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gtlbwxdolr.html

std::string s = "hi";  s += "!";
来源：http://dali.sweek.top/Article/details/gtcjsqidub.html


<!-- 参考信息 -->