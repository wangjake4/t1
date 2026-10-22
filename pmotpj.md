代发 wailian999

[Q78] 当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtapgheexs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yongpay.top/Article/details/gtsdfjydhl.html

[Q79] 字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gtpibisxbo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gtvvbvdvas.html

[Q80] 字符串截取
来源：http://dali.shuidangran.top/Article/details/gtbzcyoapf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258888.top/Article/details/gthcwcagrr.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtprjmcrqa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtuoruamaa.html

[Q82] 字符长度与字节长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsrjfjtk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtjjaaxhon.html

[Q83] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gtwgyzoret.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtiwaghbxh.html

[Q84] 去除首尾空格
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkjuxtun.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtiyiaorjm.html

[Q85] 数值取整
来源：http://dali.xylfe.cn/Article/details/gtbgrzmtky.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.bjfxy.top/Article/details/gtypgpcwgn.html

[Q86] 读取 JSON 字段
来源：http://dali.yuanzhike.top/Article/details/gtfrenqmxk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xziqi.cn/Article/details/gtwtwwqkow.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gtbfuupikr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guowangkeji.top/Article/details/gtbxzqtdyc.html

[Q88] 行转列（条件聚合）
来源：http://dali.jianghu66.top/Article/details/gtnwsyiaea.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxuanxn.top/Article/details/gthjtltibj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yongpay.top/Article/details/gtphduotey.html

[Q89] 判断表是否存在
来源：http://dali.smart0.xyz/Article/details/gtttjjeygc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ppjwa.cn/Article/details/gtfkjzvgil.html

[Q90] 生成序号列
来源：http://dali.pycfn.com/Article/details/gttvvrszra.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gtahxdfsew.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gttudxdxtd.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmmydfoia.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtgefeolza.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gtwfbcxamr.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gtbdpasecy.html

set -euo pipefail
来源：http://dali.zhiwuduotai.top/Article/details/gtvjpolcoi.html

[R02] 变量赋值与使用
来源：http://dali.zhiwuduotai.top/Article/details/gtlsnvcadn.html

name="Tom"; echo "$name"
来源：http://dali.pycfn.com/Article/details/gtgwlamsbm.html

[R03] 只读变量
来源：http://dali.hammf.cn/Article/details/gtnoascsrj.html

readonly PI=3.14
来源：http://dali.nwbrower.top/Article/details/gtbjkyimpy.html

[R04] 位置参数
来源：http://dali.jqgufenzy.top/Article/details/gtgigigsev.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gtkicxmrea.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gtgwscsyoz.html

name="${1:-default}"
来源：http://dali.hfpthk.cn/Article/details/gtlgscxfvk.html

[R06] 判断命令是否存在
来源：http://dali.jinqigufen.top/Article/details/gtionkfgci.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gtodbexvny.html

[R07] if 判断文件
来源：http://dali.cheryme.top/Article/details/gtblwhaoew.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigufen.top/Article/details/gtwzclnpup.html

[R08] 数值比较
来源：http://dali.jqgfzy.top/Article/details/gttimmoatm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgfzy.top/Article/details/gtfoxwlogk.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gtwhjtstgw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuwdprnu.html

[R10] 正则匹配
来源：http://dali.pycfn.com/Article/details/gtxgfebdhx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtsneqyx.html

[R11] case 多分支
来源：http://dali.wangshuangyany.cn/Article/details/gtxjsxwbgp.html

case "$1" in
来源：http://dali.dianchejie.cn/Article/details/gtsuhumbqd.html

start) echo "启动" ;;
来源：http://dali.gogol.net.cn/Article/details/gtrzerjsqu.html

stop)  echo "停止" ;;
来源：http://dali.cucudq.cn/Article/details/gtvxechaqj.html

*)     echo "未知命令" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gtgjhryuli.html

esac
来源：http://dali.redwolf501.top/Article/details/gtmcncupoj.html

[R12] for 遍历文件
来源：http://dali.tanke756.top/Article/details/gtvffphjbo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sysykeji.top/Article/details/gthzgjquzs.html

[R13] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gtwgxaxiro.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnxiangtu.top/Article/details/gtxldtpdxm.html

[R14] C 风格 for
来源：http://dali.nwbrower.top/Article/details/gtylohzpbn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtgtgqdlai.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtjovsduuh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ydzc1.top/Article/details/gtpqlangqj.html

[R16] until 等待条件
来源：http://dali.cashguo.top/Article/details/gtxgwyicjv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gtcwddohvz.html

[R17] 数组定义与取值
来源：http://dali.fzhhl.top/Article/details/gtdmiegows.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zycfv.cn/Article/details/gtkuphjmrd.html

[R18] 遍历数组
来源：http://dali.mhx1999.top/Article/details/gtehkrdyaj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.meibo888.top/Article/details/gtkdsxupst.html

[R19] 数组长度
来源：http://dali.wangdashe.top/Article/details/gtrqktsonb.html

echo "${#arr[@]}"
来源：http://dali.yanxiufei.cn/Article/details/gtlxpgwkov.html

[R20] 关联数组（字典）
来源：http://dali.yj20258.top/Article/details/gteclqjhal.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gtalbncfos.html

[R21] 字符串长度
来源：http://dali.ybcxt.top/Article/details/gtoibkqjhw.html

echo "${#s}"
来源：http://dali.yueranfly.top/Article/details/gtnfzeqcze.html

[R22] 截取子串
来源：http://dali.zhixingplan.top/Article/details/gtuoxfrtzm.html

echo "${s:0:5}"
来源：http://dali.svipenyu.cn/Article/details/gtifcdccnz.html

[R23] 字符串替换
来源：http://dali.quarkkingdee.top/Article/details/gtwzyxjihu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.svipenyu.cn/Article/details/gtteoeujob.html

[R24] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtavhexrge.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgufenzy.top/Article/details/gtthihegkq.html

[R25] 去后缀 / 去前缀
来源：http://dali.sysykeji.top/Article/details/gtuooghika.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gzhubu.top/Article/details/gtvbwnifxq.html

[R26] 命令替换
来源：http://dali.xziqi.cn/Article/details/gtowxvfrsf.html

now=$(date +%F); echo "$now"
来源：http://dali.svipenyu.cn/Article/details/gtdedwihmi.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gtfzpljtwz.html

echo $((1 + 2 * 3))
来源：http://dali.9152youxi.cn/Article/details/gtwtcorfpo.html

[R28] 浮点运算
来源：http://dali.zhoulong.xyz/Article/details/gtogtetwlp.html

echo "scale=2; 10/3" | bc
来源：http://dali.ppjwa.cn/Article/details/gttgopvdhl.html

[R29] 定义函数
来源：http://dali.sweek.top/Article/details/gtplegnuzz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.feifeiyinyue.top/Article/details/gtbowsbswo.html

[R30] 函数返回状态码
来源：http://dali.jlsjyb.cn/Article/details/gtepzscpwt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gtgmkukedo.html

[R31] 局部变量
来源：http://dali.xziqi.cn/Article/details/gtqswqrujs.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsllkmtjn.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gtbilbuwnp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gaohongyu789.top/Article/details/gtsvvbgacz.html

[R33] 捕获错误并提示行号
来源：http://dali.0kj1m.cn/Article/details/gtfjjpayun.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxuanxn.top/Article/details/gtjxzubbhx.html

[R34] 退出时清理
来源：http://dali.pycfn.com/Article/details/gtinglcesh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtpusbvesr.html

[R35] 后台执行并等待
来源：http://dali.chenzaomai.com/Article/details/gtyzkqyjep.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.meibo888.top/Article/details/gtrrjrcyti.html

[R36] 并发执行多个任务
来源：http://dali.yj202588.top/Article/details/gtzqjnzbda.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gaohongyu789.top/Article/details/gtuprmylre.html

[R37] 把输出赋给变量
来源：http://dali.xylfe.cn/Article/details/gtvdvxmsjg.html

files=$(ls -1)
来源：http://dali.pycfn.com/Article/details/gtnciixtzl.html

[R38] 管道串联
来源：http://dali.sweek.top/Article/details/gtvpmacove.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yueranfly.top/Article/details/gtfmuxttcn.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gtridjdodf.html

cmd > out.log 2>&1
来源：http://dali.0kj1m.cn/Article/details/gtlvnrmypd.html

[R40] 追加写日志
来源：http://dali.yangfankeji.com/Article/details/gtcpqfpsdu.html

echo "log" >> out.log
来源：http://dali.tanke756.top/Article/details/gtpzhmhpvt.html

[R41] 丢弃输出
来源：http://dali.sufxvd.cn/Article/details/gtxtxrpehd.html

cmd >/dev/null 2>&1
来源：http://dali.316326.xyz/Article/details/gtzvbizzrd.html

[R42] 输入重定向
来源：http://dali.zdqjudy.top/Article/details/gtrekyqbas.html

wc -l < a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlazifgc.html

[R43] 按名字查找文件
来源：http://dali.birdmap.top/Article/details/gtcwfaullj.html

find . -name "*.log" -type f
来源：http://dali.snrcjt.cn/Article/details/gtqoebfizu.html

[R44] 按修改时间查找
来源：http://dali.yangfankeji.com/Article/details/gtdcphnfvp.html

find . -mtime -7 -type f
来源：http://dali.birdmap.top/Article/details/gtzsmtipjj.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gthinszxsy.html

find . -name "*.tmp" -delete
来源：http://dali.meibo888.top/Article/details/gtcwesdxdx.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gtaxklrmxs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.andypj.xyz/Article/details/gtrdrrjbhu.html

[R47] sed 单行替换
来源：http://dali.zdqjudy.top/Article/details/gtkmtymrrl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gtfxtagxrf.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gtggbywheu.html

awk '{print $1, $3}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtfsfvjfus.html

[R49] awk 带条件
来源：http://dali.ivvv.top/Article/details/gtryunrvmx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxuanxn.top/Article/details/gtyutbherx.html

[R50] awk 求和
来源：http://dali.shangyingyoupin.top/Article/details/gtayxamneh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtaybjubgd.html

[R51] 排序去重取前几
来源：http://dali.snrcjt.cn/Article/details/gtbylzwlzn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258888.top/Article/details/gtkkwtxcsx.html

[R52] 统计行数
来源：http://dali.xylfe.cn/Article/details/gtxcabcpgl.html

wc -l a.txt
来源：http://dali.ydzc1.top/Article/details/gtpshxjeyd.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gtfnlcqyqg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangdashe.top/Article/details/gtgurhoslg.html

[R54] 比较两个文件
来源：http://dali.jlsjyb.cn/Article/details/gtyymtjvfp.html

diff a.txt b.txt
来源：http://dali.zhengqikj.top/Article/details/gtpmwlqgng.html

[R55] 压缩与解压
来源：http://dali.daria6918.cn/Article/details/gtpmwusolh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258.top/Article/details/gtrlkvsyvn.html

[R56] 远程拷贝
来源：http://dali.tanke756.top/Article/details/gtlsxsytpb.html

scp file user@host:/path/
来源：http://dali.zhiwuduotai.top/Article/details/gtwurqtrwe.html

[R57] 远程执行命令
来源：http://dali.hysaishi.cn/Article/details/gtllinpefc.html

ssh user@host 'uptime'
来源：http://dali.zdqjudy.top/Article/details/gtblpghgpf.html

[R58] 下载文件
来源：http://dali.jianghu66.top/Article/details/gtlrbwzexf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.snrcjt.cn/Article/details/gtuhajkfqb.html

[R59] 发 POST JSON
来源：http://dali.cheryme.top/Article/details/gtciteplcu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwhbxwcp.html

[R60] 只看 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtyicpfljf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tanke756.top/Article/details/gtuaomuglq.html

[R61] 磁盘占用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpitqvzrh.html

df -h;  du -sh *
来源：http://dali.quarkkingdee.top/Article/details/gtulfasvgn.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gtxpkleolt.html

du -ah . | sort -rh | head -10
来源：http://dali.xuanzx.com/Article/details/gtsoxfohyj.html

[R63] 内存与进程
来源：http://dali.zhixingplan.top/Article/details/gthtahmsyk.html

free -h;  ps aux | grep nginx
来源：http://dali.daxiang520.top/Article/details/gtxknkmxya.html

[R64] 结束进程
来源：http://dali.yvedp.cn/Article/details/gtbhqiwafb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gzhubu.top/Article/details/gtuyunzciw.html

[R65] 查看端口占用
来源：http://dali.shuidangran.top/Article/details/gtqbptlued.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shzxlz.cn/Article/details/gtceivbiwt.html

[R66] 定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gtceskidcm.html

crontab -e;  crontab -l
来源：http://dali.gaohongyu789.top/Article/details/gtewoutcsc.html

[R67] 生成随机十六进制串
来源：http://dali.smart0.xyz/Article/details/gtnmazblng.html

openssl rand -hex 16
来源：http://dali.sweek.top/Article/details/gtpwwjxvmm.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gtroaieotf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sufxvd.cn/Article/details/gthcuhphjw.html

[R69] 生成随机密码
来源：http://dali.ppjwa.cn/Article/details/gtkfyjynoo.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtpifllyzb.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gtcgksbinn.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gtiluuijmt.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtrihuwezj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xylfe.cn/Article/details/gtdizwztca.html

[R72] 等待端口就绪
来源：http://dali.kuanghao11.cn/Article/details/gtcyxqzmeo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yanxiufei.cn/Article/details/gtpoixuwyy.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gtgfbushab.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gtepuewgof.html

[R74] 批量重命名
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkviapxw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fengsongda.top/Article/details/gtjcxaeanv.html

[R75] 导出环境变量
来源：http://dali.aibaodan.cn/Article/details/gtumlhmmkb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.kuanghao11.cn/Article/details/gtljuirffz.html

[R76] 使用临时文件
来源：http://dali.zhengqikj.top/Article/details/gtbbgnshve.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtyfneqmxl.html

[R77] 读取用户输入
来源：http://dali.zhoulong.xyz/Article/details/gtlxfqmtbq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gtvzurveje.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gtijttbxmg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhongyouzk.top/Article/details/gtrwjvppfc.html

[R79] 解析命令行选项
来源：http://dali.xuetiantiany.cn/Article/details/gtmoyljgxo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gtxzmasyxn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhengqikj.top/Article/details/gtofrygagf.html

time ./run.sh
来源：http://dali.nanxuanxn.top/Article/details/gtcnijymdx.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtlwwanslj.html

S. C / C++ 专题
来源：http://dali.cashguo.top/Article/details/gtfzuxwsqh.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfolnigg.html

[S01] C：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gterbenxuh.html

#include <stdio.h>
来源：http://dali.yongpay.top/Article/details/gtsgqoqaxa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hywenlv.cn/Article/details/gtgpupeysw.html

[S02] C：变量与格式化输出
来源：http://dali.zhiwuduotai.top/Article/details/gtupqumwgn.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinghuilouyu.cn/Article/details/gttpjzfkdn.html

[S03] C：读入整数
来源：http://dali.ppjwa.cn/Article/details/gtnnkgevxu.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gtcjljdjux.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gtvyhajeop.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daria6918.cn/Article/details/gtfapionwl.html

[S05] C：字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtqafcxwbq.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtvyqpcaji.html

[S06] C：字符串比较
来源：http://dali.xylfe.cn/Article/details/gtrkkhvjqn.html

strcmp(a, b) == 0
来源：http://dali.dashuyun.cn/Article/details/gtjyqriwpi.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gtojfkepdw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.nwbrower.top/Article/details/gtflzyqtxz.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gthhykkbcc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yueranfly.top/Article/details/gtzpwdsgtc.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gtjvfduopt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenzaomai.com/Article/details/gtcrvckhgx.html

[S10] C：指针与解引用
来源：http://dali.iojbl.cn/Article/details/gtthemanyt.html

int *p = &a;  *p = 5;
来源：http://dali.haohaochexian.top/Article/details/gtzewxzylm.html

[S11] C：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtsrfdpfje.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zdqjudy.top/Article/details/gtixvarfyy.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtipgepwsl.html

fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtyhtimpho.html

[S12] C：写文件
来源：http://dali.tian-w.cn/Article/details/gtcpthdpmo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtxoqhvzvg.html

[S13] C：宏定义
来源：http://dali.aizwys.cn/Article/details/gtxiroqgom.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.9152youxi.cn/Article/details/gtzjkuyzeb.html

[S14] C：枚举
来源：http://dali.xziqi.cn/Article/details/gtcxfpsjka.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.smart0.xyz/Article/details/gtcmihfoey.html

[S15] C：类型转换
来源：http://dali.zhoulong.xyz/Article/details/gtvwluuimn.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gtrntgzcxs.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gtfopbblza.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gtunvcjgzc.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtjmgslhzt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gtlytixwrb.html

[S18] C：命令行参数
来源：http://dali.316326.xyz/Article/details/gtixrmvhgl.html

int main(int argc, char **argv)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtydflla.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gtpveryqrd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hysaishi.cn/Article/details/gtyabsvsib.html

[S20] C：二分查找
来源：http://dali.ivvv.top/Article/details/gtbkatwunj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtlhdlrsnw.html

[S21] C：字符类别判断
来源：http://dali.snrcjt.cn/Article/details/gtqhhqjxdx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gtpdvipswg.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gtydathrxa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gtyzfqtmjk.html

[S23] C：随机数
来源：http://dali.gzhubu.top/Article/details/gtbtnckmwx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gtrvthpqex.html

[S24] C：获取本地时间
来源：http://dali.jianghu66.top/Article/details/gtloisryut.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhixingplan.top/Article/details/gtztdmhodl.html

[S25] C：内存拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtjzceiehe.html

memcpy(dst, src, n);
来源：http://dali.guannengcc.top/Article/details/gtpqrxmfoj.html

[S26] C：内存清零
来源：http://dali.cheryme.top/Article/details/gtblwmyjhx.html

memset(a, 0, sizeof a);
来源：http://dali.0kj1m.cn/Article/details/gtcbfmegkq.html

[S27] C：定义常量
来源：http://dali.zhongyouzk.top/Article/details/gtdhmuvlog.html

const double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtlbvaexut.html

[S28] C：静态变量
来源：http://dali.jiagoushi.top/Article/details/gtaextxutb.html

static int counter = 0;
来源：http://dali.dianchejie.cn/Article/details/gthziukyzf.html

[S29] C：变参函数
来源：http://dali.yuxming.cn/Article/details/gtjvdtrsvn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnxiangtu.top/Article/details/gtarvxzrzi.html

[S30] C：头文件保护
来源：http://dali.jqgufenzy.top/Article/details/gtqhmqxods.html

#ifndef X_H
来源：http://dali.ivvv.top/Article/details/gtelovrxds.html

#define X_H
来源：http://dali.gogol.net.cn/Article/details/gtjkjexgii.html

#endif
来源：http://dali.cucudq.cn/Article/details/gtqnrretlb.html

[S31] C++：Hello World
来源：http://dali.iojbl.cn/Article/details/gtlrerxfvj.html

#include <iostream>
来源：http://dali.tian-w.cn/Article/details/gtclplfvmn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gtctzgzsvw.html

[S32] C++：字符串
来源：http://dali.ydzc1.top/Article/details/gtlzmlkvwv.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gtpuhrlrpk.html

[S33] C++：vector 增删
来源：http://dali.zhongyouzk.top/Article/details/gtjkobowgb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gtxjznxzcc.html

[S34] C++：遍历 vector
来源：http://dali.sweek.top/Article/details/gtiylbbazz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gtibjkctzq.html

[S35] C++：map
来源：http://dali.hnqzz.top/Article/details/gtkurksokg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtqmvwlyfk.html

[S36] C++：unordered_map
来源：http://dali.yuanzhike.top/Article/details/gtdihobbah.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtlcktzivx.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gtiekocycz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gtcnvvfboc.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gtylgnspef.html

std::sort(v.begin(), v.end());
来源：http://dali.aizwys.cn/Article/details/gtudaqwsgg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhiwuduotai.top/Article/details/gtsfkvlgya.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.vqdsnc.cn/Article/details/gtbmsowjmh.html

[S40] C++：查找元素
来源：http://dali.andypj.xyz/Article/details/gtmpkgnemi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtarfjtphl.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtppwcpaar.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.meibo888.top/Article/details/gteydadtyl.html

[S42] C++：继承与虚函数
来源：http://dali.hywenlv.cn/Article/details/gteopvynfd.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gtswygflsb.html

[S43] C++：智能指针
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbgurcgon.html

auto p = std::make_unique<int>(5);
来源：http://dali.jyoumei.cn/Article/details/gtuvxsucvy.html

[S44] C++：引用传参
来源：http://dali.hywenlv.cn/Article/details/gtiicypqbs.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gtfvdosvtd.html

[S45] C++：lambda
来源：http://dali.jinqigufen.top/Article/details/gtpbshsyzz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gogol.net.cn/Article/details/gtwcayjnmq.html

[S46] C++：函数模板
来源：http://dali.mhx1999.top/Article/details/gtucupvqyq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gtyuqhaqpg.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gtwbqughtu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.kuanghao11.cn/Article/details/gtfctpjhdi.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtcxormhrb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gaohongyu789.top/Article/details/gtzeitbttz.html


<!-- 参考信息 -->