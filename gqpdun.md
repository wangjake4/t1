代发 wailian999

[Q78] 当前时间
来源：http://dali.smart0.xyz/Article/details/gtfqlqiimr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aibaodan.cn/Article/details/gtockzixrg.html

[Q79] 字符串拼接
来源：http://dali.hammf.cn/Article/details/gtmsrotxwo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaeiimkd.html

[Q80] 字符串截取
来源：http://dali.jinqigfzy.top/Article/details/gtfralekda.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtelncdvxv.html

[Q81] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gtvqytjufq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258.top/Article/details/gtorvmeyst.html

[Q82] 字符长度与字节长度
来源：http://dali.xuetiantiany.cn/Article/details/gtaebwljme.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sysykeji.top/Article/details/gtkiqvcktk.html

[Q83] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtxeuicoyk.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtnazfbdrh.html

[Q84] 去除首尾空格
来源：http://dali.shangyingyoupin.top/Article/details/gtamptkxzk.html

SELECT TRIM(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtinsxeyka.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gtkijdqxrm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nanxuanxn.top/Article/details/gtoaikjjmm.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gtngrqorgb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.sxryk.cn/Article/details/gtchhqsgoo.html

[Q87] JSON 字段做条件
来源：http://dali.fengsongda.top/Article/details/gtxxggocro.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hongshengwenyu.top/Article/details/gtsrznikts.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinqigufen.top/Article/details/gtelogyiwv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ppjwa.cn/Article/details/gtyasqpsvb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtzvijzult.html

[Q89] 判断表是否存在
来源：http://dali.jianghu66.top/Article/details/gtgurwjbss.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.c1oappe.top/Article/details/gtlhjkwzhv.html

[Q90] 生成序号列
来源：http://dali.andypj.xyz/Article/details/gtbshedysf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cheryme.top/Article/details/gtlfmpkxtx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtynijxzoy.html

R. Bash 专题
来源：http://dali.ivvv.top/Article/details/gtwpugqvgd.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtgdvflvbv.html

[R01] shebang 与严格模式
来源：http://dali.nanxinkj.top/Article/details/gtylmlqmag.html

#!/usr/bin/env bash
来源：http://dali.shangyingyoupin.top/Article/details/gtanonmgoa.html

set -euo pipefail
来源：http://dali.yanxiufei.cn/Article/details/gtbamcdodm.html

[R02] 变量赋值与使用
来源：http://dali.jinqigufen.top/Article/details/gttswgeptn.html

name="Tom"; echo "$name"
来源：http://dali.hongshengwenyu.top/Article/details/gtqxwfnafe.html

[R03] 只读变量
来源：http://dali.jqgfzy.top/Article/details/gtqigmrlre.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gtffmslruh.html

[R04] 位置参数
来源：http://dali.meibo888.top/Article/details/gtpauszkvj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.daria6918.cn/Article/details/gtuojerdal.html

[R05] 参数默认值
来源：http://dali.sxryk.cn/Article/details/gtitgbtnfs.html

name="${1:-default}"
来源：http://dali.shangyingyoupin.top/Article/details/gtttjfnfld.html

[R06] 判断命令是否存在
来源：http://dali.cucudq.cn/Article/details/gtefhqscup.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gtdgedrwcj.html

[R07] if 判断文件
来源：http://dali.jianghu66.top/Article/details/gtlziruhdi.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ivvv.top/Article/details/gtlngpwuxt.html

[R08] 数值比较
来源：http://dali.wangdashe.top/Article/details/gtwahuvcvb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.shuidangran.top/Article/details/gtxwzdkjmc.html

[R09] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtjqqdqxqu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.tanke756.top/Article/details/gtlqohvsye.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzxmnoty.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtvfpanjqg.html

[R11] case 多分支
来源：http://dali.gaohongyu789.top/Article/details/gtnuvaakox.html

case "$1" in
来源：http://dali.haohaochexian.top/Article/details/gtccecnyhe.html

start) echo "启动" ;;
来源：http://dali.yonumen.top/Article/details/gtcbchwkwm.html

stop)  echo "停止" ;;
来源：http://dali.sxryk.cn/Article/details/gtxzlrbscd.html

*)     echo "未知命令" ;;
来源：http://dali.sysykeji.top/Article/details/gtgsynernv.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gtvqcpdlrs.html

[R12] for 遍历文件
来源：http://dali.xinyue.icu/Article/details/gtuhejyhav.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cqqwz.cn/Article/details/gtwnvgmywf.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gtninyvibn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.birdmap.top/Article/details/gtvpskcqod.html

[R14] C 风格 for
来源：http://dali.aibaodan.cn/Article/details/gtyfsmnhku.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtpjtakchp.html

[R15] while 逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtrphxhvdb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.andypj.xyz/Article/details/gtjplcxgku.html

[R16] until 等待条件
来源：http://dali.daria6918.cn/Article/details/gtjwqqgkho.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhiwuduotai.top/Article/details/gtosbgbizz.html

[R17] 数组定义与取值
来源：http://dali.hammf.cn/Article/details/gtzolcwcqr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgcukyidv.html

[R18] 遍历数组
来源：http://dali.0kj1m.cn/Article/details/gtpirhdlgv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihkkyxyc.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtknwzmmaj.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gtfqdekqap.html

[R20] 关联数组（字典）
来源：http://dali.andypj.xyz/Article/details/gtxlsorzwt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqxzxkxw.html

[R21] 字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtgmnyhdpo.html

echo "${#s}"
来源：http://dali.zhongyouzk.top/Article/details/gtnwnmlcmc.html

[R22] 截取子串
来源：http://dali.bjfxy.top/Article/details/gtmddadgjw.html

echo "${s:0:5}"
来源：http://dali.yueranfly.top/Article/details/gtjfnolsfc.html

[R23] 字符串替换
来源：http://dali.zhongyouzk.top/Article/details/gtuleyanki.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xylfe.cn/Article/details/gtbaoscwlp.html

[R24] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gtlfldyngs.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.andypj.xyz/Article/details/gtbquaotdl.html

[R25] 去后缀 / 去前缀
来源：http://dali.316326.xyz/Article/details/gtznduvfpy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hammf.cn/Article/details/gteembrwmn.html

[R26] 命令替换
来源：http://dali.zdqjudy.top/Article/details/gtivxlgdfu.html

now=$(date +%F); echo "$now"
来源：http://dali.havefunace.top/Article/details/gtofnfsqzc.html

[R27] 算术展开
来源：http://dali.nwbrower.top/Article/details/gtzlcxzulz.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gtydznwnpe.html

[R28] 浮点运算
来源：http://dali.yj202588.top/Article/details/gtcjaofmds.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gtmmhlziki.html

[R29] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gtfmvsvzqz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.haohaochexian.top/Article/details/gttcpghtdr.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gtgjrpgpoc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sufxvd.cn/Article/details/gttrxljysh.html

[R31] 局部变量
来源：http://dali.snrcjt.cn/Article/details/gttchkophq.html

f() { local x=1; echo "$x"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsgiobznk.html

[R32] 参数个数校验
来源：http://dali.gogol.net.cn/Article/details/gtyyiweenp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtlvfcdxau.html

[R33] 捕获错误并提示行号
来源：http://dali.zhixingplan.top/Article/details/gtnmnmigmt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cucudq.cn/Article/details/gtpdxwhifv.html

[R34] 退出时清理
来源：http://dali.cqqwz.cn/Article/details/gtbyliksjs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.tian-w.cn/Article/details/gtkkanbamo.html

[R35] 后台执行并等待
来源：http://dali.zhengqikj.top/Article/details/gtoseqrbrs.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.tian-w.cn/Article/details/gtpekyudez.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gtwagqutbb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gtrrcldpdq.html

[R37] 把输出赋给变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxiydwkth.html

files=$(ls -1)
来源：http://dali.yj202588.top/Article/details/gtryxaadsa.html

[R38] 管道串联
来源：http://dali.vqdsnc.cn/Article/details/gtdtlplngj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gtrbanbgjb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhixingplan.top/Article/details/gtcpqnqyqa.html

cmd > out.log 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtvykcfyav.html

[R40] 追加写日志
来源：http://dali.sysykeji.top/Article/details/gtnaquvqjm.html

echo "log" >> out.log
来源：http://dali.pycfn.com/Article/details/gtaqzqahho.html

[R41] 丢弃输出
来源：http://dali.chenjidiqi.icu/Article/details/gtjaoctani.html

cmd >/dev/null 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtvigsviyo.html

[R42] 输入重定向
来源：http://dali.gogol.net.cn/Article/details/gtbegbncll.html

wc -l < a.txt
来源：http://dali.ppjwa.cn/Article/details/gtqmodlero.html

[R43] 按名字查找文件
来源：http://dali.nanxinkj.top/Article/details/gtkpoigzwt.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtbbtebsdg.html

[R44] 按修改时间查找
来源：http://dali.tian-w.cn/Article/details/gtgyfhtmpr.html

find . -mtime -7 -type f
来源：http://dali.ivvv.top/Article/details/gtdemkuodh.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gtdcocvmcg.html

find . -name "*.tmp" -delete
来源：http://dali.fzhhl.top/Article/details/gtukgymdyi.html

[R46] 递归替换文件内容
来源：http://dali.cheryme.top/Article/details/gtsnzmicrx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhiwuduotai.top/Article/details/gtbteirckr.html

[R47] sed 单行替换
来源：http://dali.vqdsnc.cn/Article/details/gtmoyffgmt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtfvpbnsku.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gtrczuekfg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtlgudbduc.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gtzqdlidck.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigfzy.top/Article/details/gtivfcxnvs.html

[R50] awk 求和
来源：http://dali.xuetiantiany.cn/Article/details/gtotufflji.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aizwys.cn/Article/details/gtugdhcwtm.html

[R51] 排序去重取前几
来源：http://dali.pengpengdd.cyou/Article/details/gtfukyzpow.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gtlcmnpgjc.html

[R52] 统计行数
来源：http://dali.yj20258888.top/Article/details/gtkbnofsqm.html

wc -l a.txt
来源：http://dali.haohaochexian.top/Article/details/gtvosxltsk.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gtdyrjzkkb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gtlqvbjfzm.html

[R54] 比较两个文件
来源：http://dali.yuanzhike.top/Article/details/gtvkdmgkhi.html

diff a.txt b.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtaasbjfaf.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gtmuxdbigk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yangfankeji.com/Article/details/gtagpwztmg.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjeddgkqw.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gtzwflolpb.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gtjzmoqpaw.html

ssh user@host 'uptime'
来源：http://dali.nanxuanxn.top/Article/details/gtkwqdfidy.html

[R58] 下载文件
来源：http://dali.tian-w.cn/Article/details/gtwgzhnvwm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shangyingyoupin.top/Article/details/gtihzcmjjh.html

[R59] 发 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtpojoysbg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xylfe.cn/Article/details/gtigdjiawm.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gtehbwazhr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnxiangtu.top/Article/details/gtczheyhue.html

[R61] 磁盘占用
来源：http://dali.cucudq.cn/Article/details/gtygnmrwtc.html

df -h;  du -sh *
来源：http://dali.ehwqpu.com/Article/details/gtvdqkharb.html

[R62] 找最占空间的文件
来源：http://dali.svipenyu.cn/Article/details/gtzyazqaau.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gtbcvunzet.html

[R63] 内存与进程
来源：http://dali.sysykeji.top/Article/details/gtzimaptur.html

free -h;  ps aux | grep nginx
来源：http://dali.cheryme.top/Article/details/gttpblsqsn.html

[R64] 结束进程
来源：http://dali.jlsjyb.cn/Article/details/gtzrjewnnn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gtvmsgljnu.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gtikneyojb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cheryme.top/Article/details/gtjfqsjsxz.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gtxlxqegqx.html

crontab -e;  crontab -l
来源：http://dali.cheryme.top/Article/details/gtyvfytctj.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gtchfaofaq.html

openssl rand -hex 16
来源：http://dali.wangshuangyany.cn/Article/details/gtubiwgnik.html

[R68] 计算文件校验值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtooqmjtwn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gttzkisdde.html

[R69] 生成随机密码
来源：http://dali.quarkkingdee.top/Article/details/gtfptvuekn.html

head -c 16 /dev/urandom | base64
来源：http://dali.shzxlz.cn/Article/details/gtlwyrtrog.html

[R70] 时间戳与互转
来源：http://dali.fengsongda.top/Article/details/gtnuhvoqsz.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gtapnqsvro.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtaarqmucy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.bjfxy.top/Article/details/gtpldgitsa.html

[R72] 等待端口就绪
来源：http://dali.jiagoushi.top/Article/details/gtvoedeiij.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gtihdthrem.html

[R73] 分割大日志
来源：http://dali.316326.xyz/Article/details/gtgbjxwrnv.html

split -l 1000 big.log part_
来源：http://dali.fzhhl.top/Article/details/gtqvqvojzh.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gtcorouuaf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gtgbizwlnq.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtvxdjiarp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gotoacloud.top/Article/details/gtjcerxxca.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gttiigffqm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgprycdxp.html

[R77] 读取用户输入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvqyumoj.html

read -rp "请输入: " ans
来源：http://dali.guannengcc.top/Article/details/gtvsexovte.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvptdraag.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.birdmap.top/Article/details/gthwfubbla.html

[R79] 解析命令行选项
来源：http://dali.pycfn.com/Article/details/gtaedgqbdr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tianlin.xyz/Article/details/gtuqkiygsd.html

[R80] 查看脚本执行耗时
来源：http://dali.9152youxi.cn/Article/details/gtiffzsocn.html

time ./run.sh
来源：http://dali.wangshuangyany.cn/Article/details/gthyuqfene.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtvczsddae.html

S. C / C++ 专题
来源：http://dali.dashuyun.cn/Article/details/gtsentavvw.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtzzpivhgb.html

[S01] C：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtltmyfjdm.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gtdtytykcb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ehwqpu.com/Article/details/gtmmhxicnt.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtadjwurct.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gtiidawbxk.html

[S03] C：读入整数
来源：http://dali.jqgfzy.top/Article/details/gtdyyfnmar.html

int x; scanf("%d", &x);
来源：http://dali.ydzc1.top/Article/details/gtupwmdflr.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gthpodzfuf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xziqi.cn/Article/details/gtpdwfnsnl.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gtpryldcjy.html

strlen(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtejhnrgzh.html

[S06] C：字符串比较
来源：http://dali.wangdashe.top/Article/details/gtacrxwdwf.html

strcmp(a, b) == 0
来源：http://dali.havefunace.top/Article/details/gtyyzdmojz.html

[S07] C：数组遍历求和
来源：http://dali.zhiwuduotai.top/Article/details/gtknjegifx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtloevxknv.html

[S08] C：动态内存分配与释放
来源：http://dali.guowangkeji.top/Article/details/gtwphxlgcq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fengsongda.top/Article/details/gtawfpvsdw.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangtech.top/Article/details/gtsopysmjv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ehwqpu.com/Article/details/gtspjgsrja.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyrryapy.html

int *p = &a;  *p = 5;
来源：http://dali.cheryme.top/Article/details/gtientyjpw.html

[S11] C：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtdptzfjmh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shuidangran.top/Article/details/gthnnaeusz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.meibo888.top/Article/details/gtudokhepv.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtbemvnkxj.html

[S12] C：写文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtysslwvej.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ehwqpu.com/Article/details/gtabeqocgb.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gtgreyxqhf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yanxiufei.cn/Article/details/gthoowvbnp.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gtclhzufqo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daxiang520.top/Article/details/gtolhmnnuw.html

[S15] C：类型转换
来源：http://dali.hysaishi.cn/Article/details/gtmtgjmyuv.html

(double) a / b
来源：http://dali.sufxvd.cn/Article/details/gtchrnxuwg.html

[S16] C：位操作置位
来源：http://dali.nanxuanxn.top/Article/details/gtulsqondp.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gtvrepjlqc.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtjhffcxoa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnqzz.top/Article/details/gtfuuneipb.html

[S18] C：命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtozmiamzc.html

int main(int argc, char **argv)
来源：http://dali.nanxinkj.top/Article/details/gtzmgpfvyg.html

[S19] C：快速排序
来源：http://dali.c1oappe.top/Article/details/gtozycpszf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtvpoisjdt.html

[S20] C：二分查找
来源：http://dali.andypj.xyz/Article/details/gtthgpdcag.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtgekyuikv.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gtuyvgeqir.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gtxlpvjzqm.html

[S22] C：字符串转数字
来源：http://dali.yongpay.top/Article/details/gtqwrxxsgk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fengsongda.top/Article/details/gtxaszcreh.html

[S23] C：随机数
来源：http://dali.gotoacloud.top/Article/details/gtwqlvxnla.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zycfv.cn/Article/details/gtbiswbdea.html

[S24] C：获取本地时间
来源：http://dali.jinqigufen.top/Article/details/gtmktdozdw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hongshengwenyu.top/Article/details/gtrmftatoz.html

[S25] C：内存拷贝
来源：http://dali.andypj.xyz/Article/details/gtntltfnot.html

memcpy(dst, src, n);
来源：http://dali.gzhubu.top/Article/details/gtxrfniczd.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gttkhbmzwx.html

memset(a, 0, sizeof a);
来源：http://dali.jlsjyb.cn/Article/details/gtshpcvadj.html

[S27] C：定义常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjndmrzce.html

const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtfdutlxsl.html

[S28] C：静态变量
来源：http://dali.snrcjt.cn/Article/details/gtiiugiswf.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gtinchmdun.html

[S29] C：变参函数
来源：http://dali.vqdsnc.cn/Article/details/gtsagkszfg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhoulong.xyz/Article/details/gtbnahmpzw.html

[S30] C：头文件保护
来源：http://dali.hongshengwenyu.top/Article/details/gtgrxurqnv.html

#ifndef X_H
来源：http://dali.gzhubu.top/Article/details/gtropizixz.html

#define X_H
来源：http://dali.svipenyu.cn/Article/details/gtcvwfhnwz.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gtlzvxgfeh.html

[S31] C++：Hello World
来源：http://dali.cashguo.top/Article/details/gtikslpqut.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gtormlmcei.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibhlnqec.html

[S32] C++：字符串
来源：http://dali.jiagoushi.top/Article/details/gtidorgxtn.html

std::string s = "hi";  s += "!";
来源：http://dali.zdqjudy.top/Article/details/gtalebczdn.html

[S33] C++：vector 增删
来源：http://dali.zhoulong.xyz/Article/details/gtuqlvqwhd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ivvv.top/Article/details/gtvluoxcfc.html

[S34] C++：遍历 vector
来源：http://dali.pycfn.com/Article/details/gtesxllxxz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gotoacloud.top/Article/details/gtubruanvp.html

[S35] C++：map
来源：http://dali.cashguo.top/Article/details/gttpbojycj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gtinaxwgoi.html

[S36] C++：unordered_map
来源：http://dali.ivvv.top/Article/details/gtldnaldtr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtgtemauxe.html

[S37] C++：set
来源：http://dali.fzhhl.top/Article/details/gtpokqiogq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.haohaochexian.top/Article/details/gtdjmxvpuf.html

[S38] C++：排序
来源：http://dali.yonumen.top/Article/details/gtvjkxuyxk.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gtdnhkgyqa.html

[S39] C++：自定义比较器排序
来源：http://dali.gotoacloud.top/Article/details/gtdqwwprwv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zdqjudy.top/Article/details/gtaulrbvgw.html

[S40] C++：查找元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsuasluay.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.quarkkingdee.top/Article/details/gtpiqxbjvj.html

[S41] C++：类与构造函数
来源：http://dali.ehwqpu.com/Article/details/gtvhyhlach.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gtkqcldjis.html

[S42] C++：继承与虚函数
来源：http://dali.hnxiangtu.top/Article/details/gtoshfubqp.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksvucbwd.html

[S43] C++：智能指针
来源：http://dali.nanxinkj.top/Article/details/gtmrzyiopp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zdqjudy.top/Article/details/gtxygmycav.html

[S44] C++：引用传参
来源：http://dali.xziqi.cn/Article/details/gtvlukeohh.html

void inc(int &x) { ++x; }
来源：http://dali.mhx1999.top/Article/details/gthepjxaoj.html

[S45] C++：lambda
来源：http://dali.yangfankeji.com/Article/details/gtlkmsmips.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yonumen.top/Article/details/gtxlccrbon.html

[S46] C++：函数模板
来源：http://dali.pengpengdd.cyou/Article/details/gtrkzytfln.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.wangdashe.top/Article/details/gtioztrmgf.html

[S47] C++：结构化绑定遍历
来源：http://dali.pycfn.com/Article/details/gtcuepswhe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gtilkjepix.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtetverbjj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgmqtsjs.html


<!-- 参考信息 -->