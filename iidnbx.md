代发 wailian999

[Q80] 字符串截取
来源：http://dali.bjfxy.top/Article/details/gtuyipgmlg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtcbfojddq.html

[Q81] 字符串替换
来源：http://dali.meibo888.top/Article/details/gtlchlpaym.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtiakyanuk.html

[Q82] 字符长度与字节长度
来源：http://dali.ehwqpu.com/Article/details/gtiuleyssh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtmexoppht.html

[Q83] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtlbzndsms.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtchbtewxt.html

[Q84] 去除首尾空格
来源：http://dali.gogol.net.cn/Article/details/gtbmhalhnp.html

SELECT TRIM(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtkqxzrnbn.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gtfvhsdpyp.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hnqzz.top/Article/details/gtdnfjufgd.html

[Q86] 读取 JSON 字段
来源：http://dali.yj202588.top/Article/details/gtsmeypeox.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.316326.xyz/Article/details/gtwgegiypf.html

[Q87] JSON 字段做条件
来源：http://dali.pycfn.com/Article/details/gtqmfpvtxh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shuidangran.top/Article/details/gtahphdsms.html

[Q88] 行转列（条件聚合）
来源：http://dali.jianghu66.top/Article/details/gtwdhbsmjo.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.gogol.net.cn/Article/details/gtynityzav.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtvkqgqwwp.html

[Q89] 判断表是否存在
来源：http://dali.tanke756.top/Article/details/gtihnoermt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gzhubu.top/Article/details/gtbxlwglxe.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gtsumfayla.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.guowangkeji.top/Article/details/gtrpuuhhit.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtkayotpar.html

R. Bash 专题
来源：http://dali.ehwqpu.com/Article/details/gttpdtywrq.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvhfqyxgo.html

[R01] shebang 与严格模式
来源：http://dali.tanke756.top/Article/details/gtlsmmgkeh.html

#!/usr/bin/env bash
来源：http://dali.jinqigufen.top/Article/details/gtftqnajpc.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gtawfhzcqn.html

[R02] 变量赋值与使用
来源：http://dali.yueranfly.top/Article/details/gtvqdjmxzo.html

name="Tom"; echo "$name"
来源：http://dali.jyoumei.cn/Article/details/gtxqhenwbd.html

[R03] 只读变量
来源：http://dali.redwolf501.top/Article/details/gtaagwutij.html

readonly PI=3.14
来源：http://dali.yj202588.top/Article/details/gtpuixrrsh.html

[R04] 位置参数
来源：http://dali.tian-w.cn/Article/details/gtxxqupyxd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jiagoushi.top/Article/details/gtbbepgrlz.html

[R05] 参数默认值
来源：http://dali.sufxvd.cn/Article/details/gtfdywiewi.html

name="${1:-default}"
来源：http://dali.aizwys.cn/Article/details/gthkdodzbh.html

[R06] 判断命令是否存在
来源：http://dali.hysaishi.cn/Article/details/gtdwujbodg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtuuitdlrp.html

[R07] if 判断文件
来源：http://dali.xuetiantiany.cn/Article/details/gtqflmmoit.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtecvcuddb.html

[R08] 数值比较
来源：http://dali.yueranfly.top/Article/details/gtcijsxejz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jiagoushi.top/Article/details/gtvlzqmpro.html

[R09] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtmjdvrxid.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gthvcuatzi.html

[R10] 正则匹配
来源：http://dali.hammf.cn/Article/details/gtkudztcrb.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtnssbeuti.html

[R11] case 多分支
来源：http://dali.gogol.net.cn/Article/details/gtaxaexbmx.html

case "$1" in
来源：http://dali.snrcjt.cn/Article/details/gtfibfnlvz.html

start) echo "启动" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtmyxgjtos.html

stop)  echo "停止" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtwddlrroi.html

*)     echo "未知命令" ;;
来源：http://dali.chenjidiqi.icu/Article/details/gtdkcuvcts.html

esac
来源：http://dali.yj202588.top/Article/details/gtvqirxsec.html

[R12] for 遍历文件
来源：http://dali.0kj1m.cn/Article/details/gtydntdura.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jiagoushi.top/Article/details/gttoatqawx.html

[R13] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gtmvkrozpi.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gtoaliwggc.html

[R14] C 风格 for
来源：http://dali.jianghu66.top/Article/details/gtsmeelhdg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtvnbizoyd.html

[R15] while 逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtmeppxvqy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hysaishi.cn/Article/details/gtgqmlsezc.html

[R16] until 等待条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqrpiqav.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gtvncxhiaz.html

[R17] 数组定义与取值
来源：http://dali.feifeiyinyue.top/Article/details/gtymqjbizo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gtbqzalccj.html

[R18] 遍历数组
来源：http://dali.zhiwuduotai.top/Article/details/gtanrxtpff.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yangfankeji.com/Article/details/gtcfufihrv.html

[R19] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gttdbzvopa.html

echo "${#arr[@]}"
来源：http://dali.pycfn.com/Article/details/gtzyelrsua.html

[R20] 关联数组（字典）
来源：http://dali.smart0.xyz/Article/details/gtnffxztcz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenlongwang.top/Article/details/gtqmpkuvsl.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtodrjwweb.html

echo "${#s}"
来源：http://dali.ybcxt.top/Article/details/gtxkwyllmu.html

[R22] 截取子串
来源：http://dali.wangdashe.top/Article/details/gtyevrklrm.html

echo "${s:0:5}"
来源：http://dali.haohaochexian.top/Article/details/gtiddlprds.html

[R23] 字符串替换
来源：http://dali.zycfv.cn/Article/details/gtdcocnfpz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cashguo.top/Article/details/gtqzkkcybl.html

[R24] 大小写转换
来源：http://dali.birdmap.top/Article/details/gtrzsixsee.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tanke756.top/Article/details/gtcvlofjbl.html

[R25] 去后缀 / 去前缀
来源：http://dali.316326.xyz/Article/details/gtybpwfpwl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gtqqozgvkb.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gtwltugjby.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gtpmvtxujs.html

[R27] 算术展开
来源：http://dali.cdnleiting.top/Article/details/gtwjzhehzv.html

echo $((1 + 2 * 3))
来源：http://dali.hnqzz.top/Article/details/gtydmijnvy.html

[R28] 浮点运算
来源：http://dali.316326.xyz/Article/details/gturxkgmap.html

echo "scale=2; 10/3" | bc
来源：http://dali.mhx1999.top/Article/details/gtkspjchmh.html

[R29] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gtmpmgeehn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gtbshholgf.html

[R30] 函数返回状态码
来源：http://dali.cucudq.cn/Article/details/gtxjofxbhw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hongshengwenyu.top/Article/details/gtpivuejgu.html

[R31] 局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzhgajej.html

f() { local x=1; echo "$x"; }
来源：http://dali.aizwys.cn/Article/details/gtvintjueg.html

[R32] 参数个数校验
来源：http://dali.fengsongda.top/Article/details/gtfyjpcjrw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgufenzy.top/Article/details/gtnimkgrvz.html

[R33] 捕获错误并提示行号
来源：http://dali.aizwys.cn/Article/details/gtmjfrbrgv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.cheryme.top/Article/details/gtrtdqqaes.html

[R34] 退出时清理
来源：http://dali.sysykeji.top/Article/details/gtugcuzksr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gtgqhbydmk.html

[R35] 后台执行并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtzxybzvzm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nwbrower.top/Article/details/gtagvkoowu.html

[R36] 并发执行多个任务
来源：http://dali.zhongyouzk.top/Article/details/gttqrwuvvo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gaohongyu789.top/Article/details/gthwgmyfng.html

[R37] 把输出赋给变量
来源：http://dali.yueranfly.top/Article/details/gtzksqolkg.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gtbijmmsla.html

[R38] 管道串联
来源：http://dali.yanxiufei.cn/Article/details/gtphqcjxxf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guowangkeji.top/Article/details/gtxoosxuwe.html

[R39] 重定向标准输出与错误
来源：http://dali.hfpthk.cn/Article/details/gtazemqfvv.html

cmd > out.log 2>&1
来源：http://dali.smart0.xyz/Article/details/gtfkcnugot.html

[R40] 追加写日志
来源：http://dali.andypj.xyz/Article/details/gtxycyqupq.html

echo "log" >> out.log
来源：http://dali.dashuyun.cn/Article/details/gtzscpivcj.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkyutjleb.html

cmd >/dev/null 2>&1
来源：http://dali.hfpthk.cn/Article/details/gtiublxyaq.html

[R42] 输入重定向
来源：http://dali.dashuyun.cn/Article/details/gtwtayfdbm.html

wc -l < a.txt
来源：http://dali.gzhubu.top/Article/details/gtbrllybjv.html

[R43] 按名字查找文件
来源：http://dali.jinqigufen.top/Article/details/gtmakutnon.html

find . -name "*.log" -type f
来源：http://dali.fengsongda.top/Article/details/gtaoukjmqq.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gtsszsjhca.html

find . -mtime -7 -type f
来源：http://dali.xylfe.cn/Article/details/gtfipcpoox.html

[R45] 批量删除
来源：http://dali.zhengqikj.top/Article/details/gtjcmscvld.html

find . -name "*.tmp" -delete
来源：http://dali.quarkkingdee.top/Article/details/gtoawyqkkt.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gtmcekjxog.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.9152youxi.cn/Article/details/gtlqhnhdrc.html

[R47] sed 单行替换
来源：http://dali.ybcxt.top/Article/details/gtzfilpgtw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jianghu66.top/Article/details/gtbyzwskwq.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gtrfvnieea.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtqvdyprev.html

[R49] awk 带条件
来源：http://dali.yj20258.top/Article/details/gtxblrrfyg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gtgtraqkfx.html

[R50] awk 求和
来源：http://dali.chenzaomai.com/Article/details/gtevfqtvax.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xinyue.icu/Article/details/gtodkajcug.html

[R51] 排序去重取前几
来源：http://dali.hysaishi.cn/Article/details/gtjtauraay.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jianghu66.top/Article/details/gtiowzlxzg.html

[R52] 统计行数
来源：http://dali.yonumen.top/Article/details/gtrlhxtubg.html

wc -l a.txt
来源：http://dali.gzhubu.top/Article/details/gtnuppaqtp.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gtcwzuzkjj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangshuangyany.cn/Article/details/gtadxfnnvj.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gtbheewenc.html

diff a.txt b.txt
来源：http://dali.sxryk.cn/Article/details/gtwxhhqvju.html

[R55] 压缩与解压
来源：http://dali.pengpengdd.cyou/Article/details/gtocsoierg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gtxyvnlryj.html

[R56] 远程拷贝
来源：http://dali.cashguo.top/Article/details/gttdrsgcwk.html

scp file user@host:/path/
来源：http://dali.cucudq.cn/Article/details/gtjitxwlrw.html

[R57] 远程执行命令
来源：http://dali.shuidangran.top/Article/details/gtlhxtjahn.html

ssh user@host 'uptime'
来源：http://dali.yangfankeji.com/Article/details/gtgqnhndkk.html

[R58] 下载文件
来源：http://dali.shuidangran.top/Article/details/gtrtsicmxu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zdqjudy.top/Article/details/gtrhnmnddj.html

[R59] 发 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtbdjrmpsk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhiwuduotai.top/Article/details/gtmfbsmfmk.html

[R60] 只看 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpsragrw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gttudcfnlh.html

[R61] 磁盘占用
来源：http://dali.hfpthk.cn/Article/details/gtwikwbnfc.html

df -h;  du -sh *
来源：http://dali.yonumen.top/Article/details/gtmwdbkvbo.html

[R62] 找最占空间的文件
来源：http://dali.mhx1999.top/Article/details/gtndggokjl.html

du -ah . | sort -rh | head -10
来源：http://dali.wangdashe.top/Article/details/gthgthsizr.html

[R63] 内存与进程
来源：http://dali.yanxiufei.cn/Article/details/gtydlbvgvy.html

free -h;  ps aux | grep nginx
来源：http://dali.shzxlz.cn/Article/details/gtpbakuzda.html

[R64] 结束进程
来源：http://dali.jqgufenzy.top/Article/details/gtlrpfjimr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fzhhl.top/Article/details/gtuhfbdswp.html

[R65] 查看端口占用
来源：http://dali.daxiang520.top/Article/details/gthwuhmdqt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gthtnrggbr.html

[R66] 定时任务
来源：http://dali.guowangkeji.top/Article/details/gtfogztldu.html

crontab -e;  crontab -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpmlielw.html

[R67] 生成随机十六进制串
来源：http://dali.bjfxy.top/Article/details/gtzyptppub.html

openssl rand -hex 16
来源：http://dali.jqgufenzy.top/Article/details/gtlmwlqsdi.html

[R68] 计算文件校验值
来源：http://dali.sweek.top/Article/details/gtteyevtpo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gtgjsscyox.html

[R69] 生成随机密码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzkzxlfc.html

head -c 16 /dev/urandom | base64
来源：http://dali.cheryme.top/Article/details/gtsoeaamym.html

[R70] 时间戳与互转
来源：http://dali.c1oappe.top/Article/details/gtaayvjvbj.html

date +%s;  date -d @1700000000
来源：http://dali.jianghu66.top/Article/details/gtkivbdjij.html

[R71] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gthscuoiel.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shangyingyoupin.top/Article/details/gtqbosbjcb.html

[R72] 等待端口就绪
来源：http://dali.cashguo.top/Article/details/gttjdktupn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hnqzz.top/Article/details/gtiyofpotc.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gtegolrvbj.html

split -l 1000 big.log part_
来源：http://dali.cashguo.top/Article/details/gtgjwwkesu.html

[R74] 批量重命名
来源：http://dali.nwbrower.top/Article/details/gtmirgnsii.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fengsongda.top/Article/details/gtkmiofafe.html

[R75] 导出环境变量
来源：http://dali.shuidangran.top/Article/details/gtymbhbovu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gttjungxad.html

[R76] 使用临时文件
来源：http://dali.dianchejie.cn/Article/details/gtrwgvzglz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cdnleiting.top/Article/details/gtrfbklexj.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gtlombxdoy.html

read -rp "请输入: " ans
来源：http://dali.ppjwa.cn/Article/details/gtdtjlndax.html

[R78] 交互式菜单
来源：http://dali.jyoumei.cn/Article/details/gtqmbyfcxz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gtnrzkruwp.html

[R79] 解析命令行选项
来源：http://dali.xinyue.icu/Article/details/gtrvpnienu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcjqwpon.html

[R80] 查看脚本执行耗时
来源：http://dali.chenlongwang.top/Article/details/gtawayphyo.html

time ./run.sh
来源：http://dali.9152youxi.cn/Article/details/gtqtswpklb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtiqhmoxiw.html

S. C / C++ 专题
来源：http://dali.shuidangran.top/Article/details/gtnkchftpf.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtecfrfcpy.html

[S01] C：Hello World
来源：http://dali.pycfn.com/Article/details/gtfahrvaio.html

#include <stdio.h>
来源：http://dali.havefunace.top/Article/details/gtuurhjacd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj202588.top/Article/details/gtskgumaso.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtwrditgvq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gtkcdgvlbv.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gtrsacjxgm.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gtmzgzpokm.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gtshmqjfnj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fzhhl.top/Article/details/gtnhyeuwik.html

[S05] C：字符串长度
来源：http://dali.andypj.xyz/Article/details/gtpgfpcjrt.html

strlen(s)
来源：http://dali.zdqjudy.top/Article/details/gtwywekvah.html

[S06] C：字符串比较
来源：http://dali.hfpthk.cn/Article/details/gtdvljfxxc.html

strcmp(a, b) == 0
来源：http://dali.chenjidiqi.icu/Article/details/gtcjkpxatj.html

[S07] C：数组遍历求和
来源：http://dali.zhoulong.xyz/Article/details/gtewxfpnzt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.haohaochexian.top/Article/details/gtrgtwlvqi.html

[S08] C：动态内存分配与释放
来源：http://dali.gogol.net.cn/Article/details/gtkadtjsfc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shzxlz.cn/Article/details/gtnxamxcwd.html

[S09] C：结构体定义与初始化
来源：http://dali.bjfxy.top/Article/details/gtnrxwhrdu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuetiantiany.cn/Article/details/gtjeqdfsiw.html

[S10] C：指针与解引用
来源：http://dali.yangfankeji.com/Article/details/gtxthbcihu.html

int *p = &a;  *p = 5;
来源：http://dali.hnxiangtu.top/Article/details/gtcfsbaaaz.html

[S11] C：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtfpsuftaq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenlongwang.top/Article/details/gtcfzwrpze.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gtonpgnplc.html

fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtjkreqotx.html

[S12] C：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gtqkgtvpjt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtxrygbsxz.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtivrmvppy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.smart0.xyz/Article/details/gtquggbgli.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gtodmknpbz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhiwuduotai.top/Article/details/gtwhixmjec.html

[S15] C：类型转换
来源：http://dali.redwolf501.top/Article/details/gtlqswimrj.html

(double) a / b
来源：http://dali.zhiwuduotai.top/Article/details/gttsnqmmek.html

[S16] C：位操作置位
来源：http://dali.gogol.net.cn/Article/details/gtamstswrx.html

x |= (1 << 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuawtkltb.html

[S17] C：安全拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtezflbfcc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shuidangran.top/Article/details/gtjcfzyenv.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gtgbehanmt.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gtbtusidrb.html

[S19] C：快速排序
来源：http://dali.tian-w.cn/Article/details/gtpbemnrdq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gteqeekfzy.html

[S20] C：二分查找
来源：http://dali.havefunace.top/Article/details/gthomeqfax.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtbvzeaacp.html

[S21] C：字符类别判断
来源：http://dali.jinqigfzy.top/Article/details/gtbarqwnmq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangshuangyany.cn/Article/details/gtkcxahonu.html

[S22] C：字符串转数字
来源：http://dali.jianghu66.top/Article/details/gtuisslnij.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuanzx.com/Article/details/gthhbfhbdk.html

[S23] C：随机数
来源：http://dali.hammf.cn/Article/details/gthwmuzcgv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtskpwufjx.html

[S24] C：获取本地时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtvankgk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sysykeji.top/Article/details/gtbjbfyzkk.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gtcaqmwtjs.html

memcpy(dst, src, n);
来源：http://dali.jlsjyb.cn/Article/details/gtdcqzumie.html

[S26] C：内存清零
来源：http://dali.fengsongda.top/Article/details/gtegjwjyeu.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gtabsetesl.html

[S27] C：定义常量
来源：http://dali.ehwqpu.com/Article/details/gtwzbrihvl.html

const double PI = 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtraheinlx.html

[S28] C：静态变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarmmiuls.html

static int counter = 0;
来源：http://dali.yonumen.top/Article/details/gtvcbihqtv.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gtweupntkl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ehwqpu.com/Article/details/gtacwjfmeg.html

[S30] C：头文件保护
来源：http://dali.316326.xyz/Article/details/gtttvfaasf.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gtylifmfgy.html

#define X_H
来源：http://dali.chenzaomai.com/Article/details/gtgntslmvs.html

#endif
来源：http://dali.daria6918.cn/Article/details/gtlqfjqmkc.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtsufnjfee.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuqmubgu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guowangkeji.top/Article/details/gtbaxoiqbk.html

[S32] C++：字符串
来源：http://dali.gaohongyu789.top/Article/details/gtcnmpvcyz.html

std::string s = "hi";  s += "!";
来源：http://dali.fzhhl.top/Article/details/gtiqfvlngk.html

[S33] C++：vector 增删
来源：http://dali.svipenyu.cn/Article/details/gtoygoubob.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.svipenyu.cn/Article/details/gtawfojgbn.html

[S34] C++：遍历 vector
来源：http://dali.feifeiyinyue.top/Article/details/gtfojqxram.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmwloxqv.html

[S35] C++：map
来源：http://dali.xuetiantiany.cn/Article/details/gtcjumxmlh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtlzbddhen.html

[S36] C++：unordered_map
来源：http://dali.xuetiantiany.cn/Article/details/gtftqwlsmd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtmzkqnzsn.html

[S37] C++：set
来源：http://dali.yuxming.cn/Article/details/gtnkplfpgs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zdqjudy.top/Article/details/gtnuksuvqy.html

[S38] C++：排序
来源：http://dali.yanxiufei.cn/Article/details/gtirzhzuqd.html

std::sort(v.begin(), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtmbnwueqn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhengqikj.top/Article/details/gtqpbbmuhu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gtziuhcprb.html

[S40] C++：查找元素
来源：http://dali.nanxinkj.top/Article/details/gtqzbzewyd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xinyue.icu/Article/details/gtkzsjrvmm.html

[S41] C++：类与构造函数
来源：http://dali.gogol.net.cn/Article/details/gthpuqrvic.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cdnleiting.top/Article/details/gtdgpbwlfe.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gtbjpshddl.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuxming.cn/Article/details/gtfykqvcnm.html

[S43] C++：智能指针
来源：http://dali.havefunace.top/Article/details/gtwuyluirq.html

auto p = std::make_unique<int>(5);
来源：http://dali.yongpay.top/Article/details/gtsraxmgno.html

[S44] C++：引用传参
来源：http://dali.yongpay.top/Article/details/gtgfvnyape.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gtnooyeued.html

[S45] C++：lambda
来源：http://dali.yueranfly.top/Article/details/gtdneinjwq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shzxlz.cn/Article/details/gtfthauvmx.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gtptlglven.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gtaqmojmbe.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258888.top/Article/details/gtqfnwvmsm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.pycfn.com/Article/details/gtyfpzvfym.html

[S48] C++：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gteglbggly.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gtlaxibnod.html

while (std::getline(in, line)) { }
来源：http://dali.yvedp.cn/Article/details/gtfckkjfeq.html

[S49] C++：写文件
来源：http://dali.chenlongwang.top/Article/details/gtowaffjoc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.havefunace.top/Article/details/gtlvmbpvzk.html

[S50] C++：格式化数字
来源：http://dali.aizwys.cn/Article/details/gtomipslgf.html


<!-- 参考信息 -->