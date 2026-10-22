代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtatvghchg.html

[Q73] 查看表状态
来源：http://dali.andypj.xyz/Article/details/gtiqrsszyk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.dianchejie.cn/Article/details/gtoltlesen.html

[Q74] 强制使用索引
来源：http://dali.sysykeji.top/Article/details/gtabaacpqj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.snrcjt.cn/Article/details/gtikxlhfuj.html

[Q75] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtgjgxlstw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sweek.top/Article/details/gtghghhnud.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yuxming.cn/Article/details/gtqdddsobn.html

[Q76] 按天统计
来源：http://dali.xinyue.icu/Article/details/gtzkxnmcon.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangshuangyany.cn/Article/details/gtsnkkiaht.html

[Q77] 时间加减
来源：http://dali.gogol.net.cn/Article/details/gtgmkkcptt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.hnqzz.top/Article/details/gtatdeidsh.html

[Q78] 当前时间
来源：http://dali.shuidangran.top/Article/details/gtcfminccx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.fzhhl.top/Article/details/gtlzxkmavj.html

[Q79] 字符串拼接
来源：http://dali.sysykeji.top/Article/details/gtnporbcwf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jiagoushi.top/Article/details/gtigchbiaw.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gtgxjjojgt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtgzrlrnka.html

[Q81] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gtedckleee.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtfebhexgh.html

[Q82] 字符长度与字节长度
来源：http://dali.jyoumei.cn/Article/details/gtpawljcsm.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtmlcbunwb.html

[Q83] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtfuwjvnsf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtnaolxcgr.html

[Q84] 去除首尾空格
来源：http://dali.shuidangran.top/Article/details/gtqeprbfsi.html

SELECT TRIM(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhrlbunq.html

[Q85] 数值取整
来源：http://dali.guowangkeji.top/Article/details/gtsryfqaxp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.pengpengdd.cyou/Article/details/gtgoctvikc.html

[Q86] 读取 JSON 字段
来源：http://dali.hfpthk.cn/Article/details/gtnblwjxjc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cdnleiting.top/Article/details/gtnsqsiczq.html

[Q87] JSON 字段做条件
来源：http://dali.chenjidiqi.icu/Article/details/gtytmqcvyc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjyczhojh.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj202588.top/Article/details/gtxvwvhlfc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gotoacloud.top/Article/details/gtqbvavagh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtlklroldc.html

[Q89] 判断表是否存在
来源：http://dali.meibo888.top/Article/details/gtosavevsf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gttqiazvin.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gtesflmmvp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daxiang520.top/Article/details/gthkaadmds.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtlwnhbyzj.html

R. Bash 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtoqnsdnin.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtcuhwdbqw.html

[R01] shebang 与严格模式
来源：http://dali.ydzc1.top/Article/details/gtjinsytlz.html

#!/usr/bin/env bash
来源：http://dali.jianghu66.top/Article/details/gtrtifrlav.html

set -euo pipefail
来源：http://dali.yj20258.top/Article/details/gticiidwyc.html

[R02] 变量赋值与使用
来源：http://dali.zhixingplan.top/Article/details/gtqyjykmoo.html

name="Tom"; echo "$name"
来源：http://dali.wangshuangyany.cn/Article/details/gtzbfkablf.html

[R03] 只读变量
来源：http://dali.sweek.top/Article/details/gtrayewrjr.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gtpqrmlfka.html

[R04] 位置参数
来源：http://dali.yj202588.top/Article/details/gtuhghmdtg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj202588.top/Article/details/gtkmcutlst.html

[R05] 参数默认值
来源：http://dali.sxryk.cn/Article/details/gtqknxvdyc.html

name="${1:-default}"
来源：http://dali.smart0.xyz/Article/details/gtvbwyncoo.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtpmuiwhwk.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtnhxbmmrk.html

[R07] if 判断文件
来源：http://dali.yangfankeji.com/Article/details/gtbmmzfwux.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.bjfxy.top/Article/details/gtqtvdnzsx.html

[R08] 数值比较
来源：http://dali.shzxlz.cn/Article/details/gtyzxrnxkz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ybcxt.top/Article/details/gtldmypijr.html

[R09] 字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtztuljjjk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbutxiwqo.html

[R10] 正则匹配
来源：http://dali.birdmap.top/Article/details/gtexesvqwc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hfpthk.cn/Article/details/gtynrszoaw.html

[R11] case 多分支
来源：http://dali.yj202588.top/Article/details/gtunwpdpwy.html

case "$1" in
来源：http://dali.zdqjudy.top/Article/details/gtcbodahqt.html

start) echo "启动" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gterfngeia.html

stop)  echo "停止" ;;
来源：http://dali.cashguo.top/Article/details/gttmdriwzt.html

*)     echo "未知命令" ;;
来源：http://dali.yueranfly.top/Article/details/gtuvuzmazd.html

esac
来源：http://dali.cucudq.cn/Article/details/gtnsqsoesw.html

[R12] for 遍历文件
来源：http://dali.ybcxt.top/Article/details/gtmaahltkt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.snrcjt.cn/Article/details/gtcariidfy.html

[R13] for 计数循环
来源：http://dali.wangshuangyany.cn/Article/details/gtaexvxodh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gtzkpnlfcb.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gtphgcwzpl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtrzqklari.html

[R15] while 逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtrvjlkcwy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgufenzy.top/Article/details/gtkvvjoiyp.html

[R16] until 等待条件
来源：http://dali.quarkkingdee.top/Article/details/gtwokjuvxe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gticzlemuc.html

[R17] 数组定义与取值
来源：http://dali.shzxlz.cn/Article/details/gtcuedtjjf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxuanxn.top/Article/details/gtfyuzxccl.html

[R18] 遍历数组
来源：http://dali.meibo888.top/Article/details/gtctjlezfm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hammf.cn/Article/details/gtysbbjdan.html

[R19] 数组长度
来源：http://dali.smart0.xyz/Article/details/gtneydmsxo.html

echo "${#arr[@]}"
来源：http://dali.kuanghao11.cn/Article/details/gtbarjcxrg.html

[R20] 关联数组（字典）
来源：http://dali.xylfe.cn/Article/details/gttenbwnlx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sysykeji.top/Article/details/gtihyrldae.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gtyawdrtue.html

echo "${#s}"
来源：http://dali.xinyue.icu/Article/details/gtwxjukego.html

[R22] 截取子串
来源：http://dali.cucudq.cn/Article/details/gtncspcliz.html

echo "${s:0:5}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoojlbuuc.html

[R23] 字符串替换
来源：http://dali.sweek.top/Article/details/gtfeqiyubb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.daxiang520.top/Article/details/gthezwcjlz.html

[R24] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtzicrqsog.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.316326.xyz/Article/details/gtvivovzbz.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gtqlulbtji.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hysaishi.cn/Article/details/gtuzqqzbzv.html

[R26] 命令替换
来源：http://dali.vqdsnc.cn/Article/details/gtnkwfryis.html

now=$(date +%F); echo "$now"
来源：http://dali.zhiwuduotai.top/Article/details/gtznohqehm.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gtllqbsiqc.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gtwerrvmlh.html

[R28] 浮点运算
来源：http://dali.jianghu66.top/Article/details/gtwcyrrvty.html

echo "scale=2; 10/3" | bc
来源：http://dali.cashguo.top/Article/details/gtfagcyppn.html

[R29] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gtsheeuqmd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuxming.cn/Article/details/gtcmhcrmoc.html

[R30] 函数返回状态码
来源：http://dali.hysaishi.cn/Article/details/gtgrbodbdw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gtkukpojij.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gthnjmsljy.html

f() { local x=1; echo "$x"; }
来源：http://dali.gotoacloud.top/Article/details/gtmpsoaloo.html

[R32] 参数个数校验
来源：http://dali.yongpay.top/Article/details/gtjraslicf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.cdnleiting.top/Article/details/gthexokuvl.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gtjtpdecok.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hysaishi.cn/Article/details/gtbhjwyasi.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gttvfgjwss.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkolfhuts.html

[R35] 后台执行并等待
来源：http://dali.yuanzhike.top/Article/details/gtnjqvrhat.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jianghu66.top/Article/details/gtilrhinuk.html

[R36] 并发执行多个任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuchakphk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fzhhl.top/Article/details/gtqnwfyhsc.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gtdceqodcj.html

files=$(ls -1)
来源：http://dali.daria6918.cn/Article/details/gtcpzcrjqj.html

[R38] 管道串联
来源：http://dali.xziqi.cn/Article/details/gtkynkaisn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangtech.top/Article/details/gtfsxevvbn.html

[R39] 重定向标准输出与错误
来源：http://dali.aibaodan.cn/Article/details/gttkvhaawj.html

cmd > out.log 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtofqxfaef.html

[R40] 追加写日志
来源：http://dali.vqdsnc.cn/Article/details/gtappavofb.html

echo "log" >> out.log
来源：http://dali.gotoacloud.top/Article/details/gtuntyuysj.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtdgwzzypa.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbphgoqiz.html

[R42] 输入重定向
来源：http://dali.hnxiangtu.top/Article/details/gtslyfyald.html

wc -l < a.txt
来源：http://dali.cheryme.top/Article/details/gtmqsvnuiq.html

[R43] 按名字查找文件
来源：http://dali.jlsjyb.cn/Article/details/gtltthdbbv.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtqqcpsoyx.html

[R44] 按修改时间查找
来源：http://dali.pycfn.com/Article/details/gtgmycgehm.html

find . -mtime -7 -type f
来源：http://dali.fengsongda.top/Article/details/gtlnqkeofh.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gtaipldzvv.html

find . -name "*.tmp" -delete
来源：http://dali.daria6918.cn/Article/details/gtoijylmmr.html

[R46] 递归替换文件内容
来源：http://dali.ydzc1.top/Article/details/gtbwbxcwiy.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenzaomai.com/Article/details/gtghwlyzrt.html

[R47] sed 单行替换
来源：http://dali.hfpthk.cn/Article/details/gtzvgwkhwf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtlldvcopa.html

[R48] awk 取指定列
来源：http://dali.zdqjudy.top/Article/details/gtghkgzuwg.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtjnteznlj.html

[R49] awk 带条件
来源：http://dali.cqqwz.cn/Article/details/gttwhxicox.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dianchejie.cn/Article/details/gtqfkqztcf.html

[R50] awk 求和
来源：http://dali.sysykeji.top/Article/details/gtblmwtzve.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtmgbvufof.html

[R51] 排序去重取前几
来源：http://dali.guannengcc.top/Article/details/gtbwymlsqu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dianchejie.cn/Article/details/gtgwngdvdi.html

[R52] 统计行数
来源：http://dali.yangfankeji.com/Article/details/gtaycuubkp.html

wc -l a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtfpoddkaz.html

[R53] 查看文件头与实时尾
来源：http://dali.aibaodan.cn/Article/details/gtrwiaveco.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yueranfly.top/Article/details/gtavjogbja.html

[R54] 比较两个文件
来源：http://dali.316326.xyz/Article/details/gtmqjdnuor.html

diff a.txt b.txt
来源：http://dali.jinqigufen.top/Article/details/gtmobpszij.html

[R55] 压缩与解压
来源：http://dali.pycfn.com/Article/details/gtjvanvovj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangtech.top/Article/details/gthuugtsus.html

[R56] 远程拷贝
来源：http://dali.yj202588.top/Article/details/gtavqvgweq.html

scp file user@host:/path/
来源：http://dali.yvedp.cn/Article/details/gtbktmtnac.html

[R57] 远程执行命令
来源：http://dali.zhoulong.xyz/Article/details/gtkctpbhgo.html

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gtulifvabo.html

[R58] 下载文件
来源：http://dali.kuanghao11.cn/Article/details/gtclxhgjqt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jinqigufen.top/Article/details/gtxxgzdfqf.html

[R59] 发 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtddnkbpnk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yvedp.cn/Article/details/gtytinhznz.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtxskmrvzw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuanzx.com/Article/details/gtdgzekhje.html

[R61] 磁盘占用
来源：http://dali.jyoumei.cn/Article/details/gtsljsatla.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gtxpeveqnk.html

[R62] 找最占空间的文件
来源：http://dali.dashuyun.cn/Article/details/gtndqcfpco.html

du -ah . | sort -rh | head -10
来源：http://dali.chenjidiqi.icu/Article/details/gtlnqmcgne.html

[R63] 内存与进程
来源：http://dali.fzhhl.top/Article/details/gtkclijlee.html

free -h;  ps aux | grep nginx
来源：http://dali.mhx1999.top/Article/details/gtqnlycfjv.html

[R64] 结束进程
来源：http://dali.dianchejie.cn/Article/details/gtxjxtygcd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gtvuppukdf.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gtvcnpglpy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrbqrzfm.html

[R66] 定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafsrzlte.html

crontab -e;  crontab -l
来源：http://dali.hnqzz.top/Article/details/gtxmwmretc.html

[R67] 生成随机十六进制串
来源：http://dali.nwbrower.top/Article/details/gtyrqcrqmp.html

openssl rand -hex 16
来源：http://dali.sweek.top/Article/details/gtredrlccw.html

[R68] 计算文件校验值
来源：http://dali.jqgfzy.top/Article/details/gteehcbzbh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.iojbl.cn/Article/details/gtadwzswld.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gthvjuqyda.html

head -c 16 /dev/urandom | base64
来源：http://dali.nanxinkj.top/Article/details/gtbijlmrnr.html

[R70] 时间戳与互转
来源：http://dali.xuanzx.com/Article/details/gtlbhnqtwd.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258.top/Article/details/gtlwdxsbyf.html

[R71] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gtrhqqqtqo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangshuangyany.cn/Article/details/gtffmltfxp.html

[R72] 等待端口就绪
来源：http://dali.zhiwuduotai.top/Article/details/gtwfitoedx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdxgxjxy.html

[R73] 分割大日志
来源：http://dali.jinqigfzy.top/Article/details/gthgpslfmy.html

split -l 1000 big.log part_
来源：http://dali.yanxiufei.cn/Article/details/gtmgmbjrni.html

[R74] 批量重命名
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdioursi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yonumen.top/Article/details/gtdhzebgly.html

[R75] 导出环境变量
来源：http://dali.nanxuanxn.top/Article/details/gtzwekosaz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fzhhl.top/Article/details/gtqjfeapdl.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gthxgejwoi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtoeiieixs.html

[R77] 读取用户输入
来源：http://dali.daria6918.cn/Article/details/gtltljmuun.html

read -rp "请输入: " ans
来源：http://dali.hysaishi.cn/Article/details/gtuoycmtan.html

[R78] 交互式菜单
来源：http://dali.jiagoushi.top/Article/details/gtpistkhtb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shuidangran.top/Article/details/gtlysnshal.html

[R79] 解析命令行选项
来源：http://dali.sysykeji.top/Article/details/gtexodgbne.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hywenlv.cn/Article/details/gtnkgfygfv.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gtmfizoguw.html

time ./run.sh
来源：http://dali.xuetiantiany.cn/Article/details/gtalgoatdd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtgxcjxryz.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gtoqygdasi.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtczcaydxq.html

[S01] C：Hello World
来源：http://dali.smart0.xyz/Article/details/gtpphkyoux.html

#include <stdio.h>
来源：http://dali.yj202588.top/Article/details/gtmkklwfet.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gtnqtorcsz.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gtgtrdewpg.html

int a = 10; printf("%d\n", a);
来源：http://dali.hysaishi.cn/Article/details/gtwagzirzr.html

[S03] C：读入整数
来源：http://dali.yanxiufei.cn/Article/details/gtbaljxfqv.html

int x; scanf("%d", &x);
来源：http://dali.guowangkeji.top/Article/details/gtasbskilo.html

[S04] C：字符串复制
来源：http://dali.hnqzz.top/Article/details/gtykpzutbw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tian-w.cn/Article/details/gtxjqvdjez.html

[S05] C：字符串长度
来源：http://dali.sysykeji.top/Article/details/gtnhurulwd.html

strlen(s)
来源：http://dali.cqqwz.cn/Article/details/gtrtpdzcri.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtqpfsrrtf.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gtprwoonty.html

[S07] C：数组遍历求和
来源：http://dali.hnqzz.top/Article/details/gtxyidbrkk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnqzz.top/Article/details/gtmjyodzua.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gtjfmjyxer.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yanxiufei.cn/Article/details/gtiqbipfhm.html

[S09] C：结构体定义与初始化
来源：http://dali.sufxvd.cn/Article/details/gtivsrgyiq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxinkj.top/Article/details/gtjbjxvrlo.html

[S10] C：指针与解引用
来源：http://dali.jinqigfzy.top/Article/details/gtoazkgkfg.html

int *p = &a;  *p = 5;
来源：http://dali.zhiwuduotai.top/Article/details/gtszdsyiea.html

[S11] C：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtlmkpqdgc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuetiantiany.cn/Article/details/gteuiaraja.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zdqjudy.top/Article/details/gtaicriplq.html

fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtvcqdsfia.html

[S12] C：写文件
来源：http://dali.yj20258888.top/Article/details/gtaomovusl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gthyfrmvzg.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gtfsbklwdt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xinyue.icu/Article/details/gtblwwqojv.html

[S14] C：枚举
来源：http://dali.yanxiufei.cn/Article/details/gtwwxukhfh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gtxrewkuvd.html

[S15] C：类型转换
来源：http://dali.nanxuanxn.top/Article/details/gttepchzkp.html

(double) a / b
来源：http://dali.sysykeji.top/Article/details/gtodhlwpfs.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangtech.top/Article/details/gteeqbxobt.html

x |= (1 << 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnurfswmm.html

[S17] C：安全拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtxyessasz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gotoacloud.top/Article/details/gtiqryerya.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gtusudikpl.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gtldokzngf.html

[S19] C：快速排序
来源：http://dali.zycfv.cn/Article/details/gtwymdgvfg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gteeozskpy.html

[S20] C：二分查找
来源：http://dali.ydzc1.top/Article/details/gtargylfhd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtoaariciy.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gtpdryoxhe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zycfv.cn/Article/details/gtnqgbpykh.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtzmysfruo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gtfrvgkuec.html

[S23] C：随机数
来源：http://dali.havefunace.top/Article/details/gtipeielui.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gzhubu.top/Article/details/gtgsfuiqhv.html

[S24] C：获取本地时间
来源：http://dali.ehwqpu.com/Article/details/gtihdocpyy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gtqvfevtrl.html

[S25] C：内存拷贝
来源：http://dali.xziqi.cn/Article/details/gtanewmmur.html

memcpy(dst, src, n);
来源：http://dali.wangshuangyany.cn/Article/details/gtctmytsqa.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtisynauaj.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtzlcnnxth.html

[S27] C：定义常量
来源：http://dali.cqqwz.cn/Article/details/gtmwwmgpgs.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwtsxdja.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gtqmjgrjfy.html

static int counter = 0;
来源：http://dali.iojbl.cn/Article/details/gtdbxykxpc.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gtgcgkpbzi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daxiang520.top/Article/details/gtclrybgnq.html

[S30] C：头文件保护
来源：http://dali.ydzc1.top/Article/details/gthgvkkefo.html

#ifndef X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmefaotm.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gtfaiamrlb.html

#endif
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwubfxytr.html

[S31] C++：Hello World
来源：http://dali.cqqwz.cn/Article/details/gthggqndjg.html

#include <iostream>
来源：http://dali.yuanzhike.top/Article/details/gtikpvqalc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sweek.top/Article/details/gtezvnnwcg.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gteuyvyrgk.html

std::string s = "hi";  s += "!";
来源：http://dali.sweek.top/Article/details/gtzpzmonqf.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gtfjmbwlab.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shuidangran.top/Article/details/gtvfcqmahq.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gtpwypoimo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhengqikj.top/Article/details/gtighfyfzd.html

[S35] C++：map
来源：http://dali.jiagoushi.top/Article/details/gtcatfybps.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtpjsuwbvu.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gtkhmssjje.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjeufmhld.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqdgxdpv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.mhx1999.top/Article/details/gtpgtntipz.html

[S38] C++：排序
来源：http://dali.316326.xyz/Article/details/gtvnvkfeqk.html

std::sort(v.begin(), v.end());
来源：http://dali.0kj1m.cn/Article/details/gtrgzyxldy.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gtqxhvdijj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jlsjyb.cn/Article/details/gtninnxzve.html

[S40] C++：查找元素
来源：http://dali.jinqigfzy.top/Article/details/gtqtzocyzp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tanke756.top/Article/details/gtmkznasff.html

[S41] C++：类与构造函数
来源：http://dali.yj20258.top/Article/details/gtdqozyoef.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspglvmxk.html

[S42] C++：继承与虚函数
来源：http://dali.9152youxi.cn/Article/details/gtgupfnwbj.html

class B : public Base { public: void f() override {} };
来源：http://dali.cdnleiting.top/Article/details/gtupseheig.html


<!-- 参考信息 -->