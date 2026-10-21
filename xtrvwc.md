代发 wailian999

[Q80] 字符串截取
来源：http://dali.yongpay.top/Article/details/gtbdyzdwgf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtgshajlhq.html

[Q81] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gtrdptmmzc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtsottsbmg.html

[Q82] 字符长度与字节长度
来源：http://dali.yueranfly.top/Article/details/gthyokfvxr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gthmvegpiv.html

[Q83] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtqeojnpuq.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfclioero.html

[Q84] 去除首尾空格
来源：http://dali.hysaishi.cn/Article/details/gtcfgwljfk.html

SELECT TRIM(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gtcvgvmpwp.html

[Q85] 数值取整
来源：http://dali.xuanzx.com/Article/details/gtgdtlrqye.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sysykeji.top/Article/details/gtogellmlh.html

[Q86] 读取 JSON 字段
来源：http://dali.c1oappe.top/Article/details/gtvzifceax.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pycfn.com/Article/details/gtmtntnqhp.html

[Q87] JSON 字段做条件
来源：http://dali.zhengqikj.top/Article/details/gtbljtedio.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmiehaqhl.html

[Q88] 行转列（条件聚合）
来源：http://dali.andypj.xyz/Article/details/gtfzmqylpz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.snrcjt.cn/Article/details/gtifnqyvnb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.hammf.cn/Article/details/gthpgyrdad.html

[Q89] 判断表是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtcidciyps.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.xuetiantiany.cn/Article/details/gtfuihooph.html

[Q90] 生成序号列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgfqrdlie.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhiwuduotai.top/Article/details/gtmreuvtwx.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtvnhunwoh.html

R. Bash 专题
来源：http://dali.snrcjt.cn/Article/details/gtapogdsfy.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwpqzobn.html

[R01] shebang 与严格模式
来源：http://dali.hnqzz.top/Article/details/gtapdzklxd.html

#!/usr/bin/env bash
来源：http://dali.xinyue.icu/Article/details/gtukhzehax.html

set -euo pipefail
来源：http://dali.andypj.xyz/Article/details/gtbulrhcze.html

[R02] 变量赋值与使用
来源：http://dali.daxiang520.top/Article/details/gtogaqicou.html

name="Tom"; echo "$name"
来源：http://dali.hysaishi.cn/Article/details/gtlnnndltx.html

[R03] 只读变量
来源：http://dali.gotoacloud.top/Article/details/gtzhruiypq.html

readonly PI=3.14
来源：http://dali.sufxvd.cn/Article/details/gtpnkhfjry.html

[R04] 位置参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskxfdfdw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zdqjudy.top/Article/details/gtamkyrlrs.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gtjvfsurjy.html

name="${1:-default}"
来源：http://dali.mhx1999.top/Article/details/gtvowljfvf.html

[R06] 判断命令是否存在
来源：http://dali.yanxiufei.cn/Article/details/gtmknraoqr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtzaulqdau.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzlpjwui.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwegcbty.html

[R08] 数值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtnorpse.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gtdlwfgrrt.html

[R09] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtqxflqjrg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yueranfly.top/Article/details/gtlqouzktv.html

[R10] 正则匹配
来源：http://dali.yangfankeji.com/Article/details/gtixafhqsu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbmxlbxv.html

[R11] case 多分支
来源：http://dali.cqqwz.cn/Article/details/gtbbkeeqwx.html

case "$1" in
来源：http://dali.yuxming.cn/Article/details/gtgpjdyhsz.html

start) echo "启动" ;;
来源：http://dali.havefunace.top/Article/details/gtptqlvgix.html

stop)  echo "停止" ;;
来源：http://dali.andypj.xyz/Article/details/gthervhrgy.html

*)     echo "未知命令" ;;
来源：http://dali.yueranfly.top/Article/details/gtdgzoqvwh.html

esac
来源：http://dali.ppjwa.cn/Article/details/gtuvptdwew.html

[R12] for 遍历文件
来源：http://dali.guowangkeji.top/Article/details/gtxusezzum.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dianchejie.cn/Article/details/gtitaldcps.html

[R13] for 计数循环
来源：http://dali.mhx1999.top/Article/details/gtbxbugcfk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtmrfjbxqa.html

[R14] C 风格 for
来源：http://dali.zhiwuduotai.top/Article/details/gtplwxrtvm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daxiang520.top/Article/details/gtxwjsutfs.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gtwvjzkvsi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hywenlv.cn/Article/details/gtbktdxfzr.html

[R16] until 等待条件
来源：http://dali.xinyue.icu/Article/details/gtsswudijk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gttgegxpol.html

[R17] 数组定义与取值
来源：http://dali.yangfankeji.com/Article/details/gtxwdxjeqq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtmmqiqdpn.html

[R18] 遍历数组
来源：http://dali.chenzaomai.com/Article/details/gtagjblcfl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hammf.cn/Article/details/gtabhnmjuh.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtomequbha.html

echo "${#arr[@]}"
来源：http://dali.dianchejie.cn/Article/details/gtkofmjuat.html

[R20] 关联数组（字典）
来源：http://dali.jinqigfzy.top/Article/details/gtrudhtupx.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.bjfxy.top/Article/details/gtnekweflb.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gtysnukoyn.html

echo "${#s}"
来源：http://dali.xuetiantiany.cn/Article/details/gtaqjknwru.html

[R22] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtyrzmwxly.html

echo "${s:0:5}"
来源：http://dali.daria6918.cn/Article/details/gtrbxjxsds.html

[R23] 字符串替换
来源：http://dali.wangdashe.top/Article/details/gtxjoyvvjq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gtfkjycfks.html

[R24] 大小写转换
来源：http://dali.daxiang520.top/Article/details/gtfvonzhbn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gtdnruetzg.html

[R25] 去后缀 / 去前缀
来源：http://dali.mhx1999.top/Article/details/gtoxooyxen.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gtarcbotxk.html

[R26] 命令替换
来源：http://dali.guowangkeji.top/Article/details/gtlolxqrec.html

now=$(date +%F); echo "$now"
来源：http://dali.dashuyun.cn/Article/details/gtniccxwfs.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gtqcpzxadw.html

echo $((1 + 2 * 3))
来源：http://dali.sweek.top/Article/details/gtrexyygcc.html

[R28] 浮点运算
来源：http://dali.ivvv.top/Article/details/gtwtscwnhy.html

echo "scale=2; 10/3" | bc
来源：http://dali.bjfxy.top/Article/details/gtflsnmlue.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gtkmikycho.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkjgiocs.html

[R30] 函数返回状态码
来源：http://dali.iojbl.cn/Article/details/gtinnotmip.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hywenlv.cn/Article/details/gtauwkhxnx.html

[R31] 局部变量
来源：http://dali.jlsjyb.cn/Article/details/gthndwmyyu.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gtlcpnkupo.html

[R32] 参数个数校验
来源：http://dali.zhiwuduotai.top/Article/details/gtgtcwnfkd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtwwsyhhca.html

[R33] 捕获错误并提示行号
来源：http://dali.gotoacloud.top/Article/details/gtcgphfpdz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnxiangtu.top/Article/details/gthdlqnwdm.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gtinuthweq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtajfogida.html

[R35] 后台执行并等待
来源：http://dali.cheryme.top/Article/details/gtkcgsfsgp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hongshengwenyu.top/Article/details/gtfrkynotn.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gtpwxslbmm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gtrqfoulsu.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gthtpnondb.html

files=$(ls -1)
来源：http://dali.daxiang520.top/Article/details/gtikvnyevf.html

[R38] 管道串联
来源：http://dali.aibaodan.cn/Article/details/gtudgtttsx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gtylepaojk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhengqikj.top/Article/details/gthxsganqe.html

cmd > out.log 2>&1
来源：http://dali.hfpthk.cn/Article/details/gtzvmvdzih.html

[R40] 追加写日志
来源：http://dali.ivvv.top/Article/details/gtobzngrfi.html

echo "log" >> out.log
来源：http://dali.c1oappe.top/Article/details/gtldzwhvgq.html

[R41] 丢弃输出
来源：http://dali.jqgufenzy.top/Article/details/gtxogaffue.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gtrdauisxl.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gtpgxzwevp.html

wc -l < a.txt
来源：http://dali.hfpthk.cn/Article/details/gtmgozgcem.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gtzvffepqd.html

find . -name "*.log" -type f
来源：http://dali.pycfn.com/Article/details/gtopukkabv.html

[R44] 按修改时间查找
来源：http://dali.0kj1m.cn/Article/details/gtquifskav.html

find . -mtime -7 -type f
来源：http://dali.hammf.cn/Article/details/gtjssgihyc.html

[R45] 批量删除
来源：http://dali.ybcxt.top/Article/details/gtihjziion.html

find . -name "*.tmp" -delete
来源：http://dali.yanxiufei.cn/Article/details/gtwghtgggd.html

[R46] 递归替换文件内容
来源：http://dali.tian-w.cn/Article/details/gtfzxrryom.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gtwlftilsh.html

[R47] sed 单行替换
来源：http://dali.zhiwuduotai.top/Article/details/gtypiotrxg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtawqgvvtf.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gtzvmooalp.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtmrdegopt.html

[R49] awk 带条件
来源：http://dali.zycfv.cn/Article/details/gtvcmmzxgg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrxttlkg.html

[R50] awk 求和
来源：http://dali.tian-w.cn/Article/details/gtmzydgufi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtfzfxgrpa.html

[R51] 排序去重取前几
来源：http://dali.9152youxi.cn/Article/details/gtiyklschn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.havefunace.top/Article/details/gtxetutscu.html

[R52] 统计行数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuufmkfns.html

wc -l a.txt
来源：http://dali.haohaochexian.top/Article/details/gtkzitqhti.html

[R53] 查看文件头与实时尾
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjokkyqtd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.quarkkingdee.top/Article/details/gtbilccctz.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gtabwivwfa.html

diff a.txt b.txt
来源：http://dali.pycfn.com/Article/details/gtytlyrufq.html

[R55] 压缩与解压
来源：http://dali.c1oappe.top/Article/details/gtolybjhzw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gzhubu.top/Article/details/gtlfgokdnp.html

[R56] 远程拷贝
来源：http://dali.wangdashe.top/Article/details/gtzupflbnx.html

scp file user@host:/path/
来源：http://dali.aizwys.cn/Article/details/gtfpoiephw.html

[R57] 远程执行命令
来源：http://dali.birdmap.top/Article/details/gtosqtzfsh.html

ssh user@host 'uptime'
来源：http://dali.nanxinkj.top/Article/details/gtnepkhhun.html

[R58] 下载文件
来源：http://dali.jianghu66.top/Article/details/gtgbnyjxgd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.svipenyu.cn/Article/details/gtguhvnhsf.html

[R59] 发 POST JSON
来源：http://dali.9152youxi.cn/Article/details/gtyzyqqsbz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gtqbxyfmvh.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtcgyzbjyv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aizwys.cn/Article/details/gtidorzqkr.html

[R61] 磁盘占用
来源：http://dali.meibo888.top/Article/details/gtubwmgmjy.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gtafsdofyw.html

[R62] 找最占空间的文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbdtzabff.html

du -ah . | sort -rh | head -10
来源：http://dali.xziqi.cn/Article/details/gtauhqycqo.html

[R63] 内存与进程
来源：http://dali.andypj.xyz/Article/details/gtaofkwqsi.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gtvdpnnnaj.html

[R64] 结束进程
来源：http://dali.c1oappe.top/Article/details/gtlmespnak.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gtbmwohpyb.html

[R65] 查看端口占用
来源：http://dali.hysaishi.cn/Article/details/gtjvzfdwca.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gtdexljdbq.html

[R66] 定时任务
来源：http://dali.gzhubu.top/Article/details/gtlbauqdig.html

crontab -e;  crontab -l
来源：http://dali.yueranfly.top/Article/details/gtnqrxvqwi.html

[R67] 生成随机十六进制串
来源：http://dali.yangfankeji.com/Article/details/gtkqlqgjba.html

openssl rand -hex 16
来源：http://dali.yvedp.cn/Article/details/gticsripnw.html

[R68] 计算文件校验值
来源：http://dali.iojbl.cn/Article/details/gtyouqpxrk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cqqwz.cn/Article/details/gtnxyfyshw.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gtfmgxgwmi.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gtapojpfpt.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gtmcpgjjcq.html

date +%s;  date -d @1700000000
来源：http://dali.jqgfzy.top/Article/details/gtjuyvuspn.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtkmfhbvuk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.birdmap.top/Article/details/gtnhrvtatq.html

[R72] 等待端口就绪
来源：http://dali.sxryk.cn/Article/details/gtrmukdbot.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gteayitwsp.html

[R73] 分割大日志
来源：http://dali.yuxming.cn/Article/details/gthbicjbth.html

split -l 1000 big.log part_
来源：http://dali.aibaodan.cn/Article/details/gttuoglrix.html

[R74] 批量重命名
来源：http://dali.bjfxy.top/Article/details/gtpszvsqxa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gtytbkywaw.html

[R75] 导出环境变量
来源：http://dali.gaohongyu789.top/Article/details/gtjevfaahy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.9152youxi.cn/Article/details/gteyrbecbl.html

[R76] 使用临时文件
来源：http://dali.bjfxy.top/Article/details/gtgbkjzsst.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gtivzmkbyw.html

[R77] 读取用户输入
来源：http://dali.xylfe.cn/Article/details/gtzsokfxzi.html

read -rp "请输入: " ans
来源：http://dali.yuanzhike.top/Article/details/gtjkjkqtbk.html

[R78] 交互式菜单
来源：http://dali.hywenlv.cn/Article/details/gtntumwhxn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yangfankeji.com/Article/details/gtvczwuqhi.html

[R79] 解析命令行选项
来源：http://dali.zycfv.cn/Article/details/gteebohcks.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnqzz.top/Article/details/gtbyenewes.html

[R80] 查看脚本执行耗时
来源：http://dali.daria6918.cn/Article/details/gtqtuyfscc.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gtncvcqtdi.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtrxwhsocm.html

S. C / C++ 专题
来源：http://dali.ppjwa.cn/Article/details/gtldzmzqiy.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtsplbeglu.html

[S01] C：Hello World
来源：http://dali.cucudq.cn/Article/details/gtiyiyzhet.html

#include <stdio.h>
来源：http://dali.xinyue.icu/Article/details/gtjerjxeuv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aizwys.cn/Article/details/gtgjnedecy.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gthrvjpdan.html

int a = 10; printf("%d\n", a);
来源：http://dali.yongpay.top/Article/details/gtonyzozrs.html

[S03] C：读入整数
来源：http://dali.smart0.xyz/Article/details/gtsyiuzzoh.html

int x; scanf("%d", &x);
来源：http://dali.hammf.cn/Article/details/gtsulzcqwa.html

[S04] C：字符串复制
来源：http://dali.zycfv.cn/Article/details/gtuxnxlhrz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.pengpengdd.cyou/Article/details/gtrjttbpuk.html

[S05] C：字符串长度
来源：http://dali.smart0.xyz/Article/details/gtaqgolwmy.html

strlen(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtpcmcwxzv.html

[S06] C：字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtupwquygh.html

strcmp(a, b) == 0
来源：http://dali.guowangkeji.top/Article/details/gtxbbuupil.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gtidxprwzx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgufenzy.top/Article/details/gtujrxsvru.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gtdbdjmbhq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.fengsongda.top/Article/details/gtlwhfjgwg.html

[S09] C：结构体定义与初始化
来源：http://dali.zhoulong.xyz/Article/details/gtexwdbkhw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cashguo.top/Article/details/gthjpqusdq.html

[S10] C：指针与解引用
来源：http://dali.xinyue.icu/Article/details/gtjibvdqsy.html

int *p = &a;  *p = 5;
来源：http://dali.gaohongyu789.top/Article/details/gtukhmbrfn.html

[S11] C：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtvjzqdskh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hongshengwenyu.top/Article/details/gtnjsuuaot.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cheryme.top/Article/details/gtjgjniopa.html

fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtrroftcgr.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gthiswlwrk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.quarkkingdee.top/Article/details/gtdkjuapoo.html

[S13] C：宏定义
来源：http://dali.gaohongyu789.top/Article/details/gtiwkivzky.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gtxqelqtyl.html

[S14] C：枚举
来源：http://dali.hywenlv.cn/Article/details/gtmtoldshc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cheryme.top/Article/details/gthvihvjlo.html

[S15] C：类型转换
来源：http://dali.havefunace.top/Article/details/gtlwwpmeco.html

(double) a / b
来源：http://dali.zhiwuduotai.top/Article/details/gtpyuaahri.html

[S16] C：位操作置位
来源：http://dali.fzhhl.top/Article/details/gtdxwbkhnf.html

x |= (1 << 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtclzbxyur.html

[S17] C：安全拼接字符串
来源：http://dali.pycfn.com/Article/details/gtecqffzfs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.meibo888.top/Article/details/gtpyrxiuxq.html

[S18] C：命令行参数
来源：http://dali.316326.xyz/Article/details/gtgognwdin.html

int main(int argc, char **argv)
来源：http://dali.chenjidiqi.icu/Article/details/gtzapzkvxt.html

[S19] C：快速排序
来源：http://dali.jqgufenzy.top/Article/details/gtrhhgplsk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtpnrjrcdq.html

[S20] C：二分查找
来源：http://dali.wangdashe.top/Article/details/gtiypzfeuq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gthmfmwvki.html

[S21] C：字符类别判断
来源：http://dali.zycfv.cn/Article/details/gtmsurbzvj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.havefunace.top/Article/details/gtwxswsuwc.html

[S22] C：字符串转数字
来源：http://dali.fengsongda.top/Article/details/gtgzoimkma.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cheryme.top/Article/details/gtjnphcpqc.html

[S23] C：随机数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvvaafue.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuqsixery.html

[S24] C：获取本地时间
来源：http://dali.xylfe.cn/Article/details/gtxqbsayur.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuxming.cn/Article/details/gtmslrhkxa.html

[S25] C：内存拷贝
来源：http://dali.snrcjt.cn/Article/details/gtvvwkisfe.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gtnjyuikbv.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gttftzqqzz.html

memset(a, 0, sizeof a);
来源：http://dali.zhixingplan.top/Article/details/gtdzavyngy.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gtqdkiksnn.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtezzdutrm.html

[S28] C：静态变量
来源：http://dali.sufxvd.cn/Article/details/gtwaoyrdqj.html

static int counter = 0;
来源：http://dali.zhoulong.xyz/Article/details/gtdadphacz.html

[S29] C：变参函数
来源：http://dali.ydzc1.top/Article/details/gtznhfogoh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gtlxpnkaav.html

[S30] C：头文件保护
来源：http://dali.tian-w.cn/Article/details/gtrdfozyyy.html

#ifndef X_H
来源：http://dali.zhongyouzk.top/Article/details/gtyvygtigq.html

#define X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtczbbssan.html

#endif
来源：http://dali.jianghu66.top/Article/details/gtecafcuvd.html

[S31] C++：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtoxniqebj.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gtmznzikpc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shangyingyoupin.top/Article/details/gthwaqmpcy.html

[S32] C++：字符串
来源：http://dali.shzxlz.cn/Article/details/gtkpxyavek.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gtdeigmgqs.html

[S33] C++：vector 增删
来源：http://dali.yonumen.top/Article/details/gtbhsczwmu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtnejgvsmf.html

[S34] C++：遍历 vector
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcddvcrpm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shuidangran.top/Article/details/gtajezexpm.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gtvlenrhvl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtburkuece.html

[S36] C++：unordered_map
来源：http://dali.tanke756.top/Article/details/gtyfrehgtj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtfrwlxlwb.html

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gtnawvoqdf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yonumen.top/Article/details/gtsfrkqmqw.html

[S38] C++：排序
来源：http://dali.kuanghao11.cn/Article/details/gtyekeijaf.html

std::sort(v.begin(), v.end());
来源：http://dali.yonumen.top/Article/details/gturxucwdp.html

[S39] C++：自定义比较器排序
来源：http://dali.dashuyun.cn/Article/details/gtrvripfav.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258888.top/Article/details/gtfwuqgrmv.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gtdoijfpgs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hywenlv.cn/Article/details/gtrawvsnsl.html

[S41] C++：类与构造函数
来源：http://dali.zhixingplan.top/Article/details/gtakszdvtg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.redwolf501.top/Article/details/gtuopamrvw.html

[S42] C++：继承与虚函数
来源：http://dali.kuanghao11.cn/Article/details/gtmngejdss.html

class B : public Base { public: void f() override {} };
来源：http://dali.zdqjudy.top/Article/details/gtuzpqxujj.html

[S43] C++：智能指针
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlleklfi.html

auto p = std::make_unique<int>(5);
来源：http://dali.dashuyun.cn/Article/details/gtcbozmipr.html

[S44] C++：引用传参
来源：http://dali.hnxiangtu.top/Article/details/gtkuludbif.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gtyodqocvo.html

[S45] C++：lambda
来源：http://dali.gogol.net.cn/Article/details/gtrgqliwng.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gtnzsojpoo.html

[S46] C++：函数模板
来源：http://dali.yvedp.cn/Article/details/gtnlkukvax.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxuanxn.top/Article/details/gtuyfwhwpg.html

[S47] C++：结构化绑定遍历
来源：http://dali.jlsjyb.cn/Article/details/gtuckosmee.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sufxvd.cn/Article/details/gtrhwldkth.html

[S48] C++：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtqspnyctp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tian-w.cn/Article/details/gtunzcliar.html

while (std::getline(in, line)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrytbkoz.html

[S49] C++：写文件
来源：http://dali.fzhhl.top/Article/details/gtajyzzkbx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.0kj1m.cn/Article/details/gtrfqbfwis.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gtktjfzosv.html


<!-- 参考信息 -->